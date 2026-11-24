# CampusHelp: Scope and Work Breakdown Structure (WBS)

Related issue: #3 (task T03)

## 1. Project scope

The CampusHelp portal lets university students send service requests and track their status. Administrators manage the requests.

### In scope
- Student request form with required fields
- Request ID and confirmation screen
- Request tracking and status page
- Administrator dashboard (open, ongoing, completed counts)
- Assigning requests and changing status
- Wireframes and two prototypes (simulated)
- Project documents: charter, schedule, budget, risks, quality plan, tests, final report

### Out of scope
- Live SMS or email services
- Real database or real hosting
- Real student login with university accounts
- Mobile app
- Payments

## 2. WBS hierarchy

```
CampusHelp Project
|-- 1. Initiation and Planning
|   |-- 1.1 Project charter (T01)
|   |-- 1.2 Requirements (T02)
|   |-- 1.3 Scope and WBS (T03)
|   |-- 1.4 Schedule and budget (T04)
|   `-- 1.5 Risk register and quality plan (T06)
|-- 2. Design and Prototype
|   |-- 2.1 Wireframes (T05)
|   |-- 2.2 Student request interface (T07)
|   `-- 2.3 Administrator dashboard (T08)
|-- 3. Testing and Control
|   |-- 3.1 Prototype tests (T09)
|   `-- 3.2 Change request (T10)
`-- 4. Closure
    |-- 4.1 Final verification (T11)
    `-- 4.2 Final report and closure (T12)
```

## 3. Work package deliverables

| WBS | Work package | Deliverable |
|---|---|---|
| 1.1 | Project charter | Charter document with goals, success criteria and budget |
| 1.2 | Requirements | List of functional requirements (FR1 to FR7) |
| 1.3 | Scope and WBS | This document |
| 1.4 | Schedule and budget | Dependency table, diagram, delay risks and budget |
| 1.5 | Risk register and quality plan | Risk register with 5+ risks and a quality plan |
| 2.1 | Wireframes | Wireframes for the form, tracking page, dashboard, categories and priorities |
| 2.2 | Student request interface | Prototype page with form, error message and confirmation with request ID |
| 2.3 | Administrator dashboard | Prototype page with counts, assign and status changes |
| 3.1 | Prototype tests | Test cases with results, simulated functions marked |
| 3.2 | Change request | Change request document with scope check, impact and decision |
| 4.1 | Final verification | Verification report checking issues, PRs and milestones |
| 4.2 | Final report and closure | Final report with results, hours and lessons learned |
