# AI Engineering Evidence Engine

Live demo: https://zhane-grey-evidence-dashboard.vercel.app/

This repository is the public landing page for the **AI Engineering Evidence Engine Dashboard**. It is built to help an employer understand one thing quickly: the system turns local engineering proof into a reviewable dashboard, instead of relying on vague portfolio claims.

## Visual Tour

The first screenshot shows the full Atlas-style dashboard: verification posture, the ingest doctrine, the automation console, and the daily evidence panel.

The second screenshot opens the source-code proof drawer. That is the key behavior to notice, because it ties the dashboard back to real local code instead of leaving the system as a polished mockup.

| Dashboard overview | Source-code proof drawer |
|---|---|
| ![AAED dashboard overview](assets/aaed-dashboard-overview.png) | ![AAED proof drawer](assets/aaed-proof-drawer.png) |

## Alternative console mode
<img width="1562" height="1278" alt="image" src="https://github.com/user-attachments/assets/a1c85b21-b4b9-4300-8853-46665d2cc342" />


## What This Demonstrates

- Interactive evidence surfacing for recruiter review
- Proof-oriented UI patterns instead of narrative-only claims
- Secret-redaction and evidence-boundary controls
- Source-code inspection from inside the dashboard
- Clear state handling for verification, ingestion, and reporting

## Verified Implementation Signals

The dashboard is backed by local files in the `systems-dashboard/` workspace, including:

- `index.html` for the dashboard shell and proof drawer
- `styles.css` for the glassmorphic presentation layer
- `app.js` for hotspot behavior, redaction flows, proof drawer logic, and evidence state handling
- `vercel.json` for deployment routing

The codebase includes explicit proof-oriented UI patterns such as:

- Interactive hotspots tied to dashboard sections
- A source-code drawer for local proof inspection
- Secret-redaction review flows
- State handling around proof selection and UI synchronization

## Why an Employer Should Care

This project shows how I build under review conditions:

- I make claims traceable to local code and artifacts.
- I separate verified behavior from simulation.
- I structure dashboards so proof is easy to inspect quickly.
- I treat accessibility, reviewability, and evidence boundaries as first-class requirements.

## Fast Path For Reviewers

If you only look at three things, look at these:

1. The dashboard overview screenshot above.
2. The proof drawer screenshot above.
3. The `app.js` and `index.html` implementation that drives the proof flow.

## Related Proof

- Resume: `Zhane_Grey_AI_Engineer_ATS_Resume.md`
- Systems dashboard workspace: `systems-dashboard/`
- Live portfolio evidence files: root AI Engineer documents and daily evidence reports

## Notes

- This README is employer-facing and intentionally concise.
- It describes verified local work, not production status.
- Any simulated or demo-only behavior should remain labeled clearly in the UI and supporting docs.
