# KAGE Fitness Studio ERP - Final Portfolio Package

## Project Snapshot

| Field | Details |
|---|---|
| Project Name | KAGE Fitness Studio ERP |
| Project Type | Independent Business Analyst Portfolio Case Study |
| Domain | Fitness Studio / ERP / Gym Operations |
| Prepared By | Adina Mohammed |
| Date | May 2026 |

## Date and Demo Data Note

The portfolio documents are dated **May 2026** because that is the prepared artefact date. The live demo uses fictional sample records from **April-June 2026** to show realistic billing cycles, upcoming renewals, expired memberships and overdue follow-ups. These dates are mock data only.

## How to Open

Open `index.html` to view the portfolio page. Open `live-erp-demo.html` to launch the clickable ERP demo. No installation, login setup, backend, or database is required.

## Portfolio Boundary

This is a fictional Business Analyst portfolio case study inspired by real-world gym operations. It is not a live client project, production ERP system, or final technical implementation. All data is fictional and created for portfolio demonstration.

## Final File List

| File | Purpose |
|---|---|
| `index.html` | Main portfolio case study page |
| `live-erp-demo.html` | Clickable Live ERP Demo with 7 core modules and access-based role views |
| `assets/pdfs/kage_erp_overview_document.pdf` | ERP overview, scope and project context |
| `assets/pdfs/kage_logical_data_model_overview.pdf` | Business-friendly logical data model overview |
| `assets/pdfs/kage_detailed_data_dictionary.pdf` | Field-level data dictionary |
| `assets/pdfs/kage_business_rules_summary.pdf` | Business rules summary, including trainer role-access addendum |
| `assets/pdfs/kage_process_flow_artefacts.pdf` | Process flow artefacts and decision paths |
| `assets/pdfs/kage_uat_summary_validation_tracker.pdf` | Simulated UAT summary and validation tracker |
| `assets/images/kage_logo_transparent.png` | KAGE logo used in portfolio and demo |
| `assets/images/logical-data-model.png` | Logical data model diagram used in the portfolio page |
| `README.md` | Reviewer guide |


## Scope Count Clarification

The project uses **7 core ERP modules** across the overview, UAT, process flows and live demo. The **Trainer Dashboard / Mobile View** is not counted as an 8th ERP module; it is a limited role-based trainer view within the PT Session & Trainer Management scope.

## Live ERP Demo Review Flow

1. Open `live-erp-demo.html`.
2. Login as **D Kamal Kumar - Owner/Admin** to view the complete ERP scope.
3. Switch to **Front Desk Staff** to see limited operational access.
4. Switch to **Trainer View** to see trainer-owned PT sessions, assigned clients and commission status.

## Key BA Skills Demonstrated

- Requirement visualisation
- Process understanding
- Module scoping
- Business rule translation
- Data awareness
- UAT thinking
- Stakeholder communication
- MVP boundary control
- Role-based access control

## Trainer Role Update

The trainer dashboard is a role-based view, not a separate full mobile app. Trainers can see their assigned PT clients, today’s sessions, completed/pending sessions, progress notes and their own commission status. They cannot see full gym revenue, freelancer billing, all-trainer payout data or admin-only reports.

## Suggested Interview Explanation

“I added a limited trainer-facing dashboard because trainers need visibility of their assigned PT clients, daily sessions, pending/completed sessions and own commission status. I kept full revenue, freelancer billing and admin reports restricted to Owner/Admin/Finance roles. This demonstrates access-control thinking without over-scoping the MVP.”


## Note About README / Demo Guide

The README is a reviewer guide, not a separate BA document like the data dictionary or business rules PDF. It exists so recruiters/interviewers can quickly understand how to open and review the Live ERP Demo.


## Final Publishing Notes

The main portfolio page includes a BA Reflection section before the final artefact pack. The ERP Overview PDF uses the KAGE gold/charcoal/cream theme and consistently describes freelancer billing as access-fee based, not session-based. The UAT Summary wording frames gate/access issues as ERP status flags for front desk action rather than physical gate enforcement.
