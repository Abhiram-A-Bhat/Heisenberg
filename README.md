 ## AI Debate Coach & Argument Strength Analyzer

> **Team:** Heisenberg  
> **Lead:** Abhiram A Bhat  
> **Hackathon PS:** PS-23                  
> **Tech Stack:** LLM · NLP · Speech Analysis · React

---

## 📌 Problem Statement

Strong debating and public speaking skills are career-defining — but expert coaching is available only at elite schools. Students have no way to know whether their argument is logically sound, whether they are committing fallacies, or what the strongest counterarguments to their position are.

**Strongest counterarguments** means: arguments that directly oppose and challenge someone's position — and are hard to defeat.

---

## 🧠 What We're Building

A real-time AI-powered debate coach that listens to a speaker without interruption, analyzes their argument across logic, delivery, and structure, and gives actionable feedback — like a coach, not a calculator.

---

## ✅ Core Features

### 🎤 Live Speech Input
- Listens to the speaker without interruption until they finish
- Processes spoken arguments in real time via speech recognition

### ⚖️ Argument Analysis Engine
- **Logical Fallacy Detection** — Identifies fallacies (ad hominem, straw man, false dichotomy, etc.) with exact sentence-level location
- **Argument Strength Score** — Rates the overall argument on a 0–100 scale based on logic, evidence, and structure
- **Missing Evidence Identifier** — Flags claims made without supporting data or citations
- **3 Strong Counterarguments** — Generates the three hardest-to-defeat counterarguments to the speaker's position

### 🗣️ Vocal Delivery Analysis (Spoken Mode)
- **Pace Analysis** — Flags speaking too fast or too slow
- **Filler Word Detection** — Tracks "um," "uh," "like," "you know," etc.
- **Confidence Scoring** — Infers confidence from vocal patterns and delivery consistency

### 🏛️ Debate Format Support
- **British Parliamentary (BP)** — Respects BP structure: Government/Opposition benches, Prime Minister speech, Points of Information
- **MUN (Model United Nations)** — Supports formal resolution language, placard-raising protocol, and delegate speech flow

---

## ⚡ Advanced Features

### ⚔️ Battle Mode
Two users debate each other — or one user debates the AI directly. The AI takes the opposing side and argues back in real time. Not just a static analyzer, but a live sparring partner.

> *Note: Battle Mode is a practice feature. The core PS focuses on teaching correct counterpoints and evaluating arguments — Battle Mode extends this into experiential learning.*

### 🧬 Argument DNA Fingerprinting
After multiple sessions, the AI builds a personal weakness profile:
- *"You consistently concede on economic grounds."*
- *"You over-rely on emotional appeals in Round 2."*

Personalized coaching that evolves with the user — not generic feedback.

### ⏱️ Rebuttal Timing Coach
In BP and MUN formats, *when* you speak matters as much as *what* you say.
- Flags if a counterargument came too late in the speech
- Advises when to save a point for a Point of Information (POI)
- Scores structural placement of rebuttals

### 🔧 Upgrade My Argument
Before delivering your speech, paste a draft. The AI strengthens your own argument — plugging evidence gaps, sharpening logic, and anticipating attacks — before you go live.

---

## 🛠️ Extra Features

### 📄 Export as PDF
Export full debate reports in official formats:
- British Parliamentary layout
- MUN resolution/speech format

### 📊 Progress Tracking Dashboard
Track improvement across sessions:
- Fallacy rate over time (should drop)
- Confidence score trend (should rise)
- Filler word frequency (should decrease)
- Argument strength score history

Turns a one-shot tool into a long-term coaching platform.

### 🗺️ Fallacy Heatmap on Transcript
The full transcript is displayed with fallacy highlights:
- Each flagged sentence is color-coded by severity
- Colors are flat, non-gradient (e.g. red = critical, orange = moderate, yellow = minor)
- Hover to see the fallacy name and explanation

### 🥊 Drill Mode
Instead of just handing over counterarguments, the AI asks Socratic questions to make *you* find the weaknesses yourself:
- *"What evidence supports that claim?"*
- *"What happens to your argument if that premise is false?"*

Forces active strengthening, not passive receiving.

### ⚡ Real-Time Fact Collision Detection
During live speech, the AI detects internal contradictions:
- *"You stated X at minute 1 and Y at minute 3 — these cannot both be true."*
- Alerts are non-interrupting; surfaced after speech ends or flagged on transcript

---

## 📤 Expected Output

| Output | Description |
|---|---|
| Argument Analysis Report | Full breakdown of logic, fallacies, and structure |
| Logical Fallacy Detector | Named fallacies with sentence-level location |
| AI-Generated Counterarguments | 3 hard-to-defeat opposing arguments |
| Speech Delivery Score | Pace, filler words, confidence rating |
| Fallacy Heatmap | Color-coded transcript with severity markers |
| Progress Dashboard | Session-over-session improvement tracking |
| PDF Export | BP or MUN formatted debate report |

---



*Built with 🧠 by Team Heisenberg for mind2i Hackathon — PS-23*
