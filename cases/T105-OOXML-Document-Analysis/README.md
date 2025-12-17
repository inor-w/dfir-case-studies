# T105 - OOXML Document Analysis

## Overview

This case study focuses on analyzing Office Open XML (OOXML) documents (Microsoft Office files with .docx, .xlsx, .pptx extensions) to extract metadata, identify embedded content, and analyze document properties. OOXML documents contain a wealth of forensic information that can reveal document history, authorship, and embedded artifacts.

## Project Description

The investigation involved examining OOXML document structures to extract metadata, identify embedded files and objects, analyze document properties, and handle protected documents. This analysis helps understand document provenance, identify authors, and discover hidden content.

## Tools Used

- **oletools** - Python tools for analyzing OLE and OOXML files
- **python-docx** - Python library for parsing .docx files
- **7-Zip/Archive tools** - Extracting OOXML container contents
- **XML parsers** - Parsing OOXML internal XML structures
- **Metadata extraction tools** - Extracting document properties
- **Hex editors** - Low-level analysis of document structures

## Key Learnings

- **OOXML Structure**: Understanding that OOXML files are ZIP archives containing:
  - XML files with document content
  - Relationships files
  - Metadata files
  - Embedded objects and media
- **Metadata Extraction**: Learning to extract and interpret:
  - Document properties (author, creation date, modification date)
  - Application information
  - Revision history
  - Custom properties
- **Embedded Content Mapping**: Identifying and extracting:
  - Embedded images and media
  - Embedded OLE objects
  - Hyperlinks
  - Macros (if present)
- **Protected Documents Handling**: Understanding how to analyze password-protected or encrypted documents
- **Document History**: Recovering document revision history and tracking changes
- **Hidden Content**: Identifying hidden text, comments, and tracked changes
- **Artifact Correlation**: Correlating document metadata with other forensic artifacts

## Skills Demonstrated

- Metadata extraction and interpretation
- Embedded content mapping
- Protected document handling
- XML structure analysis
- Document provenance analysis

## Related Files

- `wang-25-T105-OOXML-Document-Analysis.pdf` - Full case study report

