# ramadan-prompting-night1
RAmadan Landing page via prompting with only html and css
# ☪ Ramadan Prompting Nights — Landing Page

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

A professional, dark-night-themed Ramadan landing page built with pure HTML, CSS, and JavaScript — no frameworks, no dependencies.

---

## 🌙 Live Preview

```
https://YOUR_USERNAME.github.io/ramadan-prompting-nights/
```

---

## 💬 Prompt Used

This webpage was generated using **Claude AI** with the following 4-segment structured prompt:

---

### 🎯 Goal
```
Make a webpage including Hero Section using HTML / CSS
```

---

### 🚧 Constraints
```
Build a Ramadan landing hero. Write `renderRamadanHero` that returns
a semantic HTML string with title and CTA text.
```

---

### ⚠️ Edge Cases
```
Make a beautiful dark night themed webpage with Hero Section described
above. Hero must look good and consider UI/UX that best fits in windows
and mobile screen too. Do not use extra colours but enhance writing and
hero should glow.
```

---

### 📤 Output Format
```
Output should be well aligned just like a professional webpage.
Must contain a button of 'Join Now'. CSS animations should be used
gracefully. It should be one page with HTML and CSS.
```

---

## ✅ What Was Generated

Based on the prompt above, the following was delivered as a single `index.html` file:

### Sections
- **Fixed Navbar** — Logo + navigation links + Join Now button
- **Hero Section** — Full-screen dark night sky with glowing title, subtitle, and CTA buttons
- **Features Strip** — 4-column section (30 Nights, AI Agents, Live Sessions, Free Access)
- **About Section** — Programme description with CTA
- **Schedule Grid** — 6 key nights of the programme
- **Final CTA Section** — Bottom conversion section with Join Now button
- **Footer** — Logo, copyright, Arabic text

### Design
- Dark navy background (`#050810`) with gold (`#d4af37`) as the only accent color
- **Amiri** serif font for headings — Arabic-origin, elegant
- **Cairo** sans-serif for body text — clean and readable
- Glowing hero title with gold text-shadow on key word

### Animations
- Animated star field via Canvas API (twinkling gold + white stars)
- Floating crescent moon ☪ with CSS keyframe loop
- Fade-up entrance animations on hero content (staggered delays)
- Shimmer sweep on the primary "Join Now" button
- Ripple click effect on all primary buttons
- Scroll indicator pulse at bottom of hero

### Responsive Behaviour
| Screen Size | Layout |
|---|---|
| Desktop `> 768px` | Full navbar, multi-column features |
| Tablet/Mobile `≤ 768px` | Nav links hidden, features stacked |
| Small Mobile `≤ 480px` | CTA buttons full-width and stacked |

---

## 🚀 How to Run

```bash
# Just open the file — no build step needed
open index.html
```

---

## 📤 Deploy on GitHub Pages

```bash
git init
git add .
git commit -m "Ramadan landing page"
git remote add origin https://github.com/YOUR_USERNAME/ramadan-prompting-nights.git
git branch -M main
git push -u origin main
```

Then: **Settings → Pages → Source: main → Save**

---

<div align="center">

**رمضان مبارك · Ramadan Mubarak**

Made with ☪ and Claude AI

</div>
