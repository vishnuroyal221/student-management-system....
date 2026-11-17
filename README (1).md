# Sterling College – Student Management System

A classic, navy-and-royal-blue Student Management System that runs entirely in the browser (HTML, CSS and JavaScript, no build step).

## Features
- Dashboard with statistics, charts, recent registrations, exams and announcements
- Students, teachers, classes, departments, courses, subjects, exams, results, fees, timetable, library and notices: add, edit, delete, search, filter, sort, paginate, CSV export and print
- Attendance marking with percentages and CSV report
- Fee receipts and printable report cards
- Reports, light/dark theme and settings

## Data
Sample data is stored in the browser's `localStorage`. Use **Settings → Reset Data** to restore it.

## Publish on GitHub Pages
1. Create a new repository on GitHub.
2. Upload `index.html`, `README.md` and `.nojekyll`.
3. Go to **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Your site will be live at `https://<your-username>.github.io/<repository-name>/`.

## Notes
This is a front-end demo with no backend or database. Charts load Chart.js from a CDN, so an internet connection is needed.
