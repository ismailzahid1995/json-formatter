# Community Distribution Posts — JSON Formatter & Validator

---

## 1. Reddit — r/webdev

**Title:** I built a free JSON formatter with tree view, live validation, and minification stats

**Body:**

Hey r/webdev,

I needed a JSON formatter that was fast, clean, and didn't assault me with ads. So I built one.

🔗 **https://ismailzahid1995.github.io/json-formatter/**

What it does:
- **Format / Beautify** — pretty-print with 2-space indent
- **Validate** — detailed error messages with position info
- **Minify** — compress and see the % savings
- **Tree View** — collapsible tree visualization (toggle between Code/Tree view)
- **Stats** — file size, total keys, max depth, root type
- **Live validation** — validates as you type with syntax highlighting

Everything runs in your browser. No backend, no tracking, no cookies. The entire thing is a single HTML file with zero dependencies.

Source: https://github.com/ismailzahid1995/json-formatter

What would you add? Thinking about JSON Schema validation and diff view.

---

## 2. Reddit — r/programming

**Title:** Show r/programming: Zero-dependency JSON formatter with tree view and live validation

**Body:**

Built a JSON tool that does the three things I constantly need: format, validate, and minify. Plus a tree view for navigating large payloads.

Features that set it apart:
- Stats dashboard: shows file size, key count, nesting depth
- Tree view with collapsible nodes
- Minification shows exact % savings
- Live validation as you type
- Pure vanilla JS, single file, no build step

https://ismailzahid1995.github.io/json-formatter/

Source (single HTML file): https://github.com/ismailzahid1995/json-formatter

---

## 3. Hacker News — Show HN

**Title:** Show HN: JSON Formatter & Validator – client-side, zero dependencies, tree view

**Body:**

Free JSON formatter that runs entirely in the browser. Format, validate, minify — with syntax highlighting, a collapsible tree view, and stats (size, keys, depth).

Single HTML file, no framework, no tracking.

https://ismailzahid1995.github.io/json-formatter/

Source: https://github.com/ismailzahid1995/json-formatter

---

## 4. Dev.to — Article

**Title:** Why I Built Yet Another JSON Formatter (And What Makes It Different)

**Body:**

Yes, there are a hundred JSON formatters out there. But most of them are:
- Bloated with ads
- Suspiciously asking you to paste production API responses
- Missing features I actually use

So I built my own. Here's what's different.

### It runs entirely client-side

Nothing is ever sent anywhere. Open DevTools, check the Network tab — zero requests. That means you can safely paste API responses with auth tokens, user data, or anything sensitive.

### Tree view for large payloads

When you're staring at a 500-line JSON blob, a tree view is invaluable. Click to collapse/expand nodes. Each object shows its key count, each array shows its item count.

### Stats at a glance

After formatting, you get: file size, total keys, max nesting depth, and root type. Useful for quickly understanding the structure of unfamiliar payloads.

### Minification with savings %

When I minify, I want to know how much I saved. The tool shows "Minified — saved 42% (1,234 → 716 chars)".

### Try it

🔗 **https://ismailzahid1995.github.io/json-formatter/**

It's a single HTML file: [GitHub](https://github.com/ismailzahid1995/json-formatter)

---

## Posting Notes
- **r/webdev** first (broadest audience for dev tools)
- **r/programming** 24-48h later (different angle: zero-dependency, stats)
- **HN**: anytime, keep it concise
- **Dev.to**: publish after getting initial feedback
