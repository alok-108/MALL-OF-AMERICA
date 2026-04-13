```markdown
# Mall of America · Interactive Sales Deck

A cinematic, video‑first sales tool designed for leasing teams, sponsors, and event partners. Built as a self‑contained, browser‑based experience that replaces static PDFs and fragmented presentations.

**Live Demo:** [https://mall-of-america-liart.vercel.app/](https://mall-of-america-liart.vercel.app/)

---

## 🚀 Features

- **Cinematic Video Background** – Immediate impact with an AI‑generated hero loop.
- **Non‑Linear Navigation** – Fixed nav with smooth scrolling; users control their journey.
- **Animated Data Counters** – Key metrics (40M+ visitors, 95% occupancy) animate on scroll.
- **Personalization Toggle** – Switches messaging between "I'm a Brand" and "Event Organizer".
- **GSAP Scroll Animations** – Parallax, fade‑ups, and staggered reveals for a premium feel.
- **Fully Responsive** – Optimized for desktop, tablet, and mobile.
- **Modular Architecture** – Ready to expand with Events, Sponsorships, and Leasing sub‑modules.

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5, CSS3 | Structure & styling (luxury minimal design) |
| JavaScript (ES6) | Interactivity, counters, navigation |
| GSAP 3.12 | Scroll‑triggered animations & parallax |
| Font Awesome 6 | Icons |
| Google Fonts (Inter) | Typography |
| Vercel | Hosting & deployment |

---

## 📁 Project Structure

```
mall-of-america-sales-deck/
├── index.html                                    # Main HTML file (self-contained CSS & JS)
├── Mall_of_America_Video_Links_AI_Generation.mp4 # AI-generated hero video
├── README.md
└── (optional) assets/                            # Additional images if separated
```

> CSS and JavaScript are embedded in `index.html` for simplicity and fast deployment.

---

## 🧠 Design Decisions

### Visual & UX
- **Dark Theme + Gold Accents** – Conveys luxury and confidence, aligning with high‑end retail.
- **Video‑First Storytelling** – Hero video autoplays muted with a radial gradient overlay.
- **Clean Typography** – Inter font with large, impactful headlines (`6.5rem` on desktop).
- **Scroll‑Triggered Reveals** – `.fade-up` elements animate in as the user scrolls.

### Technical
- **GSAP ScrollTrigger** – Performant parallax and staggered hero text animation.
- **Intersection Observer** – Triggers counter animations only when the section enters viewport.
- **Persona Toggle** – Updates hero copy and primary CTA based on selected audience.
- **Responsive Breakpoints** – Grid collapses at `900px`; font sizes scale down.

### Expandability
The code is structured to easily add sub‑modules using existing grid and card patterns.

---

## 🤖 AI Tools Used

| Tool | Usage |
|------|-------|
| **AI Video Generation** | Created the hero background loop (`Mall_of_America_Video_Links_AI_Generation.mp4`). |
| **AI Image Prompting** | Prepared Midjourney/DALL·E prompts for custom retail and event visuals. |
| **AI Copy Assistance** | Refined headlines and value propositions for impact. |

---

## 🚦 Getting Started

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/alok-108/mall-of-america-sales-deck.git
   ```
2. Navigate to the project folder:
   ```bash
   cd mall-of-america-sales-deck
   ```
3. Open `index.html` in your browser (no build step required).

### Deployment
The project is deployed on [Vercel](https://vercel.com/). To deploy your own:
1. Push the code to a GitHub repository.
2. Import the repository into Vercel.
3. Vercel will automatically detect the static site and provide a live URL.

---

## 📈 Performance

- Images use `loading="lazy"` to defer off‑screen assets.
- Video is hosted locally for reliability.
- GSAP animations are batched and use `requestAnimationFrame`.

---

## 🔮 Future Improvements

- [ ] Replace placeholder images with AI‑generated, brand‑consistent visuals.
- [ ] Build a **Sponsorship Module** with tiered cards and an ROI calculator.
- [ ] Add a **Leasing Paths** interactive map.
- [ ] Implement a **Venue‑Specific Module** for JW Marriott and event spaces.
- [ ] Add subtle, user‑initiated sound design.
- [ ] Convert video to WebM for broader browser support.

---

## 👤 Contact

**Alok Pandey**  
Email: [valok8592@gmail.com](mailto:valok8592@gmail.com)  
GitHub: [alok-108](https://github.com/alok-108)

---

## 📄 License

This project is intended for demonstration purposes as part of an interview process. All trademarks and assets belong to their respective owners.
```
