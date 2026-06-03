# Neighbor
 
Volunteer matching for Orange County. A curated directory of local organizations paired with an AI-assisted matching layer that connects people to the right place to show up.
 
---
 
## What it does
 
- Browsable, searchable directory of 20+ OC nonprofits and community organizations
- AI-assisted matching based on skills, availability, and interests
- Organization dashboard for managing volunteer inquiries (coming soon)
## Tech stack
 
- **Frontend** — Next.js, React, TypeScript, Tailwind CSS
- **Backend** — Python, FastAPI (via [sunrise-api](../sunrise-api))
- **Database** — Supabase (PostgreSQL)
## Getting started
 
### Prerequisites
 
- Node.js 18+
- Python 3.14+
- Supabase account or local instance
### Install
 
```bash
git clone https://github.com/sunrise-atelier/neighbor
cd neighbor
npm install
```
 
### Environment variables
 
```bash
cp .env.example .env.local
# fill in your Supabase URL and anon key
```
 
### Run locally
 
```bash
npm run dev
```
 
Open [http://localhost:3000](http://localhost:3000).
 
## Contributing
 
See [CONTRIBUTING.md](https://github.com/sunrise-atelier/sunrise-api/blob/main/CONTRIBUTING.md) for guidelines. Browse [`good first issue`](../../issues?q=is%3Aopen+label%3A%22good+first+issue%22) to find a starting point.
 
---
 
Part of [Sunrise Atelier](https://github.com/sunrise-atelier) — free, open-source tools for underserved communities.
