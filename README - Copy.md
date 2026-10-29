# THE STUDY TREE
Learn. Practise. Grow.

React + TypeScript educational website starter for Classes 1–10, with lesson search, sample chapter mock tests, and an Express/Prisma backend.

## Run locally
1. Install Node.js 20+.
2. In this folder run `npm install` and `npm run install:all`.
3. Copy `server/.env.example` to `server/.env` and change the admin password and JWT secret.
4. Run `npm run db:setup`.
5. Run `npm run dev` and open http://localhost:5173.

## GitHub upload
Create a repo, then upload the extracted project contents. Never upload `.env` or secrets.

## Public deployment
GitHub stores code; it does not host this full-stack app by itself. Deploy the client to Vercel/Netlify and server to a Node host. Use a managed PostgreSQL database in production and configure environment variables. The sample question bank is only a starter and must be expanded and reviewed for complete syllabus coverage.
