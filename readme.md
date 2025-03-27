# Botium Toys Cybersecurity Audit Report

## Scenario
The scope of this audit encompasses the entire security program at Botium Toys, including their assets such as employee equipment and devices, internal network, and systems. The goals are to assess existing assets and complete the controls and compliance checklist to identify necessary improvements to Botium Toys’ security posture.

### Current Assets
- On-premises equipment for in-office business needs
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products available for retail sale on-site and online; stored in the company’s adjoining warehouse
- Management of systems, software, and services: accounting, telecommunication, database, security, e-commerce, and inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance

### Risk Assessment
- **Risk Score**: 8 (on a scale of 1 to 10)
- **Risk Description**: Inadequate management of assets and lack of proper controls.

## Control Categories

### Administrative/Managerial Controls

| Control Name                     | Control Type | Control Purpose                                                                                      |
|----------------------------------|--------------|------------------------------------------------------------------------------------------------------|
| Least Privilege                  | Preventative | Reduce risk and overall impact of malicious insider or compromised accounts                         |
| Disaster Recovery Plans           | Corrective   | Provide business continuity                                                                           |
| Password Policies                 | Preventative | Reduce likelihood of account compromise through brute force or dictionary attack techniques          |
| Access Control Policies           | Preventative | Bolster confidentiality and integrity by defining which groups can access or modify data            |
| Account Management Policies       | Preventative | Manage account lifecycle, reducing attack surface, and limiting overall impact from disgruntled former employees and default account usage |
| Separation of Duties              | Preventative | Reduce risk and overall impact of malicious insider or compromised accounts                         |

### Technical Controls

| Control Name                     | Control Type | Control Purpose                                                                                      |
|----------------------------------|--------------|------------------------------------------------------------------------------------------------------|
| Firewall                          | Preventative | Filter unwanted or malicious traffic from entering the network                                       |
| IDS/IPS                           | Detective     | Detect and prevent anomalous traffic that matches a signature or rule                                 |
| Encryption                        | Deterrent    | Provide confidentiality to sensitive information                                                     |
| Backups                           | Corrective   | Restore/recover from an event                                                                         |
| Password Management               | Preventative | Reduce password fatigue                                                                               |
| Antivirus (AV) Software          | Preventative | Scan to detect and quarantine known threats                                                          |
| Manual Monitoring, Maintenance, and Intervention | Preventative | Identify and manage threats, risks, or vulnerabilities to out-of-date systems                       |

### Physical/Operational Controls

| Control Name                     | Control Type          | Control Purpose                                                                                      |
|----------------------------------|-----------------------|------------------------------------------------------------------------------------------------------|
| Time-Controlled Safe             | Deterrent             | Reduce attack surface and overall impact from physical threats                                       |
| Adequate Lighting                | Deterrent             | Deter threats by limiting “hiding” places                                                            |
| Closed-Circuit Television (CCTV) | Preventative/Detective | Reduce risk of certain types of events from occurring and inform on event conditions after an event |
| Locking Cabinets (for Network Gear) | Preventative       | Bolster integrity by preventing unauthorized personnel from physically accessing or modifying network infrastructure gear |
| Signage Indicating Alarm Service Provider | Deterrent    | Deter certain types of threats by making the likelihood of a successful attack seem low             |
| Locks                            | Deterrent/Preventative | Bolster integrity by deterring and preventing unauthorized personnel from physically accessing assets  |
| Fire Detection and Prevention (Fire Alarm, Sprinkler System, etc.) | Detective/Preventative | Detect fire in physical location and prevent damage to physical assets such as inventory, servers, etc. |

## Recommendations

To address the security issues identified in the audit, I recommend the following actions for the IT department at Botium Toys:

1. **Asset Identification and Management**: Conduct a comprehensive inventory and classification of all assets to prioritize security measures.
   
2. **Access Control Enhancements**: Implement least privilege access and establish separation of duties to minimize risks.

3. **Data Encryption**: Encrypt sensitive data, including credit card information and PII, both at rest and in transit.

4. **Intrusion Detection and Prevention**: Install an IDS to monitor and respond to suspicious activities effectively.

5. **Disaster Recovery and Backup Plans**: Develop a disaster recovery plan and implement regular data backups to ensure business continuity.

6. **Password Policy and Management**: Revise the password policy for stronger requirements and utilize a centralized password management system.

7. **Regular Security Audits and Assessments**: Schedule periodic security audits and engage in penetration testing to identify and address vulnerabilities.

8. **Employee Training and Awareness**: Implement ongoing security awareness training and establish a clear incident reporting mechanism.

9. **Compliance with Regulations**: Review and adopt relevant compliance frameworks and maintain documentation of all compliance efforts.

10. **Monitoring and Continuous Improvement**: Consider setting up a Security Operations Center (SOC) and foster a culture of continuous improvement in security practices.

By implementing these recommendations, Botium Toys can significantly enhance its security posture and mitigate risks to its assets.


