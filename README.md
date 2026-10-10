# PulseCare — React-only frontend

This version uses React + JavaScript (JSX), Vite, and plain CSS. It does not use TypeScript, Redux, React Router, Tailwind, or third-party icon/chart libraries.

## Run locally
1. Extract the ZIP.
2. Open the `PulseCare-React-Only` folder in VS Code — the folder containing `package.json`.
3. Open a terminal in that folder.
4. Run `npm install`
5. Run `npm run dev`
6. Open the localhost URL printed by Vite, usually `http://localhost:5173`.

## Screens
Overview, Patients (search/filter/add demo patient), Appointments, Alerts (mark reviewed), Clinical forms (local preview), Audit log, and Settings.

## Stack
- React + React DOM
- JavaScript / JSX
- Vite for the development server and build
- Plain CSS

React is the UI library; Vite is still needed as the local dev server/build tool. Patient details are fictional mock data. There is no backend, database, secure authentication, or live monitor connection. State resets after a browser refresh. Do not use this prototype for real clinical decisions.
