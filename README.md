<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4fd1c5,50:6b46c1,100:f6ad55&height=200&section=header&text=HEALTHCORE%20AI&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Local%20Biometric%20Health%20Companion&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

<br/>

<p>
  <img src="https://img.shields.io/badge/Version-1.0.0-4fd1c5?style=for-the-badge&labelColor=020810&logo=pulse&logoColor=4fd1c5"/>
  <img src="https://img.shields.io/badge/License-MIT-b794f4?style=for-the-badge&labelColor=020810"/>
  <img src="https://img.shields.io/badge/No%20API%20Required-✓-68d391?style=for-the-badge&labelColor=020810"/>
  <img src="https://img.shields.io/badge/Vanilla%20JS-Pure-f6ad55?style=for-the-badge&labelColor=020810&logo=javascript&logoColor=f6ad55"/>
</p>

<br/>

> **🧠 AI-powered health intelligence that runs entirely in your browser — zero servers, zero subscriptions, zero compromise.**

<br/>

</div>

---

## ✨ Overview

```
╔═══════════════════════════════════════════════════════════════╗
║  HEALTHCORE AI  //  LOCAL BIOMETRIC HEALTH COMPANION          ║
║  Real-time vitals · Circadian intelligence · Hydration AI     ║
╚═══════════════════════════════════════════════════════════════╝
```

**HealthCore AI** is a sleek, real-time health monitoring dashboard that simulates biometric data and delivers intelligent, personalized health coaching — all from a single HTML file. No backend. No API keys. No subscriptions.

Built with a cyberpunk-medical aesthetic and powered by circadian rhythm algorithms, it gives you an immersive health companion experience right in your browser.

---

## 🌈 Features

<table>
<tr>
<td width="50%">

### 💓 Live Biometrics
- Real-time **Heart Rate** with animated gauge
- **SpO₂** oxygen saturation tracking
- **HRV** (Heart Rate Variability) monitoring
- **Stress Index** with color-coded alerts

</td>
<td width="50%">

### 🧠 Circadian Intelligence
- Scientifically modelled **alertness curve**
- Wakefulness score with performance zones
- Optimal **sleep window** calculation
- Fatigue prediction & warnings

</td>
</tr>
<tr>
<td width="50%">

### 💧 Hydration Engine
- Smart **120-minute drink reminders**
- Visual water intake tracker (8 glasses)
- Overdue hydration alerts
- Countdown timer to next drink

</td>
<td width="50%">

### 🏃 Activity Tracker
- Step count & distance logging
- Active minutes accumulation
- Calorie burn estimation
- One-click activity simulation

</td>
</tr>
</table>

---

## 🎯 AI Coach System

The central AI panel analyzes all metrics simultaneously and delivers:

| Signal | What it detects | Action |
|--------|----------------|--------|
| 🔴 **ALERT** | Critical HR, SpO₂ < 96%, 15h+ awake | Immediate intervention |
| 🟡 **CAUTION** | Alertness < 55%, stress > 50 | Preventive action |
| 🟢 **NOMINAL** | All metrics balanced | Maintain & optimize |

**Dynamic coaching includes:**
- Breathing exercises (4-7-8 technique) when stress spikes
- Power nap triggers when alertness drops below 35%
- Hydration nudges timed to your drinking pattern
- Movement prompts when step count is low

---

## 🚀 Quick Start

```bash
# Option 1: Just open it
open index.html

# Option 2: Serve locally
npx serve .
# → http://localhost:3000

# Option 3: Python
python -m http.server 8080
# → http://localhost:8080
```

> **That's it.** No `npm install`. No `.env` files. No dependencies.

---

## 🖥️ Setup Screen

On first launch, enter your personal baselines:

```
┌─────────────────────────────────────┐
│  Age          →  26                 │
│  Weight (kg)  →  68                 │
│  Wake-up Time →  07:00              │
│  Sleep Goal   →  8h                 │
│  Resting HR   →  65 bpm             │
└─────────────────────────────────────┘
```

These values calibrate your **max heart rate**, circadian model, sleep window, and alertness curve for personalized coaching.

---

## 📊 Dashboard Layout

