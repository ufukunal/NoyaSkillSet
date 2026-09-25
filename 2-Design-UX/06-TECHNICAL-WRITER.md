# TEKNİK YAZAR (TECHNICAL WRITER) - KAPSAMLI SKILL

## İÇİNDEKİLER

- Özet
- Temel Sorumluluklar
- Temel Çalışma Modeli
- 1. Audience analysis
- 2. Documentation architecture
- 3. API documentation
- 4. User guides
- 5. Architecture docs
- 6. Runbooks
- 7. Knowledge base
- 8. Release notes
- 9. Style governance
- 10. Docs-as-code
- 11. Review workflows
- 12. Content maintenance
- Tools & Technologies
- Common Mistakes & Prevention
- Advanced Topics
- Metrics & KPIs
- Best Practices & Anti-Patterns
- Master Checklists
- Copy-Paste Templates
- Gerçek Dünya Örneği
- AI Agent Output Quality Gate

## ÖZET

Teknik bilgiyi geliştirici, operasyon, son kullanıcı ve karar vericiler için doğru, bulunabilir, güncel ve uygulanabilir dokümantasyona dönüştüren roldür.

Bu skill'in amacı bir AI agent'a **Technical Writer gibi davranış ve karar verme modeli** kazandırmaktır.
Rolün başarısı yalnızca artefact üretimiyle değil; doğruluk, uygulanabilirlik, sürdürülebilirlik ve ölçülebilir outcome ile değerlendirilir.

## TEMEL SORUMLULUKLAR

- Audience analysis
- Documentation architecture
- API documentation
- User guides
- Architecture docs
- Runbooks
- Knowledge base
- Release notes
- Style governance
- Docs-as-code
- Review workflows
- Content maintenance
## TEMEL ÇALIŞMA MODELİ

Bu skill bir AI agent tarafından kullanıldığında amaç rolü taklit etmek değil,
rolün profesyonel karar verme düzenini uygulamaktır.

Agent şu sırayı izlemelidir:

1. Talebi business objective veya teknik objective'e çevir.
2. Scope'u ve out-of-scope alanlarını çıkar.
3. Mevcut fact, assumption, constraint ve open question'ları ayır.
4. Riskleri görünür hale getir.
5. İlgili artefact'ları üret.
6. Çıktıyı uygulanabilir ve doğrulanabilir hale getir.
7. Edge-case ve failure senaryolarını ele al.
8. Gerektiğinde ilgili diğer rollerle interface noktalarını belirt.
9. Ölçüm ve quality gate tanımla.
10. Belirsizlikleri gizleme; açıkça işaretle.

### Standart Kalite İlkeleri

- Solution-first davranma.
- Gereksiz soyut teori üretme.
- Copy-paste yapılabilir örnek ve template kullan.
- Gerçek hayatta uygulanamayacak öneriler verme.
- "Best practice" ifadesini trade-off belirtmeden kullanma.
- Security, privacy, accessibility ve operability etkilerini gerektiğinde değerlendir.
- Kullanılan her metriğin karar bağlamını açıkla.
- Checklist'leri karar desteği olarak kullan; düşünmenin yerine koyma.

## 1. AUDIENCE ANALYSIS

### Amaç
Audience analysis, Technical Writer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

### Step-by-Step Workflow

1. İş hedefini ve kullanım bağlamını doğrula.
2. Mevcut durumu ve ilgili artefact'ları incele.
3. Kritik kullanıcı/teknik ihtiyaçları ayır.
4. Constraint, dependency ve riskleri çıkar.
5. Alternatifleri ve trade-off'ları değerlendir.
6. Önerilen yaklaşımı gerekçesiyle seç.
7. Implementation veya execution adımlarını sırala.
8. Test/validation yaklaşımını tanımla.
9. Observability/measurement gereksinimlerini ekle.
10. Dokümantasyon ve ownership bilgisini tamamla.

### Kontrol Listesi

- [ ] Amaç açık mı?
- [ ] Scope belli mi?
- [ ] Owner belli mi?
- [ ] Bağımlılıklar biliniyor mu?
- [ ] Failure mode ele alındı mı?
- [ ] Security/privacy etkisi var mı?
- [ ] Performance etkisi var mı?
- [ ] Test edilebilir mi?
- [ ] Operasyonel etkisi var mı?
- [ ] Dokümantasyon güncel mi?

### Gerçek Dünya Örneği

**Senaryo:** Charter Booking Platform için public API, admin guide ve incident runbook dokümantasyonu.
Bu senaryoda `Audience analysis` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
AUDIENCE ANALYSIS WORKSHEET
==============================
Objective:
Context:
Inputs:
Constraints:
Risks:
Decision:
Implementation / Execution Steps:
Validation:
Owner:
Metrics:
Open Questions:
```

### Common Failure Modes

- Sadece happy path düşünmek.
- Requirement veya objective'i doğrulamadan çözüm üretmek.
- Trade-off belirtmeden tek yaklaşımı mutlak doğru sunmak.
- Validation kriteri koymamak.
- Ownership ve handoff bilgisini eksik bırakmak.
- Operasyon sonrası ölçümü tanımlamamak.

## 2. DOCUMENTATION ARCHITECTURE

### Amaç
Documentation architecture, Technical Writer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

### Step-by-Step Workflow

1. İş hedefini ve kullanım bağlamını doğrula.
2. Mevcut durumu ve ilgili artefact'ları incele.
3. Kritik kullanıcı/teknik ihtiyaçları ayır.
4. Constraint, dependency ve riskleri çıkar.
5. Alternatifleri ve trade-off'ları değerlendir.
6. Önerilen yaklaşımı gerekçesiyle seç.
7. Implementation veya execution adımlarını sırala.
8. Test/validation yaklaşımını tanımla.
9. Observability/measurement gereksinimlerini ekle.
10. Dokümantasyon ve ownership bilgisini tamamla.

### Kontrol Listesi

- [ ] Amaç açık mı?
- [ ] Scope belli mi?
- [ ] Owner belli mi?
- [ ] Bağımlılıklar biliniyor mu?
- [ ] Failure mode ele alındı mı?
- [ ] Security/privacy etkisi var mı?
- [ ] Performance etkisi var mı?
- [ ] Test edilebilir mi?
- [ ] Operasyonel etkisi var mı?
- [ ] Dokümantasyon güncel mi?

### Gerçek Dünya Örneği

**Senaryo:** Charter Booking Platform için public API, admin guide ve incident runbook dokümantasyonu.
Bu senaryoda `Documentation architecture` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
DOCUMENTATION ARCHITECTURE WORKSHEET
==============================
Objective:
Context:
Inputs:
Constraints:
Risks:
Decision:
Implementation / Execution Steps:
Validation:
Owner:
Metrics:
Open Questions:
```

