# Cybersecurity Frameworks Assignment
## Project Architecture

This document explains how the project is organized and how each file contributes to the final report.

---

# Project Structure

```
Cybersecurity-Frameworks-Assignment/

├── main.tex
├── preamble.tex
├── references.bib
│
├── sections/
│   ├── titlepage.tex
│   ├── abstract.tex
│   ├── introduction.tex
│   ├── partA.tex
│   ├── partB.tex
│   ├── partC.tex
│   ├── partD.tex
│   ├── conclusion.tex
│   └── appendix.tex
│
├── figures/
├── tables/
├── templates/
├── docs/
└── appendices/
```

---

# File Responsibilities

## main.tex

The main entry point of the project.

Its job is NOT to contain report content.

Instead it

- imports the preamble
- assembles every section
- controls page numbering
- controls document order
- prints the bibliography

Think of it as the conductor of an orchestra.

---

## preamble.tex

Controls the appearance of the entire document.

Contains

- packages
- page layout
- margins
- typography
- headers
- bibliography settings
- hyperlink settings

Almost never edited once complete.

---

## references.bib

Bibliography database.

Every source should be added here.

Never manually type references into the report.

---

## sections/

Contains the actual report.

Each file has one responsibility.

Example

partA.tex only contains Part A.

Nothing else.

---

## figures/

Contains

- screenshots
- diagrams
- exported charts
- illustrations

---

## templates/

Reusable LaTeX snippets.

Examples

- Risk Register
- Comparison Table
- Gantt Chart
- Figure Template

---

## docs/

Documentation for this project.

---

# Workflow

main.tex

↓

loads preamble.tex

↓

begins document

↓

loads titlepage

↓

loads introduction

↓

loads Part A

↓

loads Part B

↓

loads Part C

↓

loads Part D

↓

prints bibliography

↓

loads appendices

---

# Design Philosophy

Every file has ONE responsibility.

Small files are easier to understand.

Small files are easier to debug.

Small files are easier to reuse.
