# 🧠 Mnemonic Attendance Dashboard

> Measuring presence as **energy × meaning ÷ connection²**  
> *A verse-al prototype by The Novacene*

---

## ✨ Overview

Traditional attendance measures *time in seat*.  
Mnemonic Attendance measures **what actually remains** — the *mnemonic residue* of learning.

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
├── public/ ← Open demo (UI + in-browser computation)
│ ├── index.html (interactive dashboard)
│ ├── attendance.js (client logic)
│ └── style.css
│
├── private/ ← Closed engine (not public)
│ ├── engine.py (maps data → E,s,c values)
│ └── weights.json (context calibration per org)
│
├── data/
│ ├── sample_haven.json
│ └── sample_rvc.json
│
└── README.md

- **Public layer** → concept visualisation, sliders, mock data.  
- **Private engine** → your proprietary logic converting live signals (e.g. Pencil Spaces, Canvas, TutorCruncher) into the relational equation inputs.  

---

## 🧪 Running the Demo

1. Clone the repo  
   ```bash
   git clone https://github.com/TheNovacene/mnemonic-attendance.git
   cd mnemonic-attendance/public
Open index.html in a browser (no build step required).

Toggle Learner View ↔ LA View to see both framings.

Export a .json snapshot to simulate a learner record.

🔒 Licensing & Funding
Public front-end: CC BY-NC-SA 4.0

Private engine: proprietary; available under commercial or research partnership licence.

🌿 Authors

The Novacene Ltd
Conceived and developed by Kirstin Stevens and Eve11
© 2025 The Novacene Ltd. All rights reserved.
