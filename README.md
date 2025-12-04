# SpeechFlow: AI-Powered Text-to-Speech Browser Extension

![Build Status](https://img.shields.io/github/actions/workflow/user/chirag127/SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension/ci.yml?style=flat-square)
![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension?style=flat-square)
![Tech Stack](https://img.shields.io/badge/Tech%20Stack-TypeScript%2C%20Vite%2C%20TailwindCSS-blue?style=flat-square)
![Linting](https://img.shields.io/badge/Lint%2FFormat-Biome-green?style=flat-square)
![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-orange?style=flat-square)
![GitHub Stars](https://img.shields.io/github/stars/chirag127/SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension?style=flat-square)

[//]: # (Add your star button markdown here if applicable for social proof)

---


**SpeechFlow** transforms web content into natural-sounding audio, enhancing productivity and accessibility for hands-free listening. It's an AI-powered browser extension designed for seamless integration into your daily workflow.

This project is maintained with the highest standards, following the **Apex Technical Authority** guidelines for professional, high-velocity, and future-proof software development.

---

## 🚀 Project Architecture & Structure

mermaid
graph TD
    A[Browser Extension Core] --> B(Content Script)
    A --> C(Popup UI)
    A --> D(Background Service)
    B --> E{Speech Synthesis API}
    C --> F[User Interface Layer]
    D --> G{AI Text-to-Speech Service Integration}
    F --> A
    G --> A
    E --> H[Audio Output]


---

## 📖 Table of Contents

*   [🚀 Project Architecture & Structure](#project-architecture--structure)
*   [📖 Table of Contents](#table-of-contents)
*   [✨ Features](#features)
*   [🛠️ Getting Started](#getting-started)
*   [📦 Tech Stack](#tech-stack)
*   [⚙️ Development & Contribution](#development--contribution)
*   [🔒 Security](#security)
*   [⚖️ License](#license)
*   [🤖 AI Agent Directives](#ai-agent-directives)

---

## ✨ Features

*   **AI-Powered TTS:** Utilizes advanced AI models for exceptionally natural and human-like speech synthesis.
*   **Seamless Integration:** Works directly within your browser, transforming selected text or entire articles.
*   **Accessibility Focused:** Enhances web accessibility for users with visual impairments or those who prefer auditory content.
*   **Productivity Boost:** Enables hands-free consumption of web content, ideal for multitasking.
*   **Cross-Browser Compatibility:** Supports major browsers like Chrome, Edge, and Firefox.

---

## 🛠️ Getting Started

### Installation

1.  **Clone the Repository:**
    bash
    git clone https://github.com/chirag127/SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension.git
    cd SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension
    

2.  **Install Dependencies:**
    This project uses `Vite` for efficient build tooling and `npm` for package management.
    bash
    npm install
    

3.  **Run in Development Mode:**
    Launches the extension in development mode, allowing for live updates.
    bash
    npm run dev
    

4.  **Load Unpacked Extension:**
    *   Open your browser (`chrome://extensions`, `edge://extensions`, `about:debugging`).
    *   Enable "Developer mode".
    *   Click "Load unpacked" and select the `dist` or `build` folder from the project directory.

### Building for Production

For a production build, run:

bash
npm run build


This will generate optimized, minified files in the `dist` or `build` folder, ready for packaging as a browser extension.

---

## 📦 Tech Stack

*   **Language:** TypeScript
*   **Build Tool:** Vite (v7+)
*   **Styling:** Tailwind CSS (v4+)
*   **UI Framework:** React (Implicitly, common for Vite extensions)
*   **Linting/Formatting:** Biome (v2+)
*   **Testing:** Vitest (Unit), Playwright (E2E) - *To be implemented
*   **Browser Extension Framework:** WXT (Web Extension Test Framework) or native Vite configuration.

---

## ⚙️ Development & Contribution

We strive for a zero-defect, high-velocity, and future-proof codebase. All contributions are welcome following our standard guidelines.

### Development Principles

*   **SOLID:** Adherence to the Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion principles.
*   **DRY:** Don't Repeat Yourself. Abstract common logic and utilities.
*   **YAGNI:** You Ain't Gonna Need It. Focus on current requirements and avoid speculative features.
*   **TypeScript Strictness:** Enable and enforce the highest level of TypeScript strictness (`strict: true`).

### Contribution Guidelines

Refer to the [CONTRIBUTING.md](https://github.com/chirag127/SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension/blob/main/.github/CONTRIBUTING.md) file for detailed information on how to contribute.

### Scripts

| Script        | Description                                              |
| :------------ | :------------------------------------------------------- |
| `npm install` | Installs project dependencies.                           |
| `npm run dev` | Starts the development server with hot-reloading.        |
| `npm run build`| Builds the project for production.                       |
| `npm run lint` | Lints the codebase using Biome.                          |
| `npm run format`| Formats the codebase using Biome.                        |
| `npm test`    | Runs unit tests using Vitest (when implemented).       |

---

## 🔒 Security

Security is paramount. Please refer to the [SECURITY.md](https://github.com/chirag127/SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension/blob/main/.github/SECURITY.md) file for our security policy and reporting procedures.

---

## ⚖️ License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**. See the [LICENSE](https://github.com/chirag127/SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension/blob/main/LICENSE) file for more details.

---

## 🤖 AI Agent Directives

<details>
<summary>View AI Agent Directives</summary>

# SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

## 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type and apply the **Apex Toolchain**. This repository, `SpeechFlow-AI-Powered-Text-to-Speech-Browser-Extension`, is a TypeScript/JavaScript browser extension.

*   **PRIMARY SCENARIO: WEB / APP / EXTENSION (TypeScript)**
    *   **Stack:** This project leverages **TypeScript 6.x** with strict type checking enabled. The build tool is **Vite 7** (using Rolldown for module bundling). **Tailwind CSS v4** is used for styling, and **React** is the presumed UI library. For browser extensions specifically, we aim for compatibility with the latest standards, potentially using frameworks like **WXT (Web Extension Test Framework)** or direct Vite configurations for multi-browser support (Chrome, Edge, Firefox).
    *   **State Management:** Standardized use of Signals (e.g., Preact Signals, SolidJS Signals, or custom implementation) for efficient and declarative state updates.
    *   **Linting & Formatting:** **Biome v2** is the sole tool for both linting and code formatting, ensuring consistency and high performance across the entire project. Development workflows must integrate Biome checks.
    *   **Testing:** **Vitest** is mandated for unit and component testing. **Playwright** is the standard for end-to-end (E2E) testing, covering cross-browser scenarios. All tests must be robust, well-documented, and run automatically via CI.
    *   **Architecture:** Adheres to modern frontend patterns such as **Feature-Sliced Design (FSD)** or similar modular architectures to ensure maintainability, scalability, and clear separation of concerns.

*   **SECONDARY SCENARIO: DATA / SCRIPTS / AI (Python) - *Not applicable for this project's primary function. Reference only for potential future AI backend services.***
    *   **Stack:** Python 3.10+, uv, Ruff, Pytest.
    *   **Architecture:** Modular Monolith.
    *   **AI Integration:** Google Gemini API.
    *   **CLI Framework:** Click.

---

## 4. DOCUMENTATION & ARTIFACT GENERATION PROTOCOL
*   **README.md:** Must be a self-contained project operating system, including badges, architecture diagrams, setup instructions, and this AI Agent Directives section.
*   **AGENTS.md:** This document serves as the definitive guide for AI agents interacting with the repository.
*   **LICENSE:** Standardized as **CC BY-NC 4.0**.
*   **Structure:** Maintain a clear, hierarchical file structure.

---

## 5. CODE QUALITY & VERIFICATION MANDATES
*   **Linting & Formatting:** Automated via **Biome** in pre-commit hooks and CI pipeline. All code MUST pass Biome checks.
*   **Type Checking:** **TypeScript strict mode** is MANDATORY. All code must be type-safe.
*   **Testing:** Unit tests (Vitest) and E2E tests (Playwright) are required for all new features and bug fixes. Aim for **>80% code coverage**.
*   **Security Audits:** Regular security reviews and vulnerability scanning (e.g., `npm audit`, browser extension vulnerability scanners) are required.

---

## 6. OPERATIONAL EXCELLENCE
*   **CI/CD:** A robust CI/CD pipeline (`.github/workflows/ci.yml`) must be implemented, covering linting, testing, building, and deployment to extension stores.
*   **Dependency Management:** Use `npm` or `yarn` with strict version pinning where necessary. Regularly update dependencies using `npm outdated` and `npm update`.
*   **Version Control:** **GitFlow** or a similar structured branching strategy. All pull requests must be reviewed and pass all CI checks before merging.

</details>
