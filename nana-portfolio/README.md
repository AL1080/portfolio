# Nana Rexford -- 3D Creator Portfolio

A dark, animated 3D-creator portfolio built with React, TypeScript, Tailwind CSS, and Framer Motion.

## Run it locally

```bash
npm install
npm run dev
```

Then open the local URL Vite prints (usually http://localhost:5173).

## Build for production

```bash
npm run build
npm run preview
```

## Before deploying

- Wire up `ContactButton` (in `src/components/ContactButton.tsx`) to your real contact method (mailto link, form, or modal) -- it currently just renders the button.
- Swap the placeholder "Live Project" links in `src/sections/ProjectsSection.tsx` for the real project URLs.
- Double check hero portrait and decorative images resolve for you -- they're hot-linked from the original design spec's asset host.
