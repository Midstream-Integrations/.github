# Midstream Integrations

**Free, open-source extensions for Microsoft Dynamics 365 Business Central.**
Read every line, install what helps, change anything. The Business Central apps are MIT-licensed; the OCR server is AGPL-3.0.

## Apps

| App | What it does | Needs |
|---|---|---|
| [Card Statement OCR + Requisition Approval](https://github.com/Midstream-Integrations/bc-card-statement-ocr) | Card statements become coded, receipted purchase invoices; managers approve from an email link | BC 25+, OCR server |
| [Scheduled Report Emailer](https://github.com/Midstream-Integrations/bc-scheduled-report-emailer) | Email any report as PDF, Excel or Word on a Job Queue schedule | BC 25+ |
| [Inventory Threshold Alerts](https://github.com/Midstream-Integrations/bc-inventory-threshold-alerts) | One email when an item drops below its minimum, per item, location and variant | BC 25+ |
| [Production Machines](https://github.com/Midstream-Integrations/bc-production-machines) | Machine register, maintenance/QA/safety log, machine on production orders | BC 25+ Premium |
| [Finance & Warehouse Reporting Pack](https://github.com/Midstream-Integrations/bc-reporting-pack) | G/L audit view with user names, receipt and accrual queries | BC 25+ |
| [Dynamic Ship BOL Commodity](https://github.com/Midstream-Integrations/bc-dynamicship-bol-commodity) | Commodity lines, NMFC/class and pro barcode on the Bill of Lading | Insight Works Dynamic Ship |
| [Dynamic Ship Productivity Pack](https://github.com/Midstream-Integrations/bc-dynamicship-productivity-pack) | Package Worksheet, shipment list, QA email and BOL field additions | Insight Works Dynamic Ship |

## Server

| Project | What it does | Needs |
|---|---|---|
| [Card Statement OCR Server](https://github.com/Midstream-Integrations/bc-card-statement-ocr-server) | Reads card statements, runs the receipts portal and writes the results back to Business Central. Python, self-hosted | Ubuntu 24.04 or Debian 13, Microsoft Entra app |

Every app stands alone, uses the `MID` prefix and has its own object ID range, so they install side by side.

## Get started

1. Download the `.app` from a repo's **Releases** and upload it on **Extension Management**, or build from source in VS Code with the AL Language extension.
2. Test in a sandbox, then assign the app's permission set.

## Need help?

We install, adapt and support these apps, host the Card Statement OCR server, and build new extensions for your process.
**[Book a 20-minute call](https://midstreamintegrations.com/contact)** · intro@MidstreamIntegrations.com · [MidstreamIntegrations.com](https://www.MidstreamIntegrations.com)
