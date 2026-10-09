<h1 align="center">Adham · Full-Stack Developer</h1>

<p align="center">
  I build production web, mobile and desktop software end to end:<br/>
  ERP platforms, ride-hailing apps and Arabic-first (RTL) products.
</p>

<p align="center">
  <img alt="Location" src="https://img.shields.io/badge/Aswan%2C%20Egypt-0d1117?style=flat-square&logo=googlemaps&logoColor=white"/>
  <img alt="Languages" src="https://img.shields.io/badge/Arabic%20%2F%20English-0d1117?style=flat-square&logo=googletranslate&logoColor=white"/>
  <img alt="Focus" src="https://img.shields.io/badge/ERP%20%C2%B7%20Mobile%20%C2%B7%20Realtime-0d1117?style=flat-square"/>
</p>

```ts
const adham = {
  role: "Full-Stack Developer",
  based: "Aswan, Egypt",
  backend: ["NestJS", "Prisma", "PostgreSQL", "Redis", "Laravel"],
  frontend: ["React", "TypeScript", "Tailwind", "shadcn/ui", "TanStack Query"],
  mobile: ["Flutter", "Bloc", "Firebase"],
  desktop: ["Tauri"],
  ships: ["ERP systems", "ride-hailing apps", "payment flows", "bilingual AR/EN interfaces"],
};
```

## What I work on

Most of my work is private client code, so here is the shape of it instead of the links.

### School ERP platform &nbsp;·&nbsp; backend, web and desktop

A multi-module ERP running a private school group: admissions, student lifecycle, attendance, finance, HR, bus logistics, parent portal and public website.

- **API** — NestJS + Prisma on PostgreSQL: 120+ data models, 140+ migrations, 60+ feature modules, 170+ test suites (Jest, Supertest).
- **Finance** — double-entry journal and ledger, treasury, receipt books, cost centers, debts and reports, with idempotent writes to block duplicate submissions.
- **Integrations** — online payment gateway, Egyptian Tax Authority e-receipts, legacy data import pipelines (CSV / Excel).
- **Security** — JWT auth, policy-based dynamic permissions with a permission simulator, full audit trail, rate limiting, Helmet.
- **Realtime** — Server-Sent Events streams for staff and parents; Redis-backed caching.
- **Admin client** — React + TypeScript + shadcn/ui, Arabic RTL by default, virtualized tables, feature flags, Excel export. Ships as a web app on Cloudflare Workers and as a desktop app with Tauri. 100+ test files (Vitest, Testing Library, Playwright + axe).
- **Delivery** — GitHub Actions build-then-deploy pipeline, PM2 cluster mode with graceful reloads.

### Ride-hailing customer app &nbsp;·&nbsp; Flutter

A feature-first Flutter app with clean `data / domain / presentation` layering, built from a Figma flow.

- Bloc/Cubit state management, `get_it` + `injectable` DI, Dio + Retrofit typed API client, `go_router` navigation, Freezed models.
- Live ride tracking on Google Maps with polylines and geolocation, over WebSocket / Socket.IO.
- Stripe payments and wallet, coupons, in-app chat, SOS, push notifications (FCM).
- Arabic and English localization; unit, bloc and integration tests.

### Team task and project manager &nbsp;·&nbsp; Laravel

An internal project-management tool: projects, members, custom task statuses, saved filters and role-based task views.

- Laravel 13 + Livewire 4, Tailwind, role and permission management.
- Realtime team chat over WebSockets (Laravel Reverb + Echo).

### Financial dashboard for Excel &nbsp;·&nbsp; Office Add-in

An investor dashboard that reads a 3-year financial model and renders KPIs, charts and filters. Excel stays the single source of truth.

- Office.js task-pane add-in, plus a Python (openpyxl) sync script and browser fallback for locked-down tenants.
- Vanilla HTML / CSS / JavaScript with Chart.js.

### Marketing and company websites &nbsp;·&nbsp; React

Fast, typed landing sites with validated lead forms: React 19, Vite, Tailwind v4, React Hook Form + Zod, Zustand, international phone input, deployed on Vercel. Includes a bilingual (i18next) school website with admissions, careers, bus reservation and parent payment flows.

## Tech stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Backend**

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Livewire](https://img.shields.io/badge/Livewire-4E56A6?style=flat-square&logo=livewire&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)

**Mobile and desktop**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![Google Maps](https://img.shields.io/badge/Google%20Maps-4285F4?style=flat-square&logo=googlemaps&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=white)

**Testing and delivery**

![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2&logoColor=white)

## How I work

- **Typed end to end.** Schema-first data models, validated DTOs, Zod on the client, generated API clients on mobile.
- **Tests where the money is.** Finance, permissions and imports get the deepest coverage.
- **Arabic-first, not Arabic-added.** RTL layout, bilingual content and locale-aware formatting from day one.
- **Boring deployments.** Build in CI, deploy only on a green build, reload without dropping requests.

## Get in touch

Open to freelance and contract work on ERP, mobile and performance projects.


[![Email](https://img.shields.io/badge/Email-0d1117?style=flat-square&logo=gmail&logoColor=white)](mailto:domi.tech.1102@gamil.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adham-ahmed-161b202b4)
