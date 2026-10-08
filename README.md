# ACCRA LIFE V3 — Online-ready project

This is now one project, designed to move from local prototype to a real online game.

## What is included
- One unified V3 codebase
- Supabase authentication
- Online player profile
- Online cash, energy, health, XP and level
- Online assets: land, vehicles and businesses
- Row Level Security database schema
- Mobile-friendly game UI
- Jobs and passive income
- Sign up / sign in / sign out

## Setup

1. Create a Supabase project.
2. Open Supabase SQL Editor and run `supabase/schema.sql`.
3. Copy `.env.example` to `.env`.
4. Put your Supabase project URL and publishable key in `.env`.
5. Install Node.js, then run:
   npm install
   npm run dev
6. Open the local URL shown by Vite.

Supabase Auth and its database integration are documented here:
https://supabase.com/docs/guides/auth

## Important
Never put a Supabase service-role/secret key in browser code. Use only the publishable key on the client.

## Next engineering stages
- server-side economic transactions so players cannot edit cash from the browser
- houses/rent
- interactive map
- transport routes and tro-tros
- random events
- crime/risk system
- marketplace/trading
- leaderboards
- admin panel
- payments/ads
- original graphics/audio
- deployment and custom domain
