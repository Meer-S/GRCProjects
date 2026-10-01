**MODULE 2 OF 4**

**Rights & Obligations**

        *Data Principal Rights and Data Fiduciary Obligations*
        
        *⏱ Estimated Reading Time: 18-22 minutes*

**Prepared by Meer Saifulla**

        Senior Cybersecurity Consultant & Solution Architect \| Ausan Tech
        Solutions
        
        *GRC Study Guide Series*

**📑 Table of Contents**

  **1. Data
  Principal
  Rights
  (Sections
  11-15)**

   **2. Data
  Fiduciary
  Obligations
  (Sections
  8-10)**

   **3.
  Consent
  Manager
  Framework
  (Section
  15)**

  **4. Notice &
  Transparency
  Requirements**

  **5. Data
  Security &
  Protection
  Measures**

  ------------

**1. Data Principal Rights (Sections 11-15)**

------------------------------------------------------------------------

Chapter 3 of the DPDPA 2023 establishes comprehensive rights for Data
Principals - individuals whose personal data is being processed. These
rights empower you to control your personal information and hold Data
Fiduciaries accountable.

          +----------------------------------------------------------------------+
          | **💡 Fundamental Principle**                                         |
          |                                                                      |
          | Under DPDPA, **YOU own your data.** Data Fiduciaries are merely      |
          | custodians who must respect your rights and process your data only   |
          | as you\'ve consented or as law permits. These rights are not         |
          | privileges - they\'re legal entitlements backed by penalties for     |
          | non-compliance.                                                      |
          +----------------------------------------------------------------------+

**Right to Access Information about Personal Data (Section 11)**

Section 11 grants Data Principals the right to obtain from the Data
Fiduciary:

          +----------------------------------------------------------------------+
          | **📋 What You Can Request Under Section 11**                         |
          |                                                                      |
          | 1.  **Summary of Personal Data:** A summary of what personal data    |
          |     the Data Fiduciary is processing about you                       |
          |                                                                      |
          | 2.  **Processing Activities:** Details of what the Data Fiduciary is |
          |     doing with your data (collection, storage, sharing, etc.)        |
          |                                                                      |
          | 3.  **Identities of Third Parties:** Who else has received your      |
          |     personal data from this Data Fiduciary                           |
          |                                                                      |
          | 4.  **Description of Shared Data:** Exactly what data was shared     |
          |     with each third party                                            |
          |                                                                      |
          | 5.  **Any Other Information:** As may be prescribed in DPDP Rules    |
          +----------------------------------------------------------------------+

          +----------------------------------------------------------------------+
          | **📱 Real-World Example: Exercising Right to Access**                |
          |                                                                      |
          | **Scenario:** Rajesh signed up for an online fitness app 2 years     |
          | ago. He\'s concerned about what data the app has collected.          |
          |                                                                      |
          | **Action:** Rajesh submits a request under Section 11 through the    |
          | app\'s privacy settings.                                             |
          |                                                                      |
          | **Data Fiduciary Must Provide:**                                     |
          |                                                                      |
          | - Summary: "We have your name (Rajesh Kumar), email (\[email         |
          |   protected\]), phone (98XXXXXXXX), date of birth, weight/height     |
          |   history, workout logs from Jan 2023-Dec 2024, location data from   |
          |   247 workout sessions"                                              |
          |                                                                      |
          | - Processing: "We collect this data through app inputs and device    |
          |   sensors. We store it on AWS servers in Mumbai. We analyze it to    |
          |   provide personalized workout recommendations."                     |
          |                                                                      |
          | - Third Parties: "We\'ve shared your email with MailChimp (for       |
          |   newsletters), your workout stats with Google Analytics             |
          |   (anonymized), and your location data with Mapbox (for route        |
          |   mapping)"                                                          |
          +----------------------------------------------------------------------+

**Right to Correction and Erasure about Personal Data (Section 12)**

