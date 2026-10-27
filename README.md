# Deamenophobia

I build tools for understanding data, exploring code, and working with infrastructure.
My projects include local analytical workbenches, reusable interfaces, and focused
utilities in Rust, TypeScript, JavaScript, Python, Go, and Java.

**Personal blog:** [happykokoro.com](https://happykokoro.com/)

[Data & visualization](#data-processing--visualization) ·
[Developer tools](#developer-tools--interfaces) ·
[Infrastructure](#infrastructure--operations) ·
[Architecture](#architecture-references)

## Data Processing & Visualization

| Project | What it does | Main technologies |
| --- | --- | --- |
| [Streamweave](https://github.com/Deamenophobia/streamweave) | Compose numerical workflows over timestamped datasets; align sources, inspect intermediate results, and export reproducible studies. | TypeScript, React, Web Workers; optional Python, NumPy and SciPy |
| [Book Replay](https://github.com/Deamenophobia/book-replay) | Import recorded books and trades, reconstruct order books, replay events, and inspect decimal-based depth analytics. | Rust, Axum, Tokio, SQLite, JavaScript and SVG |
| [Orderflow Chart](https://github.com/Deamenophobia/orderflow-chart) | Explore liquidity heatmaps, trade bubbles and candles in a shared time/price view, or embed the renderer in another interface. | JavaScript ES modules, Canvas 2D, HTML and CSS |

Book Replay exports recorded data directly to Orderflow Chart through chart JSON.
Streamweave provides a separate, general numerical workspace with its own table
and project formats; connecting these workflows would require a conversion adapter.

[Browse data-processing repositories](https://github.com/search?q=user%3ADeamenophobia+topic%3Adata-processing&type=repositories)

## Developer Tools & Interfaces

| Project | What it does | Main technologies |
| --- | --- | --- |
| [Repo Explorer](https://github.com/Deamenophobia/repo-explorer) | Explore a code repository with cited answers, focused source maps and saved review decisions. | Python, LangChain, LangGraph, FastAPI and React |
| [Retro Workbench UI](https://github.com/Deamenophobia/retro-workbench-ui) | Start a compact workbench interface with reusable controls, SVG charts, and Classic or Studio appearances. Adapted from Streamweave's UI. | React, TypeScript, Vite and SVG |

[Browse developer tools](https://github.com/search?q=user%3ADeamenophobia+topic%3Adeveloper-tools&type=repositories)

## Infrastructure & Operations

| Project | What it does | Main technologies |
| --- | --- | --- |
| [Ops Compass](https://github.com/Deamenophobia/ops-compass) | Organize service catalogs, AWS/SSH connections, runbooks, worklogs and read-only tools for AI clients in a local operations portal. | Backstage, TypeScript and React |
| [VPN Config Kit](https://github.com/Deamenophobia/vpn-config-kit) | Manage configuration for a single WireGuard gateway, with optional Xray support. | Rust, WireGuard and Xray |
| [VPN Toolkit Go](https://github.com/Deamenophobia/vpn-toolkit-go) | Generate AnyTLS server configurations and client profiles through a CLI or local web UI. | Go and AnyTLS |

[Browse infrastructure tools](https://github.com/search?q=user%3ADeamenophobia+topic%3Ainfrastructure&type=repositories)

## Architecture References

| Project | What it demonstrates | Main technologies |
| --- | --- | --- |
| [Spring Cloud Commerce Reference](https://github.com/Deamenophobia/springcloud-enterprise-demo) | A small commerce system illustrating service boundaries, JWT security, persistence, containers and deployment workflows. | Java, Spring Boot / Cloud, PostgreSQL, Docker and Kubernetes |

The [Example](https://github.com/Deamenophobia/Example) repository is currently a
README-only placeholder for future technology-stack examples.

## Working Approach

- Keep responsibilities explicit and modules focused.
- Reuse sound implementations and separate dependencies where needed.
- Preserve data semantics, numerical limits and reproducible inputs.
- Prefer useful behavior checks and complete user workflows over test counts.
- Document what works today and keep future ideas clearly identified.

Each repository's README covers setup, supported behavior and current limits.
Use its issues to report a problem or discuss a concrete improvement.
