# Closure Report: CampusHelp

Related issue: #12 (task T12)

Repository: https://github.com/defaultXcs/CampusHelp-Team67
Project Board: https://github.com/users/defaultXcs/projects/1

## 1. Final status

All 12 mandatory tasks (T01 to T12) are closed. The change request CR-01 (issue #18) was evaluated and closed with the decision Defer. All four milestones are complete. Every closed issue links to its evidence (a document, a prototype or a Pull Request), and every Pull Request is merged into main.

## 2. Planned versus actual

| Task | Owner | Planned (h) | Actual (h) | Evidence |
|------|-------|-------------|------------|----------|
| T01 Project charter | A | 4 | 4 | PR #15 |
| T02 Stakeholder requirements | B | 4 | 3 | PR #13 |
| T03 Scope and WBS | C | 4 | 4 | PR #22 |
| T04 Schedule and budget | A | 4 | 4 | PR #16 |
| T05 Wireframes | B | 4 | 2 | PR #20 |
| T06 Risk register and quality plan | C | 4 | 4 | PR #23 |
| T07 Student request prototype | B | 4 | 4 | PR #21 |
| T08 Administrator dashboard prototype | A | 4 | 4 | PR #17 |
| T09 Prototype tests | C | 4 | 4 | PR #24 |
| T10 Change request evaluation | A | 3 | 3 | PR #19 |
| T11 Final verification | C | 3 | 3 | PR #25 |
| T12 Final report and closure | B | 3 | 3 | This report |
| Total | | 45 | 42 | |

- Planned effort was 45 h (2,250,000 UZS). Actual effort was 42 h (2,100,000 UZS), which is 3 h or about 6.7% under the plan. The charter target (within 10% of 45 h) is met.
- Some actual hours were entered at closure from the team's best records, so they are estimates and not timesheets.
- Change request CR-01 would have added 3 h (150,000 UZS, about 6.7% of the budget). It was deferred, so it is not in the actual figures.

## 3. Milestones

| Milestone | Due | Result |
|-----------|-----|--------|
| M1 Project Initiation | 18 Nov 2026 | Complete, but late. T03 (scope and WBS) finished after the due date. |
| M2 Project Planning | 20 Nov 2026 | Complete, but late. T04 and T06 wait for T03, so they were late too. |
| M3 Project Execution | 25 Nov 2026 | Complete. Both prototypes and the test cases are merged. |
| M4 Monitoring and Closure | 30 Nov 2026 | Complete. Change request, verification report and final report are done. |

## 4. Major issues

1. **Late T03 blocked other tasks.** T04 and T06 depend on T03. The Pull Request for T03 waited for review, so M1 and M2 closed after their due dates. This is the risk R3 in the risk register (a late task blocks the others). It was the most serious risk and it happened.
2. **Late change request.** CR-01 (automatic email acknowledgment) arrived on Day 6, in the middle of testing. It was evaluated with a scope check and an impact analysis, and deferred because it needs a real email service, which is out of scope.
3. **One failed test.** TC5 (request status visibility) failed. The prototype has no page where a student can look up a request by its ID.
4. **Review gaps.** The Pull Request for T11 (#25) was merged with no second reviewer, and the review of #24 was recorded after the merge.

## 5. Lessons learned

- Start with the tasks that other tasks depend on, and review them first. One slow review delayed three tasks.
- Ask for a Pull Request review as soon as the Pull Request is opened, and name the reviewer.
- Record actual hours when a task is closed. Entering them later makes them estimates.
- Keep prototypes simple. Static screens made the two prototypes quick to build and easy to test.
- Test the prototype against the requirements. TC5 found a missing feature that the confirmation text already promised.
- Keep buffer time for change requests. CR-01 arrived in the middle of testing and still did not break the plan because T10 had its own 3 h.

## 6. Unresolved work

| Item | Detail | Owner | Next step |
|------|--------|-------|-----------|
| TC5 failed test | No status lookup screen for students | Student B | Add a simple screen (enter request ID, see status) in a later version |
| Display flaw | Red error messages stay visible after the fields are filled in, until Submit is clicked again | Student B | Fix in a later version |
| CR-01 deferred | Automatic email acknowledgment | Student A | Review again if an email service becomes available |
| Review gap on #25 | No second reviewer | Student A and C | Add a peer review comment if the lecturer asks |
| Actual hours | Some values are estimates | Student A | Replace with real hours if records exist |

None of these items stop the closure of the project. The prototype scope ends here, and all of them are logged for a next phase.
