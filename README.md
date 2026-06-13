# HackPilot (HACKPRIX-3.00)

HackPilot is an opinionated hackathon planning agent built with Vite + React + Tailwind (shadcn-style).
It turns a problem statement into a structured, time-aware project plan with architecture diagrams, MVP task boards, and a real-time AI co‑pilot.

---

**Highlights**
- Clean, responsive React UI using shadcn-style components
- AI-powered plan generation (integrates with Generative AI client)
- Task board, architecture tab, health dashboard, and team onboarding flows
- Themeable (dark/light) and production-ready build via Vite

**Quickstart**
1. Install dependencies

```bash
npm install
```

2. Run the dev server

```bash
npm run dev
```

3. Build for production

```bash
npm run build
npm run preview
```

---

**Project structure (important parts)**
- `src/` — React source
	- `components/` — UI + feature components (TaskBoard, ArchitectureTab, HealthDashboard)
	- `pages/` — route pages (Landing, Onboard, Plan, Index)
	- `lib/` — utilities & mock data
- `public/` — static assets (favicon.svg, favicon.ico)
- `index.html` — app entry (title, meta, fonts)

**Scripts**
- `npm run dev` — start Vite dev server
- `npm run build` — production build
- `npm run preview` — preview production build
- `npm run lint` — run ESLint

---




---

**Design & Colors**
- Primary accent: `#7c3aed` (used across UI gradients and glow effects)
- Light/dark themes are driven by CSS variables in `src/index.css`

**Notes & Next steps**
- Add CI for linting and type checks
- Provide API keys + env doc for Generative AI & Supabase (if used)
- (Optional) Export PNG/ICO favicon variants added to `public/`

---
