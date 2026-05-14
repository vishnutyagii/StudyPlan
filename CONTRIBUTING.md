# Contributing to StudyPlan 📚
Thank you for your interest in contributing to **StudyPlan** — an application designed to automatically organize tasks, schedules, and study plans. We welcome contributions from the community, especially **GSSoC contributors**!

---

## 🗺️ Table of Contents
- [GSSoC Contributors — Start Here](#-gssoc-contributors--start-here)
- [Getting Started](#-getting-started)
- [System Architecture](#-system-architecture)

---

## 🏅 GSSoC Contributors — Start Here

Welcome to GSSoC! Here's how the contribution flow works for this project:

1. **Fork** the repository to your own GitHub account (button at top-right of the repo page).
2. **Clone your fork** locally — never clone the upstream repo directly.
3. Work on a **feature branch** (not `main`) in your fork.
4. Open a **Pull Request from your fork's branch → `StudyPlan/StudyPlan:main`**.
5. A maintainer will review and approve your PR.

---

## 🚀 Getting Started
1. **Fork** the repository on GitHub.
2. **Clone** your fork:
    ```bash
   git clone https://github.com/<your-username>/StudyPlan.git
   cd StudyPlan
   ```
3. **Add upstream remote** so you can stay in sync:
   ```bash
   git remote add upstream https://github.com/Charushi06/StudyPlan
   git fetch upstream
   ```
4. **Create a feature branch** from `main`:
   ```bash
   git checkout -b your-feature/issue-name
   ```

---

## 🧠 System Architecture

```text
Frontend (Vanilla JS UI)
↓
Node.js Express API
↓
AI Layer (Gemini API)
↓
SQLite Database
↓
State Management + UI Sync
```