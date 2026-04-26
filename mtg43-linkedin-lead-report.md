# MTG-43: LinkedIn Lead Generation Report (Revised)
**Date:** 2026-04-26 (Revised after board feedback)  
**Prepared by:** CMO Agent  
**Task:** [MTG-43](/MTG/issues/MTG-43) — Job Scraping for n8n Automation Leads

---

## Revision Notes

Board feedback addressed:
1. **Role focus** — removed customer-facing roles (receptionists, intake callers). Leads now focus on **operations, document handling, and chatbot/automation demand**.
2. **Link verification** — LinkedIn job posting URLs expire and redirect to category pages. This revised list uses three tiers of URL quality:
   - `VERIFIED ACTIVE` — page was fetched and content confirmed
   - `SPECIFIC LINK` — direct job URL found in search results; may expire (use company LinkedIn as fallback)
   - Category links removed entirely
3. **Lead types added** — "Direct n8n Demand" (companies actively posting for n8n work on n8ndevs.com/Upwork) represent the highest-quality leads.

---

## Scoring Methodology

Each lead scored 1–10 on three dimensions:
- **Business Fit** — how well n8n solves their documented need
- **Pain Intensity** — how manual/repetitive the workflow is
- **Buy Likelihood** — for "Direct n8n Demand" leads: already buying (10); for operations/doc roles: 7–8

**Composite Score** = average. Priority: HOT (≥9.0), HIGH (7.5–8.9), MEDIUM (<7.5)

---

## Lead Type Summary

| Type | Count | Avg Score | Description |
|------|-------|-----------|-------------|
| Direct n8n Demand | 7 | 9.5 | Companies actively posting n8n/automation jobs — already buying |
| Workflow Automation Role | 2 | 9.2 | Companies hiring an automation specialist — they've committed budget |
| Operations/Document Role | 7 | 8.1 | Companies hiring ops/doc coordinator — indicating manual workflow pain |
| Legal Operations Role | 2 | 7.5 | Law firm document/admin roles — document-only, no client-facing |

---

## HOT Leads (Score ≥ 9.0)

### Direct n8n Demand — Companies Already Buying

**1. German Property Management Co — Email Triage Automation (Score: 9.7)**
- **URL:** https://n8ndevs.com/jobs/VRTUiEV4TNOPWXbuCfIgog *(VERIFIED ACTIVE)*
- **Workflow:** Outlook tenant inquiry emails manually reviewed, evaluated, and answered. Wants: auto-triage + Claude AI evaluation + auto-scheduling or rejection
- **n8n Solution:** Outlook API → Claude AI → conditional calendar booking or email send
- **Budget:** $550/project | **Status:** Actively hiring

**2. Australian Growth Agency (Automotive Detailing) — AI Sales Agent (Score: 9.7)**
- **URL:** https://n8ndevs.com/jobs/Z4pHixOxT6i7bcU8tV0WkA *(VERIFIED ACTIVE)*
- **Workflow:** Manual lead qualification and CRM pipeline updates across detailing clients
- **n8n Solution:** CRM trigger → AI qualification → GoHighLevel pipeline automation
- **Budget:** $1,000/project | **Location:** Australia/US | **Status:** Actively hiring

**3. Small Business — WhatsApp Sales Chatbot (Score: 9.7)**
- **URL:** https://n8ndevs.com/jobs/l4Ea1azPQnafBa6O8BKEVA *(VERIFIED ACTIVE)*
- **Workflow:** No automated response to WhatsApp inquiries; manual follow-up; no CRM logging
- **n8n Solution:** WhatsApp Business API → Claude AI chatbot → Google Sheets CRM + auto follow-up
- **Budget:** $13–25/module (5-module project) | **Status:** Actively hiring

**4. Lumis Compute — Supply Chain Intelligence (Score: 9.7)**
- **URL:** https://n8ndevs.com/jobs/zzFaXLRESuC8CIDTzcfLRg *(VERIFIED ACTIVE)*
- **Workflow:** Manual supplier data gathering, manual credibility scoring, manual outreach to leads
- **n8n Solution:** n8n + Make: scraping → OpenAI scoring → Instantly.ai email trigger
- **Budget:** $500/project | **Status:** Actively hiring

**5. Marketing Agency — n8n + ClickUp + Drive Document Automation (Score: 9.3)**
- **URL:** https://n8ndevs.com/jobs/3iPGypz4T7ODxGoG3yoiyA *(VERIFIED ACTIVE)*
- **Workflow:** Manual ClickUp updates, file management across Google Drive/Dropbox, manual AI tool processing
- **n8n Solution:** ClickUp webhook → file routing + AI pipeline + Drive/Dropbox sync
- **Budget:** $20–60/hr ongoing | **Status:** Actively hiring

**6. B2B SaaS — HubSpot Lead Validation via n8n (Score: 9.3)**
- **URL:** https://n8ndevs.com/jobs/TEuL0ajEQZKCgFHrICWckA *(VERIFIED ACTIVE)*
- **Workflow:** Manual GA4 event processing, manual email/phone validation, manual HubSpot sync
- **n8n Solution:** GA4 webhook → validation API → HubSpot update + lead scoring
- **Budget:** $40–60/hr | **Status:** Actively hiring

