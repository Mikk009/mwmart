# MWM Music with Mike

Premier music school website for **MWM Music with Mike**, located in Jos, Plateau State, Nigeria.

## About

MWM Music with Mike offers high-quality music education for all ages and skill levels — piano, guitar, drums, vocals, and more. The website showcases programs, pricing, and enrollment information.

## Tech Stack

- **React 18** + **TypeScript**
- **Vite** — fast dev server & build tool
- **Tailwind CSS** — utility-first styling with a custom dark/gold design system
- **shadcn/ui** — accessible UI components built on Radix UI
- **React Router** — client-side routing
- **TanStack React Query** — data fetching & caching

## Features

- 🎵 Responsive single-page layout with smooth navigation
- 🎹 Three-tier program showcase (Foundation, Intermediate, Professional)
- 👤 Private & group lesson breakdowns with pricing in Naira (₦)
- 📱 Mobile-friendly navbar with hamburger menu
- 🔗 External registration link integration
- 🎨 Custom dark theme with gold accent design system

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) 18+ or [Bun](https://bun.sh/)

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

The app runs at `http://localhost:8080`.

### Build

```bash
npm run build
```

### Testing

```bash
npm run test
```

## Project Structure

```
src/
├── components/       # UI sections & shared components
│   ├── Navbar.tsx
│   ├── HeroSection.tsx
│   ├── AboutSection.tsx
│   ├── ProgramsSection.tsx
│   ├── WhyUsSection.tsx
│   ├── ContactSection.tsx
│   ├── Footer.tsx
│   └── ui/           # shadcn/ui primitives
├── pages/
│   ├── Index.tsx      # Main landing page
│   └── NotFound.tsx
├── assets/            # Images
├── hooks/             # Custom React hooks
├── lib/               # Utilities
└── index.css          # Design tokens & global styles
```

## License

All rights reserved © MWM Music with Mike.
