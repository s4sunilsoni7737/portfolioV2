# Sunil Soni — Portfolio

Next.js (App Router) + TypeScript + Tailwind CSS v4 + GSAP.

## Run

```bash
npm install
npm run dev      # http://localhost:3000
npm run build && npm start
```

## Edit content

Everything lives in `lib/data.ts`: profile, projects, experience, skills, education.
Add a project by adding an object to `projects` (set `featured: true` for a full row).
Project screenshots for the older sites load from your GitHub Pages portfolio; to self-host,
put images in `public/images/` and change the `image` paths.

## Structure

- `components/Hero.tsx` — draggable, scroll-linked 360° ring (CSS 3D + GSAP)
- `components/Projects.tsx` — featured rows and "More work" list
- `components/Experience.tsx` — timeline that draws on scroll (GSAP ScrollTrigger)
- `app/layout.tsx` — fonts (Bricolage Grotesque, Source Serif 4 via next/font)
