# Agent-Matrix

**Alive, governed super‑intelligence for enterprises**

This repository hosts the **Agent‑Matrix public website**, published using **GitHub Pages (Option A: Organization Site)**.

🌐 **Live site:** [https://agent-matrix.github.io/](https://agent-matrix.github.io/)

---

## What is this repository?

This repo exists **only to publish the Agent‑Matrix website**.
It is the organization‑level GitHub Pages site for the **agent‑matrix** organization.

* The site is built from a **single static `index.html`**
* No backend, no build step, no Jekyll required
* Updates are deployed automatically on push to `main`

If you are looking for source code, SDKs, or infrastructure, see the repositories listed below.

---

## How GitHub Pages is configured (Option A)

This site uses **GitHub Pages → Organization Site**.

**Settings → Pages**

* **Source:** Deploy from a branch
* **Branch:** `main`
* **Folder:** `/ (root)`

Because the repository name is **`agent-matrix.github.io`**, GitHub automatically publishes:

```
https://agent-matrix.github.io/
```

HTTPS is enforced automatically.

---

## Repository structure

```
/
├── index.html        # Main site (architecture, system overview, demos)
├── README.md         # This file
```

Everything lives in `index.html` by design to keep publishing simple and robust.

---

## Core platform repositories

These repositories implement the actual Agent‑Matrix system:

* **matrix-hub** — Catalog, registry, memory
* **matrix-guardian** — Governance, policy, safety
* **matrix-ai** — Reasoning & planning
* **matrix-architect** — Execution & controlled self‑repair
* **matrix-system** — CLI, SDK, control plane

👉 [https://github.com/agent-matrix](https://github.com/agent-matrix)

---

## Network & ecosystem

* **network-matrixhub** — AgentLink / network layer
* **catalog** — Public + private capability catalogs
* **mcp_ingest** — MCP manifest ingestion
* **matrix-cli** — Operator interface
* **matrix-python-sdk** — SDK for integration
* **infra** — Infrastructure & deployment

---

## Updating the website

1. Edit `index.html`
2. Commit and push to `main`
3. GitHub Pages redeploys automatically (usually < 1 minute)

No build tools required.

---

## Why this approach?

* **Zero‑friction publishing**
* **No CI failures** blocking the site
* **Maximum reliability** for documentation + demos
* **Clear separation** between marketing/architecture and production code

This repo is intentionally minimal.

---

## License

Site content © Agent‑Matrix.
Code in other repositories may have separate licenses.

---

If you are new to the system, start here:
👉 [https://agent-matrix.github.io/](https://agent-matrix.github.io/)
