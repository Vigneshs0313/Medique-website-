# 🩺 MediQueue — Hospital Queue & Appointment Booking Website

> **Skip the wait, not the care.**

A fully responsive, production-styled website concept for booking doctor appointments and tracking hospital queues in real time — designed and built as a UX/UI + front-end portfolio project.

**🔗 Live Demo:** [https://vigneshs0313.github.io/mediqueue-website/](https://vigneshs0313.github.io/mediqueue-website/)

---





---

## ✨ What This Is

MediQueue solves a simple, real problem: patients waiting in hospital lobbies with zero visibility into how long it'll take. This project reimagines that experience as a modern booking website — in the spirit of how Practo, BookMyShow, or Myntra structure their product/listing/checkout flows — applied to healthcare.

It's built as a **single, self-contained HTML file**. No build step, no dependencies, no backend required to view it — open it and the whole experience works in the browser.

## 🧱 Core Features

- **Homepage** — hero search bar, specialty quick-links, top-rated doctor grid, trust stats
- **Doctor Search** — filter sidebar (specialty, availability, fee, rating) + sortable results grid
- **Doctor Profile** — tabbed detail page (About / Reviews / Location) with a sticky booking widget
- **Booking Flow** — 4-step checkout (Slot → Patient Details → Payment → Confirmation) ending in an e-ticket-style confirmation with a live queue token
- **Live Queue Tracking** — order-tracking-style timeline showing real-time position and estimated wait
- **My Account** — appointments, medical records, saved doctors, family members, settings
- **Emergency Priority** — a flagged fast-path for urgent cases
- **AI Symptom Checker** — floating chat widget for preliminary guidance
- **Staff Console** — a separate dashboard app for doctors (queue management: call next, pause/resume, mark complete) and admins (hospital-wide analytics, doctor/patient tables, report generation)
- **Fully responsive** — collapses gracefully from desktop down to mobile (hamburger nav, stacked grids, sticky mobile CTA bar)

## 🛠️ Tech Stack

Vanilla **HTML, CSS, and JavaScript** — no frameworks, no build tools, no npm install. Chosen deliberately so the entire project is viewable by opening one file in any browser, with zero setup friction for anyone reviewing it (recruiters included).

## 🎨 Design System

| Token | Value |
|---|---|
| Primary | `#2563EB` (Clinical Blue) |
| Secondary | `#0D9488` (Care Teal) |
| Typography | Manrope (headings) + Inter (body) |
| Motion | Calm, ≤400ms transitions — deliberately avoids playful/jarring motion given the healthcare context |

Full design rationale (color, type, accessibility, motion principles) is documented inline in the project and available on request.

## 🚀 Running Locally

No installation needed:

```bash
git clone https://github.com/Vigneshs0313/mediqueue-website.git
cd mediqueue-website
open index.html   # or just double-click the file
```

## 🗺️ Roadmap

- [ ] Connect to a real backend (FastAPI + SQLite version available — ask for the full-stack repo)
- [ ] Real-time queue updates via WebSocket instead of static demo data
- [ ] Multi-language support (Tamil, Hindi)
- [ ] Insurance verification at booking
- [ ] Predictive wait-time model based on historical consultation data

## 👤 About

Built by **Vignesh** ([@Vigneshs0313](https://github.com/Vigneshs0313)) — B.E CSE (AIML) student, as part of an ongoing UX/UI design and front-end development portfolio.

---

⭐ If you found this useful or interesting, consider starring the repo!
