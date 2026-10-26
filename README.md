# 🌙 Zakat & Fitra Statement Calculator

A professional, privacy-first **Single Page Application (SPA)** and **Progressive Web App (PWA)** built for calculating, tracking, and generating formal statements for annual Zakat and Sadaqah al-Fitr obligations. 

Featuring real-time currency conversion, bi-directional asset-to-debt mapping, live visual liability ratios, multi-language support (English & Bangla), and direct PDF export capabilities.

🚀 **Live Preview:** [https://SAHimu369.github.io](https://SAHimu369.github.io/zakat-statement) *(Configure repository GitHub Pages)*

---

## ✨ Key Features

- 🧮 **Comprehensive Asset Assessment:** Clean categorization for Precious Metals (Gold/Silver), Cash & Bank Balances, Investments/Stocks, and Liabilities/Debts.
- 💱 **Dual-Currency Real-Time Sync:** Effortlessly input assets in either local currency (e.g., BDT, USD, EUR, GBP) or foreign currency (e.g., SAR, AED) with live adjustable exchange rates.
- 🌐 **Multi-Language Localization (i18n):** Instant switching between **English** and **Bangla (বাংলা)** with fully reactive interface text translation.
- 📊 **Visual Asset-to-Debt Ratio Bar:** Dynamic graphical progress bar that visually tracks liabilities as a percentage of gross assets.
- 💾 **State Persistence:** Local storage automation saves your ongoing statement entries securely in your browser so data is never lost on refresh.
- 📄 **Professional PDF Export:** Powered by `html2pdf.js` to render crisp, formatted downloadable statement receipts instantly.
- 🖨️ **Print-Friendly CSS (`@media print`):** Optimized print styles that strip away dark UI themes and controls when printing directly to paper, saving ink and aligning with official financial statement formatting.

---

## 🛠️ Tech Stack

- **HTML5:** Semantic architecture with modern responsive meta tags.
- **CSS3:** Custom CSS variables (`:root`), Flexbox grid layout, custom responsive breakpoints, and dedicated `@media print` rules.
- **Vanilla JavaScript (ES6+):** Reactive DOM state binding, currency math logic, and automated `localStorage` state preservation.
- **html2pdf.js:** Client-side vector and canvas PDF generation pipeline.
- **Google Fonts:** Clean financial typography featuring *Plus Jakarta Sans* and *JetBrains Mono*.

---

## 📂 Project Structure

```text
├── index.html       # Complete single-page application (Markup, CSS, & Logic)
├── manifest.json    # PWA configuration manifest for app installation
├── sw.js            # Service worker for offline asset caching
└── README.md        # Project documentation
