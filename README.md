# Hi, I'm Adeel Uddin

**Full-Stack Developer — 10+ years building software.** I build practical, scalable software that solves real business problems: from intuitive user interfaces to backend systems, APIs, databases, and complete application workflows.

[Get in touch](#contact) · [LinkedIn](https://www.linkedin.com/in/adeeluddin01) · [See featured work](#featured-projects)

---

## About

I'm a full-stack developer with 10+ years of experience building software, working primarily with TypeScript, Next.js, and Supabase — and 50+ custom WordPress websites delivered end to end. I've been around computers since 2007, and I bring that same long-term curiosity to client work: I care about the business problem first and the framework second.

My strongest work is taking a rough idea — a booking flow, a marketplace, an internal operations tool — and carrying it through architecture, implementation, and deployment until it's actually running and usable. I'm comfortable owning the whole loop: requirements, data model, API, interface, auth and permissions, testing, and the unglamorous maintenance that keeps software alive after launch.

The WordPress track record taught me something frameworks don't: most business software lives or dies on the boring parts — reliable hosting, clean data, fast pages, and someone who answers when it breaks. I bring that operations mindset to every project, whether it's WordPress or a custom SaaS build.

I work best with clients who can describe the outcome they want and let me handle the engineering to get there.

---

## Technical expertise

Everything below is backed by shipped code in my repositories — no padding.

**Languages:** TypeScript, JavaScript, SQL

**Frontend:** React 19, Next.js 16 (App Router), Tailwind CSS 4, Progressive Web Apps

**Backend:** Node.js, Supabase (Auth, Realtime, Storage, Postgres)

**Databases:** PostgreSQL — schema design, migrations, Row-Level Security policies

**APIs & integrations:** REST API design, Google Maps Platform, Google OAuth 2.0

**Tooling:** Git, npm, Vercel

**Testing & deployment:** Vitest (unit tests), Playwright (end-to-end tests), production deploys on Vercel

*Currently studying: Python API development (FastAPI) and ORM patterns — personal learning, not client work yet.*

---

## Featured projects

### Karighar — on-demand home-services marketplace

A complete marketplace connecting customers with verified home-service providers across Karachi: customers book services, providers get verified and accept jobs, and an admin oversees the whole operation.

**The problem it solves.** Booking home services — AC repair, plumbing, electrical work — typically runs on phone calls and WhatsApp: no verified providers, no price transparency, no way to track a job once it's booked.

**What was built.** A web-first PWA with three roles (customer, provider, admin), email + Google OAuth sign-in, a full booking flow with fixed-price and custom jobs, provider onboarding with CNIC verification, live job-status updates, in-app chat, live provider location tracking, ratings and reviews, cash-on-delivery with a commission ledger, a provider earnings wallet, dispute handling, notifications, and an admin panel covering verification, catalog, jobs, settlements, and disputes. The database is managed as 15 versioned SQL migrations with Row-Level Security throughout.

**My contribution.** I authored 14 of the 21 commits in this repository, with feature work across the booking flow, the billing and commission logic, admin tooling, and the database migration chain. (Built on the open-source Karighar base by Matanza00, which I extended substantially.)

**Stack:** TypeScript · Next.js 16 · React 19 · Supabase (PostgreSQL) · Tailwind CSS 4 · Google Maps API · Vitest · Playwright

**Explore it:**

```bash
git clone https://github.com/adeeluddin01/karighar.git
cd karighar
npm install
npm run dev
```

The repo README walks through the Supabase setup (one SQL file seeds the whole schema), and `videos/` contains recorded walkthroughs of the customer, provider, and admin flows. `npm test` runs the Vitest suite covering the money/accounting logic and the job status state machine.

**Honest notes:** the public demo deployment is currently offline, so run it locally to see it working. Some roadmap items in the repo README (e.g. escrow payments, SMS OTP) are planned, not shipped.

---

## Client work

Selected client engagements. Implementation details stay private; what I can share is the problem, what was built, and what it changed.

### GaragePal — multi-garage management SaaS (Canada)

**The problem.** A client operating multiple garages ran each location on disconnected processes — bookings, day-to-day operations, and owner oversight lived in separate workflows, so running several sites meant juggling systems that didn't talk to each other.

**What was built.** A garage-management SaaS covering garage operations and bookings across multiple locations, with an owner-level view for overseeing every garage from one place.

**The outcome.** One system for the whole operation: bookings and daily management unified per location, with consolidated oversight for the owner instead of a patchwork of disconnected tools.

### SaudiPak — building & office management system (Islamabad)

**The problem.** Office operations spanning tenancy, space management, complaints, job slips, and maintenance reporting were running on paper trails and ad-hoc messaging — requests had no tracking, no assignment, and no accountability once they left someone's inbox.

**What was built.** A building and office-management system covering tenancy and space management, complaints, job slips, maintenance reporting, attendance, and role-based access for the teams who run the building day to day.

**The outcome.** Complaints, job slips, and maintenance requests moved into one permissioned system — tracked from report to resolution, with clear ownership at every step.

---

## Track record

- **50+ custom WordPress websites** — custom themes and custom functionality, from design through deployment to ongoing maintenance.
- **Karighar** — full home-services marketplace PWA (featured above).
- **GaragePal** — multi-location garage management SaaS for a Canadian client.
- **SaudiPak** — building and office management system for Islamabad operations.

---

## What I can build

Services I offer — grounded in the engineering above, scoped honestly per project:

- **Custom SaaS applications** — multi-user products with auth, roles, and billing-ready backends.
- **Business management platforms** — CRMs, operations tools, and systems that run a business day-to-day.
- **Internal dashboards & admin portals** — verification queues, catalogs, monitors, and reporting views.
- **Booking & scheduling systems** — service booking, provider/customer matching, status tracking.
- **Workflow & approval applications** — multi-step processes with roles, states, and audit trails.
- **REST APIs & backend services** — clean endpoints, secure auth, well-designed data models.
- **Database-driven applications** — PostgreSQL schemas, migrations, and Row-Level Security done right.
- **AI-assisted business features** — practical additions like smart search, summarization, or assisted data entry inside business apps.
- **Maintenance & improvement** — debugging, performance fixes, and feature work on existing applications.

---

## Engineering principles

- **Readable, maintainable code** — I write code the next developer can understand without a walkthrough.
- **Secure authentication & authorization** — auth is designed up front, not bolted on; permissions enforced in the database, not just the UI.
- **Clear application architecture** — features live where you'd expect to find them; structure follows the domain.
- **Thoughtful database design** — the schema reflects the real business rules, with constraints that protect data integrity.
- **Responsive, accessible interfaces** — software should work on a phone in the field, not just a desktop.
- **Validation & error handling** — inputs are validated, failures are handled, users get useful messages.
- **Useful documentation** — setup guides and READMEs that actually let someone run the project.
- **Testing & reliable delivery** — automated tests for the logic that matters (money, state machines, permissions).
- **Clear communication, realistic scope** — I'll tell you what something costs in time before we start, and flag trade-offs as they come up.

---

## Activity

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=adeeluddin01&show_icons=true&theme=github_dark&hide_border=true" alt="GitHub stats for adeeluddin01" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=adeeluddin01&layout=compact&theme=github_dark&hide_border=true" alt="Most used languages" />
</p>

*Live data from my public GitHub activity.*

---

## Contact

If you have a product idea, an existing application that needs work, or a business process that should be software by now — let's talk through it.

- **Email:** adeeluddin03@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/adeeluddin01
- **GitHub:** https://github.com/adeeluddin01

Tell me the outcome you want; I'll handle the engineering to get there.
