# AI Engineering Evidence Engine

Live demo: https://zhane-grey-evidence-dashboard.vercel.app/

This repository is the public landing page for the **AI Engineering Evidence Engine Dashboard**. It is built to help an employer understand one thing quickly: the system turns local engineering proof into a reviewable dashboard, instead of relying on vague portfolio claims.

## Visual Tour

The dashboard is easier to understand in three states:

| Dashboard overview | Proof drawer | Docked console |
|---|---|---|
| ![AAED dashboard overview](assets/aaed-dashboard-overview.png) | ![AAED proof drawer](assets/aaed-proof-drawer.png) | ![AAED console docked](assets/aaed-console-docked.png) |

The console log is intentionally draggable. When it is docked into the hero area, the live log stream sits beside the doctrine map so reviewers can see telemetry and proof in the same visual frame.

## What This Demonstrates

- Interactive evidence surfacing for recruiter review
- Proof-oriented UI patterns instead of narrative-only claims
- Secret-redaction and evidence-boundary controls
- Source-code inspection from inside the dashboard
- Clear state handling for verification, ingestion, and reporting
- A draggable terminal mode that lets the log stream join the main evidence map

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
- A dockable terminal that can be dragged into the hero zone for live log context

## Why an Employer Should Care

This project shows how I build under review conditions:

- I make claims traceable to local code and artifacts.
- I separate verified behavior from simulation.
- I structure dashboards so proof is easy to inspect quickly.
- I treat accessibility, reviewability, and evidence boundaries as first-class requirements.

## Fast Path For Reviewers

If you only look at three things, look at these:

1. The dashboard overview screenshot.
2. The docked console screenshot.
3. The `app.js` and `index.html` implementation that drives the proof flow.

## Related Proof

- Resume: `Zhane_Grey_AI_Engineer_ATS_Resume.md`
- Systems dashboard workspace: `systems-dashboard/`
- Live portfolio evidence files: root AI Engineer documents and daily evidence reports

## Notes

- This README is employer-facing and intentionally concise.
- It describes verified local work, not production status.
- Any simulated or demo-only behavior should remain labeled clearly in the UI and supporting docs.
