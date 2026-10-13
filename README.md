# FF League — Free Fire Tournament Website Starter

A responsive black/red esports front-end prototype for a Free Fire tournament organization platform.

## Included in this starter
- Responsive landing page and event cards
- Tournament overview / event list navigation
- Sample season standings table
- Team registration modal (front-end demo only; it does not save data yet)
- Captain dashboard placeholder
- Supabase SQL schema for profiles, teams, players, tournaments, registrations, matches, results and announcements
- Vite + React project ready for local development

## Run locally
1. Install Node.js LTS.
2. Extract this folder and open a terminal in it.
3. Run `npm install`
4. Run `npm run dev`
5. Open the local URL printed by Vite.

## Connect Supabase
1. Create a Supabase project.
2. Open SQL Editor and run `supabase/schema.sql`.
3. Configure authentication providers and signup policies.
4. Add the URL and publishable/anon key to `.env` using `.env.example` as a template.
5. Build the login, registration persistence and protected admin routes before public launch.

## Deploy
- Push this folder to a GitHub repository.
- Import the repository into Vercel.
- Add the Vite environment variables in project settings when Supabase integration is implemented.
- Deploy and test all access policies before sharing with teams.

## Important before real tournaments
- This is a starter UI, not a finished production system. Registration is currently demo-only.
- Admin authentication and role assignment must be completed securely. Never let users set their own role to `admin`.
- Add server-side validation, rate limits, audit logs, backup/export tools and test all Row Level Security policies.
- Do not expose room passwords in public queries. Use a protected table/API that checks approved tournament registration and captain identity.
- Confirm your chosen hosting plan permits your intended use. Free plans have usage limits and may restrict commercial use. Keep the project within the provider's terms.
- Use original or licensed logos, game artwork and tournament branding.
