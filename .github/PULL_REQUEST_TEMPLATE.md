# Pull Request Template

## 🚀 Feature / Fix

(Please describe the changes made in this pull request. Be specific and concise.)

--- 

## 📝 Checklist

Before submitting your pull request, please ensure:

*   [ ] My code follows the project's style guidelines.
*   [ ] I have performed a self-review of my own code.
*   [ ] I have commented my code, particularly in hard-to-understand areas.
*   [ ] I have made corresponding changes to the documentation (if applicable).
*   [ ] My changes generate no new warnings or errors.
*   [ ] I have added tests that prove my fix is effective or that my feature works.
*   [ ] New and existing unit tests pass locally with my changes.
*   [ ] Any dependent changes have been merged and published.

--- 

## 💡 Technical Alignment & Validation

*   **Architectural Integrity:** Does this PR align with the established architectural patterns (e.g., FSD for extensions, Modular Monolith for Python) and the principles outlined in `AGENTS.md`?
*   **Apex Toolchain Adherence:** Have the latest versions of the Apex toolchain (Vite, TypeScript, Biome, Vitest, Playwright for extensions; uv, Ruff, Pytest for Python) been considered and utilized appropriately?
*   **Security & Compliance:** Does this PR introduce any security vulnerabilities or violate any compliance standards (e.g., CC BY-NC license)?
*   **Testing Strategy:** Have appropriate tests (unit, integration, E2E where applicable) been included or updated to cover the changes? Are test commands defined in `AGENTS.md` executable and passing?
*   **Code Quality:** Has the code been linted and formatted using the prescribed tools (Biome/Ruff)?

--- 

## 🔗 Related Issues

(Link to any relevant GitHub issues this PR addresses. e.g., `Closes #123`)

--- 

## 📜 License & Contribution

By submitting this pull request, I agree to the terms of the **CC BY-NC 4.0 License** and the contribution guidelines in **`.github/CONTRIBUTING.md`**.
