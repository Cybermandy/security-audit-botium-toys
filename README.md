# security-audit-botium-toys
Security audit project based on the Google Cybersecurity Certificate

# Security Audit - Botium Toys

## Description
This project presents an internal security audit conducted for a fictional company, Botium Toys, as part of the Google Cybersecurity Certificate program.

The purpose of this audit is to assess risks, evaluate existing security controls, and analyze compliance with industry standards such as PCI DSS, GDPR, and SOC.

## Audit Scope
The audit covers:
- Internal IT systems  
- Customer data and transaction processes  
- Network infrastructure  
- Physical systems (office, storefront, warehouse)  
- E-commerce operations  

## Objectives
- Identify vulnerabilities and security risks  
- Evaluate existing security controls  
- Assess compliance with regulatory standards  
- Recommend improvements to strengthen security posture  

## Controls Assessment

| Control | Status |
|--------|--------|
| Least Privilege | No |
| Disaster Recovery Plan | No |
| Password Policies | No |
| Separation of Duties | No |
| Firewall | Yes |
| Intrusion Detection System (IDS) | No |
| Backups | No |
| Antivirus Software | Yes |
| Legacy System Monitoring | No |
| Encryption | No |
| Password Management System | No |
| Physical Locks | Yes |
| CCTV Surveillance | Yes |
| Fire Detection/Prevention | Yes |

## Compliance Assessment

### PCI DSS
- Access control: No  
- Encryption: No  
- Data protection: No  
- Secure password policies: No  

### GDPR
- Data protection: No  
- Breach notification (72h): Yes  
- Data classification: No  
- Privacy policies: Yes  

### SOC
- User access policies: No  
- Data confidentiality: No  
- Data integrity: Yes  
- Data availability: Yes  

## Key Risks Identified
- Lack of access control (no least privilege)  
- Absence of encryption for sensitive data  
- No data backups or disaster recovery plan  
- Weak password policies  
- Non-compliance with PCI DSS and GDPR  

## Recommendations

### High Priority
- Implement least privilege access control  
- Apply encryption to sensitive and financial data  
- Enforce strong password policies  
- Implement regular data backups  
- Develop a disaster recovery plan  

### Medium Priority
- Deploy an Intrusion Detection System (IDS)  
- Implement a password management system  
- Improve legacy system monitoring processes  

### Low Priority
- Regularly review security policies  
- Provide employee security awareness training  

## Conclusion
Botium Toys currently faces a high level of security risk due to missing critical controls and gaps in compliance.

Implementing the recommended measures will significantly reduce risks, protect sensitive data, and improve the organization's overall security posture.
