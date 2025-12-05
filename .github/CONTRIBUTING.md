# Contributing to ApexWeather-Mobile-CrossPlatform-WeatherApp

Thank you for considering contributing to ApexWeather-Mobile-CrossPlatform-WeatherApp! We aim to foster a collaborative environment where high-quality, professional code is paramount.

## 1. Code of Conduct

This project adheres to the Contributor Covenant Code of Conduct. Please read the full [CODE_OF_CONDUCT.md](https://github.com/chirag127/ApexWeather-Mobile-CrossPlatform-WeatherApp/blob/main/CODE_OF_CONDUCT.md) to understand the expected standards of behavior.

## 2. How to Contribute

We welcome contributions in the form of bug reports, feature requests, documentation improvements, and code contributions. All contributions should align with the project's goal of being a high-velocity, future-proof, and zero-defect application.

### 2.1. Reporting Bugs

1.  **Search Existing Issues:** Before reporting a bug, please check if it has already been reported. Search the existing issues on GitHub.
2.  **Create a New Issue:** If the bug is new, please create a new issue using the **Bug Report** template. Provide as much detail as possible, including:
    *   A clear and concise title.
    *   The environment where the bug occurred (e.g., iOS version, Android version, device model).
    *   Steps to reproduce the bug.
    *   Expected behavior vs. actual behavior.
    *   Relevant screenshots, logs, or error messages.

### 2.2. Suggesting Enhancements

1.  **Search Existing Issues:** Check if a similar feature request already exists.
2.  **Create a New Issue:** If not, create a new issue describing the proposed enhancement. Clearly explain the problem it solves and the benefits it provides.

### 2.3. Submitting Code Contributions

Follow these steps to submit your code:

1.  **Fork the Repository:** Create a fork of the `ApexWeather-Mobile-CrossPlatform-WeatherApp` repository under your GitHub account.
2.  **Clone Your Fork:** Clone your forked repository to your local development machine:
    bash
    git clone https://github.com/chirag127/ApexWeather-Mobile-CrossPlatform-WeatherApp.git
    cd ApexWeather-Mobile-CrossPlatform-WeatherApp
    
3.  **Create a New Branch:** Create a feature branch for your changes. Use a descriptive name (e.g., `feat/add-new-weather-source` or `fix/correct-forecast-display`).
    bash
    git checkout -b your-branch-name
    
4.  **Install Dependencies:** Install project dependencies using Expo CLI.
    bash
    npx expo install
    
5.  **Make Your Changes:** Implement your feature or bug fix. Ensure your code adheres to the project's coding standards and the Apex Tech Stack guidelines (TypeScript, React Native, Expo, Tailwind CSS v4, Biome, Vitest, Playwright).
6.  **Lint and Format:** Ensure your code is clean and well-formatted. Run the linter and formatter:
    bash
    npx @biomejs/biome format --write .
    npx @biomejs/biome lint --apply .
    
7.  **Run Tests:** Ensure all tests pass.
    bash
    npx vitest run
    # For end-to-end tests if applicable
    # npx playwright test
    
8.  **Commit Your Changes:** Commit your changes with clear and concise commit messages.
    bash
    git add .
    git commit -m "feat: Add description for the new weather service API"
    
9.  **Push to Your Fork:** Push your branch to your forked repository.
    bash
    git push origin your-branch-name
    
10. **Open a Pull Request:** Go to the original `ApexWeather-Mobile-CrossPlatform-WeatherApp` repository and open a new Pull Request (PR) from your branch. Ensure the PR template is filled out completely.

### 2.4. Pull Request Guidelines

*   **Descriptive Title and Description:** Clearly state the purpose of the PR and what it addresses.
*   **Link to Issue:** If the PR fixes or implements an issue, link to it in the description (e.g., `Closes #123`).
*   **Code Reviews:** Be prepared to address feedback from code reviewers.
*   **CI/CD:** All PRs will be automatically checked by our CI pipeline. Ensure all checks pass before merging.

## 3. Development Standards & Principles

*   **Technology Stack:** We use TypeScript, React Native, Expo, and Tailwind CSS v4. Stick to these technologies unless a compelling reason exists for deviation.
*   **Architectural Patterns:** Adhere to modern architectural principles like Feature-Sliced Design (FSD), SOLID, DRY, and YAGNI where applicable.
*   **Code Quality:** Write clean, readable, and maintainable code. Prioritize zero-defect development.
*   **Testing:** All new features and bug fixes must include comprehensive tests (unit and/or integration) using Vitest. E2E tests with Playwright should be considered for critical user flows.
*   **Performance:** Optimize for performance and efficient resource usage on mobile devices.

## 4. Repository Structure

Refer to the `README.md` for the current project structure. Contributions should respect and enhance this structure.

## 5. AI AGENT DIRECTIVES

This project is guided by the **APEX TECHNICAL AUTHORITY & ELITE ARCHITECT** AI. Contributions are expected to align with its directives and standards. Refer to the `AGENTS.md` file for detailed information on the AI's operational parameters, tech stack, and verification commands.

By contributing, you agree to uphold these standards and principles.