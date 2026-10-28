# Deamenophobia

I build tools for crypto payments, data analysis, software development, and infrastructure.
My projects include backend services, local analytical workbenches, reusable interfaces,
and focused utilities in Rust, TypeScript, JavaScript, Python, Go, and Java.

**Personal blog:** [happykokoro.com](https://happykokoro.com/)

[Crypto, market data & numerical tools](#crypto-market-data--numerical-tools) ·
[AI & developer tools](#ai--developer-tools) ·
[Frontend & UI](#frontend--ui) ·
[Infrastructure & networking](#infrastructure--networking) ·
[Backend & microservices](#backend--microservices)

## Crypto, Market Data & Numerical Tools

| Project | What it does | Main technologies |
| --- | --- | --- |
| [Crypto Payment Core](https://github.com/Deamenophobia/crypto-payment-core) | Create USDC payment requests on Base, verify finalized transfers, and issue receipts, signed webhooks and optional single-use vouchers. | TypeScript, Fastify, PostgreSQL and viem |
| [Crypto Payment UI](https://github.com/Deamenophobia/crypto-payment-ui) | Provide customer checkout with wallet or QR/address payments, confirmation progress, and a read-only merchant dashboard for Payment Core. | TypeScript, React, Wagmi, viem, Vite and Fastify |
| [Book Replay](https://github.com/Deamenophobia/book-replay) | Import recorded books and trades, reconstruct order books, replay events, and inspect decimal-based depth analytics. | Rust, Axum, Tokio, SQLite, JavaScript and SVG |
| [Orderflow Chart](https://github.com/Deamenophobia/orderflow-chart) | Explore liquidity heatmaps, trade bubbles and candles in a shared time/price view, or embed the renderer in another interface. | JavaScript ES modules, Canvas 2D, HTML and CSS |
| [Streamweave](https://github.com/Deamenophobia/streamweave) | Compose numerical workflows over timestamped datasets; align sources, inspect intermediate results, and export reproducible studies. | TypeScript, React, Web Workers; optional Python, NumPy and SciPy |

Crypto Payment UI provides the optional checkout and dashboard for Crypto Payment Core.
Book Replay exports recorded data directly to Orderflow Chart through chart JSON.
Streamweave provides a separate, general-purpose numerical workspace with its own
table and project formats.

## AI & Developer Tools

| Project | What it does | Main technologies |
| --- | --- | --- |
| [Repo Explorer](https://github.com/Deamenophobia/repo-explorer) | Explore a code repository with cited answers, focused source maps and saved review decisions. | Python, LangChain, LangGraph, FastAPI and React |

## Frontend & UI

| Project | What it does | Main technologies |
| --- | --- | --- |
| [Retro Workbench UI](https://github.com/Deamenophobia/retro-workbench-ui) | Start a compact workbench interface with reusable controls, SVG charts, and Classic or Studio appearances. Adapted from Streamweave's UI. | React, TypeScript, Vite and SVG |

## Infrastructure & Networking

| Project | What it does | Main technologies |
| --- | --- | --- |
| [Ops Compass](https://github.com/Deamenophobia/ops-compass) | Organize service catalogs, AWS/SSH connections, runbooks, worklogs and read-only tools for AI clients in a local operations portal. | Backstage, TypeScript and React |
| [Small Server OB](https://github.com/Deamenophobia/small-server-ob) | Monitor servers across providers with SSH metrics, HTTP/TCP checks, optional Docker container inventory and health status, notes, local history and cost estimates. | JavaScript, Node.js, HTML/CSS, OpenSSH and Docker CLI |
| [VPN Config Kit](https://github.com/Deamenophobia/vpn-config-kit) | Manage configuration for a single WireGuard gateway, with optional Xray support. | Rust, WireGuard and Xray |
| [VPN Toolkit Go](https://github.com/Deamenophobia/vpn-toolkit-go) | Generate AnyTLS server configurations and client profiles through a CLI or local web UI. | Go and AnyTLS |

## Backend & Microservices

| Project | What it does | Main technologies |
| --- | --- | --- |
| [SaaS Admin Template](https://github.com/Deamenophobia/saas-admin-template) | Build SaaS identity and administration APIs with tenant isolation, organization roles, scoped API keys, MFA and optional OIDC sign-in. | TypeScript, Express, Prisma and PostgreSQL |
| [Spring Cloud Commerce Reference](https://github.com/Deamenophobia/springcloud-enterprise-demo) | A small commerce system illustrating service boundaries, JWT security, persistence, containers and deployment workflows. | Java, Spring Boot / Cloud, PostgreSQL, Docker and Kubernetes |

## Working Approach

- Keep responsibilities explicit and modules focused.
- Reuse sound implementations and separate dependencies where needed.
- Preserve data semantics, numerical limits and reproducible inputs.
- Prefer useful behavior checks and complete user workflows over test counts.
- Document what works today and keep future ideas clearly identified.

Each repository's README covers setup, supported behavior and current limits.
Use its issues to report a problem or discuss a concrete improvement.

[Browse all repositories](https://github.com/Deamenophobia?tab=repositories).
The [Example](https://github.com/Deamenophobia/Example) repository is currently a
README-only placeholder for future technology-stack examples.
