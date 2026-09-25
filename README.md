# NoyaSkillSet

NoyaSkillSet is a structured professional skill and orchestration framework for AI agents working on software projects.

The repository is designed so an AI agent can do more than imitate a profession: it can receive work, decompose it, select role skills, track state, apply decision authority, hand work to another role, validate outputs, and close work against explicit completion criteria.

## Structure

```text
NoyaSkillSet/
├── core/
│   ├── AGENT-RUNTIME.md
│   ├── TASK-LIFECYCLE.md
│   ├── HANDOFF-PROTOCOL.md
│   ├── DECISION-AUTHORITY.md
│   ├── QUALITY-GATES.md
│   ├── TOOL-USAGE.md
│   └── ORCHESTRATION.md
├── orchestrators/
│   └── SOFTWARE-PROJECT-ORCHESTRATOR.md
└── skills/
    ├── PROJECT-MANAGER.md
    ├── PRODUCT-MANAGER.md
    ├── BUSINESS-ANALYST.md
    ├── MARKETING-MANAGER.md
    ├── UX-UI-DESIGNER.md
    ├── TECHNICAL-WRITER.md
    ├── BACKEND-DEVELOPER.md
    ├── MICROSERVICES-ARCHITECT.md
    ├── SOFTWARE-ARCHITECT.md
    ├── DATA-ARCHITECT.md
    ├── FRONTEND-DEVELOPER.md
    ├── MOBILE-DEVELOPER.md
    ├── FULL-STACK-DEVELOPER.md
    ├── DEVOPS-ENGINEER.md
    ├── SYSTEM-ADMINISTRATOR.md
    ├── SECURITY-TESTER.md
    ├── SECURITY-ENGINEER.md
    └── DATA-ANALYST.md
```

## Autonomous Agent Model

Every role skill includes a standard contract:

- `triggers`
- `inputs`
- `outputs`
- `depends_on`
- `handoff_to`
- `can_decide`
- `must_escalate`
- `done_when`

The common runtime defines task states:

```text
INTAKE -> DISCOVERY -> READY -> IN_PROGRESS
       -> REVIEW -> VALIDATION -> DONE
```

Tasks may enter `BLOCKED` or `CANCELLED` when appropriate.

## How To Use

For an end-to-end software project:

1. Load `core/AGENT-RUNTIME.md`.
2. Load `core/ORCHESTRATION.md`.
3. Load `orchestrators/SOFTWARE-PROJECT-ORCHESTRATOR.md`.
4. Select only the role skills required for the work.
5. Execute work using the task lifecycle and quality gates.
6. Transfer work using the standard handoff protocol.
7. Do not mark work complete until its `done_when` contract is satisfied.

For a single-role task, load the relevant file in `skills/` together with the core runtime rules.

## Design Principles

- Objective before activity
- Evidence before assumption
- Explicit authority boundaries
- Stateful task execution
- Reversible actions where possible
- Role-to-role handoff instead of context loss
- Quality gates before completion
- Tool output and runtime state over stale assumptions
- Autonomous execution within defined authority
- Explicit escalation for high-impact decisions

## Scope

NoyaSkillSet currently contains 18 professional role skills covering product, project management, analysis, design, architecture, development, infrastructure, security, marketing, documentation and data analysis.

## Version

Autonomous Agent Contract: v1  
Role Skill Contract Version: 2.0.0