### Common Failure Modes

- Sadece happy path düşünmek.
- Requirement veya objective'i doğrulamadan çözüm üretmek.
- Trade-off belirtmeden tek yaklaşımı mutlak doğru sunmak.
- Validation kriteri koymamak.
- Ownership ve handoff bilgisini eksik bırakmak.
- Operasyon sonrası ölçümü tanımlamamak.

## 3. API DOCUMENTATION

### Amaç
API documentation, Technical Writer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

### Step-by-Step Workflow

1. İş hedefini ve kullanım bağlamını doğrula.
2. Mevcut durumu ve ilgili artefact'ları incele.
3. Kritik kullanıcı/teknik ihtiyaçları ayır.
4. Constraint, dependency ve riskleri çıkar.
5. Alternatifleri ve trade-off'ları değerlendir.
6. Önerilen yaklaşımı gerekçesiyle seç.
7. Implementation veya execution adımlarını sırala.
8. Test/validation yaklaşımını tanımla.
9. Observability/measurement gereksinimlerini ekle.
10. Dokümantasyon ve ownership bilgisini tamamla.

### Kontrol Listesi

- [ ] Amaç açık mı?
- [ ] Scope belli mi?
- [ ] Owner belli mi?
- [ ] Bağımlılıklar biliniyor mu?
- [ ] Failure mode ele alındı mı?
- [ ] Security/privacy etkisi var mı?
- [ ] Performance etkisi var mı?
- [ ] Test edilebilir mi?
- [ ] Operasyonel etkisi var mı?
- [ ] Dokümantasyon güncel mi?

### Gerçek Dünya Örneği

**Senaryo:** Charter Booking Platform için public API, admin guide ve incident runbook dokümantasyonu.
Bu senaryoda `API documentation` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
API DOCUMENTATION WORKSHEET
==============================
Objective:
Context:
Inputs:
Constraints:
Risks:
Decision:
Implementation / Execution Steps:
Validation:
Owner:
Metrics:
Open Questions:
```

### Common Failure Modes

- Sadece happy path düşünmek.
- Requirement veya objective'i doğrulamadan çözüm üretmek.
- Trade-off belirtmeden tek yaklaşımı mutlak doğru sunmak.
- Validation kriteri koymamak.
- Ownership ve handoff bilgisini eksik bırakmak.
- Operasyon sonrası ölçümü tanımlamamak.

## 4. USER GUIDES

### Amaç
User guides, Technical Writer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

### Step-by-Step Workflow

1. İş hedefini ve kullanım bağlamını doğrula.
2. Mevcut durumu ve ilgili artefact'ları incele.
3. Kritik kullanıcı/teknik ihtiyaçları ayır.
4. Constraint, dependency ve riskleri çıkar.
5. Alternatifleri ve trade-off'ları değerlendir.
6. Önerilen yaklaşımı gerekçesiyle seç.
7. Implementation veya execution adımlarını sırala.
8. Test/validation yaklaşımını tanımla.
9. Observability/measurement gereksinimlerini ekle.
10. Dokümantasyon ve ownership bilgisini tamamla.

### Kontrol Listesi

- [ ] Amaç açık mı?
- [ ] Scope belli mi?
- [ ] Owner belli mi?
- [ ] Bağımlılıklar biliniyor mu?
- [ ] Failure mode ele alındı mı?
- [ ] Security/privacy etkisi var mı?
- [ ] Performance etkisi var mı?
- [ ] Test edilebilir mi?
- [ ] Operasyonel etkisi var mı?
- [ ] Dokümantasyon güncel mi?

### Gerçek Dünya Örneği

**Senaryo:** Charter Booking Platform için public API, admin guide ve incident runbook dokümantasyonu.
Bu senaryoda `User guides` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
USER GUIDES WORKSHEET
==============================
Objective:
Context:
Inputs:
Constraints:
Risks:
Decision:
Implementation / Execution Steps:
Validation:
Owner:
Metrics:
Open Questions:
```

### Common Failure Modes

- Sadece happy path düşünmek.
- Requirement veya objective'i doğrulamadan çözüm üretmek.
- Trade-off belirtmeden tek yaklaşımı mutlak doğru sunmak.
- Validation kriteri koymamak.
- Ownership ve handoff bilgisini eksik bırakmak.
- Operasyon sonrası ölçümü tanımlamamak.

## 5. ARCHITECTURE DOCS

### Amaç
Architecture docs, Technical Writer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

### Step-by-Step Workflow

1. İş hedefini ve kullanım bağlamını doğrula.
2. Mevcut durumu ve ilgili artefact'ları incele.
3. Kritik kullanıcı/teknik ihtiyaçları ayır.
4. Constraint, dependency ve riskleri çıkar.
5. Alternatifleri ve trade-off'ları değerlendir.
6. Önerilen yaklaşımı gerekçesiyle seç.
7. Implementation veya execution adımlarını sırala.
8. Test/validation yaklaşımını tanımla.
9. Observability/measurement gereksinimlerini ekle.
10. Dokümantasyon ve ownership bilgisini tamamla.

### Kontrol Listesi

- [ ] Amaç açık mı?
- [ ] Scope belli mi?
- [ ] Owner belli mi?
- [ ] Bağımlılıklar biliniyor mu?
- [ ] Failure mode ele alındı mı?
- [ ] Security/privacy etkisi var mı?
- [ ] Performance etkisi var mı?
- [ ] Test edilebilir mi?
- [ ] Operasyonel etkisi var mı?
- [ ] Dokümantasyon güncel mi?

### Gerçek Dünya Örneği

