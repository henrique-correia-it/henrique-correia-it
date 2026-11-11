# Hi, I'm Henrique Correia 👋

**Software Developer · Backend · Python · AI · Mobile** — Electrical and Computer Engineer (ISEP) · MSc student in Autonomous Systems

I build complete products, from the database and the APIs to the app in the user's hands, and I ship them to production.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-henrique--correia-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/henrique--correia/)
[![Email](https://img.shields.io/badge/Email-contact-EA4335?logo=gmail&logoColor=white)](mailto:hcorreia20042010@gmail.com)
[![Vetra](https://img.shields.io/badge/Vetra-on_Google_Play-3DDC97?logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=pt.projetos.vetra)

## 🎯 What I work on

| | Area | Where to see it |
|---|---|---|
| ⚙️ | **Backend** — REST APIs, PostgreSQL, authentication, payments, sync | [Vetra](https://github.com/henrique-correia-it/vetra-overview) · [TopTop](https://github.com/henrique-correia-it/toptop) · [FactCheck](https://github.com/henrique-correia-it/factcheck) |
| 🐍 | **Python** — FastAPI, Flask, asyncio, data processing and automation | [FactCheck](https://github.com/henrique-correia-it/factcheck) |
| 🤖 | **AI** — LLM pipelines, RAG, prompt engineering, on-device ML | [FactCheck](https://github.com/henrique-correia-it/factcheck) · [GymOS](https://github.com/henrique-correia-it/gym_os) |
| 📱 | **Mobile** — Flutter apps in production, native Android and Wear OS | [Vetra](https://github.com/henrique-correia-it/vetra-overview) · [GymOS](https://github.com/henrique-correia-it/gym_os) · [CycleTracker](https://github.com/henrique-correia-it/CycleTracker) |

## 🚀 Featured projects

### 📊 [Vetra](https://github.com/henrique-correia-it/vetra-overview): personal and shared finance app, **live on [Google Play](https://play.google.com/store/apps/details?id=pt.projetos.vetra) and the [web](https://app.vetra-app.com/)**
- Built and maintained on my own.
- Works offline on an encrypted SQLite database, with sync to Supabase/PostgreSQL protected by Row Level Security.
- Shared accounts with privacy for each member.
- 370+ test files and CI/CD that publishes straight to the Play Store.

`Flutter` `Riverpod` `Drift` `Supabase` `PostgreSQL` `GitHub Actions`

### 🤖 [FactCheck](https://github.com/henrique-correia-it/factcheck): real-time fact-checking of YouTube videos with local LLMs
- RAG pipeline: an LLM extracts claims into structured JSON, live web evidence is ranked by source credibility, and a second LLM pass gives each verdict.
- Results are streamed over WebSockets in sync with the video.
- 78 transcript segments → 10 verified claims in 33.6 s.

`Python` `FastAPI` `asyncio` `LangChain` `Ollama` `WebSockets`

### 🛒 [TopTop](https://github.com/henrique-correia-it/toptop): e-commerce platform, **live at [toptop.pt](https://toptop.pt)**
- E-commerce platform I built and host, running in production, with no framework.
- Stripe payments with webhook signatures verified by hand, and refunds.
- Transactional stock reservation, CSRF protection and a back office with access levels.

`PHP` `MySQL` `Stripe` `JavaScript`

### 🏋️ [GymOS](https://github.com/henrique-correia-it/gym_os): fitness and nutrition app that works offline
- Barcode scanning and **OCR of nutrition labels on the device** with Google ML Kit.
- Local Isar database with Firestore sync per data type.
- About 30k lines of Dart.

`Flutter` `Riverpod` `Isar` `Firebase` `ML Kit`

### ⌚ [CycleTracker](https://github.com/henrique-correia-it/CycleTracker): health-tracking app with a Wear OS companion
- Flutter app, native Kotlin for exact alarms and notification actions, and a separate **Wear OS app** in Compose.
- Supabase with Row Level Security.

`Flutter` `Kotlin` `Wear OS` `Supabase`

### ☀️ [Solar Tracker](https://github.com/henrique-correia-it/solar-tracker): dual-axis IoT solar tracker
- Bare-metal C on an ATmega328P with PID control.
- ESP8266 gateway with MQTT and ThingSpeak, a KiCad PCB and a live web dashboard.

`C` `AVR` `ESP8266` `MQTT` `KiCad`

## 🛠️ Tech

| Area | Tools |
|---|---|
| Backend | NestJS, REST APIs, PostgreSQL, Supabase (RLS, RPC, Realtime), MySQL, PHP, Keycloak, Docker, Nginx |
| Python | FastAPI, Flask, asyncio, pandas, openpyxl, pytest, PyInstaller |
| AI | LLMs (Ollama, LangChain), RAG, prompt engineering, structured outputs, Google ML Kit (OCR, barcode) |
| Mobile | Flutter, Dart, Riverpod, Drift/SQLite, Isar, Firebase, Kotlin, Wear OS |
| IoT and embedded | ThingsBoard, MQTT, C (AVR), ESP8266, KiCad |
| DevOps | Git, GitHub Actions, GitLab, Cloudflare Pages, Linux |

## 🎓 Education

- **MSc in Electrical and Computer Engineering, Autonomous Systems** · ISEP · *2026 – present*
- **BSc in Electrical and Computer Engineering** · ISEP · *2022 – 2026*
