# Security Audit Documentation

This documentation provides a security audit checklist and compliance assessment for Botium Toys. It includes controls assessment and compliance best practices to mitigate risks and ensure regulatory compliance.

## Controls Assessment Checklist

- [x] Least Privilege
- [x] Disaster recovery plans
- [x] Password policies
- [x] Separation of duties
- [x] Firewall
- [x] Intrusion detection system (IDS)
- [x] Backups
- [x] Antivirus software
- [x] Manual monitoring, maintenance, and intervention for legacy systems
- [x] Encryption
- [x] Password management system
- [x] Locks (offices, storefront, warehouse)
- [x] Closed-circuit television (CCTV) surveillance
- [x] Fire detection/prevention (fire alarm, sprinkler system, etc.)

## Compliance Checklist

### Payment Card Industry Data Security Standard (PCI DSS)

- [x] Only authorized users have access to customers’ credit card information.
- [x] Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment.
- [x] Implement data encryption procedures to better secure credit card transaction touchpoints and data.
- [x] Adopt secure password management policies.

### General Data Protection Regulation (GDPR)

- [x] E.U. customers’ data is kept private/secured.
- [x] There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach.
- [x] Ensure data is properly classified and inventoried.
- [x] Enforce privacy policies, procedures, and processes to properly document and maintain data.

### System and Organizations Controls (SOC type 1, SOC type 2)

- [x] User access policies are established.
- [x] Sensitive data (PII/SPII) is confidential/private.
- [x] Data integrity ensures the data is consistent, complete, accurate, and has been validated.
- [x] Data is available to individuals authorized to access it.

## Recommendations

- **Least Privilege:** Prioritize implementing this control. Limiting user access rights only to what's necessary for their job role significantly reduces internal and external risks.
- **Disaster Recovery Plans:** Essential for business continuity. Develop comprehensive plans to ensure quick recovery from disruptions.
- **Password Policies:** Enforce strong password creation and regular updates. This is a fundamental control for securing access to systems.
- **Separation of Duties:** Implement to prevent fraud and errors. This ensures no single individual has control over all aspects of any critical task.
- **Firewall and IDS:** Critical for network security. Ensure they are updated and configured to protect against external threats.
- **Backups:** Regular backups of critical data are vital. Implement automated solutions and test them regularly.
- **Antivirus Software:** Essential for detecting and removing malware. Keep it updated for latest threat protection.
- **Legacy Systems Monitoring:** Given their vulnerabilities, ensure manual checks and maintenance routines are robust.
- **Encryption:** Apply to sensitive data, both at rest and in transit, to protect from unauthorized access.
- **Password Management System:** Implement to manage and secure passwords effectively, reducing the risk of breaches.
- **Physical Security (Locks, CCTV):** Enhance physical security to safeguard assets from theft or damage.
- **Fire Detection/Prevention:** Critical for physical safety and to protect assets from fire damage.

### Compliance Recommendations

#### PCI DSS

- Ensure all practices are in place. Special attention to encryption and secure storage of credit card data is crucial.

#### GDPR

- Compliance is mandatory for businesses dealing with E.U. customers. Focus on data privacy, breach notification plans, and data classification.

#### SOC Reports

- Ensure policies for user access, data privacy, integrity, and availability are established and enforced. These are key for SOC compliance.

Overall, prioritize controls and compliance practices based on the risk they mitigate and the impact on Botium Toys’ operations. Regular audits and updates to these controls and practices are necessary to adapt to evolving threats and regulatory changes. Communicate the importance of these measures to all stakeholders to foster a culture of security and compliance within the organization.

---

*Created by Pedro Arturo Gonzalez Campos*
