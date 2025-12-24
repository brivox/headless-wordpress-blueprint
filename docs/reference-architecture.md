# Reference Architecture

## Principles
- WordPress is CMS only.
- Frontend is the application.
- Strict API contracts.
- Minimal plugin surface.
- CMS isolated from public traffic.

## Layers
- CMS (WordPress)
- API layer (custom endpoints)
- Frontend (SSR/SSG/ISR)
- Cache (Redis/CDN)
- Observability (logs/metrics)
