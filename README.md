<div align="center">

# 🌠 Salut, moi c'est Noa 👋

### 🤖 Vibe codeur assumé — je construis des apps entières en pilotant l'IA ✨

<a href="https://github.com/Memel-SQT/Nebula-Hub"><img src="assets/nebula-hub.svg" width="64" alt="Nebula Hub" /></a>&nbsp;
<a href="https://github.com/Memel-SQT/Nebula-Finterest"><img src="assets/nebula-finterest.svg" width="64" alt="Nebula Finterest" /></a>&nbsp;
<a href="https://github.com/Memel-SQT/nebula-clock"><img src="assets/nebula-clock.svg" width="64" alt="Nebula Clock" /></a>&nbsp;
<a href="https://github.com/Memel-SQT/Nebula-News"><img src="assets/nebula-news.svg" width="64" alt="Nebula News" /></a>&nbsp;
<img src="assets/nebula-finance-enterprise.svg" width="64" alt="Nebula Finance Enterprise" />&nbsp;
<img src="assets/voute-hub.svg" width="64" alt="Voûte Hub" />&nbsp;
<img src="assets/steward.svg" width="64" alt="Steward" />

<br />

![Vibe coding](https://img.shields.io/badge/Vibe_coding-assumé-A855F7?style=for-the-badge)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)
![Local first](https://img.shields.io/badge/Local--first-sans_télémétrie-4C6EF5?style=for-the-badge)

</div>

---

## 🛰️ À propos

Je m'appelle **Noa** et je suis **vibe codeur**.

Concrètement : je ne code pas ligne par ligne. Je décris ce que je veux, je cadre le travail avec une IA (surtout **Claude Code**), je teste, je corrige, je recommence — et ça donne de vraies applications, installables, testées et mises à jour automatiquement.

Ce qui me guide :

- 🎨 **Une identité visuelle soignée** : thème sombre, halos de nébuleuse, animations douces, un design system partagé entre toutes mes apps.
- 🏡 **Des apps locales** : sans compte, sans télémétrie, les données restent sur l'ordinateur.
- 🏴‍☠️ **Du self-hosted** : j'aime comprendre et héberger moi-même les outils que j'utilise.

---

## 🎛️ Vibe codeur, mais pas à l'arrache

| Ce que je fais | Ce que fait l'IA |
|---|---|
| Je trouve l'idée, je définis le besoin et à qui ça s'adresse | Elle écrit l'essentiel du code |
| Je choisis la direction artistique (la « DA Nebula ») | Elle propose des architectures et des variantes |
| Je rédige des prompts détaillés, découpés en jalons | Elle génère le code, les tests, la doc et les scripts de build |
| Je valide chaque jalon : démo, tests verts, rapport | Elle corrige ses erreurs quand je lui remonte un bug |
| Je teste sur de vrais postes, je déploie, je documente les bugs | Elle m'explique ce qu'elle a fait quand je pose la question |

**Mes garde-fous**, présents dans mes dépôts :

- 🗺️ **Des fichiers de contexte pour l'IA** dans chaque projet (`CLAUDE.md`, `AGENTS.md`, instructions Copilot) pour qu'elle respecte les règles du projet.
- 📜 **Un journal de décisions (ADR)** : une décision n'est jamais réécrite, si elle change, une nouvelle décision la remplace.
- 🧗 **Des prompts structurés en jalons** (M0 → M9) : un jalon à la fois, rien n'est publié sans mon accord.
- 🧪 **Des tests automatiques et de la CI** : par exemple Nebula Clock affiche 164 tests unitaires (~99 % de couverture) et 32 tests de bout en bout.
- 🪲 **Des rapports de bugs versionnés** dans les dépôts, par plateforme.
- 🛡️ **Des installations vérifiées** : catalogue signé et contrôle SHA-512 des installateurs dans Nebula Hub.

> 🪞 **En toute transparence** : je ne me présente pas comme développeur, je suis vibe codeur. Je comprends ce que je livre et je sais l'expliquer, mais je m'appuie énormément sur l'IA et certaines bases me manquent encore. J'apprends en relisant et en questionnant ce qu'elle produit.

---

## 🚀 Mes projets

Les icônes ci-dessous sont les vraies icônes d'application de chaque projet. 🔒 = dépôt privé.

### 🌌 La famille Nebula

Une famille d'apps de bureau qui partagent la même identité visuelle (bleu nuit, dégradé bleu → violet, halo de nébuleuse) et peuvent se connecter entre elles, uniquement avec le consentement de l'utilisateur.

| | Projet | Ce que c'est | Stack |
|:-:|---|---|---|
| <img src="assets/nebula-hub.svg" width="56" alt="" /> | **[Nebula Hub](https://github.com/Memel-SQT/Nebula-Hub)** | Le lanceur et « store » de la famille : il installe, met à jour, répare et relie les apps Nebula. Catalogue signé, installations vérifiées, et « Nebula Link », une couche d'échange 100 % locale avec centre de consentements. | Electron · React · TypeScript · Vite · sql.js · Jest |
| <img src="assets/nebula-finterest.svg" width="56" alt="" /> | **[Nebula Finterest](https://github.com/Memel-SQT/Nebula-Finterest)** | Budget mensuel local et hors ligne : comptes locaux protégés par un code, calendrier des prélèvements et achats, prêts, budgets et cagnottes, simulateur d'intérêts composés, thèmes et arrière-plans animés. | Electron · React 18 · TypeScript · sql.js (SQLite) · Jest |
| <img src="assets/nebula-clock.svg" width="56" alt="" /> | **[Nebula Clock](https://github.com/Memel-SQT/nebula-clock)** | Gestionnaire de temps façon Pomodoro, sans compte : tâches, statistiques, sons d'ambiance, export PDF. Une seule base de code pour une PWA installable et une app de bureau (Windows, macOS, Linux). | React · TypeScript · Zustand · Dexie · Electron · pnpm monorepo · Playwright · semantic-release |
| <img src="assets/nebula-news.svg" width="56" alt="" /> | **[Nebula News](https://github.com/Memel-SQT/Nebula-News)** | Briefing quotidien sur trois thèmes (développement personnel, finance, tech) agrégé depuis des sources françaises et anglaises, dans une interface sombre « cosmique ». Résumés par l'API Claude en option. | Next.js 15 · TypeScript · Tailwind · Prisma · SQLite · Electron |
| <img src="assets/nebula-finance-enterprise.svg" width="56" alt="" /> | **Nebula Finance Enterprise** 🔒 *(bêta)* | L'édition « entreprise » de Finterest : la finance d'une entreprise dans un coffre chiffré. | Electron · React · TypeScript · Vite |
| <img src="assets/nebula-design-system.svg" width="56" alt="" /> | **Nebula Design System** 🔒 | Toute la DA de la famille dans un seul dépôt : tokens (CSS, TypeScript, preset Tailwind), logos, composants React et fiche de direction artistique, avec un `AGENTS.md` pour que l'IA la respecte. | React · Tailwind · TypeScript · Vitest · Framer Motion |

### 🧩 Le reste de l'atelier

| | Projet | Ce que c'est | Stack |
|:-:|---|---|---|
| <img src="assets/voute-hub.svg" width="56" alt="" /> | **Voûte Hub** 🔒 | Lanceur de bureau (Windows et macOS) pour mes applications web internes : bibliothèque d'apps réordonnable par glisser-déposer, récupération automatique des icônes, import et export de listes. | Tauri 2 · Rust · React 19 · TypeScript · Vite · Motion |
| <img src="assets/steward.svg" width="56" alt="" /> | **Steward** 🔒 | Bot Discord tout-en-un pour serveurs professionnels : modération, tickets avec transcription HTML, vérification des nouveaux membres, auto-modération, candidatures et suggestions. | Python 3.11 · discord.py 2 · SQLite (aiosqlite) · Docker |
| <img src="assets/portfolio.svg" width="56" alt="" /> | **Portfolio** 🔒 | Mon portfolio bilingue FR/EN avec back-office, thème clair/sombre et documentation de mon homelab. Réécrit de Flask vers Next.js. | Next.js 15 · React 19 · Prisma · SQLite · Tailwind 4 · next-intl · Docker · Nginx |

---

## 🧬 Ma stack

**🎨 Front-end**<br />
<img src="https://skillicons.dev/icons?i=react,ts,js,vite,tailwind,nextjs,html,css" alt="React, TypeScript, JavaScript, Vite, Tailwind, Next.js, HTML, CSS" />

**🖥️ Applications de bureau**<br />
<img src="https://skillicons.dev/icons?i=electron,tauri,rust" alt="Electron, Tauri, Rust" />

**🗄️ Back-end et données**<br />
<img src="https://skillicons.dev/icons?i=nodejs,py,prisma,sqlite,discord" alt="Node.js, Python, Prisma, SQLite, Discord" />

**🧪 Tests et qualité**<br />
<img src="https://skillicons.dev/icons?i=jest,vitest" alt="Jest, Vitest" />&nbsp;
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)
![Prettier](https://img.shields.io/badge/Prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=black)

**🚢 CI/CD et livraison**<br />
<img src="https://skillicons.dev/icons?i=git,github,githubactions,npm,pnpm" alt="Git, GitHub, GitHub Actions, npm, pnpm" />&nbsp;
![Gitea](https://img.shields.io/badge/Gitea-609926?style=for-the-badge&logo=gitea&logoColor=white)
![semantic-release](https://img.shields.io/badge/semantic--release-494949?style=for-the-badge&logo=semanticrelease&logoColor=white)

**🏗️ Infra et homelab**<br />
<img src="https://skillicons.dev/icons?i=docker,linux,nginx,windows,powershell" alt="Docker, Linux, Nginx, Windows, PowerShell" />&nbsp;
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=for-the-badge&logo=tailscale&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D4?style=for-the-badge&logo=windows&logoColor=white)

**🧠 IA et outils du quotidien**<br />
<img src="https://skillicons.dev/icons?i=obsidian" alt="Obsidian" />&nbsp;
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=for-the-badge&logo=githubcopilot&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-1F1F1F?style=for-the-badge&logo=modelcontextprotocol&logoColor=white)

<details>
<summary><b>🔬 Toutes les technos en détail (celles qu'on retrouve dans mes dépôts)</b></summary>

<br />

| Domaine | Technos |
|---|---|
| **Langages** | TypeScript (5 → 7), JavaScript, Rust, Python 3.11, SQL, PowerShell, HTML/CSS |
| **Interfaces** | React 18 et 19, Next.js 15 (App Router, mode standalone), Tailwind CSS 3 et 4, Motion / Framer Motion, dnd-kit, Recharts, polices Poppins, Inter et JetBrains Mono |
| **État et i18n** | Zustand, i18next / react-i18next, next-intl (français et anglais partout) |
| **Applications de bureau** | Electron 44, electron-builder, electron-updater, Tauri 2 (plugins dialog, process, updater, opener, single-instance), crates Rust : reqwest, scraper, image, serde, tokio, sha2 |
| **Web et PWA** | vite-plugin-pwa, Workbox, rss-parser |
| **Données** | sql.js (SQLite en WebAssembly), Dexie (IndexedDB), Prisma 5 et 6, SQLite / better-sqlite3, aiosqlite |
| **Audio et export** | Howler.js (sons d'ambiance et d'interface), jsPDF et jspdf-autotable |
| **Sécurité** | Argon2, JWT (jose), Zod, vérification SHA-512, catalogue signé |
| **Tests et qualité** | Jest 29, Vitest, Testing Library, Playwright (e2e), ESLint 9, Prettier, Husky, commitlint (Conventional Commits) |
| **Build et CI/CD** | Vite 7 et 8, tsup, pnpm workspaces, GitHub Actions (matrices de build, releases, Pages), Gitea Actions, semantic-release |
| **Bot Discord** | discord.py 2, python-dotenv, aiosqlite |
| **Déploiement** | Docker et Docker Compose, Nginx, Linux (Ubuntu, Debian), scripts shell et PowerShell |

</details>

---

## 🧫 Homelab

Mon terrain de jeu pour apprendre l'infra en vrai :

- **Proxmox VE** pour faire tourner des machines virtuelles et des conteneurs ;
- **Windows Server** avec **Active Directory**, couplé à **Tailscale** ;
- **Gitea** pour héberger mes dépôts ;
- un **CRM auto-hébergé** ([Twenty](https://twenty.com)) en Docker, derrière un reverse proxy HTTPS ;
- des déploiements en **Docker Compose** derrière **Nginx**.

## 🗂️ Organisation

Je gère mes projets dans **Obsidian** synchronisé avec **Git** (Kanban, tâches, Dataview, Excalidraw, modèles), et je connecte Claude à mes outils via **MCP**.

---

<div align="center">

*🌙 Fait avec du bleu nuit, beaucoup de prompts et un peu trop de café ☕🫠*

</div>
