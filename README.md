<div align="center">

# 🚀 Shrey Gupta — Developer Portfolio

### [LinkedIn](https://linkedin.com/in/shrey-gupta-688314286) · [GitHub](https://github.com/ShreyGUPTA0924)


> **A space-themed, fully interactive personal portfolio** — hand-crafted with vanilla HTML, CSS, and JavaScript. No frameworks. No build tools. Just one file that does a lot.

<br/>

</div>

---

## ✨ What Makes This Different

Most developer portfolios are templates with a name swap. This one isn't. Here's what's inside:

| Feature | Description |
|---|---|
| 🌠 **Dual-tail Comet Cursor** | Custom canvas cursor with nucleus, warm amber dust tail, and blue-white ion tail — like a real comet |
| 🪐 **3D Floating Skill Badges** | 22 skills float in 3D perspective with elastic collision physics — badges bounce off each other and scatter from your cursor |
| 🌍 **Real Orthographic Globe** | Actual continent silhouettes drawn with lat/lon math. India always centred, city markers for Bangalore, Delhi, Mumbai |
| ⭐ **Interactive Star Field** | 260 twinkling stars + random shooting stars. Click anywhere in the hero to fire a custom shooting star from that point |
| 📊 **Animated Impact Counters** | Slow-counting metrics that prove real AI impact: 8-10hrs → 30sec, 700+ cars, 97% accuracy, 30 pages, 8+ tools |
| 🌌 **Skill Constellation** | Interactive star map of all skills — hover for proficiency, click to highlight connections, drag to draw custom constellation lines |
| 💥 **Destroy Easter Egg** | Tiny `×` in the corner. Click it and the page shatters into physics shards. Rebuilds in 1.8 seconds |
| 🎮 **Konami Code** | `↑↑↓↓←→←→BA` triggers purple Matrix rain across the entire page |
| 👀 **DevTools Message** | Open browser console — there's a message waiting for you in purple, teal, and gold |
| 🌌 **Idle Comet Debris** | After 3 seconds of no mouse movement, purple pixel sparks drift downward from the cursor |
| 🎯 **Section Color Coding** | Each section has its own accent color — teal, amber, purple, pink, blue — with gradient headings and tinted backgrounds |
| 📬 **Working Contact Form** | Form submission opens your mail client pre-filled with the visitor's message |
| 🔍 **Project Modals** | Cards show only title + stack. Click → modal slides in with full details, bullet points, GitHub links |

---

## 🛠️ Tech Stack

This entire site is **zero-dependency** vanilla web tech:

```
HTML5 · CSS3 · JavaScript (ES6+) · Canvas API
```

