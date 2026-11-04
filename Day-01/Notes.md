DAY 01 — INTRODUCTION TO CYBERSECURITY
Beginner Notes | Cybersecurity from Zero
CodeFromZero 2.0 | Beginner Notes
1. What is cybersecurity?
Cybersecurity is the practice of protecting computers, networks, applications, devices, and data from unauthorized
access, misuse, disruption, modification, or destruction.
Its purpose is to help keep digital systems and information secure, reliable, and available to authorized users.
Everyday examples
• Protecting an email account with a strong password and multi-factor authentication (MFA).
• Encrypting sensitive information so that unauthorized people cannot easily read it.
• Keeping a college portal patched and restricting access to student records.
• Backing up important files so they can be restored after accidental deletion or ransomware.
2. What are we protecting?
A valuable item that needs protection is called an asset.
Examples:
3. The CIA Triad
The CIA Triad is a foundational information-security model. It describes three important security objectives.
C — Confidentiality
Meaning: Information should be accessible only to people or systems that are authorized to access it.
Example: A student should see their own private academic record, while another student should not be able to
view it without authorization.
Common ways to support confidentiality:
• Authentication: checking who a user is.
• Authorization: deciding what an authenticated user may do.
• Encryption: protecting information from being read by unauthorized parties.
• Least privilege: giving users only the access they need.
Question to remember: Who is allowed to see this data?
I — Integrity
Meaning: Information should remain accurate and complete, and changes should happen only in authorized ways.
Example: A student's marks should not be altered by an unauthorized person.
Common ways to support integrity:
• Access controls and permissions.
• Hashes to help detect whether data has changed.
• Digital signatures to help verify authenticity and integrity.
• Audit logs and version history.
• Input validation and controlled change processes.
Question to remember: Is the data accurate and has it been changed only appropriately?
A — Availability
Meaning: Information and services should be accessible to authorized users when needed.
Example: A college results portal should be available when students need to check their results.
Common ways to support availability:
• Reliable infrastructure and capacity planning.
• Backups and tested recovery procedures.
• Redundancy and failover.
• Monitoring, maintenance, and patching.
• Protection against service disruption, including denial-of-service attacks.
Question to remember: Can an authorized user access the service when needed?
4. CIA Triad — one college portal example
Imagine a college portal that stores student profiles, attendance, and marks.
A single incident can affect more than one principle. For example, ransomware may affect availability by locking
files and integrity if data is modified. If private information is also stolen, confidentiality is affected too.
5. Important beginner terms
• **Threat:** A potential cause of harm to a system or asset. Examples include a malicious attacker, fire, or
accidental deletion.
• **Vulnerability:** A weakness that could be exploited. Examples include an unpatched application or weak access
controls.
• **Risk:** The possibility and impact of harm when a threat takes advantage of a vulnerability.
• **Attack:** An attempt to compromise a system or its data.
• **Security control:** A safeguard that reduces risk, such as MFA, encryption, backups, or access restrictions.
• **Authentication:** Verifying an identity.
• **Authorization:** Determining what an identity is permitted to do.
• **Encryption:** Transforming readable data into protected form using cryptographic methods.
• **Backup:** A separate copy of data that can be used for recovery.
Threat vs vulnerability vs risk
Example:
• Threat: An attacker attempts to access a student account.
• Vulnerability: The account uses a reused password and has no MFA.
• Risk: The account may be taken over, exposing private records.
A threat is not the same thing as a vulnerability. Risk depends on the likelihood and impact of a harmful event.
6. Cybersecurity is broader than ethical hacking
Ethical hacking is one area within cybersecurity. Cybersecurity also includes:
• Security operations and monitoring.
• Network and cloud security.
• Application security.
• Digital forensics and incident response.
• Governance, risk, and compliance.
• Identity and access management.
• Security awareness and policy.
Ethical hacking involves authorized testing to identify weaknesses so they can be fixed. Testing without permission
is not ethical hacking.
