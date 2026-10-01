**MODULE 3 OF 4**

**Compliance & Governance**

*Building Robust Data Protection Programs*

*⏱ Estimated Reading Time: 20-25 minutes*

**Prepared by Meer Saifulla**

Senior Cybersecurity Consultant & Solution Architect \| Ausan Tech
Solutions

*GRC Study Guide Series*

**📑 Table of Contents**

------------------------------------------------------------------------

  ---------------
  **1.
  Significant
  Data Fiduciary
  Designation**

  ---------------

  ------------
  **2. Data
  Protection
  Impact
  Assessment
  (DPIA)**

  ------------

  ------------
  **3. Data
  Protection
  Officer
  (DPO)**

  ------------

  --------------
  **4.
  Cross-Border
  Data Transfer
  Rules**

  --------------

  ----------------
  **5.
  Record-Keeping &
  Audit
  Obligations**

  ----------------

**1. Significant Data Fiduciary (SDF) Designation**

------------------------------------------------------------------------

Not all Data Fiduciaries are created equal. Organizations processing
large volumes of personal data or handling sensitive information face
enhanced obligations under DPDPA. These are designated as Significant
Data Fiduciaries (SDFs).

+----------------------------------------------------------------------+
| **What Makes a Data Fiduciary "Significant"?**                       |
|                                                                      |
| Section 10(1) empowers the Central Government to notify Data         |
| Fiduciaries as "Significant" based on assessment of these factors:   |
|                                                                      |
| 1.  **Volume and Sensitivity:** Amount and nature of personal data   |
|     processed                                                        |
|                                                                      |
| 2.  **Risk to Rights:** Potential harm to Data Principals\' rights   |
|                                                                      |
| 3.  **Sovereignty Impact:** Effect on India\'s sovereignty and       |
|     integrity                                                        |
|                                                                      |
| 4.  **Electoral Democracy:** Risk to democratic processes            |
|                                                                      |
| 5.  **Security of State:** National security implications            |
|                                                                      |
| 6.  **Public Order:** Impact on public order and safety              |
+----------------------------------------------------------------------+

+----------------------------------------------------------------------+
| **📱 Who is Likely to be Designated as SDF?**                        |
|                                                                      |
| Likely SDFs (Based on Criteria):                                     |
|                                                                      |
| - Large Tech Platforms: Google, Meta, Amazon, Microsoft (billion+    |
|   Indian users)                                                      |
|                                                                      |
| - Telecom Operators: Airtel, Jio, Vi (comprehensive location and     |
|   communication data)                                                |
|                                                                      |
| - Major E-commerce: Flipkart, Amazon India, Paytm (transaction data  |
|   at scale)                                                          |
|                                                                      |
| - Large Banks & Financial Institutions: SBI, HDFC, ICICI (sensitive  |
|   financial data)                                                    |
|                                                                      |
| - Healthcare Platforms: Apollo 24/7, Practo (health data)            |
|                                                                      |
| - Major EdTech: BYJU\'S, Unacademy (children\'s data)                |
|                                                                      |
| Possibly NOT SDFs:                                                   |
|                                                                      |
| - Small e-commerce with limited user base                            |
|                                                                      |
| - Local healthcare clinics with manual records                       |
|                                                                      |
| - SMEs processing minimal personal data                              |
+----------------------------------------------------------------------+

+----------------------------------------------------------------------+
| **⚙ Enhanced Obligations for SDFs (Section 10(2) & Rule 13)**        |
|                                                                      |
| Once notified as SDF, the organization MUST:                         |
|                                                                      |
| 1.  **Appoint Data Protection Officer (DPO) -** Must be based in     |
|     India, responsible to Board                                      |
|                                                                      |
| 2.  **Conduct Periodic DPIA -** Data Protection Impact Assessment    |
|     annually                                                         |
|                                                                      |
| 3.  **Conduct Independent Audits -** External auditor evaluates      |
|     compliance annually                                              |
|                                                                      |
| 4.  **Submit Reports to Board -** Furnish DPIA and audit findings to |
|     Data Protection Board                                            |
|                                                                      |
| 5.  **Algorithm Due Diligence -** Verify algorithmic software        |
|     doesn\'t pose risks to Data Principals                           |
|                                                                      |
| 6.  **Data Localization (if notified) -** Certain sensitive data     |
|     categories may be restricted from cross-border transfer          |
+----------------------------------------------------------------------+

