# Policy Tailoring Log

## Overview

For this project, I used the SANS Program Management Policy (February 2026) as a reference to develop an Information Security Policy for MedBridge Health, Inc.

Since MedBridge Health is a fictional healthcare company that handles sensitive patient information, I needed to make sure the policy covered the company's specific security risks and compliance responsibilities.

I used the security weaknesses identified in Project 1 to help determine which requirements needed to be included.

## Information Security Policy — Tailoring Log

| Policy Section | SANS Template | Changes Made for MedBridge Health | Reason |
|---|---|---|---|
| Purpose | General cybersecurity program objectives | Added specific requirements for protecting patient PHI and healthcare systems. | MedBridge Health handles sensitive patient information. |
| Scope | Applies to employees, contractors, vendors, and stakeholders. | Identified AWS, Okta, employee devices, healthcare applications, and third-party services. | The policy needed to reflect the company's actual technology environment. |
| Security Governance | PRG-06 through PRG-10 address executive sponsorship and governance responsibilities. | Assigned responsibilities to the CEO, CTO, vCISO, IT Manager, Privacy Officer, and HR Manager. | MedBridge Health does not have a dedicated cybersecurity team. |
| Risk Management | PRG-05 addresses cybersecurity governance and risk management. | Added annual risk assessments and assigned risk owners. | The company needs a consistent process for identifying and managing risks. |
| Data Protection | General confidentiality, integrity, and availability objectives. | Added PHI protection, encryption, and data classification requirements. | Patient information requires additional security protections. |
| Access Control | Not specifically detailed in this program management template. | Added MFA requirements, access reviews, and employee offboarding procedures. | Addresses shared administrator accounts and delayed access removal. |
| Security Awareness | General security awareness objectives. | Added onboarding training, annual refresher training, and training records. | Addresses the company's limited employee security awareness program. |
| Incident Response | Included in the general program management scope. | Added incident reporting, security monitoring, and annual incident response plan reviews. | MedBridge Health does not have a documented incident response plan. |
| Backup and Recovery | Not specifically detailed in this template. | Added daily backups and restoration testing every six months. | The company has not tested its backup restoration process. |
| Third-Party Risk Management | General organizational governance requirements. | Added vendor security reviews and Business Associate Agreement requirements. | Twilio and Zendesk have missing BAAs in the fictional scenario. |
| Enforcement | General policy sanctions and disciplinary actions. | Assigned responsibilities to HR, the vCISO, IT Manager, and Privacy Officer. | Policy violations need to be reviewed by the appropriate company leaders. |
| Document Control | General expectations for program review and approval. | Added a policy owner, approver, version number, and annual review schedule. | Helps track policy ownership and maintain accountability. |

## What I Learned

This part of the project helped me understand that security policies should be written around an organization's actual risks and business needs rather than copied directly from a template.

I also learned how important it is to connect policy requirements to previously identified security weaknesses.

For example, MedBridge Health's outdated asset inventory, missing vendor agreements, and delayed employee offboarding helped me identify specific requirements that needed to be included in the Information Security Policy.

## Reference

SANS Institute / Cybersecurity Risk Foundation — Program Management Policy (February 2026).

This policy was used as a reference and customized for the fictional MedBridge Health environment.
