# VFD Threat Analysis and Resilience Assessment

[![BSI TR-03183-1](https://img.shields.io/badge/Standard-BSI%20TR--03183--1-blue)](https://www.bsi.bund.de/) 
[![MITRE ATT&CK for ICS](https://img.shields.io/badge/Framework-MITRE%20ATT%26CK%20ICS-red)](https://attack.mitre.org/techniques/ics/)
[![EU CRA](https://img.shields.io/badge/Regulation-EU%20Cyber%20Resilience%20Act-green)](https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act)
[![IEC 62443](https://img.shields.io/badge/Standard-IEC%2062443-blueviolet)](https://www.iec.ch/webstore/publication/30126)

## Project Overview

This repository contains a comprehensive **Threat Analysis and Risk Assessment (TARA)** of Variable Frequency Drive (VFD) systems in industrial environments, with a focus on regulatory compliance and practical cyber resilience. The analysis applies the BSI TR-03183-1 Cyber Resilience Requirements framework (draft v0.9.0) to a VFD system in a controlled industrial test environment, ensuring alignment with the EU Cyber Resilience Act and industry-standard security practices.

**Application Project** — UM6P College of Computing, Morocco

## Key Objectives

1. **Threat Identification & Analysis**  
   Map attack vectors against VFD systems using MITRE ATT&CK for ICS taxonomy

2. **Risk Prioritization**  
   Apply ICS-specific impact hierarchy (Safety → Availability → Integrity → Confidentiality) to prioritize vulnerabilities

3. **Regulatory Compliance Assessment**  
   Validate design against BSI TR-03183-1, ETSI EN 303 645, and IEC 62443 requirements

4. **Defense Architecture Design**  
   Develop and document a defense-in-depth strategy aligned with EU CRA Annex I & II expectations

5. **Interactive Risk Communication**  
   Provide visual, interactive artifacts for stakeholder understanding across technical and non-technical audiences

## Methodology

### Threat Analysis Framework
- **Threat Enumeration**: Catalog known attack techniques from MITRE ATT&CK for ICS, adapted to VFD operational context
- **Impact Assessment**: Evaluate consequences using ICS impact dimensions (safety criticality, availability, integrity, confidentiality)
- **Risk Prioritization**: Rank threats by likelihood and impact severity
- **Mitigation Mapping**: Link each threat to applicable security controls from regulatory standards

### Standards & Requirements Alignment
The analysis cross-references multiple frameworks to ensure holistic coverage:
- **BSI TR-03183-1**: Cyber Resilience Requirements structure and control families
- **IEC 62443**: Secure product development and industrial automation security zones
- **ETSI EN 303 645**: Cybersecurity objectives and baseline requirements for connected devices
- **EU Cyber Resilience Act (CRA)**: Regulatory obligations for high-risk IoT/OT products

## Repository Structure

### `artifacts/`
Interactive, browser-based visualizations and analysis tools:
- **Threat Visualization**: Interactive dashboard mapping attack techniques to VFD components and defensive mitigations
- **Attack Scenario Simulator**: Step-through scenarios showing threat progression and detection opportunities
- **Defense Layers Explorer**: Interactive breakdown of defense-in-depth architecture with control mappings

### `diagrams/`
Static diagrams and architecture illustrations:
- **Compliance Hierarchy**: Visual relationship between regulatory frameworks and control families
- **VFD System Architecture**: Functional and network topology diagrams showing attack surfaces
- **Threat-Impact Matrices**: Heatmaps correlating threat types with impact severity
- **Defense-in-Depth Layers**: Multi-layer defensive architecture aligned with standards

### `methodology/`
Detailed documentation of analysis approach:
- **Threat Categorization & Mapping**: Structured taxonomy linking attack techniques to asset types and impact categories
- **Analysis Rationale**: Justification for scope, framework selection, and prioritization decisions
- **Control-Threat Correlation**: How specific controls address identified threats

## Standards & Frameworks

| Framework | Purpose | Coverage |
|-----------|---------|----------|
| **BSI TR-03183-1** | Cyber Resilience Requirements (draft v0.9.0) | Systematic requirements for resilient product design |
| **MITRE ATT&CK for ICS** | Industrial attack technique taxonomy | Threat enumeration and realistic attack patterns |
| **IEC 62443** | Industrial automation security (zones, conduits, controls) | Secure architecture principles |
| **ETSI EN 303 645** | Cybersecurity for consumer IoT devices | Baseline controls and security objectives |
| **EU Cyber Resilience Act (Annex I & II)** | Product security & resilience obligations | Regulatory requirements for high-risk products |

## Interactive Artifacts

All interactive visualizations are self-contained HTML files. Open in any modern web browser to explore:

- **Threat Landscape Visualization**: Explore attack techniques, attack patterns, and defensive controls in an interactive knowledge graph
- **Attack Scenario Walkthroughs**: Trace realistic attack chains step-by-step with detection and mitigation points
- **Compliance Mapping Tool**: Verify which standards address specific control requirements

*No external dependencies or server required.*

## Getting Started

1. **Review Static Diagrams**  
   Start with diagrams in `diagrams/` for a high-level understanding of the system architecture and threat landscape

2. **Explore Interactive Artifacts**  
   Open `.html` files in `artifacts/` in your web browser for interactive threat analysis and scenario exploration

3. **Dive Into Methodology**  
   Read detailed analysis documentation in `methodology/` to understand threat categorization and control rationale

## Regulatory Alignment

This analysis demonstrates alignment with:
- ✅ **EU Cyber Resilience Act** Annex I & II (product security requirements)
- ✅ **BSI TR-03183-1** resilience control families
- ✅ **IEC 62443** secure architecture principles
- ✅ **ETSI EN 303 645** cybersecurity objectives

## How to Use This Repository

**For Industry Practitioners:**  
Use the threat visualization to understand VFD attack vectors in your environment. Reference the defense layers for design considerations in new systems. Apply the compliance mapping to demonstrate regulatory alignment in documentation.

**For Security Researchers:**  
Examine the threat-impact prioritization methodology for ICS contexts. Reference the control-threat mappings for academic or assessment work. Explore the defense architecture for insights into industrial defense-in-depth patterns.

**For Regulators & Auditors:**  
Verify control coverage against BSI TR-03183-1 and CRA requirements. Use the compliance hierarchy to understand framework relationships. Reference the risk prioritization approach for guidance on ICS-specific impact assessment.

## Contributing

This is a semester project repository. Contributions, feedback, and corrections are welcome via GitHub issues and pull requests.

## Team & Supervision

**Institution**: UM6P College of Computing, Morocco  
**University Supervisor**: Sadek Belamfedel Alaoui  
**Company Supervisor**: Yassine El Moutaouaffik  
**Semester**: Spring 2025–2026

---

**Last Updated**: April 2026
