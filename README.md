# Yakana Space — Landing Page

> **Democratizing access to scientific outreach.**

This repository contains the official landing page for **Yakana Space**, a decentralized, open-source platform designed to connect science communicators, research institutions, and communities through interactive regional maps, live event calendars, AI-powered indexing, and collaborative peer validation.

## ✨ Why *Yakana*?

In Andean astronomy, the **Yakana** is the great dark-cloud constellation of the celestial llama walking along the Milky Way river (*Mayu*), with two bright stars shining as her eyes: Alpha and Beta Centauri (*Llamacñawin*).

Just as Andean observers learned to read the dark spaces between the stars to navigate, **Yakana Space** brings structure and visibility to fragmented scientific outreach—bridging ancestral curiosity with open technology and artificial intelligence.

## 🧩 Landing Page Features

* **Minimalist Astronomical Design:** Dark-mode aesthetic inspired by star charts, featuring a subtle astronomical grid, astrolabe arcs, and inline SVG illustrations of the Yakana and Uña Yakana dark-cloud constellations.
* **Bilingual Support (ES / EN):** Built-in vanilla JavaScript language switcher that translates the entire interface instantly without reloading the page.
* **Single-File Architecture:** All markup, styles, and logic live inside `index.html` with zero build steps required.
* **Fully Responsive:** Optimized for mobile, tablet, and desktop viewports, including a collapsible mobile navigation menu.
* **Included Sections:**
  * **Hero:** Core value proposition and astronomical reference coordinates ($\alpha$ & $\beta$ Centauri).
  * **The Yakana (`#origen`):** Custom SVG star chart and story connecting Andean mythology with open science.
  * **Features (`#caracteristicas`):** Overview of the 6 ecosystem pillars (Interactive Regional Map, Live Events Calendar, AI Search & Indexing, Peer-Validated Scripts, Community Ownership, and Social & Sources Hub).
  * **Peer Review (`#validacion`):** 3-step community review workflow alongside a peer-validated script preview.
  * **Open Source (`#opensource`):** Call to action for contributors with direct links to GitHub and Instagram.

## 🛠️ Tech Stack

* Semantic **HTML5**
* **Tailwind CSS** (via CDN)
* **Vanilla JavaScript** for bilingual toggling and mobile navigation
* **Inline SVG** for the brand mark and astronomical illustrations
* **Google Fonts:** `Inter` and `JetBrains Mono`

## 🚀 Getting Started & Deployment

Because this is a zero-build static site, you can preview or deploy it in seconds:

### Local Preview

1. Clone the repository:

   ```bash
   git clone https://github.com/yakanaspace/landing.git
   cd landing
   ```

2. Open `index.html` directly in your browser, or run a lightweight local server:

   ```bash
   npx serve .
   # or using Python
   python3 -m http.server 8000
   ```

### Deploying to GitHub Pages

1. Push `index.html` to the `main` branch of your repository.
2. Navigate to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, select the `main` branch and `/ (root)` folder.
4. Save your changes and the site will be live within a few minutes.

## 🤝 Contributing

Contributions are welcome! If you'd like to refine the design, add translations, or improve accessibility:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feat/your-improvement`).
3. Commit your changes (`git commit -m "feat: describe your improvement"`).
4. Push to your branch (`git push origin feat/your-improvement`) and open a **Pull Request**.

## 🌐 Official Links

* **Website:** [yakana.space](https://yakana.space)
* **GitHub:** [github.com/yakanaspace](https://github.com/yakanaspace)
* **Instagram:** [@yakana.space](https://www.instagram.com/yakana.space)

## 📄 License

This project is licensed under the **GNU General Public License v3.0 (Version 3, 29 June 2007)**.

See the [LICENSE](LICENSE) file in this repository or visit [gnu.org/licenses/gpl-3.0](https://www.gnu.org/licenses/gpl-3.0.en.html) for the full license text.
