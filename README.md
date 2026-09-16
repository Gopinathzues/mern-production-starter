# MERN Production Starter

[![CI Build Check](https://github.com/Gopinathzues/mern-production-starter/actions/workflows/ci.yml/badge.svg)](https://github.com/Gopinathzues/mern-production-starter/actions/workflows/ci.yml)

A modern, highly scalable MERN (MongoDB, Express, React, Node.js) stack starter boilerplate designed for production use. It comes pre-configured with secure JWT authentication, state management, global error handling, dynamic API interceptors, and containerized Docker setup out of the box.

## Key Features
* **Authentication & Authorization:** Secure JWT-based auth with protected route guards and user role management.
* **Frontend Shell:** Powered by React and Vite for sub-second hot module replacement (HMR).
* **Robust Backend:** Express REST API with centralized operational error handling and Mongoose schema modeling.
* **DevOps & Automation:** Multi-container orchestrations via Docker Compose and automated build pipelines via GitHub Actions.
* **Developer Experience:** Concurrent execution scripts for running client and server seamlessly in development.

## Project Structure
```text
mern-production-starter/
├── .github/workflows/   # CI/CD GitHub Actions pipelines
├── client/              # React + Vite frontend application
├── server/              # Express + Node.js REST API backend
├── docker-compose.yml   # Multi-container orchestration config
└── README.md

```

## Getting Started

### 1. Clone or Use Template

Click **"Use this template"** above or clone locally:

```bash
git clone [https://github.com/Gopinathzues/mern-production-starter.git](https://github.com/Gopinathzues/mern-production-starter.git)
cd mern-production-starter

```

### 2. Install Dependencies & Run

```bash
# Install client and server dependencies
cd server && npm install
cd ../client && npm install

```

### Push to GitHub

Run these commands in PowerShell to update your repository:

```powershell
git add README.md
git commit -m "docs: add CI badge and repository structure to README"
git push origin main

```
