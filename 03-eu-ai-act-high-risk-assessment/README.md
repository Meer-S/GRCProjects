# Project 03: Assessing a High-Risk AI Use Case Under the EU AI Act

## Overview

The EU AI Act has created a flood of shallow content—summaries, lists of obligations, and classifications with no operational depth. This project requires you to take a realistic AI use case and **treat it as if it were about to be reviewed by a regulator**.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                        AI ACT: SHALLOW VS DEEP WORK                         │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│   SHALLOW CONTENT                       DEEP GRC WORK                       │
│   ───────────────                       ─────────────                       │
│   Summaries of articles                 Full operational assessment         │
│   Lists of obligations                  Decision on deployment              │
│   High-risk classifications             Fundamental rights analysis         │
│   Framework diagrams                    Human oversight evaluation          │
│   Compliance checklists                 Documented reasoning                │
│                                                                             │
│   Result: Content exists, but          Result: Regulator-ready              │
│   no operational value                 documentation                        │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## The Scenario

**Company:** TalentMatch AI
**Industry:** HR Technology / Recruitment
**Product:** AI-powered candidate screening and ranking system
**Deployment:** SaaS platform used by 150+ enterprise clients
**Location:** Headquarters in Amsterdam, serving EU customers

### The AI System

TalentMatch AI has developed a candidate screening system that:

1. **Ingests** job descriptions and candidate resumes
2. **Extracts** skills, experience, and qualifications
3. **Scores** candidates on job-fit (0-100 scale)
4. **Ranks** candidates and highlights top matches
5. **Recommends** interview shortlists to recruiters

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    TALENTMATCH AI SYSTEM FLOW                               │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│   ┌──────────────┐     ┌──────────────┐     ┌──────────────┐                │
│   │     Job      │     │   Candidate  │     │  Historical  │                │
│   │ Description  │     │   Resumes    │     │  Hire Data   │                │
│   └──────┬───────┘     └──────┬───────┘     └──────┬───────┘                │
│          │                    │                    │                        │
│          └────────────────────┼────────────────────┘                        │
│                               │                                             │
│                               ▼                                             │
│                    ┌──────────────────────┐                                 │
│                    │    NLP Processing    │                                 │
│                    │  (Skill Extraction)  │                                 │
│                    └──────────┬───────────┘                                 │
│                               │                                             │
│                               ▼                                             │
│                    ┌──────────────────────┐                                 │
│                    │   ML Scoring Model   │                                 │
│                    │  (Job-Fit Scoring)   │                                 │
│                    └──────────┬───────────┘                                 │
│                               │                                             │
│                               ▼                                             │
│                    ┌──────────────────────┐                                 │
│                    │   Ranking Engine     │                                 │
│                    │  (Candidate Order)   │                                 │
│                    └──────────┬───────────┘                                 │
│                               │                                             │
│                               ▼                                             │
│                    ┌──────────────────────┐                                 │
│                    │   Recruiter          │                                 │
│                    │   Dashboard          │                                 │
│                    └──────────────────────┘                                 │
│                               │                                             │
│                               ▼                                             │
│                    ┌──────────────────────┐                                 │
│                    │   Interview          │                                 │
│                    │   Decision           │                                 │
│                    └──────────────────────┘                                 │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

### Technical Details Provided

- **Model Type:** Transformer-based NLP + XGBoost scoring
- **Training Data:** 5 million historical applications with hire outcomes
- **Features Used:** Skills, experience years, education, job titles, company names
- **Accuracy Metrics:** 78% agreement with human recruiter decisions
- **Explainability:** SHAP values available for individual scores

### Business Claims

The company claims:
- "Human recruiters make all final decisions"
- "The AI only assists, it doesn't decide"
- "We don't use protected characteristics"
- "Our system is unbiased because we removed names and photos"

---

## What You Need to Do

### Phase 1: Classify the AI System

**Task:** Determine the risk classification under the EU AI Act.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    EU AI ACT RISK CLASSIFICATION                            │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│   ┌─────────────────────────────────────────────────────────────────────┐   │
│   │                    UNACCEPTABLE RISK                                │   │
│   │                    (Prohibited)                                     │   │
│   │   Social scoring, manipulation, real-time biometric ID (mostly)    │   │
│   └─────────────────────────────────────────────────────────────────────┘   │
│                                                                             │
│   ┌─────────────────────────────────────────────────────────────────────┐   │
│   │                    HIGH RISK                                        │   │
│   │                    (Heavy regulation)                               │   │
│   │   Employment, education, law enforcement, migration, critical      │   │
│   │   infrastructure, access to services                               │   │
│   │                                                                     │   │
│   │   >>> CANDIDATE SCREENING FALLS HERE <<<                           │   │
│   │                                                                     │   │
│   │   Annex III, Section 4(a): AI systems intended to be used for      │   │
│   │   recruitment or selection of natural persons, particularly for    │   │
│   │   targeted job advertisements, analyzing and filtering job         │   │
│   │   applications, and evaluating candidates                          │   │
│   └─────────────────────────────────────────────────────────────────────┘   │
│                                                                             │
│   ┌─────────────────────────────────────────────────────────────────────┐   │
│   │                    LIMITED RISK                                     │   │
│   │                    (Transparency)                                   │   │
│   │   Chatbots, emotion recognition, deep fakes                        │   │
│   └─────────────────────────────────────────────────────────────────────┘   │
│                                                                             │
│   ┌─────────────────────────────────────────────────────────────────────┐   │
│   │                    MINIMAL RISK                                     │   │
│   │                    (No specific requirements)                       │   │
│   │   Spam filters, video games, inventory management                  │   │
│   └─────────────────────────────────────────────────────────────────────┘   │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

