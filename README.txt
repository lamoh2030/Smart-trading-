SMART TRADING MULTI-PAGE WEBSITE
================================

Files:
- index.html: registration-only homepage
- login.html: separate login page
- dashboard.html, markets.html, trading.html, deposit.html, withdraw.html,
  history.html, referrals.html, support.html, profile.html, admin.html
- assets/style.css and assets/app.js: shared design and Supabase logic

DEPLOYMENT
1. Download and extract the ZIP.
2. In your GitHub repository, upload the extracted files and folders into the
   repository root (not inside an extra nested folder).
3. Keep index.html at the repository root.
4. Commit the changes. Vercel should deploy automatically if connected.

IMPORTANT
- The existing Supabase project URL and public publishable key are retained.
- Existing database tables/RPC names are retained; this package does not run SQL
  migrations or delete database records.
- Test with an existing account first.
- The home page contains only registration and a login link.
- Trading page is a safe placeholder: no fake live trading or real order
  execution is claimed. A real broker/exchange integration and secure server
  execution are still required.
- Demo balance is shown as a planned $10,000 starting amount only; no demo
  order engine is implemented in this package.
- Public market prices are not fabricated; a reliable live data feed must be
  connected before displaying them.
