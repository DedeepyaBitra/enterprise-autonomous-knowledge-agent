# NovaTech Solutions — IT Support Knowledge Base

All IT issues are logged and tracked via the **IT Helpdesk Portal** (helpdesk.novatechsolutions.internal) or by emailing **itsupport@novatechsolutions.com**. Urgent (P1) issues may also be reported via the #it-urgent Slack channel for fastest response.

## Priority & Resolution Timelines

| Priority | Definition | Target Resolution |
|---|---|---|
| P1 — Critical | Complete work stoppage (no laptop access, production outage-related, account lockout blocking all work) | 2 hours |
| P2 — High | Major functionality broken (VPN down, email down, cannot join meetings) | 4 hours |
| P3 — Medium | Partial functionality issue (slow laptop, minor software bug, printer issue) | 1 business day |
| P4 — Low | Cosmetic or non-urgent (software install request, peripheral request) | 3 business days |

## 1. Password Reset

- Self-service password reset available at **passwordreset.novatechsolutions.internal** using registered phone/email OTP — resolves in under 5 minutes.
- If self-service fails (account locked, OTP not received), raise a P1 ticket via IT Helpdesk Portal.
- IT will verify identity via manager confirmation or employee ID + registered mobile before manually resetting (target: 30 minutes).
- Passwords must be changed every 90 days and meet complexity requirements (12+ characters, uppercase, lowercase, number, special character).

## 2. VPN Issues

- Common causes: expired VPN certificate, outdated VPN client, incorrect credentials, network firewall blocking VPN port.
- First step: employee should update the VPN client to the latest version via the Software Center and restart the device.
- If issue persists, raise a **P2 ticket**; L1 support will check certificate validity and remote-assist.
- VPN access is mandatory for accessing internal tools (Jira, Confluence, internal repos) while working remotely or from WFH.
- Target resolution: 4 hours.

## 3. Email Issues

- Covers: unable to send/receive, sync issues, mailbox full, spam filter misclassification.
- Mailbox storage limit is 50GB; employees nearing limit receive automated alerts at 45GB.
- Sync issues are typically resolved by re-authenticating the Outlook/mail client (Settings → Account → Re-sign in).
- Persistent issues should be raised as **P2 tickets**; target resolution: 4 hours.

## 4. Laptop Troubleshooting

- Common issues: slow performance, overheating, battery degradation, OS crashes, blue/black screen errors.
- First step: run the built-in diagnostic tool (Software Center → NovaTech Diagnostics) which auto-reports to IT.
- L1 support provides remote troubleshooting for software-level issues — target: 4 hours (P3).
- If diagnosed as a hardware fault, ticket escalates to **Hardware Replacement** process.

## 5. Software Installation

- Approved software list is available in the **Software Center** app pre-installed on all company laptops — self-install, no approval needed for listed tools (e.g., VS Code, Slack, Zoom, Chrome, Office 365).
- Non-listed software requires a request via IT Helpdesk Portal with business justification; requires **manager approval**, and additionally **Security team approval** if the software requires elevated system permissions or handles company data.
- Target resolution: 1 business day (P4) once approvals are complete.

## 6. Internet Issues

- Office internet outages are monitored centrally; status updates posted in #it-announcements.
- For WFH/remote employees experiencing personal internet issues, this is not an IT-serviceable issue (see Expense Policy — Internet Reimbursement for cost support), but employees may request a mobile hotspot device from IT for critical outage periods.
- Persistent office network issues (slow Wi-Fi, dead zones) should be logged as **P3 tickets**.

## 7. Printer Issues

- Common issues: paper jam, offline status, print quality, driver errors.
- Employees should first check printer status on the shared IT dashboard (printers.novatechsolutions.internal).
- Driver reinstallation available via Software Center → Printers.
- Unresolved issues logged as **P3 tickets**; target resolution: 1 business day.

## 8. Account Lockout

- Accounts lock automatically after **5 consecutive failed login attempts**, as a security measure.
- Auto-unlock occurs after **30 minutes**, or employees may raise a **P1 ticket** for immediate manual unlock.
- Repeated lockouts (3+ times in a month) trigger a mandatory security awareness check-in with the IT Security team, as this may indicate credential compromise attempts.

## 9. Hardware Replacement

- Applicable for confirmed hardware faults (screen, keyboard, battery, motherboard) or end-of-life devices (standard refresh cycle: 3 years for laptops).
- Process: IT diagnostic confirms fault → replacement request auto-created → approved by IT Operations Manager → loaner device issued within 24 hours while replacement is arranged.
- Full hardware replacement target: **3–5 business days**, depending on device availability.
- Accidental damage (drops, liquid spills) is covered under company asset insurance for the first replacement; repeat accidental damage within 12 months may be partially charged to the employee per the Asset Damage Policy.

## 10. Escalation Process

1. **L1 — IT Helpdesk:** First point of contact for all tickets; handles password resets, standard software issues, basic troubleshooting.
2. **L2 — IT Operations:** Escalation trigger — SLA breach (ticket not resolved within target timeline) or L1 unable to diagnose; handles VPN/network infrastructure, hardware replacement coordination, account security issues.
3. **L3 — IT Manager / Security Lead:** Escalation trigger — L2 SLA breach, or issue involves security incidents, data breaches, or system-wide outages; has authority to engage external vendors or declare a major incident.
- Employees can request escalation directly at any point by replying "escalate" on their ticket or emailing itescalations@novatechsolutions.com.
- Major incidents (system-wide outage, security breach) trigger automatic notification to the CTO and all L3 staff regardless of manual escalation.

## 11. Resolution Timelines Summary

| Issue Type | Priority | Target Resolution |
|---|---|---|
| Password Reset (self-service) | P1 | < 5 minutes |
| Password Reset (manual) | P1 | 30 minutes |
| Account Lockout | P1 | 30 minutes (auto) / immediate (manual) |
| VPN Issues | P2 | 4 hours |
| Email Issues | P2 | 4 hours |
| Laptop Software Issues | P3 | 4 hours |
| Printer Issues | P3 | 1 business day |
| Internet (office) | P3 | 1 business day |
| Software Installation (approved list) | Self-service | Immediate |
| Software Installation (new request) | P4 | 1 business day post-approval |
| Hardware Replacement | P3/P4 | 3–5 business days |