+----------------------------------------------------------------------+
| **⚠️ Consequences of SDF Non-Compliance**                            |
|                                                                      |
| SDFs face the highest penalties under DPDPA:                         |
|                                                                      |
| - Up to ₹250 crores + ₹150 crores for violations and additional      |
|   obligations                                                        |
|                                                                      |
| - Failure to appoint DPO → Penalty                                   |
|                                                                      |
| - Not conducting DPIA/audit → Penalty                                |
|                                                                      |
| - Non-compliance with data localization → Severe penalty             |
|                                                                      |
| ***The designation as SDF is a serious matter that transforms        |
| compliance requirements fundamentally.***                            |
+----------------------------------------------------------------------+

+----------------------------------------------------------------------+
| **💡 Philosophy: Proportionate Regulation**                          |
|                                                                      |
| DPDPA follows the principle of proportionate regulation: Greater     |
| power comes with greater responsibility. Organizations with massive  |
| data processing capabilities and potential to cause large-scale harm |
| face correspondingly stricter obligations.                           |
|                                                                      |
| This approach balances:                                              |
|                                                                      |
| - Not overburdening small businesses (SMEs get lighter compliance)   |
|                                                                      |
| - Ensuring big tech and platforms are held to highest standards      |
|                                                                      |
| - Protecting Data Principals from systemic risks                     |
+----------------------------------------------------------------------+

+----------------------------------------------------------------------+
| **✅ Key Takeaways - Section 1**                                     |
|                                                                      |
| - Central Government notifies SDFs based on 6 statutory factors      |
|                                                                      |
| - Volume, sensitivity, and risk to rights are primary considerations |
|                                                                      |
| - SDFs include large tech platforms, telecoms, major e-commerce,     |
|   banks                                                              |
|                                                                      |
| - Enhanced obligations: DPO, DPIA, audits, algorithmic due diligence |
|                                                                      |
| - Penalties up to ₹250 crores + ₹150 crores for SDF violations       |
|                                                                      |
| - Proportionate regulation: Bigger organizations = stricter          |
|   compliance                                                         |
+----------------------------------------------------------------------+

  -------
  **↑
  Back to
  Top**

  -------

**2. Data Protection Impact Assessment (DPIA)**

------------------------------------------------------------------------

**A Data Protection Impact Assessment (DPIA)** is a systematic
evaluation of data processing activities to identify and mitigate risks
to Data Principals\' rights. Under Section 10(2)(c)(i) and Rule 13, SDFs
must conduct periodic DPIAs.

+----------------------------------------------------------------------+
| **What is a DPIA?**                                                  |
|                                                                      |
| DPIA is a structured process comprising:                             |
|                                                                      |
| 1.  **Description of Rights:** Identify Data Principals\' rights     |
|     that may be affected                                             |
|                                                                      |
| 2.  **Purpose of Processing:** Document why personal data is being   |
|     processed                                                        |
|                                                                      |
| 3.  **Risk Assessment:** Evaluate risks to Data Principals (privacy  |
|     breaches, discrimination, etc.)                                  |
|                                                                      |
| 4.  **Risk Management:** Identify measures to mitigate identified    |
|     risks                                                            |
|                                                                      |
| 5.  **Other Prescribed Matters:** As per DPDP Rules                  |
|                                                                      |
| **Frequency:** At least once every 12 months from SDF notification   |
| date                                                                 |
+----------------------------------------------------------------------+

