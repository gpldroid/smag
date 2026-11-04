# SMAG — Editorial Magazine

A modern, responsive editorial magazine for news, features, analysis, and long-form articles.

## Stack
- Astro static site generation
- Markdown content collections
- CSS design tokens with light and dark themes
- Vanilla JavaScript for lightweight interactions

## Development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Content
Add Markdown articles under `src/content/articles/`. Each article uses the schema documented in `src/content.config.ts`.

## Deployment
The project builds to `dist/` and can be deployed to any static hosting provider that supports Astro output.
