# FitTrack Pro — Advanced Workout & Performance Tracker

A responsive, browser-based fitness tracking dashboard built with HTML, CSS and vanilla JavaScript.

## Run in Visual Studio Code
1. Extract `FitTrack_Pro_VSCode.zip`.
2. Open the extracted `fittrack_pro` folder in Visual Studio Code.
3. Open `index.html` in your browser, or use the VS Code **Live Server** extension and select **Open with Live Server**.
4. Start logging workouts.

No Node.js, database, API key or build process is required.

## Features
- Dashboard with workout count, weekly sessions, total lifting volume and personal records.
- Workout logging with date, type, muscle group, exercise, sets, reps, weight, duration, RPE and notes.
- Search, filter, sort, edit and delete workout records.
- Progress charts for weekly volume and exercise performance.
- Personal record tracking.
- Rule-based smart insights for consistency, muscle balance and stalled loads.
- Training calendar with daily workout details.
- Body-weight history and goal tracking.
- Rest timer.
- Dark/light appearance.
- JSON backup export and import.
- Browser localStorage persistence.

## Data storage and privacy
This version stores data in the current browser using `localStorage`. Records do not automatically sync between browsers or devices. Use **Backup / restore** to export a JSON backup and import it on another device. Clearing browser data can remove locally stored records.

## Recommendation logic
The Smart Insights section uses transparent, rule-based checks against the records entered by the user. It is not connected to a medical professional or an external AI service, and it does not diagnose conditions. Suggestions should be treated as general training prompts.

## Project structure
- `index.html` — page structure and components
- `styles.css` — layout, responsive styling and themes
- `app.js` — workout records, charts, insights, calendar, timer and backup logic

## Suggested future upgrades
- User accounts and cloud database (e.g. Supabase/Firebase)
- Real authentication and multi-device synchronization
- Exercise media and guided workout templates
- Nutrition and hydration logging
- More advanced analytics and downloadable PDF reports