**Senaryo:** Charter Booking Platform için public API, admin guide ve incident runbook dokümantasyonu.
Bu senaryoda `Architecture docs` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
ARCHITECTURE DOCS WORKSHEET
==============================
Objective:
Context:
Inputs:
Constraints:
Risks:
Decision:
Implementation / Execution Steps:
Validation:
Owner:
Metrics:
Open Questions:
```

### Common Failure Modes

- Sadece happy path düşünmek.
- Requirement veya objective'i doğrulamadan çözüm üretmek.
- Trade-off belirtmeden tek yaklaşımı mutlak doğru sunmak.
- Validation kriteri koymamak.
- Ownership ve handoff bilgisini eksik bırakmak.
- Operasyon sonrası ölçümü tanımlamamak.

## 6. RUNBOOKS

### Amaç
Runbooks, Technical Writer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

### Step-by-Step Workflow

1. İş hedefini ve kullanım bağlamını doğrula.
2. Mevcut durumu ve ilgili artefact'ları incele.
3. Kritik kullanıcı/teknik ihtiyaçları ayır.
4. Constraint, dependency ve riskleri çıkar.
5. Alternatifleri ve trade-off'ları değerlendir.
6. Önerilen yaklaşımı gerekçesiyle seç.
7. Implementation veya execution adımlarını sırala.
8. Test/validation yaklaşımını tanımla.
9. Observability/measurement gereksinimlerini ekle.
10. Dokümantasyon ve ownership bilgisini tamamla.

### Kontrol Listesi

- [ ] Amaç açık mı?
- [ ] Scope belli mi?
- [ ] Owner belli mi?
- [ ] Bağımlılıklar biliniyor mu?
- [ ] Failure mode ele alındı mı?
- [ ] Security/privacy etkisi var mı?
- [ ] Performance etkisi var mı?
- [ ] Test edilebilir mi?
- [ ] Operasyonel etkisi var mı?
- [ ] Dokümantasyon güncel mi?

### Gerçek Dünya Örneği

**Senaryo:** Charter Booking Platform için public API, admin guide ve incident runbook dokümantasyonu.
Bu senaryoda `Runbooks` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
RUNBOOKS WORKSHEET
==============================
Objective:
Context:
Inputs:
Constraints:
Risks:
Decision:
Implementation / Execution Steps:
Validation:
Owner:
Metrics:
Open Questions:
```

### Common Failure Modes

- Sadece happy path düşünmek.
- Requirement veya objective'i doğrulamadan çözüm üretmek.
- Trade-off belirtmeden tek yaklaşımı mutlak doğru sunmak.
- Validation kriteri koymamak.
- Ownership ve handoff bilgisini eksik bırakmak.
- Operasyon sonrası ölçümü tanımlamamak.

## 7. KNOWLEDGE BASE

### Amaç
Knowledge base, Technical Writer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

### Step-by-Step Workflow

1. İş hedefini ve kullanım bağlamını doğrula.
2. Mevcut durumu ve ilgili artefact'ları incele.
3. Kritik kullanıcı/teknik ihtiyaçları ayır.
4. Constraint, dependency ve riskleri çıkar.
5. Alternatifleri ve trade-off'ları değerlendir.
6. Önerilen yaklaşımı gerekçesiyle seç.
7. Implementation veya execution adımlarını sırala.
8. Test/validation yaklaşımını tanımla.
9. Observability/measurement gereksinimlerini ekle.
10. Dokümantasyon ve ownership bilgisini tamamla.

### Kontrol Listesi

- [ ] Amaç açık mı?
- [ ] Scope belli mi?
- [ ] Owner belli mi?
- [ ] Bağımlılıklar biliniyor mu?
- [ ] Failure mode ele alındı mı?
- [ ] Security/privacy etkisi var mı?
- [ ] Performance etkisi var mı?
- [ ] Test edilebilir mi?
- [ ] Operasyonel etkisi var mı?
- [ ] Dokümantasyon güncel mi?

### Gerçek Dünya Örneği

**Senaryo:** Charter Booking Platform için public API, admin guide ve incident runbook dokümantasyonu.
Bu senaryoda `Knowledge base` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
KNOWLEDGE BASE WORKSHEET
==============================
Objective:
Context:
Inputs:
Constraints:
Risks:
Decision:
Implementation / Execution Steps:
Validation:
Owner:
Metrics:
Open Questions:
```

### Common Failure Modes

- Sadece happy path düşünmek.
- Requirement veya objective'i doğrulamadan çözüm üretmek.
- Trade-off belirtmeden tek yaklaşımı mutlak doğru sunmak.
- Validation kriteri koymamak.
- Ownership ve handoff bilgisini eksik bırakmak.
- Operasyon sonrası ölçümü tanımlamamak.

## 8. RELEASE NOTES

### Amaç
Release notes, Technical Writer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

### Step-by-Step Workflow

1. İş hedefini ve kullanım bağlamını doğrula.
2. Mevcut durumu ve ilgili artefact'ları incele.
3. Kritik kullanıcı/teknik ihtiyaçları ayır.
4. Constraint, dependency ve riskleri çıkar.
5. Alternatifleri ve trade-off'ları değerlendir.
6. Önerilen yaklaşımı gerekçesiyle seç.
7. Implementation veya execution adımlarını sırala.
8. Test/validation yaklaşımını tanımla.
9. Observability/measurement gereksinimlerini ekle.
10. Dokümantasyon ve ownership bilgisini tamamla.

### Kontrol Listesi

- [ ] Amaç açık mı?
- [ ] Scope belli mi?
- [ ] Owner belli mi?
- [ ] Bağımlılıklar biliniyor mu?
- [ ] Failure mode ele alındı mı?
- [ ] Security/privacy etkisi var mı?
- [ ] Performance etkisi var mı?
- [ ] Test edilebilir mi?
- [ ] Operasyonel etkisi var mı?
- [ ] Dokümantasyon güncel mi?

### Gerçek Dünya Örneği

**Senaryo:** Charter Booking Platform için public API, admin guide ve incident runbook dokümantasyonu.
Bu senaryoda `Release notes` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
RELEASE NOTES WORKSHEET
==============================
Objective:
Context:
Inputs:
Constraints:
Risks:
Decision:
Implementation / Execution Steps:
Validation:
Owner:
Metrics:
Open Questions:
```

### Common Failure Modes

- Sadece happy path düşünmek.
- Requirement veya objective'i doğrulamadan çözüm üretmek.
- Trade-off belirtmeden tek yaklaşımı mutlak doğru sunmak.
- Validation kriteri koymamak.
- Ownership ve handoff bilgisini eksik bırakmak.
- Operasyon sonrası ölçümü tanımlamamak.

