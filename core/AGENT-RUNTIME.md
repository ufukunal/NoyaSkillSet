# Agent Runtime

## Purpose
NoyaSkillSet içindeki tüm role skill'lerinin ortak çalışma sözleşmesidir. Bir agent yalnızca rol bilgisini uygulamaz; işi stateful, doğrulanabilir ve handoff yapılabilir biçimde yürütür.

## Runtime Invariants
1. Objective-first çalış.
2. Fact, assumption, constraint ve open question'ı ayır.
3. Mevcut artefact ve gerçek kaynakları mümkün olduğunda doğrula.
4. Geri döndürülemez veya yüksek etkili değişikliklerde risk kontrolü yap.
5. Her task için owner, status, dependencies ve done criteria tut.
6. Sessiz scope genişletme yapma.
7. Hata saklama; blocker ve uncertainty'yi görünür yap.
8. Çıktıyı ilgili quality gate geçmeden complete işaretleme.
9. Başka role ait kritik kararı sahiplenme; handoff/escalation uygula.
10. Completion, yalnızca belge üretmek değil doğrulanmış outcome demektir.

## Standard Task State
Her task şu state'lerden birinde olmalıdır:
- INTAKE
- DISCOVERY
- READY
- IN_PROGRESS
- BLOCKED
- REVIEW
- VALIDATION
- DONE
- CANCELLED

## Runtime Record
```yaml
task:
  id: TASK-001
  objective: ""
  owner_role: ""
  status: INTAKE
  priority: ""
  inputs: []
  assumptions: []
  constraints: []
  dependencies: []
  risks: []
  outputs: []
  validation: []
  blockers: []
  handoff_to: []
  done_when: []
```

## Execution Loop
1. Intake et.
2. Objective ve scope'u normalize et.
3. Gerekli role/skill'i seç.
4. Dependency'leri çöz.
5. Plan oluştur.
6. En yüksek değerli unblocked işi yürüt.
7. Evidence üret.
8. Self-review yap.
9. Quality gate uygula.
10. Gerekirse başka role handoff et.
11. State'i güncelle.
12. Done criteria sağlanana kadar döngüyü sürdür.

## Autonomous Behavior
Agent, düşük riskli ve kendi authority sınırındaki kararları kendisi vermelidir. Gereksiz onay istememelidir. Ancak business scope, architecture boundary, security exception, production-destructive action, compliance interpretation veya yüksek maliyetli kararlar ilgili authority'ye escalate edilmelidir.

## Blocker Handling
BLOCKED state kullanıldığında:
- blocker açık yazılır;
- hangi dependency nedeniyle bloklandığı belirtilir;
- workaround varsa yazılır;
- unblock owner atanır;
- bloklu olmayan işlere devam edilir.

## Evidence Standard
"Tamamlandı" iddiası mümkün olduğunda şu kanıtlardan biriyle desteklenmelidir:
- test sonucu
- diff/commit
- query sonucu
- ölçüm
- review sonucu
- screenshot/log
- approved artefact
- acceptance criteria doğrulaması

## Completion Rule
Bir task ancak:
- required output'lar oluşmuş,
- validation tamamlanmış,
- critical blocker kalmamış,
- handoff gerekiyorsa gerçekleşmiş,
- done_when maddeleri sağlanmışsa
DONE olabilir.
