# SAP Capstone Project — Blueprint Document
## Nexora IT Services Pvt. Ltd.

**Student:** [YOUR FULL NAME]  
**Roll Number:** [YOUR ROLL NUMBER]  
**Program:** SAP Integration Developer  
**Batch:** 2027_SAP(OE)  
**Institution:** KIIT DU  
**Submission Date:** April 21, 2026  

---

## 📋 Project Overview

This repository contains the Capstone Project submission for the SAP Integration Developer program at KIIT DU. The project is a **SAP Blueprint Document** that defines the complete enterprise structure and configuration steps for a fictitious Indian IT services company — **Nexora IT Services Pvt. Ltd.**

The blueprint covers the three core SAP functional modules:
- **FI** — Financial Accounting
- **MM** — Materials Management
- **SD** — Sales & Distribution

---

## 🏢 About Nexora IT Services Pvt. Ltd.

| Field | Details |
|-------|---------|
| Company | Nexora IT Services Pvt. Ltd. |
| Industry | Information Technology & IT-Enabled Services |
| Headquarters | Bengaluru, Karnataka, India |
| Delivery Centres | NX01 (Bengaluru), NX02 (Hyderabad) |
| Currency | INR |
| Fiscal Year | April–March (Indian FY) |
| SAP System | SAP ECC 6.0 / S/4HANA |

---

## 📁 Repository Structure

```
SAP-Capstone-Blueprint/
│
├── README.md                          ← This file
└── SAP_Blueprint_Nexora.docx          ← Full project report (Word format)
```

---

## 📄 Document Contents

1. **Project Title & Problem Statement**
2. **Company Profile** — Nexora overview and organizational context
3. **FI Module Configuration** — Company Code, COA, Fiscal Year, Document Types
4. **MM Module Configuration** — Plants, Storage Locations, Purchase Org, IT Material Types
5. **SD Module Configuration** — Sales Org, Distribution Channels, Divisions, Sales Areas
6. **Cross-Module Integration** — FI-MM and FI-SD posting flows
7. **Tech Stack & T-Code Reference**
8. **Unique Highlights**
9. **Future Improvements**
10. **Conclusion**

---

## 🔧 SAP Modules Covered

### Financial Accounting (FI)
- Company Code: `NXPL`
- Chart of Accounts: `NXCA`
- Fiscal Year Variant: `V3` (April–March)
- Key T-Codes: OX02, OB29, OB62, OB37

### Materials Management (MM)
- Plants: `NX01` (Bengaluru), `NX02` (Hyderabad)
- Purchase Org: `NX_PO` (Central Procurement)
- Key T-Codes: OX10, OX09, OX08, OX18

### Sales & Distribution (SD)
- Sales Org: `NX_SO`
- Distribution Channels: DI (Direct), PT (Partner), OF (Offshore)
- Divisions: SW (Software), IN (Infrastructure), CS (Consulting)
- Key T-Codes: OVX5, OVX1, OVX2, OVX4

---

## 📌 Key Highlights

- IT Services company blueprint — tailored for service-based revenue, milestone billing, and GST @ 18%
- IT-specific material types (ZITW for hardware, ZSWL for software licenses)
- Service Entry Sheet (ML81N) integration for subcontracting and managed services
- Three service divisions with independent pricing and revenue reporting
- Full FI-MM-SD integration map with IT-sector transaction scenarios

---

## 🚀 Future Scope

- SAP PS (Project System) — WBS and project-based billing
- SAP HR/HCM — Hire-to-Retire configuration
- S/4HANA migration with Universal Journal (ACDOCA)
- Full GST (TAXINN) with e-invoicing integration

---

*Submitted as part of the KIIT DU SAP Integration Developer Capstone Program — April 2026.*
