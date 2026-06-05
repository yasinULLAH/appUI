# Missing Person Alert UI - High-Fidelity PWA Template

A professional, mobile-first, and **Progressive Web App (PWA)** interface designed for high-impact "Missing Person" emergency alerts. This project serves as an authoritative, AI-optimized template for government agencies, NGOs, or families to broadcast critical information with maximum visibility and offline reliability.

## 🚀 Live Demo
- **Standard High-Impact Poster:** [index.html](https://yasinullah.github.io/appUI/index.html)
- **Official Government Emergency Alert:** [index2.html](https://yasinullah.github.io/appUI/index2.html)

---

## ✨ Key Features

### 📱 Progressive Web App (PWA)
*   **Installable:** Can be installed on Android, iOS, and Desktop as a standalone application.
*   **Offline Mode:** Powered by **Workbox**, the app remains functional even without an internet connection, utilizing a custom `offline.html` fallback.
*   **Background Updates:** Integrated auto-update system via `version.json` ensuring users always see the latest alert data.

### 🤖 AI & Search Optimization (AEO/SEO)
*   **Structured Data (JSON-LD):** Fully optimized for AI Search Engines (Perplexity, ChatGPT, Gemini) using Schema.org `Person` and `ContactPoint` schemas.
*   **Rich Social Previews:** Comprehensive Open Graph (OG) and Twitter Card metadata for high-visibility sharing on WhatsApp, Facebook, and X.
*   **Robots-Friendly:** Optimized indexing instructions for search engine crawlers.

### 🎨 Advanced UI/UX
*   **High-Intensity Animations:** CSS-based "Emergency Pulse," "Siren Glow," and "Hazard Strips" to immediately command attention.
*   **Responsive Design:** Recalibrated `cqi` (Container Query) based typography for perfect scaling on all screen sizes.
*   **Dual-Template System:** 
    *   **Standard (`index.html`):** Clean, professional layout for general community alerts.
    *   **Govt Version (`index2.html`):** Authoritative "State Broadcast" aesthetic with "STILL MISSING" badges and high-intensity hazard styling.

### ⚡ Interactive Functions
*   **Native Sharing:** One-tap "Share Alert" button using the Web Share API (Mobile) or Clipboard fallback (Desktop).
*   **Direct Action:** Integrated `tel:` links for instant dialing of emergency helplines and family contacts.

---

## 🏗️ Project Architecture

This project is built with an automated PWA engine to ensure data integrity and offline availability:

*   **`index.html` / `index2.html`**: Core UI templates featuring high-fidelity CSS and SEO metadata.
*   **`sw.js`**: Service Worker using Workbox for smart caching strategies (Precache for core assets, Stale-While-Revalidate for styles/scripts).
*   **`manifest.json`**: Controls the app's installability, splash screens, and theme colors.
*   **`pwa-register.js`**: Handles service worker lifecycle and version-based cache busting.
*   **`build_pwa_...pyw`**: A custom Python engine that automates icon generation, asset discovery, and cache manifest updates.

---

## 💻 Tech Stack
*   **Frontend:** HTML5, CSS3, Tailwind CSS (CDN).
*   **PWA Core:** Workbox 7.0, Service Workers, Web App Manifest.
*   **Optimization:** JSON-LD, Open Graph, Twitter Cards.
*   **Typography:** Google Fonts (Archivo, Barlow Condensed, Inter, Oswald).

---

## ⚙️ Customization & Deployment

1.  **Subject Data:** Edit the name, father's name, age, and location in the "Dossier" or "Data Grid" sections of the HTML files.
2.  **AEO Update:** Ensure you update the `<script type="application/ld+json">` block to match the subject's details for AI search results.
3.  **Images:** Replace `person.png` (Subject Photo) and `UI.jpeg` (Thumbnail).
4.  **PWA Build:** Use the included `.pyw` script to regenerate the Service Worker and `manifest.json` after making file changes.
5.  **Helplines:** Update the `href="tel:..."` links with the correct emergency numbers.

---

## 📄 License & Credits
This is a public service UI project. Feel free to clone, modify, and deploy for any missing person search effort.

**Lead Developer:** Yasin Ullah (Bannu Software Solutions)  
**WhatsApp:** 03361593533  

*Every share counts. Help us bring them home.*