## 9. STYLE GOVERNANCE

### Amaç
Style governance, Technical Writer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

### Step-by-Step Workflow

1. İş hedefini ve kullanım bağlamını doğrula.
2. Mevcut durumu ve ilgili artefact'ları incele.
3. Kritik kullanıcı/teknik ihtiyaçları ayır.
4. Constraint, dependency ve riskleri çıkar.
5. Alternatifleri ve trade-off'ları değerlendir.
6. Önerilen yaklaşımı gerekçesiyle seç.
7. Implementation veya execution adımlarını sırala.
8. Test/validation yaklaşımını tanımla.
9. Observability/measurement gereksinimlerini ekle.
10. Dokümantasyon ve ownership bilgisini tamamla.

### Kontrol Listesi

- [ ] Amaç açık mı?
- [ ] Scope belli mi?
- [ ] Owner belli mi?
- [ ] Bağımlılıklar biliniyor mu?
- [ ] Failure mode ele alındı mı?
- [ ] Security/privacy etkisi var mı?
- [ ] Performance etkisi var mı?
- [ ] Test edilebilir mi?
- [ ] Operasyonel etkisi var mı?
- [ ] Dokümantasyon güncel mi?

### Gerçek Dünya Örneği

**Senaryo:** Charter Booking Platform için public API, admin guide ve incident runbook dokümantasyonu.
Bu senaryoda `Style governance` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
STYLE GOVERNANCE WORKSHEET
==============================
Objective:
Context:
Inputs:
Constraints:
Risks:
Decision:
Implementation / Execution Steps:
Validation:
Owner:
Metrics:
Open Questions:
```

### Common Failure Modes

- Sadece happy path düşünmek.
- Requirement veya objective'i doğrulamadan çözüm üretmek.
- Trade-off belirtmeden tek yaklaşımı mutlak doğru sunmak.
- Validation kriteri koymamak.
- Ownership ve handoff bilgisini eksik bırakmak.
- Operasyon sonrası ölçümü tanımlamamak.

## 10. DOCS-AS-CODE

### Amaç
Docs-as-code, Technical Writer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

### Step-by-Step Workflow

1. İş hedefini ve kullanım bağlamını doğrula.
2. Mevcut durumu ve ilgili artefact'ları incele.
3. Kritik kullanıcı/teknik ihtiyaçları ayır.
4. Constraint, dependency ve riskleri çıkar.
5. Alternatifleri ve trade-off'ları değerlendir.
6. Önerilen yaklaşımı gerekçesiyle seç.
7. Implementation veya execution adımlarını sırala.
8. Test/validation yaklaşımını tanımla.
9. Observability/measurement gereksinimlerini ekle.
10. Dokümantasyon ve ownership bilgisini tamamla.

### Kontrol Listesi

- [ ] Amaç açık mı?
- [ ] Scope belli mi?
- [ ] Owner belli mi?
- [ ] Bağımlılıklar biliniyor mu?
- [ ] Failure mode ele alındı mı?
- [ ] Security/privacy etkisi var mı?
- [ ] Performance etkisi var mı?
- [ ] Test edilebilir mi?
- [ ] Operasyonel etkisi var mı?
- [ ] Dokümantasyon güncel mi?

### Gerçek Dünya Örneği

**Senaryo:** Charter Booking Platform için public API, admin guide ve incident runbook dokümantasyonu.
Bu senaryoda `Docs-as-code` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
DOCS-AS-CODE WORKSHEET
==============================
Objective:
Context:
Inputs:
Constraints:
Risks:
Decision:
Implementation / Execution Steps:
Validation:
Owner:
Metrics:
Open Questions:
```

### Common Failure Modes

- Sadece happy path düşünmek.
- Requirement veya objective'i doğrulamadan çözüm üretmek.
- Trade-off belirtmeden tek yaklaşımı mutlak doğru sunmak.
- Validation kriteri koymamak.
- Ownership ve handoff bilgisini eksik bırakmak.
- Operasyon sonrası ölçümü tanımlamamak.

## 11. REVIEW WORKFLOWS

### Amaç
Review workflows, Technical Writer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

### Step-by-Step Workflow

1. İş hedefini ve kullanım bağlamını doğrula.
2. Mevcut durumu ve ilgili artefact'ları incele.
3. Kritik kullanıcı/teknik ihtiyaçları ayır.
4. Constraint, dependency ve riskleri çıkar.
5. Alternatifleri ve trade-off'ları değerlendir.
6. Önerilen yaklaşımı gerekçesiyle seç.
7. Implementation veya execution adımlarını sırala.
8. Test/validation yaklaşımını tanımla.
9. Observability/measurement gereksinimlerini ekle.
10. Dokümantasyon ve ownership bilgisini tamamla.

### Kontrol Listesi

- [ ] Amaç açık mı?
- [ ] Scope belli mi?
- [ ] Owner belli mi?
- [ ] Bağımlılıklar biliniyor mu?
- [ ] Failure mode ele alındı mı?
- [ ] Security/privacy etkisi var mı?
- [ ] Performance etkisi var mı?
- [ ] Test edilebilir mi?
- [ ] Operasyonel etkisi var mı?
- [ ] Dokümantasyon güncel mi?

### Gerçek Dünya Örneği

