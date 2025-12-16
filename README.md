# Investigating Suspicious PowerShell Scrip Execution
Cybersecurity analyst investigation of suspicious PowerShell script execution detected via Suricata alerts. Includes log analysis, IOC extraction, threat-intel validation, and incident response recommendations based on outbound PowerShell and Python activity.
# Scenario
A SIEM alert triggered on PowerShell executing outbound HTTP requests to previously unseen domains.
Suricata logs were reviewed to identify payload downloads, malicious indicators, and determine whether containment was required.
# Objective
- Identify outbound activity from powershell.exe and python.exe
- Confirm script or executable downloads
- Extract and validate IOCs
- Recommend containment actions
# Tools Used
- Splunk (log analysis)
- Suricata alerts (JSON)
- Threat intelligence (VirusTotal, AbuseIPDB, ThreatFox)
# Skills Demonstrated
- Log triage
- IOC extraction
- Threat validation
- Incident documentation
- SOC-style reporting
