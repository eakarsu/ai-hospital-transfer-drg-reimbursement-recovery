# Hospital Transfer DRG Reimbursement Recovery

Identify claims incorrectly reduced under transfer rules and recover the full DRG-supported reimbursement.

**Primary buyer:** Acute-care hospitals and health systems. **Evidence:** admissions, discharge status, transfer destinations, DRG assignments, length of stay, post-acute claims, payer policies, remittances, and appeals.

Full local application built with React, Vite, Express, PostgreSQL, and OpenRouter. Includes 15 domain-specific capabilities, 105 custom AI workbench fields, three scenario-fill controls per feature, operational registers, workflow transitions, analytics, professional AI decision briefs, audit history, and at least 15 PostgreSQL records per capability.

## Domain capabilities

- Inpatient claim ingestion
- Discharge status validation
- Transfer destination matching
- Post-acute claim linkage
- DRG transfer-rule library
- Geometric mean LOS validation
- Per-diem payment reconstruction
- Same-day readmission analysis
- Interrupted stay review
- Payer policy versioning
- Underpayment detection
- Corrected claim generation
- Appeal evidence package
- Remittance reconciliation
- Facility DRG analytics

Run `./start.sh`, then open <http://127.0.0.1:4643>. API: `5643`.

Administrator: `runtime-admin@example.com` / `LocalDemo!2026`. Operator and reviewer credential buttons are available on the login page.
