# 📊 CBC Survey Dashboard

> **Big Data Analytics Assignment — PIS 9204**
> PhD in Information Systems · Makerere University

---

## Overview

This repository contains data and visualizations from a field study on the **CBC Lesson Plan Generator**, a system that supports Ugandan secondary school teachers in CBC-aligned lesson planning across multiple secondary schools in Uganda.

Two surveys were administered. Survey 1 measured teacher perceptions before using the system. Survey 2 measured outcomes after teachers had generated and taught at least one lesson plan.

🌐 **Live Project:** [cbclessonplansug.com](https://www.cbclessonplansug.com)

---

## Dashboard Preview

| Chart | Type | Survey | Construct |
|-------|------|--------|-----------|
| 1 | Radar | Survey 1 | TAM Constructs (5) |
| 2 | Donut | Survey 1 | Subject Distribution |
| 3 | Stacked Bar | Survey 1 | Perceived Usefulness — Likert Distribution |
| 4 | Bubble Pack | Survey 2 | PCK Item Means (10 items) |
| 5 | Grouped Bar | Survey 2 | Construct Comparison |
| 6 | Histogram | Survey 1 | Planned Lesson Delivery Dates |

---

## Study Context

| Detail | Survey 1 | Survey 2 |
|--------|----------|----------|
| **Timing** | Post-introduction | Post-implementation |
| **Original N** | 106 | 71 |
| **Final N** | 103 | 69 |
| **Excluded** | 3 (attention check failures) | 2 (attention check failures) |
| **Scale** | 5-point Likert | 5-point Likert |
| **Setting** | Multiple Ugandan secondary schools | Same schools |

---

## Key Findings

### Survey 1 — TAM Construct Means (N = 103)

| Construct | Mean | Items |
|-----------|------|-------|
| Job Relevance | 4.52 | 2 |
| Behavioral Intention | 4.45 | 2 |
| Perceived Usefulness | 4.44 | 4 |
| Perceived Ease of Use | 4.33 | 4 |
| System Quality | 4.07 | 2 |

### Survey 2 — Post-Implementation Construct Means (N = 69)

| Construct | Mean | Items |
|-----------|------|-------|
| Teaching Self-Efficacy | 4.10 | 2 |
| System Quality | 4.06 | 4 |
| PCK Gains | 4.04 | 10 |
| Life Satisfaction *(control)* | 3.96 | 4 |

---

## Repository Structure

```
cbc-survey-dashboard/
├── cbc_survey_dashboard.html   # Self-contained D3 v7 dashboard
├── survey1_cleaned.csv         # Post-introduction survey data (N = 103)
├── survey2_cleaned.csv         # Post-implementation survey data (N = 69)
└── README.md
```

---

## Data

**survey1_cleaned.csv**
Measures five Technology Acceptance Model constructs: Perceived Usefulness, Perceived Ease of Use, Behavioral Intention, System Quality, and Job Relevance. Includes demographic variables: subject taught and planned lesson delivery date.

**survey2_cleaned.csv**
Measures Pedagogical Content Knowledge Gains (10 items), System Quality and Satisfaction (4 items), Teaching Self-Efficacy (2 items), and Life Satisfaction as a control variable (4 items). Includes an open-ended qualitative response column.

---

## How to View the Dashboard

No server or installation required.

1. Download `cbc_survey_dashboard.html`
2. Open the file in any modern browser
3. All data is embedded in the file
4. Hover over any chart element to see exact values

---

## D3 Features Demonstrated

| Feature | Chart |
|---------|-------|
| Path drawing + linear scales | Radar (Chart 1) |
| Pie layout + arc generator | Donut (Chart 2) |
| Stack operator + enter/update/exit | Stacked Bar (Chart 3) |
| Pack layout | Bubble (Chart 4) |
| Band scales + axes + transitions | Grouped Bar (Chart 5) |
| Time scale + histogram rects | Histogram (Chart 6) |

---

## Technology

- [D3.js v7](https://d3js.org) — All visualizations
- [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) — Display typography
- [Space Mono](https://fonts.google.com/specimen/Space+Mono) — Monospace labels
- Vanilla HTML/CSS/JS — No build step required

---

## Related Research

This field study supports a PhD research project at Makerere University examining the adoption of RAG-based AI tools for teacher empowerment under the Ugandan Competence-Based Curriculum framework.

A research paper on the NDU Lesson Plan Generator has been submitted to the **EAC Regional Science, Technology and Innovation Conference**.

---

*Ndejje University AI Research Centre · Faculty of Science and Computing*
