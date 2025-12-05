# Contribution Guidelines for ClimaCast-RealTime-Weather-Mobile-App

Welcome to the Apex repository! We seek contributions that enhance performance, strictly enforce TypeScript, and refine meteorological data visualization. As an Apex project, contributions must meet **zero-defect, high-velocity, future-proof** standards.

This project adheres to the principles outlined in **AGENTS.md**, specifically regarding the architectural patterns (SOLID, DRY) and the strict use of the **React Native / Expo / TypeScript (Strict)** toolchain.

## 1. Code of Conduct

This project adheres to the Contributor Covenant Code of Conduct. All contributors must adhere to its principles. Be respectful, constructive, and professional in all interactions.

## 2. Workflow: The Apex Loop

We enforce a strict workflow to maintain architectural integrity:

1.  **Triage:** Review existing issues or create a new one clearly defining the proposed change (Bug, Feature, Refactor).
2.  **Branching:** Create a new feature branch off `main`: `git checkout -b feature/short-description-of-change`.
3.  **Development:** Implement changes adhering strictly to TypeScript 6.x compiler flags and FSD (Feature-Sliced Design) principles where applicable.
4.  **Verification:** Ensure all changes pass local linting/formatting checks and that relevant **Vitest** unit tests pass. New features **MUST** include comprehensive testing.
5.  **Pull Request (PR):** Open a Pull Request against `main`. The PR **MUST** link back to the original issue.
6.  **Review:** Expect rigorous review from maintainers focusing on performance profiling, strict typing adherence, and architectural conformity.

## 3. Branching Strategy

We use a simplified Git Flow based on stability:

*   `main`: Production-ready, stable code. Protected branch.
*   `develop`: Integration branch for features slated for the next release. (Maintainers only).
*   `feature/*`: For new features or significant enhancements.
*   `fix/*`: For critical bug fixes.
*   `refactor/*`: For non-functional improvements (style, architecture, performance tuning).

## 4. Technical Standards Enforcement

Contributors must ensure their changes do not degrade the quality metrics tracked by our CI pipeline (`.github/workflows/ci.yml`).

### TypeScript Strictness

*   **Mandatory:** All new files must be maximally strict. Compiler options in `tsconfig.json` must reflect the highest level of type safety.
*   **No `any` Allowed:** The use of the `any` type is strictly prohibited unless explicitly documented and justified as a last resort for external interoperability (and still requires maintainer approval).

### Testing & Coverage

*   **Vitest:** All new logic, hooks, components, and utility functions must have corresponding unit tests.
*   **Coverage Gate:** The CI pipeline enforces a minimum coverage threshold (Check `ci.yml` for the current required percentage). Contributions that lower coverage will be blocked.

### State Management

*   Adhere to established patterns for state management (e.g., using Redux Toolkit, Zustand, or React Context appropriately). **DRY** principle heavily applies here; avoid redundant state stores.

## 5. Reporting Issues and Features

If you discover a bug or have an idea for a new feature, please use the provided GitHub Issue Templates (`.github/ISSUE_TEMPLATE/bug_report.md`).

When reporting, please provide:

1.  Steps to reproduce (for bugs).
2.  Expected vs. Actual behavior.
3.  Your current environment details (Device/OS/Expo SDK Version if known).

## 6. Repository Ownership

By contributing code, you agree that your submissions will be licensed under the **CC BY-NC 4.0 License**, as specified in the root `LICENSE` file. See the **SECURITY.md** file for details on responsible disclosure.