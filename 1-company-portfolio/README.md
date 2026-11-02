# Project 1: MedBridge Health — Company Profile & Security Architecture

## Objective

The goal of this project was to create a fictional healthcare company and document its business operations, IT infrastructure, sensitive information, and potential cybersecurity risks.

I used MedBridge Health as my example to better understand how Governance, Risk, and Compliance (GRC) applies to healthcare organizations that handle patient information.

## Company Background

MedBridge Health, Inc. is a fictional telehealth company based in San Francisco, California. The company has 50 employees and provides virtual healthcare services to approximately 40,000 patients across six U.S. states.

Since the company handles Protected Health Information (PHI) and Personally Identifiable Information (PII), it needs to address healthcare security and privacy requirements, including HIPAA and HITECH.

## Project Scope

For this project, I focused on:

- Documenting the company's business operations and organizational structure.
- Identifying important IT assets and assigning business owners.
- Classifying sensitive information based on how it should be protected.
- Identifying third-party vendors that may handle patient information.
- Creating network architecture and patient data flow diagrams.
- Reviewing the fictional company's security weaknesses and recommending improvements.

## Frameworks and Tools

- HIPAA Security Rule
- NIST Cybersecurity Framework (CSF) 2.0
- GitHub
- draw.io (diagrams.net)

## Approach

1. Created a fictional healthcare company and documented its business operations.
2. Identified critical systems, applications, and third-party services.
3. Built an asset inventory to track important IT resources and their owners.
4. Created a network architecture diagram showing how the company's systems connect.
5. Developed a patient data flow diagram to understand how sensitive information moves between systems.
6. Reviewed eight simulated security weaknesses and recommended improvements.

## Key Findings

Based on the fictional company scenario, I identified several areas that need improvement:

- The company does not maintain an updated asset inventory.
- Security awareness training is limited.
- Backup restoration has not been tested.
- There is no documented incident response plan.
- Two vendors have missing Business Associate Agreements (BAAs).
- Shared administrator accounts make it difficult to track administrative activity.
- Security logs are collected but not regularly reviewed.
- Employee access is not always removed promptly during offboarding.

These findings will be used in future projects to build a risk register and assess MedBridge Health's cybersecurity program.

## Deliverables

- [Company Profile (PDF)](https://github.com/andree-salvo/GRC-PORTFOLIO/blob/main/1-company-portfolio/MedBridge%20Health%E2%80%94profile.pdf)
- [Asset Inventory (CSV)](https://github.com/andree-salvo/GRC-PORTFOLIO/blob/main/1-company-portfolio/asset-inventory.csv)
- [Network Architecture Diagram](diagrams/medbridge-network-architecture.drawio)
- [Patient Data Flow Diagram](diagrams/medbridge-patient-data-flow.drawio)

## Project Screenshots

### Network Architecture Diagram

<img width="568" height="600" alt="network-architecture" src="https://github.com/user-attachments/assets/17f3ad7d-9b50-4703-ac3c-78b146978f9b" />)

*This diagram shows the fictional company's main systems, cloud infrastructure, and network connections.*

### Patient Data Flow Diagram

<img width="696" height="830" alt="patient-data-flow" src="https://github.com/user-attachments/assets/a1f614ec-ac22-4b77-b50b-8d405088c0db" />

*This diagram shows a simulated patient data workflow and how information may move between healthcare systems.*

### Asset Inventory

<img width="938" height="563" alt="asset-inventory" src="https://github.com/user-attachments/assets/467a7a74-f7f0-4f5c-838b-88e5b30b9c49" />

*The asset inventory identifies the company's critical systems, business owners, and potential security risks.*

## What I Learned

This project helped me understand why it's important to know what systems and information an organization needs to protect before conducting a risk assessment.

I also gained experience documenting IT assets, identifying security weaknesses, and understanding how patient information moves between different systems.

One thing I learned is that even basic security issues, such as outdated asset inventories or delayed employee offboarding, can create risks for an organization.

I'll use what I documented in this project as the foundation for the next GRC labs.

## Disclaimer

MedBridge Health, Inc. is a fictional healthcare company created for educational and portfolio purposes. The infrastructure, data flows, and security findings are simulated and do not represent an actual healthcare organization.
