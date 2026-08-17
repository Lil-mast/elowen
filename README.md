# Elowen

A personal digital garden and writing space built with Quartz v4. This project publishes notes, essays, and reflections from the `content/` folder as a static website.

## About this site

This app is designed for:

- publishing personal notes and long-form writing
- keeping content in Markdown files
- generating a polished static site from a simple content structure
- previewing changes locally before publishing

The main content lives in `content/`, and the generated site is output to `public/`.

## Requirements

- Node.js 22 or newer
- npm or pnpm

This repository includes a `pnpm-lock.yaml`, so `pnpm` is the recommended package manager.

## Install dependencies

```bash
pnpm install
```

If you prefer npm:

```bash
npm install
```

## Build the site

Generate the static site output:

```bash
pnpm exec quartz build
```

or with npm:

```bash
npx quartz build
```

This builds the site into the `public/` directory.

## Run the local preview server

Start the local development preview:

```bash
pnpm exec quartz build --serve
```

or:

```bash
npx quartz build --serve
```

Then open this in your browser:

```text
http://localhost:8080/
```

The local preview server watches for changes in the content and rebuilds automatically while it runs.

## Optional: custom port

If you want to serve the site on a specific port:

```bash
pnpm exec quartz build --serve --port 8081
```

Then visit:

```text
http://localhost:8081/
```

## Useful project folders

- `content/` — the writing and note content for the site
- `public/` — generated static site output
- `quartz/` — Quartz app and build logic
- `quartz.config.ts` — site configuration

## Common workflow

```bash
pnpm install
pnpm exec quartz build --serve
```

Then edit files in `content/` and refresh the browser to see them appear in the local preview.

## Notes

This is a static site generator setup, so the site is best suited for local previewing and production deployment via a static host or a platform that supports generated HTML output.