+----------------------------------------------------------------------+
| **📱 DPIA Example: Social Media Platform**                           |
|                                                                      |
| **Scenario:** A social media platform (SDF) introduces a new         |
| AI-powered "friend recommendation" feature that analyzes user        |
| behavior, location, and interests.                                   |
|                                                                      |
| **DPIA Process:**                                                    |
|                                                                      |
| 1\. Describe Rights Affected:                                        |
|                                                                      |
| - Right to access (users may not know what data is analyzed)         |
|                                                                      |
| - Right to correction (algorithm may use outdated preferences)       |
|                                                                      |
| - Right to object to profiling                                       |
|                                                                      |
| **2. Purpose:** Improve user experience by suggesting relevant       |
| connections                                                          |
|                                                                      |
| 3\. Risk Assessment:                                                 |
|                                                                      |
| - High Risk: Sensitive inferences (religion, political views) may be |
|   derived                                                            |
|                                                                      |
| - Medium Risk: Location tracking may reveal home/work addresses      |
|                                                                      |
| - Low Risk: Basic interest matching (e.g., both like cricket)        |
|                                                                      |
| 4\. Mitigation Measures:                                             |
|                                                                      |
| - Implement consent mechanism specifically for this feature          |
|                                                                      |
| - Allow users to opt-out of behavioral analysis                      |
|                                                                      |
| - Provide transparency report showing what data is used              |
|                                                                      |
| - Regular algorithm audits to detect bias                            |
|                                                                      |
| - Data minimization: Use only necessary attributes                   |
|                                                                      |
| **5. Submit Report:** Significant findings submitted to Data         |
| Protection Board                                                     |
+----------------------------------------------------------------------+

+----------------------------------------------------------------------+
| **📋 DPIA Compliance Checklist**                                     |
|                                                                      |
| **☑** Conduct DPIA within 12 months of SDF notification              |
|                                                                      |
| **☑** Document all processing activities comprehensively             |
|                                                                      |
| **☑** Identify high-risk processing (profiling, children\'s data,    |
| sensitive data)                                                      |
|                                                                      |
| **☑** Assess risks: likelihood and severity                          |
|                                                                      |
| **☑** Design mitigation strategies for each identified risk          |
|                                                                      |
| **☑** Engage independent assessor (external consultant/auditor)      |
|                                                                      |
| **☑** Submit DPIA report with significant observations to Board      |
|                                                                      |
| **☑** Review and update DPIA annually                                |
|                                                                      |
| **☑** Implement recommended safeguards                               |
|                                                                      |
| **☑** Maintain DPIA records for audit                                |
+----------------------------------------------------------------------+

+----------------------------------------------------------------------+
| **✅ Key Takeaways - Section 2**                                     |
|                                                                      |
| - DPIA is mandatory for SDFs, conducted annually                     |
|                                                                      |
| - Systematic process: Describe rights, purpose, assess risks, manage |
|   risks                                                              |
|                                                                      |
| - Must be conducted by independent assessor                          |
|                                                                      |
| - Significant findings reported to Data Protection Board             |
|                                                                      |
| - DPIA is proactive risk management, not reactive compliance         |
|                                                                      |
| - Helps organizations identify privacy issues before they become     |
|   violations                                                         |
+----------------------------------------------------------------------+

  -------
  **↑
  Back to
  Top**

  -------

**3. Data Protection Officer (DPO)**

------------------------------------------------------------------------

**The Data Protection Officer (DPO)** is the linchpin of an SDF\'s
compliance program. Under Section 10(2)(a), every SDF must appoint a
DPO.

+----------------------------------------------------------------------+
| **Who is the Data Protection Officer?**                              |
|                                                                      |
| Legal Requirements (Section 10(2)(a)):                               |
|                                                                      |
| 1.  **Represent the SDF:** Acts as official representative under     |
|     DPDPA                                                            |
|                                                                      |
| 2.  **Based in India:** Must be resident in India (not remote from   |
|     another country)                                                 |
|                                                                      |
| 3.  **Report to Board:** Responsible to Board of Directors or        |
|     similar governing body                                           |
|                                                                      |
| 4.  **Point of Contact:** Interface for grievance redressal with     |
|     Data Principals                                                  |
|                                                                      |
| 5.  **Liaison with Data Protection Board:** Primary contact for      |
|     regulatory interactions                                          |
+----------------------------------------------------------------------+

