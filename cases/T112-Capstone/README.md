# T112 - Capstone Investigation

## Overview

This capstone case study represents a comprehensive, end-to-end digital forensics investigation that integrates multiple analysis techniques and tools. It demonstrates the application of memory forensics, disk analysis, encryption handling, and suspicious file analysis in a real-world scenario.

## Project Description

The investigation involved conducting memory and static disk forensics on a Windows 10 virtual machine to identify user activity, encryption usage, and potential malicious intent. Volatility 3 was used to confirm the memory capture context (system time and OS major version) and to enumerate running processes, which showed Microsoft Edge, VeraCrypt, and Windows Subsystem for Linux (WSL) with a Kali Linux distribution. Autopsy was then used to analyze the primary virtual disk image to document system details, review web artifacts showing research into malware generation (Metasploit/msfvenom), and identify encryption usage.

## Tools Used

- **Volatility 3** - Memory analysis and process enumeration
- **Autopsy** - Static disk image analysis and artifact extraction
- **VeraCrypt** - Analysis of encrypted container usage
- **Hashcat** - Password recovery and hash analysis (if applicable)

## Key Learnings

- **Integrated Analysis**: Combining multiple forensic disciplines:
  - Memory forensics + disk forensics
  - Timeline analysis + artifact correlation
  - Static analysis + dynamic analysis
- **Encryption Handling**: Working with encrypted evidence:
  - Identifying encryption types
  - Attempting decryption when possible
  - Documenting encryption as evidence
  - Understanding limitations
- **Suspicious File Analysis**: Analyzing potentially malicious files:
  - Static analysis techniques
  - Behavioral analysis
  - Hash analysis
  - Reputation checking
- **Evidence Correlation**: Synthesizing evidence from multiple sources:
  - Memory artifacts + disk artifacts
  - Registry + file system + logs
  - Network activity + process activity
- **Comprehensive Reporting**: Creating a complete investigation report:
  - Executive summary
  - Methodology
  - Findings with evidence
  - Conclusions supported by facts
- **Investigation Workflow**: Following a structured approach:
  - Evidence intake and verification
  - Analysis planning
  - Systematic examination
  - Documentation throughout
- **Tool Integration**: Using multiple tools together effectively:
  - Understanding tool strengths and limitations
  - Combining tool outputs
  - Validating findings across tools

## Skills Demonstrated

- Integrated memory + disk DFIR analysis
- Encryption handling and documentation
- Suspicious file analysis
- Evidence correlation and synthesis
- Comprehensive investigation reporting
- End-to-end investigation workflow

## Related Files

- `wang-25-T112-Capstone.pdf` - Full capstone investigation report

