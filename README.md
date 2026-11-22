### Hi, I'm Garvit 👋

I build systems software and on-device AI. Class XII (ISC) at Sanskriti The Gurukul, Guwahati, India. I've been taking computers apart in software since 2020, when I got macOS running on my i3-6006U laptop with OpenCore.

---

<a href="https://github.com/garvitsurana271/stambha"><img src="https://raw.githubusercontent.com/garvitsurana271/stambha/main/assets/stambha-icon.svg" width="64" align="left" alt="Stambha"></a>

**[Stambha](https://github.com/garvitsurana271/stambha)**: run the real Apple-silicon macOS on ordinary PCs, straight from a USB stick. I lead it as the continuation of Stela after its creator archived the project. It's a bare-metal Rust UEFI program: an AArch64-to-x86 translator, a Metal driver for NVIDIA GPUs and a model of Apple's hardware.

My work on it:
- Ported Linux's `rtw89` Wi-Fi driver to Rust for the Realtek RTL8852CE, so macOS installs over Wi-Fi with no cable. Brought up on my own laptop, from firmware boot to WPA2/3 and HTTPS.
- Apple's matrix engine (AMX) running natively on the PC's CPU: up to 375× faster per operation, bit-exact against the reference model.
- Laptop support (battery, touchpad gestures, brightness, lid), and experimental AMD and Intel graphics.
- Run the community: [website](https://garvitsurana271.github.io/stambha/), a Discord of testers, and other people's fixes merged with their names on them.

<br clear="left">

---

**Other projects**

| | |
|---|---|
| **[Burnd](https://github.com/garvitsurana271/burnd)** | Local-first cost control for Claude Code: ranks nine cost-leak patterns in session logs by dollar value. 1,305 npm installs in its first 48 hours, listed in five awesome-lists. `npx getburnd` |
| **[Viveka](https://github.com/garvitsurana271/viveka)** | Checks a suspicious chat forward before you spread it: claim extraction, multi-hop search over trusted sources, a calibrated verdict with citations, or a hand-off to a human when the evidence is thin. Benchmarked on AVeriTeC. USAII Global AI Hackathon 2026. |
| **KropScan** | Offline-first crop disease detection for farmers with poor connectivity: ONNX on-device, Gemma in the cloud, graceful fallback. 3rd of 200+ teams, Masters' Union AI Hackathon 2026. |
| **[Pravaah](https://github.com/garvitsurana271/pravaah)** | Explainable train-dispatch copilot for Indian Railways, with an interlocking layer that makes unsafe states unrepresentable. [Live demo](https://garvitsurana271.github.io/pravaah/) |
| **AuraSound** | Turns a laptop, a TV, a Bluetooth speaker and phones into one calibrated surround system, with tactile bass through phone vibration motors. |
| **[StudyDeck](https://github.com/garvitsurana271/studydeck)** | ISC Class 12 PCM practice: 7,710 questions with difficulty-mapped practice. |

**Recognition**
- Masters' Union AI Hackathon 2026: 3rd of 200+ teams (India's largest high-school AI hackathon)
- IIT Kharagpur Young Innovators Program: Top 5 of 1,500 (international)
- IIT Guwahati Research and Industrial Conclave: 1st place
- The Big Plan 2.0, SRCC, Delhi University: Finalist
- National Math-n-Coding 2024: Winner · LogIQids: International rank 34
- ICSE 2025: Certificate of Excellence (CISCE)

**Stack:** Rust (bare-metal, UEFI, drivers), TypeScript, React, Node, Python, FastAPI, ONNX Runtime, Three.js, Claude API.

[Portfolio](https://garvit-surana.vercel.app) · [Stambha](https://garvitsurana271.github.io/stambha/) · [npm](https://www.npmjs.com/~garvitsurana271) · garvitsurana10@gmail.com
