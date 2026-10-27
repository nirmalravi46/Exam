# NICL AO 2026 Smart Preparation Hub

Responsive, dependency-free study application for a Generalist candidate preparing from 28 October to 17 November 2026.

## Run

```bash
cd nicl-ao-smart-hub
npm test
npm start
```

Open `http://localhost:4173`.

## Implemented routes

Dashboard, 21-Day Study Plan, Study Materials, Daily Practice, Sectional Mock Tests, Full-Length Mock Tests, Results & Analytics, Mistake Notebook, Bookmarks & Revision, and Exam-Day Checklist.

## Storage

All completion, tests, mistakes, bookmarks and checklist state persist in browser `localStorage` under `niclHubV2`. No account or cloud sync is included.

## Test scope

`npm test` verifies negative marking and blank-answer behavior. Static server and JavaScript syntax are smoke-tested during packaging.

## Important limitation

The app includes 15 original sample questions. It provides functional daily, sectional and mixed diagnostic tests, but does not falsely claim a complete 100-question question bank. The official full structure is shown as a reference.
