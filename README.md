# ChainAcademy_

# ChainAcademy – Web3 Learning Progress Engine

ChainAcademy is a React + Vite learning app that teaches Web3 through lessons and quizzes. It tracks learning progress and generates a printable certificate with a SHA-256 content hash.

## Features
- 4 Web3 learning modules with sequential lesson unlocking
- Quizzes with a 75% pass mark, retries, and score history
- Progress saved using `localStorage`
- Course completion calculated from actual lesson and quiz states
- Printable certificate with learner name, completion time, and SHA-256 hash
- Simple, responsive white theme

## Project Pipeline

`Course Data → Progress Rules → Save Progress → React UI → Certificate`

- `src/data/course.js` – Modules, lessons, and quiz questions
- `src/logic/progress.js` – Unlocking rules, quiz grading, and progress calculation
- `src/logic/storage.js` – Saves and loads progress
- `src/logic/certificate.js` – Certificate eligibility and SHA-256 hash
- `src/components.jsx` and `src/App.jsx` – UI components and application state
- `src/styles.css` – Layout and theme

## Run Locally

Requires Node.js 18 or newer.

```bash
npm install
npm run dev
```

Open the local URL shown in the terminal.

## Test and Build

```bash
npm test
npm run build
npm run preview
```

## Deployment

Push the project to GitHub and import the repository into [Vercel](https://vercel.com/new).

Build command: `npm run build`

Output directory: `dist`

## AI Assistance

AI assistance was used for minor styling and UI-related improvements in `src/styles.css` and `src/App.jsx`. I reviewed the changes and am responsible for understanding the code.