Section 12 gives you two important rights:

            +----------------------------------------------------------------------+
            | **Right to Correction, Completion, and Updating**                    |
            |                                                                      |
            | If your personal data is inaccurate, incomplete, or outdated, you    |
            | can request the Data Fiduciary to:                                   |
            |                                                                      |
            | **Correct** inaccurate or misleading personal data                   |
            |                                                                      |
            | **Complete** incomplete personal data                                |
            |                                                                      |
            | **Update** outdated personal data                                    |
            |                                                                      |
            | **Timeline:** DPDP Rules 2025 prescribe that Data Fiduciaries must   |
            | respond within a reasonable timeframe                                |
            +----------------------------------------------------------------------+
            
            +----------------------------------------------------------------------+
            | **Right to Erasure ("Right to be Forgotten")**                       |
            |                                                                      |
            | You can request deletion of your personal data. The Data Fiduciary   |
            | **must erase** your data unless:                                     |
            |                                                                      |
            | - Retention is necessary for the specified purpose (e.g., ongoing    |
            |   service delivery or by Court Orders)                               |
            |                                                                      |
            | - Retention is required for compliance with any law (e.g., tax       |
            |   records for 6 years and call detail records (CDRs) for 2 years)    |
            |                                                                      |
            | ***Important: "Right to erasure" is NOT absolute. Legitimate         |
            | business or legal needs can override it.***                          |
            +----------------------------------------------------------------------+

          +----------------------------------------------------------------------+
          | 📖 Example: Right to Correction vs. Right to Erasure                |
          |                                                                      |
          | **Correction Example:**                                              |
          |                                                                      |
          | Priya notices her e-commerce account shows her old address. She      |
          | requests correction under Section 12(2). The platform must update    |
          | her address to the new one.                                          |
          |                                                                      |
          | **Erasure Example:**                                                 |
          |                                                                      |
          | Amit closed his streaming subscription 6 months ago. He requests     |
          | erasure of his viewing history under Section 12(3).                  |
          |                                                                      |
          | **Outcome:** The platform must delete his viewing history UNLESS     |
          | they need it for ongoing investigations (e.g., copyright             |
          | infringement case) or legal compliance (e.g., maintaining records    |
          | for potential disputes during limitation period).                    |
          +----------------------------------------------------------------------+

**Right to Grievance Redressal (Section 13)**

Section 13 mandates that every Data Fiduciary and Consent Manager must
provide a **grievance redressal mechanism**.

      +----------------------------------------------------------------------+
      | **🔄 How Grievance Redressal Works**                                 |
      |                                                                      |
      | 1.  **File Complaint:** You file a grievance through the Data        |
      |     Fiduciary\'s website/app (Rule 14 requires this to be clearly    |
      |     published)                                                       |
      |                                                                      |
      | 2.  **Response Timeline:** Data Fiduciary must respond within the    |
      |     period prescribed in DPDP Rules (typically 7-15 days)            |
      |                                                                      |
      | 3.  **Exhaust Internal Remedy:** You must try to resolve the issue   |
      |     with the Data Fiduciary FIRST before approaching the Data        |
      |     Protection Board                                                 |
      |                                                                      |
      | 4.  **Escalate to Board:** If unsatisfied with the response (or no   |
      |     response received), you can file a complaint with the Data       |
      |     Protection Board                                                 |
      +----------------------------------------------------------------------+

      +----------------------------------------------------------------------+
      | **⚖️ Precedent: Grievance Redressal in Digital Rights**              |
      |                                                                      |
      | **Shreya Singhal v. Union of India (2015) 5 SCC 1**                  |
      |                                                                      |
      | The Supreme Court emphasized that any intermediary or platform       |
      | handling user data must provide effective and timely grievance       |
      | redressal. This principle is now codified in DPDPA Section 13.       |
      |                                                                      |
      | **Key Principle:** Grievance mechanisms must be "readily             |
      | available" - not buried in fine print or requiring complex           |
      | procedures.                                                          |
      +----------------------------------------------------------------------+

**Right to Nominate (Section 14)**

