# Kaaf Academy – Online Quran Teaching Website

Welcome to the **Kaaf Academy** website repository. This responsive, single-page site presents the services of Kaaf Academy – an online platform that offers personalised Quran learning with certified teachers.

<p align="center">
  <img alt="Kaaf Academy Hero" src="assets/images/hero/hero.png" width="600"/>
</p>

---

## ✨ Key Features

| Section | Highlights |
|---------|------------|
| **Hero** | Striking headline, custom scroll indicator, call-to-action buttons (Explore Courses / Free Trial) |
| **Courses** | Four course cards with pricing, hover effects and icons (Tajweed, Tafseer, Hifz, Noorani Qaida) |
| **Why Choose Us** | Six feature cards (Certified Teachers, Flexible Schedule, One-on-One Sessions, etc.) |
| **About Teacher** | Biography of *Hafiza Kainat Noor* with social links and layered image shadow effect |
| **Teaching Methodology** | Vertical timeline explaining the 4-step learning process |
| **Testimonials** | Swiper-enabled carousel of student reviews |
| **FAQ** | Accordion component with common questions |
| **Contact** | WhatsApp floating button, contact form & social icons |
| **UX Enhancements** | Pre-loader SVG animation, custom cursor icons, smooth scrolling, card hover effects |

## 🛠️ Tech Stack

* **HTML5** – semantic markup
* **Tailwind CSS** – utility-first styling (compiled to `assets/css/output.css`)
* **Font Awesome 6** – iconography
* **Google Fonts** – *Lato* & *Reem Kufi Fun*
* **Vanilla JavaScript** – mobile menu toggle, accordions, Swiper initialisation, etc.

> Tailwind was built locally with the CLI:  
> `npx tailwindcss -i ./assets/css/style.css -o ./assets/css/output.css --watch`

## 📂 Project Structure

```
Kaaf_Academy/
├── assets/
│   ├── css/
│   │   ├── style.css          # Tailwind directives & custom rules
│   │   └── output.css         # Compiled production CSS
│   ├── images/                # All imagery & illustrations
│   └── cursors/               # Custom cursor PNGs
├── index.html                  # Main single-page application
└── README.md                   # ← you are here
```

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/s5sajid/kaaf
   ```
2. **Open** `index.html` directly in your browser **or** serve the folder with any static server, e.g.:
   ```bash
   npx serve .
   ```
3. For development, rebuild Tailwind when you modify `assets/css/style.css`:
   ```bash
   npx tailwindcss -i ./assets/css/style.css -o ./assets/css/output.css --watch
   ```

## 🖌️ Customisation

* **Branding / Colours** – Edit Tailwind config (if present) or override in `style.css`.
* **Content** – Update text & images in `index.html`.
* **Assets** – Replace images in `assets/images` & cursor PNGs in `assets/cursors`.

## 🤝 Contributing

Pull requests are welcome! If you have suggestions for improvements, please follow these steps:

1. Fork the repo & create your feature branch: `git checkout -b feature/awesome-feature`
2. Commit your changes: `git commit -m "Add awesome feature"`
3. Push to the branch: `git push origin feature/awesome-feature`
4. Open a pull request

Make sure your code follows the existing style, includes meaningful comments, and is lint-free.

## 🛡️ License

This project is licensed under the **MIT License** – see the [`LICENSE`](LICENSE) file for details.

## 📞 Contact
[Portfolio](https://s5sajid.github.io/)
---

> Built with ❤️ & commitment by [SajidUllah Shahi](https://s5sajid.github.io/).
