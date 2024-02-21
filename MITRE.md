## MITRE ATT&CK Framework Overview

### Purpose:
The MITRE ATT&CK framework is a knowledge base of tactics and techniques designed for threat hunters, defenders, and red teams to classify attacks, identify attack attribution, assess an organization's risk, and prioritize mitigations based on risk.

### History:
- MITRE initiated the ATT&CK framework project in 2013 to document tactics, techniques, and procedures (TTPs) used by advanced persistent threat (APT) groups.
- It evolved from the FMX research project aimed at improving post-intrusion detection within enterprise networks.
- Originally focused on Windows systems, it now covers various platforms like Linux, macOS, mobile, cloud, network, containers, and industrial control systems (ICS).

### MITRE Engenuity:
- MITRE Engenuity collaborates with private companies to evaluate cybersecurity products using the ATT&CK framework.
- The evaluations help vendors enhance their products and improve defense strategies.

### ATT&CK Matrix:
- Organized into matrices, each focusing on a specific domain like enterprise, mobile, or cloud.
- Categorizes tactics (the "why" of an attack) and techniques (the "how" of an attack) used by adversaries.

### Tactics and Techniques:
- Tactics represent the goals or objectives of attackers, while techniques describe how those objectives are achieved.
- The Enterprise ATT&CK Matrix consists of 14 tactics encompassing various techniques and subtechniques

## DeTT&CT: DEtect Tactics, Techniques & Combat Threats

### Introduction:
DeTT&CT is a cybersecurity framework developed at the Cyber Defence Centre of Rabobank, built atop of MITRE ATT&CK. It aims to assist blue teams in scoring and comparing data log source quality, visibility coverage, detection coverage, and threat actor behaviors to enhance resilience against cyber attacks.

### Features:
- Provides a framework for scoring and comparing data log source quality, visibility coverage, detection coverage, and threat actor behaviors.
- Built upon the MITRE ATT&CK framework, leveraging its taxonomy of tactics, techniques, and procedures (TTPs).
- Enables detailed administration of data sources, visibility, detection, and threat intelligence within an organization.
- Facilitates the identification of gaps and prioritization of defense efforts based on visibility, detection coverage, and threat actor behaviors.

### Components:
1. **ATT&CK Matrix Integration**:
   - Utilizes the MITRE ATT&CK Matrix for visualization and analysis of tactics, techniques, and procedures (TTPs) used by adversaries.
   - Allows mapping of organization-specific data sources, visibility, and detection coverage to the ATT&CK Matrix.

2. **Data Sources Administration**:
   - Provides functionality for inventorying and assessing data log sources based on their quality and usability for data analytics.
   - Supports administration of data sources using a dedicated YAML file format.

3. **Visibility Assessment**:
   - Helps organizations identify areas lacking visibility by mapping data sources to ATT&CK techniques.
   - Facilitates visualization of potential visibility coverage based on mapped data sources.

4. **Detection Scoring**:
   - Enables manual scoring and visualization of detection capabilities for each technique within the ATT&CK Matrix.
   - Allows comparison of detection scores to identify gaps and prioritize defense efforts.

5. **Threat Actor Groups Analysis**:
   - Allows analysis and comparison of threat actor groups based on their usage of ATT&CK techniques.
   - Facilitates visualization of threat actor capabilities and techniques used across different groups.

6. **Gap Identification and Prioritization**:
   - Enables organizations to identify gaps and prioritize defense efforts based on visibility, detection coverage, and threat intelligence.
   - Supports comparison of threat intelligence with current detection and visibility status to uncover areas for improvement.

### Usage:
- Detailed information and usage instructions are documented on the [GitHub Wiki pages](https://github.com/rabobank-cdc/DeTTECT/wiki).


## Caldera

### Introduction
- Caldera helps cybersecurity professionals reduce the amount of time and resources needed for routine cybersecurity testing.