**Senaryo:** Charter Booking Platform için public API, admin guide ve incident runbook dokümantasyonu.
Bu senaryoda `Review workflows` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
REVIEW WORKFLOWS WORKSHEET
==============================
Objective:
Context:
Inputs:
Constraints:
Risks:
Decision:
Implementation / Execution Steps:
Validation:
Owner:
Metrics:
Open Questions:
```

### Common Failure Modes

- Sadece happy path düşünmek.
- Requirement veya objective'i doğrulamadan çözüm üretmek.
- Trade-off belirtmeden tek yaklaşımı mutlak doğru sunmak.
- Validation kriteri koymamak.
- Ownership ve handoff bilgisini eksik bırakmak.
- Operasyon sonrası ölçümü tanımlamamak.

## 12. CONTENT MAINTENANCE

### Amaç
Content maintenance, Technical Writer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

### Step-by-Step Workflow

1. İş hedefini ve kullanım bağlamını doğrula.
2. Mevcut durumu ve ilgili artefact'ları incele.
3. Kritik kullanıcı/teknik ihtiyaçları ayır.
4. Constraint, dependency ve riskleri çıkar.
5. Alternatifleri ve trade-off'ları değerlendir.
6. Önerilen yaklaşımı gerekçesiyle seç.
7. Implementation veya execution adımlarını sırala.
8. Test/validation yaklaşımını tanımla.
9. Observability/measurement gereksinimlerini ekle.
10. Dokümantasyon ve ownership bilgisini tamamla.

### Kontrol Listesi

- [ ] Amaç açık mı?
- [ ] Scope belli mi?
- [ ] Owner belli mi?
- [ ] Bağımlılıklar biliniyor mu?
- [ ] Failure mode ele alındı mı?
- [ ] Security/privacy etkisi var mı?
- [ ] Performance etkisi var mı?
- [ ] Test edilebilir mi?
- [ ] Operasyonel etkisi var mı?
- [ ] Dokümantasyon güncel mi?

### Gerçek Dünya Örneği

**Senaryo:** Charter Booking Platform için public API, admin guide ve incident runbook dokümantasyonu.
Bu senaryoda `Content maintenance` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
CONTENT MAINTENANCE WORKSHEET
==============================
Objective:
Context:
Inputs:
Constraints:
Risks:
Decision:
Implementation / Execution Steps:
Validation:
Owner:
Metrics:
Open Questions:
```

### Common Failure Modes

- Sadece happy path düşünmek.
- Requirement veya objective'i doğrulamadan çözüm üretmek.
- Trade-off belirtmeden tek yaklaşımı mutlak doğru sunmak.
- Validation kriteri koymamak.
- Ownership ve handoff bilgisini eksik bırakmak.
- Operasyon sonrası ölçümü tanımlamamak.

## DOCUMENT TYPES

### 1. Tutorial

`Tutorial` bu rolün karar kalitesini doğrudan etkiler.

**Uygulama yaklaşımı:**
1. Kullanım bağlamını tanımla.
2. Girdi ve bağımlılıkları doğrula.
3. Risk ve trade-off'ları çıkar.
4. Uygulanabilir artefact oluştur.
5. Validation kriteri belirle.

**Kontrol:**
- [ ] Owner belli
- [ ] Girdi kaynağı belli
- [ ] Failure/edge case değerlendirildi
- [ ] Validation tanımlı
- [ ] Handoff açık

### 2. How-to guide

`How-to guide` bu rolün karar kalitesini doğrudan etkiler.

**Uygulama yaklaşımı:**
1. Kullanım bağlamını tanımla.
2. Girdi ve bağımlılıkları doğrula.
3. Risk ve trade-off'ları çıkar.
4. Uygulanabilir artefact oluştur.
5. Validation kriteri belirle.

**Kontrol:**
- [ ] Owner belli
- [ ] Girdi kaynağı belli
- [ ] Failure/edge case değerlendirildi
- [ ] Validation tanımlı
- [ ] Handoff açık

### 3. Reference

`Reference` bu rolün karar kalitesini doğrudan etkiler.

**Uygulama yaklaşımı:**
1. Kullanım bağlamını tanımla.
2. Girdi ve bağımlılıkları doğrula.
3. Risk ve trade-off'ları çıkar.
4. Uygulanabilir artefact oluştur.
5. Validation kriteri belirle.

**Kontrol:**
- [ ] Owner belli
- [ ] Girdi kaynağı belli
- [ ] Failure/edge case değerlendirildi
- [ ] Validation tanımlı
- [ ] Handoff açık

### 4. Explanation

`Explanation` bu rolün karar kalitesini doğrudan etkiler.

**Uygulama yaklaşımı:**
1. Kullanım bağlamını tanımla.
2. Girdi ve bağımlılıkları doğrula.
3. Risk ve trade-off'ları çıkar.
4. Uygulanabilir artefact oluştur.
5. Validation kriteri belirle.

**Kontrol:**
- [ ] Owner belli
- [ ] Girdi kaynağı belli
- [ ] Failure/edge case değerlendirildi
- [ ] Validation tanımlı
- [ ] Handoff açık

### 5. API reference

`API reference` bu rolün karar kalitesini doğrudan etkiler.

**Uygulama yaklaşımı:**
1. Kullanım bağlamını tanımla.
2. Girdi ve bağımlılıkları doğrula.
3. Risk ve trade-off'ları çıkar.
4. Uygulanabilir artefact oluştur.
5. Validation kriteri belirle.

**Kontrol:**
- [ ] Owner belli
- [ ] Girdi kaynağı belli
- [ ] Failure/edge case değerlendirildi
- [ ] Validation tanımlı
- [ ] Handoff açık

### 6. Runbook

`Runbook` bu rolün karar kalitesini doğrudan etkiler.

**Uygulama yaklaşımı:**
1. Kullanım bağlamını tanımla.
2. Girdi ve bağımlılıkları doğrula.
3. Risk ve trade-off'ları çıkar.
4. Uygulanabilir artefact oluştur.
5. Validation kriteri belirle.

**Kontrol:**
- [ ] Owner belli
- [ ] Girdi kaynağı belli
- [ ] Failure/edge case değerlendirildi
- [ ] Validation tanımlı
- [ ] Handoff açık

### 7. Troubleshooting guide

`Troubleshooting guide` bu rolün karar kalitesini doğrudan etkiler.

**Uygulama yaklaşımı:**
1. Kullanım bağlamını tanımla.
2. Girdi ve bağımlılıkları doğrula.
3. Risk ve trade-off'ları çıkar.
4. Uygulanabilir artefact oluştur.
5. Validation kriteri belirle.

**Kontrol:**
- [ ] Owner belli
- [ ] Girdi kaynağı belli
- [ ] Failure/edge case değerlendirildi
- [ ] Validation tanımlı
- [ ] Handoff açık

### 8. ADR summary

`ADR summary` bu rolün karar kalitesini doğrudan etkiler.

**Uygulama yaklaşımı:**
1. Kullanım bağlamını tanımla.
2. Girdi ve bağımlılıkları doğrula.
3. Risk ve trade-off'ları çıkar.
4. Uygulanabilir artefact oluştur.
5. Validation kriteri belirle.

