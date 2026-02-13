# Notifications & Reminders

[Project Homepage](project-homepage.md) > Notifications & Reminders

---

## Functional Description

The system must automatically send notifications and reminders to students and counselors regarding appointment confirmations, schedule changes, cancellations, and upcoming sessions. Notifications may be delivered through in-system alerts or email services.

---

## Use Case Scenario

| Actor | Student / Counselor |
|-------|---------------------|
| Precondition | Appointment exists in the system |
| Main Flow | System detects event (approval/cancellation/upcoming session) → Sends notification |
| Alternative Flow | Notification service fails → Retry or log error |
| Postcondition | User receives appointment update notification |

---

© 2026 Agori
