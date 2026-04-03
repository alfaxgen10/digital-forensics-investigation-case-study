# Case Study – Evidence Acquisition

## Objective
To acquire and preserve digital evidence from live systems, RAM, and HDD while maintaining forensic integrity and chain of custody.

## Process
1. **Live Acquisition**
   - Captured volatile data from the running system.
   - Documented system state and environment prior to acquisition.

2. **RAM Capture**
   - Used Volatility-compatible memory dump tools.
   - Ensured hash values were recorded to verify integrity.

3. **Disk Imaging**
   - Utilized FTK Imager to create a forensic image of the HDD.
   - Applied write-blocking techniques to prevent data alteration.
   - Generated MD5/SHA1 hashes for validation.

4. **Chain of Custody**
   - Recorded acquisition steps, timestamps, and responsible analyst.
   - Maintained evidence logs to ensure admissibility in a forensic context.

## Key Notes
- Evidence was preserved in a manner consistent with forensic best practices.
- Integrity checks confirmed that no data was altered during acquisition.
- Documentation ensured transparency and accountability throughout the process.

## Deliverables
- RAM dump file with verified hash values.
- HDD forensic image with integrity validation.
- Chain of custody documentation.
