<div align="center">

# 🎯 Soc Ops

**Social Bingo for in-person mixers** — find people who match the prompts and get 5 in a row!

[![Java 21](https://img.shields.io/badge/Java-21-ED8B00?logo=openjdk&logoColor=white)](https://adoptium.net/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3-6DB33F?logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![GitHub Pages](https://img.shields.io/badge/Docs-GitHub%20Pages-0969DA?logo=github&logoColor=white)](https://treinamentos-serpro.github.io/copilot-dev-days-rodrigolara/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

🌐 [Português (BR)](README.pt_BR.md) · [Español](README.es.md)

</div>

---

## ✨ What is this?

Soc Ops is a **real-time Social Bingo web app** built with Spring Boot. Each player gets a randomly generated 5×5 bingo board filled with icebreaker prompts. Walk the room, find colleagues who match each square, and race to get five in a row!

It's also a **hands-on GitHub Copilot workshop** — you'll build and extend this app using AI-assisted development techniques across four guided labs.

---

## 🚀 Quick Start

**Prerequisites:** [Java 21+](https://adoptium.net/) and [Maven 3.9+](https://maven.apache.org/)

```bash
cd socops
./mvnw spring-boot:run
```

Then open **http://localhost:8080** in your browser. Each page load generates a fresh bingo board!

---

## 📚 Workshop Labs

| Lab | Title | What you'll do |
|-----|-------|----------------|
| [**00**](workshop/00-overview.md) | Overview & Checklist | Get oriented and verify your setup |
| [**01**](workshop/01-setup.md) | Setup & Context Engineering | Configure Copilot and explore the codebase |
| [**02**](workshop/02-design.md) | Design-First Frontend | Redesign the UI guided by Copilot |
| [**03**](workshop/03-quiz-master.md) | Custom Quiz Master | Build a custom agent to generate bingo prompts |
| [**04**](workshop/04-multi-agent.md) | Multi-Agent Development | Orchestrate multiple agents for complex tasks |

> 📖 **[Open the full Lab Guide →](workshop/GUIDE.md)**

---

## 🛠️ Development

```bash
# Run tests
cd socops && ./mvnw test

# Build a JAR
cd socops && ./mvnw clean package
```

The workshop docs deploy automatically to **GitHub Pages** on every push to `main`.

---

## 🤝 Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines. Please review the [Code of Conduct](CODE_OF_CONDUCT.md) before opening issues or pull requests.
