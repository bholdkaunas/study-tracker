# Study Tracker

A stopwatch and GitHub-style activity graph for your study time. One HTML file, no account, no server: everything is saved in your browser.

## Features

- **Stopwatch:** pick a subject, start, pause, resume, then stop & save. It keeps running if you close or reload the tab.
- **Activity graph:** a contribution-style heatmap of the last year. Hover a day to see how long you studied and on what. Filter it by subject.
- **Stats:** today, this week, total, % of days studied, current and longest streak, best day, active days.
- **By subject and last 8 weeks:** where your time goes, and how it's trending.
- **Editable sessions:** fix the date, subject or minutes of any session, delete it, or add one you forgot to time.
- **Your own subjects:** add, remove and recolor them. Removing a subject keeps its past sessions in your totals.
- **Backups:** export everything as JSON (and import it on another device), or export your sessions as CSV for a spreadsheet.
- Light and dark mode, works on phones.

## Use it

Open `index.html` in a browser, or host it with GitHub Pages:

1. Go to the repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
3. After a minute the site is live at `https://<your-username>.github.io/<repo-name>/`.

## Where your data lives

Sessions and subjects are stored in your browser's `localStorage`, on your device only. Nothing is sent anywhere. That also means:

- Clearing your browser's site data deletes your sessions, so **export a backup now and then**.
- Each browser and device has its own data. Use **Export backup** and **Import backup** to move it.

## Customize

The default subjects are at the top of the script in `index.html` (`DEFAULT_SUBJECTS`). Colors come from a small palette (`blue`, `purple`, `green`, `orange`, `pink`, `yellow`, `gray`, `red`, `teal`) defined as CSS variables, with separate light and dark values.

## License

MIT
