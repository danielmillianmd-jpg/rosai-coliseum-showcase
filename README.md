<div align="center">

<img src="media/rosai_logo.png" width="90" alt="RosAI logo" />

# RosAI Coliseum

**An AI-native pathology learning platform — quiz engine, hematopathology workspace, flow-cytometry analyzer, and adaptive AI tutoring in one desktop app.**

[![Status](https://img.shields.io/badge/Status-Active_Development-2ea44f?style=for-the-badge)](#)
[![Built with](https://img.shields.io/badge/Built_with-PySide6-41cd52?style=for-the-badge&logo=qt&logoColor=white)](https://wiki.qt.io/Qt_for_Python)
[![AI](https://img.shields.io/badge/AI-Claude_Powered-8A2BE2?style=for-the-badge)](#)
[![Scale](https://img.shields.io/badge/Codebase-24k%2B_lines-blue?style=for-the-badge)](#)

*A showcase repository — screenshots and overview. Source code is private (commercial product).*

</div>

---

> **Educational use only.** RosAI Coliseum is a study and teaching tool for pathology trainees. It is not a diagnostic device and is not for clinical decision-making.

## What it is

RosAI Coliseum is a desktop pathology-education platform I designed and built as a practicing physician. It combines a large adaptive question bank with AI-driven tutoring, a WHO-aligned hematopathology workspace, and interactive diagnostic games — the tools I wished existed during board preparation, built into one cohesive app.

The name is a nod to *Rosai & Ackerman*-era surgical pathology tradition, reimagined for an AI-assisted study workflow.

---

## Contents

- [Highlights](#highlights)
- [Feature tour](#feature-tour)
- [The learning loop](#the-learning-loop)
- [Tech stack](#tech-stack)
- [About the author](#about-the-author)

---

## Highlights

- 🧪 **Adaptive Q-Bank** — multi-layer questions with per-distractor reasoning
- 🤖 **AI Tutor & Image Analyzer** — Claude-powered explanations and image read-outs
- ☁️ **Study Cloud** — explanations tailored to *your specific* wrong answer, with a visual "misconception map"
- 🩸 **HemePath workspace** — WHO 5th-edition diagnostic worksheets across 130+ entities
- 📊 **Flow Cytometry Analyzer** — interactive dot-plot gating, marker atlas, and case library (B-ALL, CLL, AML, APL, FL, normal marrow)
- 🎭 **SlideLies game** — the AI describes a slide; you call *BS* or *Concur* — gamified pattern recognition
- ⌨️ **Command Palette (Ctrl+K)** — instant navigation across every module

---

## Feature tour

### Dashboard
A unified home for every study module.

![Dashboard](media/Dashboard%20New%20UI.png)

### Quiz interface
Clean, distraction-free question layout with adaptive explanations.

![Quiz layout](media/clean_layout.png)

### Whole-slide image integration
Embedded WSI viewing alongside questions for image-based reasoning.

![WSI integration](media/embedded_wsi_mockup.png)

### SlideLies — diagnostic reasoning as a game
The AI generates a slide description; the learner decides whether it's accurate.

![SlideLies](media/SlideLies.png)

### Slide preview & question templating
![Slide preview](media/slide_preview.png)

---

## The learning loop

1. **Answer** an adaptive question or play a SlideLies round.
2. **Miss one?** Study Cloud generates an explanation targeted at the *specific* misconception behind your chosen distractor.
3. **See the pattern** — recurring errors surface as a visual misconception map.
4. **Go deeper** — jump to the HemePath workspace or Flow analyzer for the underlying entity.
5. **Repeat** — the bank adapts to what you keep getting wrong.

---

## Tech stack

- **PySide6 (Qt for Python)** — native cross-platform desktop UI
- **Claude API** — AI tutor, image analysis, adaptive explanations, SlideLies generation
- **Custom widgets** — flow-cytometry dot-plot gating, animated "study cloud" visualizations, WSI preview
- **Local-first data** — question banks, case libraries, and progress stored on-device

---

## About the author

Built by **Daniel Millian, MD** — a physician designing AI-assisted tools for pathology education. RosAI Coliseum represents the full arc: clinical domain expertise, product design, and hands-on engineering of a 24,000-line application.

<div align="center">

*© 2026 Daniel Millian. All rights reserved. Screenshots shown for portfolio purposes.*

</div>