**Deliverable:** Classification justification document

### Phase 2: Map Requirements for High-Risk AI

**Task:** Identify all applicable requirements under Article 6 and Annex III.

**High-Risk AI Requirements:**

| Requirement | Article | Key Obligation |
|-------------|---------|----------------|
| Risk Management | Art. 9 | Continuous risk identification and mitigation |
| Data Governance | Art. 10 | Training data quality, bias testing |
| Technical Documentation | Art. 11 | Full system documentation |
| Record Keeping | Art. 12 | Automatic logging of operations |
| Transparency | Art. 13 | Clear information to deployers |
| Human Oversight | Art. 14 | Meaningful human intervention |
| Accuracy & Robustness | Art. 15 | Appropriate performance levels |
| Cybersecurity | Art. 15 | Protection against manipulation |

### Phase 3: Assess Fundamental Rights Impact

**Task:** Conduct a fundamental rights impact assessment.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                 FUNDAMENTAL RIGHTS IMPACT ASSESSMENT                        │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│   RIGHT                    POTENTIAL IMPACT               SEVERITY          │
│   ─────                    ────────────────               ────────          │
│                                                                             │
│   Non-discrimination       Proxy discrimination via       HIGH              │
│   (Art. 21 EU Charter)     education, location, names                       │
│                                                                             │
│   Right to work            Denied employment              HIGH              │
│   (Art. 15 EU Charter)     opportunities                                    │
│                                                                             │
│   Human dignity            Reduced to a score             MEDIUM            │
│   (Art. 1 EU Charter)                                                       │
│                                                                             │
│   Data protection          Processing of personal         MEDIUM            │
│   (Art. 8 EU Charter)      data without transparency                        │
│                                                                             │
│   Effective remedy         No appeal mechanism            HIGH              │
│   (Art. 47 EU Charter)     for rejected candidates                          │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

**Analysis Questions:**

1. **Proxy Discrimination**
   - Does the model use features that correlate with protected characteristics?
   - Is "university name" a proxy for socioeconomic status?
   - Is "company name" a proxy for race/ethnicity/gender?
   - Can "location" data reveal national origin?

2. **Training Data Bias**
   - Does historical hire data reflect past discrimination?
   - Were diverse candidates historically hired fairly?
   - Is the 78% agreement with humans a problem if humans were biased?

3. **Impact Severity**
   - What happens to rejected candidates?
   - Is there any recourse?
   - How many people are affected?

### Phase 4: Evaluate Human Oversight

**Task:** Assess whether human oversight is meaningful or symbolic.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    HUMAN OVERSIGHT ASSESSMENT                               │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│   MEANINGFUL OVERSIGHT                  SYMBOLIC OVERSIGHT                  │
│   ────────────────────                  ──────────────────                  │
│                                                                             │
│   Human reviews all candidates          Human reviews only AI-selected     │
│   Human can override easily             Override requires justification     │
│   Human has time to review              1000 candidates, 2 minutes each    │
│   Human sees uncertainty                Only sees final score              │
│   Human trained on limitations          Human trusts the AI                │
│   Appeals process exists                No candidate feedback              │
│                                                                             │
│   Key Question: Does the human have meaningful ability to deviate from     │
│   AI recommendations, or does the system create automation bias?           │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

**Analysis Framework:**

```markdown
## Human Oversight Evaluation

### Current State
- Recruiters see ranked candidate list
- Top 20 candidates highlighted for interview
- Recruiters can view other candidates but rarely do
- No explanation of why candidates ranked lower
- Average time per hiring decision: 45 seconds

### Questions to Investigate
1. What percentage of interviews come from AI top-20?
2. How often do recruiters select outside top-20?
3. Do recruiters understand how the score is calculated?
4. Can recruiters explain why they rejected a candidate?
5. Is there an appeals process for candidates?

### Assessment
□ Meaningful oversight  □ Partially meaningful  □ Symbolic only
```

### Phase 5: Make the Deployment Decision

