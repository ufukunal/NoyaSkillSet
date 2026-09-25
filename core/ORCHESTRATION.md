# Orchestration

## Role Selection
Bir task bir veya daha fazla skill gerektirebilir. Orchestrator rol seçimini title'a göre değil work type'a göre yapar.

## Routing Matrix
- roadmap, value, prioritization -> PRODUCT-MANAGER
- project plan, dependency, risk -> PROJECT-MANAGER
- requirement, process, rules -> BUSINESS-ANALYST
- market, campaign, GTM -> MARKETING-MANAGER
- UX research, flow, UI -> UX-UI-DESIGNER
- documentation -> TECHNICAL-WRITER
- API/domain/server -> BACKEND-DEVELOPER
- service boundaries/distributed systems -> MICROSERVICES-ARCHITECT
- system architecture/quality attributes -> SOFTWARE-ARCHITECT
- data model/platform/governance -> DATA-ARCHITECT
- web UI -> FRONTEND-DEVELOPER
- iOS/Android/cross-platform -> MOBILE-DEVELOPER
- end-to-end vertical feature -> FULL-STACK-DEVELOPER
- CI/CD/IaC/platform -> DEVOPS-ENGINEER
- OS/network/server ops -> SYSTEM-ADMINISTRATOR
- authorized security testing -> SECURITY-TESTER
- secure design/threat/IAM -> SECURITY-ENGINEER
- BI/SQL/experiment analysis -> DATA-ANALYST

## Dependency Graph
Orchestrator DAG oluşturur. Circular dependency varsa decision owner belirler veya interface contract ile döngüyü kırar.

## Parallelization
Paralel yürüt:
- bağımsız research streams
- frontend/backend contract netse implementation
- docs/test preparation
- security design review ile implementation planning

Serileştir:
- requirement -> architecture breaking decisions
- schema contract -> dependent implementation
- deployment -> smoke validation
- security finding -> remediation -> retest

## Orchestration Loop
1. Decompose
2. Route
3. Order dependencies
4. Execute unblocked tasks
5. Collect artefacts
6. Validate
7. Rework failed gates
8. Integrate
9. Release/readiness review
10. Outcome review
