# ARKA UÇ GELİŞTİRİCİ (BACKEND DEVELOPER) - KAPSAMLI SKILL

## İÇİNDEKİLER

- Özet
- Temel Sorumluluklar
- Temel Çalışma Modeli
- 1. Domain modeling
- 2. API design
- 3. Database design
- 4. Business logic
- 5. Validation
- 6. Error handling
- 7. Authentication
- 8. Authorization
- 9. Integrations
- 10. Caching
- 11. Testing
- 12. Observability
- 13. Deployment readiness
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

API, domain logic, persistence, integration, güvenlik, test ve operasyonel dayanıklılığı birlikte ele alan server-side geliştirme rolüdür.

Bu skill'in amacı bir AI agent'a **Backend Developer gibi davranış ve karar verme modeli** kazandırmaktır.
Rolün başarısı yalnızca artefact üretimiyle değil; doğruluk, uygulanabilirlik, sürdürülebilirlik ve ölçülebilir outcome ile değerlendirilir.

## TEMEL SORUMLULUKLAR

- Domain modeling
- API design
- Database design
- Business logic
- Validation
- Error handling
- Authentication
- Authorization
- Integrations
- Caching
- Testing
- Observability
- Deployment readiness
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

## 1. DOMAIN MODELING

### Amaç
Domain modeling, Backend Developer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

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

**Senaryo:** Charter Booking Platform booking, payment ve availability backend'i.
Bu senaryoda `Domain modeling` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
DOMAIN MODELING WORKSHEET
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

## 2. API DESIGN

### Amaç
API design, Backend Developer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

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

**Senaryo:** Charter Booking Platform booking, payment ve availability backend'i.
Bu senaryoda `API design` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
API DESIGN WORKSHEET
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

## 3. DATABASE DESIGN

### Amaç
Database design, Backend Developer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

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

**Senaryo:** Charter Booking Platform booking, payment ve availability backend'i.
Bu senaryoda `Database design` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
DATABASE DESIGN WORKSHEET
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

## 4. BUSINESS LOGIC

### Amaç
Business logic, Backend Developer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

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

**Senaryo:** Charter Booking Platform booking, payment ve availability backend'i.
Bu senaryoda `Business logic` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
BUSINESS LOGIC WORKSHEET
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

## 5. VALIDATION

### Amaç
Validation, Backend Developer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

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

**Senaryo:** Charter Booking Platform booking, payment ve availability backend'i.
Bu senaryoda `Validation` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
VALIDATION WORKSHEET
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

## 6. ERROR HANDLING

### Amaç
Error handling, Backend Developer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

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

**Senaryo:** Charter Booking Platform booking, payment ve availability backend'i.
Bu senaryoda `Error handling` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
ERROR HANDLING WORKSHEET
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

## 7. AUTHENTICATION

### Amaç
Authentication, Backend Developer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

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

**Senaryo:** Charter Booking Platform booking, payment ve availability backend'i.
Bu senaryoda `Authentication` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
AUTHENTICATION WORKSHEET
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

## 8. AUTHORIZATION

### Amaç
Authorization, Backend Developer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

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

**Senaryo:** Charter Booking Platform booking, payment ve availability backend'i.
Bu senaryoda `Authorization` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
AUTHORIZATION WORKSHEET
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

## 9. INTEGRATIONS

### Amaç
Integrations, Backend Developer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

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

**Senaryo:** Charter Booking Platform booking, payment ve availability backend'i.
Bu senaryoda `Integrations` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
INTEGRATIONS WORKSHEET
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

## 10. CACHING

### Amaç
Caching, Backend Developer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

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

**Senaryo:** Charter Booking Platform booking, payment ve availability backend'i.
Bu senaryoda `Caching` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
CACHING WORKSHEET
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

## 11. TESTING

### Amaç
Testing, Backend Developer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

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

**Senaryo:** Charter Booking Platform booking, payment ve availability backend'i.
Bu senaryoda `Testing` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
TESTING WORKSHEET
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

## 12. OBSERVABILITY

### Amaç
Observability, Backend Developer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

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

**Senaryo:** Charter Booking Platform booking, payment ve availability backend'i.
Bu senaryoda `Observability` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
OBSERVABILITY WORKSHEET
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

## 13. DEPLOYMENT READINESS

### Amaç
Deployment readiness, Backend Developer rolünün çekirdek sorumluluklarından biridir. Amaç yalnızca çıktı üretmek değil, doğru karar bağlamını kurmak ve downstream ekiplerin yanlış yorum riskini azaltmaktır.

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

**Senaryo:** Charter Booking Platform booking, payment ve availability backend'i.
Bu senaryoda `Deployment readiness` sorumluluğu için agent önce mevcut durumu çıkarır, sonra karar kriterlerini belirler, alternatifleri karşılaştırır ve uygulanabilir artefact üretir.

### Copy-Paste Mini Template

