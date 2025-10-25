# Dealer-App
# Dealer Platform

A modern automotive inventory management platform for dealerships.

## Features
- 📊 Real-time inventory analytics
- 💰 AI-powered pricing optimization
- 🚗 VIN decoder integration
- 📈 Market intelligence dashboard

## Tech Stack
- **Backend:** Node.js, Express, Prisma, PostgreSQL
- **Frontend:** React, TypeScript, Tailwind CSS, Vite
- **Database:** PostgreSQL, Redis
- **Deployment:** Railway/Docker

## Getting Started

### Prerequisites
- Node.js 18+
- PostgreSQL
- Redis (optional for development)

### Installation

1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/dealer-platform.git
cd dealer-platform
```

2. Install dependencies
```bash
npm install
cd backend && npm install
cd ../frontend && npm install
```

3. Setup environment variables
```bash
cd backend && cp .env.example .env
cd ../frontend && cp .env.example .env
```

4. Setup database
```bash
cd backend
npx prisma migrate dev
```

5. Start development servers
```bash
# From root directory
npm run dev
```

## Scripts

- `npm run dev` - Start both backend and frontend
- `npm run build` - Build for production
- `npm run rename` - Rebrand the application

## License

MIT
```

**.gitignore**
```
# Dependencies
node_modules/
.pnp
.pnp.js

# Production
dist/
build/

# Environment
.env
.env.local
.env.production

# Database
*.db
*.sqlite

# IDE
.vscode/
.idea/
*.swp
*.swo
.DS_Store

# Logs
*.log
npm-debug.log*

# Testing
coverage/

# Prisma
backend/prisma/migrations/