**Task:** Decide whether this system should be deployed at all.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    DEPLOYMENT DECISION FRAMEWORK                            │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│                        ┌────────────────────┐                               │
│                        │ Is system high-risk│                               │
│                        │ under AI Act?      │                               │
│                        └─────────┬──────────┘                               │
│                                  │                                          │
│                        ┌─────────▼──────────┐                               │
│                        │        YES         │                               │
│                        └─────────┬──────────┘                               │
│                                  │                                          │
│              ┌───────────────────┼───────────────────┐                      │
│              │                   │                   │                      │
│              ▼                   ▼                   ▼                      │
│   ┌──────────────────┐ ┌──────────────────┐ ┌──────────────────┐           │
│   │ Can requirements │ │ Are fundamental  │ │ Is human         │           │
│   │ be met?          │ │ rights protected?│ │ oversight real?  │           │
│   └────────┬─────────┘ └────────┬─────────┘ └────────┬─────────┘           │
│            │                    │                    │                      │
│   ┌────────▼─────────────────────▼────────────────────▼────────┐           │
│   │                                                            │           │
│   │   ALL YES ──────────────▶ DEPLOY with safeguards          │           │
│   │                                                            │           │
│   │   ANY NO  ──────────────▶ DO NOT DEPLOY until remediated  │           │
│   │                                                            │           │
│   │   UNCERTAIN ────────────▶ Conduct deeper assessment       │           │
│   │                                                            │           │
│   └────────────────────────────────────────────────────────────┘           │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

**Your Assessment Must Address:**

1. **Technical Compliance**
   - Can the system meet documentation requirements?
   - Can logging be implemented adequately?
   - Is accuracy sufficient for the use case?

2. **Fundamental Rights**
   - Are discrimination risks adequately mitigated?
   - Is there meaningful recourse for affected individuals?
   - Is the severity of impact proportionate to the benefit?

3. **Human Oversight**
   - Is oversight meaningful or performative?
   - Can humans actually intervene effectively?
   - Does the system create automation bias?

4. **Risk-Benefit Analysis**
   - What are the benefits of automation?
   - What are the risks to candidates?
   - Is the trade-off acceptable?

### Phase 6: Document Your Recommendation

**Task:** Write a formal assessment recommendation.

**Structure:**

```markdown
# EU AI Act Compliance Assessment
## TalentMatch AI Candidate Screening System

### Executive Summary
[One paragraph: Classification, key findings, recommendation]

### 1. System Description
- Purpose and intended use
- Technical architecture
- Training data and methodology
- Performance metrics

### 2. Risk Classification
- Classification determination: HIGH RISK
- Applicable Annex III category
- Justification for classification

### 3. Requirements Analysis
| Requirement | Current State | Gap | Remediation |
|-------------|--------------|-----|-------------|
| Art. 9 Risk Management | ... | ... | ... |
| Art. 10 Data Governance | ... | ... | ... |
[Continue for all requirements]

### 4. Fundamental Rights Impact
- Rights potentially affected
- Severity assessment
- Mitigation measures

### 5. Human Oversight Evaluation
- Current oversight mechanisms
- Effectiveness assessment
- Recommendations for improvement

### 6. Recommendation
□ APPROVE for deployment
□ APPROVE with conditions (list conditions)
□ DO NOT APPROVE until (list requirements)
□ PROHIBIT (fundamental rights concerns)

### 7. Conditions for Approval (if applicable)
1. [Specific condition]
2. [Specific condition]
[...]

### 8. Monitoring Requirements
- Ongoing compliance measures
- Review schedule
- Incident reporting
```

---

## Success Criteria

Your assessment demonstrates strong GRC judgment if:

| Criteria | Evidence |
|----------|----------|
| **Clear classification with reasoning** | Not just "it's high-risk" but WHY |
| **Fundamental rights analyzed** | Specific rights, specific impacts |
| **Human oversight critically evaluated** | Meaningful vs symbolic distinction |
| **Business claims challenged** | Questioned "we don't decide" narrative |
| **Clear recommendation** | Deploy / Don't deploy with reasoning |
| **Proportionality considered** | Benefits vs risks explicitly weighed |

### Red Flags (Weak Project)

- Simply listing AI Act articles without application
- Accepting "human-in-the-loop" claims at face value
- No fundamental rights analysis
- Generic compliance checklist without context
- No deployment recommendation (fence-sitting)

---

## Deliverables Checklist

```
□ Risk classification justification document
□ Requirements mapping with gap analysis
□ Fundamental rights impact assessment
□ Human oversight evaluation
□ Deployment recommendation with conditions
□ 5-minute video explaining why you would/wouldn't deploy
```

---

## Additional Scenarios (Practice)

Try this assessment framework with other high-risk use cases:

1. **Credit Scoring** - Bank using AI for loan decisions
2. **Biometric Identification** - Airport security verification
3. **Educational Assessment** - AI grading student essays
4. **Insurance Pricing** - AI setting health insurance premiums
5. **Law Enforcement** - Predictive policing algorithms

---

## Reflection Questions

After completing this project, answer:

1. What was the hardest part of challenging the "human decides" claim?
2. How did you weigh discrimination risk against efficiency benefits?
3. If you approved deployment, what keeps you up at night?
4. If you rejected deployment, what would change your mind?
5. How would you explain your decision to affected candidates?

---

*Remember: AI governance is not about compliance checklists. It's about preventing harm before it happens.*
