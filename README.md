# StoreXray

> **Showcase page.** This repository is a public showcase of a **private repository**:
> it contains a description of the work only, with **no source code**.

**Instant Amazon audit plus managed-service SaaS.** Paste a store URL and get a 60-second X-ray: listing health, revenue estimate, hidden upside, hijacker detection, and the specific fixes that move the needle, then convert into a managed-service lead.

## What I built

- **Audit engine** - pure-JavaScript extraction from listing pages, with no headless browser, so the whole product stays serverless and cheap to run
- **Scoring** - listing-health checks, revenue estimation, upside detection and hijacker (unauthorised seller) detection
- **Lead conversion** - one-click "have your team contact me" flow turning an audit into a sales lead
- **Auth** - local scrypt password authentication with no external auth dependency
- **Background worker** for longer-running audits
- **Admin area** for reviewing audits and leads

## Stack

Next.js 14 (App Router), TypeScript, Tailwind CSS, Supabase Postgres, scrypt auth, serverless deployment

---

*Source code is private. This page documents the work; code can be shared on request.*
