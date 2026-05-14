# Frequently Asked Questions

## About the product

### What is 100tools?
A collection of 100 free, privacy-first online tools — text utilities, developer formatters, image editors, PDF tools, SEO helpers, and more — all running entirely in your browser.

### Where do I use it?
At **[100tools.site](https://100tools.site)**. There's nothing to install.

### How is it different from other "online tools" sites?
Three things:
1. **Privacy.** Everything runs in your browser. Other sites upload your text and files to a server; we don't.
2. **Speed.** Pages are statically prerendered and code-split — most tools load in under a second.
3. **No upsell.** Free, no accounts, no watermarks, no "Pro" gates.

### Is it really free?
Yes. Every tool. No usage caps, watermarks, or sign-up walls. Tool pages carry small, unobtrusive display ads to cover hosting — never anything that reads your input.

---

## Privacy & security

### Do you upload my files or text?
No. Tools are marked **client-side** by default and process input entirely in your browser. The handful that genuinely need a server (e.g. capturing a website screenshot, fetching a YouTube thumbnail) are clearly labeled on the tool page.

### Do you track what I do?
We use minimal, aggregate analytics for page views — never the content you paste, upload, or generate.

### Do I need an account?
No. There is no sign-up.

### Is my data sold? Shared? Stored?
No. There's no data to sell — your input never leaves your browser for client-side tools.

### What about the ads?
Display ads on tool pages are served by a third-party ad network and follow standard ad targeting (page topic, not page content). The home page, category pages, and 404 page are ad-free.

---

## Using the tools

### Do tools work on mobile?
Yes. Every tool is fully responsive and tested on small screens.

### Do tools work offline?
After the first visit, most tools continue to work without a connection because all processing is in-browser. We're working on full offline support via PWA install — see the [Roadmap](ROADMAP.md).

### Can I use the output commercially?
Yes. Anything you generate — formatted JSON, resized images, generated copy — is yours to use commercially with no attribution required.

### Why is tool X slow on a big file?
Browser-only tools are bounded by your device's CPU and memory. A 200 MB PDF will be slower than a 200 KB one. The trade-off for privacy. If a tool ever genuinely needs server-side processing for performance, we'll mark it accordingly.

### A tool gave me a wrong result. What now?
Please [open a bug report](../../issues/new?template=bug-report.md) with the exact input (or a sample that reproduces it). Reproducible reports get fixed fastest.

---

## Requesting and contributing

### How do I request a new tool?
[Open an issue](../../issues/new?template=tool-request.md) using the Tool Request template. Describe what it does, the input/output, and reference any tools you've used before. We prioritise by 👍 reactions.

### Can I contribute code?
The application source lives in a private repo so we can ship updates quickly. This public repo is for **docs, roadmap, issues, and discussions** — those contributions are very welcome (typo fixes, FAQ additions, example use cases, translations).

### Can I embed 100tools or its tools on my site?
Currently no — we don't offer an embed product. If there's enough demand, we may add it via the planned public API. [Vote on the issue](../../issues).

---

## Technical

### What's the tech stack?
Next.js (App Router), React, TypeScript (strict), Tailwind CSS, fully static export. See the [main README](README.md#tech-stack).

### Lighthouse scores?
100 on Accessibility, Best Practices, and SEO across the site. We treat regressions as bugs.

### Is there an API?
Not yet. A public, read-only API for stateless tools (UUID, hash, slug, base64, lorem ipsum) is on the [Roadmap](ROADMAP.md).

### Where's the sitemap?
[100tools.site/sitemap.xml](https://100tools.site/sitemap.xml).

---

Didn't find your answer? **[Start a discussion](../../discussions/new)** or **[open an issue](../../issues/new)**.
