# 🛡️ Design History File (DHF) Architecture Template

### Aligned with FDA 21 CFR Part 820 (QSR) & ISO 13485:2016

**Program Owner:** Joseph T. Roszhart, PMP, PSM II | **Objective:** Establish an auditable DHF index structure that directly links to project planning and change management workflows.

## 1. Project Planning & Governance (PMO Phase)

*This section confirms adherence to PMP principles (charter, scope, stakeholders) and establishes the agile/waterfall framework (PSM II).*

| DHF Document Control (DHF-XX) | Description | Governance Link | Change Control Owner |
| :---: | :--- | :--- | :--- |
| **DHF-1.0** | **Design & Development Plan (DDP)** - Establishes the project scope, phases (Sprints/Phases), team roles, and required design reviews. | PMP Project Charter & Scope Statement | Program Manager (Joseph R.) |
| **DHF-1.1** | **Project Risk Management Plan** - Defines the process for identifying, assessing, and mitigating product and process risks (ISO 14971 aligned). | Risk Register Management (PMBOK/Agile) | Quality/Risk Manager |
| **DHF-1.2** | **Design Review Schedule** - Includes required phase gate reviews (e.g., SDR, CDR, PDR) and required participant sign-offs. | PSM II Sprint/Increment Reviews | Program Manager / Scrum Master |
| **DHF-1.3** | **Software Version & Build History** (if applicable) - Links to the official configuration management system (e.g., Windchill or Jira versions). | Change Control Board (CCB) Log | IT/Software Lead |

## 2. Design Inputs (Requirements Definition)

*This section captures the "Voice of the Customer" and technical requirements, demonstrating discipline in requirements management—a critical PM skill.*

| DHF Document Control (DHF-2.X) | Description | Regulatory Link (21 CFR 820.30) | Verification Link |
| :---: | :--- | :---: | :---: |
| **DHF-2.1** | **User Needs Specification (UNS)** - Defines the high-level needs and intended use of the device, written from the user's perspective. | **Design Input** | Links to **Design Outputs** |
| **DHF-2.2** | **Requirements Specification (RS)** - Translated UNS into measurable, unambiguous, and verifiable system requirements (e.g., functional, performance, safety). | **Traceability Matrix** | Links to **DHF-4.X (V&V)** |
| **DHF-2.3** | **Regulatory Strategy/Checklist** - Documentation outlining required submissions (510(k), PMA, CE Mark) and adherence to essential ISO standards. | **Regulatory Affairs** | Links to **DHF-5.1 (Submission)** |

## 3. Design Outputs (Design Specifications)

*This section includes the technical documentation and specifications that are generated to meet the Design Inputs.*

| DHF Document Control (DHF-3.X) | Description | Storage System (Example) |
| :---: | :--- | :---: |
| **DHF-3.1** | **Device Master Record (DMR)** - Index of all documents needed for manufacturing (e.g., component specs, drawings, procedures). | **PTC Windchill PLM** |
| **DHF-3.2** | **Acceptance Criteria Documentation** - Specifications for inspection, testing, and quality acceptance of the final product and components. | **LIMS/MES System** |
| **DHF-3.3** | **Labeling & Instructions For Use (IFU)** - Controlled version of all labeling, packaging, and user manuals (Crucial for Abbott/Medtronic). | **SharePoint / Document Control** |

## 4. Design Verification & Validation (V&V)

*This section proves the design works as intended (Verification) and meets user needs (Validation).*

| DHF Document Control (DHF-4.X) | Description | Phase/Type | Status Tracking (Issues/PRs) |
| :---: | :--- | :---: | :---: |
| **DHF-4.1** | **Verification Test Protocols & Reports** - Proof that Design Outputs