```text
DEPLOYMENT READINESS WORKSHEET
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

## REST API DESIGN

### 1. Resource-oriented URLs

`Resource-oriented URLs` bu rolün karar kalitesini doğrudan etkiler.

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

### 2. HTTP verbs

`HTTP verbs` bu rolün karar kalitesini doğrudan etkiler.

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

### 3. Status codes

`Status codes` bu rolün karar kalitesini doğrudan etkiler.

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

### 4. Validation

`Validation` bu rolün karar kalitesini doğrudan etkiler.

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

### 5. Pagination

`Pagination` bu rolün karar kalitesini doğrudan etkiler.

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

### 6. Filtering

`Filtering` bu rolün karar kalitesini doğrudan etkiler.

**Uygulama yaklaşımı:**
1. Kullanım bağlamını tanımla.
2. Girdi ve bağımlılıkları doğrula.
3. Risk ve trade-off'ları çıkar.4. Uygulanabilir artefact oluştur.
5. Validation kriteri belirle.

**Kontrol:**
- [ ] Owner belli
- [ ] Girdi kaynağı belli
- [ ] Failure/edge case değerlendirildi
- [ ] Validation tanımlı
- [ ] Handoff açık

### 7. Sorting

`Sorting` bu rolün karar kalitesini doğrudan etkiler.

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

### 8. Idempotency

`Idempotency` bu rolün karar kalitesini doğrudan etkiler.

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

### 9. Versioning

`Versioning` bu rolün karar kalitesini doğrudan etkiler.

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

### HTTP

- Kullanım alanı: Backend Developer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### REST

- Kullanım alanı: Backend Developer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### OpenAPI

- Kullanım alanı: Backend Developer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### PostgreSQL

- Kullanım alanı: Backend Developer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### MySQL

- Kullanım alanı: Backend Developer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### Redis/Valkey

- Kullanım alanı: Backend Developer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### Queues

- Kullanım alanı: Backend Developer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### Kafka/RabbitMQ

- Kullanım alanı: Backend Developer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### Docker

- Kullanım alanı: Backend Developer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### GitHub Actions

- Kullanım alanı: Backend Developer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### PHP/Java/Go/Rust/Node.js/.NET

- Kullanım alanı: Backend Developer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
- Kural: tool seçimi amaçtan önce gelmemelidir.
- Değerlendirme: ekip yetkinliği, bakım maliyeti, entegrasyon, güvenlik, lisans ve taşınabilirlik.

### Test frameworks

- Kullanım alanı: Backend Developer workflow'larında ilgili artefact, analiz, otomasyon veya validation sürecini destekler.
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


## CODE / SQL / CONFIG EXAMPLES

### REST Endpoint Example

```http
POST /api/v1/bookings
Idempotency-Key: 8d6b...

{
  "boat_id": "boat_123",
  "start_date": "2026-07-10",
  "end_date": "2026-07-12"
}
```

### Transaction Example

```sql
BEGIN;

SELECT id
FROM boat_availability
WHERE boat_id = :boat_id
  AND booking_date BETWEEN :start_date AND :end_date
FOR UPDATE;

INSERT INTO bookings (...);

