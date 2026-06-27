# Festival DevOps - Pacific Music Fest

Plataforma para la gestión y despliegue automatizado del festival musical "Pacific DevOps Music Fest".

## 📊 Estado del Proyecto
![CI Status](https://github.com/JHbotero-deve/festival-devops-2026/actions/workflows/ci.yml/badge.svg)

## 🛠️ Tecnologías Utilizadas
* **Git:** Control de versiones.
* **GitHub Actions:** Implementación de Integración Continua (CI).
* **Docker:** Contenerización de microservicios.
* **Docker Compose:** Orquestación del entorno (Frontend, Backend API, Base de datos).

## 🏗️ Arquitectura del Proyecto
El sistema se organiza en microservicios para garantizar la escalabilidad y profesionalismo del despliegue:
- **/frontend:** Landing page estática (HTML/CSS).
- **/backend:** API desarrollada en Python (Flask).
- **/database:** Base de datos MySQL con persistencia de volúmenes.

## 🚀 Despliegue
Para levantar el entorno profesional, utiliza el comando:
```bash
docker compose up -d