+----------------------------------------------------------------------+
| **🎯 DPO Duties & Responsibilities**                                 |
|                                                                      |
| 1.  **Compliance Oversight:** Monitor SDF\'s adherence to DPDPA and  |
|     DPDP Rules                                                       |
|                                                                      |
| 2.  **Training & Awareness:** Educate employees on data protection   |
|     obligations                                                      |
|                                                                      |
| 3.  **Policy Development:** Develop and update data protection       |
|     policies                                                         |
|                                                                      |
| 4.  **Grievance Handling:** Manage Data Principal complaints and     |
|     grievances                                                       |
|                                                                      |
| 5.  **DPIA Coordination:** Oversee Data Protection Impact            |
|     Assessments                                                      |
|                                                                      |
| 6.  **Audit Facilitation:** Coordinate independent data audits       |
|                                                                      |
| 7.  **Breach Response:** Lead data breach notification and           |
|     remediation                                                      |
|                                                                      |
| 8.  **Board Reporting:** Regular compliance updates to leadership    |
|                                                                      |
| 9.  **Regulatory Liaison:** Interface with Data Protection Board     |
|                                                                      |
| 10. **Record-Keeping:** Maintain comprehensive compliance            |
|     documentation                                                    |
+----------------------------------------------------------------------+

+----------------------------------------------------------------------+
| **📖 A Day in the Life of a DPO**                                    |
|                                                                      |
| **Morning (9 AM - 12 PM):**                                          |
|                                                                      |
| - Review overnight data breach alerts (none today, thankfully)       |
|                                                                      |
| - Meeting with engineering team about new feature launch - conduct   |
|   quick DPIA review                                                  |
|                                                                      |
| - Approve updated privacy notice for mobile app                      |
|                                                                      |
| - Respond to 3 Data Principal access requests                        |
|                                                                      |
| **Afternoon (2 PM - 5 PM):**                                         |
|                                                                      |
| - Training session for customer support team on handling data        |
|   requests                                                           |
|                                                                      |
| - Review quarterly DPIA report prepared by external consultant       |
|                                                                      |
| - Call with legal team about cross-border data transfer agreement    |
|                                                                      |
| - Update Board presentation on compliance status                     |
|                                                                      |
| **Evening (5 PM - 6 PM):**                                           |
|                                                                      |
| - Review Data Protection Board circular on consent management        |
|                                                                      |
| - Email to CEO: Recommend additional budget for security upgrades    |
+----------------------------------------------------------------------+

+----------------------------------------------------------------------+
| **💡 DPO: Skills and Qualifications**                                |
|                                                                      |
| DPDPA does NOT prescribe specific qualifications, but effective DPOs |
| typically have:                                                      |
|                                                                      |
| - Legal Knowledge: Understanding of DPDPA, IT Act, relevant laws     |
|                                                                      |
| - Technical Expertise: Familiarity with data systems, security,      |
|   encryption                                                         |
|                                                                      |
| - Business Acumen: Balance compliance with business objectives       |
|                                                                      |
| - Communication Skills: Interface with Board, employees, regulators, |
|   Data Principals                                                    |
|                                                                      |
| - Independence: Ability to report concerns without fear              |
|                                                                      |
| *Emerging certifications: CIPP/E (Certified Information Privacy      |
| Professional), CIPM (Certified Information Privacy Manager)*         |
+----------------------------------------------------------------------+

