# Prototype Test Cases

Related issue: #9 (task T09)

Both prototypes were opened in Chrome and tested by hand on 24 Nov 2026.

- Student form: prototype/student-request.html
- Admin dashboard: prototype/admin-dashboard.html

## Simulated parts

- The request ID (for example CH-5345) is made up by the page. Nothing is saved.
- The dashboard list is fixed sample data. There is no login.
- Changes on the dashboard stay in the page memory and are lost on reload.

## Test cases

| ID | Test | Steps | Expected result | Actual result | Pass/Fail |
|---|---|---|---|---|---|
| TC1 | Required fields | Open the form, leave all fields empty, click Submit | Error message under each empty field | Four red error messages appeared (Student ID, category, description, priority) | Pass |
| TC2 | Category selection | Click the Request Category dropdown and pick an option | Options are shown and one can be selected | Options shown, "Classroom maintenance" selected | Pass |
| TC3 | Priority selection | Click the Priority dropdown and pick an option | Options are shown and one can be selected | Options shown, "Low" selected | Pass |
| TC4 | Confirmation after submission | Fill in all fields, click Submit | Confirmation screen with a request ID | "Your request was submitted successfully" with ID CH-5345 (simulated) | Pass |
| TC5 | Request status visibility | Look for a place where a student can see the status of a request | Student can look up the status with the request ID | No tracking or status page exists in the prototype. The confirmation says "track your request" but there is no way to do it | Fail |
| TC6 | Admin dashboard | Open the dashboard, check the counts, change R-101 to Completed, open the Assigned to list | Counts show open, ongoing and completed. Counts update after a status change. Requests can be assigned | Counts started at 2 / 2 / 1 and changed to 1 / 2 / 2. Assign list shows IT Support, Maintenance, Library Desk and Registrar Office | Pass |

## Failed tests and follow-up

| Test | Problem | Follow-up action |
|---|---|---|
| TC5 | No status page for students | Add a simple status lookup screen (enter request ID, see status) in a later version. Owner: Student B. Logged for the next phase because the prototype scope ends here |

## Other observation

- On the form, the red error messages stay visible after the fields are filled in, until Submit is clicked again. This is a small display flaw, not a failed test.

## Summary

5 of 6 tests passed and 1 failed (TC5).
