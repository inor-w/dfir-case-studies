# T110 - Threat Hunting with Velociraptor

## Overview

This case study demonstrates threat hunting using Velociraptor, an endpoint visibility and response tool. Threat hunting involves proactively searching for threats and suspicious activity on endpoints, rather than waiting for alerts from security tools.

The investigation involved using Velociraptor, Autopsy, and supporting tools to perform endpoint triage and limited static analysis of a Windows Server 2022 Datacenter host identified as acme-blg2-ysam. The focus was to document core system configuration, identify the interactive user and active applications, correlate Windows Event Logs with PowerShell execution, and perform threat hunting to identify suspicious activity.

## Tools Used

- **Velociraptor** - Endpoint visibility and response platform for threat hunting
- **Velociraptor VQL (Velociraptor Query Language)** - Query language for artifact collection
- **Autopsy** - Static disk analysis and artifact extraction
- **CyberChef** - Data decoding and transformation
- **ClamAV** - Antivirus scanning of collected artifacts
- **file** - File type identification

## Key Learnings

- **Threat Hunting Methodology**: Understanding the proactive approach to security:
  - Hypothesis-driven hunting
  - Indicator-based hunting
  - Anomaly detection
- **Velociraptor Architecture**: Learning how Velociraptor works:
  - Client-server model
  - VQL query language
  - Artifact system
  - Collection and analysis workflow
- **Endpoint Hunts**: Performing hunts for:
  - Specific malware indicators
  - Suspicious process activity
  - Unusual network connections
  - File system anomalies
- **PowerShell/Log Correlation**: Understanding how to:
  - Analyze PowerShell execution logs
  - Correlate PowerShell activity with other logs
  - Identify suspicious script execution
  - Detect obfuscation and evasion techniques
- **Detection Reasoning**: Learning to:
  - Build evidence-based detections
  - Support findings with multiple data sources
  - Distinguish between benign and malicious activity
  - Create defensible detection logic
- **Artifact Collection**: Using Velociraptor to collect:
  - Process information
  - Network connections
  - File system artifacts
  - Registry data
  - Event logs
- **Response Capabilities**: Understanding how to use collected data for incident response

## Skills Demonstrated

- Endpoint hunting techniques
- PowerShell and log correlation
- Detection reasoning and evidence-based analysis
- VQL query development
- Threat identification and validation

## Related Files

- `wang-25-T110-Threat-Hunting-w-Velociraptor.pdf` - Full case study report

