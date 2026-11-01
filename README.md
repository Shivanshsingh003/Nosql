# Campus Placement Management System - Frontend

A modern, production-grade Next.js frontend application built with a dark SaaS aesthetic, Tailwind CSS, TypeScript, and Lucide React.

## Key Features

- **Role-based Workspaces**:
  - **Student Workspace**: Dashboard metrics, eligibility-checked job browsing, detailed job applications with resume attachment, live application tracking, and profile management with projects & certifications.
  - **Admin Workspace**: Executive command center with interactive Recharts analytics (volume by company, recruitment status distribution, branch-wise placement), corporate partner management, job posting lifecycle management, and application status pipeline updater.
- **Design System & Aesthetics**:
  - Dark mode by default (`#0f0f1a` background, `#1a1a2e` glassmorphism card surfaces)
  - Inter font from Google Fonts
  - Indigo-to-Violet gradient accents
  - Loading skeleton pulses and micro-interactions
  - Real-time form validation via Zod and React Hook Form
  - Notifications powered by `react-hot-toast`

## Getting Started

### 1. Install dependencies
```bash
cd campus-placement/frontend
npm install
```

### 2. Configure Environment
Verify `.env.local` has the backend URL:
```env
NEXT_PUBLIC_API_URL=http://localhost:8000
```

### 3. Run Development Server
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the portal.
