# Sheheryar Zia Khan — Operational Systems

**I build multi-layer operational systems end to end — a field app, a central database, automated workflows, and a live dashboard, working as one.** I replace manual logging and per-seat software with systems built on tools organisations already own, and because I come from plant operations, the systems fit how the work actually happens.

🔗 **Live portfolio:** https://YOUR-USERNAME.github.io/REPO-NAME/
*(replace with your real GitHub Pages link once it's live — see LAUNCH_KIT.md)*

---

## What I build

A coordinated stack where each layer has one job and they hand off cleanly:

`Field app (capture)` → `Central database (store + audit trail)` → `Automation (alerts, escalation, compliance)` → `Dashboard (oversight + foresight)`

Most "tools" are a single piece. The value is in connecting them so data flows from the field to the decision-maker without anyone re-keying it.

---

## Projects

### 01 · Industrial Safety Equipment Tracker *(deployed system)*
A safety-equipment compliance platform that replaced **$30,000/year of licensed software** with a near-zero-cost system built on the Microsoft 365 a facility already owned. Field app with mandatory photo evidence → SharePoint database with an automatic audit trail → three Power Automate workflows (daily health summary, audit-compliance check, 72-hour management escalation) → live dashboard.
**Demo:** `safety_tracker_demo.html` — the full system across three tabs (field app, automation, executive dashboard), with a guided assistant.
**Stack:** Power Apps · SharePoint · Power Automate · Power BI · HTML/JS
*Presented with all internal data removed; the demo runs on synthetic data.*

### 02 · TR-01 — Predictive Column Monitoring *(interactive demonstration)*
An early-warning layer that sits above a control room and catches slow process drift days before it becomes an upset — the trend no single rotating shift stays long enough to see. Watches each instrument's trend and the relationships between tags, flags developing failure signatures (fouling, flooding, feed instability) with a predicted time-to-consequence and a suggested mitigation.
**Demo:** `tr01_instrumentation_monitor.html` — 33 tags, 60 days of data, three seeded upsets caught early, with a stewardship assistant that defers control to the DCS and board.
**Stack:** HTML/JS · Chart.js · trend & anomaly engine

### 03 · MERIDIAN — Equity & Portfolio Analytics (PSX) *(interactive demonstration)*
Turns a portfolio of stocks into a plain-English read on return, risk, and drawdown — annualised return, volatility, max drawdown, Sharpe, and beta to the market — with growth, drawdown, and risk-return exhibits. A guided assistant explains every number and deliberately refuses to give investment advice.
**Demo:** `meridian_psx_analytics.html`
**Stack:** HTML/JS · Chart.js · financial analytics
*Runs on clearly-labelled sample data; structured to drop in real exported price history.*

---

## Capabilities

**Capture & apps** — Microsoft Power Apps, custom web apps, validated field data entry
**Data & structure** — SharePoint, schema design, audit trails, role-based permissions, REST API
**Automation** — Power Automate, scheduled & event-driven workflows, conditional escalation
**Analytics & dashboards** — Power BI, custom HTML/JavaScript dashboards, trend & anomaly detection

`Power Apps` · `SharePoint` · `Power Automate` · `Power BI` · `HTML` · `CSS` · `JavaScript` · `Chart.js` · `REST APIs` · `systems architecture`

---

## A note on the demos

All three demos run on **synthetic or clearly-labelled sample data** and are fully self-contained — open any `.html` file in a browser, no setup. The safety-tracker case reflects a real deployed system with every piece of internal/identifying data removed. The assistants are transparent, rule-based explainers built on the data shown — they describe and inform, and deliberately stop short of giving advice (finance), directing control actions (process safety), or making safety sign-off calls (safety tracker).

---

## Contact

- **Upwork:** *(add link)*
- **LinkedIn:** *(add link)*
- **Email:** *(add)*
