# T109 - Static Analysis with Autopsy

## Overview

This case study demonstrates disk image analysis using Autopsy, a digital forensics platform. Autopsy provides a comprehensive suite of tools for analyzing file systems, extracting artifacts, and conducting investigations on disk images.

## Project Description

The investigation involved using Autopsy, VeraCrypt, and supporting tools to perform static disk analysis of a Windows 10 Pro workstation used by the account "AntiRenzik." The focus was to document system configuration, identify installed and executed programs (especially VeraCrypt), review USB and web activity tied to ransom planning and related activities. The analysis used Autopsy for comprehensive file system review and artifact extraction.

## Tools Used

- **Autopsy** - Digital forensics platform for static disk analysis
- **VeraCrypt** - Analysis of encrypted container usage
- **Plaso (log2timeline)** - Timeline creation from file system artifacts
- **ClamAV** - Antivirus scanning of suspicious files
- **file** - File type identification

## Key Learnings

- **File System Review**: Understanding how to systematically review file systems:
  - Directory structure analysis
  - File type identification
  - Deleted file recovery
  - Unallocated space analysis
- **Artifact Extraction**: Learning to extract and analyze:
  - Windows artifacts (registry, event logs, etc.)
  - Browser artifacts
  - Email artifacts
  - Application-specific artifacts
- **Investigative Pivoting**: Understanding how to:
  - Follow leads from one artifact to another
  - Correlate findings across different sources
  - Build a comprehensive picture from multiple artifacts
- **Keyword Searching**: Using keyword searches effectively:
  - Identifying relevant search terms
  - Understanding search limitations
  - Interpreting search results
- **Hash Analysis**: Using hash databases to:
  - Identify known files
  - Filter out common system files
  - Focus on unique or suspicious files
- **Timeline Integration**: Using Autopsy's timeline features to understand file system activity
- **Report Generation**: Creating comprehensive reports from Autopsy analysis

## Skills Demonstrated

- File system review and analysis
- Artifact extraction and interpretation
- Investigative pivoting
- Systematic investigation methodology
- Evidence correlation

## Related Files

- `wang-25-T109-Static-Analysis-w-Autopsy.pdf` - Full case study report

