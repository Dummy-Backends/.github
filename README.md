# 🧪 Dummy-Backends

**Dummy backends for backend testing – mock, simulate, and accelerate your development.**

[![Organization](https://img.shields.io/badge/GitHub-Dummy--Backends-181717?style=flat&logo=github)](https://github.com/Dummy-Backends)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

---

## 🚀 What is Dummy-Backends?

**Dummy-Backends** is a collection of lightweight, plug‑and‑play mock backend services designed for frontend developers, QA engineers, and backend teams who need to:

- **Test frontend applications** without a live backend.
- **Simulate API responses** for various scenarios (success, error, edge cases).
- **Speed up development** by decoupling frontend and backend work.
- **Run integration tests** in CI/CD pipelines without external dependencies.

Each repository in this organization provides a ready‑to‑run dummy backend for a specific protocol or use case – REST, GraphQL, WebSocket, gRPC, and more.

---

## 📦 Available Dummy Backends

| Repository | Description | Tech Stack |
|------------|-------------|------------|
| [dummy-rest](https://github.com/Dummy-Backends/dummy-rest) | RESTful API mock with configurable routes and responses | Node.js / Express |
| [dummy-graphql](https://github.com/Dummy-Backends/dummy-graphql) | GraphQL server with dynamic schema and resolvers | Apollo Server / TypeScript |
| [dummy-websocket](https://github.com/Dummy-Backends/dummy-websocket) | WebSocket echo server and event simulator | Node.js / ws |
| [dummy-grpc](https://github.com/Dummy-Backends/dummy-grpc) | gRPC mock server with predefined proto services | gRPC / Python |
| [dummy-auth](https://github.com/Dummy-Backends/dummy-auth) | OAuth2 / JWT authentication mock | Go / Gin |
| [dummy-database](https://github.com/Dummy-Backends/dummy-database) | In‑memory database with RESTful CRUD operations | Python / Flask |

> 👉 **More backends are under active development** – check back often or [request a new one](https://github.com/Dummy-Backends/.github/issues).

---

## 🧰 Getting Started

### 1. Choose a backend

Browse the [repositories](https://github.com/orgs/Dummy-Backends/repositories) and pick the one that matches your testing needs.

### 2. Run it locally

Each repository includes a `README.md` with specific setup instructions. Typically, it’s as simple as:

```bash
git clone https://github.com/Dummy-Backends/<repo-name>.git
cd <repo-name>
npm install   # or pip install, go mod, etc.
npm start     # or python app.py, go run, etc.
```

### 3. Configure your frontend
Point your frontend application to `http://localhost:PORT` (or the port specified in the backend’s docs). You can now develop and test against a realistic API.

### 4. Customise responses
Most backends support configuration via environment variables, JSON files, or query parameters – allowing you to simulate different data shapes, status codes, and latencies.

---

## 📄 License
All repositories in this organization are licensed under the MIT License unless otherwise stated. See the `LICENSE` file in each repository for details.

---
