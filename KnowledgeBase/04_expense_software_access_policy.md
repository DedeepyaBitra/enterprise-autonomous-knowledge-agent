# NovaTech Solutions — Expense & Software Access Policy

## 1. Travel Reimbursement

- Domestic travel: economy class flights/AC 2-tier train, booked via the approved corporate travel partner (ClearTrip Business) wherever possible.
- International travel: economy class flights for individual contributors; premium economy permitted for Director+ on flights exceeding 6 hours, with VP approval.
- Local conveyance (cabs, auto) for official work is reimbursable with receipts; ride-hailing app receipts accepted.
- Accommodation: capped at ₹8,000/night domestic (metro cities), ₹5,000/night domestic (non-metro), actuals with prior approval for international travel.
- All travel must be pre-approved by the manager before booking, via the Travel Request Form in the Expense Portal.

## 2. Food Reimbursement

- Applicable only during **official business travel** (not regular office days).
- Cap: **₹500/day** for domestic travel, **₹1,500/day** for international travel, actuals with receipts required above ₹200 per meal.
- Client entertainment meals require pre-approval and are reimbursed separately under the Sales/Customer Success entertainment budget, not the individual travel food allowance.
- No food reimbursement for regular working days at the office or WFH.

## 3. Internet Reimbursement

- Applicable to employees on **WFH (regularly, 4+ days/month)** and **fully Remote** designations.
- Reimbursement: **₹1,000/month**, submitted quarterly with a broadband bill in the employee's name (or a self-declaration if the connection is shared/family-owned).
- Not applicable to employees who are primarily office-based (less than 4 WFH days/month).

## 4. Certification Reimbursement

- Employees may claim up to **₹20,000/year** for job-relevant certifications, courses, or conference attendance.
- Requires **pre-approval** from both the direct manager and the Learning & Development (L&D) team before enrollment — retroactive claims are not accepted except for certifications completed within the last 30 days, which require both manager **and** L&D sign-off as a one-time exception.
- Reimbursement is processed only upon **proof of completion** (certificate or passing score).
- If an employee resigns within 6 months of receiving certification reimbursement exceeding ₹10,000, the amount is deducted from Full & Final settlement, per the signed L&D agreement.

## 5. Expense Approval Workflow

1. Employee submits expense claim via the Expense Portal within **15 days** of incurring the expense, with itemized receipts attached.
2. **Manager approval** required for all claims.
3. Claims **above ₹10,000** additionally require **Finance team approval**.
4. Claims **above ₹50,000** (e.g., international travel, large certifications) require **Department Head approval** in addition to Finance.
5. Approved claims are reimbursed in the **next payroll cycle** following approval.
6. Rejected claims are returned to the employee with a reason and may be resubmitted with corrections within 7 days.
7. Expenses submitted after 30 days from the date incurred are not eligible for reimbursement except with HR-approved exception (e.g., employee was on medical leave).

## 6. Software Access Policy

- All software/tool access requests are raised via the **IT Helpdesk Portal → Access Request** category, specifying tool, business justification, and duration (permanent or time-boxed).
- Default approval chain: **Direct Manager approval → Tool Owner/Admin approval → IT provisions access.**
- Access is granted on a **least-privilege, role-based basis** — employees receive only the permission tier needed for their role (e.g., Read vs. Write vs. Admin).
- Access reviews are conducted **quarterly** by IT Security; unused access (no login in 60+ days) is automatically flagged for revocation.
- All access grants and revocations are logged for audit/compliance purposes.

### GitHub Access

- Requires manager approval + Engineering Lead (repo owner) approval.
- Default access tier: Write access to team-specific repositories; org-wide Admin access restricted to Engineering Managers and above.
- Contractors/interns receive time-boxed access (expires automatically at contract end date) and read-only access by default.

### Figma Access

- **Viewer access:** No approval required. Broadly available to Product, Engineering, and Marketing employees on request.
- **Editor access:** Requires manager approval. Editor access to shared design systems/libraries additionally requires Design team lead approval. Editor access is restricted to Design and Product roles.

### Jira Access

- Standard Jira access (project-level, based on team) is auto-provisioned during onboarding based on department.
- Cross-team project access requires the requesting employee's manager + the target project's Jira Admin approval.
- Admin-level Jira access (workflow configuration, project creation) restricted to Engineering Managers, Product Leads, and IT Operations.

### OpenAI API Access

- Highest-sensitivity access tier due to data handling and cost implications.
- Requires: Manager approval → Department Head approval → **Security & Compliance team approval** (mandatory, due to potential exposure of customer/company data to third-party model providers).
- All OpenAI API usage must go through NovaTech's approved gateway (internal proxy with logging and PII redaction) — direct unproxied API key usage is prohibited.
- Usage is capped by budget tier assigned to the requesting team; overages require Finance approval.
- Access is reviewed monthly by Security & Compliance given the sensitivity and cost profile.

## 7. Approval Rules Summary

| Request Type | Approval Chain | Additional Trigger |
|---|---|---|
| Expense < ₹10,000 | Manager | — |
| Expense ₹10,000–₹50,000 | Manager → Finance | — |
| Expense > ₹50,000 | Manager → Finance → Department Head | — |
| Certification Reimbursement | Manager → L&D | Pre-approval mandatory |
| GitHub Access | Manager → Engineering Lead | Admin tier needs Eng Manager+ |
| Figma Access | Manager (Viewer: none needed) | Editor needs Design Lead |
| Jira Access | Auto (default) / Manager + Project Admin (cross-team) | Admin tier restricted |
| OpenAI API Access | Manager → Department Head → Security & Compliance | Budget cap enforced |