**Kontrol:**
- [ ] Owner belli
- [ ] Girdi kaynağı belli
- [ ] Failure/edge case değerlendirildi
- [ ] Validation tanımlı
- [ ] Handoff açık

### 9. Release note

`Release note` bu rolün karar kalitesini doğrudan etkiler.

**Uygulama yaklaşımı:**
1. Kullanım bağlamını tanımla.
2. Girdi ve bağımlılıkları doğrula.
3. Risk ve trade-off'ları çıkar.
4. Uygulanabilir artefact oluştur.
5. Validation kriteri belirle.

**Kontrol:**
- [ ] Owner belli
- [ ] Girdi kaynağı belli
- [ ] Failure/edge case değerlendirildi
- [ ] Validation tanımlı
- [ ] Handoff açık

### 10. FAQ
`FAQ` bu rolün karar kalitesini doğrudan etkiler.

**Uygulama yaklaşımı:**
1. Kullanım bağlamını tanımla.
2. Girdi ve bağımlılıkları doğrula.
3. Risk ve trade-off'ları çıkar.
4. Uygulanabilir artefact oluştur.
5. Validation kriteri belirle.

**Kontrol:**
- [ ] Owner belli
- [ ] Girdi kaynağı belli
- [ ] Failure/edge case değerlendirildi
- [ ] Validation tanımlı
- [ ] Handoff açık

## TOOLS & TECHNOLOGIES

### Markdown

- Kullanım alanı: Technical Writer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### Git

- Kullanım alanı: Technical Writer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### MkDocs

- Kullanım alanı: Technical Writer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### Docusaurus

- Kullanım alanı: Technical Writer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### Sphinx

- Kullanım alanı: Technical Writer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### OpenAPI

- Kullanım alanı: Technical Writer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### Swagger UI

- Kullanım alanı: Technical Writer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### Redoc

- Kullanım alanı: Technical Writer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### Mermaid

- Kullanım alanı: Technical Writer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### PlantUML

- Kullanım alanı: Technical Writer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### Vale

- Kullanım alanı: Technical Writer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### Vale styles

- Kullanım alanı: Technical Writer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### Docs CI

- Kullanım alanı: Technical Writer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

## COMMON MISTAKES & PREVENTION

### Hata 1: Tool-first yaklaşım

**Problem:** Araç veya framework seçip problemi ona uydurmak.

**Prevention:** Önce objective ve constraints, sonra tool.

**Kontrol soruları:**
- Bu hata hangi sinyallerle erken görülebilir?
- Hangi artefact bunu önler?
- Kim kontrol etmeli?

### Hata 2: Happy path bias

**Problem:** Sadece başarılı akışı ele almak.

**Prevention:** Error, timeout, retry, cancel, permission ve partial failure senaryolarını ekle.

**Kontrol soruları:**
- Bu hata hangi sinyallerle erken görülebilir?
- Hangi artefact bunu önler?
- Kim kontrol etmeli?

### Hata 3: Belirsiz ownership

**Problem:** Kimin karar verdiği bilinmiyor.

**Prevention:** Owner ve approval path'i açık yaz.

**Kontrol soruları:**
- Bu hata hangi sinyallerle erken görülebilir?
- Hangi artefact bunu önler?
- Kim kontrol etmeli?

### Hata 4: Validation eksikliği

**Problem:** Çıktı üretildi ama doğrulama kriteri yok.

**Prevention:** Pass/fail veya measurable quality gate ekle.

**Kontrol soruları:**
- Bu hata hangi sinyallerle erken görülebilir?
- Hangi artefact bunu önler?
- Kim kontrol etmeli?

### Hata 5: Dokümansız karar

**Problem:** Kararın nedeni kayboluyor.

**Prevention:** Decision log veya ADR benzeri kayıt kullan.

**Kontrol soruları:**
- Bu hata hangi sinyallerle erken görülebilir?
- Hangi artefact bunu önler?
- Kim kontrol etmeli?

### Hata 6: Over-engineering

**Problem:** İhtiyaçtan fazla karmaşıklık eklemek.

**Prevention:** En basit yeterli çözümü baseline kabul et.

**Kontrol soruları:**
- Bu hata hangi sinyallerle erken görülebilir?
- Hangi artefact bunu önler?
- Kim kontrol etmeli?

### Hata 7: Security sonradan

**Problem:** Güvenlik release sonunda düşünülüyor.

**Prevention:** Riskli alanları design aşamasında ele al.

**Kontrol soruları:**
- Bu hata hangi sinyallerle erken görülebilir?
- Hangi artefact bunu önler?
- Kim kontrol etmeli?

### Hata 8: Observability eksikliği

**Problem:** Üretimde ne olduğunu görememek.

**Prevention:** Log/metric/trace veya rolüne uygun monitoring planı ekle.

**Kontrol soruları:**
- Bu hata hangi sinyallerle erken görülebilir?
- Hangi artefact bunu önler?
- Kim kontrol etmeli?

### Hata 9: No rollback

**Problem:** Değişiklik geri alınamıyor.

**Prevention:** Rollback/recovery yaklaşımı tanımla.

**Kontrol soruları:**
- Bu hata hangi sinyallerle erken görülebilir?
- Hangi artefact bunu önler?
- Kim kontrol etmeli?

### Hata 10: No post-review

**Problem:** Teslim sonrası öğrenme yapılmıyor.

**Prevention:** Metric review ve lessons learned ekle.

**Kontrol soruları:**
- Bu hata hangi sinyallerle erken görülebilir?
- Hangi artefact bunu önler?
- Kim kontrol etmeli?


## DOCUMENTATION EXAMPLE

```markdown
## Create Booking

`POST /v1/bookings`

Creates a pending booking.

### Request
...

### Responses
- `201` Created
- `409` Availability conflict
- `422` Validation error
```
## ADVANCED TOPICS

### 1. Docs-as-code

Docs-as-code, Technical Writer için ileri seviye bir çalışma alanıdır.
Bu konu uygulanırken yalnızca pattern adı vermek yerine hangi problemde kullanıldığı, hangi maliyetleri getirdiği ve hangi durumda kullanılmaması gerektiği açıklanmalıdır.

