 Balanced Coffee — Landing Page
A clean, simple landing page for Balanced Coffee café, built with pure HTML & CSS. No frameworks, no dependencies.
---
📁 File Structure
```
├── index.html     → Main HTML file (all sections & content)
└── style.css      → All styles (colors, layout, responsive)
```
---
🗂️ Sections
Section	Description
Home	Hero section with café name, tagline, and CTA button
Menu	Tabbed menu — Drinks, Food, Sweets — with prices in USD
About	Story of the café + stats (cups/day, years, satisfaction)
Gallery	CSS grid photo gallery with 5 placeholder slots
Contact	Address, phone, hours, email + contact form
---
🎨 Design
Colors: Pistachio green `#8fac78` + Brown `#6b4c35` on Cream `#f5f0e8`
Fonts: Playfair Display (headings) + Lato (body)
Direction: LTR (English)
Minimal animations — subtle hover effects only
---
🚀 How to Run
Just open `index.html` in any browser — no build step needed.
```bash
open index.html
# or double-click the file
```
> ⚠️ Requires an internet connection to load Google Fonts.
---
🖼️ Adding Real Images
The gallery currently uses emoji placeholders. To replace with real photos:
Open `index.html`
Find the `gallery-placeholder` divs inside `#gallery`
Replace each with an `<img>` tag:
```html
<!-- Before -->
<div class="gallery-placeholder"><span>☕</span><p>Morning Cup</p></div>

<!-- After -->
<img src="your-photo.jpg" alt="Morning Cup" style="width:100%;height:100%;object-fit:cover;" />
```
---
📱 Responsive
Fully responsive on mobile & desktop
Hamburger menu appears on screens under `768px`
Grid layouts stack to single column on mobile
---
📦 Built With
HTML5
CSS3 (CSS Variables, Grid, Flexbox)
Vanilla JavaScript (tabs, smooth scroll, hamburger menu)
Google Fonts
---
> © 2024 Balanced Coffee — All rights reserved
