# HQnews — Autonomous Crypto Editorial Cloud Dispatcher

This repository serves as the public cloud dispatcher for [CryptoCardHQ](https://cryptocardhq.com).

### Architecture
- **Runner Visibility:** Public (grants 100% unlimited, free GitHub Actions runner minutes forever).
- **Security:** Checks out the private core repository securely via encrypted GitHub Secrets (`GH_PAT`).
- **Core Engine:** Runs 6 scheduled daily market drops covering breaking news, Bitcoin scaling, crypto payment cards, DeFi, memecoins, and macro war analytics.
- **Headless Publishing:** Deploys live directly to `https://cryptocardhq.com/api/publish` with zero website rebuilds.
- **Mobile Push Alerts:** Dispatches real-time Telegram hero alerts with interactive read buttons to `@Fomonewzbot`.
