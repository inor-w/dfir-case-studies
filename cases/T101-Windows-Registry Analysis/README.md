# T101 - Windows Registry Analysis

## Overview

This case study focuses on analyzing Windows Registry hives to extract forensic artifacts and understand system and user activity. The registry serves as a critical source of evidence in Windows forensics, containing information about installed software, user activity, system configuration, and execution traces.

## Project Description

The investigation involved examining Windows Registry hives to answer specific investigative questions. This included analyzing both system-level and user-level registry hives to reconstruct activity, identify installed applications, track user behavior, and extract defensible artifacts that could support or refute investigative hypotheses.

## Tools Used

- **Registry Explorer** - GUI tool for navigating and analyzing registry hives
- **Python** - Custom parsing scripts for specific registry keys and analysis
- **Hash verification tools** - Ensuring evidence integrity

## Key Learnings

- **Hive Structure**: Understanding the hierarchical structure of Windows Registry hives (HKEY_LOCAL_MACHINE, HKEY_CURRENT_USER, etc.) and how they map to physical files
- **User vs System Context**: Distinguishing between system-wide and user-specific registry entries and their forensic significance
- **Artifact Extraction**: Identifying and extracting high-value forensic artifacts from registry keys such as:
  - Recently used applications
  - USB device connections
  - Network shares
  - Installed software
  - User activity timestamps
- **Defensible Methodology**: Following a structured approach to registry analysis that ensures findings are repeatable and defensible
- **Timestamp Interpretation**: Understanding how timestamps in the registry are stored and interpreted (FILETIME format, timezone considerations)
- **Correlation**: Learning to correlate registry artifacts with other evidence sources for a complete picture

## Skills Demonstrated

- Hive interpretation and navigation
- User/system context differentiation
- Defensible artifact extraction
- Evidence preservation and integrity verification
- Technical documentation and reporting

## Related Files

- `wang-25-T101-Windows-Registry-Analysis.pdf` - Full case study report

