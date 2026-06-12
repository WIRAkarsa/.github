<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=32&pause=1000&color=6366F1&center=true&vCenter=true&width=600&lines=Welcome+to+WIRAkarsa+%F0%9F%9A%80;Building+the+Future+of+Tech+Careers" alt="Typing SVG" />

<br/>

**WIRAkarsa** is an MBKM program initiative dedicated to building **Wirapath** — an AI-powered platform that helps students evaluate tech readiness, bridge skill gaps, and prepare for real-world internship roles.

<br/>

[![Frontend](https://img.shields.io/badge/Frontend-Next.js%2014-black?style=for-the-badge&logo=nextdotjs)](https://github.com/WIRAkarsa/Wirapath-fe)
[![Backend](https://img.shields.io/badge/Backend-Express.js-339933?style=for-the-badge&logo=nodedotjs)](https://github.com/WIRAkarsa/Wirapath-be)
[![Mobile](https://img.shields.io/badge/Mobile-Flutter-02569B?style=for-the-badge&logo=flutter)](https://github.com/WIRAkarsa/Wirapath-mobile)
[![AI](https://img.shields.io/badge/AI%20Model-Keras%20%2B%20Flask-FF6F00?style=for-the-badge&logo=tensorflow)](https://github.com/WIRAkarsa/Wirapath-ai)

</div>

---

## 🌟 About Wirapath

> **Your Path to Success** — Wirapath empowers aspiring tech professionals by identifying their strengths, uncovering skill gaps, and simulating real internship experiences through AI-driven tools.

Whether you're a student preparing for your first internship or a career switcher exploring the tech world, Wirapath guides you every step of the way.

---

## 🗂️ Repositories

### 🌐 [Wirapath-fe](https://github.com/WIRAkarsa/Wirapath-fe) — Web Frontend
> The web-based client application powering the Wirapath dashboard experience.

- **Framework**: Next.js 14 (App Router) + TypeScript
- **Styling**: Tailwind CSS + Lucide React
- **Key Pages**: Dashboard, Skill Assessment, Onboarding, Dev Hub, Profile
- **Highlights**: GitHub OAuth integration, AI-powered CV screening, real-time scoring

```bash
git clone git@github.com:WIRAkarsa/Wirapath-fe.git
cd Wirapath-fe && pnpm install && pnpm dev
```

---

### ⚙️ [Wirapath-be](https://github.com/WIRAkarsa/Wirapath-be) — Web Backend
> REST API powering all platform features — auth, assessments, leaderboard, and more.

- **Framework**: Express.js + TypeScript
- **Database**: MySQL (Docker / XAMPP)
- **Key Features**: JWT Auth, skill gap analytics, DB-backed activity tracking, mini-project submissions
- **DevOps**: Docker Compose for one-command local setup

```bash
git clone git@github.com:WIRAkarsa/Wirapath-be.git
cd Wirapath-be && pnpm install && docker compose up -d && pnpm dev
```

---

### 📱 [Wirapath-mobile](https://github.com/WIRAkarsa/Wirapath-mobile) — Flutter App
> A polished mobile experience for on-the-go career readiness training.

- **Framework**: Flutter (Dart) + Riverpod
- **Key Features**:
  - 🔐 Auth with Google/Facebook & GitHub integration
  - 📋 Readiness Center (Initial, Data Analysis, UX, QA tests)
  - 💻 Dev Hub — hands-on coding challenges with zip submission
  - 🎮 Simulation — AI-powered internship scenario practice
  - 📄 CV Screening with AI analysis
- **Platforms**: Android & iOS

```bash
git clone git@github.com:WIRAkarsa/Wirapath-mobile.git
cd Wirapath-mobile && flutter pub get && flutter run
```

---

### 🤖 [Wirapath-ai](https://github.com/WIRAkarsa/Wirapath-ai) — AI Model & API
> The brain behind Wirapath's skill recommendations — a deep learning model trained to map job titles to required IT skills.

- **Framework**: Flask + Keras (TensorFlow backend)
- **Model**: Multi-label classifier — 251 IT skills
- **Deployment**: Docker + HuggingFace Spaces
- **Key Endpoints**:
  - `GET /health` — liveness check
  - `POST /predict` — returns skill recommendations with confidence scores

```bash
git clone git@github.com:WIRAkarsa/Wirapath-ai.git
cd Wirapath-ai && pip install -r requirements.txt && python app.py
```

---

## 🏗️ Platform Architecture

```
┌─────────────────────────────────────────────────────┐
│                     Users                           │
│          (Web Browser / Mobile App)                 │
└────────────┬──────────────────────┬─────────────────┘
             │                      │
     ┌───────▼──────┐      ┌────────▼────────┐
     │  Wirapath-fe │      │ Wirapath-mobile │
     │  (Next.js 14)│      │   (Flutter)     │
     └───────┬──────┘      └────────┬────────┘
             │                      │
             └──────────┬───────────┘
                        │
               ┌────────▼────────┐
               │  Wirapath-be    │
               │  (Express.js +  │
               │   MySQL)        │
               └────────┬────────┘
                        │
               ┌────────▼────────┐
               │  Wirapath-ai    │
               │  (Flask + Keras │
               │   Deep Learning)│
               └─────────────────┘
```

---

## 🛠️ Tech Stack Overview

| Layer | Technology |
|---|---|
| Web Frontend | Next.js 14, TypeScript, Tailwind CSS |
| Mobile | Flutter, Dart, Riverpod |
| Backend API | Express.js, TypeScript, MySQL |
| AI / ML | Python, Keras, TensorFlow, Flask |
| DevOps | Docker, Docker Compose |
| Auth | JWT, GitHub OAuth |
| AI Hosting | HuggingFace Spaces |

---

## 🚀 Getting Started

To run the full Wirapath stack locally:

1. **Clone all repos** and follow setup instructions in each repository's `README.md`
2. **Start AI service** → `Wirapath-ai` on port `5000`
3. **Start Backend** → `Wirapath-be` on port `5000` (Docker recommended)
4. **Start Frontend** → `Wirapath-fe` on port `3000`
5. **Run Mobile** → `Wirapath-mobile` connected to the backend

---

<div align="center">

Built with ❤️ by the **WIRAkarsa MBKM Team**

*Empowering the next generation of Indonesian tech talent*

</div>