Section 14 allows you to nominate another individual who can exercise
your data rights in case of your death or incapacity.

        +----------------------------------------------------------------------+
        | **How Nomination Works**                                             |
        |                                                                      |
        | **When to Nominate:** At any time while you\'re alive and of sound   |
        | mind                                                                 |
        |                                                                      |
        | **Who Can Be Nominated:** Any other individual (family member,       |
        | friend, legal advisor)                                               |
        |                                                                      |
        | **What Nominee Can Do:** Exercise ALL your data rights - access,     |
        | correction, erasure, grievance redressal                             |
        |                                                                      |
        | **When Nominee Acts:** Only upon your death or incapacity (defined   |
        | as "unsoundness of mind or infirmity of body")                       |
        |                                                                      |
        | **How to Nominate:** As prescribed in DPDP Rules (likely through a   |
        | standard form filed with the Data Fiduciary)                         |
        +----------------------------------------------------------------------+
        
        +----------------------------------------------------------------------+
        | **💡 Why Nomination Matters: Digital Legacy**                        |
        |                                                                      |
        | In the digital age, our personal data often outlives us. Section 14  |
        | addresses the question: "What happens to my data after I die?"       |
        |                                                                      |
        | **Without Nomination:** Your data remains with Data Fiduciaries      |
        | indefinitely, and your family has no legal standing to request its   |
        | deletion or access.                                                  |
        |                                                                      |
        | **With Nomination:** Your nominee can ensure your digital footprint  |
        | is managed according to your wishes - delete sensitive data,         |
        | preserve memories, or claim digital assets.                          |
        |                                                                      |
        | **Philosophical Note:** This reflects the concept of "digital        |
        | dignity" - your privacy rights should extend beyond your lifetime.   |
        +----------------------------------------------------------------------+

**Duties of Data Principal (Section 15)**

While DPDPA grants you powerful rights, **Section 15** also imposes
certain duties. Rights and responsibilities go hand-in-hand.

        +----------------------------------------------------------------------+
        | **⚖️ Your Duties as a Data Principal**                               |
        |                                                                      |
        | 1.  **Comply with Applicable Law:** When exercising your rights, you |
        |     must do so in accordance with the law and not abuse the process  |
        |                                                                      |
        | 2.  **No False or Frivolous Complaints:** You cannot file baseless   |
        |     grievances or make false claims                                  |
        |                                                                      |
        | 3.  **Not Impersonate:** You cannot exercise rights on behalf of     |
        |     another person without proper authorization (nomination)         |
        |                                                                      |
        | 4.  **Provide Complete Information:** When requesting access or      |
        |     correction, you must provide accurate information to identify    |
        |     yourself                                                         |
        +----------------------------------------------------------------------+

        +----------------------------------------------------------------------+
        | **📖 Example: Balancing Rights and Duties**                          |
        |                                                                      |
        | **Proper Exercise of Rights:**                                       |
        |                                                                      |
        | Neha requests erasure of her data from an e-commerce site she no     |
        | longer uses. She provides her registered email and account ID for    |
        | verification. The company deletes her data within 15 days. ✅ Rights |
        | properly exercised, duties fulfilled.                                |
        |                                                                      |
        | **Improper Exercise (Violation of Duties):**                         |
        |                                                                      |
        | Rohit files 50 erasure requests to different Data Fiduciaries with   |
        | the intention of causing disruption, not genuine privacy concern.    |
        | This violates Section 15. ❌ The Data Protection Board can impose    |
        | penalties on Rohit for frivolous complaints (up to ₹10,000 per Data  |
        | Fiduciary under Section 33).                                         |
        +----------------------------------------------------------------------+
        
        +----------------------------------------------------------------------+
        | **✅ Key Takeaways - Section 1**                                     |
        |                                                                      |
        | - Section 11: Right to know what data is processed and who it\'s     |
        |   shared with                                                        |
        |                                                                      |
        | - Section 12: Right to correct inaccurate data and request erasure   |
        |   (with exceptions)                                                  |
        |                                                                      |
        | - Section 13: Right to effective grievance redressal before          |
        |   approaching Board                                                  |
        |                                                                      |
        | - Section 14: Right to nominate someone to exercise your rights      |
        |   after death/incapacity                                             |
        |                                                                      |
        | - Section 15: Data Principals have duties - don\'t abuse your rights |
        |   with frivolous complaints                                          |
        |                                                                      |
        | - All rights must be exercised through readily available means       |
        |   published by Data Fiduciary                                        |
        +----------------------------------------------------------------------+

