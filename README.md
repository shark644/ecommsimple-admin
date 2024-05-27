## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Authentication
Email: user@nextmail.com
Password: 123456

## Prisma
- `npm install prisma @prisma/client` to install required prisma packages
- `npx prisma init` to initialize schema
- update `DATABASE_URL` in .env file
- `npx prisma db pull` to pull schema from existing database
- `npx prisma db push` to push schema from `prisma\schema.prisma` to database
- `npx prisma generate` to generate models
- add queries to `/lib/database.ts`
