# Midstream Integrations

**Custom integrations for Microsoft Dynamics 365 Business Central, and the open-source tools behind them.**
Everything here came out of real client work. Read every line, install what helps, change anything. The Business Central apps and wirewatch are MIT-licensed; the OCR server is AGPL-3.0.

**[Book a 20-minute call](https://midstreamintegrations.com/contact)** · intro@MidstreamIntegrations.com · [MidstreamIntegrations.com](https://www.MidstreamIntegrations.com)

## What we do

- **Custom Business Central extensions** in AL: new pages, reports, approvals and automation built around your process
- **Integrations** between Business Central and everything else: APIs, EDI, OCR, email, Python services on your own servers
- **Hosting and support** for the tools below, so you get the result without running anything yourself

## Business Central apps

| App | What it does | Needs |
|---|---|---|
| [Card Statement OCR + Requisition Approval](https://github.com/Midstream-Integrations/bc-card-statement-ocr) | Card statements become coded, receipted purchase invoices; managers approve from an email link | BC 25+, OCR server |
| [Scheduled Report Emailer](https://github.com/Midstream-Integrations/bc-scheduled-report-emailer) | Email any report as PDF, Excel or Word on a Job Queue schedule | BC 25+ |
| [Inventory Threshold Alerts](https://github.com/Midstream-Integrations/bc-inventory-threshold-alerts) | One email when an item drops below its minimum, per item, location and variant | BC 25+ |
| [Production Machines](https://github.com/Midstream-Integrations/bc-production-machines) | Machine register, maintenance/QA/safety log, machine on production orders | BC 25+ Premium |
| [Finance & Warehouse Reporting Pack](https://github.com/Midstream-Integrations/bc-reporting-pack) | G/L audit view with user names, receipt and accrual queries | BC 25+ |
| [Dynamic Ship BOL Commodity](https://github.com/Midstream-Integrations/bc-dynamicship-bol-commodity) | Commodity lines, NMFC/class and pro barcode on the Bill of Lading | Insight Works Dynamic Ship |
| [Dynamic Ship Productivity Pack](https://github.com/Midstream-Integrations/bc-dynamicship-productivity-pack) | Package Worksheet, shipment list, QA email and BOL field additions | Insight Works Dynamic Ship |

Every app stands alone, uses the `MID` prefix and has its own object ID range, so they install side by side. Download the `.app` from a repo's **Releases**, upload it on **Extension Management** in a sandbox first, then assign the app's permission set.

## Servers and infrastructure

| Project | What it does | Runs on |
|---|---|---|
| [Card Statement OCR Server](https://github.com/Midstream-Integrations/bc-card-statement-ocr-server) | Reads card statements, runs the receipts portal and writes the results back to Business Central. Self-host it or have us host it | Ubuntu 24.04 or Debian 13 |
| [wirewatch](https://github.com/Midstream-Integrations/wirewatch) | Network traffic dashboard from a switch mirror port: every device and destination, outside-the-country alerts, UniFi switch ports, and a live world map for a wall display | Raspberry Pi or Ubuntu |

## Need something that isn't here?

Most of these started as one client's problem. If you have a process that still runs on spreadsheets, retyping or someone remembering to click a button, we'd like to hear about it.
**[Book a 20-minute call](https://midstreamintegrations.com/contact)** · intro@MidstreamIntegrations.com
