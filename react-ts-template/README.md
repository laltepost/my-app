# React + TypeScript + Vite + Tailwind Template

A minimal, production-ready starter for building React apps.

## Stack

- **React 19** — UI framework
- **TypeScript 5.9** — strict mode enabled
- **Vite 7** — dev server & build tool
- **Tailwind CSS 3** — utility-first styling
- **ESLint** — linting with React hooks & refresh plugins
- **pnpm** — package manager (npm/yarn also work)

## Quick Start

```bash
# 1. Copy this folder and rename it
cp -r react-ts-template my-new-project
cd my-new-project

# 2. Update the project name in package.json and index.html

# 3. Install dependencies
pnpm install

# 4. Start developing
pnpm dev
```

## Scripts

| Command         | Description                        |
|-----------------|------------------------------------|
| `pnpm dev`      | Start dev server with HMR          |
| `pnpm build`    | Type-check and build for production|
| `pnpm preview`  | Preview the production build       |
| `pnpm lint`     | Run ESLint                         |

## Path Aliases

Import from `src/` using the `@/` alias:

```tsx
import { MyComponent } from '@/components/MyComponent'
```

## Project Structure

```
├── src/
│   ├── App.tsx          ← start here
│   ├── main.tsx         ← React entry point
│   ├── index.css        ← Tailwind directives
│   └── vite-env.d.ts    ← Vite type declarations
├── public/              ← static assets
├── index.html           ← HTML entry
├── vite.config.ts
├── tailwind.config.js
├── tsconfig.json
├── eslint.config.js
└── package.json
```
