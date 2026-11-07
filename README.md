# The Family Boardroom

> Break the churn. Build intentional family outcomes.

**The Family Boardroom** is a lightweight, privacy-first mobile application designed to help families cut through daily household chaos using strategic leadership frameworks, rotating daily insights, daily outcome tracking, and an automated Saturday accountability review.

---

## 🌟 Key Features

* **Rotating Leadership Insights:** Access a built-in database of 500 leadership principles, quotes, micro-actions, and strategic lenses. The engine serves 3 fresh insights daily based on the calendar day without repeating.
* **Daily Action & Thought Logging:** Dedicated reflection spaces for every day of the week (Monday through Sunday) to track personal thoughts, leadership decisions, and family wins.
* **Saturday In-App Accountability Banner:** Automatically alerts users every Saturday (or when unworked days exist) to review weekly progress, flag missed days, and conduct a strategic alignment check.
* **100% Privacy & Local Storage:** All notes, preferences, and tracking stay entirely on your device using browser `localStorage`. No external servers, accounts, or data tracking required.
* **Automated Cloud Builds:** Powered by GitHub Actions to automatically compile ready-to-install Android APKs on every code push.

---

## 🏗️ Technical Architecture

* **Frontend:** Single-page HTML5, CSS3, and modern JavaScript (ES6+).
* **Native Wrapper:** [Capacitor 5](https://capacitorjs.com/) (translates web assets into native Android container).
* **CI/CD Pipeline:** GitHub Actions (`.github/workflows/build-apk.yml`).

---

## 📁 Repository Structure

```text
.
├── .github/
│   └── workflows/
│       └── build-apk.yml      # CI/CD automated APK build workflow
├── www/
│   └── index.html             # Main application source code & styling
├── capacitor.config.json      # Capacitor project configuration
└── package.json               # Node dependencies for Capacitor CLI
