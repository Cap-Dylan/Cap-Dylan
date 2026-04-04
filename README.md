# Hey, I'm Dylan 👋

Sophomore studying **Applied AI & IoT Engineering**, transferring to FIU in May 2026. I build things that run locally — no cloud dependency, no shortcuts.

---

## What I'm working on

**[homelab_setup](https://github.com/Cap-Dylan/homelab_setup)** — A seven-node homelab built around local AI inference, smart home automation, and IoT experimentation.

The current stack:
- **Frigate NVR** running on an Intel N100 NAS with hardware QuickSync decode, consuming a Tapo C121 RTSP stream
- **Home Assistant** on a dedicated always-on node, fully integrated with Frigate via HACS + MQTT — person detection, motion, occupancy sensors all live
- **Ollama** on an RTX 2060 for local LLM inference (llama3.1:8b, llama3.2:3b), fronted by a **FastAPI wrapper** with `/health`, `/ask`, `/summarize`
- **Prometheus + Grafana** observability stack across all four nodes including the HA box
- **AdGuard Home + Tailscale** for privacy-first DNS and remote access

Long-term goal: a closed-loop agentic smart home system — Frigate computer vision events feeding into a local LLM orchestrator that drives HA automations. Fine-tuned MobileNetV3/EfficientNet-Lite on the RTX 4090 for resident/delivery/unknown classification.

---

## Stack

```
Languages:    Python
Inference:    Ollama · FastAPI · PyTorch (planned)
Homelab:      Home Assistant · Frigate NVR · Zigbee2MQTT · MQTT
Observability: Prometheus · Grafana · Node Exporter
Networking:   Tailscale · AdGuard Home · Docker · Portainer
Hardware:     RTX 4090 · RTX 2060 · Intel N100 · M4 Pro
```

---

## Currently learning

- Python (CS150B) — first formal CS course
- Applied AI & IoT Engineering fundamentals
- Building toward: PyTorch fine-tuning, agentic orchestration, Coral TPU integration

---

> Everything here runs on-prem. Privacy-first, fully local, no cloud dependency.
