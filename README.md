# JUCOCH — Anonymous Mental Health & Campus Wellness Platform

> **Capstone Project 2026** • Landing Page & Direct Android APK Download Portal

---

## 🌿 Overview
**JUCOCH** is an anonymous mental health and emotional resilience mobile application built with **React Native Expo**, **Google Gemini AI**, **PostgreSQL (Neon)**, and **Express TypeScript**. It is engineered to protect student identity with real-time asterisk masking and zero-PII storage while providing continuous emotional tracking and AI-driven support.

---

## 🚀 Live Evaluation & Access Portals
- **Option 1: Direct Android APK Build:** [Expo EAS Cloud Build Link](https://expo.dev/accounts/bearoy/projects/jucoch-wellness/builds/28bc7b6f-9b6f-42ab-8cd1-a4c7a067419a)
  - Full standalone Android app installation (Android 8.0+).
- **Option 2: Live Local Web App (LAN):** `http://192.168.0.106:8081/`
  - Instant browser access for iOS (Safari), Android (Chrome), and PC laptops.
  - Requires the host machine to run `npx expo start --web` (or dev server) and all devices connected to the same Wi-Fi network / hotspot.
- **Dynamic Dual QR Codes:** Dynamically generated in `index.html` via QRServer API for instant mobile phone camera scanning for both APK download and Web access.

---

## 💻 1-Click Vercel Deployment

This project is a standalone, single-file production-ready static site. You can deploy it to Vercel in seconds:

### Method 1: Push to GitHub & Connect to Vercel
1. Initialize a git repository and commit:
   ```bash
   git init
   git add .
   git commit -m "feat: initial JUCOCH landing page"
   ```
2. Push to your GitHub / GitLab repository.
3. Import the repository in [Vercel Dashboard](https://vercel.com/new).
4. Click **Deploy** (Zero configuration needed).

### Method 2: Vercel CLI
```bash
npm install -g vercel
vercel
```

---

## 🎨 Theme & Architecture
- **Palette:** Emerald Green (`#2D6A4F`), Deep Forest (`#1B4332`), Soft Sage (`#52B788`), Pastel Mint (`#D8F3DC`)
- **Frontend Stack:** Expo React Native (TypeScript), React Native Paper
- **Backend Stack:** Express.js (TypeScript), Prisma ORM, Neon Serverless PostgreSQL
- **AI Integration:** Google Gemini AI
