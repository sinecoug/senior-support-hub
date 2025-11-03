# 🧭 Senior Support Hub

**Simplifying life’s essential admin for seniors and carers through human insight and AI-powered documentation.**

---

## 📘 Overview
The **Senior Support Hub** is a structured, AI-enhanced knowledge base designed to make complex everyday workflows—like renewing a driving licence, submitting medical reports, or managing public services—clear, accessible, and efficient.

Built in **Markdown** with **MkDocs + Material** for a clean, searchable, and responsive user experience, this project explores how **AI-driven authoring and automation** can transform traditional technical documentation processes.

---

## 🧩 Key Features
- 🧱 **Structured Authoring:** Uses industry-standard task, concept, and reference topic types.
- 🤖 **AI Integration:** Demonstrates practical AI transformations—authoring, review, linting, and publishing.
- 🧭 **Real-World Use Cases:** Begins with the NDLS (National Driver Licence Service) renewal workflow.
- 🧰 **Open, Scalable Stack:** Markdown-first, published via MkDocs Material, deployable through GitHub Pages.
- 📊 **End-to-End Transparency:** Shows human-in-the-loop writing, then AI optimization and automation.

---

## 📂 Repository Structure

    docs/
      index.md
      tasks/
      concepts/
      reference/
    mkdocs.yml
    .gitignore
    .github/workflows/deploy.yml


## 🚀 Getting Started
1. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-username>/senior-support-hub.git
   cd senior-support-hub
1. **Install dependencies:**
     ```bash
   pip install mkdocs-material mkdocs-git-revision-date-localized-plugin
1. **Preview locally:**
     ```bash
   mkdocs serve
Then visit http://127.0.0.1:8000 in your browser.

## 🌍 Deployment
This site is built and deployed automatically using GitHub Actions to GitHub Pages.

For manual local builds:
    ```bash
     mkdocs build

## 💡 Vision
This project is part of a larger initiative to explore how AI and human expertise can co-author clear, trustworthy documentation for digital inclusion—starting with eldercare but extensible to broader accessibility domains.

## 🧠 Credits
Created and maintained by Sinéad Coughlan
© 2025 | Licensed under MIT
