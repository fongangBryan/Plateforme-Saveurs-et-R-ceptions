# Plateforme Saveurs & Réceptions

Application web multi-services combinant vente d'épices et marinades, location de matériel de réception et services traiteur événementiel.

## Structure

- `/frontend` : Application Next.js (React, Tailwind CSS)
- `/backend` : API FastAPI (Python)
- `/docs` : Documentation technique
- `/.github/workflows` : Pipelines CI/CD

## Stack

| Composant | Technologie |
|---|---|
| Frontend | Next.js, Tailwind CSS |
| Backend | FastAPI, Python 3.11 |
| Base de données | Supabase (PostgreSQL) |
| Paiement | Stripe |
| Email | Brevo |
| Hébergement | Vercel + Render |
| CI/CD | GitHub Actions |

## Installation locale

### Prérequis
- Node.js 18+
- Python 3.11+
- Docker (optionnel)

### Frontend
```bash
cd frontend
npm install
npm run dev