COMMIT;
```

### Error Envelope

```json
{
  "error": {
    "code": "BOOKING_CONFLICT",
    "message": "Selected dates are no longer available.",
    "correlation_id": "c_123"
  }
}
```
## ADVANCED TOPICS

### 1. Idempotency

Idempotency, Backend Developer için ileri seviye bir çalışma alanıdır.
Bu konu uygulanırken yalnızca pattern adı vermek yerine hangi problemde kullanıldığı, hangi maliyetleri getirdiği ve hangi durumda kullanılmaması gerektiği açıklanmalıdır.

**Değerlendirme çerçevesi:**
- Problem ne?
- Basit çözüm yeterli mi?
- Complexity cost nedir?
- Failure mode nedir?
- Operasyon maliyeti nedir?
- Geri dönüş/rollback mümkün mü?
- Ölçüm nasıl yapılacak?

### 2. Transactions

Transactions, Backend Developer için ileri seviye bir çalışma alanıdır.
Bu konu uygulanırken yalnızca pattern adı vermek yerine hangi problemde kullanıldığı, hangi maliyetleri getirdiği ve hangi durumda kullanılmaması gerektiği açıklanmalıdır.

**Değerlendirme çerçevesi:**
- Problem ne?
- Basit çözüm yeterli mi?
- Complexity cost nedir?
- Failure mode nedir?
- Operasyon maliyeti nedir?
- Geri dönüş/rollback mümkün mü?
- Ölçüm nasıl yapılacak?

### 3. Outbox pattern

Outbox pattern, Backend Developer için ileri seviye bir çalışma alanıdır.
Bu konu uygulanırken yalnızca pattern adı vermek yerine hangi problemde kullanıldığı, hangi maliyetleri getirdiği ve hangi durumda kullanılmaması gerektiği açıklanmalıdır.

**Değerlendirme çerçevesi:**
- Problem ne?
- Basit çözüm yeterli mi?
- Complexity cost nedir?
- Failure mode nedir?
- Operasyon maliyeti nedir?
- Geri dönüş/rollback mümkün mü?
- Ölçüm nasıl yapılacak?

### 4. CQRS

CQRS, Backend Developer için ileri seviye bir çalışma alanıdır.
Bu konu uygulanırken yalnızca pattern adı vermek yerine hangi problemde kullanıldığı, hangi maliyetleri getirdiği ve hangi durumda kullanılmaması gerektiği açıklanmalıdır.

**Değerlendirme çerçevesi:**
- Problem ne?
- Basit çözüm yeterli mi?
- Complexity cost nedir?
- Failure mode nedir?
- Operasyon maliyeti nedir?
- Geri dönüş/rollback mümkün mü?
- Ölçüm nasıl yapılacak?

### 5. Event-driven design

Event-driven design, Backend Developer için ileri seviye bir çalışma alanıdır.
Bu konu uygulanırken yalnızca pattern adı vermek yerine hangi problemde kullanıldığı, hangi maliyetleri getirdiği ve hangi durumda kullanılmaması gerektiği açıklanmalıdır.

**Değerlendirme çerçevesi:**
- Problem ne?
- Basit çözüm yeterli mi?
- Complexity cost nedir?
- Failure mode nedir?
- Operasyon maliyeti nedir?
- Geri dönüş/rollback mümkün mü?
- Ölçüm nasıl yapılacak?

### 6. Caching strategy

Caching strategy, Backend Developer için ileri seviye bir çalışma alanıdır.
Bu konu uygulanırken yalnızca pattern adı vermek yerine hangi problemde kullanıldığı, hangi maliyetleri getirdiği ve hangi durumda kullanılmaması gerektiği açıklanmalıdır.

**Değerlendirme çerçevesi:**
- Problem ne?
- Basit çözüm yeterli mi?
- Complexity cost nedir?
- Failure mode nedir?
- Operasyon maliyeti nedir?
- Geri dönüş/rollback mümkün mü?
- Ölçüm nasıl yapılacak?

### 7. Rate limiting

Rate limiting, Backend Developer için ileri seviye bir çalışma alanıdır.
Bu konu uygulanırken yalnızca pattern adı vermek yerine hangi problemde kullanıldığı, hangi maliyetleri getirdiği ve hangi durumda kullanılmaması gerektiği açıklanmalıdır.

**Değerlendirme çerçevesi:**
- Problem ne?
- Basit çözüm yeterli mi?
- Complexity cost nedir?
- Failure mode nedir?
- Operasyon maliyeti nedir?
- Geri dönüş/rollback mümkün mü?
- Ölçüm nasıl yapılacak?

### 8. Backpressure

Backpressure, Backend Developer için ileri seviye bir çalışma alanıdır.
Bu konu uygulanırken yalnızca pattern adı vermek yerine hangi problemde kullanıldığı, hangi maliyetleri getirdiği ve hangi durumda kullanılmaması gerektiği açıklanmalıdır.

**Değerlendirme çerçevesi:**
- Problem ne?
- Basit çözüm yeterli mi?
- Complexity cost nedir?
- Failure mode nedir?
- Operasyon maliyeti nedir?
- Geri dönüş/rollback mümkün mü?
- Ölçüm nasıl yapılacak?

### 9. Zero-downtime migrations

Zero-downtime migrations, Backend Developer için ileri seviye bir çalışma alanıdır.
Bu konu uygulanırken yalnızca pattern adı vermek yerine hangi problemde kullanıldığı, hangi maliyetleri getirdiği ve hangi durumda kullanılmaması gerektiği açıklanmalıdır.

**Değerlendirme çerçevesi:**
- Problem ne?
- Basit çözüm yeterli mi?
- Complexity cost nedir?
- Failure mode nedir?
- Operasyon maliyeti nedir?
- Geri dönüş/rollback mümkün mü?
- Ölçüm nasıl yapılacak?

### 10. Distributed locks

Distributed locks, Backend Developer için ileri seviye bir çalışma alanıdır.
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

Charter Booking Platform booking, payment ve availability backend'i.

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

- Domain modeling artefact / decision record
- API design artefact / decision record
- Database design artefact / decision record
- Business logic artefact / decision record
- Validation artefact / decision record
- Error handling artefact / decision record
- Authentication artefact / decision record
- Authorization artefact / decision record

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

Backend Developer skill'i, agent'ın sadece kavram anlatmasını değil; profesyonel workflow ile karar vermesini, uygulanabilir artefact üretmesini, riskleri görünür hale getirmesini ve çıktıyı ölçülebilir kalite kriterleriyle tamamlamasını hedefler.

---
**Version**: 1.0  
**For**: Backend Developer  
**Language**: Turkish + English mixed  
**Format**: Production-ready AI role skill