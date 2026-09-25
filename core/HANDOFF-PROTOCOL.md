# Handoff Protocol

## Goal
Roller arası bilgi kaybını önlemek ve multi-agent execution'ı deterministic hale getirmek.

## Standard Handoff Envelope
```yaml
handoff:
  from: BUSINESS-ANALYST
  to: SOFTWARE-ARCHITECT
  task_id: TASK-123
  objective: ""
  deliverables: []
  decisions: []
  assumptions: []
  constraints: []
  risks: []
  open_questions: []
  validation_completed: []
  expected_next_action: ""
```

## Rules
1. Raw chat geçmişi handoff değildir.
2. Consumer'ın ihtiyaç duyduğu bağlam explicit olmalıdır.
3. Bilinmeyen bilgi known fact gibi aktarılmamalıdır.
4. Critical decision rationale korunmalıdır.
5. Open issue'lar saklanmamalıdır.
6. Consumer, handoff'u kabul etmeden kendi scope'unu genişletmemelidir.

## Default Role Flow
PRODUCT-MANAGER -> BUSINESS-ANALYST  
BUSINESS-ANALYST -> UX-UI-DESIGNER / SOFTWARE-ARCHITECT / DATA-ARCHITECT  
SOFTWARE-ARCHITECT -> BACKEND-DEVELOPER / FRONTEND-DEVELOPER / MOBILE-DEVELOPER / DEVOPS-ENGINEER  
DATA-ARCHITECT -> BACKEND-DEVELOPER / DATA-ANALYST  
UX-UI-DESIGNER -> FRONTEND-DEVELOPER / MOBILE-DEVELOPER  
BACKEND-DEVELOPER -> SECURITY-TESTER / DEVOPS-ENGINEER / TECHNICAL-WRITER  
FRONTEND-DEVELOPER -> SECURITY-TESTER / DEVOPS-ENGINEER  
MOBILE-DEVELOPER -> SECURITY-TESTER / TECHNICAL-WRITER  
SECURITY-ENGINEER -> all implementation roles  
DEVOPS-ENGINEER -> SYSTEM-ADMINISTRATOR / TECHNICAL-WRITER  
DATA-ANALYST -> PRODUCT-MANAGER / MARKETING-MANAGER  
PROJECT-MANAGER -> all roles for coordination, not domain override

## Rejection
Consumer handoff'u şu nedenlerle reject edebilir:
- missing required input
- contradictory requirements
- invalid dependency
- absent acceptance criteria
- unresolved critical risk

Reject edildiğinde eksik bilgiler açık liste halinde producer role'e döner.
