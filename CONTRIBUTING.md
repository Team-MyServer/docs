# Contributing

Thanks for helping improve the mysrvr.org documentation.

## Getting started

```bash
npm i -g mintlify
mintlify dev
```

Docs will be live at `http://localhost:3000` with hot reload on save.

## Making changes

All pages are `.mdx` files in the root of the repo. Mintlify supports standard Markdown plus a set of built-in components like `<Card>`, `<CardGroup>`, `<Info>`, and `<Warning>` — see the [Mintlify component docs](https://mintlify.com/docs/content/components) for the full list.

Navigation is controlled by `docs.json`. If you're adding a new page, register it there under the appropriate group.

## What to contribute

- Fixing typos or outdated information
- Clarifying confusing steps
- Adding missing detail to existing pages
- Reporting issues via GitHub Issues

If you're adding a whole new page, open an issue first to discuss it.

## Pull request process

1. Fork the repo and create a branch from `main`
2. Make your changes and verify them with `mintlify dev`
3. Open a pull request with a short description of what you changed and why
4. A maintainer will review and merge

Please keep PRs focused — one topic per PR makes review much faster.

## Style guidelines

- Write in plain, direct English
- Use second person ("you") when addressing the reader
- Prefer `<Info>` and `<Warning>` callouts over bold text for important notes
- Code examples should be complete and copy-paste ready
- Keep page descriptions (the `description` frontmatter field) to one sentence
