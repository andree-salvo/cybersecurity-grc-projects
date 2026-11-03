# Cybersecurity Risk Assessment and Risk Register

## Project Overview

For this project, I conducted a simulated cybersecurity risk assessment for **MedBridge Health, Inc.**, a fictional telehealth company headquartered in San Francisco, California.

The goal was to identify cybersecurity risks that could affect the company's patient information, systems, and daily operations. I used the security weaknesses identified in the company profile and developed additional risk scenarios based on its technology environment.

I documented the risks, evaluated their likelihood and impact, assigned risk owners, and recommended security improvements. I also created inherent and target residual risk heat maps to show how the company's risk exposure could change after implementing the proposed controls.

## Project Objectives

- Identify and document cybersecurity risks affecting MedBridge Health.
- Evaluate risks using a 5 × 5 likelihood and impact scoring matrix.
- Assign inherent risk scores and risk ratings.
- Identify responsible risk owners and recommend appropriate risk treatments.
- Estimate target residual risk scores after proposed security improvements.
- Create risk heat maps to visualize the assessment results.
- Develop a risk treatment plan and communicate findings to management.

## Tools and Methodology

**Tools Used:**
- Google Sheets
- Google Docs
- Microsoft Excel (.xlsx)
- Markdown
- GitHub

**Risk Assessment Methodology:**

I used a qualitative 5 × 5 risk scoring matrix to evaluate the likelihood and potential impact of each identified risk.

**Risk Score = Likelihood × Impact**

| Risk Score | Risk Rating |
|---|---|
| 1–4 | Low |
| 5–9 | Medium |
| 10–16 | High |
| 17–25 | Critical |

After scoring each risk, I documented recommended mitigation actions and estimated the target residual risk that could remain if the proposed controls were implemented successfully.

The target residual scores are estimates, not verified reductions.

## Key Findings

I identified **16 cybersecurity risks**, including weaknesses in backup recovery, incident response, access management, security monitoring, vendor compliance, and cloud security.

The initial assessment resulted in:

- **3 Critical risks**
- **13 High risks**

The three Critical risks were:

| Risk ID | Risk Title | Inherent Risk Score |
|---|---|---|
| R-02 | Backup Restoration Failure | 20 |
| R-03 | Delayed Incident Response | 20 |
| R-12 | Ransomware Infection | 20 |

These risks were prioritized because they could significantly affect MedBridge Health's ability to protect patient information, maintain healthcare services, and recover from cybersecurity incidents.

### Inherent vs. Target Residual Risk

| Risk Rating | Inherent Risk Count | Target Residual Risk Count |
|---|---:|---:|
| Critical | 3 | 0 |
| High | 13 | 4 |
| Medium | 0 | 11 |
| Low | 0 | 1 |
| **Total** | **16** | **16** |

The estimated target residual risk ratings suggest that the proposed security improvements could reduce several High and Critical risks.

However, the controls have not been implemented or tested. Actual residual risk would need to be reassessed after implementation.

## Risk Treatment Recommendations

I recommended mitigation for all 16 risks and documented corrective actions in the Risk Treatment Plan.

Some of the main recommendations included:

- Testing backup restoration procedures and documenting recovery results.
- Implementing an incident response process and conducting tabletop exercises.
- Strengthening endpoint security and ransomware defenses.
- Replacing shared administrator accounts with individually assigned accounts.
- Reviewing security logs and establishing alert monitoring procedures.
- Completing required vendor Business Associate Agreements.
- Improving employee security awareness, access reviews, and offboarding procedures.
- Strengthening AWS cloud security configurations and application security.

Each risk was assigned a proposed owner and remediation target date to support tracking and accountability.

## Project Deliverables

| Deliverable | Description |
|---|---|
| [Risk Assessment Methodology](https://github.com/andree-salvo/cybersecurity-grc-projects/blob/main/3-risk-register/MedBridge%20Health%20%E2%80%94%20Risk%20Assessment%20Methodology.pdf) | Explains the assessment scope, scoring criteria, risk ratings, and treatment approach. |
| [Cybersecurity Risk Register](https://github.com/andree-salvo/cybersecurity-grc-projects/blob/main/3-risk-register/medbridge-cybersecurity-risk-register.xlsx) | Contains all 16 risks, inherent and target residual scores, risk owners, treatment actions, and heat maps. |
| [Risk Treatment Plan](https://github.com/andree-salvo/cybersecurity-grc-projects/blob/main/3-risk-register/MedBridge%20Health%20%E2%80%94%20Risk%20Treatment%20Plan.pdf) | Documents recommended corrective actions, priorities, responsible owners, and proposed deadlines. |
| [Cybersecurity Risk Assessment Report](https://github.com/andree-salvo/cybersecurity-grc-projects/blob/main/3-risk-register/MedBridge%20Health%20%E2%80%94%20Cybersecurity%20Risk%20Assessment%20Report.md) | Summarizes the assessment findings, critical risks, recommendations, and lessons learned. |

## Skills Demonstrated

Through this project, I gained hands-on experience with:

- Cybersecurity risk identification and assessment
- Likelihood and impact scoring
- Risk register development and maintenance
- Inherent and target residual risk analysis
- Risk prioritization and treatment planning
- Risk ownership and remediation tracking
- Risk heat map development
- GRC documentation and management reporting

## What I Learned

This project helped me understand how cybersecurity risks are evaluated and communicated from a GRC perspective.

One of the biggest things I learned was how different security weaknesses can increase the impact of an incident. For example, untested backups, limited security monitoring, and missing incident response procedures could make a ransomware attack much harder to recover from.

I also learned how important it is to explain the reasoning behind risk scores, assign clear responsibilities, and track corrective actions rather than just documenting security problems.

Creating the Risk Register, heat maps, treatment plan, and assessment report gave me practical experience connecting cybersecurity findings to business risk and recommended security improvements.

## Disclaimer

MedBridge Health, Inc. is a fictional healthcare company created for this cybersecurity GRC portfolio project.

All risk assessments, findings, scores, treatment recommendations, and company information are simulated for educational purposes. No production systems were assessed, and no security controls were implemented or verified.
