SLICE / IN MOTION — GLOBAL LEADERBOARD VERSION

1) Create a free Supabase project.
2) Open Supabase > SQL Editor.
3) Paste and run the entire contents of supabase_setup.sql.
4) In Supabase Project Settings > API, copy:
   - Project URL
   - anon/public key (NEVER use service_role in browser code)
5) Open sketch.js and find these near the top:
   const SUPABASE_URL = "https://wmbwdieaietetjxoqcrl.supabase.co";
   const SUPABASE_ANON_KEY = "sb_publishable_Sj2yTWvvFh1ZGs_VSB1LFg_wVpBc2MZ";
6) Replace only the placeholder strings with your values and save.
7) Commit + push the changed project to GitHub. Vercel will redeploy automatically.
8) Test once on your computer and once on your phone. Both should show the same GLOBAL TOP 5.

Notes:
- Each nickname keeps only its highest score.
- Top 5 is shared across devices.
- The anon/public key is intended for client-side use when RLS is configured. Do NOT expose service_role.
- This is a casual public leaderboard, not an anti-cheat system. A determined user could spoof scores from the browser.
