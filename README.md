> This website was generated with [PageAI](https://pageai.pro).
>
> 1-shot production-ready websites with a design system and AI-powered content generation.
> Get started on **[pageai.pro](https://pageai.pro)**.

Vibe Coding Starter
===================

This starter was created as part of the [Vibe Coding Starter](https://pageai.pro/vibe-coding-starter-guide) tutorial.

See the full video here:

[![Image](https://pageai.pro/static/images/blog/vibe-coding-starter-guide.jpg)](https://www.youtube.com/watch?v=p_q7-iW606U)

- [Installation](#installation)
- [Development](#development)
- [Build](#build)

## Installation

```bash
npm i
```

## Development

First, run the development server:

```bash
npm run dev
```

### Note: `next-env.d.ts` changes during dev

On Next.js 16, `npm run dev` may rewrite `next-env.d.ts` to reference
`./.next/dev/types/routes.d.ts`, while `npm run build` may switch it back to
`./.next/types/routes.d.ts`.

If you want to ignore this local-only churn while developing:

```bash
git restore next-env.d.ts
git update-index --skip-worktree next-env.d.ts
```

To revert that behavior later:

```bash
git update-index --no-skip-worktree next-env.d.ts
git restore next-env.d.ts
```

## Build

To build the site for production, run the following command:

```bash
npm run build
```
