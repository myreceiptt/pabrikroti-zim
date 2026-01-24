# PABRIK ROTI [![version](https://img.shields.io/badge/version-2.4.47-blue)](https://github.com/myreceiptt/pabrikroti-master/releases/tag/v.2.4.47-zim) [![status](https://img.shields.io/badge/status-active-brightgreen)](https://github.com/myreceiptt/pabrikroti-master/blob/preview/SECURITY.md#-supported-versions) [![Build Status](https://github.com/myreceiptt/pabrikroti-master/actions/workflows/ci.yml/badge.svg)](https://github.com/myreceiptt/pabrikroti-master/actions/workflows/ci.yml) [![Deployed to Vercel](https://img.shields.io/badge/Vercel-deployed-success?logo=vercel)](https://preroti.endhonesa.com/)

> "This is not just a factory. This is a rehearsal of freedom—kneaded with code, fermented by its community, and baked through the heat of shared struggles."
>
> — Prof. NOTA

## Staging 2.4.47 by Zim Systems Limited

Link #1: [researach.zim-tech.com](https://researach.zim-tech.com/) [![status](https://img.shields.io/badge/deploy-live-brightgreen)](https://researach.zim-tech.com/)  
Link #2: [zim.endhonesa.com](https://zim.endhonesa.com/) [![status](https://img.shields.io/badge/deploy-live-brightgreen)](https://zim.endhonesa.com/)

---

## Quick Start

```bash
yarn install && yarn dev
```

> If you find this useful, consider starring ⭐ the repository! Please!
>
> — Prof. NOTA

---

## About This Repo (Zim Systems Limited)

This repo is a proof-of-concept web app built with **Zim Systems Limited** to demonstrate a simple and practical use of blockchain: **onchain-gated content**. We use the **Base** blockchain and the **thirdweb SDK** to provision **Smart Accounts** for users, then leverage onchain ownership and permissions to control access to research content.

### Purpose

- Prove that blockchain can be used as a secure access layer for digital documents and gated experiences.
- Establish a prototype that can later integrate with Zim’s user database, so only registered users can access specific research materials.

### What it does

- Serves Web3 research documents behind access rules.
- Uses Smart Accounts as the user identity primitive for gating, enabling a smoother onboarding path than raw EOAs.
- Keeps the UX production-safe and deployable while the underlying Web3 policy remains the source of truth for access.

### Technology

- Next.js (App Router) + React + TypeScript
- Tailwind CSS
- thirdweb SDK (Smart Accounts + EVM wallet/contract integrations)
- Base blockchain (EVM-compatible)
- Vercel deployment

### How we build (quality + workflow)

- We ship in small, reviewable steps and keep the repo evergreen with controlled dependency updates.
- We verify every update with audit/lint/build, and treat this repo as a stable artefact for global proof-of-work and collaboration.

## 📜 Licenses

