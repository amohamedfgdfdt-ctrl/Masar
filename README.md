# Masar (مَسَار)

A personal productivity web app in Arabic (RTL) that brings daily tasks, prayer times, notes, and adhkar into one clean interface.

🔗 **Live demo:** https://amohamedfgdfdt-ctrl.github.io/Masar/

## Features
- **Goal focus:** keep your main goal front and center on the home screen.
- **Tasks and subtasks:** daily schedule, a completion progress ring, and undo on delete.
- **Weekly planner:** plan your week at a glance.
- **Prayer times:** live countdown to the next prayer, with location-based timings.
- **Notifications:** optional prayer and task reminders; tapping a reminder opens the app.
- **Adhkar:** a daily remembrance section.
- **Notes:** quick personal notes.
- **Statistics:** track your progress over time.
- **Privacy-first:** data is stored locally in your browser (`localStorage`), with no account required.

## Tech Stack
- HTML, CSS, and vanilla JavaScript (single-file app)
- Service Worker (`sw.js`) for notification handling
- [Aladhan API](https://aladhan.com/prayer-times-api) for prayer times
- Google Fonts (Cairo, Amiri, Aref Ruqaa)
- Hosted on GitHub Pages

## Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/amohamedfgdfdt-ctrl/Masar.git
   ```
2. Serve the folder with any static server, for example:
   ```bash
   npx serve
   ```
3. Open `http://localhost:3000` in your browser.

## Author
**Idris** · [GitHub](https://github.com/amohamedfgdfdt-ctrl)
