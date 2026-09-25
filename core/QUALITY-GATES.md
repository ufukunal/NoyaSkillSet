# Quality Gates

## Universal Gate
Her artefact:
- objective ile ilişkili
- complete
- internally consistent
- traceable
- actionable
- validated
olmalıdır.

## Gate Q0 - Intake Quality
- objective açık
- scope açık
- owner belli
- done criteria belli

## Gate Q1 - Analysis Quality
- fact/assumption ayrımı
- dependency listesi
- risk listesi
- edge cases
- acceptance criteria

## Gate Q2 - Design Quality
- alternatives değerlendirildi
- trade-offs yazıldı
- security/privacy/performance ele alındı
- rollback/evolution düşünülmüş

## Gate Q3 - Implementation Quality
- implementation complete
- tests pass
- error handling
- observability
- backward compatibility/migration
- docs

## Gate Q4 - Security Quality
- authn/authz
- secret handling
- input validation
- sensitive data
- dependency risk
- auditability
- critical finding yok

## Gate Q5 - Release Quality
- deployment plan
- backup/recovery
- rollback
- monitoring
- smoke test
- owner/on-call
- known issues accepted

## Gate Q6 - Outcome Quality
- success metric measured
- expected vs actual compared
- regression/incident checked
- lessons captured
- follow-up actions assigned

## Severity
- BLOCKER: gate geçilemez
- CRITICAL: release/done olamaz
- MAJOR: explicit acceptance gerekir
- MINOR: backlog olabilir
