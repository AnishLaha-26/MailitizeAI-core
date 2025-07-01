# ⚙️ Mail App Core

This is the secure local backend of the Mail Assistant — a privacy-first, intelligent desktop email client that helps users stay focused and respond to the most important messages without distraction.

This repo contains all backend functionality powered by [Tauri](https://tauri.app) and written in **Rust**, including:
- User login and session handling
- OAuth2 integration with Gmail and Outlook (Microsoft Graph)
- Local encrypted storage of tokens and metadata
- Background email sync and polling
- Urgency classification via local AI
- Native system notifications and cross-device alert triggers

---

## 🔧 Features

- 🔐 Secure email/password login (with optional OAuth)
- ✉️ Gmail & Outlook Workspace API integration
- 🧠 AI-based classification (urgent vs non-urgent)
- 📦 Local-first storage using SQLite
- 🔔 System notifications and optional mobile pings (Telegram/FCM)
- 🚀 Auto-launch and background polling on boot

---

## 🧱 Project Structure

