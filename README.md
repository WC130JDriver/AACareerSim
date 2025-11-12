# AA Career Simulator (to 2054)

Vite + React + TypeScript app that models AA seniority movement (system-wide threshold) and 401(k) growth based on `hourly × monthlyCredit`.

## Quick start

```bash
npm install
npm run dev
```

Then open the URL Vite prints (usually http://localhost:5173).

## Uploads
- **Roster**: any .xlsx/.xls with columns resembling `Seniority Number`, `Fleet`, `Seat`, `Base`, `DOB`, `DOH` (headers are flexible).
- **Rates**: a sheet named like `Rates` with columns `Fleet`, `Seat`, `Year`, `HourlyRate`.

## Build
```bash
npm run build
npm run preview
```
