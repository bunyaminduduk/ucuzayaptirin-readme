# Ucuzayaptirin – Platform for Home Service Providers

**Ucuzayaptirin** is a platform that enables users to easily and securely find trusted businesses for their home service needs, such as plumbing, electrical work, or cleaning. The application is designed with scalability, data integrity, and security in mind.

## 🛠️ Tech Stack

- **Frontend:** Next.js (React) with TypeScript
- **Backend:** Nest.js (Node.js)
- **Database:** PostgreSQL (via Prisma ORM for type safety)
- **Session & Caching:** Redis (session management & email blacklist)
- **Storage:** Backblaze B2 via AWS S3-compatible API
- **Email Service:** SendGrid (for transactional emails)
- **Infrastructure:** Docker (for local development)

## ⚙️ Architecture Highlights

- Type-safe data models using Prisma with strict validation
- Role-based access control and secure API endpoints
- MIME-type validation and image compression (to WebP) before upload
- Session storage and rate-limiting via Redis
- Transactional emails for actions such as verification and booking confirmations

## 🔐 Closed Source Notice

This repository does not contain source code due to the private nature of the project. It exists as a reference to showcase the architecture, stack, and responsibilities involved.

## 🌐 Live Demo

Visit the live site at: [https://www.ucuzayaptirin.com](https://www.ucuzayaptirin.com)

> ⚠️ Please note: I am currently working on a full code refactor. The live site may differ from the version described here or what is currently under development.
