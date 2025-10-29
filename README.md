# 🧠 Mnemonic Attendance Dashboard

> Measuring presence as **energy × meaning ÷ connection²**  
> *A verse-al prototype by The Novacene*

---

## 🚀 Try the Demo

🌐 **Live Prototype:** [https://thenovacene.github.io/mnemonic-attendance/](https://thenovacene.github.io/mnemonic-attendance/)  
*(Hosted via GitHub Pages — demo data only, no learner information collected)*

[![View Demo](https://img.shields.io/badge/View-Demo-blueviolet?style=for-the-badge)](https://thenovacene.github.io/mnemonic-attendance/)

---

## ✨ Overview

Traditional attendance measures *time in seat*.  
**Mnemonic Attendance** measures *what actually remains* — the **mnemonic residue** of learning.

This prototype redefines attendance as a **field equation**:

\[
A = \frac{E × s}{c²}
\]

| Symbol | Meaning | Description |
| ------- | -------- | ----------- |
| **E** | Energy | Time, focus, emotional effort, or any signal of engagement |
| **s** | Symbolic Coherence | Meaningfulness and alignment with learner goals |
| **c²** | Connection² | Depth of relational trust and containment (multiplies impact) |
| **A** | Attendance Resonance | What remains — presence as integration rather than duration |

---

## 🌐 Purpose

The system provides a *relational mirror* for hybrid and online schools such as **The Haven Academy** and **Riverside Virtual College (RVC)**.

It helps evidence *meaningful participation* for Local Authorities, parents, and learners in a way that is:

- Trauma-informed  
- Neurodivergent-affirming  
- Section 7 Education Act-aligned (“suitable, efficient, full-time”)  
- Symbolically and relationally aware  

---

## 🧩 Prototype Architecture

mnemonic-attendance/
│
├── docs/ ← Published demo (UI + in-browser computation)
│ └── index.html (interactive dashboard)
│
├── public/ ← Development workspace (optional)
│ └── index.html
│
├── private/ ← Closed engine (not public)
│ ├── engine.py (maps data → E, s, c values)
│ └── weights.json (context calibration per org)
│
├── data/
│ ├── sample_haven.json
│ └── sample_rvc.json
│
└── README.md

yaml
Copy code

- **Public layer** → concept visualisation, sliders, mock data  
- **Private engine** → proprietary logic converting live signals (e.g. Pencil Spaces, Canvas, TutorCruncher) into relational-physics inputs  

---

## 🧪 Running the Demo Locally

1. Clone the repo  
   ```bash
   git clone https://github.com/TheNovacene/mnemonic-attendance.git
   cd mnemonic-attendance/docs
Open index.html in a browser (no build step required).

Toggle Learner View ↔ LA View to see both framings.

Export a .json snapshot to simulate a learner record.

🔒 Licensing & Funding
Public front-end: CC BY-NC-SA 4.0

Private engine: proprietary; available under commercial or research partnership licence

This separation enables open demonstration and funding partnerships while protecting The Novacene’s symbolic attendance engine as IP.

🌿 Authors
The Novacene Ltd
Conceived and developed by Kirstin Stevens and Eve11


---

## ⚖️ License

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-blue.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

This repository’s public content — including `/docs` and `/public` — is licensed under the  
**Creative Commons Attribution–NonCommercial–ShareAlike 4.0 International License (CC BY-NC-SA 4.0).**

> The private computation engine (`/private`) remains proprietary to **The Novacene Ltd**  
> and may only be used under a commercial or research partnership agreement.

© 2025 The Novacene Ltd. All rights reserved.

