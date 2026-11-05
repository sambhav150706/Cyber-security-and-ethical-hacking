# DAY 03 — FIVE PHASES OF PENETRATION TESTING

## 1. What is Penetration Testing?

Penetration Testing (Pen Testing) is an authorized security assessment in which a cybersecurity professional simulates attacks against a computer system, network, or application to identify security weaknesses.

**Main objectives:**
- Identify security vulnerabilities.
- Evaluate the security of systems.
- Understand possible attack paths.
- Help organizations improve their security.
- Prevent unauthorized access and data breaches.

**Important:** Penetration testing must always be performed with proper authorization and a clearly defined scope.

## 2. Five Phases of Penetration Testing

Penetration testing is commonly divided into five phases:

1. Reconnaissance
2. Scanning and Enumeration
3. Gaining Access
4. Maintaining Access
5. Covering Tracks

### Phase 1: Reconnaissance

**Definition:** Reconnaissance is the first phase of penetration testing. It involves collecting information about the target before attempting any security tests.

**Objectives:**
- Identify the target organization or system.
- Collect domain and IP address information.
- Discover publicly available information.
- Understand the target's technology and infrastructure.

**Types of Reconnaissance:**

1. Passive Reconnaissance:
   - Collecting information without directly interacting with the target's systems.
   - Example: Searching public websites, social media and WHOIS records.

2. Active Reconnaissance:
   - Directly interacting with the target to collect information.
   - Example: Authorized network discovery and service probing.

**Common tools:**
- WHOIS
- Google Dorking
- Maltego
- theHarvester
- Shodan

**Example:** Finding publicly available domain information and identifying an organization's exposed subdomains.

### Phase 2: Scanning and Enumeration

**Definition:** Scanning and Enumeration involve examining the target system or network to identify active hosts, open ports, running services and possible vulnerabilities.

**Objectives:**
- Identify active devices.
- Discover open ports.
- Identify running services.
- Detect possible vulnerabilities.
- Collect additional technical information.

**Scanning:** Identifies systems, ports and services.

**Enumeration:** Collects more detailed information about discovered services, users, shares or other resources.

**Common tools:**
- Nmap
- Nessus
- OpenVAS / Greenbone Vulnerability Management (GVM)
- Nikto
- Netcat

**Example:** Discovering that an authorized test server has port 22 (SSH) and port 80 (HTTP) open.

### Phase 3: Gaining Access

**Definition:** Gaining Access is the phase in which a penetration tester attempts to validate whether an identified vulnerability can be exploited to gain unauthorized-level access within the agreed testing scope.

**Objectives:**
- Validate identified vulnerabilities.
- Test security weaknesses.
- Evaluate the impact of successful exploitation.
- Determine whether sensitive resources could be accessed.

**Common techniques:**
- Password security testing.
- Exploitation of vulnerable services.
- SQL Injection testing.
- Cross-Site Scripting (XSS) testing.
- Privilege escalation testing.

**Common tools:**
- Metasploit Framework
- Burp Suite
- SQLmap
- Hydra

**Example:** Demonstrating that a deliberately vulnerable application allows access through an SQL Injection vulnerability in an authorized lab.

### Phase 4: Maintaining Access

**Definition:** Maintaining Access involves assessing whether access obtained during an authorized penetration test could persist or be reused.

**Objectives:**
- Evaluate persistence-related security weaknesses.
- Test session management.
- Assess privilege escalation risks.
- Understand the potential impact of prolonged access.

**Common concepts:**
- Persistence mechanisms.
- Session hijacking.
- Privilege escalation.
- Weak authentication and access controls.

**Common tools:**
- Metasploit Framework
- Empire (in controlled security labs)
- PowerShell security-testing tools

**Example:** Testing whether a compromised test account can retain access after a session ends.

**Note:** Persistence testing must be explicitly authorized. Avoid installing persistent access mechanisms on real systems without permission.

### Phase 5: Covering Tracks

**Definition:** Covering Tracks is traditionally described as the final phase of penetration testing. It examines how an attacker might attempt to hide their activities and avoid detection.

