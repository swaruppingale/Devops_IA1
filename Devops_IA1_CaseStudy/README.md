# Grafana Case Study – DevOps IA1

This folder contains my case study implementation of **Grafana** as part of the DevOps IA-1.

## 📌 Project Overview
- Tool: Grafana (Monitoring & Visualization)
- Environment: Local Machine
- Data Source: TestData DB
- Dashboard Name: `Devops_IA1`

## 🚀 Implementation Steps
1. Installed Grafana locally (v12.1.1).
2. Added **TestData DB** as a datasource.
3. Created a dashboard with multiple panels:
   - Timeseries graph (CPU/metrics simulation).
   - Gauge panel with thresholds (green < 80, red ≥ 80).
4. Configured an alert rule:
   - Trigger if value > 80.
   - Shown in Grafana Alert UI.
5. Exported the dashboard as JSON.

## 📂 Files Included
- `grafana-dashboard.json` → exported JSON of my dashboard.
- `screenshots/` → images of my dashboard, alerts, and setup.


## 🔧 How to Import the Dashboard
1. Open Grafana → click **+ → Import**.
2. Upload `grafana-dashboard.json`.
3. The `Devops_IA1` dashboard will appear in your Grafana.

This is the practical implementation of Grafana as a monitoring tool in the DevOps cycle.
