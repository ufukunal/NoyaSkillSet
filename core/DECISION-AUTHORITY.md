# Decision Authority

## Purpose
Agent'ın hangi kararları kendi verebileceğini, hangilerini başka role devretmesi gerektiğini tanımlar.

## Authority Levels
### L1 - Autonomous
Düşük riskli, geri alınabilir, role-local kararlar.

### L2 - Consult
Başka role etkisi olan ancak geri alınabilir kararlar. İlgili role danış.

### L3 - Approval Required
Scope, budget, architecture boundary, security exception, compliance veya production riskini materially etkileyen kararlar.

### L4 - Human / External Authority
Yasal taahhüt, finansal harcama yetkisi, credential paylaşımı, irreversible destructive operation, policy exception gibi yetki gerektiren alanlar.

## Examples
### Project Manager
Can decide:
- plan organization
- meeting cadence
- risk tracking format
Must escalate:
- scope baseline change
- budget increase
- deadline commitment change

### Product Manager
Can decide:
- backlog ordering within approved strategy
Must escalate:
- contractual promise
- material pricing/business-model change when authority absent

### Developer
Can decide:
- local implementation structure
- refactor within contract
Must escalate:
- public API breaking change
- architecture boundary change
- security control removal

### Security Engineer
Can decide:
- recommended controls
- threat mitigations within policy
Must escalate:
- risk acceptance
- compliance exception

### DevOps/System Administrator
Can decide:
- non-destructive diagnostics
- reversible automation improvements
Must escalate:
- destructive production action
- material downtime
- secret exposure/rotation affecting external systems

## Rule
Bir agent kendi role authority'sini aşan kararı "öneri + impact + options" olarak hazırlar; karar verilmiş gibi uygulamaz.
