# T106 - Triage Capture with KAPE

## Overview

This case study demonstrates the use of KAPE (Kroll Artifact Parser and Extractor) for rapid triage collection of high-value forensic artifacts from Windows systems. KAPE enables efficient collection of critical evidence without requiring full disk imaging, making it valuable for time-sensitive investigations.

## Project Description

The investigation involved conducting a triage acquisition and review of Windows artifacts from a domain controller (DC01) and a workstation (DESKTOP) for Case 25-T106. The objective was to rapidly preserve high-value artifacts (e.g., registry hives, Prefetch, Amcache, RecentFileCache) to support timeline reconstruction around a suspected September intrusion. Triage was performed using KAPE with the !SANS_Triage compound target; images were mounted read-only with Arsenal Image Mounter to maintain forensic soundness.

## Tools Used

- **KAPE (Kroll Artifact Parser and Extractor)** - Primary triage collection tool
- **!SANS_Triage compound target** - Pre-configured KAPE target for comprehensive artifact collection
- **Arsenal Image Mounter** - Mounting disk images read-only to maintain forensic soundness
- **Hash verification tools** - Validating collection integrity (MD5/SHA1/SHA256)

## Key Learnings

- **Triage Mindset**: Understanding when and why to use triage collection instead of full disk imaging:
  - Time-sensitive investigations
  - Limited storage resources
  - Initial assessment needs
  - Remote collection scenarios
- **KAPE Architecture**: Learning how KAPE works:
  - Targets (what to collect)
  - Modules (how to process)
  - Collection methodology
  - Output organization
- **High-Value Artifacts**: Identifying and prioritizing which artifacts to collect:
  - Registry hives
  - Event logs
  - Prefetch files
  - Link files and Jump Lists
  - Browser artifacts
  - Memory artifacts
- **Collection Validation**: Ensuring that:
  - Expected artifacts were collected
  - File counts match expectations
  - Paths are correct
  - Integrity is maintained
- **Rapid Acquisition**: Learning to balance speed with thoroughness in artifact collection
- **Evidence Handling**: Properly documenting and preserving triage collections

## Skills Demonstrated

- Rapid acquisition of high-value artifacts
- Collection validation and verification
- Triage collection methodology
- Evidence integrity preservation
- Tool configuration and execution

## Related Files

- `wang-25-T106-Triage-Capture-with-KAPE.pdf` - Full case study report

