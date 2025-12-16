# Requirements Management Plan (RMP)

**Company Name:** <Company Name>  
**Project Name:** <Project Name>  
**Version:** 1.0

---

## Revision History

| Date | Version | Description | Author |
|-----|--------|-------------|--------|
| <dd/mmm/yy> | <x.x> | <details> | <name> |

---

## Table of Contents
1. Introduction  
2. Requirements Management  
3. Requirements Artifacts  
4. Requirements Change Management  
5. Milestones  
6. Training and Resources  

---

## 1. Introduction

This document describes the guidelines used by the project to establish standard requirement documents, requirement types, requirement attributes, and traceability. It defines a general strategy for managing requirements and serves as a resource for all persons participating in this project.

### 1.1 Purpose
The purpose of this plan is to establish and document a systematic approach to eliciting, organizing, and documenting the requirements of the system.  
This plan also establishes and maintains agreement between the customer and the project team on the changing requirements of the system.

### 1.2 Scope
This plan provides guidelines for the management of **[project name(s)]**.

### 1.3 Definitions, Acronyms, and Abbreviations
For common vocabulary for this project, please refer to the **Glossary document**.

### 1.4 References
- Philippe Kruchten (1999). *The Rational Unified Process*. Addison Wesley.  
- Dean Leffingwell & Don Widrig (2000). *Managing Software Requirements*. Addison Wesley.  
- Spence, I. & Probasco, L. (1998). *Traceability Strategies for Managing Requirements with Use Cases*. Rational Software Corporation.  
- Rational Unified Process®, Version 2002.05.00.

### 1.5 Overview
This document contains specific details and strategies for managing the requirements of the project.  
It describes how requirements are organized, traced, modified, and controlled throughout the lifecycle.

---

## 2. Requirements Management

### 2.1 Organization, Responsibilities, and Interfaces

#### 2.1.1 Customer
A person or organization that takes financial responsibility for the system.

#### 2.1.2 User
A person who will use the developed system.

#### 2.1.3 Stakeholder
An individual or organization materially affected by the outcome of the system.

#### 2.1.4 Project Manager
Responsible for overall planning, scheduling, budget, and quality.

#### 2.1.5 Quality Assurance (QA)
Ensures project standards are correctly followed.

#### 2.1.6 Developer
Responsible for developing system functionality.

#### 2.1.7 Team Leader
Interface between project management and developers.

#### 2.1.8 Configuration Manager
Manages configuration, integration, and status reporting.

#### 2.1.9 Requirements Specifier
Defines and maintains system requirements and use cases.

---

### 2.2 Contact Table

| Role | Name | Title | Organization | Contact |
|----|----|----|----|----|
| Customer |  |  |  |  |
| User |  |  |  |  |
| Stakeholder |  |  |  |  |
| Project Manager |  |  |  |  |
| Quality Assurance |  |  |  |  |
| Team Leader |  |  |  |  |
| Requirements Specifier |  |  |  |  |

---

### 2.3 Tools, Environment, and Infrastructure

| Tool | Description | License Info | Technical Support | Website |
|----|------------|-------------|------------------|--------|
| Rational RequisitePro | Requirements management tool |  | support@rational.com | www.rational.com |

---

## 3. Requirements Artifacts

### 3.1 Artifact Description
Defines how requirement artifacts are named, marked, and numbered.

### 3.1.1 Document Types

| Document Type | Description | Default Requirement Type |
|-------------|------------|--------------------------|
| Stakeholder Requests (STR) | Key stakeholder requests | STRQ |
| Vision (VIS) | System vision & features | FEAT |
| Use-Case Specification (UCS) | Use case descriptions | UC |
| Glossary (GLS) | Common vocabulary | TERM |
| Supplementary Requirements (SUP) | Non-use-case requirements | SUPL |
| Requirements Management Plan (RMP) | Requirements management strategy | RMP |

---

### 3.1.2 Requirement Types

| Requirement Type | Description | Attributes |
|-----------------|-------------|------------|
| Stakeholder Request (STRQ) | Stakeholder requests | Priority, Status, Cost, Difficulty |
| Feature (FEAT) | User-visible system service | Priority, Status, Cost |
| Use Case (UC) | System behavior description | Priority, Status, Test |
| Glossary Item (TERM) | Common vocabulary | — |
| Supplementary Requirement (SUPL) | Non-use-case requirement | Priority, Status, Cost |

---

### 3.1.3 Attributes
Attributes include Priority, Status, Difficulty, Stability, Assigned To, Cost, Origin, Rationale, Test, etc.

### 3.1.4 List Values
Defines allowed values such as:
- Priority: Must, Should, Could, Won’t
- Status: Proposed, Approved, Incorporated, Validated
- Difficulty: High, Medium, Low
- Stability: High, Medium, Low

---

## 3.2 Traceability

### 3.2.1 Traceability Criteria

| Requirement Type | Guideline |
|-----------------|-----------|
| STRQ | Approved requests must trace to Features |
| FEAT | Approved features must trace to Use Cases or SUPL |
| TERM | Definitions must be consistent |
| SUPL | Must trace to Features or Use Cases |

---

## 3.3 Reports and Measures
Reports are generated using the **Requirement Metrics tool**, including:
- Attribute Value reports
- Change history reports
- Traceability change reports

---

## 4. Requirements Change Management

### 4.1 Change Request Processing
1. Stakeholder submits Change Request (CR).  
2. CCB reviews impact and priority.  
3. Responsibilities are assigned.  
4. Changes are implemented and tested.  
5. Change Request is validated and closed.

### 4.2 Change Control Board (CCB)
The CCB evaluates, prioritizes, and approves change requests.

---

## 5. Milestones

### 5.1 Inception
**Evaluation Criteria**
- Stakeholder agreement on scope
- Shared understanding of requirements
- Identified risks with mitigation plans

### 5.2 Elaboration
- Stable vision and architecture
- Risks addressed
- Detailed construction plans

### 5.3 Construction
- Product stability
- Stakeholder readiness
- Acceptable resource usage

### 5.4 Transition
- User satisfaction
- Product release readiness

---

## 6. Training and Resources
Describes tools, personnel, and training required to execute requirements management activities.
