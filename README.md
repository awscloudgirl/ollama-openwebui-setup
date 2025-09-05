# 🧠 Ollama + OpenWebUI Setup on macOS with External SSD

This repo documents how I set up [Ollama](https://ollama.com/) with [OpenWebUI](https://github.com/open-webui/open-webui) running in Docker, with models and data stored on an external SSD — including all the troubleshooting, issues, and resolutions encountered along the way.

---

## 📦 Project Goals

- Run OpenWebUI in Docker
- Store Ollama models and volumes on external SSD
- Work around Mac hardening issues
- Document full debugging journey

---

## 🛠️ Components

- macOS (with hardened security settings)
- Docker
- External SSD (e.g., `/Volumes/OllamaSSD`)
- Ollama
- OpenWebUI (Dockerized)

---

## 📂 Folder Structure

See `notes/` and `docker/` folders for implementation details.