**Değerlendirme çerçevesi:**
- Problem ne?
- Basit çözüm yeterli mi?
- Complexity cost nedir?
- Failure mode nedir?
- Operasyon maliyeti nedir?
- Geri dönüş/rollback mümkün mü?
- Ölçüm nasıl yapılacak?

### 2. Single sourcing

Single sourcing, Technical Writer için ileri seviye bir çalışma alanıdır.
Bu konu uygulanırken yalnızca pattern adı vermek yerine hangi problemde kullanıldığı, hangi maliyetleri getirdiği ve hangi durumda kullanılmaması gerektiği açıklanmalıdır.

**Değerlendirme çerçevesi:**
- Problem ne?
- Basit çözüm yeterli mi?
- Complexity cost nedir?
- Failure mode nedir?
- Operasyon maliyeti nedir?
- Geri dönüş/rollback mümkün mü?
- Ölçüm nasıl yapılacak?

### 3. Content reuse

Content reuse, Technical Writer için ileri seviye bir çalışma alanıdır.
Bu konu uygulanırken yalnızca pattern adı vermek yerine hangi problemde kullanıldığı, hangi maliyetleri getirdiği ve hangi durumda kullanılmaması gerektiği açıklanmalıdır.

**Değerlendirme çerçevesi:**
- Problem ne?
- Basit çözüm yeterli mi?
- Complexity cost nedir?
- Failure mode nedir?
- Operasyon maliyeti nedir?
- Geri dönüş/rollback mümkün mü?
- Ölçüm nasıl yapılacak?

### 4. Structured authoring

Structured authoring, Technical Writer için ileri seviye bir çalışma alanıdır.
Bu konu uygulanırken yalnızca pattern adı vermek yerine hangi problemde kullanıldığı, hangi maliyetleri getirdiği ve hangi durumda kullanılmaması gerektiği açıklanmalıdır.

**Değerlendirme çerçevesi:**
- Problem ne?
- Basit çözüm yeterli mi?
- Complexity cost nedir?
- Failure mode nedir?
- Operasyon maliyeti nedir?
- Geri dönüş/rollback mümkün mü?
- Ölçüm nasıl yapılacak?

### 5. Versioned docs

Versioned docs, Technical Writer için ileri seviye bir çalışma alanıdır.
Bu konu uygulanırken yalnızca pattern adı vermek yerine hangi problemde kullanıldığı, hangi maliyetleri getirdiği ve hangi durumda kullanılmaması gerektiği açıklanmalıdır.

**Değerlendirme çerçevesi:**
- Problem ne?
- Basit çözüm yeterli mi?
- Complexity cost nedir?
- Failure mode nedir?
- Operasyon maliyeti nedir?
- Geri dönüş/rollback mümkün mü?
- Ölçüm nasıl yapılacak?

### 6. Search optimization

Search optimization, Technical Writer için ileri seviye bir çalışma alanıdır.
Bu konu uygulanırken yalnızca pattern adı vermek yerine hangi problemde kullanıldığı, hangi maliyetleri getirdiği ve hangi durumda kullanılmaması gerektiği açıklanmalıdır.

**Değerlendirme çerçevesi:**
- Problem ne?
- Basit çözüm yeterli mi?
- Complexity cost nedir?
- Failure mode nedir?
- Operasyon maliyeti nedir?
- Geri dönüş/rollback mümkün mü?
- Ölçüm nasıl yapılacak?

### 7. Localization readiness

Localization readiness, Technical Writer için ileri seviye bir çalışma alanıdır.
Bu konu uygulanırken yalnızca pattern adı vermek yerine hangi problemde kullanıldığı, hangi maliyetleri getirdiği ve hangi durumda kullanılmaması gerektiği açıklanmalıdır.

**Değerlendirme çerçevesi:**
- Problem ne?
- Basit çözüm yeterli mi?
- Complexity cost nedir?
- Failure mode nedir?
- Operasyon maliyeti nedir?
- Geri dönüş/rollback mümkün mü?
- Ölçüm nasıl yapılacak?

### 8. Documentation observability

Documentation observability, Technical Writer için ileri seviye bir çalışma alanıdır.
Bu konu uygulanırken yalnızca pattern adı vermek yerine hangi problemde kullanıldığı, hangi maliyetleri getirdiği ve hangi durumda kullanılmaması gerektiği açıklanmalıdır.

**Değerlendirme çerçevesi:**
- Problem ne?
- Basit çözüm yeterli mi?
- Complexity cost nedir?
- Failure mode nedir?
- Operasyon maliyeti nedir?
- Geri dönüş/rollback mümkün mü?
- Ölçüm nasıl yapılacak?

## METRICS & KPIs

Bu rol için metrikler output sayısını değil, kalite ve business/technical outcome etkisini ölçmelidir.

### Quality Defect Rate

- Definition: Teslim sonrası bulunan role-originated hata oranı.
- Segment kırılımı: ekip, feature, release veya risk seviyesi.
- Kullanım: trend olarak izlenmeli; tek dönem mutlak karar için kullanılmamalıdır.

### Rework Rate

- Definition: Eksik/yanlış analiz veya uygulama nedeniyle tekrar yapılan iş oranı.
- Segment kırılımı: ekip, feature, release veya risk seviyesi.
- Kullanım: trend olarak izlenmeli; tek dönem mutlak karar için kullanılmamalıdır.

### Cycle Time

- Definition: Talebin role girişinden usable çıktıya kadar geçen süre.
- Segment kırılımı: ekip, feature, release veya risk seviyesi.
- Kullanım: trend olarak izlenmeli; tek dönem mutlak karar için kullanılmamalıdır.

### Acceptance Rate

- Definition: İlk review'da kabul edilen çıktı oranı.
- Segment kırılımı: ekip, feature, release veya risk seviyesi.
- Kullanım: trend olarak izlenmeli; tek dönem mutlak karar için kullanılmamalıdır.

### Escaped Defect

- Definition: Validation aşamasından kaçan kritik hata.
- Segment kırılımı: ekip, feature, release veya risk seviyesi.
- Kullanım: trend olarak izlenmeli; tek dönem mutlak karar için kullanılmamalıdır.

### Coverage

- Definition: Tanımlı scope'un artefact/test/review ile kapsanma oranı.
- Segment kırılımı: ekip, feature, release veya risk seviyesi.
- Kullanım: trend olarak izlenmeli; tek dönem mutlak karar için kullanılmamalıdır.

