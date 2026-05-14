# Example: a JSON workflow that doesn't leak your data

A common scenario for backend developers: you've got an API response with sensitive data and you want to clean it up, compare versions, and generate types — without pasting it into a sketchy "online JSON formatter" that may log everything.

This is exactly what 100tools is for.

## The workflow

### 1. Format and validate

Paste the raw response into the **[JSON Formatter](https://100tools.site/tools/json-formatter)**.

- Pretty-prints with 2- or 4-space indent
- Catches syntax errors with line numbers
- Lets you minify back to a single line for production

Your JSON never leaves the browser.

### 2. Diff against a known-good copy

Switch to **[JSON Diff](https://100tools.site/tools/json-diff)**.

- Paste yesterday's payload on the left, today's on the right
- Spot added, removed, and changed fields at a glance
- Useful for API regression hunts

### 3. Generate TypeScript types

Switch to **[JSON → TypeScript](https://100tools.site/tools/json-to-typescript)**.

- Drop the cleaned JSON in
- Get inferred `interface` definitions you can paste straight into your codebase
- Optionals are detected from missing keys across array elements

### 4. (Optional) Convert to CSV for the data team

Switch to **[JSON → CSV](https://100tools.site/tools/json-to-csv)**.

- Flatten nested keys with dot notation
- Pick which columns to keep
- Download as `.csv` for Sheets or BigQuery

## What you got

- A formatted, validated payload
- A clean diff vs the last known version
- TypeScript types for your client
- A CSV for non-developer stakeholders

All without sending a single byte to a server you don't control.

---

Got a workflow worth sharing? **[Open a PR](../CONTRIBUTING.md)** and add a file under `examples/`.
