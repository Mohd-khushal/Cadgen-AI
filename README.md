# CADGen: AI-Powered Text-to-CAD Generator

> Convert natural language into editable parametric CAD models using Large Language Models and OpenSCAD.

![Status](https://img.shields.io/badge/Status-Completed-success)
![AI](https://img.shields.io/badge/Powered%20By-Google%20Gemini-blue)
![Rust](https://img.shields.io/badge/Backend-Rust-orange)
![OpenSCAD](https://img.shields.io/badge/CAD-OpenSCAD-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## Overview

CADGen is an AI-powered desktop application that transforms natural language descriptions into editable parametric CAD models. By leveraging Google's Gemini Large Language Model and OpenSCAD, the system automatically generates OpenSCAD scripts, renders 3D models, and exports them for engineering workflows such as rapid prototyping and manufacturing.

Unlike conventional text-to-3D systems that generate static meshes, CADGen focuses on producing **editable parametric CAD code**, allowing engineers to modify dimensions, features, and design parameters after generation.

---

## Problem Statement

Traditional CAD modeling requires significant expertise and manual effort. Designing complex mechanical components is often:

- Time-consuming
- Technically demanding
- Difficult to iterate rapidly
- Less accessible for beginners

Current AI-powered Text-to-3D systems primarily generate meshes for visualization but lack the precision and editability required for engineering applications.

CADGen bridges this gap by generating executable OpenSCAD code from natural language prompts.

---

## Features

- AI-powered Text-to-CAD generation
- Natural language interface
- Automatic OpenSCAD code generation
- Editable parametric CAD models
- STL model generation
- Cross-platform desktop application
- GUI-based workflow
- Human-in-the-loop design refinement
- Engineering-focused design pipeline

---

## How It Works

```
           User Prompt
                │
                ▼
      Google Gemini LLM
                │
                ▼
    OpenSCAD Script Generation
                │
                ▼
     OpenSCAD Geometry Engine
                │
                ▼
     Parametric CAD Model
                │
                ▼
      STL / Preview / Export
```

---

## Project Architecture

(Add architecture diagram here)

```
assets/architecture.png
```

---

## Technology Stack

| Category | Technology |
|----------|------------|
| AI Model | Google Gemini |
| CAD Engine | OpenSCAD |
| Backend | Rust |
| Frontend | Svelte 5 |
| Desktop Framework | Tauri v2 |
| IDE | Visual Studio Code |
| Version Control | Git & GitHub |
| Operating System | Ubuntu 24.04 LTS |

---

## Project Objectives

- Investigate the capability of Large Language Models to understand mechanical engineering terminology.
- Convert natural language prompts into executable OpenSCAD scripts.
- Generate editable parametric CAD models automatically.
- Evaluate generated models based on precision, editability, complexity, and manufacturability.
- Improve engineering design productivity through AI-assisted CAD generation.

---

## Example Prompt

```
Create a cube of 100 mm with a centered hole of diameter 20 mm.
```

### AI Output

- OpenSCAD Script
- Rendered CAD Model
- STL File

---

## Repository Structure

```
CADGen/
│
├── assets/
│   ├── screenshots/
│   ├── demo.gif
│   └── architecture.png
│
├── docs/
│   ├── installation.md
│   ├── prompts.md
│   └── project-report.pdf
│
├── examples/
├── src/
├── README.md
├── LICENSE
└── .gitignore
```

---

## Installation

Detailed installation instructions will be available in:

```
docs/installation.md
```

---

## Screenshots

### Home Screen

(Add screenshot)

---

### Generated OpenSCAD Code

(Add screenshot)

---

### Generated CAD Model

(Add screenshot)

---

### Application Interface

(Add screenshot)

---

## Demo

(Add GIF)

```
assets/demo.gif
```

---

## Applications

- Mechanical Engineering
- Product Design
- CAD Automation
- Rapid Prototyping
- Manufacturing
- AI-Assisted Design
- Engineering Education

---

## Future Improvements

- Multi-turn CAD editing
- Support for additional CAD platforms
- RAG-based OpenSCAD documentation retrieval
- Multi-model LLM support
- CAD validation pipeline
- Automatic design optimization
- Cloud deployment
- Agentic CAD workflows

---

## Publication

This work was presented as part of the B.Tech final-year project titled:

**Exploratory Analysis of Generative AI in Automated CAD Design of Mechanical Parts**

Department of Mechanical Engineering

Netaji Subhas University of Technology (NSUT)

---

## Team

- Mohd Khushal
- Shubham Yadav
- Sumit Kumar

Supervisor:

Dr. A. V. Muley

Department of Mechanical Engineering

Netaji Subhas University of Technology

---

## Acknowledgements

We thank the Department of Mechanical Engineering, NSUT, and our project supervisor for their continuous guidance and support throughout the development of CADGen.

---

## License

This project is released under the MIT License.

```
MIT License
```