This project is protected under a [**Custom Limited License**](./LICENSE) by [Prof. NOTA & Prof. NOTA Inc.](https://nota.endhonesa.com/). Usage is only allowed for cultural, educational, and women- or child-focused projects approved by Prof. NOTA.

License available in multiple languages:

- 🏛️ [English (UK)](./licenses/LICENSE_en-GB.md)
- 🇮🇩 [Bahasa Indonesia](./licenses/LICENSE_ID.md)
- 🇺🇿 [Oʻzbekcha](./licenses/LICENSE_uz-Latn.md)
- 🇭🇰 [Cantonese – Hong Kong](./licenses/LICENSE_yue-Hant-HK.md)
- 🇲🇾 [Bahasa Malaysia](./licenses/LICENSE_ms-MY.md)
- 🇦🇪 [العربية – الإمارات](./licenses/LICENSE_ar-AE.md)

> 📩 For permission or inquiries, contact: [nota@endhonesa.com](mailto:nota@endhonesa.com)

---

## 📜 Manifestos

If you already have obtained the license, please read and understand the manifesto from [Prof. NOTA & Prof. NOTA Inc.](https://nota.endhonesa.com/) before starting to use it. Each deployment must respect the ideological foundation of Prof. NOTA Inc.

Manifestos are available in:

- 🏛️ [English (UK)](./manifestos/manifesto_en-GB.md)
- 🇮🇩 [Bahasa Indonesia](./manifestos/manifesto_id.md)
- 🇺🇿 [Oʻzbekcha](./manifestos/manifesto_uz-Latn.md)
- 🇭🇰 [Cantonese – Hong Kong](./manifestos/manifesto_yue-Hant-HK.md)
- 🇲🇾 [Bahasa Malaysia](./manifestos/manifesto_ms-MY.md)
- 🇦🇪 [العربية – الإمارات](./manifestos/manifesto_ar-AE.md)

---

## 🛠️ Getting Started

### Install dependencies

```bash
yarn install
```

### Review dependency updates (interactive)

```bash
yarn up -i
```

### Upgrade dependencies

```bash
yarn up -R
```

### Cleaning and re-install dependencies

```bash
rm -rf node_modules .yarn/install-state.gz && yarn install
```

### Run development server

```bash
yarn dev
```

### Lint and check all the code quality

```bash
yarn lint
```

### Build for production

```bash
yarn build
```

### Preview the production

```bash
yarn start
```

---

## 📜 Resources

- [Prof. NOTA Inc.](https://nota.endhonesa.com/)
- [Prof. NOTA Console](https://prompt.endhonesa.com/)
- [Prof. NOTA Tutor](https://baca.endhonesa.com/)
- [Prof. NOTA Artefacts](https://docs.endhonesa.com/)

---

## 🤝 Contributing

Your contribution is not only welcome — it's part of the protocol.

If you believe in the mission of PABRIKROTI and want to help improve it, follow these simple steps:

1. Fork this repository
2. Create a new branch (`feature/your-feature-name`)
3. Commit your changes mindfully
4. Open a pull request to the `preview` branch

Before submitting your PR, make sure to run:

```bash
yarn lint
```

To keep our code clean and consistent.

If you have questions, feel free to open an issue or reach out via the Prof. NOTA community Discord.

> ✊ You’re not just contributing code — you’re shaping how the people eat, learn, and resist.
>
> — Prof. NOTA

---

### Join Prof. NOTA Discord

For feedback, questions, or cultural-technical collaboration, join Prof. NOTA discord at [https://discord.gg/5KrsT6MbFm](https://discord.gg/5KrsT6MbFm).

---

---

## Maintenance by Prof. NOTA Evergreen Standard

This repo is a **Live Artefact App**: the user-facing UX is intentionally frozen
("MINT CLOSED", no wallet prompts), while the codebase remains buildable and
production-safe on Vercel.

### Runtime

- Node: **24.x** (local + Vercel)
- Package manager: **Yarn 4.12.0** (lockfile: `yarn.lock`)
- `@types/node`: **24.10.7** (pinned to match Node 24; 25.x intentionally deferred)
- Deploy target: **Vercel**

### Build System

- Next.js **16.1.4** App Router (Turbopack)

### Monthly Safe Updates (recommended)

Monthly is **monitor + verify**, not modernization.

1. Check what’s outdated (report only):

   - `yarn outdated`

2. Security report (report only unless explicitly approved):

   - `yarn npm audit --severity moderate`

3. Verify build reproducibility:

   - `yarn lint`
   - `yarn build`

4. Verify production sanity:

   - Confirm "MINT CLOSED"
   - Confirm no wallet prompts / connect flows
   - Confirm no critical console errors

### Major Updates (quarterly / scheduled)

Major upgrades must be done **one at a time**, with a dedicated PR and full testing.
Artefact UX must remain unchanged.

Examples:

- Next.js / React major version upgrade
- Web3 stack upgrade (e.g., thirdweb major)
- Toolchain changes (Next.js or bundler shifts)
- Node major policy change

### Artefact UX Policy (Frozen)

- Minting must remain **disabled**
- Wallet connect must remain **disabled**
- Any functional change requires a versioned successor (new tag/release)

### Notes

- `@types/node` is pinned to **24.10.7** to match the Node 24 runtime (Vercel); 25.x intentionally deferred.
- Use `yarn outdated` for update review and `yarn npm audit --severity moderate` for security checks.
- CI runs on Node **24.x** with Corepack-enabled Yarn (**4.12.0**).
- Live parity check (zim.endhonesa.com): **All green** — MINT CLOSED, no wallet prompts, no critical console errors.

---
