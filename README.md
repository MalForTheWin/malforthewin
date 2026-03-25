# MalForTheWin (malforthewin.github.io)

Official website for Late Night Space Flight with MalForTheWin — live space science in a late night talk show format. Source for malforthewin.com. Static site hosted on GitHub Pages.

Live site: [https://malforthewin.com](https://malforthewin.com)

Current version: v1.1.0

---

## About This Site

Built collaboratively with Claude (Anthropic). Plain HTML, a single CSS file, a single JS file, and an assets folder. No frameworks, no build tools, no dependencies. Fast, mobile-friendly, and editable in any text editor. Hosted free on GitHub Pages.

## About the Channel

Late Night Space Flight with MalForTheWin is a live Twitch show about real astronomy, cosmology, and astrophysics — broadcast in a late night talk show format while exploring a scientifically accurate, 1:1 scale recreation of the Milky Way inside Elite: Dangerous. Real stellar catalogue data. 400 billion star systems. Destinations chosen for astronomical interest, not game progression. Chat is the studio audience — every member is a point of light. The dog fetches.

**Channel:** [twitch.tv/malforthewin](https://twitch.tv/malforthewin) — Twitch Partner

---

## File Structure

```
/
├── index.html          # Single-page site — hero, show, destinations, community, numbers
├── style.css           # Stylesheet — brand colors, fonts, layout, responsive
├── main.js             # JavaScript — starfield, scroll reveal, nav, count-up animations
├── CNAME               # Custom domain for GitHub Pages → malforthewin.com
├── README.md           # This file
└── assets/
    ├── avatar.png                  # M mark avatar — nav logo and footer
    ├── MalFTW_lnsfTitleCard.png    # Show title card — hero h1 image
    ├── screenshot_sagA.jpg         # In-game screenshot of Sagittarius A* (sample dest card)
    └── emotes/
        ├── emote_hype.png          # malftwHype
        ├── emote_fetch.png         # malftwFetch
        ├── emote_cozy.png          # malftwCozy
        ├── emote_hug.png           # malftwHug
        ├── emote_stcmd.png         # malftwSTCmd
        ├── emote_lurk.png          # malftwLurk
        ├── emote_o7.png            # malftwO7
        └── emote_gasm.png          # malftwGasm
```

---

## Design Tokens

| Token | Value | Used For |
|---|---|---|
| Void Black | `#080D1F` | Page background |
| Midnight Navy | `#0A0F28` | Surface / panel backgrounds |
| Deep Royal Blue | `#001870` | Depth / section backgrounds |
| Electric Blue | `#0060E0` | Primary active UI, borders, light source, stat numbers |
| Steel Blue | `#4A7FD4` | Secondary UI, subtle borders |
| Cockpit Orange | `#D47040` | Accent — CTAs and nav, one use per page |
| Pure White | `#FFFFFF` | Headings and body text on dark |
| Muted Blue | `#8BA8CC` | Secondary / muted text |
| Display font | Orbitron Bold 700 | Headlines, all-caps with tracking |
| UI font | Exo 2 SemiBold 600 | Subheadings, widget labels |
| Body font | Inter Regular 400 | Body copy, panel descriptions |

All fonts via Google Fonts. Violet colors (Deep Violet `#3D1A78`, Cosmic Violet `#7B4FCC`) are atmospheric only — used in background gradients, never as foreground text or button fills. They are referenced directly in CSS gradient values rather than as CSS variables.

---

## Sections

| Section | ID | Description |
|---|---|---|
| Hero | `#hero` | Show title card, three-card concept summary, primary CTA |
| The Show | `#show` | Format explainer, show elements panel, Sagittarius A* sample destination |
| Destinations | `#destinations` | Scale stats, 8-card science topic grid |
| Community | `#community` | Emote gallery, !fetch showcase, Discord CTA |
| The Numbers | `#numbers` | Audience metrics, engagement data, community reach |

---

## Deployment

Deploys automatically via GitHub Pages on every push to `main`. No build step required.

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
Late Night Space Flight with MalForTheWin. A Twitch show about real astronomy, live in the galaxy. The dog has opinions. The Constellation — welcome.
```

---

## Content & Branding Notes

### Show Concept

**Show title:** Late Night Space Flight with MalForTheWin

**Canonical tagline:** Real space science. Virtual galaxy. Copawlot included.

**Format:** Late night talk show structure applied to live space science — a host, a recurring format, and show energy. Not a gaming stream.

**Method:** Real astronomical objects and phenomena are chosen as destinations for their scientific interest. The host flies there live inside Elite: Dangerous — a space flight simulation whose back end is a 1:1 scale procedural recreation of the Milky Way built on real stellar catalogue data. The game is the vehicle. The science and the show format provide the structure.

**Positioning:** Science communication (astronomy, cosmology, astrophysics). Category: Cosmos meets The Late Show.

### The Copawlot

The cartoon dog is the emotional core of the brand — hero-level asset across all materials. 40 custom Twitch channel emotes. The !fetch command has the dog fetching items for chat members (sonic screwdriver, Thargoid artifact, NASA mission patch, tiramisu, etc.). Community name: The Constellation.

The emote character is based on Leo, a Border Collie/Golden Retriever mix who passed away in 2021 — a memorial. The current real-world copawlot is Ripley, a Belgian Malinois service dog in training, who shares a birthday with Mal (Nov 30). The emote set may eventually be updated to reflect Ripley.

Do not use "mascot" or "cartoon dog" in copy — always use "copawlot," "the copawlot," or "Ripley."

### Visual System

Corner bracket motif is the brand's signature geometric element. Electric Blue (`#0060E0`) is the light source — it outlines, borders, and activates. Cockpit Orange (`#D47040`) is the accent color: one use per page, primary CTAs only. Violet-indigo is atmospheric depth — background gradients only, never foreground.

### Brand Reference Files

- `MalForTheWin_Brand_Style_Guide_2026.docx` — single source of truth for all brand decisions
- `MalForTheWin_Brand_Audit_2026_Revised.docx` — legacy asset review and Phase 4 action items
- `MalForTheWin_Phase4_Dashboard.html` — Phase 4 production session prompt tracker
