# MalForTheWin (malforthewin.github.io)

Official website for Late Night Space Flight with MalForTheWin — live space science in a late night talk show format. Source for malforthewin.com. Static site hosted on GitHub Pages.

Live site: [https://malforthewin.com](https://malforthewin.com)

## Current version: v2.0
- Structure
    - Podcast banner moved to sit between The Show and Destinations sections
    - Discord card removed from Community section; community copy now runs full width
- Content
    - Leo introduced as the AI copawlot (virtual avatar, permanent co-presence, memorial to Mal's former service dog)
    - Ripley introduced as the IRL Crew (doggo-cam, !fetch command)
    - Emote gallery explicitly attributed to Leo
    - The Copawlot, The Subject, and The Format element copy updated
- Code
    - All CTA buttons unified: orange outline at rest, solid orange on hover
    - Removed orphaned CSS: `.comm-cols`, `.disc-panel`, `.disc-label`, `.disc-copy`
    - Merged duplicate `.stat-panel-title` / `.stat-section-title` rules into a single selector

---

## About This Site

Plain HTML, a single CSS file, a single JS file, and an assets folder. No frameworks, no build tools, no dependencies. Fast, mobile-friendly, and editable in any text editor. Built collaboratively with Claude (Anthropic); hosted free on GitHub Pages.

## About the Channel

Late Night Space Flight with MalForTheWin is a live Twitch show about real astronomy, cosmology, and astrophysics — broadcast in a late night talk show format while exploring a scientifically accurate, 1:1 scale recreation of the Milky Way inside Elite: Dangerous. Real stellar catalogue data. 400 billion star systems. Destinations chosen for astronomical interest, not game progression. Chat is the studio audience — every member is a point of light. Lt. Leo holds the copawlot seat. Ripley fetches.

**Channel:** [twitch.tv/malforthewin](https://twitch.tv/malforthewin) — Twitch Partner

---

## File Structure

```
/
├── index.html          # Single-page site — hero, show, podcast, destinations, community, stats
├── style.css           # Stylesheet — brand colors, fonts, layout, responsive
├── main.js             # JavaScript — starfield, scroll reveal, nav, count-up animations
├── CNAME               # Custom domain for GitHub Pages → malforthewin.com
├── README.md           # This file
└── assets/
    ├── MalFTW_avatarLNSF.png           # LNSF circle logo — nav and footer
    ├── MalFTW_lnsfTitleCard.png        # Show title card — hero h1 image
    ├── MalFTW_portraitMalFTW.jpg       # Host portrait — The Show section
    ├── MalFTW_screenshot_sagA.jpg      # In-game screenshot of Sagittarius A*
    └── emotes/
        ├── MalFTW_emoteHype.png        # malftwHype
        ├── MalFTW_emoteFetch.png       # malftwFetch
        ├── MalFTW_emoteCozy.png        # malftwCozy
        ├── MalFTW_emoteHug.png         # malftwHug
        ├── MalFTW_emoteSTCmd.png       # malftwSTCmd
        ├── MalFTW_emoteLurk.png        # malftwLurk
        ├── MalFTW_emoteO7.png          # malftwO7
        └── MalFTW_emoteGasm.png        # malftwGasm
```

---

## Design Tokens

| Token | Value | Used For |
|---|---|---|
| Void Black | `#080D1F` | Page background |
| Midnight Navy | `#0A0F28` | Surface / panel backgrounds |
| Electric Blue | `#0060E0` | Primary active UI, borders, light source, stat numbers |
| Steel Blue | `#4A7FD4` | Secondary UI, subtle borders |
| Cockpit Orange | `#D47040` | Accent — all CTA buttons and nav |
| Pure White | `#FFFFFF` | Headings and body text on dark |
| Muted Blue | `#8BA8CC` | Secondary / muted text |
| Display font | Roboto Bold 700/900 | Headlines, section titles, stat numbers, all-caps with tracking |
| UI font | Exo 2 SemiBold 600 | Subheadings, labels, eyebrows, widget labels |
| Body font | Inter Regular 400 | Base body font — paragraphs, descriptions |

All fonts via Google Fonts (`Roboto:wght@700;900`, `Exo+2:wght@400;600`, `Inter:wght@400;500`). Violet colors (Deep Violet `#3D1A78`, Cosmic Violet `#7B4FCC`) are atmospheric only — used in background gradients, never as foreground text or button fills. They are referenced directly in CSS gradient values rather than as CSS variables.

CTA buttons are Cockpit Orange outline at rest; solid Cockpit Orange fill on hover. This applies to all `.btn-primary` instances site-wide, including the nav Watch Live button.

---

## Sections

| Section | ID | Description |
|---|---|---|
| Hero | `#hero` | Show title card, three-card concept summary, primary CTA |
| The Show | `#show` | Format explainer, show elements panel (host, copawlot, IRL crew, audience, subject, format), host portrait, vehicle callout |
| Podcast Banner | *(no ID)* | Podcast availability — Spotify, Apple Podcasts, Amazon Music |
| Destinations | `#destinations` | Scale stats, 8-card science topic grid, Sagittarius A* sample destination card |
| Community | `#community` | Leo emote gallery, !fetch showcase, community copy |
| The Stats | `#stats` | Audience metrics, engagement data, community reach |

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

### The Copawlot & The IRL Crew

**Lt. Leo — the copawlot.** Leo is an on-screen animated virtual avatar and the show's permanent co-presence. He is a memorial to Mal's former service dog Leo (Border Collie/Golden Retriever mix, 2007–2021). All 40 custom Twitch channel emotes are based on Leo — this is intentional, not incidental. If Mal is flying, Leo is in the seat.

**Ripley — the IRL crew.** Ripley is Mal's current Belgian Malinois service dog in training. She appears on the doggo-cam when she feels like it. She runs the !fetch command. She once retrieved a Thargoid artifact and has not explained where she found it.

Do not use "mascot" or "cartoon dog" in copy — always use "the copawlot," "Lt. Leo," "Leo," or "Ripley" as appropriate. Leo and Ripley have distinct roles and should never be conflated.

### Visual System

Corner bracket motif is the brand's signature geometric element. Electric Blue (`#0060E0`) is the light source — it outlines, borders, and activates. Cockpit Orange (`#D47040`) is the accent color for all CTA buttons — outline at rest, solid fill on hover. Violet-indigo is atmospheric depth — background gradients only, never foreground.

### Brand Reference Files

- `MalForTheWin_Brand_Style_Guide_2026.docx` — single source of truth for all brand decisions
- `MalForTheWin_Brand_Audit_2026_Revised.docx` — legacy asset review and Phase 4 action items
- `MalForTheWin_Phase4_Dashboard.html` — Phase 4 production session prompt tracker
