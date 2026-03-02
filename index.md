---
layout: home
title: ""
---

<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

<div align="center">
  <h1>Miguel López Cordero</h1>
  <h3>Aerospace Engineer | Systems & Software Specialist (C++, Python, MBSE)</h3>
  
  <a href="https://www.linkedin.com/in/miguel-l%C3%B3pez-cordero-b62b88233/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:miguecllopez@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <br/> <a href="/assets/docs/CV_MIGUEL_LOPEZ.pdf">
    <img src="https://img.shields.io/badge/Download_Resume_(PDF)-000000?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Download CV"/>
  </a>
</div>

<br><br>
---

## 🚀 About Me

I am an **Aerospace Engineer** specializing in the intersection of **Systems Engineering (MBSE)** and **Critical Flight Software**. My goal is to optimize the lifecycle of space systems using rigorous methodologies and modern programming languages.

Currently balancing two master's programs in **Space Operations** and **Space Systems**, I combine theoretical knowledge of orbital mechanics with practical implementation in **C++ and Python**.

---

## 🛠 Tech Stack & Skills

| Category | Technologies |
| :--- | :--- |
| **Languages** | ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=white) ![Matlab](https://img.shields.io/badge/MATLAB-orange?style=flat) |
| **Systems Eng.** | ![Capella](https://img.shields.io/badge/Capella-MBSE-purple?style=flat) ![SysML](https://img.shields.io/badge/SysML-Arcadia-blue?style=flat) ![Siemens](https://img.shields.io/badge/Siemens-Teamcenter-009999?style=flat) |
| **Tools** | ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white) ![LaTeX](https://img.shields.io/badge/LaTeX-47A141?style=flat&logo=LaTeX&logoColor=white) |
| **AI & LLM** | ![MCP](https://img.shields.io/badge/Model_Context_Protocol-MCP-blueviolet?style=flat) ![LLM](https://img.shields.io/badge/LLM-APIs-ff69b4?style=flat) ![Agents](https://img.shields.io/badge/AI-Agents-orange?style=flat) ![ReqIF](https://img.shields.io/badge/ReqIF-Automation-darkblue?style=flat) |
| **CI/CD & DevOps** | ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white) ![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat&logo=gitlab&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white) |
| **Standards** | **ECSS** (Space), **DO-178C** (Avionics), **MISRA-C++** |

---

## 🛰️ Featured Projects

### 1. Microsatellite AOCS Flight Software
**GitLab Repository** | *ARM Cortex-A9, FreeRTOS, C, SysML v2*

Developed as my **Master's Thesis (TFM)**, this project implements a safety-critical Attitude and Orbit Control System (AOCS) for a microsatellite. It features a full migration from initial RISC-V prototypes to a production-ready ARM-based environment.

* [![GitLab](https://img.shields.io/badge/View_Project_on-GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)](https://gitlab.com/miguelito-space/Miguelito-Microsatellite-AOCS-SW)

**Technical Key Points:**
* **Real-Time Architecture:** GNC algorithms deployed on **ARM Cortex-A9 (Zynq-7000)** using **FreeRTOS** to ensure deterministic execution and multi-tasking.
* **MBSE & SysML v2:** "Single source of truth" design using **SysML v2**, maintaining traceability between requirements and embedded C implementation.
* **Control Algorithms:** Implementation of a **B-Dot** law for detumbling and **EKF** for attitude estimation, optimized for low-power microsatellite platforms.
* **V&V Workflow:** Comprehensive verification through **Software-in-the-Loop (SIL)** and **Hardware-in-the-Loop (HIL)**, validating control performance against physical hardware constraints.

---

### 2. AI & Personal Projects *(Agents · LLMs · Edge AI)*
**Python · LLM APIs · RISC-V · Duffel API**

Two applied AI initiatives: an autonomous flight search agent using the **Model Context Protocol** and an edge-AI deployment on a **RISC-V SoC (SG2002/Lichee Pi)** using **OpenClaw**.

* [![View Projects](https://img.shields.io/badge/View_AI_Projects-4A90D9?style=for-the-badge&logo=github&logoColor=white)](https://miguelcllopez.github.io/ai-projects/)

---

### 3. MBSE Application to ATA 21 (ECS) System
**Systems Engineering** | *Capella, MATLAB/Simulink*

Digital thread implementation for the Air Conditioning and Pressurization System of a **C-295 aircraft**.

* [![PDF](https://img.shields.io/badge/Read_Full_Report-PDF-B31B1B?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](assets/docs/MBSE_ATA21_Report.pdf)

* **Methodology:** Full ARCADIA application (Operational to Physical architecture).
* **Simulation:** Developed **Fault Tree Analysis (FTA)** and 1D physical models in Simulink for V&V.
* **Traceability:** Automated requirements management from EASA CS-25 using **Python4Capella**.

---

## 💼 Professional Experience

### **Systems Software Engineer Intern (C++/Embedded)**
**Tecnobit - Grupo Oesía** | *Nov 2025 - Present*
* Develop critical software for aerospace communication and defense systems (encryption), strictly adhering to military standards (**MIL-STD**, **DO-178C**).
* Program in **C++** for embedded systems, covering hardware-software integration and physical validation.
* Manage software and system requirements traceability using **IBM DOORS** and **Enterprise Architect**.
* Ensure quality assurance through static analysis (**CppCheck**), bug fixing, and compliance with **MISRA-C++** standards.
* Utilize **GitLab** for version control, implement CI/CD pipelines with **Jenkins**, and manage Agile workflows in **Jira**.

### **System Architecture Engineer**
**Accenture** | *Apr 2025 - Jul 2025*
* Applied **Model-Based Systems Engineering (MBSE)** principles using the Arcadia methodology and **Capella** tool for the analysis of naval systems.
* Developed reusable model libraries for Navantia's naval vessels, enhancing design standardization across systems.
* Executed a case study on the **S-80 submarine** control system, validating the application of models in defense.
* Performed 1D modeling and simulation with **Siemens Amesim (PLM)** for early Verification and Validation (V&V) of requirements.
* Managed engineering data and lifecycle traceability using **Teamcenter**.

---

## 🎓 Education

* **Master's in Operation of Space Systems** - Univ. de Sevilla (2025-2026)
* **Master's in Space Systems** - Universidad Europea (2025-2026)
* **B.Sc. Aerospace Engineering** - Univ. de Sevilla (2021-2025)
* **Erasmus+ Exchange Program (Aerospace Engineering)** - University of Pisa (2023-2024)

---

## 🌍 Global Mindset & Interests

Beyond the technical field, I am passionate about **languages and cultural immersion**. Having visited **over 50 countries across all continents**, I thrive in dynamic environments and possess strong logistical planning skills.

* **Languages:**
  * **Spanish:** Native
  * **English:** [C1 Certified](assets/docs/English-C1.pdf) 
  * **French:** [B2 Certified](assets/docs/French-B2.pdf)
  * **Italian:** [B2 Certified](assets/docs/Italian-B2.pdf)
  * **Learning:** German & Portuguese
* **Exploration:** Experienced traveler with a global perspective, essential for seamless integration into international engineering projects.

<div align="center">
  <small>© 2026 Miguel López Cordero</small>
</div>
