# Cyberpunk-Inspired Transition Module

This is a standalone interactive transition page from my personal portfolio site [willemtouw.com](https://willemtouw.com). It’s a taste of my creative approach to immersive web design, UI/UX storytelling, and visual theming.

This module is styled as a fictional secure login system for "ARASAKA OS :: SHINOBI v6.2"—featuring a boot sequence, authentication flow, terminal commands, and a glyph puzzle that unlocks access to the rest of the portfolio.

> I’m not open-sourcing my entire site (yet), but I wanted to share this piece to highlight my aesthetic, attention to detail, and interaction logic, I am still improving it and building as I go!

## Some Features

- Fully custom HTML/CSS/JS with no frameworks
- Cyberpunk OS-style boot sequence + login interface
- Interactive secure terminal with real command parsing
- Glyph-based puzzle challenge with puzzle logic + response validation
- Sound design using embedded audio cues -- (working on it)
- Styled with custom fonts (VT323, Patrick Hand) and layered visual effects
- Desktop icon simulation, popups, taskbar, fake notifications, and more

## Try It Live

Want to try out the experience?
👉 [willemtouw.com](https://willemtouw.com) the small terminal button top right :)

This repo only contains the standalone page (`portfoliotransition.html`) and relevant assets.
## 🛠Technical Overview

This module is built entirely with vanilla HTML, CSS, and JavaScript—no external libraries or frameworks. The core goal is to create an immersive, retro-futuristic UX inspired by games like *Cyberpunk 2077* and *Deus Ex*, simulating a secure OS interface with a hint of narrative depth. (still a work in progress!)

**Key Systems Implemented:**

- **Boot Sequence Simulator:** Uses timed line-by-line rendering with sound effects to mimic a BIOS-style startup.
- **Login System:** Verifies hardcoded credentials and triggers a fake secure environment experience.
- **Desktop Environment:** Features styled desktop icons with click functionality, faux file viewer popups, and a persistent taskbar.
- **Terminal Interface:** Custom shell-like UI that accepts commands (`help`, `ls`, `cat`, etc.), including file parsing and dynamic outputs.
- **Glyph Puzzle System:** Implements a randomized visual authentication puzzle mapped to a key string (`K7GX3ZR8A`) with error handling and feedback.
- **Passphrase Override:** Unlocks final content after solving the puzzle and answering a narrative riddle.
- **Sound Design:** Audio feedback is embedded for every major interaction using preloaded sound assets. (In process)
- -**More In the works**

The entire interaction flow is state-managed within the DOM—no backend, no APIs. Everything is self-contained and crafted for aesthetic storytelling.


## Notes

This is not the full source of my portfolio. It’s a creative sample from a larger, private project. Please don’t reuse or distribute without permission. Thank u!

---

— Willem (Sebastian)
