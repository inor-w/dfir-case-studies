# T103 - Microsoft IIS Web Log Analysis

## Overview

This case study focuses on analyzing Internet Information Services (IIS) web server logs to identify suspicious activity, understand web traffic patterns, and investigate potential security incidents. Web logs are a critical source of evidence for understanding what happened on a web server.

## Project Description

The investigation involved parsing and analyzing IIS web server logs to identify suspicious requests, understand attack patterns, correlate events, and answer specific investigative questions about web server activity. This included handling various log formats and understanding timestamp semantics.

## Tools Used

- **Log Parser** - Microsoft Log Parser for querying IIS logs
- **Log Parser Studio** - GUI tool for log analysis
- **Python scripts** - Custom parsing and analysis scripts
- **Excel/Pandas** - Data analysis and filtering
- **Regular expressions** - Pattern matching for suspicious requests
- **Timeline tools** - Correlating log entries with other evidence

## Key Learnings

- **IIS Log Format**: Understanding the structure of IIS log files (W3C Extended Log Format) and the fields they contain:
  - Client IP addresses
  - Request methods (GET, POST, etc.)
  - Requested URLs and query strings
  - HTTP status codes
  - User agents
  - Timestamps
- **Suspicious Request Identification**: Learning to identify patterns indicative of:
  - SQL injection attempts
  - Directory traversal attacks
  - Unusual user agents
  - Failed authentication attempts
  - Unusual access patterns
- **Timestamp Handling**: Understanding how timestamps are stored in IIS logs (UTC vs local time) and properly converting them for analysis
- **Log Parsing Techniques**: Using various methods to parse and query large log files efficiently
- **Correlation**: Correlating web log entries with other evidence sources to build a complete picture
- **Attack Pattern Recognition**: Identifying common web attack patterns and their signatures in logs

## Skills Demonstrated

- Web log parsing and analysis
- Suspicious request identification
- Timestamp handling and conversion
- Pattern recognition and attack identification
- Data correlation and timeline construction

## Related Files

- `wang-25-T103-Microsoft-IIS-Web-Log-Analysis.pdf` - Full case study report

