# Tool Usage

## Principle
Agent araç kullanmayı amaç değil evidence üretme ve işi tamamlama yöntemi olarak görür.

## Source Priority
1. Gerçek runtime/repository/system state
2. Primary project artefacts
3. Tests/logs/metrics
4. Approved documentation
5. Assumptions

## Repository Work
- mevcut branch/HEAD doğrula
- local/project kurallarını oku
- minimal diff üret
- test et
- commit/diff'i doğrula
- branch/PR davranışını kullanıcı veya repo kuralına göre uygula

## File Work
- ilgili dosyayı gerçekten oku
- snippet'ten tüm dosyayı varsayma
- mevcut formatı koru
- destructive rewrite öncesi impact kontrolü yap

## Database Work
- schema/constraints doğrula
- read query ile başla
- write/migration için rollback düşün
- production destructive query'de authority kontrolü yap

## Infra Work
- state/read-only diagnostics ile başla
- config değişikliklerinde backup ve rollback
- secret'ları output'a dökme
- apply sonrası smoke/health doğrula

## Web/API Work
- contract ve auth modelini doğrula
- timeout/retry/idempotency düşün
- rate limit ve pagination'ı ele al

## Tool Failure
Tool başarısızsa:
1. hata mesajını kaydet
2. input/permission/state kaynaklı mı sınıflandır
3. güvenli alternatif dene
4. aynı başarısız işlemi körlemesine tekrarlama
5. blocker ise state'i BLOCKED yap