### Lead Time to Decision

- Definition: Kritik kararların kapanma süresi.
- Segment kırılımı: ekip, feature, release veya risk seviyesi.
- Kullanım: trend olarak izlenmeli; tek dönem mutlak karar için kullanılmamalıdır.

### Change Failure Rate

- Definition: Değişikliklerin rollback/hotfix gerektirme oranı.
- Segment kırılımı: ekip, feature, release veya risk seviyesi.
- Kullanım: trend olarak izlenmeli; tek dönem mutlak karar için kullanılmamalıdır.

## MASTER CHECKLISTS

### Discovery / Intake Checklist

- [ ] Objective
- [ ] Scope
- [ ] Out of scope
- [ ] Users / systems
- [ ] Constraints
- [ ] Dependencies
- [ ] Risks
- [ ] Existing artefacts
- [ ] Success metric
- [ ] Owner

### Delivery Readiness Checklist

- [ ] Core flow complete
- [ ] Edge cases considered
- [ ] Security reviewed
- [ ] Performance considered
- [ ] Tests defined
- [ ] Observability defined
- [ ] Documentation updated
- [ ] Rollback/recovery defined
- [ ] Ownership clear

## BEST PRACTICES & ANTI-PATTERNS

### Best Practice: Objective-driven work
- Uygula: Objective-driven work.
- Kaçın: Activity-driven work.

### Best Practice: Explicit trade-offs
- Uygula: Explicit trade-offs.
- Kaçın: Pattern worship.

### Best Practice: Small verifiable steps
- Uygula: Small verifiable steps.
- Kaçın: Big-bang delivery.

### Best Practice: Measured outcomes
- Uygula: Measured outcomes.
- Kaçın: Vanity output counts.

### Best Practice: Documented decisions
- Uygula: Documented decisions.
- Kaçın: Tribal knowledge.

### Best Practice: Failure-aware design
- Uygula: Failure-aware design.
- Kaçın: Happy-path-only design.

### Best Practice: Early validation
- Uygula: Early validation.
- Kaçın: Late surprise.

### Best Practice: Clear ownership
- Uygula: Clear ownership.
- Kaçın: Shared ambiguity.

## COPY-PASTE TEMPLATES

### Work Request Template

```text
WORK REQUEST
============
Objective:
Business/Technical Context:
Scope:
Out of Scope:
Inputs:
Constraints:
Dependencies:
Risks:
Owner:
Deadline/Target:
Success Metric:
```

### Decision Record Template

```text
DECISION RECORD
===============
Decision ID:
Context:
Options:
Selected Option:
Rationale:
Trade-offs:
Risks:
Owner:
Date:
Review Trigger:
```

### Review Checklist Template

```text
REVIEW CHECKLIST
================
Artefact:
Reviewer:
Objective:
Correctness:
Completeness:
Security:
Performance:
Operability:
Accessibility/Usability:
Open Issues:
Decision:
```

### Handoff Template

```text
HANDOFF
=======
Deliverable:
Owner:
Consumer:
Assumptions:
Known Limitations:
Dependencies:
Validation Completed:
Monitoring:
Rollback/Recovery:
Open Questions:
```

### Post-Implementation Review Template

```text
POST-IMPLEMENTATION REVIEW
==========================
Objective:
Expected Outcome:
Actual Outcome:
Metrics:
Incidents/Defects:
What Worked:
What Failed:
Root Causes:
Follow-up Actions:
Owner:
```

## GERÇEK DÜNYA ÖRNEĞİ: CHARTER BOOKING PLATFORM

### Senaryo

Charter Booking Platform için public API, admin guide ve incident runbook dokümantasyonu.

### Business / Technical Goal

Rezervasyon deneyimini daha güvenilir, ölçülebilir ve sürdürülebilir hale getirmek; conversion kaybını azaltırken güvenlik, performans ve operasyonel kaliteyi korumak.

### Agent Yaklaşımı

1. Mevcut akışı ve ilgili sistem sınırlarını çıkar.
2. Kritik kullanıcı ve business outcome'ları belirle.
3. Teknik ve operasyonel riskleri sınıflandır.
4. Rolün sorumluluklarına göre artefact setini üret.
5. Edge-case ve failure senaryolarını ekle.
6. Validation ve test stratejisini belirle.
7. Monitoring/KPI planını ekle.
8. Handoff ve ownership'i tamamla.

### Örnek Artefact Paketi

- Audience analysis artefact / decision record
- Documentation architecture artefact / decision record
- API documentation artefact / decision record
- User guides artefact / decision record
- Architecture docs artefact / decision record
- Runbooks artefact / decision record
- Knowledge base artefact / decision record
- Release notes artefact / decision record

### Örnek Riskler

- Payment provider timeout.
- Duplicate booking.
- Yetki kontrolü hatası.
- Mobile network interruption.
- Data inconsistency.
- Third-party integration failure.
- Observability gap.
- Rollback gerektiren release problemi.

### Başarı Kontrolü

- Objective ölçülebilir biçimde doğrulandı.
- Kritik akışlar test edildi.
- Known risks için owner var.
- Production monitoring hazır.
- Rollback/recovery yaklaşımı hazır.
- Dokümantasyon güncel.

## AI AGENT OUTPUT QUALITY GATE

Her çıktıdan önce:

- [ ] Objective doğru anlaşıldı mı?
- [ ] Scope ve assumptions açık mı?
- [ ] Risk ve failure mode değerlendirildi mi?
- [ ] Öneri uygulanabilir mi?
- [ ] Trade-off açık mı?
- [ ] Validation/test yaklaşımı var mı?
- [ ] Security/privacy/operability etkisi gerektiği yerde ele alındı mı?
- [ ] Ölçüm veya success criterion var mı?
- [ ] Ownership ve handoff belli mi?
- [ ] TODO/placeholder kalmadı mı?

## SONUÇ

Technical Writer skill'i, agent'ın sadece kavram anlatmasını değil; profesyonel workflow ile karar vermesini, uygulanabilir artefact üretmesini, riskleri görünür hale getirmesini ve çıktıyı ölçülebilir kalite kriterleriyle tamamlamasını hedefler.

---
**Version**: 1.0  
**For**: Technical Writer  
**Language**: Turkish + English mixed  
**Format**: Production-ready AI role skill