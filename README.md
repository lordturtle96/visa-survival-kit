# Visa Survival Kit

Production-ready Next.js 14 + Supabase app for tracking visa constraints, sponsorship-ready semiconductor employers, and job applications across UK, USA, Canada, Germany, Australia, Netherlands, Ireland, Singapore, and UAE.

## Features
- Country selector with cascaded visa type selector
- Visa countdown with urgency thresholds
- Dynamic visa rules and alerts
- Searchable semiconductor employer directory
- Job application tracker
- Interview prep accordion
- Country-specific visa conversation guide
- Supabase magic link auth
- JSON import endpoint for profile + applications

## Tech stack
- Next.js 14 (App Router)
- TypeScript
- Tailwind CSS
- Supabase
- Vercel

## Getting started
1. Install dependencies with `npm install`
2. Copy `.env.example` to `.env.local`
3. Create a Supabase project and set the env vars
4. Run the SQL in `supabase/migrations/001_initial.sql`
5. Run the seed SQL in `supabase/seed.sql`
6. Start the app with `npm run dev`

## Environment variables
See `.env.example`.

## Deployment
Deploy to Vercel and set the same environment variables in the Vercel project settings.

## Repository URL
https://github.com/lordturtle96/visa-survival-kit

## Live URL
A live Vercel URL must be created after connecting the repo to Vercel and configuring Supabase credentials.
