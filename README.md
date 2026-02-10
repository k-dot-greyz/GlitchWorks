# GLITCHWORKS.ONLINE

**Systems Architecture Holding Company**  
**Asset Light • Profit First • Global Mobility**

---

## 🎯 Project Overview

GlitchWorks terminal landing page - a production-ready, accessibility-first web presence that doubles as a functional terminal interface.

### Key Features

- **Terminal Interface**: Boot sequence, command execution, easter eggs
- **WCAG 2.2 AA/AAA Compliant**: 95% accessibility score
- **Neurodivergent-Friendly**: ASPECTSS™ framework compliance
- **Performance Optimized**: <100KB, 30fps canvas throttling, zero bundle
- **Mobile Responsive**: Touch commands, keyboard handling, safe areas
- **Error Resilient**: Error boundary with graceful degradation

---

## 🚀 Deployment

### Static Hosting (Recommended)

Deploy `index.html` to:
- **Vercel**: Drop file in project root
- **Netlify**: Drop in deploy folder
- **Cloudflare Pages**: Push to repo, auto-deploy
- **GitHub Pages**: Enable in repo settings

### Local Development

```bash
# Serve with any static server
python3 -m http.server 8000
# or
npx serve .
# or
open index.html
```

No build step required - fully self-contained HTML.

---

## 🎮 Commands

| Command | Description |
|---------|-------------|
| `help` | List all available commands |
| `status` | Display system telemetry |
| `whoami` | Show current user role |
| `manifesto` | Display core directive |
| `services` | List service offerings |
| `stack` | Show tech stack |
| `contact` | Get contact info |
| `matrix` | Matrix rain effect |
| `clear` | Purge terminal history |
| `sudo` | Easter egg |

### Keyboard Shortcuts

- **Tab**: Autocomplete/cycle commands
- **↑/↓**: Command history navigation
- **Escape**: Release focus trap
- **Skip >>**: Skip boot sequence

### Easter Eggs

Discover hidden features through exploration. 😈

---

## 📊 Technical Specs

### Stack

- React 18 (UMD, no build required)
- Tailwind CSS (CDN)
- Babel Standalone (in-browser JSX)
- Pure HTML/CSS/JS (single file)

### Accessibility

- **WCAG 2.2**: AA/AAA compliant (95% score)
- **ARIA**: Live regions, labels, roles
- **Keyboard**: Full navigation, focus management
- **Screen Readers**: Semantic HTML, skip links
- **Motion**: `prefers-reduced-motion` support
- **Contrast**: AAA ratios verified

### Performance

- **Size**: <100KB total (including CDN scripts)
- **FPS**: 30fps cap on canvas animations
- **Memory**: Cleanup on unmount, throttled redraws
- **Mobile**: Lazy scroll, keyboard occlusion handling

### Security

- **SRI Hashes**: CDN script integrity verification
- **CSP Ready**: No inline event handlers
- **XSS Safe**: React escaping, no `dangerouslySetInnerHTML`
- **Error Boundary**: Graceful failure handling

---

## 📁 Project Structure

```
GlitchWorks/
├── index.html              # Landing page (self-contained)
├── README.md               # This file
├── docs/
│   └── AUDIT_2026-02-10.md # Accessibility audit report
└── .github/
    └── workflows/
        └── deploy.yml      # (Optional) CI/CD config
```

---

## 🔍 Audit Results

**Date**: February 10, 2026  
**Score**: A- (87/100) → A (95/100) after fixes

See [`docs/AUDIT_2026-02-10.md`](./docs/AUDIT_2026-02-10.md) for full report.

### Highlights

✅ All critical/high priority issues resolved  
✅ WCAG 2.2 AA/AAA compliance (21/22 criteria)  
✅ Neurodivergent UX score: B+ (88/100)  
✅ Error boundary, focus trap, SRI hashes  
✅ Matrix canvas throttled to 30fps  
✅ Mobile keyboard handling fixed  

---

## 🛠️ Future Enhancements

### v2.5.0 Roadmap

- [ ] Command aliases (`ls` → `help`, `cat` → `manifesto`)
- [ ] Theme switcher (beyond glitch mode)
- [ ] Sound effects toggle
- [ ] More interactive commands (`ping`, `traceroute`, `dig`)
- [ ] Integration with actual backend API
- [ ] Analytics (privacy-respecting)

### Backlog

- [ ] PWA support (offline mode)
- [ ] i18n (LV/EN/PL)
- [ ] Custom cursor
- [ ] ASCII art loader
- [ ] WebGL shader effects

---

## 📞 Contact

**Email**: connect@glitchworks.online  
**Location**: Riga, Latvia → Worldwide  
**Status**: Active & Accepting Contracts

---

## 📜 License

**Copyright © 2026 GlitchWorks Mazkapitāla SIA**  
All rights reserved.

This code is proprietary and confidential. Unauthorized copying, distribution, or use is strictly prohibited.

---

## 🎨 Credits

**Design & Development**: greyZ @ GlitchWorks  
**Audit Framework**: ASPECTSS™ + WCAG 2.2  
**Inspiration**: Lemongrab, Patrick Bateman, Lisan al Gaib  
**Anthem**: The Funk Hunters - Empire

---

**Built with spite. Powered by systems mastery. Deployed with calm.**

🔥 `lmao` 🔥