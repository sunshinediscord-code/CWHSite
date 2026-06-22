# Cryonics World Hub Site

Public static website for **Cryonics World Hub** / **CWH**.

This repository contains only the public website: HTML, CSS, light JavaScript, SVG assets and static-hosting configuration.

## Repository role

This repository is public by design.

Allowed here:

- public landing page;
- public brand assets;
- public CSS/JS;
- public FAQ/content pages;
- GitHub Pages / static hosting configuration.

Not allowed here:

- private project planning;
- backend logic;
- credentials, tokens, API keys;
- personal data;
- partner private contacts;
- medical/legal documents;
- internal financial or operational notes.

Private project materials live in the private repository:

```text
sunshinediscord-code/CWH
```

The old VPN project lives separately and must not be used as the working home for CWH:

```text
sunshinediscord-code/vpn-control
```

## Local preview

Open `index.html` directly or run a simple local server:

```bash
npm run dev
```

Then open:

```text
http://localhost:8080
```

Windows fallback:

```bash
npm run dev:win
```

## Publish directory

For GitHub Pages / Netlify / Cloudflare Pages, publish the repository root for now:

```text
.
```

The static entry point is:

```text
index.html
```

## Status

Current status: early static MVP.

No backend, accounts, forms, payment, chats or personal cabinets are active yet.
