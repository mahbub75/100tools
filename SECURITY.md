# Security Policy

We take security seriously, even though 100tools is a browser-only product with no user accounts or stored data.

## What's in scope

- Any **XSS** or content-injection issue on **[100tools.site](https://100tools.site)** that affects other users.
- Any tool that **unexpectedly transmits** user input to a remote server (other than tools explicitly labeled `Runs on server`).
- Any tool that **stores** user input in `localStorage`, cookies, or IndexedDB in a way that's not clearly disclosed.
- Mixed-content, broken CSP, or supply-chain issues in our published bundles.

## What's out of scope

- "Browser-side processing can be intercepted by browser extensions." Yes, by design — the user controls their own browser. We assume an honest user agent.
- Issues that require physical access to the user's device.
- Rate-limiting or DoS reports against the static CDN — it's a static site.
- Reports based purely on automated scanner output without a working proof of concept.

## How to report

Please **do not** open a public GitHub issue for security reports.

Email **security@100tools.site** with:

- A description of the issue
- Steps to reproduce, or a minimal proof of concept
- The version of the page (URL with `?v=` if applicable) and your browser

We'll acknowledge receipt within **72 hours** and aim to ship a fix within **14 days** for confirmed issues. We don't currently run a paid bug bounty, but we credit reporters in the [CHANGELOG](CHANGELOG.md) if they'd like.

## Disclosure

We follow **coordinated disclosure**. Please give us a reasonable window to ship a fix before publishing details.
