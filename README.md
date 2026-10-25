# 🚀 Jawbio — Smart Job Tracker & Chrome Extension

[![Live Web App](https://img.shields.io/badge/Live_App-jawbio.vercel.app-2563eb?style=for-the-badge&logo=vercel)](https://jawbio.vercel.app/)
[![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Install_Extension-0f766e?style=for-the-badge&logo=googlechrome)](https://chromewebstore.google.com/detail/jawbio-%E2%80%94-smart-job-tracke/mgkcjaajigcceekhhpmbfbdkppdckdon)

> **Jawbio** is a full-stack SaaS platform and Manifest V3 Chrome Extension designed to automate and streamline the job application tracking workflow across dynamic SPA job boards like **LinkedIn** and **Djinni**.

---

## ✨ Key Features

- **1-Click Job Saving (Chrome Extension):** Automatically extracts job title, company name, location, description, and direct URL directly from the DOM on LinkedIn and Djinni.
- **Centralized Application Dashboard:** Manage your job pipeline across stages (*Saved, Applied, Interviewing, Offer, Rejected*) in a clean, responsive UI.
- **Seamless Cloud Sync:** Instant synchronization between the browser extension and the Next.js web application.
- **Secure Authentication:** Protected user sessions and cross-origin API communication powered by NextAuth.

---

## 🏗️ System Architecture & Tech Stack

This project was engineered end-to-end using **AI-assisted development workflows** combined with modern full-stack and browser automation architecture.

| Layer | Technologies Used |
| :--- | :--- |
| **Frontend & Web App** | Next.js (App Router), TypeScript, React, Tailwind CSS |
| **Backend & ORM** | Next.js API Routes, Prisma ORM, NextAuth |
| **Database** | Neon Serverless PostgreSQL |
| **Browser Extension** | Chrome Extension API (Manifest V3), Content Scripts, DOM Parsing |
| **Deployment** | Vercel (Web App), Official Chrome Web Store (Extension) |

---

## 🧠 Engineering Challenges Solved

1. **Resilient DOM Scraping on Dynamic SPAs:** Engineered custom DOM parsers capable of handling asynchronous content rendering and layout shifts on LinkedIn and Djinni without breaking selector logic.
2. **Cross-Origin Extension-to-Backend Sync:** Implemented secure token/session validation allowing the Manifest V3 background/popup scripts to communicate seamlessly with the Next.js API.
3. **End-to-End Chrome Web Store Compliance:** Configured strict Content Security Policies (CSP), minimal host permissions, and privacy disclosures to pass official Google review.

---

## 🔗 Live Links & Author

- 🌐 **Web Application:** [https://jawbio.vercel.app/](https://jawbio.vercel.app/)
- 🧩 **Chrome Extension:** [Download on Chrome Web Store](https://chromewebstore.google.com/detail/jawbio-%E2%80%94-smart-job-tracke/mgkcjaajigcceekhhpmbfbdkppdckdon)
- 👤 **Author:** **Maksim Kuzubov** — [LinkedIn](https://www.linkedin.com/in/maksim-kuzubov-6664121a2/)
