# Case Study – Evidence Correlation & Reconstruction

## Objective
To correlate findings from memory, disk, and network analysis in order to reconstruct the attack scenario and validate forensic evidence.

## Process
1. **Cross-Source Validation**
   - Linked suspicious processes found in RAM (Volatility) with executables recovered from disk (Autopsy/FTK Imager).
   - Verified persistence mechanisms in registry entries against memory artifacts.

2. **Network Correlation**
   - Matched outbound connections identified in Wireshark with malware processes discovered in memory.
   - Confirmed communication with known malicious IP addresses.

3. **Timeline Reconstruction**
   - Built a chronological sequence of events using Autopsy’s timeline analysis.
   - Integrated memory and network events to create a unified incident timeline.

4. **Threat Intelligence Integration**
   - Used VirusTotal to validate suspicious files and hashes.
   - Mapped Indicators of Compromise (IOCs) across all evidence sources.

## Key Findings
- Malware executed from disk and maintained persistence via registry modifications.
- Memory analysis confirmed runtime behavior of malicious processes.
- Network traffic revealed active communication with external malicious hosts.
- Correlation across sources provided a complete picture of the compromise.

## Deliverables
- Unified incident timeline combining disk, memory, and network evidence.
- IOC list validated through external threat intelligence.
- Narrative reconstruction of the attack scenario for reporting.

## Academic Note
This was part of a **team project**. My contributions included:
- Correlating memory artifacts with disk evidence.
- Mapping suspicious processes to network traffic.
- Drafting the incident reconstruction and correlation section of the report.
