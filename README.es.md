<!-- l10n-sync: source-file="README.md" -->
<div align="center">

# 🎯 Soc Ops

**Social Bingo para encuentros presenciales** — ¡encuentra personas que coincidan con las preguntas y consigue 5 en línea!

[![Java 21](https://img.shields.io/badge/Java-21-ED8B00?logo=openjdk&logoColor=white)](https://adoptium.net/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3-6DB33F?logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![GitHub Pages](https://img.shields.io/badge/Docs-GitHub%20Pages-0969DA?logo=github&logoColor=white)](https://treinamentos-serpro.github.io/copilot-dev-days-rodrigolara/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

🌐 [English](README.md) · [Português (BR)](README.pt_BR.md)

</div>

---

## ✨ ¿Qué es esto?

Soc Ops es una **aplicación web de Social Bingo en tiempo real** construida con Spring Boot. Cada jugador recibe un tablero 5×5 generado aleatoriamente con preguntas para romper el hielo. ¡Recorre la sala, encuentra colegas que coincidan con cada casilla y gana quien complete cinco en línea primero!

También es un **taller práctico de GitHub Copilot** — construirás y extenderás esta app usando técnicas de desarrollo asistido por IA en cuatro laboratorios guiados.

---

## 🚀 Inicio Rápido

**Requisitos:** [Java 21+](https://adoptium.net/) y [Maven 3.9+](https://maven.apache.org/)

```bash
cd socops
./mvnw spring-boot:run
```

Abre **http://localhost:8080** en tu navegador. ¡Cada carga de página genera un tablero nuevo!

---

## 📚 Laboratorios del Taller

| Lab | Título | Qué harás |
|-----|--------|-----------|
| [**00**](workshop/es/00-overview.md) | Descripción General y Lista de Verificación | Orientación y verificación del entorno |
| [**01**](workshop/es/01-setup.md) | Configuración e Ingeniería de Contexto | Configura Copilot y explora el código |
| [**02**](workshop/es/02-design.md) | Desarrollo Frontend Orientado al Diseño | Rediseña la interfaz guiado por Copilot |
| [**03**](workshop/es/03-quiz-master.md) | Quiz Master Personalizado | Crea un agente para generar preguntas de bingo |
| [**04**](workshop/es/04-multi-agent.md) | Desarrollo Multi-Agente | Orquesta múltiples agentes para tareas complejas |

> 📖 **[Abrir la Guía Completa del Lab →](workshop/es/GUIDE.md)**

---

## 🛠️ Desarrollo

```bash
# Ejecutar pruebas
cd socops && ./mvnw test

# Generar JAR
cd socops && ./mvnw clean package
```

La documentación del taller se publica automáticamente en **GitHub Pages** con cada push a `main`.

---

## 🤝 Contribución

Consulta [CONTRIBUTING.md](CONTRIBUTING.md) para las pautas. Revisa el [Código de Conducta](CODE_OF_CONDUCT.md) antes de abrir issues o pull requests.
