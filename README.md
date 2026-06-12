# Next.js SVG Domination Page Transition

An SVG stroke-draw page transition for Next.js, animated with GSAP and [`next-transition-router`](https://github.com/vercel/next-transition-router).

**Author:** AJ

## Features

- SVG wipe/draw transition on route changes
- GSAP timeline animations for leave and enter
- Next.js App Router with shared layout and navbar

## Getting Started

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser. Use the navbar links (Home, About, Contact) to see the transition.

## Tech Stack

- [Next.js](https://nextjs.org)
- [GSAP](https://gsap.com)
- [next-transition-router](https://github.com/vercel/next-transition-router)

## Project Structure

- `src/providers/TransitionProvider.jsx` — SVG paths and GSAP leave/enter animations
- `src/components/NavBar/NavBar.jsx` — navigation links
- `src/app/` — App Router pages (home, about, contact)

## Scripts

| Command       | Description              |
| ------------- | ------------------------ |
| `npm run dev` | Start development server |
| `npm run build` | Build for production   |
| `npm run start` | Start production server |
