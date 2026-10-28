# GOODFELLAS

**GOODFELLAS — Root the Impossible. Rise Unstoppable.**

GOODFELLAS is a competitive CTF (Capture the Flag) team of cybersecurity enthusiasts. We play CTFs to sharpen real security skills, break hard problems, and document what we learn.

This repository contains the team's website: a single-page, dark, terminal-inspired site.

## The Team

| Gamertag | Name | GitHub | LinkedIn | TryHackMe |
|---|---|---|---|---|
| RageBear62 | Aditya Tripathi | [Profile](https://github.com/tripathiaditya-codes) | [Profile](https://www.linkedin.com/in/aditya-kumar-tripathi28/) | [Profile](https://tryhackme.com/p/Aditya.Tripathi) |
| Noddy | Parth Nagam | [Profile](https://github.com/NodYwhoo/) | [Profile](https://www.linkedin.com/in/parthnagam/) | [Profile](https://tryhackme.com/p/NodyWhoo) |
| Sierraaa | Chirag Dubey | [Profile](https://github.com/Chirag24-droid) | [Profile](https://www.linkedin.com/in/chirag-dubey-5b4327351/) | [Profile](https://tryhackme.com/p/Sierraaaa.17) |

## Focus Areas

- **Web Exploitation:** injection, auth flaws, broken access control, logic bugs
- **Cryptography:** classical ciphers, weak primitives, implementation mistakes
- **Reverse Engineering:** reading binaries and bytecode to recover hidden logic
- **Digital Forensics:** disk, memory, network captures, file carving
- **Pwn:** memory corruption and binary exploitation
- **OSINT:** turning public information into verifiable answers

## The Website

**Sections:** Hero, About, Team, Expertise, Interactive Terminal, CTF Records, Contact.

**Highlights**
- Dark theme (`#08090C`) with neon-green accents (`#00FF9C`) and monospace typography
- Typewriter slogan and a simulated terminal
- Responsive layout, keyboard-accessible navigation and social links (with tooltips and aria-labels)
- Social links open in a new tab with `rel="noopener noreferrer"`
- SEO metadata, Open Graph tags, custom GF favicon
- Respects `prefers-reduced-motion`

**Terminal commands** (all simulated, no real command execution or network access):

`help` · `about` · `team` · `members` · `expertise` · `whoami` · `date` · `clear`

**Stack:** React 18, TypeScript, Tailwind CSS. Everything is in one `index.html` and compiled in the browser via CDN (React, Babel Standalone, Tailwind Play CDN), so there is no build step.

## Editing Content

Open the page source and edit the constants at the top of the script:

- `MEMBERS`: gamertags, names, and social links
- `EXPERTISE`: focus areas and descriptions
- `SLOGAN`: keep it exactly as written

Changes flow automatically to the team cards, footer, and terminal output.

## CTF Records

No competitions are logged yet. This section is a placeholder for future events, scores, and write-ups. Only real results should be added here.

## Run Locally

No install needed. Open `index.html` in a browser (an internet connection is required to load the CDN scripts), or serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Any static host works: GitHub Pages, Netlify, Vercel, or Cloudflare Pages. Publish `index.html` as the site root, with no build command.

## Roadmap

- Migrate to a Vite + React + TypeScript project with a pre-built Tailwind pipeline for faster loads
- Add CTF records and write-ups as results come in

---

*GOODFELLAS — Root the Impossible. Rise Unstoppable.*
