<div align="center">

<img src="media/rosai_logo.png" width="92" alt="RosAI Coliseum logo" />

# RosAI Coliseum

**An AI-native pathology learning platform — quiz engine, hematopathology workspace, flow-cytometry analyzer, and adaptive AI tutoring in one desktop app.**

[![Status](https://img.shields.io/badge/Status-Active_Development-2ea44f?style=for-the-badge)](#)
[![Built with](https://img.shields.io/badge/Built_with-PySide6-41cd52?style=for-the-badge&logo=qt&logoColor=white)](https://wiki.qt.io/Qt_for_Python)
[![AI](https://img.shields.io/badge/AI-Claude_Powered-8A2BE2?style=for-the-badge)](#)
[![Scale](https://img.shields.io/badge/Codebase-24k%2B_lines-blue?style=for-the-badge)](#)

<br/>

<a href="media/Intro_RosAI.mp4"><img src="media/Intro_RosAI_poster.png" width="760" alt="RosAI Coliseum — click to play the overview video" /></a>

### ▶ [Watch the 20-second tour](media/Intro_RosAI.mp4)

<sub>*A showcase repository — screenshots and overview. Source code is private (commercial product).*</sub>

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
- 🔍 **Global search** — one query across questions, images, flashcards, notes, and explanations
- 🤖 **AI Tutor & Image Analyzer** — Claude-powered explanations and image read-outs
- ☁️ **Study Cloud** — explanations tailored to *your specific* wrong answer, with a visual "misconception map"
- 🩸 **HemePath workspace** — WHO 5th-edition diagnostic worksheets across 130+ entities
- 🔬 **Cell Counter** — interactive blood-smear differentials with AI-assisted classification
- 📊 **Flow Cytometry Analyzer** — interactive dot-plot gating, marker atlas, and case library (B-ALL, CLL, AML, APL, FL, normal marrow)
- 📚 **Built-in references** — WHO Blue Books and a categorized lecture library inside the app
- 🎭 **SlideLies game** — the AI describes a slide; you call *BS* or *Concur* — gamified pattern recognition
- ⌨️ **Command Palette (Ctrl+K)** — instant navigation across every module

---

## Feature tour

### Whole-slide image viewer
The built-in viewer pans and zooms full Aperio slides right beside a live quiz question — image-based reasoning without ever leaving the question.

<div align="center">

<a href="media/QBANK_BUILT_IN_WSI_VIEWER.mp4"><img src="media/QBANK_BUILT_IN_WSI_VIEWER_poster.png" width="760" alt="Built-in WSI viewer demo — click to play" /></a>

**▶ [Play the live WSI viewer demo (44s)](media/QBANK_BUILT_IN_WSI_VIEWER.mp4)**

</div>

### Global search across the whole library
A single search box spans questions, images, flashcards, notes, and explanations — find every place a concept appears without switching modules.

![Global search](media/global_search.png)

### Lecture library with inline video
Curated board-review lectures play right inside the app, organized by category, with notes and source links beside each video.

![Lecture library](media/lectures.png)

### WHO Blue Books, built in
The WHO Classification of Tumours (5th edition) is one click away — browse the official Blue Books without leaving the app for a browser.

![WHO Blue Books integration](media/who_books.png)

### Cell Counter — interactive blood-smear differentials
Click cells on a smear to tag them; the counter keeps a running differential across the WBC, RBC, and platelet lines, with AI-assisted classification on demand.

![Cell Counter](media/cell_counter.png)

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
