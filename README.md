# NextJS template

## Tech stack
- NextJS
- Tailwind
- Shadcn
- stripe
- vercel
- supabase

## Rules
- Use server side as much as possible

## Setup

### Environment Variables
Create a `.env` file in the root directory with the following variables:

```env
# Supabase Configuration
NEXT_PUBLIC_SUPABASE_URL=your_supabase_project_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
```

### Database Setup
This template uses Supabase for authentication and database management. No additional database setup is required beyond configuring your Supabase project.

### Available Scripts
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint