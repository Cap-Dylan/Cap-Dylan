# Hi, I'm Dylan 👋

Applied AI & IoT Engineering @ FIU · U.S. Navy veteran · Building privacy-first, fully local AI systems on hardware I own.

---

## What I'm Building

**[Jarvis](https://github.com/Cap-Dylan/Jarvis)** — Multi-zone smart home agent with two input paths (Frigate motion automation + Matrix chat) sharing one decision log and one Home Assistant backend. Model routing validated by committed eval harnesses: llama3.2:3b for color-temp decisions (100% JSON compliance, <1s) and Qwen3.5:9b for chat + tool calls (88% accuracy). Dockerized, CI/CD via GitHub Actions, Prometheus + Grafana alerting into Matrix.

**[Jarvis Control Center](https://github.com/Cap-Dylan/control-center)** — Full-stack ops console for real-time Jarvis decision inspection, Home Assistant control, and infrastructure monitoring. FastAPI backend (8 endpoints, Python 3.14, Pydantic v2) with live Canvas LMS integration, Prometheus/Node Exporter alerting, and HA REST API overrides. Vanilla React frontend with Linear/Vercel-style dark dense UI.

**[Tort Agent](https://github.com/Cap-Dylan/tort-agent)** — Local study assistant running qwen3.6:35b-a3b on an RTX 4090. Six tools against an Obsidian vault: morning briefs, handwritten-note OCR (Apple Vision), atomic concept extraction, weekly course summaries, Apple Notes export, and directory navigation. Two-mode interface — Socratic persona chat and tool-using study assistant.

**[Vault Sync](https://github.com/Cap-Dylan/vault-sync)** — Local-first Obsidian vault sync across Mac, Windows, and UGREEN NAS via Syncthing + automated Apple Notes export via launchd.

**[Homelab](https://github.com/Cap-Dylan/homelab_setup)** — 7-node hybrid infrastructure. Low-power 24/7 services (HA, light inference on RTX 2060) + heavy CUDA on demand (RTX 4090, 128GB DDR5). Tailscale mesh, multi-gig networking, UPS-backed. Model selection driven by evaluation harnesses with committed results.

---

## Focus Areas

Agentic AI · Local-first inference · Smart home / IoT · Edge ML · Cybersecurity

---

## Stack

**Languages** — Python, Bash, YAML, JavaScript

**Infrastructure** — Docker, GitHub Actions, Prometheus, Grafana, Tailscale, Syncthing, Home Assistant, Frigate

**ML / AI** — Ollama, LoRA / QLoRA, ONNX, structured outputs, tool-calling agents, eval harness design

**Hardware** — RTX 4090 (24GB), RTX 2060 (8GB), Apple M4 Pro, Zigbee mesh, multi-node Tailscale mesh

---

## Background

**U.S. Navy** — Logistics Specialist (2016–2021)

**Nucamp Bootcamps** — Backend, SQL & DevOps with Python · Modern Software Engineering with DevOps (2023)

**Google Cybersecurity Professional Certificate** — SIEM, IDS, network security, Python security automation (2023)
