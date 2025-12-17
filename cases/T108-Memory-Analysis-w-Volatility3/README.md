# T108 - Memory Analysis with Volatility 3

## Overview

This case study demonstrates memory forensics using Volatility 3, the leading open-source memory analysis framework. Memory analysis is crucial for detecting malware, understanding running processes, identifying network connections, and discovering evidence that may not be present on disk.

## Project Description

The investigation involved analyzing Windows memory from CITADEL-DC01 and DESKTOP-SDN1RPT with Volatility 3, then triaging dumped regions using file, ClamAV, FLOSS, and capa. The focus was to capture image context (system time/NT version), identify short-lived processes, confirm spoolsv.exe injection, enumerate DLLs/handles/mutants, map sockets, and tie memory artifacts to a single C2. The analysis revealed brief coreupdater.exe stager processes, spoolsv.exe injection with malfind-positive VADs containing MZ headers, AV hits (Meterpreter/Razy), FLOSS extracting C2 IP addresses, and capa identifying malware capabilities.

## Tools Used

- **Volatility 3** - Memory analysis framework for Windows memory dumps
- **file** - File type identification for dumped memory regions
- **ClamAV** - Antivirus scanning of extracted memory artifacts
- **FLOSS** - String extraction and deobfuscation from memory dumps
- **capa** - Malware capability analysis framework

## Key Learnings

- **Memory Forensics Fundamentals**: Understanding:
  - How operating systems manage memory
  - Process structures in memory
  - Memory layout and organization
  - Virtual vs physical memory
- **Volatility 3 Framework**: Learning to use Volatility 3:
  - Plugin architecture
  - Profile selection
  - Command syntax
  - Output interpretation
- **Process Analysis**: Identifying and analyzing:
  - Running processes
  - Process relationships (parent/child)
  - Process command lines
  - Process memory contents
- **Network Analysis**: Extracting network information:
  - Active connections
  - Listening ports
  - Network connections by process
- **Injection Triage**: Detecting and analyzing:
  - DLL injection
  - Process hollowing
  - Reflective DLL loading
  - Other code injection techniques
- **Short-Lived Process Reasoning**: Understanding how to identify and analyze processes that:
  - Ran briefly and exited
  - May have left minimal disk artifacts
  - Are visible only in memory
- **Malware Detection**: Using memory analysis to detect:
  - Hidden processes
  - Injected code
  - Unusual network activity
  - Rootkits

## Skills Demonstrated

- Process and network analysis from memory
- Injection triage and detection
- Short-lived process reasoning
- Memory artifact extraction
- Malware detection techniques

## Related Files

- `wang-25-T108-Memory-Analysis-w-Volatility3.pdf` - Full case study report

