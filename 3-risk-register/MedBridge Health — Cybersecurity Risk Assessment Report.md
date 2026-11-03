# MedBridge Health, Inc.
# Cybersecurity Risk Assessment Report

**Assessment Date:** November 2, 2026

**Assessment Type:** Simulated Cybersecurity Risk Assessment

**Prepared By:** GRC Analyst (Simulated)

**Location:** San Francisco, California

**Report Status:** Draft — Pending Management Review

---

## 1. Executive Summary

I conducted a simulated cybersecurity risk assessment for MedBridge Health, Inc., a fictional healthcare company based in San Francisco, California.

The purpose of this assessment was for me to identify security risks that could affect the company's systems, patient information, and business operations.

Using the security weaknesses documented in Project 1 and additional risk scenarios based on the company's technology environment, I identified and evaluated 16 cybersecurity risks.

Each risk was assessed using a 5 × 5 likelihood and impact scoring matrix. I also assigned risk owners, recommended corrective actions, and estimated the level of risk that could remain after the proposed improvements are implemented.

### Key Assessment Results

| Risk Rating | Number of Risks |
|---|---:|
| Critical | 3 |
| High | 13 |
| Medium | 0 |
| Low | 0 |
| **Total** | **16** |

The assessment identified three Critical risks involving backup restoration failure, delayed incident response, and ransomware.

These risks received the highest priority because they could significantly affect healthcare services, patient information, and the company's ability to recover from security incidents.

The assessment also identified important risks involving employee account security, vendor compliance, security monitoring, privileged access, cloud infrastructure, and application security.

All 16 risks require management attention and have been assigned proposed mitigation actions.

## 2. Company Background

MedBridge Health is a fictional telehealth company headquartered in San Francisco, California.

The company has approximately 50 employees and provides telehealth services to around 40,000 patients across six U.S. states.

Its technology environment includes Amazon Web Services (AWS), Electronic Health Records (EHR), patient applications, clinician portals, Okta, Google Workspace, and third-party services such as Zoom for Healthcare, Twilio, and Zendesk.

Because the company handles Protected Health Information (PHI) and Personally Identifiable Information (PII), cybersecurity weaknesses could affect patient privacy, healthcare availability, and regulatory compliance.

MedBridge Health does not have a dedicated cybersecurity department. Security responsibilities are shared between the CTO, IT Manager, part-time vCISO, Privacy Officer, and department leaders.

This environment was used as the basis for the simulated risk assessment.

## 3. Assessment Objectives and Scope

The main objectives of this assessment were to:

- Identify cybersecurity risks affecting MedBridge Health.
- Evaluate the likelihood and potential impact of each risk.
- Assign risk ratings using a consistent scoring methodology.
- Identify responsible risk owners.
- Recommend security improvements to reduce risk exposure.
- Estimate target residual risk levels after proposed treatments.
- Provide leadership with a prioritized risk treatment plan.

The assessment covered risks involving cloud infrastructure, employee devices, healthcare applications, third-party services, identity and access management, network security, and protection of patient information.

The assessment was based on the fictional company profile and documented security weaknesses. No live systems were scanned or tested.

## 4. Risk Assessment Methodology

I used a qualitative risk assessment approach based on a 5 × 5 scoring matrix.

Each identified risk was assigned a likelihood score between 1 and 5 and an impact score between 1 and 5.

The overall risk score was calculated using the following formula:

**Risk Score = Likelihood × Impact**

The risk ratings were classified as follows:

| Risk Score | Risk Rating | Priority |
|---|---|---|
| 1–4 | Low | Monitor through normal security processes. |
| 5–9 | Medium | Develop corrective actions and track progress. |
| 10–16 | High | Prioritize remediation and assign a responsible risk owner. |
| 17–25 | Critical | Escalate to leadership and prioritize urgent risk treatment. |

After assigning inherent risk scores, I recommended security controls and estimated target residual risk scores.

These target residual scores represent the expected risk levels if the recommended improvements are implemented and operating effectively.

## 5. Risk Assessment Findings

The assessment identified 16 cybersecurity risks.

Eight risks were based on the security weaknesses documented in Project 1. Eight additional risks were developed as realistic scenarios involving MedBridge Health's technology environment.

### 5.1 Identified Cybersecurity Risks

| Risk ID | Risk Title | Inherent Score | Risk Rating |
|---|---|---:|---|
| R-01 | Phishing and Employee Account Compromise | 16 | High |
| R-02 | Backup Restoration Failure | 20 | Critical |
| R-03 | Delayed Incident Response | 20 | Critical |
| R-04 | Missing Vendor Business Associate Agreements | 16 | High |
| R-05 | Delayed Employee Offboarding | 16 | High |
| R-06 | Shared Firewall Administrator Account | 16 | High |
| R-07 | Unreviewed Security Logs | 16 | High |
| R-08 | Lost or Stolen Employee Device | 12 | High |
| R-09 | AWS Cloud Storage Misconfiguration | 15 | High |
| R-10 | Unpatched Employee Devices | 16 | High |
| R-11 | Excessive User Access Permissions | 16 | High |
| R-12 | Ransomware Infection | 20 | Critical |
| R-13 | Third-Party Service Outage | 12 | High |
| R-14 | Patient Portal Vulnerability | 15 | High |
| R-15 | PHI Shared Through Unauthorized Channels | 16 | High |
| R-16 | Inadequate Network Segmentation | 12 | High |

### 5.2 Critical Risk Findings

**R-02 — Backup Restoration Failure**

MedBridge Health has not tested its backup restoration procedures. If ransomware or a major system failure occurs, the company may be unable to restore critical healthcare systems and patient records within an acceptable timeframe.

