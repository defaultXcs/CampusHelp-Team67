# CampusHelp - Requirements Document

**Prepared by:** Student B (Business Analyst & Designer)
**Related task:** T02 - Gather stakeholder requirements

## 1. Purpose
Students now send service requests by email and paper forms, so requests are hard to track. CampusHelp is a web portal where students can submit requests and see their progress.

## 2. Stakeholder Analysis

| Stakeholder | What they need | Main concern | Influence |
|---|---|---|---|
| Students | Submit requests easily and see the status | Requests get lost or have no answer | Medium |
| IT support | Clear requests with category and priority | Too many unclear requests | Medium |
| Administrators | See all requests and assign them to staff | No overview of work | High |
| Maintenance staff | Receive clear tasks with a location and description | Missing details in requests | Low |
| University administration (sponsor) | Better service and a simple system | Cost and time | High |

## 3. Functional Requirements

| ID | Requirement | Priority |
|---|---|---|
| FR1 | A student can submit a service request using a form. | High |
| FR2 | The form has a category (IT, Maintenance, Library, Administration) and a priority (High, Medium, Low). | High |
| FR3 | Each request gets a unique request ID (example: CH-0001). | High |
| FR4 | A student can enter the request ID to track the request. | High |
| FR5 | An administrator can assign a request to a staff member. | High |
| FR6 | An administrator can change the status (Open, In Progress, Completed). | High |
| FR7 | A dashboard shows the number of open, ongoing and completed requests. | Medium |

## 4. Non-Functional Requirements

| ID | Requirement |
|---|---|
| NFR1 | The request form must be simple and easy to use. |
| NFR2 | The pages must work on both phone and computer. |
| NFR3 | The system must show a message if a required field is empty. |
| NFR4 | The status page must show the latest status of a request. |

## 5. User Stories
- As a student, I want to submit a request online so that I do not need paper forms.
- As a student, I want to enter my request ID so that I can see the status.
- As an administrator, I want to assign a request to a staff member so that the work is clear.
- As an administrator, I want a dashboard so that I can see how many requests are open and completed.

## 6. Assumptions and Out of Scope
- The system is a prototype only. Real login, a production server and email/SMS services are **not** included.
- Request IDs and data in the prototype are simulated.

## 7. Traceability to Project Features

| Project feature | Requirement |
|---|---|
| Student request submission | FR1 |
| Request categories and priority levels | FR2 |
| Request tracking with unique ID | FR3, FR4 |
| Administrator request assignment | FR5 |
| Request status updates | FR6 |
| Dashboard (open, ongoing, completed) | FR7 |
