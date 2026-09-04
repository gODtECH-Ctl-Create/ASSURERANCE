<div align="center">

# 🧠 ASSURERANCE

### A collection of product concepts, UX explorations, architecture notes, and engineering experiments.

<p>
<img src="https://img.shields.io/badge/status-concept%20archive-111827" alt="Concept archive">
<img src="https://img.shields.io/badge/license-proprietary-7c3aed" alt="Proprietary license">
<img src="https://img.shields.io/badge/research-product%20experiments-0f766e" alt="Product experiments">
</p>

**A working archive of ideas explored across software products and engineering tools.**

</div>

---

## 🧭 What is ASSURERANCE?

ASSURERANCE is a historical project workspace containing several product concepts and technical explorations. The repository is valuable as a record of product thinking, architecture sketches, engineering tasks, and interface research rather than as a single finished application.

<table>
<tr><td width="50%">

### 🪪 Certificate Generator
A workflow for generating personalized certificates from templates and bulk recipient data.

### 🌦️ Rain When
A simple Nigeria-focused weather experience centered on one question: **will it rain today, and when?**

</td><td width="50%">

### 💱 Real Exchange Rate
An exploration of a country-aware exchange-rate experience focused on local market context.

### 🧑‍💻 Engineering 360° Evaluator
A skills-assessment concept for organizations to evaluate engineers across topics and visualize results.

</td></tr>
</table>

## 🔄 Concept map

```mermaid
graph TD
    A[ASSURERANCE archive] --> B[Certificate Generator]
    A --> C[Rain When]
    A --> D[Real Exchange Rate]
    A --> E[Engineering 360° Evaluator]
    B --> F[Templates + CSV + delivery]
    C --> G[Weather data + simple forecast]
    D --> H[Location + currency data]
    E --> I[Questions + scoring + radar profile]
```

<details open>
<summary><strong>🪪 Certificate Generator</strong></summary>

The original concept explored template selection, recipient data import from Comma-Separated Values (CSV) files, unique certificate URLs, bulk email delivery, and downloadable certificate output.

</details>

<details>
<summary><strong>🌦️ Rain When</strong></summary>

The concept intentionally removes unnecessary weather information and focuses on whether rain is expected and when it may begin. It was designed as a frontend-heavy experience with a backend reverse proxy for protected API access.

</details>

<details>
<summary><strong>💱 Real Exchange Rate</strong></summary>

The concept explored location-aware country selection, map interaction, and exchange-rate lookup using country/currency codes.

</details>

<details>
<summary><strong>🧑‍💻 Engineering 360° Evaluator</strong></summary>

Organizations create assessment spaces, candidates answer timed multiple-choice questions, and results are grouped by category for comparison and radar/spider-chart visualization.

</details>

## 🛠️ Technology themes

Historical notes reference React, Tailwind CSS, Chakra UI, Chart.js, Node.js, TypeScript, PostgreSQL, MongoDB, Prisma, Python, FastAPI, and email/API integrations.

## 📚 Why this repository matters

The archive preserves early product exploration, interaction ideas, data models, and engineering decisions. Individual concepts may later become independent products or research branches.

## 🔐 Ownership

This repository contains proprietary product concepts, source material, documentation, and design research. See [`LICENSE`](./LICENSE) for usage terms.
