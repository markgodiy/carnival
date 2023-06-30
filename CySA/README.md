# Study Guide for CySA+ Certification

https://www.comptia.org/certifications/cybersecurity-analyst

## Exam Details
- 85 questions max
- 165 Minutes

## Domains
1. Security Operations (33%) 
2. Vulnerability Management (30%)
3. Incident Response and Management (20%)
4. Reporting and Communication (17%)

## 1.0 Security_Operations 

### 1.1 Explain the importance of system and network architecture in Security Operations

#### 1. Log Ingestion
- Time Synchronization
- Logging Levels
#### 2. Operating system concepts
- Windows Registry
- System hardening
- File Structure
  - Configuration File Locations
- System Processes
- Hardware Architecture
#### 3. Infrastructure Concepts
- Serverless
- Containerization
- Virtualization
#### 4. Network Architecture
- On-Premises
- Cloud 
- Hybrid
- Network Segmentation
- Zero-Trust
- Secure Access Secure Edge (SASE)
- Software Defined Networking (SDN)
#### 5. Identity and Access Management
- MFA
- SSO 
- Federation
- Priviledge Access Management (PAM)
- Passwordless 
- Cloud Access Security Broker (CASB)
#### 6. Encryption 
- PKI
- SSL Inspection
#### 7. Sensitive Data Protection
- Data Loss Prevention
- Personally Identifiable Information
- Cardholder Data

### 1.2 Given a scenario, analyze indicators of potential malicious activity

#### 1. Network-Related
- Bandwidth consumption
- Beaconing
- Irregular peer-to-peer communication
- Rogue devices on the network
- Scans and sweeps
- Unusual traffic spikes
- Activity on unexpected ports
#### 2. Host-Related
- Processor consumption
- Memory consumption
- Drive capacity consumption
- Unauthorized software
- Malicious processes
- Unauthorized changes
- Unauthorized privileges
- Data exfiltration
- Abnormal OS process behavior
- File system changes or anomalies
- Registry changes or anomalies
- Unauthorized scheduled tasks
#### 3. Application-related
- Anomalous Activity
- Introduction of New Accounts
- Unexpected Output
- Unexpected Outbound Communication
- Service Interruption
- Application Logs
- Social Engineering attacks
- Obfuscated Links

### 1.3 Given a scenario, use appropriate tools or techniques to determine malicious activity
#### 1. Tools
- Packet Capture
  - WireShark
  - TcpDump
- Log analysis
  - Security Information and Event Management (SIEM)
  - Security Orchestration, Automation, and Response (SOAR)
- Endpoint Security
  - Endpoint Detection and Response (EDR)
- DNS and IP Reputation
  - WhoIs
  - AbuseIPDB
- File Analysis
  - Strings
  - Virus Total
- Sandboxing
  - Joe Sandbox
  - Cuckoo Sandbox
#### 2. Common Techniques
- Pattern Recognition
  - Command and Control
- Interpreting Suspicious Commands
- Email Analysis
  - Header
  - Impersonation
  - Domain Keys Identified Mail (DKIM)
  - Domain Based Messaging, Authentication, Response, and Conformance (DMARC)
  - Sender Policy Framework (SPF)
  - Embedded Links
- File Analysis
  - Hashing
- User Behavior Analysis
  - Abnormal Account Activity
  - Impossible Travel
#### 3. Programming Languages/Scripting
- Javascript Object Notation (JSON)
- Extensible Markup Language (XML)
- Python
- PowerShell
- Shell script
- Regular Expressions

### 1.4 Compare and Contrast Threat-Intelligence and Threat-Hunting Concepts
#### 1. Threat Actors
- Advanced Persistent Threats (APT)
- Hacktivists
- Orgainized Crime
- Nation States
- Script-Kiddie
- Insider Threat
  - Intentional
  - Unintentional
- Supply Chain
#### 2. Tactics, Techniques, and Procedures (TTP)
#### 3. Condifence Levels
- Timeliness
- Relevancy
- Accuracy
#### 4. Collection Methods and Sources
- Open Source
  - Social Media
  - Blogs/Forums
  - Government Bulletins
  - Computer Emergency Response Team (CERT)
  - Deep/Dark Web