**7. Australian Accounting Firm — Operations Automation (Score: 9.3)**
- **URL:** https://www.upwork.com/freelance-jobs/apply/Automation-Systems-Operator-n8n-Business-Process-Client-Facing-Long-Term-Partner_~022038887339875660708/ *(Upwork March 31 2026)*
- **Workflow:** 29-year-old firm with fully manual admin operations, client document handling, billing
- **n8n Solution:** Client form → document requests + appointment scheduling + billing + weekly reports
- **Budget:** $800 fixed + ongoing contract | **Location:** Australia | **Status:** Actively hiring

### Workflow Automation Roles — Budget Committed

**8. Talent Global LLC (Luxury Design Showroom) — Spain (Score: 9.0)**
- **URL:** https://www.linkedin.com/jobs/view/automation-workflow-specialist-odoo-at-talent-global-llc-4391695667 *(VERIFIED ACTIVE)*
- **Workflow:** Manual order management, manual inventory, manual CRM/client workflows in Odoo
- **n8n Solution:** Odoo webhook → eCommerce sync + CRM update + inventory alert + payment workflow
- **Tools already in use:** Odoo, Make.com, Bill.com — n8n can replace Make here

**9. Multiple German SMBs — KI Automation (n8n/Make/Zapier) (Score: 9.3)**
- **URL:** https://www.growthroles.com/jobs/freelancer-im-bereich-ki-automation-u-a-in-marketing-sales-e-commerce-it-b2b-prozesse-n8n-make-zapier-uipath-python-feeab491 *(VERIFIED ACTIVE)*
- **Workflow:** Manual marketing, sales, e-commerce, IT and B2B processes across multiple German firms
- **n8n Solution:** Full workflow automation suite — one freelancer posting represents multiple SMB clients

---

## HIGH Leads (Score 7.7–8.9)

| # | Company | Sector | Country | Score | Job URL | Workflow Pain |
|---|---------|--------|---------|-------|---------|---------------|
| 10 | FreezPak Logistics | Import/Export | USA | 8.7 | [LinkedIn](https://www.linkedin.com/jobs/view/import-export-coordinator-at-freezpak-logistics-4374774288) ✓ | Manual BL/invoice/customs docs; shipment tracking; compliance reports |
| 11 | SLC TRADE | Logistics/FTZ | USA | 8.7 | [LinkedIn](https://www.linkedin.com/jobs/view/logistics-operations-coordinator-at-slc-trade-4377997488) ✓ | FTZ customs docs; inventory reconciliation; billing; KPI reports |
| 12 | Starlux Logistics | Import/Export | USA | 8.3 | [LinkedIn](https://www.linkedin.com/jobs/view/operations-coordinator-operations-specialist-import-%2B-export-at-starlux-logistics-north-america-4346486762) | Import/export docs; shipment coordination; vendor communication |
| 13 | EHIF | Construction | UAE | 8.0 | [Bayt](https://www.bayt.com/en/uae/jobs/document-controller-74228248/) | Document filing; distribution; version tracking; compliance records |
| 14 | Horizonhr Consultancy | HR/Consulting | UAE | 8.0 | [Bayt](https://www.bayt.com/en/uae/jobs/document-controller-74202823/) | Document intake; registration; distribution; version control; archiving |
| 15 | CEEIC | Engineering | Saudi Arabia | 7.7 | [Bayt](https://www.bayt.com/en/saudi-arabia/jobs/document-controller-74108720/) | Technical document circulation; approval tracking; progress status |
| 16 | Al Jomaih Energy & Water | Energy | Saudi Arabia | 7.7 | [Bayt](https://www.bayt.com/en/saudi-arabia/jobs/document-controller-74160781/) | Document compliance; tracking; regulatory reporting |
| 17 | Gleeson Recruitment (law firm) | Legal Ops | UK | 7.7 | [LinkedIn](https://uk.linkedin.com/jobs/view/legal-administrator-at-gleeson-recruitment-group-3780115756) | Legal document management; case file creation; deadline tracking |

✓ = page content verified

---

## MEDIUM Leads

| # | Company | Sector | Country | Score | URL |
|---|---------|--------|---------|-------|-----|
| 18 | MYTILINEOS S.A. | Legal Ops | UK | 7.3 | [LinkedIn](https://uk.linkedin.com/jobs/view/legal-administration-assistant-at-mytilineos-s-a-3493880181) |

---

## Link Reliability Guide

- **n8ndevs.com job URLs** — stable, purpose-built job board for n8n work; links persist
- **Upwork job URLs** — moderately stable; use within a few weeks
- **Bayt.com job URLs** — stable individual listing pages; Bayt listings stay up longer than LinkedIn
- **LinkedIn `/jobs/view/` URLs** — expire in 30–90 days, redirect to category pages. Always note the job number in the URL and fall back to the company's LinkedIn page

---

## Recommended Outreach Order

1. **n8ndevs.com leads (1–7)** — highest intent, already spending; reach out via the original Upwork/Freelancer posting
2. **Talent Global LLC (Spain)** — verified active LinkedIn; automation budget committed
3. **GrowthRoles Germany posting** — explicitly n8n-aware; one contact = multiple SMB clients
4. **FreezPak Logistics** — family-owned, verified active LinkedIn; document automation pitch is clean
5. **UAE/Saudi Bayt.com document controller roles** — pitch to hiring manager: "before you hire a DC, let me show you how n8n automates 80% of that role"

---

## Files
- **Lead CSV (revised):** `jobs-data/jobs/leadgen/linkedin_leads_mtg43.csv` — 18 leads, scored and ranked
- **Prev report:** replaced in-place
