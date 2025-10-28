# Security Principles

## Learning Objectives:
- Understand the CIA Triad and its importance.
- Explain Risk, Privacy, and Accountability.
- Relate security principles to real-world cyber incidents.

## CIA Triad
- The CIA Triad forms the foundation of information security.
- Each element ensures that information remains safe and trustworthy.


<img width="237" height="212" alt="download" src="https://github.com/user-attachments/assets/9b4df54e-b1b9-4d94-ad0e-f9459423118e" />


| Element | Description | Example |
|----------|--------------|----------|
| Confidentiality | Ensures data is accessible only to authorized users. | Encrypting files, using passwords, access control lists. |
| Integrity | Ensures data is accurate, consistent, and not tampered with. | Using hashing, digital signatures, checksums. |
| Availability | Ensures systems and data are available when needed. | Redundant servers, backups, DDoS protection. |



## Key Concepts
- Data breaches often occur when one or more CIA principles are compromised.
- Balance is key — too much focus on one (e.g., availability) can weaken another (e.g., confidentiality).
  
# risk,privacy and accountability
## risk
- definition:probability of a threat exploiting a vulnerability to cause harm.

## components: 
- threat -> something that can cause damage
- vulnerability -> weakness that can be exploited
- impact -> damage if threat is realized

- ## formula:
- risk= threat x vulnerability x impact

## example:
- threat:phishing
- vulnerabilty:employee lack of awareness
- impact: credential theft,financiial loss


![download](https://github.com/user-attachments/assets/a5e33613-f0ca-4865-b373-bee25a4791d3)

# privacy
- protecting personal and sensitive information of individuals
- governed by laws like GDPR,DPDP act(india),HIPAA



![download](https://github.com/user-attachments/assets/12f2ae1e-30d8-4ff2-9941-8183d2c575fb)

## key practices
- data minimization
- informed consent
- data anonymization
- example: a healthcare app must not share user health data without consent.

# accountability

- ensuring every action in an IT system can be traced back to an individual.

## achieved through  
- logging and auditing.
- user access tracking
- non-repudiation mechanisms
- example: audit logins in firewalls to trace malicious user actions.

# real-world case studies
| Case | Description | Violated Principle |
|------|--------------|--------------------|
| WannaCry (2017) | Ransomware disabled hospital systems worldwide | Availability |
| Equifax Breach (2017) | Personal data of 143M users leaked | Confidentiality & Integrity |
| Twitter Hack (2020) | Insider access to admin tools | Confidentiality & Accountability |


