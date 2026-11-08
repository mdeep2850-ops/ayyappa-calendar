# 🕉️ అయ్యప్ప భిక్ష క్యాలెండర్ (Ayyappa Biksha Calendar)

![Release](https://img.shields.io/badge/Release-v1.0.0-orange?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Vercel%20%7C%20GitHub-blue?style=flat-square)

A modern, mobile-first single-page web application designed for Ayyappa Swamy devotees and Guruswamys during the sacred Mandala Deeksha season to easily organize, view, and share **భిక్ష (Biksha / Afternoon Lunch)** and **అల్పాహారం (Alpharam / Night Tiffin)** schedules.

---

## 🌟 Key Features

- **Mobile-First Sacred Design**: Clean, responsive layout with spiritual aesthetics (Sacred Ivory `#FAF7F2` and Terracotta `#C2410C`), optimized for high-contrast viewing under sunlight.
- **Interactive Calendar Grid**:
  - Distinct high-contrast indicator dots: Emerald Green for Biksha and Royal Indigo for Alpharam.
  - One-tap date selection to filter schedules.
  - **"Today (ఈ రోజు)"** instant filter pill with dedicated filter reset button.
- **Strict 12-Hour AM/PM Time Format**:
  - Eliminates 24-hour confusion across all event cards, modal dropdowns, and WhatsApp invites.
  - Auto-fills default timings (**12:30 PM** for Biksha, **08:00 PM** for Alpharam) with manual override.
- **Bilingual Support (తెలుగు / English)**:
  - Instant one-tap language switch.
  - Dynamic client-side translation engine for Guruswamy user posts (Host names, addresses, announcements).
- **Guruswamy Admin Portal (PIN: 108)**:
  - Secure modal with non-overlapping header layout (touch target ≥ 44×44px).
  - Add, edit, and delete Biksha and Alpharam schedules.
  - Publish urgent broadcast banner tickers across all devotee screens.
- **1-Click WhatsApp Direct Invite**: Generates formatted Telugu/English invitation cards with event type, date, 12-hour time, host details, and optional Google Maps navigation link.
- **Automatic Midnight Cleanup**: Events scheduled for past dates are automatically purged at midnight (12:00 AM) and on tab focus.
- **Firebase Realtime Database Sync**: Seamless real-time synchronization across all devices and offline local storage fallback.

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, Tailwind CSS (CDN), Vanilla JavaScript (ES6+)
- **Icons**: Lucide Icons
- **Database**: Firebase Realtime Database
- **Hosting**: Vercel / GitHub Pages / Any static hosting provider

---

## 🚀 Getting Started

Simply open `index.html` in any modern web browser or serve it via a static file server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js npx serve
npx serve .
```

---

## 📜 License

MIT License. Swamiye Saranam Ayyappa! 🌿

