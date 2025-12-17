# T102 - Microsoft Link File and Jump List Analysis

## Overview

This case study examines Windows Link Files (.lnk) and Jump Lists to reconstruct file access and program execution activity. These artifacts provide valuable evidence of user interactions with files and applications, even when the original files may no longer exist.

## Project Description

The investigation involved analyzing Windows Link Files and Jump Lists to determine what files were accessed, when they were accessed, and what applications were used. This analysis helps reconstruct user activity and provides evidence of program execution and file manipulation.

## Tools Used

- **LECmd (LogFile Parser)** - Eric Zimmerman's tool for parsing Link Files (.lnk)
- **JumpList Explorer/Parser** - Tools for analyzing Jump List artifacts
- **FTK Imager** - File system analysis and artifact extraction
- **file** - File type identification

## Key Learnings

- **Link File Structure**: Understanding the binary structure of .lnk files and the wealth of metadata they contain:
  - Target file paths (local and network)
  - Volume information
  - MAC times (Modified, Accessed, Created)
  - File size
  - Network share information
- **Jump List Analysis**: Learning how Jump Lists track:
  - Recently opened files
  - Frequently accessed items
  - Taskbar pinning activity
  - Application usage patterns
- **Execution Evidence**: Using Link Files and Jump Lists as evidence of program execution, even when executables are deleted
- **File Access Reconstruction**: Reconstructing a timeline of file access and application usage from these artifacts
- **Network Share Tracking**: Identifying network share access through Link File metadata
- **Artifact Persistence**: Understanding where these artifacts are stored and how long they persist on the system

## Skills Demonstrated

- Evidence of execution identification
- File access reconstruction
- Timeline correlation
- Binary artifact parsing
- Metadata extraction and interpretation

## Related Files

- `wang-25-T102-Microsoft-Link-File-and-Jumplist-Analysis.pdf` - Full case study report

