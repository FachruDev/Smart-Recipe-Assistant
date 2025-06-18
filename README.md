<h1 align="center"> SMART-RECIPE-ASSISTANT </h1>

<p align="center">
  <img src="https://img.shields.io/github/last-commit/FachruDev/Smart-Recipe-Assistant?style=for-the-badge&logo=github&color=black" alt="Last Commit">
  <img src="https://img.shields.io/github/languages/top/FachruDev/Smart-Recipe-Assistant?style=for-the-badge&color=3399ff" alt="Top Language">
  <img src="https://img.shields.io/github/languages/count/FachruDev/Smart-Recipe-Assistant?style=for-the-badge&color=007ec6" alt="Languages">
</p>

<h2 align="center"> Built with the tools and technologies: </h2>

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
  <a href="https://www.docker.com/" target="_blank"><img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"></a>
  <a href="https://www.json.org/json-en.html" target="_blank"><img src="https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white" alt="JSON"></a>
  <a href="https://www.npmjs.com/" target="_blank"><img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm"></a>
  <a href="https://eslint.org/" target="_blank"><img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" alt="ESLint"></a>
</p>

---

## Overview

Smart-Recipe-Assistant is an open-source platform designed to help developers build AI-powered culinary applications with seamless recipe generation, interactive chat, and real-time user engagement. Its robust architecture combines a FastAPI backend with multimodal AI services and a dynamic frontend, enabling personalized cooking experiences.

### Why Smart-Recipe-Assistant?

This project simplifies the development of intelligent cooking assistants by providing a comprehensive, modular toolkit. The core features include:

## ✨ Core Features

* 🤖 **AI Ingredient Extraction**: Leverages multimodal models to identify ingredients from text or images, streamlining recipe creation.
* 🚀 **Recipe Generation & Personalization**: Generates tailored recipes based on available ingredients, enhancing user engagement.
* 💬 **Interactive Chat & Session Management**: Supports real-time conversations with contextual understanding for a natural user experience.
* 📦 **Containerized Deployment**: Ensures consistent environments with Docker and docker-compose, facilitating reliable deployment.
* 🧩 **Reusable UI Components**: Offers a suite of frontend components for building intuitive, responsive interfaces.
* 🔒 **Secure & Configurable**: Manages environment variables and dependencies for flexible, secure integrations.

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Make sure you have the following software installed:
* [Git](https://git-scm.com/)
* [Docker](https://www.docker.com/products/docker-desktop/)
* [Docker Compose](https://docs.docker.com/compose/install/)

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/FachruDev/Smart-Recipe-Assistant.git](https://github.com/FachruDev/Smart-Recipe-Assistant.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd Smart-Recipe-Assistant
    ```
3.  **Create a `.env` file:**
    Copy the `.env.example` file to `.env`. Fill in the necessary environment variables such as API keys, database configuration, etc.
    ```sh
    cp .env.example .env
    ```
4.  **Run with Docker Compose:**
    This command will build the images and run all the necessary services.
    ```sh
    docker-compose up --build
    ```

## 💻 Usage

After the installation is complete, the application will be accessible:
* **Frontend**: Open your browser and navigate to `http://localhost:3000`
* **Backend API Docs**: Interactive API documentation (Swagger UI) is available at `http://localhost:8000/docs`

## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
