# AfriStart OS

**A complete business operating system for African entrepreneurs.**

AfriStart OS helps entrepreneurs start a business, register it correctly, stay compliant, run daily operations, and access trusted business services—all in one platform.

## What is AfriStart OS?

AfriStart OS is the operating system for your business. Unlike traditional registration services, we help you not just form your company—we help you run it every single day.

### Key Differentiator

> "What needs my attention today?"

Every business owner logs in and sees:
- 💰 Money owed (unpaid invoices)
- 📄 Documents missing
- ⚖️ Compliance due
- ✅ Tasks pending
- 📍 Next business step

## Core Modules

### 1. **Start Module** (Business Formation)
- Country selector
- Business structure recommendation
- Registration checklist
- Document upload
- Payment processing
- Registration status tracking
- Tax ID guidance
- Bank account readiness checklist

### 2. **Run Module** (Business Operations)
- Business dashboard
- Invoice management
- Expense tracking
- Customer management
- Supplier tracking
- Income tracking
- Business tasks
- Cash snapshot

### 3. **Compliance Module** (Stay Legal)
- Compliance calendar
- Annual return reminders
- Tax deadline reminders
- License renewal reminders
- Document expiry alerts
- Filing history
- Accountant/lawyer access

### 4. **Vault Module** (Document Storage)
- Incorporation certificates
- Tax documents
- Government IDs
- Permits & licenses
- Invoices & receipts
- Contracts
- Founder documents
- Bank documents

### 5. **Advisory Module** (Get Help)
- AI-powered guidance
- Business type guidance
- Tax explanations
- Invoice templates
- Contract templates
- Compliance explanations
- Document checklists

### 6. **Marketplace Module** (Find Services)
- Accountants
- Lawyers
- Tax advisors
- Banks
- Insurance providers

## MVP Features (Phase 1)

✅ User authentication (email/password)
✅ Country selector & business wizard
✅ Dashboard with business status summary
✅ Invoice creation, sending, & tracking
✅ Expense tracking with categories
✅ Customer management
✅ Document vault with file uploads
✅ Task management
✅ Registration progress tracker
✅ Compliance calendar with reminders
✅ Admin dashboard
✅ Responsive mobile design

## Tech Stack

### Frontend
- **Next.js 14** - React framework with SSR/SSG
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first styling
- **Shadcn/UI** - High-quality components
- **Zustand** - State management
- **React Query** - Server state management

### Backend
- **Next.js API Routes** - Serverless backend
- **PostgreSQL** - Relational database
- **Prisma ORM** - Database management
- **NextAuth.js** - Authentication
- **Zod** - Schema validation

### Infrastructure
- **Vercel** - Frontend deployment
- **Railway/Render** - Backend & database
- **AWS S3** - File storage
- **Stripe/Paystack** - Payments

## Getting Started

### Prerequisites
- Node.js 18+
- PostgreSQL 14+
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mutiu245/afristart-os.git
   cd afristart-os
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env.local
   # Edit .env.local with your configuration
   ```

4. **Initialize database**
   ```bash
   npx prisma migrate dev
   npx prisma db seed
   ```

5. **Start development server**
   ```bash
   npm run dev
   ```

6. **Open in browser**
   ```
   http://localhost:3000
   ```

## Development

### Available Scripts

```bash
# Start development server
npm run dev

# Build for production
npm run build

# Start production server
npm start

# Run database migrations
npm run db:migrate

# Open Prisma Studio
npm run db:studio

# Lint code
npm run lint

# Format code
npm run format

# Run tests
npm run test
```

## Pricing Model

- **Free** - Business checklist, guides, 3 invoices/month
- **Start** - Guided registration, document collection, ₦50,000/month
- **Run** - Unlimited invoices, expense tracking, vault, ₦150,000/month
- **Grow** - Advisor access, tax support, templates, ₦500,000/month
- **Concierge** - Done-for-you services, ₦5,000,000+

## Initial Market

Launching in **Nigeria** with expansion to Kenya, Ghana, South Africa, and Rwanda.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

MIT License

## Support

- 📧 Email: support@afristart.io
- 🐛 Issues: [GitHub Issues](https://github.com/mutiu245/afristart-os/issues)

---

**AfriStart OS** - Your business. Operating system.
