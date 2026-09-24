# 📘 DPDP Audit Engine Documentation

## 📌 Overview
This repository provides structured documentation and templates for conducting **Digital Personal Data Protection Act (DPDPA) 2023 audits**.  
It defines a complete lifecycle framework: **Discovery → Gap Assessment → Remediation → Closure**, with consolidated deliverables for auditors and management.

---

## 🎯 Objectives
- Identify and classify sensitive data across systems (**Data Discovery**)
- Assess compliance gaps against DPDPA and related frameworks (**Gap Assessment**)
- Implement corrective actions and validate controls (**Remediation**)
- Document closure, residual risks, and sign‑off (**Final Audit Closure**)
- Provide clear deliverables: **Data Inventory Map, Prioritized Gap Report, VAPT Vulnerability Sign‑Off**

---

## 🛠️ Tools Integrated
The audit engine leverages **open‑source/freeware tools** via APIs:

- **PIICatcher** → Database PII scanning  
- **Presidio** → SaaS/text PII detection  
- **OWASP ZAP** → Web application vulnerability scanning  
- **Fides** → Compliance mapping (RoPA, DPIA)  
- **OpenMetadata / DataHub** → Metadata lineage and audit logs  
- **Apache Atlas** → Audit trail and lineage reporting  

---

## 📑 Documentation Lifecycle

### Phase 1 – Data Discovery
- [`1.Data_Discovery.md`](./06-dpdp-act-documentation/template/1.Data_Discovery.md)

### Phase 2 – Gap Assessment
- [`2.Gap_Assessment.md`](./06-dpdp-act-documentation/template/2.Gap_Assessment.md)
- [`3.Gap_Analysis_Report.md`](./06-dpdp-act-documentation/template/3.Gap_Analysis_Report.md)

### Phase 3 – Remediation
- [`4.Remediation_Plan.md`](./06-dpdp-act-documentation/template/4.Remediation_Plan.md)

### Phase 4 – Closure
- [`5.Final_Audit_Closure_Report.md`](./06-dpdp-act-documentation/template/5.Final_Audit_Closure_Report.md)
  
### Deliverables
- [`6.Deliverables.md`](./06-dpdp-act-documentation/template/6.Deliverables.md) 

### Master Index
- [`0.Master_Index.md`](./06-dpdp-act-documentation/template/0.Master_Index.md) → Table of contents linking all phases

---

## 📊 Usage Notes
- Follow the lifecycle in order: **Discovery → Gap → Remediation → Closure**  
- Each `.md` file is modular and can be updated independently  
- Deliverables provide consolidated outputs for management and auditors  
- Architecture diagrams and evidence indexes should be added under **Appendices** in each phase document  

---

## ✅ Next Steps
- Populate templates with real audit findings  
- Attach network/data flow diagrams in appendices  
- Use tool APIs (PIICatcher, Presidio, ZAP, Fides, Atlas) to automate evidence collection  
- Update deliverables for sign‑off by auditors and management
