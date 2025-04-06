# 📁 FixMyCode AI – Folder Structure

This repository contains the complete source code for **FixMyCode AI**, divided into three main parts:

---

## 1. `FixMyCode-AI-dashboard/` – Frontend (Next.js + Tailwind CSS)

- `app/`
  - `api/razorpay.ts` – Razorpay API Integration
  - `dashboard/page.tsx` – Dashboard Page
  - `auth/login.tsx` – Login Page
  - `layout.tsx` – Root Layout
  - `globals.css` – Global Styles
- `components/`
  - `Navbar.tsx`
  - `Sidebar.tsx`
  - `ReportCard.tsx`
- `lib/`
  - `auth.ts`
  - `api.ts`
- `public/` – Assets
  - `images/`
  - `favicon.ico`
- `package.json` – Dependencies
- `tailwind.config.js` – Tailwind Configuration
- `tsconfig.json` – TypeScript Configuration

---

## 2. `FixMyCode-AI-backend/` – Backend (Flask + AI Services)

- `app/`
  - `__init__.py` – Flask Initialization
  - `routes.py` – API Routes
  - `models.py` – Data Models
  - `ai_service.py` – AI Logic
  - `utils.py` – Helper Functions
- `tests/`
  - `test_routes.py`
  - `test_ai_service.py`
- `config.py` – Configuration File
- `requirements.txt` – Python Dependencies
- `.env` – Environment Variables
- `run.py` – Entry Point for Flask App

---

## 3. `FixMyCode-AI-extension/` – VS Code Extension

- `src/`
  - `extension.ts` – Main Entry
  - `api.ts` – API Calls
  - `auth.ts` – Auth Logic
  - `utils.ts`
- `assets/`
  - `icon.png`
  - `manifest.json`
- `package.json` – NPM Dependencies
- `tsconfig.json` – TypeScript Config
- `webpack.config.js` – Webpack Config

---

## Root Files

- `.gitignore`
- `README.md` – Main Project Overview

---

Let me know if you want to add a logo, license, or deployment instructions!
