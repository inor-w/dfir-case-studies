# T111 - Forensic Countermeasures

## Overview

This case study examines anti-forensics techniques and countermeasures used to evade detection or hide evidence. Understanding these techniques is crucial for digital forensics examiners to recognize when they're being used and to develop methods to overcome them.

## Project Description

The investigation involved identifying and analyzing various anti-forensics techniques, including data hiding, encryption, obfuscation, and artifact manipulation. The case focused on recognizing these techniques, understanding how they work, and developing methods to detect or recover evidence despite their use.

## Tools Used

- **Autopsy** - Digital forensics platform for static disk analysis
- **FTK Imager** - Disk imaging and analysis tool
- **CyberChef** - Data decoding and transformation tool
- **Hashcat** - Password recovery and hash cracking tool
- **Dominic Breuker's Stego-Toolkit** - Steganography detection and extraction
- **foremost** - File carving tool for recovering deleted files
- **Hide'N'Seek** - Tool for finding hidden data
- **Python** - Custom scripts for analysis and decoding

## Key Learnings

- **Anti-Forensics Recognition**: Learning to identify common anti-forensics techniques:
  - File deletion and secure deletion
  - Timestamp manipulation
  - Data hiding and steganography
  - Encryption and password protection
  - Obfuscation and encoding
- **Decoding/Carving Mindset**: Developing the analytical mindset to:
  - Look beyond obvious artifacts
  - Consider where data might be hidden
  - Use carving techniques to recover deleted data
  - Decode obfuscated content
- **Container Inspection**: Understanding how to analyze:
  - Encrypted containers (VeraCrypt, BitLocker, etc.)
  - Password-protected archives
  - Nested containers
  - Hidden volumes
- **Artifact Manipulation Detection**: Recognizing when artifacts have been:
  - Modified or deleted
  - Timestamps altered
  - Metadata scrubbed
- **Recovery Techniques**: Learning methods to recover evidence despite countermeasures:
  - Unallocated space analysis
  - Memory analysis
  - Shadow copy analysis
  - Registry analysis
- **Pattern Recognition**: Identifying patterns that indicate anti-forensics activity:
  - Anomalies in timelines
  - Missing expected artifacts
  - Unusual file system activity
- **Limitations and Workarounds**: Understanding the limitations of anti-forensics techniques and potential workarounds

## Skills Demonstrated

- Anti-forensics recognition
- Decoding and carving techniques
- Container inspection and analysis
- Anomaly detection
- Evidence recovery despite countermeasures

## Related Files

- `wang-25-T111-Forensic-Countermeasures.pdf` - Full case study report

