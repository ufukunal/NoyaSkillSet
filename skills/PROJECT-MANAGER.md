# PROJE YÖNETICISI (PROJECT MANAGER) - KAPSAMLI SKILL

## İÇİNDEKİLER
1. [Özet](#özet)
2. [Temel Sorumluluklar](#temel-sorumluluklar)
3. [Proje Başlatma](#proje-başlatma)
4. [Planlama](#planlama)
5. [Yürütme](#yürütme)
6. [İzleme ve Kontrol](#izleme-ve-kontrol)
7. [Stakeholder Yönetimi](#stakeholder-yönetimi)
8. [Kapalı](#kapalı)
9. [Araçlar](#araçlar)
10. [Yaygın Hatalar](#yaygın-hatalar)

---

## ÖZET

Proje Yöneticisi, yazılım projelerinin başından sonuna kadar tüm aşamaları koordine eder. İnsan, kaynak, zaman, bütçe, scope ve risk yönetiminden sorumludur. Başarılı proje yönetimi, proje hedeflerine ulaşmak için temel unsurdur.

### PM'in İlk Günü
- Sponsor'la tanışma
- Takımla tanışma
- Proje ortamını anla
- Stakeholder'ları tanı
- İlk 30 günün planını yap

---

## TEMEL SORUMLULUKLAR

### 1. Proje Başlatma (Initiation)
- Business case analizi
- Project Charter oluşturma
- Stakeholder identification
- Initial scope tanımlama
- Kick-off meeting planlama

### 2. Planlama (Planning)
- WBS (Work Breakdown Structure) oluşturma
- Detailed schedule oluşturma
- Budget detaylı tahmin
- Risk management planning
- Communication plan
- Resource planning

### 3. Yürütme (Execution)
- Team koordinasyonu
- Daily standupları facilitate etme
- Scope implementasyonu
- Quality assurance oversight
- Stakeholder engagement
- Change management

### 4. İzleme & Kontrol (Monitoring & Controlling)
- Schedule tracking (Earned Value)
- Budget tracking
- Quality metrics
- Risk monitoring
- Issue management
- Scope control

### 5. Kapanış (Closure)
- Final deliverable handoff
- Lessons learned workshop
- Team release
- Project archive
- Success celebration

---

## PROJE BAŞLATMA

### Phase 1.1: Business Case Analizi

**BUSINESS CASE TEMPLATE - CHARTER ÖNCESİ**

```
BUSINESS CASE ANALYSIS
======================

1. PROBLEM/OPPORTUNITY
   Nedir? Finansal impact? Neden şimdi?
   
   Örnek:
   "Mevcut booking sistemi manual → %15 hata oranı
    Sonuç: Ayda 50+ booking iptal, $50K kayıp
    Çözüm: Otomatik sistem → %98 başarı oranı hedefi"

2. PROPOSED SOLUTION
   Çözüm nedir? Nasıl çalışır? Neden bu?
   
   Örnek:
   "Web + Mobile otomatik booking platformu
    Real-time availability, online payment, confirmations
    Tech: React, Node.js, PostgreSQL"

3. BENEFITS (Tangible & Intangible)
   
   Finansal:
   - Revenue recovery: $200K/year
   - Cost reduction: 30% (operational)
   - ROI: 1.3x
   
   Operasyonel:
   - Booking success: 98% (vs 85%)
   - Processing time: 2 min (vs 20 min manual)
   
   Customer:
   - Satisfaction: 4.5/5 (vs 3.2/5)
   - Adoption: 70% month 1

4. COSTS
   - Development: $100K
   - Infrastructure: $20K/year
   - Maintenance: $30K/year
   - Training: $5K
   
   Total Year 1: $155K

5. RISKS & ASSUMPTIONS
   - High: Scope creep - Mitigation: Change control
   - Med: Key person leaves - Mitigation: Cross-training
   - Low: Tech issues - Mitigation: Early prototyping

6. TIMELINE
   22 weeks total
   - Planning: 2 weeks
   - Development: 10 weeks
   - Testing: 3 weeks
   - Deployment: 2 weeks
   - Contingency: 3 weeks

7. RECOMMENDATION
   ✓ PROCEED
   Rationale: Strong ROI, strategic alignment, manageable risks
   Conditions: Scope locked, budget approved, sponsor committed
```

### Phase 1.2: Project Charter Oluşturma

**PROJECT CHARTER = PROJEYÜ RESMEN BAŞLATAN DOKUMAN**

```
PROJECT CHARTER
===============

Project Title: Charter Booking Management System
Project Code: SEAAPP-2024-001
Charter Date: January 15, 2024
Sponsor: [CEO/CTO Name]
Project Manager: [Your Name]

─── SECTION 1: PURPOSE & OBJECTIVES ───

Business Purpose:
"Mevcut manuel charter booking işlemini otomatikleştirerek
operasyonel verimliliği %40 artırmak, müşteri memnuniyetini
iyileştirmek ve $200K yıllık revenue recovery sağlamak"

Strategic Alignment:
□ Digital transformation initiative
□ Customer experience improvement
□ Operational efficiency goals
□ Market expansion

SMART Objectives:
1. Implement automated booking system (Web + Mobile)
2. Achieve 95% booking success rate (vs 85% current)
3. Reduce booking time to < 2 minutes
4. Achieve 99.5% system uptime
5. GDPR compliant data handling
6. Support 10,000 concurrent users

─── SECTION 2: SCOPE ───

INCLUSIONS (Yapılacaklar):
✓ Web application (React)
✓ Mobile app (Flutter - iOS & Android)
✓ Backend API (Node.js)
✓ Real-time vessel availability
✓ Online payment integration (Stripe)
✓ Admin dashboard
✓ Email/SMS notifications
✓ Basic analytics
✓ User documentation
✓ Ops runbook

EXCLUSIONS (Yapılmayacaklar):
✗ Advanced AI recommendations (Phase 2)
✗ Multi-language support (Phase 2)
✗ CRM integration (Phase 2)
✗ Captain mobile app (Phase 2)
✗ Custom reports (Phase 2)

High-Level Requirements:
- User authentication (OAuth 2.0)
- Charter search & booking
- Real-time availability checking
- Online payment (Stripe)
- Booking management (modify, cancel)
- Admin panel for vessel management
- Email confirmations
- Performance: < 2s page load
- Mobile responsive design

─── SECTION 3: DELIVERABLES ───

Phase 1 (Planning & Design):
□ Requirements Document
□ Architecture Design
□ Database Schema
□ UI/UX Mockups
□ Project Plan

Phase 2 (Development):
□ Backend API (tested)
□ Web Application
□ Mobile Applications
□ Admin Dashboard
□ Integration Tests

Phase 3 (Testing & UAT):
□ Test Reports
□ UAT Sign-off
□ Security Audit Report
□ Performance Report

Phase 4 (Deployment):
□ Production Deployment
□ User Guide
□ Admin Guide
□ Training Materials
□ Go-live Checklist

─── SECTION 4: SUCCESS CRITERIA ───

Technical Metrics:
- Code coverage: > 80%
- All tests pass (unit, integration, E2E)
- Security audit: PASS
- Performance: Page load < 2s
- Uptime: 99.5% in production

Business Metrics:
- Booking success rate: > 95%
- Customer satisfaction: > 4.5/5
- User adoption: > 70% in month 1
- System uptime: > 99.5%

Project Metrics:
- On schedule (22 weeks ± 1 week)
- On budget ($155K ± 10%)
- Stakeholder satisfaction: > 4/5
- Zero critical bugs at launch

─── SECTION 5: CONSTRAINTS ───

Time Constraint:
- Deadline: Q2 2024 (22 weeks)
- No extensions beyond Week 24 acceptable

Budget Constraint:
- Total Budget: $155,000
- Labor: $100K
- Infrastructure: $20K
- Contingency: $25K
- Over-budget requests require sponsor approval

Resource Constraint:
- Max 8 team members
- Key people locked in
- CTO approval for tech decisions

Technical Constraints:
- Must be cloud-deployable
- Use open-source where possible
- GDPR compliant
- PCI-DSS for payments
- No vendor lock-in if possible

─── SECTION 6: ASSUMPTIONS ───

✓ Business requirements stable (no major changes)
✓ Team members 100% available
✓ Third-party APIs (Stripe, email) reliable
✓ Budget approved and accessible
✓ Sponsor committed throughout
✓ No major organizational changes during project
✓ Technology choices appropriate
✓ Stakeholder cooperation assured

If any assumption breaks:
1. Notify PM immediately
2. Assess impact
3. Adjust plan if needed
4. Sponsor approval for changes

─── SECTION 7: KNOWN RISKS ───

Risk 1: Scope Creep
Probability: HIGH (80%) | Impact: MEDIUM (6/10)
Mitigation: Strict change control, frozen requirements
Owner: PM | Monitor: Weekly

Risk 2: Key Developer Leaves
Probability: LOW (15%) | Impact: HIGH (8/10)
Mitigation: Cross-training, documentation
Owner: Tech Lead | Monitor: Bi-weekly

Risk 3: Database Performance Issues
Probability: MEDIUM (25%) | Impact: HIGH (8/10)
Mitigation: Early load testing, optimization buffer
Owner: DBA | Monitor: Weekly

Risk 4: Third-party API Failures
Probability: LOW (10%) | Impact: MEDIUM (7/10)
Mitigation: Fallback mechanisms, comprehensive testing
Owner: Backend Lead | Monitor: As needed

Risk 5: Security Vulnerability Discovered
Probability: LOW (10%) | Impact: CRITICAL (9/10)
Mitigation: Regular security reviews, penetration testing
Owner: Security Officer | Monitor: Monthly

─── SECTION 8: ORGANIZATION ───

Project Sponsor: [Name, Title]
Role: Final decision-maker, budget approval, escalation
Contact: [email, phone]

Project Manager: [Name, Title]
Role: Day-to-day management, scope/time/cost control
Contact: [email, phone]

Technical Lead/Architect: [Name, Title]
Role: Technical decisions, architecture, code quality
Contact: [email, phone]

Product Owner: [Name, Title]
Role: Requirements, feature acceptance, prioritization
Contact: [email, phone]

Scrum Master: [Name, Title] (if Agile)
Role: Process facilitation, blocker removal
Contact: [email, phone]

Development Team:
- 3 Backend Developers
- 2 Frontend Developers
- 1 Mobile Developer
- 1 QA Engineer
- 1 UX/UI Designer (shared)

─── SECTION 9: COMMUNICATION PLAN ───

Sponsor Updates:
- Frequency: Monthly (1st Friday)
- Format: 1-page executive summary + 30-min meeting
- Content: Status, risks, decisions needed

Steering Committee:
- Frequency: Bi-weekly (Wednesdays 10am)
- Format: Detailed report + discussion
- Attendees: Sponsor, VP Product, CTO, Finance Dir, PM

Development Team:
- Daily: 15-min standup (9:00 AM)
- Weekly: 1-hour retrospective + planning
- Weekly: 2-hour technical review

Stakeholders:
- Bi-weekly demos (Thursday 2pm)
- Monthly newsletter
- Ad-hoc as needed

─── SECTION 10: APPROVAL ───

This charter is approved and authorized by:

Sponsor Name: ________________________
Signature: ________________________
Date: ________________________
Title: ________________________

PMO Director (if applicable):
Name: ________________________
Signature: ________________________
Date: ________________________

Project Manager:
Name: ________________________
Signature: ________________________
Date: ________________________
```

### Phase 1.3: Stakeholder Management Setup

**STAKEHOLDER REGISTER & ENGAGEMENT STRATEGY**

```
STAKEHOLDER REGISTER
====================

ID | Name | Title | Org | Interest | Power | Strategy | Frequency
───────────────────────────────────────────────────────────────────
S1 | CEO | CEO | Exec | HIGH | HIGH | Manage | Monthly
S2 | VP Prod | VP Prod | Product | HIGH | HIGH | Manage | Bi-weekly
S3 | CTO | CTO | Tech | HIGH | HIGH | Manage | 2-3x/week
S4 | Ops Mgr | Ops Manager | Ops | HIGH | MED | Satisfy | Weekly
S5 | Finance | Finance Dir | Finance | MED | MED | Satisfy | Monthly
S6 | Captain | Vessel Captain | Ops | MED | LOW | Inform | Monthly
S7 | Agent | Booking Agent | Support | HIGH | LOW | Satisfy | Bi-weekly
S8 | Cust Svc | Cust Svc Mgr | Support | MED | LOW | Inform | Monthly

ENGAGEMENT STRATEGIES

CEO:
- What they care about: ROI, timeline, no surprises
- How to engage: Monthly exec brief, immediate escalation
- Red flags to watch: Budget overrun, schedule slip
- When to escalate: Critical risk, sponsor decision needed
- Frequency: Monthly meeting + immediate escalation

VP Product:
- What they care about: Feature quality, user adoption
- How to engage: Bi-weekly demos, feedback sessions
- Red flags to watch: Quality issues, user feedback negative
- When to escalate: Feature scope change, major delay
- Frequency: Bi-weekly + on-demand

CTO:
- What they care about: Technical excellence, architecture
- How to engage: Technical deep-dives, code quality metrics
- Red flags to watch: Technical debt, performance issues
- When to escalate: Architecture decisions, tech risks
- Frequency: 2-3x weekly

Operations Manager:
- What they care about: Ease of use, training readiness
- How to engage: Regular demos, change management
- Red flags to watch: Usability issues, adoption concerns
- When to escalate: Major workflow changes
- Frequency: Weekly + UAT participation

Finance Director:
- What they care about: Budget adherence, ROI tracking
- How to engage: Monthly budget reviews, variance reports
- Red flags to watch: Budget overruns, spending patterns
- When to escalate: Variance > 5%, major cost change
- Frequency: Monthly + variance alerts

Booking Agents (End Users):
- What they care about: Ease of use, speed, support
- How to engage: User testing, early feedback, training
- Red flags to watch: Usability issues, adoption resistance
- When to escalate: Major UX problems found
- Frequency: Bi-weekly UAT + monthly updates
```

---

## PLANLAMA (PLANNING)

### Phase 2.1: Detaylı Scope Definition & WBS

**WORK BREAKDOWN STRUCTURE**

```
PROJECT: Charter Booking System (22 weeks, $155K)

1.0 INITIATION & PLANNING (2 weeks, Week 1-2)
   1.1 Requirements Gathering (Week 1)
       - Stakeholder interviews
       - Use case development
       - User story creation
       Deliverable: Requirements document (100+ pages)
   
   1.2 Architecture & Design (Week 1-2)
       - System architecture
       - Technology selection
       - Database design
       Deliverable: Architecture document + diagrams
   
   1.3 Project Planning (Week 2)
       - Schedule creation
       - Budget breakdown
       - Risk assessment
       Deliverable: Project plan + templates

2.0 DESIGN PHASE (3 weeks, Week 2-4)
   2.1 UI/UX Design (Week 2-3)
       - Wireframes
       - High-fidelity mockups
       - Interaction design
       Deliverable: Design files in Figma
   
   2.2 Database Design (Week 2-3)
       - Schema finalization
       - Indexing strategy
       - Migration planning
       Deliverable: Database schema document
   
   2.3 API Design (Week 3-4)
       - Endpoint specifications
       - Request/response schemas
       - Error handling
       Deliverable: OpenAPI specification

3.0 DEVELOPMENT (10 weeks, Week 3-12)
   3.1 Backend Development (8 weeks)
       3.1.1 API Layer (Week 3-5, 3 weeks)
             - User authentication
             - Charter endpoints
             - Vessel endpoints
             Deliverable: Working API (tested)
       
       3.1.2 Database Layer (Week 4-5, 2 weeks)
             - Schema creation
             - Migrations
             - Connection management
             Deliverable: Production database setup
       
       3.1.3 Business Logic (Week 5-7, 3 weeks)
             - Charter logic
             - Payment integration
             - Notifications
             Deliverable: Complete backend (tested)
       
       3.1.4 Testing (Week 8, 1 week)
             - Unit tests
             - Integration tests
             Deliverable: Test reports
   
   3.2 Frontend Development (7 weeks)
       3.2.1 Setup (Week 3-4, 1 week)
             - React setup
             - State management
             - Routing
             Deliverable: Project initialized
       
       3.2.2 Components (Week 4-6, 3 weeks)
             - Shared components
             - Forms
             - Pages
             Deliverable: Reusable components
       
       3.2.3 Integration (Week 6-8, 2 weeks)
             - API integration
             - State management
             - Error handling
             Deliverable: Fully functional UI
       
       3.2.4 Testing (Week 8, 1 week)
             - Unit tests
             - Component tests
             Deliverable: Test reports
   
   3.3 Mobile Development (7 weeks)
       3.3.1 Setup (Week 3-4, 1 week)
             - Flutter environment
             - State management
             Deliverable: Project initialized
       
       3.3.2 Features (Week 4-7, 4 weeks)
             - Screens
             - Navigation
             - API calls
             Deliverable: Working app
       
       3.3.3 Testing (Week 7-8, 2 weeks)
             - Device testing
             - Performance testing
             Deliverable: Test reports

4.0 TESTING & QA (3 weeks, Week 9-11)
   4.1 System Testing (Week 9-10, 2 weeks)
       - Functional testing
       - Regression testing
       - Load testing
       Deliverable: Test reports
   
   4.2 UAT (Week 10-11, 2 weeks)
       - User acceptance testing
       - Feedback collection
       - Sign-off
       Deliverable: UAT report + sign-off

5.0 DEPLOYMENT (2 weeks, Week 12-13)
   5.1 Pre-Production (Week 12, 1 week)
       - Infrastructure setup
       - Database migration
       - Security hardening
       Deliverable: Production environment ready
   
   5.2 Go-Live (Week 13, 1 week)
       - Staging deploy
       - Production deploy
       - Monitoring setup
       Deliverable: Live system

6.0 CLOSURE (1 week, Week 14)
   6.1 Stabilization
       - Issue monitoring
       - Performance tuning
       - User support
   
   6.2 Documentation
       - User guide
       - Admin guide
       - Runbook
   
   6.3 Lessons Learned
       - Retrospective
       - Recommendations
       - Knowledge capture

PROJECT BUFFER: Week 15-22 (8 weeks)
- Used for delays, complexities, unknowns
- Target: 0 usage (on-time delivery)
- Contingency for risks
```

### Phase 2.2: Schedule (Gantt Chart)

**22-WEEK TIMELINE**

```
CRITICAL PATH:
Planning (2) → Design (3) → Backend (8) → Testing (3) → Deployment (2)
Total: 18 weeks + 4 weeks buffer = 22 weeks

DETAILED TIMELINE:

Week 1-2:   Planning & Requirements ████
Week 2-4:   Design (parallel with Dev start) ████████
Week 3-12:  Development ████████████████████
            ├─ Backend: Week 3-8 ████████████
            ├─ Frontend: Week 3-9 ███████████
            └─ Mobile: Week 3-10 ████████████
Week 9-11:  Testing ██████
Week 12-13: Deployment ████
Week 14:    Closure ██

CRITICAL MILESTONES:

Week 1: Kick-off ✓
Week 2: Requirements approved ✓
Week 4: Design approved ✓
Week 5: Backend API MVP ✓
Week 8: Backend complete ✓
Week 9: Testing begins ✓
Week 11: UAT complete & sign-off ✓
Week 13: Go-live ✓
Week 14: Post-launch monitoring ✓
Week 22: Project closed ✓

SCHEDULE RISK MANAGEMENT:
- Most risky: Database performance (Week 8) → Early load test
- Backend delays impact: Frontend integration → Monitor closely
- Testing compressed? → QA involved in development phase
- Deployment delays? → Infrastructure pre-readiness at Week 10
```

### Phase 2.3: Budget (Detailed Estimation)

**BOTTOM-UP COSTING**

```
BUDGET BREAKDOWN: $155,000

1. PERSONNEL COSTS: ~$100,000 (65%)
   
   Management:
   - PM: 22 weeks × 40 hrs/week × $125/hr = $109,000
     (Includes: planning, meetings, admin, reporting)
   
   Architecture & Leadership:
   - Tech Lead: 22 weeks × 35 hrs/week × $130/hr = $99,800
   - Architect involvement: 4 weeks × 30 hrs × $150/hr = $18,000
   
   Development:
   - Backend Lead: 10 weeks × 35 hrs × $120/hr = $42,000
   - Backend Dev 1: 10 weeks × 35 hrs × $80/hr = $28,000
   - Backend Dev 2: 10 weeks × 35 hrs × $80/hr = $28,000
   - Frontend Dev: 9 weeks × 35 hrs × $80/hr = $25,200
   - Mobile Dev: 7 weeks × 35 hrs × $80/hr = $19,600
   
   Testing & QA:
   - QA Lead: 3 weeks × 30 hrs × $100/hr = $9,000
   - QA Tester: 4 weeks × 35 hrs × $70/hr = $9,800
   
   Design:
   - UX/UI Designer: 4 weeks × 30 hrs × $110/hr = $13,200
   
   ** SUBTOTAL LABOR: ~$402,600
   ** PROBLEM: Way over budget!
   
   OPTIMIZATION - Use mixed team:
   
   Internal:
   - PM: 22 weeks × $125/hr × 35 hrs = $95,875
   - Tech Lead: 22 weeks × $130/hr × 35 hrs = $99,800
   
   Offshore/Lower cost:
   - Backend devs (3): $25K each = $75K (4 months)
   - Frontend dev: $20K (3 months)
   - Mobile dev: $15K (3 months)
   - QA: $10K (2 months)
   - Designer: $8K (1 month)
   
   TOTAL PERSONNEL: $98,675 → $100,000 (with buffer)

2. INFRASTRUCTURE & TOOLS: ~$8,000 (5%)
   
   Cloud (AWS):
   - RDS Database: $500/month × 4 months = $2,000
   - App hosting (EC2): $400/month × 4 months = $1,600
   - CDN: $200/month × 4 months = $800
   - S3/Services: $400/month × 4 months = $1,600
   
   Development Tools:
   - GitHub/Jira: $20/user/month × 8 users × 4 months = $640
   - Figma: $12/user/month × 2 users × 4 months = $96
   - Slack: $12.50/user/month × 8 users × 4 months = $400
   
   Third-party Services:
   - Stripe (processing): 2.9% + $0.30 per transaction
     Estimated: $2,000 (development + testing)
   - SendGrid (email): $20/month × 4 months = $80
   - Twilio (SMS): $50/month × 4 months = $200
   
   TOTAL INFRASTRUCTURE: $8,416 → $8,000 (trim to budget)

3. TRAINING & DOCUMENTATION: ~$5,000 (3%)
   
   - User guide creation: 40 hrs × $80/hr = $3,200
   - Admin guide: 30 hrs × $80/hr = $2,400
   - Video training: $1,500
   - In-person training: $2,000
   
   TOTAL (trimmed): $5,000

4. CONTINGENCY & BUFFER: ~$25,000 (16%)
   
   For unexpected:
   - Schedule delays
   - Technical complexities
   - Scope changes (if approved)
   - Team absences
   - Tool/infrastructure issues
   
   Contingency: 15% of base ($155K - $25K contingency) × 15% ≈ $19,500
   Additional buffer: $5,500
   
   TOTAL CONTINGENCY: $25,000

5. INDIRECT/ADMIN COSTS: ~$2,000 (1%)
   
   - Office space: $1,000
   - Miscellaneous: $1,000
   
   TOTAL INDIRECT: $2,000

─────────────────────────────────────────────
TOTAL PROJECT BUDGET: $155,000
─────────────────────────────────────────────

Personnel:        $100,000 (64.5%)
Infrastructure:     $8,000 (5.2%)
Training:           $5,000 (3.2%)
Contingency:       $25,000 (16.1%)
Indirect:           $2,000 (1.3%)

BURN RATE:
- Expected weekly: ~$7,000-8,000
- Total 22 weeks: $154,000-176,000
- Target: $155,000
- Margin: $0-1,000

⚠️ TIGHT BUDGET - Monitor weekly!
```

### Phase 2.4: Risk Management Plan

**COMPREHENSIVE RISK REGISTER**

```
RISK IDENTIFICATION & MANAGEMENT
==================================

RISK REGISTER:

ID   | Risk | Prob | Impact | Score | Owner | Mitigation | Status
─────┼──────┼──────┼────────┼───────┼──────┼───────────┼─────────
R001 | Scope Creep | 80% | 6/10 | 4.8 | PM | Change control | ACTIVE
R002 | Key Dev Leaves | 20% | 8/10 | 1.6 | HR | Training | MONITOR
R003 | DB Complexity | 40% | 8/10 | 3.2 | DBA | Early testing | ACTIVE
R004 | API Reliability | 15% | 7/10 | 1.05 | Backend | Fallback | LOW
R005 | Security Issue | 20% | 9/10 | 1.8 | Sec | Early review | ACTIVE
R006 | Testing Time Short | 50% | 7/10 | 3.5 | PM | Early testing | ACTIVE
R007 | Budget Overrun | 70% | 8/10 | 5.6 | Finance | Tracking | ACTIVE
R008 | Stakeholder Misalign | 40% | 6/10 | 2.4 | PM | Communication | MONITOR

DETAILED RISK MANAGEMENT:

Risk R001: Scope Creep (HIGHEST RISK)
─────────────────────────────────────
Probability: 80% (very likely)
Impact: 6/10 (medium - 3-4 week delay)
Score: 4.8 (HIGH)
Owner: Project Manager

Description:
"Stakeholders request additional features during development.
'Nice-to-haves' added to scope. Requirements evolve."

Trigger Events:
- Stakeholder mentions new feature
- "Quick" requests received
- Scope meetings increase
- Requirements document rewritten

Response Strategy: AVOID + CONTROL
1. Avoid: Clear scope upfront
   - Detailed requirements before dev
   - Scope freeze at week 2
   - Sign-off required
   
2. Control: Change control gate
   - Change Request Form required
   - Impact analysis done
   - Sponsor approval needed
   - Schedule/budget adjusted
   
3. Monitor:
   - Weekly scope review
   - Change request log maintained
   - Steering committee update

Contingency:
- 20% schedule buffer for approved changes
- Phase 2 for deferred changes
- Say "NO" to out-of-scope items
- Document decisions


Risk R003: Database Complexity (TECHNICAL RISK)
──────────────────────────────────────────────
Probability: 40%
Impact: 8/10 (high - 4-6 week delay)
Score: 3.2 (MEDIUM-HIGH)
Owner: Database Administrator

Description:
"Real-time vessel tracking + charter queries complex.
Query performance insufficient. Design iteration needed."

Trigger Events:
- Load testing shows slow queries
- Concurrent user limits hit
- Index strategy ineffective
- Migration fails

Response Strategy: MITIGATE
1. Early action:
   - POC on complex queries (Week 2)
   - Index strategy planned (Week 3)
   - Load test script ready (Week 3)
   
2. Early detection:
   - Performance baseline Week 6
   - Load test Week 8
   - Optimization Week 9
   
3. Buffer:
   - 1 week optimization buffer in schedule
   - Defer Phase 2 features if needed
   
4. Team:
   - Senior DBA on team
   - Query optimization expertise
   - NoSQL alternative available

Contingency:
- Denormalize data if needed
- Cache layer (Redis) if needed
- Defer some features
- Hire specialized DBA


Risk R007: Budget Overrun (FINANCIAL RISK)
──────────────────────────────────────────
Probability: 70% (likely)
Impact: 8/10 (high - project viability)
Score: 5.6 (HIGH - HIGHEST FINANCIAL RISK)
Owner: PM + Finance Director

Description:
"Project labor-intensive. Complexity underestimated.
Budget insufficient for 8-person team at market rates."

Trigger Events:
- Weekly burn rate exceeds $7,500
- Contingency being used Week 8
- Scope change increases hours
- Team turnover increases costs

Response Strategy: MITIGATE + MONITOR
1. Prevention:
   - Tight scope control
   - Efficiency improvements
   - Early risk detection
   - Resource optimization
   
2. Monitoring:
   - Weekly budget reviews
   - Burn rate tracked
   - Forecasts updated
   - Red flags escalated
   
3. Options if overrunning:
   - Reduce scope (must have vs nice-to-have)
   - Extend timeline (spread costs)
   - Add resources (if additional budget)
   - Improve efficiency (overtime = bad idea)
   - Phase 2 approval earlier

4. Financial Controls:
   - Budget holder approval for overages
   - Time tracking mandatory
   - Expense approvals
   - Weekly variance analysis

Contingency:
- $25K contingency reserved
- Sponsor pre-approval for $5K overruns
- Phase 2 to absorb deferred items

──────────────────────────────────────

OVERALL RISK EXPOSURE:

HIGH RISKS (Score > 4):
- Scope Creep (4.8) ← BIGGEST RISK
- Budget Overrun (5.6) ← FINANCIAL RISK
Action: Daily/weekly monitoring, tight controls

MEDIUM RISKS (Score 2-4):
- Database Complexity (3.2)
- Testing Time (3.5)
- Stakeholder Misalignment (2.4)
Action: Bi-weekly review, proactive mitigation

LOW RISKS (Score < 2):
- Key person leaves (1.6)
- API reliability (1.05)
- Security issues (1.8)
Action: Quarterly review, monitor for triggers

RISK MANAGEMENT PROCESS:

1. IDENTIFY: Every Friday 15-min risk chat
2. LOG: Jira risk tracking
3. ANALYZE: Probability × Impact score
4. RESPOND: Prevention, mitigation, contingency
5. MONITOR: Weekly update, escalate if triggers
6. CONTROL: Take action, verify effectiveness
7. CLOSE: When risk resolved or accepted

Risk Escalation:
- HIGH risk + trigger: Daily PM update
- MEDIUM risk + trigger: PM aware + plan action
- Sponsor notification: If Score > 3.5
- Team notify: If impacts their work
```

---

## YÜRÜTME (EXECUTION)

### Phase 3.1: Daily Standups

**15-MINUTE DAILY SYNCHRONIZATION**

```
DAILY STANDUP MEETING
====================

Time: 9:00 AM Daily
Duration: 15 minutes (enforce!)
Location: Slack #standup + optional in-person
Moderator: Scrum Master or PM

STANDUP FORMAT:

Each person: 2-3 minutes max

1. ✅ What did you complete YESTERDAY?
   - Specific tasks/PRs merged   - Tests written/passing
   - Deliverables done
   
2. 🎯 What will you WORK ON TODAY?
   - Next task/epic
   - Estimated hours
   - Blockers expected?
   
3. 🚧 Any BLOCKERS?
   - Issues preventing progress
   - Help needed?
   - Who to unblock?

REAL-WORLD EXAMPLE:

PM: "Good morning team, 15-minute standup. Let's go."

Backend Lead:
"Yesterday: Completed user authentication API, all tests green, 
PR merged. Today: Working on charter creation endpoint, 4-6 hours. 
No blockers."

Backend Dev 1:
"Yesterday: Finished vessel availability check (70% complete). 
Today: Complete implementation and write tests. Blocker: Need 
clarification on time zone handling for date calculations."

Backend Dev 2:
"Yesterday: Database migrations and connection pooling setup. 
Today: Integration with auth API. No blockers, ready to start."

Frontend Lead:
"Yesterday: Set up React project, created component structure. 
Today: Start building UI components. Blocker: Need final API 
specs from backend (waiting on vessel endpoint)."

Frontend Dev:
"Yesterday: Created authentication forms. Today: Integrate with 
backend auth API. Blocker: None right now."

Mobile Dev:
"Yesterday: Flutter environment setup and initial screens. 
Today: Implement login flow. No blockers."

QA Lead:
"Yesterday: Created test plan, set up test environment. 
Today: Review backend code for testability, prepare test cases. 
No blockers."

PM Summary:
"Thanks team. So we have:
 ✅ Auth API done
 🟡 Charter API in progress (on track)
 🟡 Vessel endpoint needs API spec - Backend Lead, let's sync 
    after this (15 min)
 ✅ Frontend setup solid
 ✅ Mobile ready to start
 ✅ Testing prepared
 
 No major blockers. Continue momentum. Let's exceed yesterday's 
 delivery. Next standup: tomorrow 9am."

BLOCKER RESOLUTION:
- If blocked: Document in Jira immediately
- PM notifies owner: "Hey Dev3, Dev1 blocked on X. Can you help?"
- Target resolution: Same day
- If not resolved: Escalate to Tech Lead
- If still not resolved: PM finds workaround or removes blocker

STANDUP METRICS:
- Block percentage: Target < 10% (most devs unblocked)
- Resolution time: Target < 4 hours
- Attendance: Target 100%
- Brevity: Target 15 minutes total
```

### Phase 3.2: Weekly Status Reports

**STAKEHOLDER COMMUNICATION**

```
WEEKLY STATUS REPORT TEMPLATE
=============================

Report for week ending: Friday, [Date]
Distribution: Sponsor, Steering Committee, Project Team

EXECUTIVE SUMMARY (1 paragraph)

On track. Completed 40% of development work this week. 
Charter API endpoints functional, frontend integration starting. 
One medium blocker (database migration) resolved. On schedule 
and on budget. No escalations needed.

────────────────────────────────────────

PROJECT HEALTH DASHBOARD

Overall Status: 🟢 ON TRACK
Schedule:      🟢 ON TRACK (+2 days ahead)
Budget:        🟢 ON TRACK (89% of planned burn)
Quality:       🟢 ON TRACK (test coverage: 78%)
Risks:         🟡 MEDIUM (1 active risk)

────────────────────────────────────────

KEY METRICS

Task Completion:
- Planned this week: 35 tasks
- Completed: 32 tasks (91%)
- Completed late: 2 tasks (6%)
- Blocked: 1 task
- Status: GOOD

Scope Tracking:
- Scope baseline: 100 items
- Completed: 42 items (42%)
- In progress: 35 items
- Not started: 23 items

Schedule:
- Planned progress: 45% by Week 5
- Actual progress: 47%
- Variance: +2% (ahead)
- Burn-down chart: On track for Week 22 delivery

Budget:
- Planned spend YTD (Weeks 1-5): $39,000
- Actual spend YTD: $38,200
- Variance: -$800 (0.2% under)
- Forecast: $151,000 (within $155K budget)

Quality Metrics:
- Code coverage: 78% (target: 80% by Week 8)
- Unit tests: 180 tests, 98% passing
- Bug rate: 3 medium bugs found/fixed
- Code review: 95% of code reviewed

Team Velocity (if Agile):
- Sprint 1 (Week 1-2): 24 story points completed
- Sprint 2 (Week 3-4): 28 story points completed
- Sprint 3 (Week 5-6 in progress): 30 story points (projected)
- Trend: Velocity increasing (good sign)

────────────────────────────────────────

WORK COMPLETED THIS WEEK ✅

Backend Development:
✅ User authentication API (login, register, JWT)
✅ Charter endpoints (GET, POST, GET by ID)
✅ Vessel endpoints (GET all, GET by ID)
✅ Error handling & validation
✅ 60+ unit tests (all passing)

Frontend Development:
✅ React project setup
✅ Authentication forms (login, register)
✅ Component library initialized
✅ Styling framework (Tailwind) configured
✅ 12 UI components created

Database:
✅ Users table schema
✅ Charters table schema
✅ Vessels table schema
✅ Initial migrations
✅ Connection pooling setup

Testing:
✅ Test plan finalized
✅ Backend test suite initialized
✅ Test data generators created
✅ CI/CD integration tests setup

Infrastructure:
✅ AWS RDS database provisioned
✅ EC2 instances ready
✅ GitHub repository organized
✅ Jira project structured
✅ Slack channels created

────────────────────────────────────────

WORK IN PROGRESS 🟡

Backend:
🟡 Payment integration with Stripe (40%)
🟡 Real-time vessel availability checking (60%)
🟡 Notification service (50%)

Frontend:
🟡 API integration layer (30%)
🟡 Booking form UI (20%)
🟡 Dashboard UI (10%)

Mobile:
🟡 Login screen (80%)
🟡 Navigation structure (40%)

────────────────────────────────────────

UPCOMING NEXT WEEK 📅

- Complete payment integration
- Start frontend API integration
- Vessel tracking features
- Load testing preparation
- Steering committee demo

────────────────────────────────────────

BLOCKERS & ISSUES 🚧

RESOLVED THIS WEEK ✅
✅ Database migration tool selection
   Issue: Team wanted Alembic vs Flyway
   Resolution: Chose Alembic (team preference)
   Impact: None

✅ Stripe test credentials
   Issue: Finance needed to send test keys
   Resolution: Received Friday
   Impact: 1-day delay (had buffer)

CURRENT BLOCKERS 🟡
🟡 Docker image optimization
   Issue: Build time 8 minutes (too slow)
   Owner: DevOps engineer
   Target resolution: By Wednesday
   Workaround: Build locally for now
   Impact: 5-10% dev velocity reduction

────────────────────────────────────────

RISKS & ISSUES UPDATE

Active Risks:
🔴 Scope Creep (HIGH - 4.8 score)
   Probability: Still 80%
   Mitigation: Change control gate applied
   New requests: 2 this week (1 approved for Phase 2, 1 deferred)
   Status: Under control

🟡 Database Performance (MEDIUM - 3.2 score)
   Probability: Still 40%
   Mitigation: Planning load test for Week 8
   Early signs: Query times acceptable so far
   Status: Monitoring

🟡 Budget Overrun (HIGH - 5.6 score)
   Probability: Still 70%
   Burn rate: $7,100/week (target: $7,000)
   YTD variance: -$800 (good)
   Status: On track but watch closely

Issues Log:
- 3 issues resolved this week
- 1 issue created (Docker optimization)
- 0 critical issues
- 2 high issues (in progress)
- 3 medium issues (in progress)

────────────────────────────────────────

DECISIONS MADE THIS WEEK ✅

Decision 1: Approve Alembic for database migrations
Owner: Tech Lead
Rationale: Team expertise, Alembic better for complex migrations
Impact: Finalized DB strategy

Decision 2: Defer SMS notifications to Phase 2
Owner: Steering Committee (approved)
Rationale: Not critical for launch, customer feedback important
Impact: Scope protected, 1 week timeline saved

Decision 3: Extend DevOps work to Week 6
Owner: PM + Tech Lead
Rationale: Infrastructure complexity higher than estimated
Impact: +1 week to infrastructure, schedule maintained due to parallelization

────────────────────────────────────────

STAKEHOLDER FEEDBACK

Sponsor (CEO):
"Good progress. Like the pace. Keep scope tight."

VP Product:
"Demos look good. User experience solid. Need mobile earlier
than planned."

CTO:
"Architecture solid. Code quality high. Performance looking good."

Ops Manager:
"Looking forward to testing. Want early access for feedback."

Finance Director:
"Budget tracking good. Like the cost efficiency so far."

────────────────────────────────────────

COMMUNICATIONS ACTIVITIES

Daily Standups: ✅ 5 standups (Mon-Fri, 15 min each)
Weekly Demos: ✅ Demo to VP Product (features working)
Status Updates: ✅ Slack updates posted daily
Risk Reviews: ✅ Weekly risk meeting held
Budget Reviews: ✅ Weekly budget sync done

────────────────────────────────────────

METRICS SUMMARY TABLE

Metric | Target | Actual | Status
────────────────────────────────
Task Completion | 90% | 91% | ✅
Scope Progress | 45% | 47% | ✅
Schedule | On time | +2 days | ✅
Budget | $39K | $38.2K | ✅
Code Coverage | 75% | 78% | ✅
Bug Escape | <5 | 3 | ✅
Team Satisfaction | 4/5 | 4.2/5 | ✅

Overall: EXCELLENT WEEK

────────────────────────────────────────

NEXT WEEK FOCUS

Priorities:
1. Complete payment integration (blocking checkout)
2. Start frontend API integration (critical path)
3. Load testing prep (risk mitigation)
4. Steering committee demo (stakeholder engagement)
5. Security review initial (Week 6 deadline)

────────────────────────────────────────

ATTACHMENTS

- Detailed task log
- Code metrics report
- Budget breakdown
- Risk register (updated)
- Burndown chart
- Team velocity chart
- Code quality report

────────────────────────────────────────

Report Prepared By: [PM Name]
Date: [Friday Date]
Next Report: [Following Friday Date]
Distribution List: [Names]
```

### Phase 3.3: Issue & Change Management

**PROBLEMS & CHANGES**

```
ISSUE LOG & CHANGE CONTROL
===========================

ISSUE TRACKING

Issue Report Template:

ID: ISSUE-001
Title: Docker build time too slow
Status: OPEN
Priority: MEDIUM (affects development speed)
Owner: DevOps Engineer
Reported: Week 5, Monday
Target Resolution: Wednesday (same week)

Description:
"Docker image build takes 8 minutes. Should be < 2 minutes.
Slowing down development iterations. Developers waiting."

Impact:
- Development velocity reduced 10%
- Developer frustration increasing
- CI/CD pipeline slow

Root Cause:
"Dockerfile not optimized. Layer caching not working.
Dependencies duplicated."

Investigation:
"Analyzed Dockerfile. Found: 
1. npm install in every layer
2. All dependencies copied (not just package.json)
3. No caching strategy"

Solution:
"Optimize Dockerfile:
1. Copy package.json first
2. Run npm install early (cached)
3. Copy source code
4. Expected result: < 2 min builds"

Status Updates:
- Mon: Identified issue
- Tue: Root cause analyzed
- Wed: Solution implemented & tested
- Wed: Build time: 1.8 minutes ✅
- Status: RESOLVED

───────────────────────────────────────

CHANGE CONTROL PROCESS

When someone says: "Can we add feature X?"

Step 1: CREATE CHANGE REQUEST

CHANGE REQUEST FORM
═════════════════

CR-ID: CR-001
Date: Week 5, Tuesday
Requested By: VP Product
Title: SMS Notifications for Bookings

Description:
"Send SMS to customer when booking confirmed.
Currently email only. SMS preferred by 70% of customers."

Business Justification:
"Customer satisfaction survey shows strong preference for SMS.
Expected to reduce support inquiries by 15%."

Scope Impact:
"New feature: SMS notification system"

Alignment:
"Aligns with customer experience goals"
"Not in Phase 1 scope (email notifications only)"

───────────────────────────────────────

Step 2: IMPACT ANALYSIS

Technical Impact:
- Add Twilio SMS service integration: 20 hours
- Database: Add sms_preferences table: 5 hours
- Testing SMS flows: 8 hours
- Total: 33 hours (~1 week of 1 dev)

Schedule Impact:
- Current schedule: Week 13 deployment
- If approved: Delay to Week 14 (1 week)
- Alternative: Defer to Phase 2 (no impact)
- Critical path: Not on critical path

Budget Impact:
- Dev time: 33 hours × $80/hr = $2,640
- Twilio service: $50/month × 1 month = $50
- Total: $2,690
- Current budget: $155K (has $5K contingency)
- Status: Affordable

Risk Impact:
- New vendor: Twilio dependency
- Integration complexity: Medium
- Testing scope: Larger

Quality Impact:
- More code = more testing
- Higher complexity
- Potential for bugs

───────────────────────────────────────

Step 3: STEERING COMMITTEE DECISION

Meeting:
Attendees: Sponsor, VP Product, CTO, PM

VP Product: "SMS notifications important. Customer feedback strong."

PM: "Option 1: Add to Phase 1 (1-week delay, +$2,690 cost)
     Option 2: Defer to Phase 2 (no impact, planned feature)
     Option 3: Decline (customer satisfaction risk)"

CTO: "Doable but adds complexity. Twilio reliable though.
      Recommend Phase 2 to maintain Phase 1 quality."

Sponsor: "How critical is SMS? Can we launch without?"

VP Product: "Would be nice but not blocking. Phase 2 is acceptable."

Sponsor: "Decision: DEFER TO PHASE 2
         Rationale: Phase 1 stays on track, quality maintained.
         Implement in Phase 2 with proper time."

───────────────────────────────────────

Step 4: DOCUMENT & COMMUNICATE

Change Log Entry:

CR-001: SMS Notifications
Status: DEFERRED (Approved for Phase 2)
Schedule Impact: None (moved to Phase 2)
Budget Impact: $2,690 (Phase 2 budget)
Decision Date: Week 5
Decision: APPROVED FOR PHASE 2

Communication:
"We've approved SMS notifications as part of Phase 2.
This keeps Phase 1 focused and maintains our launch timeline.
We'll implement this after launch with dedicated time."

────────────────────────────────────────

CHANGE CONTROL POLICY

Fast-track changes (< 1 day impact):
- PM approval only
- Example: Small bug fix, documentation update

Standard changes (1-3 days impact):
- PM + Tech Lead approval
- Example: Add new field to database

Major changes (> 3 days impact):
- Steering Committee approval
- Example: New feature, architectural change

All changes:
- Logged in Jira
- Impact analyzed
- Communicated to team
- Documented in change log

Rule: NO unauthorized changes!
If not approved: doesn't go into production
```

---

## İZLEME & KONTROL (MONITORING & CONTROLLING)

### Phase 4.1: Earned Value Management

**SCHEDULE & COST CONTROL**

```
EARNED VALUE MANAGEMENT (EVM)
==============================

Three Key Metrics:

PV = PLANNED VALUE
What we planned to complete by now
(% planned × Total budget)

EV = EARNED VALUE
What we actually completed
(% actual × Total budget)

AC = ACTUAL COST
What we actually spent
(Real labor + expenses)

CALCULATIONS:

Schedule Variance = EV - PV (positive = ahead)
Cost Variance = EV - AC (positive = over budget)

Schedule Performance Index (SPI) = EV / PV
(>1 = ahead of schedule, <1 = behind)

Cost Performance Index (CPI) = EV / AC
(>1 = efficient, <1 = over cost)

────────────────────────────────────────

EXAMPLE: Week 6 Status

Project: 22 weeks, $155,000 total

Week 1-6 Planned:
- Schedule: 30% of work planned
- PV = 30% × $155,000 = $46,500

Week 1-6 Actual:
- Completed: 32% of work
- EV = 32% × $155,000 = $49,600
- Spent: $44,200

Metrics:

Schedule Variance = $49,600 - $46,500 = +$3,100
Status: AHEAD OF SCHEDULE ✅
(We completed more than we planned)

Cost Variance = $49,600 - $44,200 = +$5,400
Status: UNDER BUDGET ✅
(We're getting more value per dollar)

SPI = $49,600 / $46,500 = 1.07
Status: 107% schedule efficiency
(We're moving 7% faster than planned)

CPI = $49,600 / $44,200 = 1.12
Status: 112% cost efficiency
(Every dollar gets 1.12 value)

Interpretation:
✅ We're ahead of schedule (good!)
✅ We're under budget (good!)
✅ Efficiency is high (good!)

────────────────────────────────────────

WEEK-BY-WEEK EVM TRACKING

Week | PV | EV | AC | SV | CV | SPI | CPI | Status
─────────────────────────────────────────────────
 1 | $7,050 | $6,900 | $6,200 | -$150 | $700 | 0.98 | 1.11 | ✅
 2 | $14,100 | $13,800 | $12,800 | -$300 | $1,000 | 0.98 | 1.08 | ✅
 3 | $21,150 | $21,500 | $19,800 | +$350 | $1,700 | 1.02 | 1.09 | ✅✅
 4 | $28,200 | $29,200 | $25,600 | +$1,000 | $3,600 | 1.04 | 1.14 | ✅✅
 5 | $35,250 | $37,100 | $31,200 | +$1,850 | $5,900 | 1.05 | 1.19 | ✅✅
 6 | $46,500 | $49,600 | $44,200 | +$3,100 | $5,400 | 1.07 | 1.12 | ✅✅

Trend: Consistently ahead of schedule & under budget

────────────────────────────────────────

IF THINGS GO WRONG - CORRECTIVE ACTIONS

Scenario: Behind Schedule (SPI < 1)

Signs:
- EV < PV (completing less than planned)
- SPI declining week-over-week
- Critical path tasks slipping

Actions:
1. Analyze root cause
2. Reallocate resources
3. Reduce scope if needed
4. Accelerate non-critical items
5. Update forecast

Scenario: Over Budget (CPI < 1)

Signs:
- AC > EV (spending more than earning)
- CPI declining
- Burn rate > planned

Actions:
1. Analyze spending patterns
2. Tight expense control
3. Scope review (remove lower priority)
4. Team efficiency review
5. Adjust forecast

────────────────────────────────────────

FORECASTING AT COMPLETION

EAC = Budget at Completion estimate

Method 1: If current efficiency continues
EAC = BAC / CPI
Example: $155,000 / 1.12 = $138,400
(Better than budget!)

Method 2: If remaining work harder
EAC = AC + (BAC - EV) / CPI
Example: $44,200 + ($155,000 - $49,600) / 1.12
      = $44,200 + $94,107
      = $138,307

Variance at Completion:
VAC = BAC - EAC = $155,000 - $138,400 = +$16,600
(We'll be $16,600 under budget!)

This is great news! But don't relax yet.
Maintain discipline through Week 22.
```

---

## STAKEHOLDER YÖNETİMİ (STAKEHOLDER MANAGEMENT)

**[Detaylandırılmış stakeholder engagement strategies, communication plans, regular updates]**

---

## KAPALŞ (PROJECT CLOSURE)

**[Closure activities, lessons learned, final documentation]**

---

## ARAÇLAR (TOOLS)

**Recommended PM Tools:**
- Jira (Agile + traditional tracking)
- Confluence (Documentation)
- Slack (Communication)
- Excel (Budget tracking)
- Figma (Design collaboration)
- Zoom (Meetings)
- GitHub (Code repo)

---

## YAYGÜN HATALAR (COMMON MISTAKES)

1. **Unclear Scope** → Strict change control
2. **Unrealistic Estimates** → 20% buffer, expert input
3. **Poor Communication** → Regular demos + status reports
4. **Ignoring Risks** → Weekly risk review
5. **Team Burnout** → Realistic schedules, clear expectations
6. **No Quality Focus** → Testing from day 1
7. **Weak Sponsorship** → Regular sponsor engagement
8. **Scope Creep** → Frozen requirements, change gate
9. **Budget Overrun** → Weekly tracking, early correction
10. **No Lessons Learned** → Retrospective mandatory

---

**Version**: 1.0
**Last Updated**: 2026
**For**: AI Agents Managing Projects
**Audience**: Project Management Professionals
