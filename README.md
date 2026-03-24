# ⚡ Stremio Setup Optimizer

A high-performance, single-page setup wizard for Stremio. This tool simplifies the configuration of debrid-based addons by applying "Guided Defaults"—automatically pairing the best scrapers and catalogs for a faster, higher-quality experience.

## 🚀 Live Demo
**[Launch the Optimizer](https://outatime83.github.io/Stremio-Setup-Optimizer/)**
*(Note: Replace YOUR-GITHUB-USERNAME with your actual username after hosting)*

## ✨ Key Features
* **Global Content Preferences:** Set your preferred audio and subtitle languages once; the tool automatically carries them into every addon configuration.
* **Guided Scraper Pairings:** Choose from optimized presets like "Speed + Stability" (Torrentio + MediaFusion) or "Coverage First" (Torrentio + Sootio).
* **Debrid Integration:** Full native support for **Real-Debrid**, **AllDebrid**, and **Premiumize**.
* **Free (No Debrid) Mode:** A dedicated path for users without subscriptions, utilizing public Torrentio instances.
* **Privacy-First Design:** This is a static "client-side" application. Your API tokens are never sent to a server; they are only used locally in your browser to build your installation links.

## 🛠 Supported Addons & Scrapers
Based on the current version, this optimizer configures:
* **Scrapers:** Torrentio, MediaFusion, and Sootio.
* **Catalogs:** Streaming Catalogs and CyberFlix for better content discovery.
* **Utilities:** Trakt integration for syncing your watch history.

## 📖 How to Use
1.  **Set Preferences:** Select your languages and toggle "Strict Language Match" if desired.
2.  **Connect Debrid:** Select your provider and paste your API key (links to find your key are provided in the wizard).
3.  **Choose a Pairing:** Pick a recommended scraper preset or switch to "Manual Mode" for full control.
4.  **Generate & Install:** The tool generates unique `stremio://` links. Click them to install each addon directly into your Stremio app.

## 🔒 Security & Safety
This tool is hosted via GitHub Pages and runs entirely on your local machine. 
* **No Databases:** Your data is never stored.
* **Open Source:** You can inspect the `index.html` file to see exactly how your API tokens are used to generate links.

---
*Optimized for faster, high-quality streaming — Clean. Fast. Minimal.*