+----------------------------------------------------------------------+
| **✅ Key Takeaways - Section 3**                                     |
|                                                                      |
| - DPO mandatory only for SDFs (not all Data Fiduciaries)             |
|                                                                      |
| - Must be based in India and report to Board of Directors            |
|                                                                      |
| - Represents SDF in all DPDPA matters                                |
|                                                                      |
| - Primary responsibilities: compliance oversight, training, DPIA,    |
|   grievances                                                         |
|                                                                      |
| - No specific qualifications prescribed, but legal + technical       |
|   knowledge essential                                                |
|                                                                      |
| - DPO ensures accountability at highest organizational level         |
+----------------------------------------------------------------------+

  -------
  **↑
  Back to
  Top**

  -------

**4. Cross-Border Data Transfer Rules**

------------------------------------------------------------------------

**Section 16** grants the Central Government power to restrict
cross-border transfer of personal data to specific countries or
territories. This is one of the most debated provisions of DPDPA.

+----------------------------------------------------------------------+
| **Cross-Border Transfer Framework**                                  |
|                                                                      |
| **Section 16(1):** Central Government may, by notification, restrict |
| transfer of personal data to specific countries/territories outside  |
| India.                                                               |
|                                                                      |
| **Default Position:** Until government issues restrictions,          |
| cross-border transfers are generally permitted (subject to consent   |
| and other obligations).                                              |
|                                                                      |
| **Rule 13(4) - SDF Data Localization:** SDFs must ensure that        |
| certain personal data categories (as notified by government) are     |
| processed only in India with restrictions on cross-border flow.      |
+----------------------------------------------------------------------+

+-------------------------------------------------------------------+
| **⚠️ What We\'re Waiting For**                                    |
|                                                                   |
| As of December 2025, the Central Government has NOT YET NOTIFIED: |
|                                                                   |
| - Which countries/territories are restricted for data transfers   |
|                                                                   |
| - Which personal data categories must be localized for SDFs       |
|                                                                   |
| - Criteria for "safe" vs. "unsafe" countries                      |
|                                                                   |
| Until notifications are issued, organizations should:             |
|                                                                   |
| - Continue existing cross-border transfers (with valid consent)   |
|                                                                   |
| - Monitor MeitY website for notifications                         |
|                                                                   |
| - Prepare contingency plans for potential restrictions            |
|                                                                   |
| - Document all cross-border data flows                            |
+-------------------------------------------------------------------+

+----------------------------------------------------------------------+
| **📱 Cross-Border Transfer Scenarios**                               |
|                                                                      |
| **Scenario 1: Cloud Storage**                                        |
|                                                                      |
| Indian startup uses AWS servers in Singapore for customer data       |
| storage.                                                             |
|                                                                      |
| **Current Status:** ✅ Permitted (no restrictions notified yet)      |
|                                                                      |
| **Requirements:** Valid consent, security safeguards, data           |
| processing agreement with AWS                                        |
|                                                                      |
| **Future Risk:** If government restricts transfers to Singapore,     |
| must migrate to Indian servers                                       |
|                                                                      |
| **Scenario 2: SDF Healthcare Platform**                              |
|                                                                      |
| Major health-tech platform (SDF) processes patient data.             |
|                                                                      |
| **Current Status:** ✅ Can use global cloud providers                |
|                                                                      |
| **Likely Future:** If "health data" is notified under Rule 13(4),    |
| must localize in India                                               |
|                                                                      |
| **Preparation:** Architect systems to enable rapid localization if   |
| needed                                                               |
|                                                                      |
| **Scenario 3: Multinational HR System**                              |
|                                                                      |
| Global company with Indian employees uses centralized HR system in   |
| USA.                                                                 |
|                                                                      |
| **Current Status:** ✅ Permitted with employee consent               |
|                                                                      |
| **Compliance:** Data processing agreement, security measures,        |
| employee informed consent                                            |
+----------------------------------------------------------------------+

