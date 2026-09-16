# ApiScribe 🧬

**Describe an API, get the blueprint** — Describe an API in plain English, get organized endpoints.

## What it does

Describe your API in plain English and ApiScribe drafts organized endpoints, params, and sensible responses. Powered by Pollinations.

- **Connect Pollen** → approve the consent screen → every request is paid from **your own** Pollen balance (default budget 5, valid 7 days, revocable anytime from https://enter.pollinations.ai/keys).
- Free tier: `openai/gpt-5.4-nano` · Premium toggle: `openai/gpt-5.5`.

## Options

- **API style:** `REST/GraphQL`
## Stack

- Static single-file frontend (no build step), deployed on GitHub Pages.
- Pollinations [Connect User Wallets / BYOP](https://github.com/pollinations/pollinations/blob/main/BRING_YOUR_OWN_POLLEN.md) OAuth PKCE flow — the app never touches your secret key.
- Scoped keys live in `sessionStorage` only, never localStorage/logs/URLs.

## Links

- **Live app:** https://fadyabohamza-netizen.github.io/apiscribe/
- Source: https://github.com/fadyabohamza-netizen/apiscribe
- App key (publishable, earnings enabled): `pk_itRy3u7x64ngHgQx`
- Powered by [Pollinations](https://gen.pollinations.ai) · Author: [fadyabohamza-netizen](https://github.com/fadyabohamza-netizen)
