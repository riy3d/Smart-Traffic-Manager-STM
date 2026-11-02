# Smart Traffic Manager (STM)

<p align="center">
  <strong>A System Analysis and Design Project</strong>
  <br>
  Modeling a Smart Traffic Management System
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Project-Academic%20Project-blue?style=for-the-badge" alt="Academic Project">
  <img src="https://img.shields.io/badge/Domain-Software%20Engineering-purple?style=for-the-badge" alt="Software Engineering">
  <img src="https://img.shields.io/badge/Focus-System%20Analysis%20%26%20Design-green?style=for-the-badge" alt="System Analysis and Design">
</p>

---

## Table of Contents

* [Project Overview](#-project-overview)
* [Project Objectives](#-project-objectives)
* [System Analysis and Modeling](#-system-analysis-and-modeling)
* [System Diagrams](#-system-diagrams)

  * [Context Diagram](#1-context-diagram)
  * [Data Flow Diagrams](#2-data-flow-diagrams-dfd)
  * [Transaction Diagram](#3-transaction-diagram)
* [UML Diagrams](#-uml-diagrams)

  * [Use Case Diagram](#4-use-case-diagram)
  * [Sequence Diagram](#5-sequence-diagram)
  * [Class Diagram](#6-class-diagram)
  * [Activity Diagram](#7-activity-diagram)
* [Project Documentation](#-project-documentation)
* [Tools and Concepts](#-tools-and-concepts)
* [Repository Structure](#-repository-structure)
* [Project Information](#-project-information)
* [Contributors](#-contributors)

---

## 📌 Project Overview

**Smart Traffic Manager (STM)** is an academic project developed as part of the **System Analysis and Design** course.

The project focuses on analyzing and modeling a smart traffic management system through structured system analysis techniques and software engineering diagrams.

It aims to represent the system's overall structure, processes, interactions, data flows, and activities using different modeling approaches.

This repository contains the project's system models, diagrams, and supporting documentation.

## 🎯 Project Objectives

The main objectives of this project are:

* Analyze the requirements of a Smart Traffic Management System.
* Identify the main system components and external entities.
* Represent how information flows between system processes.
* Model system behavior and interactions.
* Define the structural relationships between system components.
* Apply system analysis and software design concepts.
* Document the system using standard modeling techniques.

---

## 🧩 System Analysis and Modeling

The project applies several system analysis and modeling techniques to describe the system from different perspectives.

| Modeling Technique      | Purpose                                                                 |
| ----------------------- | ----------------------------------------------------------------------- |
| Context Diagram         | Defines the system boundary and its interaction with external entities. |
| Data Flow Diagram (DFD) | Represents the movement and processing of information.                  |
| Transaction Diagram     | Illustrates the transaction-related flow within the system.             |
| Use Case Diagram        | Describes system functionality from the users' perspective.             |
| Sequence Diagram        | Shows interactions between system components over time.                 |
| Class Diagram           | Represents the system's structural design and relationships.            |
| Activity Diagram        | Describes workflows and sequences of activities.                        |

---

## 📊 System Diagrams

### 1. Context Diagram

The Context Diagram provides a high-level overview of the Smart Traffic Manager system.

It illustrates the system boundary and the interactions between the system and its external entities.

<p align="center">
  <img src="Diagrams/Context-Diagram.png" alt="Smart Traffic Manager Context Diagram" width="90%">
</p>

---

### 2. Data Flow Diagrams (DFD)

Data Flow Diagrams illustrate how information moves throughout the system, including processes, external entities, data stores, and data flows.

#### DFD Level 0

Provides a high-level representation of the system's main processes and data flows.

<p align="center">
  <img src="Diagrams/DFD/DFD-Level-0.png" alt="DFD Level 0" width="90%">
</p>

#### DFD Level 1

Decomposes the main system processes into more detailed subprocesses and illustrates their internal data flows.

<p align="center">
  <img src="Diagrams/DFD/DFD-Level-1.png" alt="DFD Level 1" width="90%">
</p>

#### Lower-Level DFDs

Provide further decomposition of selected processes, showing their internal operations and detailed data flows.

<details>
<summary><strong>Lower-Level DFD 1</strong></summary>
<br>
<img src="Diagrams/DFD/Lower-Level/Lower-Level-1.png" alt="Lower-Level DFD 1" width="100%">
</details>

<details>
<summary><strong>Lower-Level DFD 2</strong></summary>
<br>
<img src="Diagrams/DFD/Lower-Level/Lower-Level-2.png" alt="Lower-Level DFD 2" width="100%">
</details>

<details>
<summary><strong>Lower-Level DFD 3</strong></summary>
<br>
<img src="Diagrams/DFD/Lower-Level/Lower-Level-3.png" alt="Lower-Level DFD 3" width="100%">
</details>

<details>
<summary><strong>Lower-Level DFD 4</strong></summary>
<br>
<img src="Diagrams/DFD/Lower-Level/Lower-Level-4.png" alt="Lower-Level DFD 4" width="100%">
</details>

---

### 3. Transaction Diagram

The Transaction Diagram represents the transaction flow within the system and illustrates the sequence of transaction-related operations.

<p align="center">
  <img src="Diagrams/Transaction-Diagram.png" alt="Transaction Diagram" width="90%">
</p>

---

## 🔷 UML Diagrams

UML diagrams are used to represent the system's functionality, behavior, structure, and interactions.

### 4. Use Case Diagram

Illustrates the interactions between system actors and the functionalities provided by the Smart Traffic Manager system.

<p align="center">
  <img src="Diagrams/UML/Use-Case-Diagram.png" alt="Use Case Diagram" width="90%">
</p>

### 5. Sequence Diagram

Describes the sequence of interactions between system components and how operations are performed over time.

<p align="center">
  <img src="Diagrams/UML/Sequence-Diagram.png" alt="Sequence Diagram" width="90%">
</p>

### 6. Class Diagram

Represents the system's structural design, including classes, attributes, operations, and relationships.

<p align="center">
  <img src="Diagrams/UML/Class-Diagram.png" alt="Class Diagram" width="90%">
</p>

### 7. Activity Diagram

Illustrates the workflow of system activities, including actions, decisions, and possible execution paths.

<p align="center">
  <img src="Diagrams/UML/Activity-Diagram.png" alt="Activity Diagram" width="90%">
</p>

---

## 📚 Project Documentation

The following documents provide additional details about the project and its analysis.

| Document                                                             | Description                                        |
| -------------------------------------------------------------------- | -------------------------------------------------- |
| [Project Documentation](Documentation/STM-Project-Documentation.pdf) | Contains the main project documentation.           |
| [System Analysis](Documentation/STM-System-Analysis.pdf)             | Contains supporting system analysis documentation. |

---

## 🛠 Tools and Concepts

### System Analysis & Design

* System Requirements Analysis
* System Modeling
* Process Decomposition
* Data Flow Modeling
* System Behavior Modeling

### Diagramming & Modeling

* Context Diagrams
* Data Flow Diagrams (DFD)
* Unified Modeling Language (UML)
* Use Case Modeling
* Sequence Modeling
* Class Modeling
* Activity Modeling

---

## 📁 Repository Structure

```text
Smart-Traffic-Manager-STM/
│
├── README.md
│
├── Diagrams/
│   │
│   ├── Context-Diagram.png
│   │
│   ├── DFD/
│   │   ├── DFD-Level-0.png
│   │   ├── DFD-Level-1.png
│   │   │
│   │   └── Lower-Level/
│   │       ├── Lower-Level-1.png
│   │       ├── Lower-Level-2.png
│   │       ├── Lower-Level-3.png
│   │       └── Lower-Level-4.png
│   │
│   ├── Transaction-Diagram.png
│   │
│   └── UML/
│       ├── Use-Case-Diagram.png
│       ├── Sequence-Diagram.png
│       ├── Class-Diagram.png
│       └── Activity-Diagram.png
│
├── Documentation/
│   ├── STM-Project-Documentation.pdf
│   └── STM-System-Analysis.pdf
│
└── LICENSE
```

---

## ℹ️ Project Information

| Attribute          | Details                               |
| ------------------ | ------------------------------------- |
| Project Name       | Smart Traffic Manager (STM)           |
| Project Type       | Academic Project                      |
| Field              | Software Engineering                  |
| Course             | System Analysis and Design            |
| Main Focus         | System Analysis, Modeling, and Design |
| Repository Purpose | Academic Documentation and Portfolio  |

---

## 👥 Contributors

This project was developed collaboratively as part of an academic team.

* **Riyad Ayman** — Project Contributor
* **[Team Member 2]** — Project Contributor
* **[Team Member 3]** — Project Contributor
* **[Team Member 4]** — Project Contributor

---

<p align="center">
  <strong>Smart Traffic Manager (STM)</strong>
  <br>
  <sub>System Analysis and Design Project</sub>
  <br><br>
  <em>Designed to model and understand smarter traffic management systems.</em>
</p>
