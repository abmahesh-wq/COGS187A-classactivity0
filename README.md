# COGS 187A Activity 0 — Vercel Frontend

Frontend hosting: Vercel
Backend/auth/storage: Supabase project tcpgckvbkqpoaobncmou

Routes:
- `/` — student submission portal
- `/instructor` — instructor email/password dashboard

No server-side secrets are included. The browser uses the Supabase publishable key; RLS/storage policies enforce access.

Vercel deployment:
1. Import this folder as a new Vercel project.
2. Framework preset: Other / Static.
3. No build command.
4. Output directory: leave blank/root.
5. Deploy.

Supabase requirements:
- Anonymous sign-ins enabled for students.
- Email/password auth enabled for instructors.
- activity_submissions table and activity-screenshots bucket already configured.
- Instructor RLS currently authorizes abmahesh@ucsd.edu and kirsh@ucsd.edu.
