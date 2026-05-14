# Roadmap

A living document. Dates are intentions, not commitments. Open an issue if you want to nudge something up.

## Now (shipping)

- 📦 **Tool catalogue expansion** — going from 100 to 150 tools, prioritised by community 👍 on [tool requests](../../issues?q=is%3Aissue+label%3Atool-request)
- 🎨 **Visual polish pass** — consistent empty states, error messages, and result cards across every tool
- ⌨️ **Keyboard shortcuts** — copy result, clear input, focus next field on every tool page

## Next (planned)

- 🔗 **Shareable input state** — every tool gets an opt-in `?input=…` query so links reproduce a result deterministically
- ⚡ **Command palette** — `⌘K` from any page, fuzzy search across all 100 tools
- 📲 **PWA / offline mode** — install 100tools to your home screen; favourites work without a connection
- 🌍 **Localisation** — Spanish, French, German, Portuguese, Japanese to start
- 🧩 **Browser extension** — right-click any selection → run a 100tools utility

## Later (exploring)

- 🔌 **Public API** for read-only/stateless tools (UUID, hash, slug, base64, lorem ipsum)
- 🪝 **Webhook recipes** — sample integrations with Zapier, Make, n8n that use the API tier
- 📊 **Tool analytics dashboard** — anonymous, aggregate-only popularity stats (no per-user tracking)
- 🤖 **AI-assisted helpers** — opt-in, BYOK (bring-your-own-key) AI features for select text tools, with all data flow local-or-direct-to-provider (never through us)
- 🏢 **Team workspaces** — saved favourites, shared snippets, private to a workspace

## Not planned

We deliberately avoid:

- Accounts and logins required for core tools
- Server-side processing of user input (unless the tool fundamentally needs it)
- Tracking pixels, third-party analytics on tool pages
- Watermarks on outputs
- "Pro" tiers that gate the obvious features

If you want a tool that requires a backend, we'd rather not build it than build it badly. Suggest a privacy-respecting alternative in an issue.

---

Want to influence this list? **[Open an issue](../../issues/new)** or **[start a discussion](../../discussions/new)**.
