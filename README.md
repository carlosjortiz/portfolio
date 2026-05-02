<h1 align="center">portfolio</h1>

<p align="center">
  The personal portfolio of <strong>Carlos J. Ortiz</strong>
</p>

<p align="center">
  <em>Where Modbus meets GraphQL — and microcontrollers talk to microservices.</em>
</p>

---

## About

Built where two worlds meet: industrial automation, where signals from PLCs and microcontrollers move physical things in the real world, and software engineering, where distributed services move bytes across networks at scale. After years working on both sides of that line, this site is an attempt to render the conversation in public — one where Modbus and GraphQL get equal billing, and a SCADA HMI is treated with the same respect as an OAuth flow.

## Stack

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://svgl.app/library/astro-icon-dark.svg" />
    <img alt="Astro" src="https://svgl.app/library/astro-icon-light.svg" height="44" />
  </picture>
  &nbsp;&nbsp;&nbsp;
  <img alt="Tailwind CSS" src="https://svgl.app/library/tailwindcss.svg" height="44" />
  &nbsp;&nbsp;&nbsp;
  <img alt="TypeScript" src="https://svgl.app/library/typescript.svg" height="44" />
</p>

- [Astro](https://astro.build) `6.1.9` — content-first framework, ships zero JS by default
- [Tailwind CSS](https://tailwindcss.com) `4.2.4` — wired through `@tailwindcss/vite`
- [TypeScript](https://www.typescriptlang.org) — `astro/tsconfigs/strict` preset

## Local development

All commands run from the project root.

| Command          | Action                                              |
| :--------------- | :-------------------------------------------------- |
| `pnpm install`   | Install dependencies                                |
| `pnpm dev`       | Start the dev server at `localhost:4321`            |
| `pnpm build`     | Build the production site to `./dist/`              |
| `pnpm preview`   | Preview the build locally before deploying          |
| `pnpm astro ...` | Run CLI commands like `astro add` or `astro check`  |

## A note on dependency pinning

Versions are pinned exactly (no caret) to satisfy a global pnpm `minimum-release-age` policy of seven days. When updating, confirm the new version was published more than a week ago.