- Closed Source
  - Paid Feeds
  - Information Sharing Orgs
  - Internal Sources
- Threat Intelligence Sharing
  - Incident Response
  - Vulnerability Management
  - Risk Management
  - Security Engineering
  - Detection and Monitoring
#### 5. Threat Hunting
- Indicators of Compromise (IoC)
  - Collection
  - Analysis
  - Application
- Focus Areas
  - Configurations/Misconfigs
  - Isolated Networks
  - Business Critical Assets/Processes
- Active Defense
- Honeypot

### 1.5 Explain the importance of Efficiency and Process Improvement in security operations

#### 1. Standardize Processes
- Identification of Tasks suitable for Automation
  - Repeatable, no human interaction necessary
- Team coordination to manage and facilitate automation
#### 2. Streamline Operations
- Automation and Orchestration
  - Security Operations Automation and Response (SOAR)
- Orchestration Threat Intelligence Data
  - Data Enrichment
  - Threat Feed Combination
- Maximize Human Engagement
#### 3. Technology and Tool integration
- Application Programming Interface (API)
- Webhooks
- Plugins
#### 4. "Single Pane of Glass"

## 2.0 Vulnerability_Management

### 2.1 Implement vulnerability scanning methods and concepts
#### 1. Asset Discovery
- Map Scans
- Device Fingerprinting
#### 2. Special Considerations
- Scheduling 
- Operations
- Performance
- Sensitivity Levels
- Segmentation
- Regulatory Requirements
#### 3. Internal vs External Scanning
#### 4. Agent vs Agentless
#### 5. Credentialed vs Non-Credentialed
#### 6. Static vs Dynamic
- Reverse Engineering
- Fuzzing
#### 7. Critical Infrastructure
- Operational Technology (OT)
- Industrial Control Systems (ICS)
- Supervisory Control and Data Acquisition (SCADA)
#### 8. Security Baseline Scanning
#### 9. Industry Frameworks
- Payment Card Industry Data Security Standard (PCI DSS)
- Center for Internet Security Benchmarks (CIS)
- Open Web Application Security Project (OWASP)
- International Organization for Standardization (ISO) 27000 series

### 2.2 Analyse output from vulnerability assessment tools

#### 1. Tools
- Network Scanning and Mapping
  - Angry IP Scanner
  - Maltego
- Web Application Scanners
  - Burp Suite
  - Zed Attack Proxy (ZAP)
  - Arachni
  - Nikto
- Vulnerability Scanners
  - Nessus
  - OpenVAS
- Debuggers
  - Immunity Debugger
  - GNU Debugger (GDB)
- Multipurpose
  - NMAP
  - Metasploit Framework (MSF)
  - Recon-NG
- Cloud infrastructure Assessment
  - Scout Suite
  - Prowler
  - Pacu

### 2.3 Analyze data to prioritize vulnerabilities
#### 1. Common Vulnerability Scoring System (CVSS) Interpretation
- Attack Vectors
- Attack complexity
- Privileges required
- User interaction
- Scope
- Impact
  - Confidentiality
  - Integrity
  - Availability

#### 2. Validation
- True/False Positives
- True/False Negatives
#### 3. Context Awareness
- Internal
- External
- Isolated

#### 4. Exploitability/Weaponization
#### 5. Asset Value
#### 6. Zero-Day

### 2.4 Recommend Controls to mitigate attacks and software vulnerabilities

### 2.5 Explain concepts related to vulnerability response, handling, and management

## 3.0 Incident_Response_and_Management

### 3.1 Explain concepts relate to attack methodology frameworks
### 3.2 Perform incident response activities
### 3.3 Explain the preparation and post-incident activity phases of the incident management lifecycle

## 4.0 Reporting_and_Communication

### 4.1 Explain the importance of vulnerability management reporting and communication
### 4.2 Explain the importance of indicdent response reporting and communication
