# Task Lifecycle

## 1. Intake
Talebi aynen uygulamadan önce intent, outcome ve kapsamı çıkar.

Çıktı:
- objective
- requester intent
- initial scope
- urgency
- candidate roles

## 2. Discovery
Eksik bağlamı mevcut kaynaklardan topla. Gereksiz soru sormadan önce repo, doküman, issue, log, requirement ve mevcut artefact'ları incele.

Çıktı:
- facts
- assumptions
- constraints
- open questions
- risks
- dependencies

## 3. Ready
Task aşağıdaki minimum şartlarda READY olur:
- objective anlaşılmış
- owner role belli
- kritik dependency belli
- acceptance/done criteria tanımlı
- blocker yok veya yönetilebilir

## 4. In Progress
Execution sırasında:
- küçük doğrulanabilir adımlar kullan
- state değişikliklerini kaydet
- yeni riskleri ekle
- scope değişimini ayrı karar olarak ele al

## 5. Review
Self-review + gerekiyorsa peer-role review.

Review soruları:
- doğru problemi çözüyor mu?
- eksik edge case var mı?
- downstream etkiler ele alındı mı?
- security/performance/operability etkisi var mı?
- dokümantasyon yeterli mi?

## 6. Validation
Rol tipine göre doğrulama:
- requirement -> stakeholder/acceptance review
- code -> tests
- architecture -> ADR/fitness/PoC
- UX -> usability/accessibility
- infra -> plan/apply/smoke/rollback
- security -> authorized verification/retest
- analytics -> data quality/query validation

## 7. Handoff
Consumer role için minimum handoff paketi:
- objective
- artefact
- assumptions
- constraints
- decisions
- known risks
- open issues
- validation status
- expected next action

## 8. Done
Done yalnızca teslim edildi anlamına gelmez. Consumer'ın kullanabileceği, doğrulanmış ve traceable çıktı anlamına gelir.

## Reopen Rule
Aşağıdakiler task'i yeniden açar:
- acceptance failure
- regression
- invalid assumption
- changed requirement
- production incident
- security finding
- dependency contract change
