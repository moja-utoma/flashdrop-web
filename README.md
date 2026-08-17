# FlashDrop Web

Angular frontend for [FlashDrop API](https://github.com/moja-utoma/flashdrop-api) — a limited-inventory flash-sale platform.

## Tech stack

- Angular (latest LTS), standalone components, Signals
- RxJS for live stock updates
- Tailwind
- HTTP interceptors for auth + error handling

## Getting started

```bash
git clone https://github.com/yourname/flashdrop-web.git
cd flashdrop-web
npm install
npm start
```

Requires [flashdrop-api](#) running locally (default expected at `https://localhost:5001`, configurable in `src/environments/environment.ts`).

## Key screens

- Sales list (live/upcoming/ended)
- Sale detail with live stock counter + reserve flow
- Reservation checkout with expiry countdown
- Order history
- Admin dashboard (sale management, live analytics)

## Project status

Tracked on the [FlashDrop project board](#).

## Running tests

```bash
npm test
```