**2. Data Fiduciary Obligations (Sections 8-10)**

------------------------------------------------------------------------

While Data Principals have rights, Data Fiduciaries have corresponding
obligations. Sections 8-10 establish the duties that organizations must
fulfill when processing personal data.

**General Obligations of Data Fiduciary (Section 8)**

      +----------------------------------------------------------------------+
      | **Section 8: Core Duties of Every Data Fiduciary**                   |
      |                                                                      |
      | 1.  **Purpose Limitation:** Process data only for lawful purposes    |
      |     for which consent was obtained                                   |
      |                                                                      |
      | 2.  **Collection Limitation:** Collect only necessary data - no      |
      |     excessive collection                                             |
      |                                                                      |
      | 3.  **Storage Limitation:** Retain data only as long as needed for   |
      |     the specified purpose                                            |
      |                                                                      |
      | 4.  **Reasonable Security:** Implement appropriate technical and     |
      |     organizational measures                                          |
      |                                                                      |
      | 5.  **Data Breach Notification:** Inform Board and affected Data     |
      |     Principals of breaches                                           |
      |                                                                      |
      | 6.  **Accuracy:** Ensure data is complete, accurate, and not         |
      |     misleading                                                       |
      |                                                                      |
      | 7.  **Designate Point of Contact:** Publish contact information for  |
      |     Data Principal queries                                           |
      +----------------------------------------------------------------------+

      +----------------------------------------------------------------------+
      | **📱 Example: Purpose Limitation in Action**                         |
      |                                                                      |
      | **Scenario:** A telecom company collects customer phone numbers for  |
      | service activation (specified purpose with consent).                 |
      |                                                                      |
      | **Permitted:** Using the number to send service alerts, billing      |
      | notifications ✅                                                    |
      |                                                                      |
      | **NOT Permitted:** Selling the phone number to marketing companies,  |
      | using it for political campaigns ❌                                 |
      |                                                                      |
      | **Why:** Purpose limitation means you can only use data for what you |
      | originally said you\'d use it for. New purposes require new consent. |
      +----------------------------------------------------------------------+

**Processing of Personal Data of Children (Section 9)**

Section 9 provides enhanced protection for children\'s personal data.

        +----------------------------------------------------------------------+
        | **👶 Special Rules for Children\'s Data**                            |
        |                                                                      |
        | 1.  **Verifiable Parental Consent Required:** Data Fiduciaries must  |
        |     obtain consent from parent/guardian, not the child               |
        |                                                                      |
        | 2.  **Age Verification:** Reasonable efforts to verify child\'s age  |
        |                                                                      |
        | 3.  **No Tracking or Behavioral Monitoring:** Cannot track children  |
        |     or do behavioral monitoring for targeted advertising             |
        |                                                                      |
        | 4.  **No Profiling:** Cannot create detailed profiles of children    |
        |                                                                      |
        | 5.  **No Detrimental Content:** Cannot process data in ways harmful  |
        |     to child\'s well-being                                           |
        +----------------------------------------------------------------------+
        
        +----------------------------------------------------------------------+
        | **💡 Philosophy: Protecting Digital Childhood**                      |
        |                                                                      |
        | Children are particularly vulnerable online. They may not understand |
        | the long-term consequences of data sharing. Section 9 embodies the   |
        | principle of "best interests of the child" from the UN Convention on |
        | the Rights of the Child.                                             |
        |                                                                      |
        | **Real Impact:** Social media platforms, gaming apps, and EdTech     |
        | companies must fundamentally redesign their data practices for users |
        | under 18.                                                            |
        +----------------------------------------------------------------------+

