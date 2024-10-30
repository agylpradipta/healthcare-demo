# Healthcare Demo System

A demo healthcare management system built with Next.js, PostgreSQL, and Prisma.

## Features

- User Authentication (Registration/Login)
- Appointment Scheduling
- Patient Management
- Doctor Management

## Tech Stack

- **Frontend:** Next.js 13+, TailwindCSS
- **Backend:** Next.js API Routes
- **Database:** PostgreSQL
- **ORM:** Prisma
- **Authentication:** NextAuth.js
- **Styling:** TailwindCSS

## Prerequisites

- Node.js 18+
- PostgreSQL
- pnpm

## Setup

1. Clone the repository
```bash
git clone [your-repo-url]
cd healthcare-demo
```

2. Install dependencies
```bash
pnpm install
```

3. Set up environment variables
```bash
cp .env.example .env
# Update .env with your values
```

4. Set up the database
```bash
npx prisma db push
```

5. Start the development server
```bash
pnpm dev
```

## Development

- `pnpm dev` - Start development server
- `pnpm build` - Build for production
- `pnpm start` - Start production server
- `npx prisma studio` - Open Prisma Studio

## Contributing

1. Create a new branch (`git checkout -b feature/amazing-feature`)
2. Commit your changes (`git commit -m 'feat: add amazing feature'`)
3. Push to the branch (`git push origin feature/amazing-feature`)
4. Open a Pull Request