# Stakeholder Memorandum

**TO**: IT Manager, Stakeholders  
**FROM**: John Patrick Anteola
**DATE**: 27/03/2025  
**SUBJECT**: Internal IT Audit Findings and Recommendations

---

Dear Colleagues,

I am writing to share important insights regarding the findings from the recent internal audit conducted at Botium Toys. This memorandum outlines the audit scope, goals, critical findings, a summary of recommendations, and conclusions that are essential for enhancing our security posture.

## Scope of the Audit

The audit encompassed several key systems, specifically focusing on:
- Accounting
- Endpoint Detection
- Firewalls
- Intrusion Detection System (IDS)
- Security Information and Event Management (SIEM) tool

The evaluation criteria include:
- Current user permissions for accessing systems and data
- Existing implemented controls
- Current procedures and protocols
- Alignment with compliance requirements, specifically GDPR and PCI DSS
- Comprehensive accounting for all technology and assets, including hardware and system access

## Goals of the Audit

The primary objectives of the audit are as follows:
- Adhere to the NIST Cybersecurity Framework (CSF)
- Establish a more efficient process to ensure compliance across systems
- Fortify existing system controls
- Implement the principle of least privilege in user credential management
- Create and formalize comprehensive policies and procedures, inclusive of playbooks

## Critical Findings (Immediate Attention Required)

The audit revealed several critical areas that require immediate action:
- **Principle of Least Privilege and Separation of Duties**: Essential for reducing risk and enhancing security.
- **Disaster Recovery Plans**: These plans are vital for maintaining business continuity in the face of disruptions.
- **Password, Access Control, and Account Management Policies**: Must be established to safeguard user accounts and sensitive information.
- **Intrusion Detection System (IDS)**: Implementation is crucial for real-time threat detection and response.
- **Encryption**: Secure transactions and protect sensitive information stored on disk drives.
- **Backups**: Regular backups are needed to ensure data recovery in case of incidents.
- **Password Management System**: To streamline and secure password handling.
- **Antivirus (AV) Software**: Required for threat detection and prevention.
- **Manual Monitoring and Maintenance**: Necessary for legacy systems to mitigate risks.
- **Physical Security Measures**: Including Closed-Circuit Television (CCTV) surveillance, locks, and locking cabinets for network gear.
- **Fire Detection and Prevention Systems**: Such as fire alarms and sprinkler systems to protect physical assets.

## Policy Development Recommendations

Policies must be developed and implemented to ensure compliance with:
- PCI DSS and GDPR requirements
- SOC1 and SOC2 guidelines related to user access policies and overall data safety

## Additional Findings (Future Considerations)

While not immediately urgent, the following physical controls should be evaluated for future implementation:
- **Time-Controlled Safe**: To secure sensitive physical assets.
- **Adequate Lighting**: Enhances security by minimizing hidden areas.
- **Signage Indicating Alarm Service Provider**: Acts as a deterrent for potential threats in restricted areas.

## Summary of Recommendations

It is imperative that we address the critical findings related to compliance with PCI DSS and GDPR as Botium Toys expands its online payment capabilities and services, particularly concerning customer data from the European Union. Aligning our practices with SOC1 and SOC2 guidance will facilitate the effective implementation of least privilege principles and the necessary policies and procedures for compliance.

Additionally, establishing disaster recovery plans and backup processes is critical for ensuring business continuity during unforeseen incidents, whether they are physical disasters or cyberattacks that could disrupt operations. Implementing effective fire detection and prevention systems is also worth considering to bolster our physical security measures.

Incorporating an IDS and effective AV software will enhance our capability to detect intrusions and mitigate potential risks, especially as we manage legacy systems that require manual oversight.

To enhance the security of Botium Toys’ physical location, implementing locks and CCTV will safeguard physical assets and provide monitoring against potential threats. The introduction of a time-controlled safe, ensuring adequate lighting, and providing clear signage indicating alarm service providers will further strengthen our overall security posture.

Thank you for your attention to these important matters.

Best regards,

John Patrick Anteola


## Conclusion

This memorandum summarizes the findings and recommendations from the internal audit. I hope you find this information both useful and insightful. I welcome any constructive feedback or suggestions for improvement.

### Self-Evaluation

Reflecting on this process, I believe I successfully identified the top priority controls that need immediate implementation to reduce risk. I also recognized the importance of adhering to relevant regulations and standards. This assignment has challenged me to apply the knowledge I’ve gained through my studies and hands-on experience.

### Lessons Learned

Throughout this audit, I encountered challenges in articulating my findings within the stakeholder memorandum. I learned the importance of being concise and direct, utilizing lists for clarity, and ensuring my writing is proofread to avoid redundancy. Additionally, I recognized the need to clearly explain how System and Organization Controls standards relate to user access policies, confidentiality, privacy, integrity, availability, security, and overall data safety, beyond mere financial compliance.

---