**Additional Obligations of Significant Data Fiduciary (Section 10)**

Organizations designated as **Significant Data Fiduciaries (SDFs)** face
enhanced obligations due to the scale and sensitivity of their data
processing.

          ------------------------------------------------------------------
          **Regular Data Fiduciary**       **Significant Data Fiduciary
                                           (SDF)**
          -------------------------------- ---------------------------------
          Comply with Sections 8-9         Comply with Sections 8-9 PLUS
                                           Section 10
        
          No mandatory DPO                 **Must appoint Data Protection
                                           Officer (DPO) based in India**
        
          No mandatory audit               **Must conduct periodic
                                           independent data audits**
        
          No DPIA required                 **Must conduct Data Protection
                                           Impact Assessment (DPIA)
                                           periodically**
        
          Standard security measures       Enhanced security measures as
                                           prescribed
          ------------------------------------------------------------------

        +----------------------------------------------------------------------+
        | **✅ Key Takeaways - Section 2**                                     |
        |                                                                      |
        | - Section 8: All Data Fiduciaries must follow purpose limitation,    |
        |   data minimization, security safeguards                             |
        |                                                                      |
        | - Section 9: Children\'s data requires verifiable parental consent;  |
        |   no tracking or profiling allowed                                   |
        |                                                                      |
        | - Section 10: SDFs have enhanced obligations - DPO, audits, DPIA     |
        |                                                                      |
        | - Data breach notification is mandatory for all Data Fiduciaries     |
        |                                                                      |
        | - Storage limitation: Delete data when purpose is no longer served   |
        +----------------------------------------------------------------------+

**3. Consent Manager Framework (Section 6)**

------------------------------------------------------------------------

The **Consent Manager** is an innovative concept introduced in DPDPA to
help Data Principals manage their consents across multiple Data
Fiduciaries efficiently.

        +----------------------------------------------------------------------+
        | **What is a Consent Manager?**                                       |
        |                                                                      |
        | A Consent Manager is a registered entity that acts as an             |
        | intermediary between Data Principals and Data Fiduciaries to         |
        | facilitate consent management.                                       |
        |                                                                      |
        | **Think of it as:** A "consent dashboard" where you can view, grant, |
        | withdraw, and modify all your consents to various Data Fiduciaries   |
        | in one place.                                                        |
        +----------------------------------------------------------------------+

      +-------------------------------------------------------------------+
      | **📱 Example: Consent Manager in Action**                         |
      |                                                                   |
      | **Without Consent Manager:**                                      |
      |                                                                   |
      | - You log into Amazon → Manage privacy settings                   |
      |                                                                   |
      | - You log into Flipkart → Manage privacy settings                 |
      |                                                                   |
      | - You log into Swiggy → Manage privacy settings                   |
      |                                                                   |
      | - You log into 20 other services → Repeat 20 times                |
      |                                                                   |
      | **With Consent Manager:**                                         |
      |                                                                   |
      | - You log into your Consent Manager account (like DigiLocker)     |
      |                                                                   |
      | - See ALL consents across ALL services in one dashboard           |
      |                                                                   |
      | - Withdraw consent to Swiggy\'s marketing emails → Done instantly |
      |                                                                   |
      | - Modify consent to Zomato\'s location access → Updated centrally |
      +-------------------------------------------------------------------+

        +----------------------------------------------------------------------+
        | **💡 Consent Manager: Inspired by Account Aggregators**              |
        |                                                                      |
        | India\'s Account Aggregator framework (for financial data) served as |
        | inspiration. Consent Managers extend this model to ALL personal data |
        | across sectors - healthcare, e-commerce, social media, etc.          |
        |                                                                      |
        | **Coming into Force:** Consent Manager provisions become effective   |
        | one year after DPDP Rules notification (by November 13, 2026)        |
        +----------------------------------------------------------------------+
        
        +----------------------------------------------------------------------+
        | **✅ Key Takeaways - Section 3**                                     |
        |                                                                      |
        | - Consent Managers provide centralized consent dashboard             |
        |                                                                      |
        | - Must be registered with Data Protection Board                      |
        |                                                                      |
        | - Help Data Principals exercise control easily                       |
        |                                                                      |
        | - Interoperability ensures consents work across all Data Fiduciaries |
        |                                                                      |
        | - Penalties up to ₹250 crores for Consent Manager failures           |
