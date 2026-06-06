<h1 align="center">Hi, I'm Blake 👋</h1>

<p align="center">
  <strong>Full-stack engineer in Melbourne, building SaaS on the edge.</strong><br />
  Astro · React · TypeScript · Cloudflare Workers · Supabase · Stripe
</p>

<p align="center">
  <a href="https://streamvault.gg"><img alt="streamvault.gg" src="https://img.shields.io/badge/Live%20product-streamvault.gg-22c55e?style=flat-square" /></a>
  <a href="https://github.com/FusionBrah/StreamVault-website"><img alt="StreamVault repo" src="https://img.shields.io/badge/Code-StreamVault--website-181717?style=flat-square&logo=github&logoColor=white" /></a>
  <a href="https://github.com/FusionBrah/hyperliquid-autotrader"><img alt="Hyperliquid Autotrader repo" src="https://img.shields.io/badge/Code-hyperliquid--autotrader-181717?style=flat-square&logo=github&logoColor=white" /></a>
</p>

---

### Currently building

**[StreamVault](https://streamvault.gg)** — a production Twitch VOD archiving SaaS. Automatic stream capture, chat archive, role-based team access, and a self-pruning storage quota. Server-rendered Astro on Cloudflare Workers with Stripe-driven subscriptions, Supabase auth, and Backblaze B2 storage.

→ [Repo & technical write-up](https://github.com/FusionBrah/StreamVault-website)

**[Hyperliquid Autotrader](https://github.com/FusionBrah/hyperliquid-autotrader)** — a fully mechanical trading bot for Hyperliquid perpetual futures. WebSocket-driven entries and exits (~2s reaction), rule-based signals (RSI, Bollinger Bands, regime detection), ATR trailing stops with profit-locking giveback floors — no AI in the trading loop. Backtest numbers are pinned by a golden-master regression test in CI, so any change that shifts results fails the build.

→ [Repo & backtest results](https://github.com/FusionBrah/hyperliquid-autotrader)

### Stack I reach for

<p>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img alt="React" src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img alt="Astro" src="https://img.shields.io/badge/Astro-FF5D01?style=flat-square&logo=astro&logoColor=white" />
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
  <img alt="Cloudflare Workers" src="https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white" />
  <img alt="Supabase" src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img alt="Stripe" src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white" />
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img alt="Go" src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
</p>

### How I work

- **Ship to production, then iterate.** StreamVault auto-deploys on every push to `main` via Cloudflare Workers; CI gates type-checking, build, npm audit, and secret scanning.
- **Edge-first SSR over SPA wherever it fits.** Astro for marketing + dashboard, React islands only where interactivity earns it.
- **Database-layer access control.** Postgres RLS on every table in StreamVault; the app and webhook handlers use distinct roles.
- **Webhooks as the source of truth** for any state that lives in a third party (Stripe subscriptions reconcile into Supabase, never the other way around).
- **Golden-master testing for anything with money on the line.** The autotrader's 180-day backtest is frozen byte-for-byte in CI — behavior changes must be intentional and re-blessed, never accidental.

### Get in touch

<p>
  <a href="https://streamvault.gg"><img alt="streamvault.gg" src="https://img.shields.io/badge/Web-streamvault.gg-22c55e?style=for-the-badge" /></a>
</p>

<p align="center">
  <sub>📍 Melbourne, Australia</sub>
</p>
