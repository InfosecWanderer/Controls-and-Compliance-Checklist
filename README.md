# Botium Toys: Scope, Goals, and Risk Assessment Report

## Description
This report presents an audit of the security program at Botium Toys, focusing on the evaluation of assets, controls, and compliance practices. The aim is to assess the current security posture and identify areas for improvement to ensure the organization meets U.S. and international regulations and standards. The findings highlight significant risks and offer best practices for enhancing security measures.

## Scope and Goals of the Audit
### Scope
The scope of this audit encompasses the entire security program at Botium Toys, including:
- Employee equipment and devices
- Internal network
- Systems and services utilized by the organization

### Goals
The primary goals are to:
- Assess existing assets
- Complete a controls and compliance checklist
- Identify necessary controls and compliance best practices to enhance Botium Toys’ security posture

## Current Assets
Assets managed by the IT Department include:
- On-premises equipment for in-office business needs
- Employee equipment: desktops, laptops, smartphones, remote workstations, and peripherals
- Storefront products for retail sale, stored in the company’s warehouse
- Management of systems for accounting, telecommunications, database, security, ecommerce, and inventory
- Internet access
- Internal network
- Data retention and storage
- Maintenance of legacy systems requiring monitoring

## Risk Assessment
### Risk Description
Botium Toys currently lacks adequate management of its assets, and proper controls are not fully in place. There is a risk of non-compliance with U.S. and international regulations.

### Control Best Practices
To mitigate risks, Botium Toys should:
- Dedicate resources to identify and classify assets
- Assess the impact of asset loss on business continuity

### Risk Score
On a scale of 1 to 10, the risk score is **8**, indicating a fairly high risk level due to insufficient controls and compliance practices.

### Additional Comments
The potential impact of asset loss is rated as medium, as the IT department lacks visibility into at-risk assets. The risk of fines from regulatory bodies is high due to the absence of necessary controls. Specific issues include:
- All employees have access to sensitive data, including cardholder data and personal identifiable information (PII).
- No encryption is used for customers' credit card information.
- Access controls for least privilege and separation of duties are not implemented.
- While the IT department has measures to ensure availability and data integrity, there is no intrusion detection system (IDS) installed.
- No disaster recovery plans or backups of critical data exist.
- A nominal password policy is in place, lacking complexity requirements, and no centralized password management system exists.
- Physical security measures are adequate, including locks, CCTV, and fire detection systems.

## Controls and Compliance Checklist

***

### Introduction to Controls and Compliance Checklist
### Purpose and Scope
The controls and compliance checklist is designed to assess Botium Toys' adherence to regulatory requirements, industry standards, and internal policies governing information security and operational practices. This assessment covers key areas such as data protection, access controls, network security, incident response, and physical security.

### Objectives
The primary objectives of this checklist are to:
- Identify gaps in compliance with applicable laws, regulations, and standards.
- Evaluate the effectiveness of existing controls and practices in mitigating risks.
- Document the current state of compliance to support internal and external audits.
- Provide a foundation for developing remediation strategies to enhance security and compliance posture.

### Controls and Compliance Checklist for Botium Toys
- **Audit Date:** June 18th, 2024
- **Audit Team Members:** Lawrence [IT Security Analyst]

### Instructions
This checklist is designed to assess Botium Toys’ compliance with regulatory requirements, industry standards, and internal policies related to information security and operational practices. Please review each control area and select "Yes" or "No" to indicate whether the control is currently in place. Provide comments or additional details where necessary to document findings.

### Controls Assessment Checklist
![image](https://github.com/user-attachments/assets/0c40a31d-e0ea-4afa-b1cb-51f90344bcd0)
![image](https://github.com/user-attachments/assets/62808680-9f0c-4e57-9d42-43e049aca422)

## Compliance Checklist

### Payment Card Industry Data Security Standard (PCI DSS)
![image](https://github.com/user-attachments/assets/ee4e5366-c80c-4a7b-b0f1-c5eefd7ff6c7)

### General Data Protection Regulation (GDPR)
![image](https://github.com/user-attachments/assets/a33b7b4a-474f-4fec-8022-e76907486e95)


### System and Organizations Controls (SOC Type 1, SOC Type 2)
![image](https://github.com/user-attachments/assets/fe4d7cfe-72e9-437e-a2c2-83a782dcd2fa)


## Recommendations

***

Based on the information provided in the Botium Toys’ security risk assessment report, here are recommendations for best practices to improve their security posture:

1. **Access to Internally Stored Data:**
   - **Current Situation:** All employees have access to sensitive information.
   - **Recommendation:** Implement least privilege access to restrict data access based on roles.

2. **Encryption of Credit Card Information:**
   - **Current Situation:** Credit card information is not encrypted.
   - **Recommendation:** Use strong encryption methods (e.g., AES-256) for sensitive data.

3. **Access Controls and Separation of Duties:**
   - **Current Situation:** Least privilege and separation of duties are not enforced.
   - **Recommendation:** Establish controls to limit access and prevent conflicts of interest.

4. **Data Integrity Controls:**
   - **Current Situation:** Specific data integrity measures are lacking.
   - **Recommendation:** Implement regular verification mechanisms like checksums and audit logs.

5. **Firewall Security:**
   - **Current Situation:** A firewall exists but requires updates.
   - **Recommendation:** Regularly review and update firewall rules.

6. **Antivirus Software:**
   - **Current Situation:** Antivirus software is installed and monitored.
   - **Recommendation:** Ensure definitions are up to date and consider advanced detection solutions.

7. **Intrusion Detection System (IDS):**
   - **Current Situation:** No IDS is in place.
   - **Recommendation:** Implement an IDS to monitor for unauthorized access.

8. **Disaster Recovery and Data Backups:**
   - **Current Situation:** No disaster recovery plans or backups exist.
   - **Recommendation:** Develop a comprehensive disaster recovery plan with regular backups.

9. **EU Customer Breach Notification and Privacy Policies:**
   - **Current Situation:** A breach notification plan exists.
   - **Recommendation:** Regularly review and update privacy policies for compliance.

10. **Password Policy and Management:**
    - **Current Situation:** Existing password policy is insufficient.
    - **Recommendation:** Revise the policy to enforce stronger complexity and implement centralized management.

11. **Legacy System Maintenance:**
    - **Current Situation:** Maintenance lacks a regular schedule.
    - **Recommendation:** Establish a consistent maintenance schedule for legacy systems.

12. **Physical Security Measures:**
    - **Current Situation:** Physical security measures are adequate.
    - **Recommendation:** Regularly assess and update physical security protocols.

## Summary
This audit report highlights critical vulnerabilities in Botium Toys’ security program, emphasizing the need for improved asset management, compliance practices, and control implementations.By implementing these recommendations, Botium Toys can enhance its security posture, mitigate risks associated with data breaches, and improve compliance with regulatory requirements, thereby safeguarding sensitive information and maintaining trust with customers and stakeholders. Regular audits and ongoing monitoring are crucial to ensure these measures remain effective over time.