+----------------------------------------------------------------------+

**4. Notice & Transparency Requirements**

------------------------------------------------------------------------

**Section 5** mandates that Data Fiduciaries must provide clear notice
to Data Principals before or at the time of collecting personal data.

      +----------------------------------------------------------------------+
      | **✔ What Must Be in the Notice (Section 5 & Rule 3)**                |
      |                                                                      |
      | 1.  **Identity of Data Fiduciary:** Who is collecting your data      |
      |                                                                      |
      | 2.  **Purpose of Processing:** Why your data is being collected      |
      |                                                                      |
      | 3.  **Manner of Exercising Rights:** How you can access, correct,    |
      |     erase your data                                                  |
      |                                                                      |
      | 4.  **Grievance Redressal:** How to file complaints                  |
      |                                                                      |
      | 5.  **Data Sharing:** Who else will receive your data                |
      |                                                                      |
      | 6.  **Retention Period:** How long data will be kept                 |
      +----------------------------------------------------------------------+

      +----------------------------------------------------------------------+
      | **📱 Good Notice vs. Bad Notice**                                    |
      |                                                                      |
      | **Bad Notice (Vague, Non-Compliant):**                               |
      |                                                                      |
      | *"We collect your data for various purposes. We may share it with    |
      | partners. See our privacy policy for details."*                      |
      |                                                                      |
      | **❌ Problems:** No specific purpose, no identity, vague language,   |
      | forces user to read lengthy policy                                   |
      |                                                                      |
      | **Good Notice (Clear, Compliant):**                                  |
      |                                                                      |
      | *"Swiggy Food Services Pvt. Ltd. collects your name, phone number,   |
      | and delivery address to fulfill food orders. We share your address   |
      | with restaurant partners and delivery riders. Data is kept for 5     |
      | years for legal compliance. You can access, correct, or delete your  |
      | data anytime via Settings \> Privacy. Complaints: or file grievance  |
      | in-app."*                                                            |
      |                                                                      |
      | **✅ Compliant:** Specific, clear, actionable                        |
      +----------------------------------------------------------------------+

      +---------------------------------------------------------------+
      | **✅ Key Takeaways - Section 4**                              |
      |                                                               |
      | - Notice must be provided before/at time of data collection   |
      |                                                               |
      | - Must be in clear, plain language (not legal jargon)         |
      |                                                               |
      | - Layered approach encouraged: short notice + detailed policy |
      |                                                               |
      | - Notice must inform about rights and how to exercise them    |
      |                                                               |
      | - Updates to notice require new consent if purpose changes    |
      +---------------------------------------------------------------+

**5. Data Security & Protection Measures**

------------------------------------------------------------------------

