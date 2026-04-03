# Report Summary – Digital Forensics Investigation

## Project Context
This project was completed as part of the **Advanced Forensic Methods (AFM)** coursework at Asia Pacific University (APU).  
It simulates a real-world **Digital Forensics and Incident Response (DFIR)** workflow, covering evidence acquisition, analysis, malware identification, and formal reporting.

## Objectives
- Acquire and preserve digital evidence from live systems, RAM, and HDD.
- Perform forensic analysis using industry-standard tools.
- Identify malicious activity and reconstruct attack scenarios.
- Maintain chain of custody and produce a structured forensic report.

## Methodology
1. **Evidence Acquisition**
   - Live capture of volatile data (RAM).
   - Disk imaging using FTK Imager.
   - Preservation of evidence with proper chain of custody documentation.

2. **Tool-Based Analysis**
   - **Wireshark**: Network traffic inspection and anomaly detection.
   - **FTK Imager**: Disk imaging and file system exploration.
   - **Autopsy**: Timeline analysis and artifact recovery.
   - **Volatility**: Memory dump analysis for malware and process artifacts.
   - **VirusTotal**: Malware verification and threat intelligence correlation.

3. **Malware Identification**
   - Detection of suspicious processes and executables in memory.
   - Cross-validation with VirusTotal to confirm malicious signatures.

4. **Data Reconstruction & Correlation**
   - Rebuilt activity timeline from disk and memory artifacts.
   - Correlated network traffic with identified malware activity.
   - Validated findings across multiple sources.

5. **Chain of Custody**
   - Documented evidence handling procedures.
   - Ensured integrity and admissibility of forensic data.

## Key Findings
- Identified malicious processes running in memory.
- Recovered disk artifacts linked to malware execution.
- Network traffic analysis revealed suspicious connections.
- Correlated evidence confirmed compromise and attack scenario.

## Deliverables
- Structured forensic report including evidence summary, analysis, and conclusions.
- Documentation of chain of custody and forensic best practices.
- Case study demonstrating applied DFIR methodologies.

## Academic Note
This was a **team academic project**. My primary contributions included:
- Memory analysis using Volatility.
- Malware identification and correlation with disk artifacts.
- Drafting sections of the forensic report.

---
