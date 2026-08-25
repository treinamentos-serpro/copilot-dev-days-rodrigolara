<!-- l10n-sync: source-file="README.md" -->
<div align="center">

# 🎯 Soc Ops

**Social Bingo para encontros presenciais** — encontre pessoas que correspondam às perguntas e faça 5 em linha!

[![Java 21](https://img.shields.io/badge/Java-21-ED8B00?logo=openjdk&logoColor=white)](https://adoptium.net/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3-6DB33F?logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![GitHub Pages](https://img.shields.io/badge/Docs-GitHub%20Pages-0969DA?logo=github&logoColor=white)](https://treinamentos-serpro.github.io/copilot-dev-days-rodrigolara/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

🌐 [English](README.md) · [Español](README.es.md)

</div>

---

## ✨ O que é isso?

Soc Ops é um **aplicativo web de Social Bingo em tempo real** construído com Spring Boot. Cada jogador recebe um tabuleiro 5×5 gerado aleatoriamente com perguntas para quebrar o gelo. Circule pela sala, encontre colegas que correspondam a cada quadrado e ganhe quem fizer cinco em linha primeiro!

É também um **workshop prático de GitHub Copilot** — você vai construir e estender este app usando técnicas de desenvolvimento assistido por IA em quatro laboratórios guiados.

---

## 🚀 Início Rápido

**Pré-requisitos:** [Java 21+](https://adoptium.net/) e [Maven 3.9+](https://maven.apache.org/)

```bash
cd socops
./mvnw spring-boot:run
```

Abra **http://localhost:8080** no navegador. Cada carregamento de página gera um tabuleiro novo!

---

## 📚 Laboratórios do Workshop

| Lab | Título | O que você vai fazer |
|-----|--------|----------------------|
| [**00**](workshop/pt_BR/00-overview.md) | Visão Geral & Lista Rápida | Orientação e verificação do ambiente |
| [**01**](workshop/pt_BR/01-setup.md) | Configuração & Engenharia de Contexto | Configure o Copilot e explore o código |
| [**02**](workshop/pt_BR/02-design.md) | Frontend Design-First | Redesenhe a interface guiado pelo Copilot |
| [**03**](workshop/pt_BR/03-quiz-master.md) | Quiz Master Personalizado | Crie um agente para gerar perguntas de bingo |
| [**04**](workshop/pt_BR/04-multi-agent.md) | Desenvolvimento Multi-Agente | Orquestre múltiplos agentes para tarefas complexas |

> 📖 **[Abrir o Guia Completo do Lab →](workshop/pt_BR/GUIDE.md)**

---

## 🛠️ Desenvolvimento

```bash
# Executar testes
cd socops && ./mvnw test

# Gerar JAR
cd socops && ./mvnw clean package
```

A documentação do workshop é publicada automaticamente no **GitHub Pages** a cada push para `main`.

---

## 🤝 Contribuição

Veja [CONTRIBUTING.md](CONTRIBUTING.md) para orientações. Leia o [Código de Conduta](CODE_OF_CONDUCT.md) antes de abrir issues ou pull requests.
