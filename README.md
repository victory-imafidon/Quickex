# 🚀 QuickEx

QuickEx is a full-featured fintech web platform built for the African market. It allows users to buy airtime, affordable data, pay utility bills, fund wallets, subscribe to TV plans, trade crypto, and generate virtual cards — all in one place.

> ⚡ Built by [Imafidon Victory](https://github.com/victory-imafidon) | Laravel + Bootstrap + JS | Telegram Mini App + TWA + PWA

---

## ✨ Features

- 📱 **Airtime & Data Purchase** – For all major Nigerian networks
- 💳 **Virtual Card Creation** – Secure online payments (via third-party APIs)
- 💡 **Electricity & Utility Bills** – Seamless and fast
- 📺 **TV Subscriptions** – DSTV, GOTV, etc.
- 🪙 **Crypto Trading** – Buy/Sell BTC, USDT, and more at competitive rates
- 🧾 **Wallet System** – Transaction history, secure balance, and fraud prevention
- 📣 **Telegram Mini App** – Light, mobile-first experience
- 🌐 **PWA/TWA Support** – Install as an app on Android with offline capabilities

---

## 🛠 Built With

- **Backend:** PHP (Laravel), MySQL
- **Frontend:** Bootstrap 5, JavaScript
- **Mobile Support:** PWA / TWA for Android
- **Third-Party APIs:** Paystack, Monnify, VTPass, etc.
- **Cloud:** Deployed on VPS (Linux), GCP ready

---

## 🔐 Security & Fraud Protection

- OTP verification for wallet funding
- Smart monitoring for unusual transaction behavior
- Webhook integration with payment processors

---


---

## 📦 Getting Started (Dev Mode)

```bash
git clone https://github.com/yourusername/quickex.git
cd quickex
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
