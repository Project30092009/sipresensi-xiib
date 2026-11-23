# SIPRESENSI XII-B — Frontend Demo

Vue 3 + Vite. Frontend demo only; login is simulated locally and is not secure authentication.

## Run

```bash
npm install
npm run dev
```

## Demo login

- Student: NISN `0123456789`, password `demo123`
- Secretary: username `sekretaris`, password `admin123`

## New features in this version

- Login screen before dashboard (simulated)
- Student menu separates session dispensation and full-day leave
- Full-day leave accepts date range, illness requires photo proof
- Secretary can review requests; approval creates attendance entries for each of the five two-hour sessions per day

No backend or real OCR is included yet. Demo data and session storage remain browser-local.