I assigned this risk a likelihood score of 4 and an impact score of 5, resulting in a Critical risk score of 20.

**R-03 — Delayed Incident Response**

MedBridge Health does not currently have an implemented incident response plan. Without established procedures and assigned responsibilities, the company could experience delays in investigating, containing, and recovering from cybersecurity incidents.

I assigned this risk a likelihood score of 4 and an impact score of 5, resulting in a Critical risk score of 20.

**R-12 — Ransomware Infection**

Ransomware could disrupt the company's ability to access patient records, operate critical applications, and provide telehealth services.

The company's untested backup restoration procedures and limited incident response capabilities could increase the impact of a ransomware incident.

I assigned this risk a likelihood score of 4 and an impact score of 5, resulting in a Critical risk score of 20.

### 5.3 Other Significant Findings

The assessment also identified important weaknesses in identity management, security monitoring, vendor compliance, and data protection.

For example, MedBridge Health uses a shared firewall administrator account, which makes it difficult to determine who performed specific administrative actions.

AWS CloudWatch logs are not reviewed regularly, which could delay the detection of suspicious activity.

The company also has missing Business Associate Agreements for certain vendors and has experienced delays in removing employee access after termination.

These findings show why MedBridge Health needs stronger security processes, clearer responsibilities, and regular monitoring of important controls.

## 6. Risk Treatment Recommendations

All 16 risks were assigned the treatment recommendation **Mitigate**.

I selected mitigation because the identified weaknesses can be addressed through administrative, technical, and operational security improvements.

The most important recommended actions are:

1. **Test Backup Restoration:** Perform restoration tests at least every six months and document whether critical systems can be recovered successfully.
2. **Implement Incident Response Procedures:** Obtain approval for the Incident Response Policy, establish escalation procedures, and conduct annual tabletop exercises.
3. **Strengthen Ransomware Defenses:** Improve endpoint protection, monitor suspicious activity, and verify recovery capabilities.
4. **Improve Access Management:** Replace shared administrator accounts, enforce MFA, conduct access reviews, and remove unnecessary permissions.
5. **Improve Security Monitoring:** Configure AWS security alerts and establish regular reviews of high-priority events.
6. **Address Vendor Compliance:** Review vendor PHI handling and execute required Business Associate Agreements.
7. **Strengthen Employee Security Awareness:** Provide regular security awareness training and guidance on protecting PHI.
8. **Improve Asset and Vulnerability Management:** Maintain an accurate device inventory and establish patch management procedures.

The detailed corrective actions, risk owners, and proposed deadlines are documented in the separate Risk Treatment Plan and Risk Register.

## 7. Inherent and Target Residual Risk Comparison

After identifying the risks, I estimated how the risk ratings could change if the recommended controls were implemented successfully.

### 7.1 Risk Rating Comparison

| Risk Rating | Inherent Risk Count | Target Residual Risk Count |
|---|---:|---:|
| Critical | 3 | 0 |
| High | 13 | 3 |
| Medium | 0 | 12 |
| Low | 0 | 1 |
| **Total** | **16** | **16** |

Based on these estimates, the number of Critical risks could decrease from three to zero.

The remaining risks would fall into the High, Medium, and Low categories.

However, these results do not mean that MedBridge Health has already reduced its security risks.

The proposed controls would need to be implemented, tested, and reviewed before actual residual risk levels could be confirmed.

### 7.2 Risk Heat Maps

I created two 5 × 5 risk heat maps to visualize the assessment results.

The Inherent Risk Heat Map shows how the 16 risks are distributed before the recommended security improvements.

The Target Residual Risk Heat Map shows how the risk distribution could change after the proposed controls are implemented.

Together, these heat maps help demonstrate which risks should receive priority and how security improvements could affect the company's overall risk exposure.

## 8. Risk Ownership and Monitoring

Each cybersecurity risk was assigned to an owner based on the responsibilities of MedBridge Health's leadership and technical staff.

The CTO is responsible for coordinating technical risks involving AWS, healthcare applications, backup recovery, and system availability.

The IT Manager is responsible for risks involving employee devices, account management, privileged access, and network security.

The vCISO is responsible for coordinating cybersecurity risk management activities and reviewing security improvement recommendations.

The Privacy Officer is responsible for coordinating risks involving PHI, HIPAA compliance, and vendor requirements.

The HR Manager is responsible for supporting employee offboarding and related access removal procedures.

Risk owners should regularly review assigned risks, track remediation progress, and provide supporting evidence when corrective actions are completed.

High and Critical risks should receive more frequent management attention until appropriate security improvements are implemented.

## 9. Conclusion and Lessons Learned

This assessment helped me better understand how cybersecurity risks are identified, evaluated, and prioritized in a healthcare environment.

By reviewing MedBridge Health's security weaknesses, I was able to connect technical and administrative issues to potential business impacts.

One thing that stood out to me was how different security weaknesses can affect one another. For example, untested backups, limited security monitoring, and missing incident response procedures could make a ransomware incident much more difficult to manage.

I also learned why risk scoring should be supported by clear reasoning instead of simply assigning numbers.

Creating the Risk Register, treatment plan, and heat maps gave me practical experience documenting risk findings, assigning owners, recommending corrective actions, and presenting results in a way management can understand.

Overall, this project helped me develop a better understanding of how GRC supports cybersecurity decision-making and continuous security improvement.

## 10. Assessment Disclaimer

This Cybersecurity Risk Assessment Report was created for MedBridge Health, Inc., a fictional healthcare company, as part of my hands-on GRC lab.

All risks, scores, findings, responsibilities, and recommendations are simulated for educational purposes.

No production systems were assessed, and the proposed security improvements have not been implemented or independently verified.