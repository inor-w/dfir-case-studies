# T104 - Volume Shadow Copy Analysis

## Overview

This case study examines Windows Volume Shadow Copies (VSS) to identify file changes over time, recover deleted or modified files, and understand system state at different points in time. Volume Shadow Copies provide snapshots of the file system that can be invaluable for forensic investigations.

## Project Description

The investigation involved accessing and analyzing Volume Shadow Copies to compare file system states, identify when files were created, modified, or deleted, and recover previous versions of files. This analysis helps establish timelines of file changes and can reveal evidence that no longer exists in the current file system state.

## Tools Used

- **VSSAdmin** - Windows command-line tool for managing Volume Shadow Copies
- **vss-carve** - Tool for extracting files from shadow copies
- **FTK Imager** - Mounting and examining shadow copies
- **Autopsy** - File system analysis with shadow copy support
- **File comparison tools** - Comparing file versions across snapshots
- **NTFS analysis tools** - Understanding NTFS structures

## Key Learnings

- **Volume Shadow Copy Technology**: Understanding how Windows creates and manages shadow copies:
  - When shadow copies are created
  - How they're stored
  - Retention policies
  - Access methods
- **Snapshot Comparison**: Learning to compare file system states across different shadow copy snapshots to identify:
  - Files that were deleted
  - Files that were modified
  - Files that were created
  - Timestamp changes
- **File-Change Validation**: Verifying file changes by comparing multiple snapshots and establishing reliable timelines
- **NTFS-Level Reasoning**: Understanding NTFS file system structures and how shadow copies interact with them
- **Recovery Techniques**: Extracting previous versions of files from shadow copies
- **Timeline Construction**: Using shadow copy timestamps to build accurate timelines of file system changes
- **Limitations**: Understanding when shadow copies may not be available or may have been disabled

## Skills Demonstrated

- Snapshot comparison and analysis
- File-change validation
- NTFS-level reasoning
- Timeline construction from file system artifacts
- Evidence recovery from shadow copies

## Related Files

- `wang-25-T104-Volume-Shadow-Copy-Analysis.pdf` - Full case study report

