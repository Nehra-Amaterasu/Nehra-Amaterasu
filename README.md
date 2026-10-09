### Hi, I'm Amritanshu 👋

Electronics & Communication Engineering undergraduate. I build systems where
hardware, signals and machine learning meet — and I care about measuring things
properly before claiming they work.

Heading toward **VLSI and digital design**, with a strong interest in running
AI efficiently on constrained hardware.

---

#### 🔭 What I'm building

**[JARVIS](https://github.com/Nehra-Amaterasu/JARVIS)** — a local-first voice
assistant that runs entirely on a laptop with a 6 GB GPU. No cloud LLM.

- **Voice:** Whisper large-v3-turbo + Qwen3-4B on-device; time to first spoken
  word cut from 22–97 s to **0.6 s** by diagnosing hidden reasoning tokens
- **Memory:** 110k messages indexed for episodic recall with hybrid
  **BM25 + vector search** and Reciprocal Rank Fusion; finds a single line from
  years back from a casual Hinglish question
- **People model:** tie-strength scoring validated against labelled data
  (**95% precision@20**), including a case where the data contradicted my own
  hypothesis
- **Sensing:** ESP32-S3 firmware for Wi-Fi RSSI/CSI presence detection, and an
  LD2450 mmWave radar decoder
- **Honest by design:** abstains instead of inventing memories it doesn't have

Every decision is documented with the measurement behind it in the
[engineering log](https://github.com/Nehra-Amaterasu/JARVIS/blob/main/docs/DECISIONS.md).

---

#### 🛠️ Tools I work with

**Languages:** Python · C++ (Arduino / ESP32)
**ML & retrieval:** scikit-learn · PyTorch · sentence-transformers · LanceDB · BM25
**LLMs & speech:** Ollama · Whisper (faster-whisper) · local quantised models
**Hardware:** ESP32-S3 · HLK-LD2450 mmWave radar · serial / WebSocket telemetry
**Engineering:** Git · benchmarking · reproducible environments

---

#### 🌱 Currently

- Taking JARVIS's presence sensing from simulation to real hardware
- Building toward digital design and FPGA work

<!-- Profile last updated 2026-10 -->
