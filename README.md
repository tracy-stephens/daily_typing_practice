# Daily Typing Practice

Short, time-boxed touch-typing practice you can run every day in a browser.

## Use

Open `index.html` in Chrome, or use the GitHub Pages URL after Pages is enabled:

`https://tracy-stephens.github.io/daily_typing_practice/`

- Default session length is 2 minutes.
- Change the minutes before pressing Start.
- Press `Command+Enter` on macOS to start or end a session.
- Type the practice paragraph until time runs out.
- Use `Save & End` to save before the timer finishes.
- A random paragraph is selected each session.
- Use `New paragraph` to skip before starting.
- Use the keyboard diagram at the top to keep fingers in the right zones.

## Tracking

Each ended session is saved in browser `localStorage`. The history table shows daily sessions, best WPM, average WPM, average accuracy, total minutes, and errors.

If the page closes or reloads during a session, the active session is recovered and saved the next time the app opens.

Practice text lives in `paragraphs.js`.

## GitHub Pages

To turn on the permanent URL:

1. Open repo Settings.
2. Go to Pages.
3. Set Source to `Deploy from a branch`.
4. Select branch `main` and folder `/ (root)`.
5. Save.
