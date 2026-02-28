```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure the development of AI coding agents within this repository are efficient, maintainable, and reliable. Adherence to these principles is mandatory for all development efforts.

## 1. DRY (Don't Repeat Yourself)

*   All functions, classes, and modules should have single, well-defined purposes.
*   Avoid duplicating logic.
*   Refactor existing code whenever possible to eliminate redundancies.
*   Utilize interfaces or abstract classes to promote flexibility and reduce code repetition.

## 2. KISS (Keep It Simple, Stupid)

*   Strive for clarity and conciseness.
*   Minimize complexity where possible.
*   Focus on the essential requirements.
*   Avoid unnecessary abstractions.
*   Write straightforward code that is easy to understand.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module should have one, and only one, reason to change.
*   **Open/Closed Principle:** The system should be extensible without modifying the core implementation.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Each client should be required only for the interface it uses, and no more.
*   **Dependency Inversion Principle:** Higher-level modules should not depend on implementation details; they should depend on abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

*   Only implement functionality that is explicitly required at the current time.
*   Avoid adding features that are not currently needed.
*   Focus on solving the current problem; don't prematurely add complexity.

## 5. Code Structure & Formatting

*   **File Size:** Each file shall not exceed 180 lines of code.  Short files improve readability.
*   **Naming Conventions:**
    *   Functions: Use snake_case.
    *   Classes: Use camelCase.
    *   Modules: Use hyphens in the top level.
    *   Constants: Use lowercase with underscores.
*   **Comments:** Clear, concise comments explaining the *why* not the *what*.
*   **Docstrings:** Provide detailed docstrings for each function, class, and module.
*   **Code Style:** Adhere to a consistent coding style (e.g., PEP 8).  Use a linter (e.g., `flake8`, `black`) for automated style checks.

## 6. Test Coverage & Automation

*   **Unit Tests:**  All functions and classes should be thoroughly tested through unit tests.
*   **Integration Tests:**  Integrate unit tests with the core agent functionality.
*   **Coverage Percentage:**  Aim for 80% minimum test coverage.  Tools like `pytest-cov` can be utilized.
*   **Test Driven Development (TDD):**  Consider adopting a TDD approach, ensuring tests are written before the code.
*   **Test-Driven Development (TDD):**  Every function/class should be tested before implementation.

## 7. Development Process

*   **Version Control:** Use Git for version control.
*   **Code Review:** All code changes shall be reviewed by at least one other team member before merging.
*   **Documentation Updates:**  Any documentation changes must be updated to reflect the changes.
*   **Refactoring:**  Regularly refactor code to improve its structure and readability.
*   **Documentation:** Maintain a comprehensive documentation of the codebase, including API documentation.

## 8.  Specific Considerations for AI Agents

*   All code should be designed to be adaptable to various AI agents and their underlying models.
*   Consider modular design for ease of integration with different AI frameworks.
*   Prioritize clear, verifiable logic to enable easy debugging and reasoning.

## 9.  Content Requirements

*   **Algorithm Design:** Each algorithm should be thoroughly documented and its complexity should be clearly indicated.
*   **Data Handling:** Any data handling should be clearly documented and presented, avoiding excessive detail.
*   **Error Handling:** Implement robust error handling and logging.

These guidelines are designed to foster a robust, maintainable, and efficient development workflow. Compliance with these principles is mandatory for all AGENTS.md file development.
```