**Comparison: DPDPA vs. GDPR on Cross-Border Transfers**

  ------------------------------------------------------------------
  **Aspect**       **DPDPA (India)**        **GDPR (EU)**
  ---------------- ------------------------ ------------------------
  Default          Permitted until          Restricted unless
                   restricted               adequate safeguards

  Mechanism        Government notification  Adequacy decisions,
                   (blacklist)              SCCs, BCRs (whitelist)

  Localization     Possible for SDFs (Rule  No mandatory
                   13(4))                   localization

  Current Status   No restrictions notified 100+ adequacy decisions
                   yet                      in place
  ------------------------------------------------------------------

+----------------------------------------------------------------------+
| **✅ Key Takeaways - Section 4**                                     |
|                                                                      |
| - Section 16: Government can restrict transfers to specific          |
|   countries                                                          |
|                                                                      |
| - No restrictions notified yet - transfers currently permitted (with |
|   consent)                                                           |
|                                                                      |
| - SDFs may face data localization for certain sensitive categories   |
|   (Rule 13(4))                                                       |
|                                                                      |
| - Organizations should map and document all cross-border data flows  |
|                                                                      |
| - Monitor MeitY notifications for updates                            |
|                                                                      |
| - DPDPA uses "restriction" model vs. GDPR\'s "adequacy" model        |
+----------------------------------------------------------------------+

  -------
  **↑
  Back to
  Top**

  -------

**5. Record-Keeping & Audit Obligations**

------------------------------------------------------------------------

Effective compliance requires meticulous documentation. DPDPA imposes
record-keeping obligations to ensure accountability and enable audits.

**Record-Keeping Requirements**

+-------------------------------------------------------------+
| **📋 Essential Records Every Data Fiduciary Must Maintain** |
|                                                             |
| **1. Consent Logs:**                                        |
|                                                             |
| - When consent was obtained                                 |
|                                                             |
| - How consent was obtained (method)                         |
|                                                             |
| - What consent was for (purpose)                            |
|                                                             |
| - Consent withdrawal records                                |
|                                                             |
| **2. Processing Records:**                                  |
|                                                             |
| - Data inventory (what personal data is held)               |
|                                                             |
| - Processing activities log                                 |
|                                                             |
| - Purpose and legal basis for each processing activity      |
|                                                             |
| - Data retention periods                                    |
|                                                             |
| **3. Data Sharing Records:**                                |
|                                                             |
| - List of third parties with whom data is shared            |
|                                                             |
| - Data processing agreements with processors                |
|                                                             |
| - Cross-border transfer documentation                       |
|                                                             |
| **4. Data Principal Requests:**                             |
|                                                             |
| - Access requests and responses                             |
|                                                             |
| - Correction/erasure requests and actions taken             |
|                                                             |
| - Grievances filed and resolutions                          |
|                                                             |
| **5. Breach Register:**                                     |
|                                                             |
| - Details of all data breaches (even minor ones)            |
|                                                             |
| - Actions taken to remediate                                |
|                                                             |
| - Notifications sent (to Board and Data Principals)         |
|                                                             |
| **6. Security Measures:**                                   |
|                                                             |
| - Documentation of security safeguards implemented          |
|                                                             |
| - Vulnerability assessment reports                          |
|                                                             |
| - Employee training records                                 |
+-------------------------------------------------------------+

**Independent Data Audits (SDFs Only)**

+----------------------------------------------------------------------+
| **Data Audit Requirements (Section 10(2)(b) & Rule 13)**             |
|                                                                      |
| **Who Must Conduct:** All Significant Data Fiduciaries               |
|                                                                      |
| **Frequency:** At least once every 12 months                         |
|                                                                      |
| **Auditor:** Must be Independent (external auditor, not internal     |
| team)                                                                |
|                                                                      |
| **Scope:** Evaluate compliance with ALL DPDPA provisions and DPDP    |
| Rules                                                                |
|                                                                      |
| **Reporting:** Submit audit report with significant observations to  |
| Data Protection Board                                                |
+----------------------------------------------------------------------+

