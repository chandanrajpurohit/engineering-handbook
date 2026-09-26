# Contributing to Technology Documentation

Thank you for your interest in contributing to **technology-docs**! This project aims to be a reliable, structured, and comprehensive reference for developers, engineers, and architects.

---

## 🛠️ How Can You Contribute?

You can contribute in several ways:
- **Add new technology guides**: Document a tool or framework within the relevant category under `docs/`.
- **Improve existing documentation**: Fix typos, clarify explanations, add practical code snippets or architectural diagrams.
- **Add cheat sheets**: Contribute concise reference sheets to `resources/cheat-sheets/`.
- **Add interview questions**: Share real-world questions and architectural scenarios in `resources/interview-questions/`.
- **Add roadmaps**: Update learning tracks in `resources/roadmaps/`.

---

## 📁 Repository Conventions

### Directory Layout
- Each technology lives under its category: `docs/<category>/<technology>/`.
- Each folder must have a `README.md` serving as the main entry point.
- Additional topic files (e.g. `architecture.md`, `commands.md`, `faq.md`) can be added inside the respective technology folder.

### Content Structure
When adding or updating a technology guide, follow this general template:
1. **Title & Badge / One-liner Summary**
2. **Official Documentation Links**
3. **Core Concepts & Architecture**
4. **Getting Started / Hello World Example**
5. **Production Best Practices & Anti-patterns**
6. **Common Commands / Configurations**
7. **References & External Links**

---

## 📝 Markdown Style Guide

- Use standard GitHub Flavored Markdown (GFM).
- Use fenced code blocks with appropriate language tags (`bash`, `python`, `yaml`, `json`, etc.).
- Prefer clean bullet points and tables for comparison.
- Use relative links when referencing other documents within this repository.

---

## 🚀 Contribution Workflow

1. **Fork** the repository and clone your fork locally.
2. **Create a branch** for your feature or fix:
   ```bash
   git checkout -b docs/add-kafka-deep-dive
   ```
3. **Make your changes** following the style and folder conventions.
4. **Commit your changes** with descriptive commit messages:
   ```bash
   git commit -m "docs(kafka): add consumer rebalance and partition guide"
   ```
5. **Push** your branch to your fork:
   ```bash
   git push origin docs/add-kafka-deep-dive
   ```
6. **Open a Pull Request** against the `main` branch with a clear description of your additions.

---

## ⚖️ Code of Conduct

Please adhere to our [Code of Conduct](CODE_OF_CONDUCT.md) in all project interactions.
