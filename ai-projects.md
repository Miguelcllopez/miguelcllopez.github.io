---
layout: page
title: "AI & Personal Projects"
permalink: /ai-projects/
---

<div align="center">
  <h2>AI & Personal Projects</h2>
  <p>Applied AI initiatives exploring autonomous agents, LLM-driven engineering workflows, and edge inference on embedded hardware.</p>
  <a href="/">← Back to Portfolio</a>
</div>

<br>

---

## 1. Autonomous AI Flight Search Agent
**Personal Project** | *Python · Duffel API · Google Flights API · LLM Agent*

[![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=white)](https://github.com/miguelcllopez)
[![LLM](https://img.shields.io/badge/LLM-Agent-blueviolet?style=flat)]()

Developed an **autonomous AI agent** that automates end-to-end flight search and selection. The system integrates the **Duffel** and **Google Flights** APIs to retrieve real-time flight offers, then delegates decision-making to an LLM, which evaluates and ranks results against a user-defined preference profile (price, layovers, departure time, airline).

**Key aspects:**
- Agentic pipeline with **tool-use** and structured output parsing
- LLM acts as a reasoning layer over live API data — no hardcoded rules
- Preference profile system allows personalised, context-aware flight selection
- Demonstrates end-to-end automation of a multi-step search and decision workflow

> *Motivation: explore practical LLM agent design for real-world API orchestration and automated decision-making.*

---

## 2. LLM-driven Requirements Engineering for MBSE
**Master's Thesis Component** | *Python · LLM APIs · ReqIF · Capella · Arcadia*

[![Capella](https://img.shields.io/badge/Capella-MBSE-purple?style=flat)]()
[![ReqIF](https://img.shields.io/badge/ReqIF-Requirements-darkblue?style=flat)]()
[![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=white)](https://github.com/miguelcllopez)

Designed and implemented a tool that uses **Large Language Models** to automatically generate **ReqIF-compliant requirements files** from natural language inputs, ready for direct import into **Capella MBSE models**.

The tool bridges the gap between informal requirement descriptions and structured systems engineering artefacts, reducing manual authoring effort and minimising traceability inconsistencies across the ARCADIA methodology layers.

**Key aspects:**
- LLM parses natural language specs and produces structured **ReqIF XML** output
- Generated files import directly into **Capella** without manual reformatting
- Enforces requirement attribute consistency (ID, type, rationale, verification method)
- Reduces requirements authoring time and improves traceability from system-level to software-level
- Validated on real aerospace system models (ATA 21 Environmental Control System)

> *Directly applicable to AI-assisted requirements traceability and automated design review workflows in science operations environments.*

---

## 3. Edge AI Task Automation on RISC-V SoC
**Research & Development** | *OpenClaw · SG2002 · Lichee Pi · RISC-V · Python*

[![RISC-V](https://img.shields.io/badge/RISC--V-AI_SoC-green?style=flat)]()
[![Linux](https://img.shields.io/badge/Linux-Embedded-FCC624?style=flat&logo=linux&logoColor=black)]()

Investigating the deployment of **AI-driven task automation** on the **Sipeed NanoSG2002 / Lichee Pi** — a compact RISC-V AI SoC featuring an integrated **NPU**, **WiFi 6**, and Ethernet — using the **OpenClaw** framework for local inference and autonomous workflow execution.

The work explores running lightweight AI agents entirely at the edge, without cloud dependency, for autonomous daily task management: scheduling, monitoring, and event-triggered responses.

**Key aspects:**
- **Target hardware:** SG2002 SoC (RISC-V C906 + NPU + WiFi 6 + Ethernet)
- **Framework:** OpenClaw for on-device AI agent orchestration
- Local AI inference — no cloud dependency, privacy-preserving by design
- Bridges embedded systems engineering with on-device AI deployment
- Builds on prior RISC-V experience from thesis work on the **neorv32** soft-core (Xilinx Arty A7 FPGA)

> *Explores the intersection of edge computing, AI autonomy, and the RISC-V open-hardware ecosystem.*

---

<div align="center">
  <small>© 2026 Miguel López Cordero · <a href="/">Portfolio</a> · <a href="https://www.linkedin.com/in/miguel-l%C3%B3pez-cordero-b62b88233/">LinkedIn</a></small>
</div>
