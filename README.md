# 🚗 Morya Cars — Premium Pre-Owned Luxury Website

A scroll-driven, 3D animated website for **[Morya Cars Pvt. Ltd.](https://www.moryacars.in)** — India's premier pre-owned luxury car dealership. Built with GSAP ScrollTrigger, Lenis smooth scroll, and canvas-based video frame playback.

![Morya Cars Preview](https://www.moryacars.in/images/logo1.png)

---

## ✨ Features

- 🎬 **270-frame scroll-driven video** — car animates as you scroll
- 🔵 **Circle-wipe hero reveal** — cinematic canvas entrance
- 🎞️ **7 scroll sections** — each with a unique GSAP animation type
- 📊 **Animated stat counters** — numbers count up from 0
- 🏷️ **Dual scrolling marquees** — brand names + city names
- 🌙 **Dark luxury aesthetic** — gold + deep black palette
- 🖱️ **Custom gold cursor** with expand on hover
- 📣 **Ad widgets** — floating EMI offer + ticker banner
- 📱 **Fully responsive** — mobile optimised
- ⚡ **Two-phase frame preloader** — fast first paint

---

## 🗂️ Project Structure

```
morya-cars/
├── index.html          # Main HTML — all sections & structure
├── css/
│   └── style.css       # All styles — variables, layout, animations
├── js/
│   └── app.js          # GSAP + Lenis + canvas scroll logic
├── frames/
│   ├── frame_0001.webp # 270 WebP frames extracted from video
│   ├── frame_0002.webp
│   └── ...
├── .gitignore
└── README.md
```

---

## 🚀 Local Development

> ⚠️ Must be served over HTTP — frames won't load from `file://`

**Option 1 — Python (no install)**
```bash
cd morya-cars
python -m http.server 8000
# Open http://localhost:8000
```

**Option 2 — Node serve**
```bash
npx serve .
```

**Option 3 — VS Code Live Server**
Install the Live Server extension → right-click `index.html` → Open with Live Server

---

## 🌐 Deploy to Netlify (Free, 1 minute)

1. Go to **[netlify.com/drop](https://netlify.com/drop)**
2. Drag the entire `morya-cars/` folder onto the page
3. Get a live URL instantly — e.g. `https://morya-cars.netlify.app`

---

## 🎨 Tech Stack

| Tool | Purpose |
|------|---------|
| [GSAP 3](https://gsap.com) | ScrollTrigger, animations, counters |
| [Lenis](https://lenis.studiofreight.com) | Buttery smooth scroll |
| HTML5 Canvas | Frame-by-frame video playback |
| WebP frames | Compressed video frames (270 total) |
| Vanilla JS | No framework, no bundler |
| Google Fonts | Cormorant Garamond + Rajdhani |

---

## 🏢 Brand Info

**Morya Cars Pvt. Ltd.**
- 🌐 [moryacars.in](https://www.moryacars.in)
- 📞 Buy: +91 88880 98877
- 📞 Sell: +91 88880 08877

**Showroom Locations:**
- Andheri West, Mumbai
- Powai, Mumbai
- Thane (W)
- Sanpada, Navi Mumbai
- Baner, Pune
- Nashik
- Al Quoz, Dubai 🇦🇪

**Brands Available:**
Mercedes-Benz · BMW · Audi · Porsche · Land Rover · Bentley · Jaguar · Aston Martin · Volkswagen · Volvo · and more

---

## 📄 License

This website was built for Morya Cars Pvt. Ltd. All brand assets and trademarks belong to their respective owners.

---

*Built with ❤️ — scroll-driven luxury experience*
