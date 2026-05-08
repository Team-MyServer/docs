# mysrvr.org Docs

Documentation for [mysrvr.org](https://mysrvr.org) — the Discord server listing platform. Built with [Mintlify](https://mintlify.com).

## What's in here

| File | Description |
|------|-------------|
| `introduction.mdx` | Landing page and overview |
| `getting-started.mdx` | How to register a server |
| `bot-commands.mdx` | All slash commands |
| `dashboard.mdx` | Dashboard usage guide |
| `subdomain-system.mdx` | How subdomain routing works |
| `docs.json` | Mintlify configuration |

## Local development

**Prerequisites:** Node.js 18+

```bash
npm i -g mintlify
mintlify dev
```

The docs will be available at `http://localhost:3000`.

## Deployment

This repo is connected to Mintlify's hosted deployment. Pushing to `main` automatically deploys to the live docs site. No manual steps required.

## Links

- **Live site:** [mysrvr.org](https://mysrvr.org)
- **Dashboard:** [mysrvr.org/dashboard](https://mysrvr.org/dashboard)
- **Login:** [mysrvr.org/auth/login](https://mysrvr.org/auth/login)