+-------------------------------------------------------------+
| **📋 Audit Checklist for SDFs**                             |
|                                                             |
| **Pre-Audit Preparation:**                                  |
|                                                             |
| **☑** Appoint independent auditor (external firm)           |
|                                                             |
| **☑** Define audit scope and timeline                       |
|                                                             |
| **☑** Gather all compliance documentation                   |
|                                                             |
| **☑** Prepare data flow maps and inventories                |
|                                                             |
| **During Audit:**                                           |
|                                                             |
| **☑** Review consent mechanisms and logs                    |
|                                                             |
| **☑** Test security safeguards (technical + organizational) |
|                                                             |
| **☑** Verify Data Principal rights exercise processes       |
|                                                             |
| **☑** Assess DPIA quality and implementation                |
|                                                             |
| **☑** Review third-party processor agreements               |
|                                                             |
| **☑** Check compliance with children\'s data protections    |
|                                                             |
| **☑** Evaluate breach response procedures                   |
|                                                             |
| **Post-Audit:**                                             |
|                                                             |
| **☑** Receive audit report with findings                    |
|                                                             |
| **☑** Address identified gaps                               |
|                                                             |
| **☑** Submit significant observations to Board              |
|                                                             |
| **☑** Implement remediation measures                        |
|                                                             |
| **☑** Plan next annual audit                                |
+-------------------------------------------------------------+

+----------------------------------------------------------------------+
| **💡 Best Practices: Building an Audit-Ready Organization**          |
|                                                                      |
| **1. Maintain Real-Time Records:** Don\'t scramble before audit;     |
| maintain records continuously                                        |
|                                                                      |
| **2. Use Technology:** Implement consent management platforms, data  |
| mapping tools                                                        |
|                                                                      |
| **3. Assign Ownership:** Clear responsibility for each compliance    |
| area (e.g., DPO owns DPIA, CISO owns security)                       |
|                                                                      |
| **4. Regular Internal Audits:** Don\'t wait for annual external      |
| audit; conduct quarterly internal reviews                            |
|                                                                      |
| **5. Training:** Ensure all employees understand their data          |
| protection responsibilities                                          |
|                                                                      |
| **6. Third-Party Management:** Audit processors and vendors          |
| periodically                                                         |
|                                                                      |
| **7. Documentation Culture:** *"If it\'s not documented, it didn\'t  |
| happen"*                                                             |
+----------------------------------------------------------------------+

+----------------------------------------------------------------------+
| **✅ Key Takeaways - Section 5**                                     |
|                                                                      |
| - All Data Fiduciaries must maintain comprehensive records (consent, |
|   processing, sharing, breaches)                                     |
|                                                                      |
| - SDFs must conduct independent data audits annually                 |
|                                                                      |
| - Audit reports with significant findings submitted to Data          |
|   Protection Board                                                   |
|                                                                      |
| - Records enable accountability and facilitate compliance            |
|   verification                                                       |
|                                                                      |
| - Best practice: Real-time documentation, not pre-audit scramble     |
|                                                                      |
| - Technology tools (consent management, data mapping) are essential  |
|   at scale                                                           |
+----------------------------------------------------------------------+

  -------
  **↑
  Back to
  Top**

  -------

**📚 Recommended Reading & Resources**

------------------------------------------------------------------------

+----------------------------------------------------------+
| **Primary Legislation:**                                 |
|                                                          |
| DPDPA 2023 - Section 10 (SDF), Section 16 (Cross-border) |
+----------------------------------------------------------+

+--------------------------------------------------------+
| **DPDP Rules:**                                        |
|                                                        |
| Rule 13: SDF Additional Obligations (DPIA, Audit, DPO) |
+--------------------------------------------------------+

+---------------------------------------------------------------------+
| **Government Resources:**                                           |
|                                                                     |
| MeitY - Monitor for SDF notifications and cross-border restrictions |
+---------------------------------------------------------------------+

