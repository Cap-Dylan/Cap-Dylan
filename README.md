# hey, I'm Dylan

I'm a full-time sophomore studying Applied AI and IoT Engineering. Currently building a
privacy-first, fully local smart home system powered by local LLM inference on
repurposed consumer hardware.

## what I'm working on

**[homelab_setup](https://github.com/Cap-Dylan/homelab_setup)** — a multi-node homelab
running local AI inference, computer vision, and smart home automation with zero cloud
dependency.

The flagship project is **Jarvis**, an agentic smart home system I built from scratch:
- Frigate NVR detects occupancy via a security camera
- A local LLM (llama3.1:8b on an RTX 2060) reasons about what to do
- Home Assistant executes the decision autonomously
- I can chat with it naturally through a self-hosted Matrix server and give it commands or ask why it did something
- Every decision is logged with its reasoning for a full audit trail

The whole stack runs on repurposed laptops and a NAS in my apartment. No cloud,
no subscriptions, no data leaving the network.

## the stack

| Layer | What | Where |
|-------|------|-------|
| AI inference | Ollama (llama3.1:8b) | MSI GE76, RTX 2060 |
| Chat server | Continuwuity (Matrix) | MSI GE76 |
| Orchestration | Python (Flask), systemd | ASUS Vivobook |
| Monitoring | Prometheus + Grafana | ASUS Vivobook |
| DNS filtering | AdGuard Home | ASUS Vivobook |
| NVR | Frigate (QuickSync decode) | UGREEN NAS |
| Smart home | Home Assistant, Zigbee2MQTT, MQTT | Lenovo IdeaPad |
| Heavy ML | PyTorch (planned fine-tuning) | Custom tower, RTX 4090 |

## what's next

- Fine-tuned CV model on the 4090 for person classification (resident vs. delivery vs. unknown)
- Frigate snapshot → multimodal LLM visual reasoning
- Voice interface via Makeblock Halocode
- Human-in-the-loop approval for high-impact actions via Matrix