### External Resources (CDN only, no npm)
| Resource | Used For |
|---|---|
| [Google Fonts](https://fonts.google.com) | Outfit (display), Inter (body), JetBrains Mono (labels/code) |

### Browser APIs Used
| API | Purpose |
|---|---|
| `Canvas 2D` | Star field, comet cursor, globe, skill constellation, project illustrations, badge physics |
| `IntersectionObserver` | Scroll-reveal animations + impact counter triggers |
| `CSS Custom Properties` | Section theming, color system, responsive tokens |
| `CSS Animations` | Orb pulse, status dot, scroll hint float, blink cursor, shatter physics |
| `Backdrop Filter` | Nav blur, modal blur background |
| `requestAnimationFrame` | All canvas animations (60fps) |

---

## 📁 File Structure

```
📦 portfolio/
├── index.html              ← The entire site (HTML + CSS + JS, self-contained)
├── SHRY_GUPTA_resume.pdf   ← Resume — must be in same folder for download to work
└── README.md               ← You are here
```

> **That's it.** No `node_modules`, no build step, no config files. Open `index.html` in a browser and it works.

---

## 🗂️ Sections

```
Hero          — Name, typewriter role, stat pills, 3D floating skill badges
About         — Bio covering full-stack + AI/ML, stats card, rotating globe
Experience    — BEL (GenAI Intern, current) · Deepneura (Data Science Intern)
Impact        — Animated counters: real AI impact in numbers
Skills        — Interactive constellation of 19 skills with proficiency tooltips
Projects      — WealthPortal · CategorAIze · Research Agent · AutoAssist
Resume        — One-click PDF download
Contact       — Links + working contact form
```

---

## 🎨 Design System

**Color palette:**

| Token | Hex | Used For |
|---|---|---|
| Background | `#03010A` | Page base |
| Purple | `#A78BFA` | Primary accent, borders |
| Teal | `#5EEAD4` | About section, success states |
| Amber | `#FCD34D` | Experience section, dates, globe cities |
| Pink | `#F472B6` | Projects section, AI/ML skills |
| Blue | `#60A5FA` | Contact section, database skills |

**Typography:**
- Display headings → `Outfit 900`
- Body text → `Inter 400`
- Labels, tags, code → `JetBrains Mono 700`

---

## 🚀 Deployment

### Option A — GitHub Pages (Recommended)

```bash
# 1. Create repo named exactly: YourUsername.github.io
# 2. Push both files:
git init
git add index.html SHRY_GUPTA_resume.pdf
git commit -m "feat: launch portfolio 🚀"
git remote add origin https://github.com/ShreyGUPTA0924/ShreyGUPTA0924.github.io.git
git push -u origin main

# 3. Go to repo Settings → Pages → Source: main branch
# Site is live at https://shreygupta0924.github.io in ~2 minutes
```

### Option B — Netlify (Drag & Drop, 30 seconds)

1. Go to [netlify.com/drop](https://app.netlify.com/drop)
2. Drag your folder (containing `index.html` + `SHRY_GUPTA_resume.pdf`) onto the page
3. Done — live URL generated instantly

**To enable real email delivery with Netlify Forms:**

```html
<!-- In index.html, change the form tag to: -->
<form name="contact" method="POST" data-netlify="true" onsubmit="handleForm(event)">
  <input type="hidden" name="form-name" value="contact" />
  <!-- rest of form stays the same -->
</form>
```
Netlify will email all submissions to your account email. Free up to 100/month.

---

## 🖼️ Adding Project Screenshots

When you have real screenshots or designs for your projects, swap out the animated canvas placeholders:

```html
<!-- In index.html, find the comment for each project: -->

<!-- ▼▼▼ INSERT IMAGE HERE ▼▼▼
     <img src="images/wealthportal.jpg" alt="WealthPortal Preview" class="proj-img"/>
     Then delete the canvas element below.
     ▲▲▲ INSERT IMAGE HERE ▲▲▲ -->
```

1. Create an `images/` folder next to `index.html`
2. Add your screenshot (recommended: 1200×400px, any format)
3. Uncomment the `<img>` line, update the `src`
4. Delete the `<canvas>` line below it

---

## 🐣 Easter Eggs

Found them all?

- [ ] Open DevTools console
- [ ] Type the Konami code: `↑↑↓↓←→←→BA`
- [ ] Click the Destroy in the top-right corner
- [ ] Click anywhere in the hero (star field area)


---

## 📬 Contact

**Shrey Gupta** — ECE + CS @ JIIT Noida (Batch 2027)

[![Email](https://img.shields.io/badge/Email-shreygupta0924%40gmail.com-A78BFA?style=flat-square&logo=gmail&logoColor=white)](mailto:shreygupta0924@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-shrey--gupta--688314286-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/shrey-gupta-688314286)
[![GitHub](https://img.shields.io/badge/GitHub-ShreyGUPTA0924-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ShreyGUPTA0924)
[![Phone](https://img.shields.io/badge/Phone-%2B91%208303881616-5EEAD4?style=flat-square&logo=whatsapp&logoColor=white)](tel:+918303881616)

---

## 📄 License

```
MIT License — feel free to use this as inspiration.
If you fork it, a star ⭐ would be appreciated.
```

---

<div align="center">

**Built by Shrey Gupta** · *co-piloted by Claude AI — proof that vibe coding is a legitimate skill*

`git commit -m "shipped it finally"`

</div>