```
┌──────────────────────────────────────────────────────────┐
│  HEADER: Clock · Sensor Status · Awake Duration          │
├──────────────┬───────────────────────┬───────────────────┤
│  LEFT PANEL  │    CENTER PANEL       │  RIGHT PANEL      │
│              │                       │                   │
│  Heart Rate  │  🔵 AI COACH ORB      │  💧 Hydration     │
│  Gauge       │                       │  Timer            │
│              │  Status Headline      │                   │
│  SpO₂  HRV   │  Biometric Insight    │  😴 Sleep         │
│  Stress      │                       │  Window           │
│  Alertness   │  Action Cards         │                   │
│              │  (clickable)          │  ⚡ Wakefulness   │
│  Activity    │                       │  Arc Gauge        │
│  Stats       │                       │                   │
├──────────────┴───────────────────────┴───────────────────┤
│  BOTTOM BAR: Analyze · Log Water · Activity · New Day    │
└──────────────────────────────────────────────────────────┘
```

---

## 🎨 Design System

```css
--bg:      #020810   /* Deep space black   */
--accent:  #4fd1c5   /* Teal (primary)     */
--purple:  #b794f4   /* Lavender           */
--warn:    #f6ad55   /* Amber              */
--danger:  #fc8181   /* Coral red          */
--good:    #68d391   /* Mint green         */
```

Typography stack: **Syne** (display) · **Fira Code** (data) · **DM Sans** (body)

---

## 🔬 Science Behind It

### Alertness Model
Based on a two-process circadian model:
- **Circadian rhythm** (24h sinusoidal oscillation peaking ~10am)
- **Sleep pressure** (linear accumulation with wakefulness hours)
- Factored against personal RHR baseline

### Heart Rate Zones
```
Zone 1  <60% Max HR   →  Resting / Recovery
Zone 2  60–70%        →  Fat burn / Easy
Zone 3  70–80%        →  Aerobic / Moderate
Zone 4  80–90%        →  Threshold / Hard
Zone 5  >90%          →  VO₂ Max / Maximum
```

### HRV Interpretation
| HRV (ms) | Autonomic State |
|----------|----------------|
| > 50     | Excellent recovery |
| 35–50    | Adequate recovery |
| < 35     | Elevated strain |

---

## 📁 File Structure

```
healthcore-ai/
└── index.html          ← Everything. One file. ~500 lines.
    ├── CSS Variables    (design tokens)
    ├── Setup Screen     (user calibration)
    ├── Dashboard Grid   (3-column layout)
    └── Engine JS        (simulation + AI logic)
```

---

## 🛠️ Tech Stack

<p>
  <img src="https://img.shields.io/badge/HTML5-Semantic-E34F26?style=flat-square&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-Grid%20%2B%20Variables-1572B6?style=flat-square&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-Vanilla%20ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/SVG-Animated%20Gauges-FF9900?style=flat-square"/>
  <img src="https://img.shields.io/badge/Google%20Fonts-Syne%20%2B%20Fira-4285F4?style=flat-square&logo=google&logoColor=white"/>
</p>

**Zero dependencies.** No frameworks, no bundlers, no package managers.

---

## 🔮 Roadmap

- [ ] 📱 Mobile responsive layout
- [ ] 🔊 Audio cues for water & sleep alerts
- [ ] 📈 Historical data charts (localStorage)
- [ ] 🌙 Dark/Light theme toggle
- [ ] 🩺 Custom metric targets
- [ ] 📤 Export health report (PDF)
- [ ] 🔗 Web Bluetooth API integration (real wearables)

---

## 🤝 Contributing

```bash
git clone https://github.com/yourusername/healthcore-ai.git
cd healthcore-ai

# No install needed — open index.html and hack away!
```

Pull requests welcome. For major changes, open an issue first.

---

## 📄 License

```
MIT License — free to use, modify, and distribute.
Just keep the spirit of open health tech alive. 💚
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:f6ad55,50:4fd1c5,100:6b46c1&height=120&section=footer&animation=fadeIn" width="100%"/>

**Built with 💙 for healthier humans everywhere**

*HealthCore AI — because your health deserves intelligence, not subscriptions.*

⭐ **Star this repo** if it helped you build something awesome!

</div>
