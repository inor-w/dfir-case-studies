# T107 - Forensic Timeline Analysis with Timesketch

## Overview

This case study demonstrates the creation and analysis of forensic timelines using Timesketch, a collaborative timeline analysis tool. Timelines are essential for understanding the sequence of events in an investigation and correlating evidence from multiple sources.

## Project Description

The investigation involved analyzing triaged Windows data from CITADEL-DC01 and DESKTOP-SDN1RPT to explain RDP, logon, and persistence activity tied to public IP 194.61.24.102 (Timesketch → Russia). Data sources were existing KAPE timelines in Timesketch, Hayabusa logonsummary-success/-failed CSVs, and Saved Searches (RDP sessions, logon events). The analysis focused on correlating timeline events to answer specific investigative questions about remote access and authentication activity.

## Tools Used

- **Timesketch** - Collaborative timeline analysis platform
- **KAPE** - Artifact collection (timelines were pre-collected using KAPE)
- **Hayabusa** - Windows Event Log analysis tool (logonsummary-success/-failed)
- **Plaso (log2timeline)** - Tool for creating super timelines from multiple sources
- **Arsenal Image Mounter** - Mounting disk images for analysis

## Key Learnings

- **Timeline Creation**: Learning to create comprehensive timelines from multiple sources:
  - File system timestamps (MACE times)
  - Registry entries
  - Event logs
  - Browser history
  - Link files
  - Prefetch files
- **Cross-Artifact Correlation**: Understanding how to correlate events from different artifact types to build a complete picture:
  - Registry changes and file system activity
  - Log entries and program execution
  - Network activity and file access
- **Hypothesis Testing**: Using timelines to test investigative hypotheses:
  - What happened and when?
  - What was the sequence of events?
  - What artifacts support or refute theories?
- **Timesketch Features**: Learning to use Timesketch for:
  - Event search and filtering
  - Tagging and labeling
  - Story creation
  - Collaboration
  - Visualization
- **Timestamp Normalization**: Handling different timestamp formats and timezones across artifacts
- **Event Significance**: Identifying which timeline events are most significant for the investigation

## Skills Demonstrated

- Timeline creation from multiple sources
- Cross-artifact correlation
- Hypothesis testing using timelines
- Collaborative analysis
- Event significance assessment

## Related Files

- `wang-25-T107-Forensic-Timeline-Analysis-w-Timesketch.pdf` - Full case study report

