# StepSense-Health-Tracking-Mobile-App

![Build Status](https://img.shields.io/github/actions/workflow/user/chirag127/StepSense-Health-Tracking-Mobile-App/ci.yml?style=flat-square&logo=githubactions)
![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/StepSense-Health-Tracking-Mobile-App?style=flat-square&logo=codecov)
![Tech Stack](https://img.shields.io/badge/tech-stack-TypeScript%2CRN%2CExpo-blue?style=flat-square&logo=typescript)
![Lint Status](https://img.shields.io/badge/lint-Biome-orange?style=flat-square&logo=biome)
![License](https://img.shields.io/badge/license-CC%20BY--NC%204.0-red?style=flat-square&logo=creativecommons)
![GitHub Stars](https://img.shields.io/github/stars/chirag127/StepSense-Health-Tracking-Mobile-App?style=flat-square&logo=github)

<p align="center">
  <a href="https://github.com/chirag127/StepSense-Health-Tracking-Mobile-App/stargazers">
    <img src="https://img.shields.io/github/stars/chirag127/StepSense-Health-Tracking-Mobile-App?style=social" alt="GitHub Stars" />
  </a>
</p>

## Project Overview

StepSense is a sophisticated, cross-platform mobile application engineered with Expo and React Native, utilizing TypeScript for enhanced developer experience and code robustness. It meticulously tracks daily step counts and activity levels, providing users with actionable insights into their physical well-being.

## Architecture

mermaid
graph TD
  A[Client (Expo/React Native)] --> B(API Layer)
  B --> C{Core Logic Module}
  C --> D[Data Storage (AsyncStorage/SQLite)]
  C --> E(Device Sensors/HealthKit/GoogleFit)
  E --> C
  D --> C


## Table of Contents

*   [Project Overview](#project-overview)
*   [Architecture](#architecture)
*   [Table of Contents](#table-of-contents)
*   [🤖 AI Agent Directives](#ai-agent-directives)
*   [Development Standards](#development-standards)
*   [Setup & Installation](#setup--installation)
*   [Contributing](#contributing)
*   [License](#license)

## 🤖 AI Agent Directives

<details>
<summary>View Agent Directives</summary>

## SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

### 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

### 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

### 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type and apply the **Apex Toolchain**. This repository, `StepSense-Health-Tracking-Mobile-App`, is a TypeScript-based mobile application.

*   **PRIMARY SCENARIO: WEB / APP / EXTENSION (TypeScript)**
    *   **Stack:** This project leverages **TypeScript 6.x (Strict)**. Development is powered by **Expo 7.x** for cross-platform capabilities and **React Native 0.75+** for native UI components. **Vite 7 (Rolldown)** is used for rapid development builds. State management employs **Signals (Standardized)**.
    *   **Linting & Formatting:** **Biome 1.x** is the standard for ultra-fast linting and code formatting.
    *   **Testing:** **Vitest 2.x** for unit testing and **Playwright 1.x** for end-to-end testing.
    *   **Architecture:** Adheres to **Feature-Sliced Design (FSD)** principles for modularity and maintainability.

*   **SECONDARY SCENARIO B: SYSTEMS / PERFORMANCE (Rust/Go) - *Not applicable.***
*   **TERTIARY SCENARIO C: DATA / AI / SCRIPTS (Python) - *Not applicable.***

### 4. CODE INTEGRITY & QUALITY
*   **SOLID Principles:** Enforce Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion.
*   **DRY (Don't Repeat Yourself):** Eliminate redundant code. Abstract common logic.
*   **YAGNI (You Ain't Gonna Need It):** Implement only necessary features. Avoid premature optimization or complexity.
*   **KISS (Keep It Simple, Stupid):** Favor straightforward solutions.

### 5. TESTING & VERIFICATION
*   **Unit Tests:** **Vitest** must be used. Aim for >85% code coverage.
*   **Integration Tests:** Covered by Vitest or Playwright where applicable.
*   **End-to-End (E2E) Tests:** **Playwright** is mandatory for critical user flows. All E2E tests must be executed in a CI environment.
*   **Verification Commands:**
    *   `pnpm install` (or `npm install`)
    *   `pnpm run lint` (or `npm run lint`)
    *   `pnpm run test` (or `npm run test`)
    *   `pnpm run e2e` (or `npm run e2e`)

### 6. SECURITY MANDATES (DECEMBER 2025)
*   **Dependency Scanning:** Integrate `npm audit` / `yarn audit` / `pnpm audit` into CI. Regularly update dependencies.
*   **Secrets Management:** **NEVER** hardcode secrets. Use environment variables or dedicated secret management solutions.
*   **Input Validation:** Sanitize and validate all user inputs to prevent injection attacks.
*   **Secure Defaults:** Employ secure configurations for all libraries and frameworks.

### 7. ARCHIVAL PROTOCOL (RETIRED PRODUCT STANDARD)
*   **Dignified Retirement:** Archived repositories are "Retired Products," not junk. Metadata (Name, Description, Topics) must remain professional and descriptive.
*   **Full Documentation:** Even retired projects must retain comprehensive READMEs, licenses, and architectural documentation.

### 8. AGENTS.MD - DYNAMIC ADAPTATION
This document (`AGENTS.md`) will be dynamically updated to reflect the specific technology stack and architectural patterns of the **current repository**. For `StepSense-Health-Tracking-Mobile-App`, this includes:
*   **Language:** TypeScript 6.x (Strict)
*   **Framework:** Expo 7.x, React Native 0.75+
*   **Build Tool:** Vite 7 (Rolldown)
*   **Linter/Formatter:** Biome 1.x
*   **Testing:** Vitest 2.x (Unit), Playwright 1.x (E2E)
*   **Architecture:** Feature-Sliced Design (FSD)

</details>

## Development Standards

*   **Principles:** SOLID, DRY, YAGNI, KISS
*   **Language:** TypeScript 6.x (Strict Mode Enabled)
*   **Framework:** Expo 7.x, React Native 0.75+
*   **Linting & Formatting:** Biome 1.x
*   **Testing:** Vitest 2.x (Unit), Playwright 1.x (E2E)
*   **Architecture:** Feature-Sliced Design (FSD)

## Setup & Installation

Follow these steps to set up the project locally:

1.  **Clone the Repository:**
    bash
    git clone https://github.com/chirag127/StepSense-Health-Tracking-Mobile-App.git
    cd StepSense-Health-Tracking-Mobile-App
    

2.  **Install Dependencies:**
    We use `pnpm` for efficient package management. If you don't have it installed, run `npm install -g pnpm`.
    bash
    pnpm install
    

3.  **Running the Development Server:**
    Start the Expo development server:
    bash
    pnpm start
    
    Or, to run on a specific platform:
    bash
    pnpm expo:run:ios
    pnpm expo:run:android
    

## Scripts

| Script        | Description                                     |
|---------------|-------------------------------------------------|
| `pnpm lint`   | Run Biome linter and formatter                  |
| `pnpm test`   | Run Vitest unit tests                           |
| `pnpm test:e2e` | Run Playwright end-to-end tests                 |
| `pnpm start`  | Start the Expo development server               |
| `pnpm expo:run:ios` | Run the app on an iOS simulator/device        |
| `pnpm expo:run:android` | Run the app on an Android emulator/device | 

## Contributing

Contributions are welcome! Please follow these guidelines:

1.  Fork the repository.
2.  Create a new branch for your feature (`git checkout -b feature/your-feature-name`).
3.  Commit your changes (`git commit -m 'Add some feature'`).
4.  Push to the branch (`git push origin feature/your-feature-name`).
5.  Open a Pull Request.

Please ensure all code adheres to the project's standards and passes all tests.

## License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license. See the [LICENSE](LICENSE) file for more details.
