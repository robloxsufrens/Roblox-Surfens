# Security Policy

## Supported Versions

This project is a single-page browser game maintained on the `main` branch
only. There are no separate long-term-support versions.

| Version | Supported |
|---|---|
| `main` | ✅ |

## Reporting a Vulnerability

This is a client-side, static HTML/JS game with no server, database, or user
authentication — data (scores, coins, settings) is stored only in the
browser's `localStorage`. Security impact is therefore limited, but if you
find:

- A way to inject/execute arbitrary script beyond the page's own code
- A cross-site scripting (XSS) vector introduced through a contribution
- Any other client-side security issue

please open a private report via GitHub's **Security → Report a
vulnerability** tab, or open an issue marked `security` if that's not
available. Please avoid publicly disclosing details until it has been
addressed.

We'll do our best to respond within a few days.
