## PyBe-learning-platform

PyBe is a **scenario-driven Python learning prototype** that helps learners improve their Python programming and problem-solving skills through interactive learning sessions.

The application is built using the **MERN Stack** with a **React + Vite frontend**, an **Express + Node.js backend**, and **JSON-based local data storage**. It is designed as a prototype, so no authentication or external database is required.

This project is being developed collaboratively as part of the **Vicharanashala Summer Internship**.

---

## ✨ Features

- 📚 Scenario-based Python learning
- 🔍 Browse scenarios with search and filters
- 🎯 Difficulty-based learning
- 💬 Interactive learning sessions
- 🧠 Abstraction mapping
- 📝 Python construct generation
- 📊 Progress dashboard
- 📈 Learning analytics
- 💡 Reflection and feedback
- 🗂 JSON-backed local API
- 🛣 Learning roadmap

---

# 🛠 Tech Stack

### Frontend
- React.js
- Vite
- JavaScript
- CSS

### Backend
- Node.js
- Express.js

### Data Storage
- JSON Files

### Version Control
- Git
- GitHub

---

# 📂 Repository Structure

```text
pybe/
│
├── docs/
│   ├── screenshots/
│   ├── architecture.md
│   ├── api.md
│   ├── setup.md
│   └── roadmap.md
│
├── .github/
│   ├── ISSUE_TEMPLATE/
│   └── PULL_REQUEST_TEMPLATE.md
│
├── README.md
├── PRODUCT.md
├── CONTRIBUTING.md
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
└── LICENSE

```

> **Note:** The `client/` and `server/` folders containing the application source code will be added during development.

---

# ⚙️ Prerequisites

Before running the project, make sure you have:

- Node.js (v18 or above)
- npm

---

# 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/gunjancodes/pybe.git
```

### Move to the project directory

```bash
cd pybe
```

### Install all dependencies

```bash
npm run installAll
```

### Configure environment variables

```bash
cp server/.env.example server/.env
```

### Seed sample data

```bash
npm run seed
```

### Start the application

```bash
npm run dev
```

---

# 🌐 Local Development

Frontend

```
http://localhost:5173
```

Backend API

```
http://localhost:5000/api
```

---

# 📖 Documentation

Project documentation is available in the **docs** folder.

- Architecture
- API Documentation
- Setup Guide
- Roadmap
- Screenshots

---

# 🤝 Contributing

We follow a collaborative GitHub workflow.

- Create a new feature branch from `develop`
- Make your changes
- Commit with meaningful messages
- Push your branch
- Open a Pull Request
- Wait for review before merging

⚠️ Direct commits to the **main** branch are not allowed.

For complete guidelines, see **CONTRIBUTING.md**.

---

# 🌿 Branch Strategy

```
main
│
└── develop
      │
      ├── feature/login
      ├── feature/dashboard
      ├── feature/session
      ├── feature/api
      └── fix/navbar
```

- **main** → Stable production-ready code
- **develop** → Active development
- **feature/** → New features
- **fix/** → Bug fixes
- **docs/** → Documentation updates

---

# 📸 Screenshots

Application screenshots will be added as development progresses.

---

# 🗺 Roadmap

Upcoming improvements include:

- Interactive learning enhancements
- Dashboard improvements
- UI refinements
- API enhancements
- Documentation updates

---

# 👥 Team

Developed collaboratively by the project team during the **Vicharanashala Summer Internship**.

Team member details will be updated soon.

---

# 📄 License

This project is licensed under the **MIT License**.
