#  N G L   F L O O D   E N G I N E

A high‑performance, anonymous message flooder for NGL.link built with Python and asyncio. Designed for cybersecurity research and educational stress‑testing, it demonstrates advanced asynchronous request handling, adaptive throttling, and dynamic message pools.

## ✨ Features

- 🎭 **9 Message Categories** – Filipino Trashtalk, English Quotes, Spanish Rizz, Brainrot, Gen Z Chats, Sarcastic, English Offensive, Pure Offensive + Racism, and a Mix (All) – each with 30+ unique messages.
- 🔄 **Proxy Rotation** – Supports rotating proxies from a `proxies.txt` file (format: `host:port:user:pass` or `host:port`).
- 🧠 **Adaptive Throttling** – Monitors success rate and automatically adjusts concurrency and delay to maximise throughput while avoiding bans.
- 🤖 **Capsolver Integration** – Optional Turnstile bypass using Capsolver API key (for Cloudflare challenges).
- 📊 **Live Dashboard** – Rich terminal UI showing total attempts, success/fail counts, RPS, elapsed time, and recent message logs.
- ⚡ **Async Concurrency** – Uses `aiohttp` with semaphore control for efficient request handling.
- 🛡️ **Randomised Device IDs & User‑Agents** – Each request uses a unique device ID and rotating browser fingerprints to evade detection.
- 🎨 **Modern Terminal UI** – Earthy‑themed panels, progress bars, and clear prompts using `rich` and `pyfiglet`.
- 🔐 **Ethical Use Disclaimer** – Built for authorised testing on links you own or have explicit permission to test.

## 📦 Requirements

- Python 3.8+
- Internet connection (for API calls)
- Optional: `proxies.txt` file for proxy rotation
- Optional: Capsolver API key for Turnstile bypass

## 🚀 Installation

1. **Download** this repository as a ZIP from GitHub.
2. **Extract** the archive to your preferred folder.
3. **Open a terminal** inside the extracted folder.
4. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
