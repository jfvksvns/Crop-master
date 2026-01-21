Soil Project 🌱

A modern web application for soil data visualization and environmental insights. Built with Next.js 13 (App Router), TypeScript, and TailwindCSS, the project emphasizes clean architecture, reusable UI components, and scalable patterns for dashboards and geospatial data apps.

🚀 Deployment

Production Server:
👉 https://soil-crop.netlify.app/

🧩 Tech Stack

Next.js 13+ — App Router, Server Components, and modern React

TypeScript — Strict typing for safer, maintainable code

TailwindCSS — Utility-first styling for rapid UI development

pnpm — Fast, disk-efficient package manager

shadcn/ui — Accessible, themeable React components

📂 Project Structure
soil/
├── app/                 # App Router pages, layouts, global styles
│   ├── page.tsx         # Main application page
│   ├── layout.tsx       # Root layout wrapper
│   └── globals.css      # Global TailwindCSS styles
│
├── components/          # Reusable UI components (accordion, charts, buttons, etc.)
│   └── ui/              # Shadcn-based UI elements
│
├── public/              # Static assets
│
├── package.json         # Project metadata & scripts
├── next.config.mjs      # Next.js configuration
├── tailwind.config.ts   # TailwindCSS configuration
├── tsconfig.json        # TypeScript configuration
└── pnpm-lock.yaml       # Dependency lockfile

🎨 UI Components Included

The project ships with a modular set of reusable UI components:

Buttons, Inputs, Checkboxes

Dialogs, Alerts, Tooltips

Cards, Accordions, Tabs

Charts & Data Visualization utilities

🔧 Installation & Usage
pnpm install
pnpm dev


Runs locally at: http://localhost:3000

📝 License

Licensed under the MIT License.
Free to use, modify, and distribute without restrictions.
