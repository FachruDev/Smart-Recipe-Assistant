<h1 align="center"> SMART-RECIPE-ASSISTANT </h1>

<p align="center">
  <img src="https://img.shields.io/github/last-commit/FachruDev/Smart-Recipe-Assistant?style=for-the-badge&logo=github&color=black" alt="Last Commit">
</p>

<h2 align="center"> Built with these technologies: </h2>

<p align="center">
  <a href="https://www.python.org/" target="_blank"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"></a>
  <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"></a>
  <a href="https://www.sqlalchemy.org/" target="_blank"><img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy"></a>
  <a href="https://docs.pydantic.dev/" target="_blank"><img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white" alt="Pydantic"></a>
  <a href="https://gunicorn.org/" target="_blank"><img src="https://img.shields.io/badge/Gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white" alt="Gunicorn"></a>
  <a href="https://nextjs.org/" target="_blank"><img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js"></a>
  <a href="https://www.typescriptlang.org/" target="_blank"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"></a>
  <a href="https://www.javascript.com/" target="_blank"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"></a>
  <a href="https://axios-http.com/" target="_blank"><img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white" alt="Axios"></a>
  <a href="https://react-hook-form.com/" target="_blank"><img src="https://img.shields.io/badge/React%20Hook%20Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white" alt="React Hook Form"></a>
  <a href="https://www.json.org/json-en.html" target="_blank"><img src="https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white" alt="JSON"></a>
  <a href="https://www.npmjs.com/" target="_blank"><img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm"></a>
  <a href="https://eslint.org/" target="_blank"><img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" alt="ESLint"></a>
</p>

---

## Overview

Smart-Recipe-Assistant is an open-source platform for building AI-powered cooking applications—combining seamless recipe generation, interactive chat, and real-time user engagement. The architecture is modular, combining a FastAPI backend and a Next.js frontend, and uses Git submodules for clean code separation and maintainability.

### Why Smart-Recipe-Assistant?

This project simplifies the development of intelligent, modular, and customizable cooking assistants, with the following core features:

## ✨ Core Features

* 🤖 **Ingredient Extraction**: Multimodal AI models to extract ingredients from text or images.
* 🚀 **Recipe Generation & Personalization**: AI-powered, customized recipes based on available ingredients.
* 💬 **Interactive Chat & Session Management**: Real-time chat with contextual memory and state.
* 🧩 **Reusable UI Components**: Highly modular frontend for intuitive user experience.
* 🔒 **Configurable & Secure**: Environment variable and dependency management for each service.

## 📦 Submodule Structure

This repository uses **Git Submodules** to manage backend and frontend independently but in an integrated way. Basic structure:
```
Smart-Recipe-Assistant/
├── backend/    # submodule: Recipe-Ai-backend (FastAPI, Python)
└── frontend/   # submodule: Recipe-Ai-Frontend (Next.js, TypeScript)
```

> **Note:** All backend/frontend development happens inside the respective submodules.

---

## 🚀 Getting Started

To use this repository and its submodules correctly, follow these steps.

### Prerequisites

Make sure you have:
- [Git](https://git-scm.com/) installed

### Cloning with Submodules

**DO NOT** manually clone the backend or frontend folders! Use:

```sh
git clone --recurse-submodules https://github.com/FachruDev/Smart-Recipe-Assistant.git
```

If you already cloned without submodules, initialize them with:
```sh
git submodule update --init --recursive
```

### Forking & Keeping Submodules Updated

1. **Fork this repository on GitHub.**
2. Clone your fork locally with submodules:
    ```sh
    git clone --recurse-submodules https://github.com/<your-username>/Smart-Recipe-Assistant.git
    ```
3. To update submodules if upstream changes:
    ```sh
    git submodule update --remote --merge
    ```

> To contribute to backend or frontend, make changes inside the respective submodule—not in the root repo.

---

## 💻 Local Development

- **Frontend**: Go to `frontend/` and follow its README instructions.
- **Backend**: Go to `backend/` and follow its README instructions.

---

## 🤝 Contributing

We love contributions! Please follow these steps:
1. Fork this repo
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit changes in the appropriate submodule
4. Push and open a Pull Request