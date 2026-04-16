# 🐔 Chicken Road | Telegram Mini App

**Chicken Road** is a high-octane, arcade-style survival game built exclusively for the Telegram ecosystem. Designed for instant play, it leverages the Telegram Mini App (TMA) platform to provide a seamless, "no-install" gaming experience.

---

## 🎮 Game Features
- **One-Tap Mechanics:** Simple, addictive gameplay optimized for mobile.
- **Instant Authorization:** Zero-friction login. The app automatically recognizes your Telegram identity using `initData`.
- **Global Leaderboards:** Compete against friends and the world for the top spot.
- **Real-Time Backend:** Powered by **Daphne (ASGI)** for high-concurrency and smooth performance.

---

## 🛠 Tech Stack
- **Backend:** [Django 5.0+](https://www.djangoproject.com/)
- **ASGI Server:** [Daphne](https://github.com/django/daphne)
- **Frontend:** HTML5 Canvas & Vanilla JavaScript
- **SDK:** [Telegram Web Apps SDK](https://core.telegram.org/bots/webapps)
- **Deployment:** [Render](https://render.com/)

---

## 🚀 Getting Started

### 1. Project Initialization
```bash
# Create project
django-admin startproject chikenroad .

# Install dependencies
pip install django daphne requests python-decouple
