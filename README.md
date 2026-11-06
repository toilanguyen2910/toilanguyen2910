<p align="center">
  <img src="./assets/flicker-name.svg" alt="MY NAME IS NGUYEN" />
</p>

<p align="center">
  <sub><b>Khôi Nguyên Vũ Hoàng</b> · Nguyen JN</sub><br />
  <sub>Vibe coder · Ship fast with AI agents · Then make it hold up</sub>
</p>

<p align="center">
  <a href="#-vaa-share"><img src="https://img.shields.io/badge/Now_building-VAA_Share-666666?style=flat-square&labelColor=1a1a1a" alt="Now building" /></a>
  <a href="https://github.com/toilanguyen2910?tab=followers"><img src="https://img.shields.io/github/followers/toilanguyen2910?style=flat-square&labelColor=1a1a1a&color=666666&logo=github&logoColor=white" alt="Followers" /></a>
  <img src="https://komarev.com/ghpvc/?username=toilanguyen2910&style=flat-square&label=PROFILE+VIEWS&color=666666" alt="Profile views" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=666666&height=1&section=footer" />
</p>

## 👋 About

I'm a **vibe coder** based in **Ho Chi Minh City, Vietnam**. I build by describing what I want,
letting an AI agent write the first pass, then tightening it until it's something I'd actually
put my name on.

That's not code golf and it's not autopilot. The agent types fast; **I own the design system,
the data model, and the decisions about what ships.** Most of my time goes into the parts
generation is worst at: picking the right boundary, killing a feature that doesn't earn its
place, and proving the thing works.

- 🚀 **Build fast, verify faster** — working demo first, then tests, then polish
- 🎨 **Design tokens before components** — AI is great at filling in a system, bad at inventing one
- 🧱 **Small, boring stacks** — fewer moving parts means fewer places for a hallucination to hide
- 🧭 **Spec-driven** — a written brief beats a clever prompt

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=666666&height=1&section=footer" />
</p>

## 🧭 How I vibe code

| Rule | Why |
|---|---|
| **Write the spec first** | A short brief with schema, routes, and states gets a usable first pass; a vague prompt gets a rewrite. |
| **One concern per session** | Mixing UI, auth, and DB in one prompt produces code that compiles but doesn't fit. |
| **Read every diff** | Generated code is a draft, not a commit. I merge what I understand. |
| **Lock the design system** | Colors, spacing, and motion live in tokens — the agent composes, it doesn't improvise. |
| **Verify before declaring done** | A response saying "done" is a hypothesis. A passing test is evidence. |
| **Ship the boring solution** | The clever one costs three sessions to debug later. |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=666666&height=1&section=footer" />
</p>

## ✈️ VAA Share

> **A student-to-student exchange platform for the Vietnam Aviation Academy (VAA).**
> Give away or swap textbooks, laptops, and dorm essentials — free, local, no money involved.

Built for a real campus need: students with spare aviation textbooks and no clean way to hand
them to the people who need them. No marketplace fees, no shipping, no checkout — just a listing,
a Zalo message, and a handoff at the library.

**What it does**

- 📚 **Listings** for textbooks, electronics, dorm gear — free (`0đ`) or swap
- 🛡️ **Admin moderation** — every post starts `PENDING`, reviewed before it goes public
- 📲 **One-click Zalo contact** — no in-app chat, no middleman
- 🚩 **Reporting & account lockout** — students report violations, admins act
- 🎛️ **Admin console** — dashboard, user management, listing queue, categories, reports
- 🗂️ **Docs in the repo** — ERD (Mermaid), full REST API reference, a 5-minute defense script
- ⚡ **One-click launcher** — `RUN_VAA_SHARE.bat` boots MySQL check, backend, frontend, and the browser

**Stack**

| Layer | Choice |
|---|---|
| Frontend | React 19 + Vite + React Router |
| Styling | Hand-rolled CSS design system — *Dark Cockpit Aero-Tech HUD*, WCAG 2.2 AA |
| Backend | Node.js 22 + Express (MVC: controllers, routes, middleware) |
| Database | MySQL 8 / MariaDB (`utf8mb4`), 8 tables via `database/vaa_share.sql` |
| Auth | JWT + Bcrypt (10 rounds), role middleware, rate limiting |
| Uploads | Multer — JPG/PNG/WEBP, 5 MB cap |
| Deploy | Vercel (SPA fallback + reverse proxy + CSP headers) |
| Integrity | Signed commits (SSH/GPG) on `main` |

<sub>🔒 Repository is private — happy to walk through the code or grant access on request.</sub>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=666666&height=1&section=footer" />
</p>

## 🧰 Stack

**Languages**

![JavaScript](https://img.shields.io/badge/-JavaScript-1a1a1a?style=flat-square&logo=javascript&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-1a1a1a?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/-Python-1a1a1a?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-1a1a1a?style=flat-square&logo=mysql&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-1a1a1a?style=flat-square&logo=gnubash&logoColor=white)

**Frontend & backend**

![React](https://img.shields.io/badge/-React_19-1a1a1a?style=flat-square&logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/-Vite-1a1a1a?style=flat-square&logo=vite&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js_22-1a1a1a?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/-Express-1a1a1a?style=flat-square&logo=express&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL_8-1a1a1a?style=flat-square&logo=mysql&logoColor=white)
![JWT](https://img.shields.io/badge/-JWT-1a1a1a?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Ship & verify**

![Vercel](https://img.shields.io/badge/-Vercel-1a1a1a?style=flat-square&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/-Signed_Commits-1a1a1a?style=flat-square&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/-API_Tests-1a1a1a?style=flat-square&logo=postman&logoColor=white)

**AI agents I build with**

![Claude Code](https://img.shields.io/badge/-Claude_Code-1a1a1a?style=flat-square&logo=anthropic&logoColor=white)
![Codex CLI](https://img.shields.io/badge/-Codex_CLI-1a1a1a?style=flat-square&logo=openai&logoColor=white)
![Gemini CLI](https://img.shields.io/badge/-Gemini_CLI-1a1a1a?style=flat-square&logo=googlegemini&logoColor=white)
![Cursor](https://img.shields.io/badge/-Cursor-1a1a1a?style=flat-square&logo=cursor&logoColor=white)

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=666666&height=1&section=footer" />
</p>

## 📊 GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=toilanguyen2910&show_icons=true&include_all_commits=true&hide_border=true&bg_color=00000000&title_color=ffffff&icon_color=999999&text_color=999999" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=toilanguyen2910&layout=compact&langs_count=8&hide_border=true&bg_color=00000000&title_color=ffffff&text_color=999999" alt="Top languages" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=666666&height=1&section=footer" />
</p>

## 📬 Connect

<p align="center">
  <a href="https://www.facebook.com/sourrrkngyn7/"><img src="https://img.shields.io/badge/-Facebook-1a1a1a?style=flat-square&logo=facebook&logoColor=white" alt="Facebook" /></a>
  <a href="https://www.instagram.com/sourrrr_kngyn/"><img src="https://img.shields.io/badge/-Instagram-1a1a1a?style=flat-square&logo=instagram&logoColor=white" alt="Instagram" /></a>
  <a href="https://github.com/toilanguyen2910?tab=repositories"><img src="https://img.shields.io/badge/-Repositories-1a1a1a?style=flat-square&logo=github&logoColor=white" alt="Repositories" /></a>
</p>

<p align="center">
  <sub>Always up for a conversation about vibe coding workflows, prompt structure, or where agents still fall short.</sub>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=666666&height=1&section=footer" />
</p>
