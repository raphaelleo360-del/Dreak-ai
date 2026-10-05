# Bachathon AI v0.2 — functional job platform prototype

## What is included
- Seeker and employer registration/login
- Password hashing with bcrypt
- Session-based authentication
- Job search and category filtering
- Job details and applications
- Seeker profile editing
- Seeker application tracking
- Employer job posting API
- Employer application review/status updates
- SQLite database with seed jobs

## Run locally
Requires Node.js 18+.

```bash
npm install
npm start
```
Then open `http://localhost:3000`.

## Important for production
This is a functional prototype, not a production deployment. Before launch, add HTTPS, a strong SESSION_SECRET, persistent production database/storage, email verification, password reset, rate limiting, CSRF protection, audit logs, moderation/admin tools, secure document uploads, legal/privacy pages, and payment/identity verification where applicable.
