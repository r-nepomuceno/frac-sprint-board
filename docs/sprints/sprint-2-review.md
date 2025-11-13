# Sprint 2 — Review
**Goal:** Working staging app with DB + dynamic page  
**Staging URL:** https://<your-app>.onrender.com

## What’s Working (demo)
- `/health/` returns `ok`
- `/executives/` lists profiles from DB (Render Postgres)
- `/executives/<id>/` detail page
- Django Admin accessible; sample data added

## Completed Stories
- #NN Browse executives list — **3 pts**
- #NN Executive detail — **3 pts**
- #NN Health route — **1 pt**
- #NN Staging deploy (Render, Postgres, WhiteNoise) — **5 pts**

**Planned:** 12 pts  
**Completed:** 12 pts  
**Velocity:** 12  
**Completion rate:** 100%

## Incomplete Stories
- N/A (or list any, with reason and carryover plan)

## Lessons Learned
- Render free tier lacks shell → ran migrations via local `DATABASE_URL`
- WhiteNoise needed for admin/static in prod
- Env-driven `ALLOWED_HOSTS` prevents host errors

## Backlog Updates
- Add basic job classifieds model (Sprint 3)
- Add seed script/fixtures
- Simple search/filter (later)