+------------------------------------------------------------------------------+
| **✅ Self-Assessment Quiz**                                                  |
|                                                                              |
| Test your understanding of Module 3 concepts:                                |
|                                                                              |
| +--------------------------------------------------------------------------+ |
| | **1. What are the 6 factors for designating a Significant Data           | |
| | Fiduciary?**                                                             | |
| |                                                                          | |
| | **Hide Answer**                                                          | |
| |                                                                          | |
| | +----------------------------------------------------------------------+ | |
| | | **Answer:**                                                          | | |
| | |                                                                      | | |
| | | Section 10(1) lists 6 factors: (1) Volume and sensitivity of         | | |
| | | personal data, (2) Risk to rights of Data Principals, (3) Potential  | | |
| | | impact on sovereignty and integrity of India, (4) Risk to electoral  | | |
| | | democracy, (5) Security of the State, (6) Public order.              | | |
| | +----------------------------------------------------------------------+ | |
| +--------------------------------------------------------------------------+ |
|                                                                              |
| +--------------------------------------------------------------------------+ |
| | **2. What is a DPIA and how often must SDFs conduct it?**                | |
| |                                                                          | |
| | **Hide Answer**                                                          | |
| |                                                                          | |
| | +----------------------------------------------------------------------+ | |
| | | **Answer:**                                                          | | |
| | |                                                                      | | |
| | | Data Protection Impact Assessment is a systematic evaluation of data | | |
| | | processing to identify and mitigate risks. SDFs must conduct DPIA at | | |
| | | least once every 12 months from SDF notification. It includes:       | | |
| | | description of rights, purpose of processing, risk assessment, and   | | |
| | | risk management measures.                                            | | |
| | +----------------------------------------------------------------------+ | |
| +--------------------------------------------------------------------------+ |
|                                                                              |
| +--------------------------------------------------------------------------+ |
| | **3. What are the key requirements for a Data Protection Officer?**      | |
| |                                                                          | |
| | **Hide Answer**                                                          | |
| |                                                                          | |
| | +----------------------------------------------------------------------+ | |
| | | **Answer:**                                                          | | |
| | |                                                                      | | |
| | | Under Section 10(2)(a), DPO must: (1) Represent the SDF under DPDPA, | | |
| | | (2) Be based in India, (3) Be responsible to Board of Directors, (4) | | |
| | | Serve as point of contact for grievance redressal, (5) Interface     | | |
| | | with Data Protection Board.                                          | | |
| | +----------------------------------------------------------------------+ | |
| +--------------------------------------------------------------------------+ |
|                                                                              |
| +--------------------------------------------------------------------------+ |
| | **4. Can personal data currently be transferred outside India freely?**  | |
| |                                                                          | |
| | **Hide Answer**                                                          | |
| |                                                                          | |
| | +----------------------------------------------------------------------+ | |
| | | **Answer:**                                                          | | |
| | |                                                                      | | |
| | | YES, currently (as of Dec 2025). Section 16 allows government to     | | |
| | | restrict transfers, but NO restrictions have been notified yet.      | | |
| | | Cross-border transfers are permitted with valid consent and          | | |
| | | appropriate safeguards. However, SDFs should prepare for potential   | | |
| | | future restrictions under Rule 13(4).                                | | |
| | +----------------------------------------------------------------------+ | |
| +--------------------------------------------------------------------------+ |
|                                                                              |
| +--------------------------------------------------------------------------+ |
| | **5. What records must all Data Fiduciaries maintain?**                  | |
| |                                                                          | |
| | **Hide Answer**                                                          | |
| |                                                                          | |
| | +----------------------------------------------------------------------+ | |
| | | **Answer:**                                                          | | |
| | |                                                                      | | |
| | | Essential records include: (1) Consent logs, (2) Processing records  | | |
| | | and data inventory, (3) Data sharing records and third-party         | | |
| | | agreements, (4) Data Principal requests and responses, (5) Breach    | | |
| | | register, (6) Security measures documentation. These enable          | | |
| | | accountability and compliance verification.                          | | |
| | +----------------------------------------------------------------------+ | |
| +--------------------------------------------------------------------------+ |
+------------------------------------------------------------------------------+
