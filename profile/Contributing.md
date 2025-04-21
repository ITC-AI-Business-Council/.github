# Contributing to ITC AI Business Council Repositories

Thank you for your interest in contributing! We value every bit of help—from typo fixes to new workflow templates. This guide will walk you through the process of opening issues, submitting pull requests, and helping us keep everything organized.

---

## 🛠 Getting Started

1. **Fork & Clone**  
   ```bash
   git clone git@github.com:ITC-AI-Business-Council/.github.git
   cd .github
   ```

2. **Create a Branch**  
   Use a descriptive branch name:  
   ```bash
   git checkout -b feature/add-new-template
   git checkout -b fix/typo-in-code-of-conduct
   ```

3. **Install Dependencies (if any)**  
   > Most of our org‑wide tools are Markdown/YAML‑only.  
   > If you add scripts or Actions that require local testing, list any prerequisites here.

---

## 📋 Issue Guidelines

- **Search first**: Check [existing issues](https://github.com/ITC-AI-Business-Council/.github/issues) before opening a new one.  
- **Use templates**: Click **“New issue”** and select an appropriate template (bug report, feature request, or question).  
- **Be descriptive**:  
  - **Title**: short summary (e.g. `Add issue template for security disclosures`)  
  - **Body**: include steps to reproduce (for bugs), proposed behavior (for features), and any relevant context.

---

## 🛠 Pull Request Process

1. **Branch off** from `main` using the naming conventions above.  
2. **Work on your changes**, making sure to:  
   - Follow existing file structure and naming.  
   - Keep pull requests focused (one logical change per PR).  
3. **Commit messages** should follow this style:  
   ```text
   <type>(<scope>): <short description>

   [optional detailed explanation and motivation]
   ```
   - **type**: `feat` (new feature), `fix` (bugfix), `docs` (documentation), `chore` (maintenance), `refactor`, etc.  
   - **scope**: area affected (e.g. `pull_request_template`, `ci`, `security`).  
   - **short description**: imperative, under 50 characters.

4. **Push & Open PR**  
   ```bash
   git push origin feature/add-new-template
   ```
   - Go to GitHub and open a pull request against `ITC-AI-Business-Council/.github:main`.  
   - Select the **“Pull Request”** template if one applies.  
   - Reference any related issues: `Closes #123`.

5. **Review & Iterate**  
   - Maintainers will review within 48 hours.  
   - Address review feedback by pushing additional commits to your branch.  
   - Once approved, a maintainer will merge your PR.

---

## 🧹 Coding & Style Conventions

- **Markdown**  
  - Use [GitHub-flavored Markdown](https://guides.github.com/features/mastering-markdown/).  
  - Wrap lines at ~~80 characters.  
  - Use fenced code blocks with language specifiers (```yaml```, ```bash```, ```markdown```).

- **YAML** (for workflows & templates)  
  - 2‑space indentation.  
  - Keys in `snake_case` when possible.  
  - Comments sparingly—aim for self‑documenting names.

- **Scripts & Actions**  
  - If you add scripts (e.g. `.sh`, `.js`), include a header describing purpose, usage, and license.  
  - Ensure executables have the proper shebang and file permissions.

---

## 🔒 Security & Sensitive Data

- **Never commit** credentials, tokens, or private keys.  
- If you discover a vulnerability in one of our templates or workflows, see [SECURITY.md](SECURITY.md) for private reporting steps.

---

## 📣 Communication & Support

- **Real-time questions**: Ping `@ITC-AI-Business-Council/maintainers` in a GitHub issue or organization discussion.  
- **Major proposals**: Before investing significant work (e.g., new top-level workflow), open an **“RFC”** issue to gather community feedback.

---

## 🎉 Thank You!

Your contributions help keep our community running smoothly and ensure every ITC AI Business Council repo adheres to best practices. We appreciate your time and expertise!

<sub>Made with ❤️ by the ITC AI Business Council maintainers.</sub>
```
