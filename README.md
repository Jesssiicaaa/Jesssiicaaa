# Hi, I'm Jessica Olaniyi 👋

**Computer Engineering Student @ Toronto Metropolitan University**

I'm a third-year Computer Engineering student with a focus on **data analytics and applied machine learning** — specifically turning messy, real-world datasets into pipelines, models, and insights that are actually usable. My background is in Computer Engineering, and I've worked on projects ranging from firmware and embedded systems to full-stack development, making me always think about problems from top to bottom. I think about problems at every layer, from  hardware limitations to how data moves through the system and what the user ultimately sees.

My primary interest is **data analysis** — I'm drawn to problems where quantitative analysis drives decisions. Outside of that, I've built across embedded systems, full-stack, and ML evaluation, which gives me context for how software behaves at every level.

---

## Featured Projects

### 🌍 Global Unicorn Landscape — Data & ML Pipeline
`Python` `SQL` `XGBoost` `Prophet` `scikit-learn` `Tableau` `Google Sheets API` `openpyxl`

End-to-end analytics platform on 1,074 unicorn companies across 46 countries — from raw data to live collaborative dashboard.

**What I built:**
- Engineered 9 custom features including a funding efficiency ratio (valuation ÷ funding) across 16 industries
- Built and compared 5 models: XGBoost regression (R²=0.978), binary classifier for high-value unicorns (ROC-AUC=1.0), multiclass industry classifier, K-Means + PCA clustering, and Prophet time series forecasting
- Discovered Fintech leads all industries with 224 unicorns but ranks 4th in funding efficiency (9.1×) vs. Internet software at 28.5× — a non-obvious insight from cross-industry segmentation
- Resolved a 94%/6% class imbalance using `class_weight='balanced'` and stratified cross-validation; log-transformed a $1B–$180B skewed valuation distribution to normalise the regression target
- Automated delivery to Google Sheets via the gspread API — zero-download stakeholder access with native sparkline formulas
- Packaged as a reproducible GitHub repo with a `run_all.py` master script, `requirements.txt`, and structured README

**Focus:** Data engineering → modelling → insight → decision-relevant output

🔗 [LinkToBeUpdated](#) · [LinkToBeUpdated](#)

---

### 🎮 Gesture-Controlled Browser Game — ML Evaluation Framework
`TensorFlow.js` `JavaScript` `Pose Estimation` `HTML/CSS`

Real-time browser game controlled by body pose — but the actual project is the evaluation framework built alongside it.

**What I built:**
- Integrated TensorFlow.js MoveNet pose estimation to classify gestures from webcam input in real time, with no server required
- Built a full evaluation suite from scratch: confusion matrix, per-class precision/recall, confidence distributions, and stability analysis — measuring trust, not just accuracy
- Identified Left/Right misclassification as the dominant failure mode through error analysis; rebalanced training data and reduced prediction flicker measurably
- Treated the project like a real product: designed, user-tested, documented failure modes, and iterated until reliability improved

**Focus:** ML evaluation depth — understanding when and why a model fails, not just whether it runs

🔗 [LinkToBeUpdated](#)

---

### 🔒 TrancheGuard — Milestone-Based Fund Release Platform
`React` `Full-Stack` `JavaScript` · *Hackathon Project — Team of 4*

Escrow simulation platform with enforced role separation and audit-gated fund release — built to address systemic funding opacity affecting NGOs and underserved businesses.

**What I built:**
- Designed and implemented three enforced roles (Donor, Contractor, Auditor) with a React state machine — invalid transitions are blocked at the application logic level, not just the UI
- Built an append-only audit trail: no tranche is released without timestamped evidence submission and independent Auditor sign-off
- Researched the problem space before writing a line of code — identified funding opacity as a documented issue affecting Black-owned businesses, NGOs, and community organizations across North America and the UK
- Shipped a working product end-to-end within a hackathon timeframe as a team of 4

**Focus:** Business logic enforcement, fintech system design, product thinking under constraints

🔗 [LinkToBeUpdated](#)

---

### 🤖 Robot Guidance System — Embedded Firmware
`C` `HCS12 Microcontroller` `CodeWarrior` `Assembly`

Autonomous robot programmed entirely in firmware — no OS, no abstractions, direct hardware control.

**What I built:**
- Developed firmware for motor control, collision detection, and timer-based navigation on the Freescale HCS12 MCU
- Used hardware interrupts, memory-mapped I/O, serial protocols, and PWM for real-time, event-driven behavior
- Debugged timing and logic errors at the hardware level — no print statements, no stack traces

**Focus:** Low-level systems, real-time constraints, hardware-software integration

🔗 [LinkToBeUpdated](#)

---

## Technical Skills

| Area | Tools |
|---|---|
| **Languages** | Python, C, Java, SQL, Assembly, HTML/CSS, MATLAB |
| **Data & ML** | Pandas, NumPy, scikit-learn, XGBoost, Prophet, TensorFlow.js, Matplotlib |
| **Visualization** | Tableau, Power BI, Excel, GNUPlot |
| **Full-Stack** | React, Flask, Firebase, REST APIs |
| **Embedded** | HCS12, ESP32, FPGA (DE1-SoC), ROS2, Altium Designer |
| **Tools** | Git, GitHub, MySQL, Jupyter, VS Code, Google Sheets API |

**Currently deepening:** Advanced SQL analytics · Demand forecasting · Financial modelling · Cloud deployment (AWS/Azure)

---

## What I'm Looking For

I'm actively seeking a **co-op position in data analytics, AI/ML, or software engineering** starting in 2026. I'm looking for a role where I can contribute to real work — not just shadow — and learn from engineers who care about correctness and depth.

If you're working on something in data, fintech infrastructure, or applied ML and want someone who goes end-to-end: let's talk.

📧 jessica.olaniyi@torontomu.ca · 🔗 [LinkToBeUpdated](#) · 🌐 [LinkToBeUpdated](#)

---

## Portfolio Philosophy

Three things that are consistent across everything I build:

- **I go end-to-end.** From raw data to deployed dashboard. From requirement to working product. I don't hand off halfway.
- **I measure, not just build.** Confusion matrices, cross-validation, audit trails — I ask "how do we know this works?" before calling something done.
- **I learn fast and ask well.** XGBoost, Prophet, TensorFlow.js, ROS2, gspread API — none of these were taught in my courses. I pick up tools quickly and know how to ask precise questions when I'm stuck.
