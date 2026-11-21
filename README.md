# AroMaa – Food Recipes App

A responsive food recipe app built with **Next.js 15** and **React 19**, using the [DummyJSON](https://dummyjson.com/docs/recipes) recipes API as its data source.

[![Live demo](https://img.shields.io/badge/demo-live-brightgreen?logo=vercel)](https://aroma-shardul.vercel.app/)
![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js)
![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3-06B6D4?logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-components-000000)

**Live demo:** https://aroma-shardul.vercel.app/

## Features

- **Incremental Static Regeneration (ISR)** – fast pages with content that refreshes without a full rebuild.
- **Streaming with Suspense** – progressive rendering with skeleton loading states.
- **Server-side, URL-based pagination, search and filtering** – shareable, bookmarkable, SEO-friendly URLs.
- **Browse by tag** – dedicated pages for recipe tags, plus a trending recipes section.
- **Async request APIs** – uses the latest Next.js handling of `params` and `searchParams`.
- **SEO** – dynamic sitemap, `robots.txt`, and static and dynamic metadata with Open Graph images.
- **`next/font`** for performance-optimised typography.
- **Dark and light themes** via `next-themes`.
- **Fully responsive** design for mobile, tablet and desktop.

## Tech stack

- [Next.js 15](https://nextjs.org/) (App Router) and React 19
- TypeScript
- Tailwind CSS
- [shadcn/ui](https://ui.shadcn.com/) components built on Radix UI, with Lucide icons
- [DummyJSON](https://dummyjson.com/) recipes API

## Getting started

```bash
git clone https://github.com/sharky412/Aroma.git
cd Aroma
npm install
npm run dev
```

Then open http://localhost:3000.

| Script          | Description                  |
| --------------- | ---------------------------- |
| `npm run dev`   | Start the development server |
| `npm run build` | Create a production build    |
| `npm start`     | Serve the production build   |
| `npm run lint`  | Run ESLint                   |

## Project structure

```
src/
├── app/          # App Router pages: home, recipes, recipes/[id], tag/[id], sitemap, robots
├── components/   # UI components (recipe cards, pagination, search, theme toggle, skeletons, shadcn/ui)
├── contexts/     # Theme provider
├── data/         # Models, enums, constants and helpers
├── hooks/        # Custom hooks
├── lib/          # Utilities
└── services/     # DummyJSON recipes API client
```