**Section 8(5)** requires Data Fiduciaries to implement "reasonable
security safeguards" to prevent data breaches. **Rule 6** of DPDP Rules
2025 elaborates on what constitutes "reasonable."

        +----------------------------------------------------------+
        | **Reasonable Security Safeguards (Rule 6)**              |
        |                                                          |
        | **Technical Measures:**                                  |
        |                                                          |
        | - Encryption of data at rest and in transit              |
        |                                                          |
        | - Access controls and authentication mechanisms          |
        |                                                          |
        | - Secure data deletion methods                           |
        |                                                          |
        | - Regular security testing and vulnerability assessments |
        |                                                          |
        | - Intrusion detection and prevention systems             |
        |                                                          |
        | **Organizational Measures:**                             |
        |                                                          |
        | - Data protection policies and procedures                |
        |                                                          |
        | - Employee training on data security                     |
        |                                                          |
        | - Access restriction on need-to-know basis               |
        |                                                          |
        | - Incident response plans                                |
        |                                                          |
        | - Third-party vendor security assessments                |
        +----------------------------------------------------------+

        +----------------------------------------------------------------------+
        | **⚠️ Data Breach Case Studies**                                      |
        |                                                                      |
        | **Global Example: British Airways GDPR Fine (2020) - £20 Million**   |
        |                                                                      |
        | **Issue:** Poor security led to breach affecting 400,000+ customers  |
        |                                                                      |
        | **Lesson for India:** "Reasonable security" isn\'t optional - it\'s  |
        | enforceable with penalties                                           |
        |                                                                      |
        | **India Context: Domino\'s India Data Breach (2021)**                |
        |                                                                      |
        | 18 crore customer records exposed. Under DPDPA, this would trigger:  |
        |                                                                      |
        | - Mandatory breach notification to Board (Rule 7)                    |
        |                                                                      |
        | - Notification to affected customers                                 |
        |                                                                      |
        | - Potential penalty up to ₹250 crores if negligence found            |
        +----------------------------------------------------------------------+

          +----------------------------------------------------------------------+
          | **📖 Breach Notification Requirements (Section 8(6) & Rule 7)**      |
          |                                                                      |
          | **When Breach Occurs:**                                              |
          |                                                                      |
          | 1.  **Assess Impact:** Determine if personal data was compromised    |
          |                                                                      |
          | 2.  **Notify Board:** Intimate Data Protection Board immediately     |
          |     (format as prescribed)                                           |
          |                                                                      |
          | 3.  **Notify Affected Individuals:** Inform Data Principals whose    |
          |     data was breached                                                |
          |                                                                      |
          | 4.  **Document:** Maintain records of breach, response, and          |
          |     remediation                                                      |
          |                                                                      |
          | **Failure to Notify:** Considered serious violation, attracts        |
          | penalties                                                            |
          +----------------------------------------------------------------------+
          
          +----------------------------------------------------------------------+
          | **✅ Key Takeaways - Section 5**                                     |
          |                                                                      |
          | - Rule 6: Reasonable security means both technical AND               |
          |   organizational measures                                            |
          |                                                                      |
          | - Security must be proportionate to sensitivity of data and scale of |
          |   processing                                                         |
          |                                                                      |
          | - Encryption, access controls, and regular audits are essential      |
          |                                                                      |
          | - Data breach notification is mandatory - to Board and affected      |
          |   individuals                                                        |
          |                                                                      |
          | - Failure to maintain security = penalties up to ₹250 crores         |
          |                                                                      |
          | - Third-party processors must also maintain reasonable security      |
          +----------------------------------------------------------------------+
          
          +-----------------------------------------------------+
          | **Primary Legislation:**                            |
          |                                                     |
          | DPDPA 2023 - Sections 8-15 (Obligations and Rights) |
          +-----------------------------------------------------+
          
          +----------------------------------------------------------------------+
          | **DPDP Rules:**                                                      |
          |                                                                      |
          | Rules 6-15: Security Safeguards, Breach Notification, Rights         |
          | Exercise                                                             |
          +----------------------------------------------------------------------+
          
          +----------------------------------------------------------------------+
          | **Case Law:**                                                        |
          |                                                                      |
          | Shreya Singhal v. Union of India (2015) 5 SCC 1 - Grievance          |
          | Redressal Principles                                                 |
          +----------------------------------------------------------------------+
          
          +------------------------------------------------------------------------------+
          | **✅ Self-Assessment Quiz**                                                  |
          |                                                                              |
          | Test your understanding of Module 2 concepts:                                |
          |                                                                              |
          | +--------------------------------------------------------------------------+ |
          | | **1. What information can you request under Section 11 (Right to         | |
          | | Access)?**                                                               | |
          | |                                                                          | |
          | | **Hide Answer**                                                          | |
          | |                                                                          | |
          | | +----------------------------------------------------------------------+ | |
          | | | **Answer:**                                                          | | |
          | | |                                                                      | | |
          | | | Under Section 11, you can request: (1) Summary of your personal data | | |
          | | | being processed, (2) Processing activities undertaken, (3)           | | |
          | | | Identities of all third parties with whom data was shared, (4)       | | |
          | | | Description of data shared with each third party, (5) Any other      | | |
          | | | prescribed information.                                              | | |
          | | +----------------------------------------------------------------------+ | |
          | +--------------------------------------------------------------------------+ |
          |                                                                              |
          | +--------------------------------------------------------------------------+ |
          | | **2. Can a Data Fiduciary refuse your request to delete data? If yes,    | |
          | | when?**                                                                  | |
          | |                                                                          | |
          | | **Hide Answer**                                                          | |
          | |                                                                          | |
          | | +----------------------------------------------------------------------+ | |
          | | | **Answer:**                                                          | | |
          | | |                                                                      | | |
          | | | YES, under Section 12(3), a Data Fiduciary can refuse erasure if:    | | |
          | | | (1) Retention is necessary for the specified purpose (e.g., ongoing  | | |
          | | | service), OR (2) Retention is required for compliance with any law   | | |
          | | | for the time being in force (e.g., tax records, legal disputes).     | | |
          | | +----------------------------------------------------------------------+ | |
          | +--------------------------------------------------------------------------+ |
          |                                                                              |
          | +--------------------------------------------------------------------------+ |
          | | **3. What special protections apply to children\'s data under Section    | |
          | | 9?**                                                                     | |
          | |                                                                          | |
          | | **Hide Answer**                                                          | |
          | |                                                                          | |
          | | +----------------------------------------------------------------------+ | |
          | | | **Answer:**                                                          | | |
          | | |                                                                      | | |
          | | | Section 9 requires: (1) Verifiable parental consent (not child\'s    | | |
          | | | consent), (2) Age verification, (3) No tracking or behavioral        | | |
          | | | monitoring for targeted advertising, (4) No profiling of children,   | | |
          | | | (5) No processing detrimental to child\'s well-being.                | | |
          | | +----------------------------------------------------------------------+ | |
          | +--------------------------------------------------------------------------+ |
          |                                                                              |
          | +--------------------------------------------------------------------------+ |
          | | **4. What are the additional obligations of a Significant Data Fiduciary | |
          | | (SDF)?**                                                                 | |
          | |                                                                          | |
          | | **Hide Answer**                                                          | |
          | |                                                                          | |
          | | +----------------------------------------------------------------------+ | |
          | | | **Answer:**                                                          | | |
          | | |                                                                      | | |
          | | | Under Section 10, SDFs must: (1) Appoint Data Protection Officer     | | |
          | | | (DPO) based in India, (2) Conduct independent data audits            | | |
          | | | periodically, (3) Conduct Data Protection Impact Assessments (DPIA)  | | |
          | | | periodically, (4) Implement enhanced security measures as            | | |
          | | | prescribed.                                                          | | |
          | | +----------------------------------------------------------------------+ | |
          | +--------------------------------------------------------------------------+ |
          |                                                                              |
          | +--------------------------------------------------------------------------+ |
          | | **5. What must a Data Fiduciary do when a data breach occurs?**          | |
          | |                                                                          | |
          | | **Hide Answer**                                                          | |
          | |                                                                          | |
          | | +----------------------------------------------------------------------+ | |
          | | | **Answer:**                                                          | | |
          | | |                                                                      | | |
          | | | Under Section 8(6) and Rule 7: (1) Assess impact of breach, (2)      | | |
          | | | Immediately notify Data Protection Board in prescribed format, (3)   | | |
          | | | Notify affected Data Principals whose data was compromised, (4)      | | |
          | | | Document breach, response, and remediation actions taken.            | | |
          | | +----------------------------------------------------------------------+ | |
          | +--------------------------------------------------------------------------+ |
          +------------------------------------------------------------------------------+
