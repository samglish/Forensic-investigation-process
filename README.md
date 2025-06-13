# Forensic-investigation-process
The forensic process involves collecting, analyzing, and preserving digital evidence to understand security incidents.
## Computer Crime Investigation

### Introduction
Computer crime investigation is a branch of digital forensics that aims to detect, analyze, preserve, and present digital evidence related to illegal activities carried out via or against computer systems.

### Objectives of Digital Investigation
* Identify sources of digital evidence.
* Preserve the integrity of collected data.
* Reconstruct events that led to an attack.
* Identify the perpetrators or those responsible for malicious actions.
* Provide admissible evidence in a court of law.

### Key Steps in the Investigation
1. Identification
* Detection of an incident or crime (e.g., intrusion, fraud, data theft).
* Defining the digital crime scene.

2. Preservation
* Backing up systems, drives, and event logs.
* Using bit-by-bit imaging tools to avoid altering evidence.

3. Collection
* Extracting files, emails, logs, metadata, etc.
* Maintaining the chain of custody.

4. Analysis
* Examining data using specialized tools (e.g., EnCase, Autopsy, Volatility).
* Reconstructing activities: logins, transfers, deletions, etc.

5. Presentation
* Writing a clear and chronological technical report.
* Legal use of evidence: expert testimony, submitting evidence in court.

### Types of Computer Crimes Investigated

| Type of Crime   | Example                                           |
|-----------------|---------------------------------------------------|
| **Intrusion**    | Unauthorized access to a server                  |
| **Fraud**        | Phishing, bank fraud                             |
| **Espionage**    | Theft of confidential data                       |
| **Sabotage**     | Data deletion or denial of service               |
| **Hacking**      | Deployment of malicious software (malware)       |

### Tools and Methods Used

**Disk Analysis**: FTK Imager, Autopsy  
**RAM Analysis**: Volatility Framework  
**Network Analysis**: Wireshark, tcpdump  
**Timeline and Correlation**: Plaso, SleuthKit

### Legal Aspects

* Comply with local laws (e.g., GDPR, cybersecurity laws, Budapest Convention).
* Digital evidence must be **authentic**, **intact**, **complete**, and **explainable**.

### Best Practices

* Always work on a **copy** of the original data.
* **Document** every action (time, tool used, responsible person).
* Use **certified tools** recognized by the forensic community.
