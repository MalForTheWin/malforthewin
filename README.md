# MalForTheWin (malforthewin.github.io)

Official website for Late Night Space Flight with MalForTheWin — live space science in a late night talk show format. Source for malforthewin.com. Static site hosted on GitHub Pages.

Live site: [https://malforthewin.com](https://malforthewin.com)

Current version: v1.0.0

---

## About This Site

Built collaboratively with Claude (Anthropic). Plain HTML files, a shared CSS file, a shared JS file, and an assets folder. No frameworks, no build tools, no code dependencies. Fast, mobile-friendly, and editable in any text editor. Hosted free on GitHub Pages.

## About the Channel

Late Night Space Flight with MalForTheWin is a live Twitch show about real astronomy, cosmology, and astrophysics — broadcast in a late night talk show format while exploring a scientifically accurate, 1:1 scale recreation of the Milky Way inside Elite: Dangerous. Real stellar catalogue data. 400 billion star systems. Destinations chosen for astronomical interest, not game progression. Chat is the studio audience. The dog fetches.

**Channel:** [twitch.tv/malforthewin](https://twitch.tv/malforthewin) — Twitch Partner

---

## File Structure

```
/
├── index.html          # Homepage — hero, show concept, mascot, community CTA
├── style.css           # Shared stylesheet — colors, fonts, layout
├── main.js             # Shared JavaScript — nav, scroll reveal, interactions
├── CNAME               # Custom domain mapping for GitHub Pages
├── README.md           # This file
└── assets/
    ├── logo_m.svg                  # M mark — icon only, transparent background
    ├── logo_wordmark.svg           # M mark + "MalForTheWin" lockup
    ├── mascot_hero.png             # Dog mascot — hero placement, large format
    ├── banner-x.svg                # X/Twitter header banner — 1500×500px
    ├── banner-youtube.svg          # YouTube channel banner — 2560×1440px
    └── favicon.ico                 # Site favicon
```

---

## Design Tokens

| Token | Value | Used For |
|---|---|---|
| Void Black | `#080D1F` | Page background |
| Midnight Navy | `#0A0F28` | Surface / panel backgrounds |
| Deep Royal Blue | `#001870` | Depth / section backgrounds |
| Electric Blue | `#0060E0` | Primary active UI, borders, light source |
| Steel Blue | `#4A7FD4` | Secondary UI, subtle borders |
| Deep Violet | `#3D1A78` | Atmospheric depth — gradients only |
| Cosmic Violet | `#7B4FCC` | Atmospheric depth — glows only |
| Cockpit Orange | `#FF6B35` | Accent only — one use per page, primary CTA |
| Pure White | `#FFFFFF` | Headings and body text on dark |
| Muted Blue | `#8BA8CC` | Secondary / muted text |
| Display font | Orbitron Bold 700 | Headlines, all-caps with tracking |
| UI font | Exo 2 SemiBold 600 | Subheadings, widget labels |
| Body font | Inter Regular 400 | Body copy, panel descriptions |

All fonts via Google Fonts. Violet colors are atmospheric only — never used as foreground text or button fills.

---

## Deployment

This site deploys automatically via GitHub Pages on every push to `main`. No build step required.

---

## Social Media Links

| Platform | URL |
|---|---|
| Twitch | https://twitch.tv/malforthewin |
| X / Twitter | https://x.com/malforthewin |
| YouTube | https://youtube.com/@malforthewin |
| Discord | https://discord.gg/malforthewin |

---

## Social Media Bios

**Twitter / X**
```
Late Night Space Flight with MalForTheWin. A Twitch show about real astronomy, live in the galaxy. The dog has opinions. Dogs of Lore welcome.
```

---

## Content & Branding Notes

### Show Concept

**Show title:** Late Night Space Flight with MalForTheWin

**Format:** Late night talk show structure applied to live space science — a host, a recurring format, and show energy. Not a gaming stream.

**Method:** Real astronomical objects and phenomena are chosen as destinations for their scientific interest. The host flies there live inside Elite: Dangerous — a space flight simulation whose back end is a 1:1 scale procedural recreation of the Milky Way built on real stellar catalogue data. The game is the vehicle. The science and the show format provide the structure.

**Positioning:** Science communication (astronomy, cosmology, astrophysics). Category: Cosmos meets The Late Show.

### The Mascot

The cartoon dog is the emotional core of the brand — hero-level asset across all materials. 40 custom Twitch channel emotes. The !fetch command has the dog fetching items for chat members (sonic screwdriver, Thargoid artifact, NASA mission patch, tiramisu, etc.). Community name: Dogs of Lore.

The character is based on Leo, a Belgian Malinois and former service dog who passed away in 2021. A memorial. May eventually be updated to reflect Ripley — current Belgian Malinois, service dog in training.

### Visual System

Corner bracket motif is the brand's signature geometric element — appears consistently across assets as a structural frame. Electric Blue (#0060E0) functions as the light source: it outlines, borders, and activates. Violet-indigo is the shadow and depth — lives in gradients and glows, never foreground. Starfield Gold is punctuation: one use per asset, maximum.

### Brand Reference Files

- `MalForTheWin_Brand_Style_Guide_2026.docx` — single source of truth for all brand decisions
- `MalForTheWin_Brand_Audit_2026_Revised.docx` — legacy asset review and Phase 4 action items
- `MalForTheWin_Phase4_Dashboard.html` — Phase 4 production session prompt tracker
