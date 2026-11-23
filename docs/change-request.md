# Change Request CR-01: Automatic Email Acknowledgment

Related issue: #18 (change request) and #10 (task T10)

## 1. Request summary

| Item | Detail |
|---|---|
| Request ID | CR-01 |
| Raised by | Project sponsor (simulated) |
| Date received | Day 6 (24 Nov 2026) |
| Requested change | When a student submits a request, the system sends an automatic email acknowledgment that includes the request ID. |
| Reason | Students want proof that their request was received without checking the portal. |

## 2. Scope check

- The project charter lists "live SMS/email services" as **out of scope**.
- The current requirements (FR1 to FR7) include a request ID and status tracking (FR4), but no email message.
- Result: the change is **outside the approved scope**. Approving it means changing the scope baseline.

## 3. Impact analysis

| Area | Impact |
|---|---|
| Effort | +3 h (provisional): 1 h to design the email text and trigger, 1 h to add it to the request interface prototype, 1 h to add test cases |
| Cost | 3 h x 50,000 UZS = 150,000 UZS, which is 6.7% above the 2,250,000 UZS budget |
| Affected tasks | T07 (student request interface prototype), T09 (prototype tests), T11 (final verification) |
| Affected milestones | M3 (Project Execution, due 25 Nov) and M4 (Monitoring and Closure, due 30 Nov) |
| Schedule | T07 is already finished on 23 Nov. Rework would push T09 (24 to 25 Nov) and could push T11 (27 Nov), which is on the critical path. About 1 day of delay is possible. |
| Quality | A real email needs an email service and a mail server. In a prototype this can only be simulated, so the value to the sponsor is small. |

## 4. Risk assessment

| Risk | Likelihood | Effect | Note |
|---|---|---|---|
| Delay of M3 and M4 | Medium | Medium | The critical path has no spare time. |
| Real email service needed | High | High | Out of scope and needs external accounts and cost. |
| Spam or wrong-address emails | Low | Low | Only relevant in a real system. |

## 5. Options

1. **Approve now:** add the feature in this project. Costs 3 h, risks a 1-day delay, and breaks the scope baseline.
2. **Reject:** keep the scope as it is. The request is lost.
3. **Defer:** keep the current scope and record the request as a candidate for a later phase (version 2), where a real email service can be planned and budgeted.

## 6. Recommendation

**Defer.**

Reason: the feature is outside the approved scope, it needs a real email service that the project does not have, and the project has no spare time on the critical path. The need is valid, so rejecting it would be too strong. The request is moved to the backlog for a later phase, and the current prototype shows the request ID on screen as a temporary replacement.

## 7. Decision record

| Item | Entry |
|---|---|
| Decision | Defer (recommended by the Project Manager) |
| Decision date | 26 Nov 2026 |
| Approved by | Project sponsor (simulated) |
| Baseline change | None. Scope, schedule and budget stay the same (45 h, 2,250,000 UZS). |
| Follow-up | Add CR-01 to the backlog for the next phase. Close issue #18 with the decision. |
