# DFIR Case Studies

A curated collection of sanitized DFIR case studies and lab writeups by the examiner, showcasing memory + disk forensics workflows (Volatility 3, Autopsy), Windows artifact analysis, timelines, and professional reporting—no evidence images, malware samples, or sensitive identifiers included.

## Table of Contents

- [Overview](#overview)
- [Case Studies](#case-studies)
- [Key Features](#key-features)
- [Tools Used Across Cases](#tools-used-across-cases)
- [Best Entry Points](#best-entry-points)
- [Methodology](#methodology)
- [Course Context](#course-context)
- [Learning Outcomes](#learning-outcomes)
- [Disclaimer](#disclaimer)

> 💡 **Quick Start**: For a 60-second overview, see [QUICK-READ.md](QUICK-READ.md)

## Overview

This repository contains 12 comprehensive case studies completed as part of **IS 4523 — Digital Forensic Analysis II (Fall 2025)**, demonstrating advanced DFIR techniques including Windows artifacts, timeline analysis, memory forensics, malware triage, and professional reporting.

## Case Studies

Each case study includes a detailed PDF report and a comprehensive README with:
- **Overview** - Context and purpose of the investigation
- **Project Description** - Specific objectives and scope
- **Tools Used** - Exact tools and versions utilized
- **Key Learnings** - Concepts and techniques learned
- **Skills Demonstrated** - Competencies showcased
- **Related Files** - Links to the full PDF report

| Case | Topic | Skills Demonstrated | README |
|------|-------|---------------------|--------|
| [T101](cases/T101-Windows-Registry%20Analysis/) | Windows Registry Analysis | Hive interpretation, user/system context, defensible artifact extraction | [README](cases/T101-Windows-Registry%20Analysis/README.md) |
| [T102](cases/T102-Microsoft-Link-File-and-Jumplist-Analysis/) | Link Files & Jump Lists | Evidence of execution & file access reconstruction | [README](cases/T102-Microsoft-Link-File-and-Jumplist-Analysis/README.md) |
| [T103](cases/T103-Microsoft-IIS-Web-Log-Analysis/) | IIS Web Log Analysis | Web log parsing, suspicious request identification, timestamp handling | [README](cases/T103-Microsoft-IIS-Web-Log-Analysis/README.md) |
| [T104](cases/T104-Volume-Shadow-Copy-Analysis/) | Volume Shadow Copy Analysis | Snapshot comparison, file-change validation, NTFS-level reasoning | [README](cases/T104-Volume-Shadow-Copy-Analysis/README.md) |
| [T105](cases/T105-OOXML-Document-Analysis/) | OOXML Document Analysis | Metadata extraction, embedded content mapping, protected docs handling | [README](cases/T105-OOXML-Document-Analysis/README.md) |
| [T106](cases/T106-Triage-Capture-with-KAPE/) | Triage Collection w/ KAPE | Rapid acquisition of high-value artifacts, collection validation | [README](cases/T106-Triage-Capture-with-KAPE/README.md) |
| [T107](cases/T107-Forensic-Timeline-Analysis-w-Timesketch/) | Forensic Timeline w/ Timesketch | Timeline creation, cross-artifact correlation, hypothesis testing | [README](cases/T107-Forensic-Timeline-Analysis-w-Timesketch/README.md) |
| [T108](cases/T108-Memory-Analysis-w-Volatility3/) | Memory Analysis w/ Volatility 3 | Process/network analysis, injection triage, short-lived process reasoning | [README](cases/T108-Memory-Analysis-w-Volatility3/README.md) |
| [T109](cases/T109-Static-Analysis-w-Autopsy/) | Static Analysis w/ Autopsy | File system review, artifact extraction, investigative pivoting | [README](cases/T109-Static-Analysis-w-Autopsy/README.md) |
| [T110](cases/T110-Threat-Hunting-w-Velociraptor/) | Threat Hunting w/ Velociraptor | Endpoint hunts, PowerShell/log correlation, detection reasoning | [README](cases/T110-Threat-Hunting-w-Velociraptor/README.md) |
| [T111](cases/T111-Forensic-Countermeasures/) | Forensic Countermeasures | Anti-forensics recognition, decoding/carving mindset, container inspection | [README](cases/T111-Forensic-Countermeasures/README.md) |
| [T112](cases/T112-Capstone/) | Capstone | Integrated memory + disk DFIR, encryption handling, suspicious file analysis | [README](cases/T112-Capstone/README.md) |

## Key Features

- **Comprehensive Coverage**: Windows artifacts, memory forensics, timeline analysis, threat hunting, and anti-forensics detection
- **Professional Methodology**: Structured, defensible workflow following forensic best practices
- **Tool Diversity**: Experience with 20+ forensic tools including Volatility 3, Autopsy, KAPE, Timesketch, Velociraptor, and specialized analysis tools
- **Evidence-Based Analysis**: All conclusions supported by artifacts, not conjecture
- **Sanitized Content**: No sensitive data, evidence images, or malware samples included

## Tools Used Across Cases

This repository demonstrates proficiency with a wide range of digital forensics and incident response tools:

**Memory Forensics:**
- Volatility 3, file, ClamAV, FLOSS, capa

**Disk & File System Analysis:**
- Autopsy, FTK Imager, Arsenal Image Mounter, VeraCrypt

**Artifact Collection & Triage:**
- KAPE (Kroll Artifact Parser and Extractor), !SANS_Triage targets

**Timeline Analysis:**
- Timesketch, Plaso (log2timeline), Hayabusa

**Windows Artifact Analysis:**
- Registry Explorer, LECmd, JumpList Explorer, RegRipper

**Threat Hunting:**
- Velociraptor, VQL (Velociraptor Query Language)

**Anti-Forensics & Decoding:**
- CyberChef, Hashcat, Stego-Toolkit, foremost, Hide'N'Seek

**Log Analysis:**
- Log Parser, Log Parser Studio

**Document Analysis:**
- oletools, python-docx, 7-Zip

**Volume Shadow Copy:**
- VSSAdmin, vss-carve

## Best Entry Points

If time is limited, start with:
- **Capstone (T112)** — End-to-end investigation with memory + disk analysis
- **Memory Analysis (T108)** — Volatility 3 workflow + process/network triage
- **Threat Hunting (T110)** — Endpoint hunting + evidence-backed reasoning

## Methodology

All case studies follow a consistent, defensible workflow:

1. **Define scope and questions** - Translate investigative questions into testable claims
2. **Preserve integrity** - Verify hashes, work from copies, record tool versions
3. **Acquire or triage evidence** - Collect high-value artifacts first, validate results
4. **Analyze using multiple sources** - Corroborate evidence, separate observation from inference
5. **Document and communicate** - Capture supporting evidence, write concise findings

See [METHODOLOGY.md](METHODOLOGY.md) for more details.

## Course Context

- **Course**: IS 4523 — Digital Forensic Analysis II (Fall 2025)
- **Modality**: In-person
- **Focus**: Advanced DFIR topics including Windows artifacts, timeline analysis, memory forensics, malware triage, and reporting
- **Final Grade**: A+

## Learning Outcomes

Across these writeups, the examiner demonstrated the ability to:
- Preserve and handle digital evidence using forensic best practices
- Identify sources of evidence on Windows systems
- Process and analyze artifacts to answer scoped investigative questions
- Develop defensible forensic timelines
- Support conclusions using facts from artifacts (not conjecture)
- Produce technical reports using a structured template

## Disclaimer

This repository contains **sanitized DFIR case studies and lab writeups** created for educational/portfolio purposes. All content is provided for learning and professional demonstration. It does not include original evidence images, malware samples, or any sensitive identifiers.

See [DISCLAIMER.md](DISCLAIMER.md) for full details.

## License

See [LICENSE](LICENSE) for license information.
