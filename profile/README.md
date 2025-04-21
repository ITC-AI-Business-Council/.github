# ITC AI Business Council · Organization Meta

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](./LICENSE)

A central repository of community guidelines, templates, workflows, and shared assets for the  
**ITC AI Business Council** GitHub organization.

---

## 📖 Table of Contents

1. [About](#about)  
2. [What’s Here](#whats-here)  
3. [Getting Started](#getting-started)  
4. [Contributing](#contributing)  
5. [Support & Reporting Issues](#support--reporting-issues)  
6. [License](#license)  

---

## 🏢 About

The ITC AI Business Council is a global chamber of commerce under the International Trade Council that  
brings together enterprises, SMEs, startups, and policy makers to share best practices, tools, and  
actionable insights around artificial intelligence in international trade, supply chains, and global policy.

This repository lives in `.github/` at the org level so that:

- **Issue & PR templates** are standardized across every repo  
- **GitHub Actions workflows** (CI, release, security scans, etc.) can be centrally managed  
- **Community & security policies**, code of conduct, and contributing guidelines are consistent  
- **Shared assets** (logos, badges, scripts) are available to all projects  

---

## 📂 What’s Here

- **`ISSUE_TEMPLATE/`** & **`PULL_REQUEST_TEMPLATE/`** — standardized templates  
- **`workflows/`** — GitHub Actions workflows you can reference via `uses: ITC-AI-Business-Council/.github/.github/workflows/...`  
- **`CODE_OF_CONDUCT.md`** — our community code of conduct  
- **`CONTRIBUTING.md`** — how to propose changes to council repos and this org‑wide config  
- **`SECURITY.md`** — vulnerability reporting guidelines  
- **`assets/`** — shared badges, logos, scripts, etc.  

---

## 🚀 Getting Started

1. **Browse Templates**  
   - Copy or link from `.github/ISSUE_TEMPLATE/` or `.github/PULL_REQUEST_TEMPLATE/` into your project.  
2. **Adopt Workflows**  
   - In your repo’s `.github/workflows/` add:
     ```yaml
     name: CI
     on: [push, pull_request]
     jobs:
       build:
         uses: ITC-AI-Business-Council/.github/.github/workflows/ci.yml@main
     ```
3. **Follow the Guidelines**  
   - Read our [Code of Conduct]([CODE_OF_CONDUCT.md](https://github.com/ITC-AI-Business-Council/.github/blob/main/CODE_OF_CONDUCT.MD)) and [Contributing Guide](CONTRIBUTING.md) before opening issues or PRs.  
4. **Security First**  
   - If you discover a vulnerability, see [SECURITY.md](SECURITY.md) for private disclosure instructions.  

---

## 🤝 Contributing

We welcome all members of the AI Business Council community to help improve these templates and workflows:

1. Fork this repo.  
2. Create a branch: `git checkout -b feature/your-change`  
3. Make your edits (see each `.md` for style guidelines).  
4. Commit and push: `git commit -m "feat: add X template"`  
5. Open a pull request against `main`.  

See [CONTRIBUTING.md](CONTRIBUTING.md) for full details.

---

## 🆘 Support & Reporting Issues

If you encounter problems or have suggestions for improvements, please:

1. Check existing issues for similar requests.  
2. Open a new issue in **this** repo under the appropriate template.  
3. Tag `@ITC-AI-Business-Council/maintainers` for priority attention.  

---

## 📄 License

This repo and its contents are licensed under the **Apache License 2.0**—see [LICENSE](LICENSE) for details.
