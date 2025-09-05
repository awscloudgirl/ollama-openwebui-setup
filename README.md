<h1 align="center">🧠 Ollama + OpenWebUI Setup (macOS with Docker)</h1>

<p align="center">
  A fully local AI chat stack using <strong>Ollama</strong> and <strong>OpenWebUI</strong>, running smoothly on macOS with Docker.
</p>

<p align="center">
  <a href="https://github.com/open-webui/open-webui">
    <img alt="Docker Image Size" src="https://img.shields.io/docker/image-size/ghcr.io/open-webui/open-webui/latest?label=OpenWebUI%20Image&logo=docker&style=flat-square">
  </a>
  <a href="https://github.com/ollama/ollama">
    <img alt="Ollama CLI" src="https://img.shields.io/badge/Ollama-Installed-blueviolet?style=flat-square&logo=OpenAI">
  </a>
  <img alt="Platform" src="https://img.shields.io/badge/Platform-macOS-lightgrey?style=flat-square&logo=apple">
  <img alt="License" src="https://img.shields.io/github/license/yourusername/ollama-openwebui-setup?style=flat-square">
</p>

---

## 🚀 Features

✅ Local LLMs via Ollama  
✅ Beautiful interface via OpenWebUI  
✅ Full offline access  
✅ Works with external SSDs  
✅ Dockerized for clean install  
✅ Cross-browser support  

---

## 🛠️ What This Repo Covers

This repo documents how I successfully set up a full local AI chat system using:
- [Ollama](https://ollama.com)
- [OpenWebUI](https://github.com/open-webui/open-webui)
- Docker on macOS
- External SSD for model storage
- Fixes for networking and port issues on hardened systems

---

## ✅ What Works

- OpenWebUI accessible at `http://localhost:3000`
- Local models working through Ollama backend
- Full communication between Ollama and OpenWebUI
- Docker container remains healthy and persistent

---

## 📦 Quick Start

```bash
# Start container
./docker/start-openwebui.sh

# Stop container
./docker/stop-openwebui.sh
