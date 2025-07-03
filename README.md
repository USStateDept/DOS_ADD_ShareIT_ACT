# DoS - Metadata

This repository contains the consolidated metadata inventory for all Department of State (DoS) software projects, collected in compliance with federal source code policies and the [Federal Source Code Policy](https://www.congress.gov/bill/118th-congress/house-bill/9566).

## Description

This repository serves as the central metadata registry for DoS software projects, providing a comprehensive inventory of all department-developed software assets. The metadata is automatically collected and updated from individual project repositories across DoS GitLab instances.

## Contents

- `metadata.csv` - Master inventory file containing metadata for all DoS software projects

## Metadata Schema

The metadata inventory includes the following information for each software project:

| Field | Description | Purpose |
|-------|-------------|---------|
| Project_Name | Name of the software project | Project identification and cataloging |
| Description | Brief description of the project's purpose and functionality | Understanding project scope and capabilities |
| Contract_ID | Associated contract or funding identifier | Budget tracking and compliance |
| License_Information | Software license type (e.g., MIT, Apache 2.0, Public Domain) | Legal compliance and reuse guidelines |
| Link | URL to the project repository or documentation | Access and reference |
| POC | Point of Contact (name and email) | Support and collaboration |

## Data Usage

This metadata inventory supports:

### Federal Compliance
- **Source Code Inventory**: Satisfies federal requirements for maintaining software asset inventories
- **Open Source Reporting**: Tracks open source releases per OMB guidelines
- **License Compliance**: Ensures proper licensing documentation for all projects

### Internal Operations
- **Project Discovery**: Enables staff to find and leverage existing solutions
- **Resource Planning**: Supports budget and resource allocation decisions
- **Collaboration**: Facilitates cross-bureau collaboration on similar projects

### Public Transparency
- **Government Accountability**: Provides visibility into DoS software development activities
- **Reuse Opportunities**: Helps other agencies identify reusable solutions
- **Innovation Tracking**: Documents DoS contributions to open source ecosystem

## Data Updates

The metadata in this repository is automatically updated on a regular schedule through automated collection processes. Updates include:

- New project additions
- Metadata corrections and updates
- License and contact information changes
- Project status updates

**Last Updated**: [Automatically updated timestamp]

## Data Quality

### Validation
All metadata entries are validated for:
- Required field completeness
- URL accessibility and validity
- Contact information accuracy
- License compliance

### Data Sources
Metadata is collected directly from:
- Individual project `metadata.csv` files
- GitLab project settings and descriptions
- Bureau-provided project registrations

## Using This Data

### For DoS Staff
- Search the CSV file to find existing projects before starting new development
- Use contact information to collaborate with project teams
- Reference license information for reuse decisions

### For Other Federal Agencies
- Identify DoS solutions that may address similar needs
- Understand licensing terms for potential reuse
- Contact project teams for collaboration opportunities

### For the Public
- View DoS contributions to open source software
- Access publicly available DoS software projects
- Understand the scope of DoS software development activities

## Data Format

The metadata is provided in CSV format for maximum compatibility with analysis tools. To use the data:

1. Download `metadata.csv` from this repository
2. Open in spreadsheet software (Excel, Google Sheets, etc.)
3. Use built-in filtering and search capabilities
4. Import into database systems for advanced analysis

## Compliance Framework

This metadata collection supports compliance with:

- **Federal Source Code Policy** (H.R. 9566, 118th Congress)
- **OMB Memorandum M-16-21**: Federal Source Code Policy
- **DoS Information Management Directive**: Software Asset Management
- **FISMA Requirements**: Information system inventories

## Contact Information

### For Metadata Questions
- **Technical Issues**: Contact the project POC listed in individual entries
- **Process Questions**: Contact **ADD_Share_IT@state.gov** for requesting access to Software Projects/repositories.
- **Policy Questions**: [DoS Information Management contact information]

### For Data Corrections
To report incorrect or outdated metadata:
1. Contact the project POC directly (preferred)
2. Submit correction through [internal process]
3. For urgent corrections: [emergency contact information]

## Related Resources

- **DoS Software Development Guidelines**: [Internal link]
- **Federal Source Code Policy**: https://www.congress.gov/bill/118th-congress/house-bill/9566
- **OMB Source Code Guidance**: https://code.gov/
- **DoS Open Source Projects**: [Public facing portal if available]

## Repository Maintenance

This repository is maintained by the Department of State Bureau of Information Resource Management in coordination with software development teams across the department.

**Repository Type**: Metadata Registry  
**Classification**: Unclassified  
**Availability**: Internal DoS / Federal Government  
**Retention**: Permanent Record

---

*This metadata inventory is maintained in accordance with federal records management requirements and DoS information governance policies.*