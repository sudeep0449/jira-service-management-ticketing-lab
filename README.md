# Jira Service Management Ticketing Lab

This project was built to get hands-on practice with Jira Service Management as an IT support tool rather than just reading about ticket workflows. I set up a service desk project ("Sudeep Technologies IT Help Desk") and worked three support tickets end-to-end — creation, assignment, prioritisation, investigation, resolution, and closure — the same lifecycle a real help desk technician follows.

## Environment

- **Tool:** Jira Service Management (Atlassian)
- **Project:** Sudeep Technologies IT Help Desk (key: `STHD`)
- **Platform:** Windows 11, web browser
- **Framework referenced:** ITIL service desk concepts

## Ticket Lifecycle

Every ticket in this lab followed the same six stages:

1. **Creation** — a user submits an incident or service request through the portal
2. **Assignment** — the ticket is assigned to an IT support technician
3. **Priority classification** — priority is set based on business impact and urgency
4. **Investigation & troubleshooting** — the technician reviews the issue and documents findings
5. **Resolution** — the issue is fixed and resolution notes are added to the ticket
6. **Closure** — the ticket is closed once the resolution is confirmed

## 1. STHD-1 — Password Reset Request

**Issue:** Sarah Wilson (HR) reported she couldn't log in to her company account after forgetting her password, blocking her from daily HR operations.

Handled as: create ticket → assign to IT support → set priority to Medium → verify identity via employee records → reset password → save resolution notes → close ticket. Account access was confirmed restored.

| # | Screenshot | What's happening |
|---|---|---|
| 01 | `01-sthd1-ticket-assigned-to-it-support.png` | STHD-1 raised via Jira and assigned to IT support |
| 02 | `02-sthd1-priority-set-to-medium.png` | Priority set to Medium based on business impact |
| 03 | `03-sthd1-identity-verified-via-employee-records.png` | Sarah Wilson's identity verified against employee records before any account action |
| 04 | `04-sthd1-password-reset-internal-note-drafted.png` | Password reset performed, internal note drafted to record the action |
| 05 | `05-sthd1-resolution-notes-saved.png` | Resolution notes saved to the ticket |
| 06 | `06-sthd1-ticket-in-progress-status.png` | Ticket status moved to In Progress while work was underway |
| 07 | `07-sthd1-ticket-resolved-status.png` | Ticket marked Resolved once the password reset was confirmed working |
| 08 | `08-sthd1-ticket-closed-account-access-restored.png` | Ticket closed — account access restored |

## 2. STHD-2 — Printer Connectivity Issue

**Issue:** The network printer went unavailable for the Finance Department, reported as an incident rather than a service request.

Handled as: create incident ticket → assign to self → set priority to Highest (department-wide impact) → investigate connectivity → restore functionality → print a test page to confirm → document resolution → close via customer reply.

| # | Screenshot | What's happening |
|---|---|---|
| 09 | `09-sthd2-incident-ticket-created.png` | STHD-2 incident created: "Network printer unavailable for Finance Department" |
| 10 | `10-sthd2-priority-set-to-highest.png` | Priority set to Highest, reflecting the department-wide impact |
| 11 | `11-sthd2-connectivity-investigation-notes.png` | Investigation notes logged while tracing the connectivity fault |
| 12 | `12-sthd2-ticket-in-progress-highest-priority.png` | Ticket In Progress, flagged Highest priority |
| 13 | `13-sthd2-test-page-printed-resolution-documented.png` | Test page printed successfully; resolution documented |
| 14 | `14-sthd2-resolve-this-issue-dialog.png` | Ticket moved through the "Resolve this issue" transition |
| 15 | `15-sthd2-ticket-closed-customer-reply.png` | Ticket closed after a reply confirming the fix with the customer |

## 3. STHD-3 — Software Installation Request

**Issue:** Emma Brown (Sales) requested Adobe Acrobat Reader, since she couldn't view or manage the PDF-based customer contracts her role depends on.

Handled as: submit service request → assign to self → review the request → install the software → verify it → update ticket notes → close.

| # | Screenshot | What's happening |
|---|---|---|
| 16 | `16-sthd3-service-request-submitted-unassigned.png` | STHD-3 submitted — "Adobe Acrobat Reader installation request", unassigned |
| 17 | `17-sthd3-ticket-assigned-to-self.png` | Ticket assigned to self |
| 18 | `18-sthd3-installation-request-reviewed.png` | Request reviewed against the stated business need (contract/PDF access) |
| 19 | `19-sthd3-software-installed-and-verified.png` | Adobe Acrobat Reader installed and verified working |
| 20 | `20-sthd3-ticket-updated-customer-reply.png` | Ticket updated with a reply to the customer |
| 21 | `21-sthd3-ticket-closed.png` | Ticket closed |
| 22 | `22-sthd3-final-closed-ticket-view.png` | Final view of the closed ticket |

## Skills Demonstrated

Incident management, service request management, ticket prioritisation and assignment, IT documentation, troubleshooting process, customer service, and general IT service desk operations within an ITIL-based support model.

## Key Takeaways

- A consistent lifecycle (create → assign → prioritise → investigate → resolve → close) makes ticket handling repeatable regardless of whether the issue is an access problem, a hardware fault, or a software request.
- Priority isn't just about the technical severity of the issue — it reflects business impact, which is why a department-wide printer outage was rated higher than a single user's password reset.
- Documenting resolution notes and replying to the customer before closing a ticket matters as much as fixing the underlying issue — it's what makes the resolution auditable later.

## Repository Contents

- [`Jira-Ticketing-System-Lab-Documentation.pdf`](./Jira-Ticketing-System-Lab-Documentation.pdf) — full write-up with all screenshots embedded inline
- [`ss/`](<./ss>) — the individual screenshots referenced in the ticket tables above
