# TIMELOG ⏱

A local, zero-dependency time tracker inspired by Clockify. Runs entirely in your browser — no server, no sign-up, no internet required after page load.

## Features

- **Live Timer** — Start/stop tracking with one click
- **Manual Entry** — Log time blocks with custom start/end times
- **Projects** — Create color-coded projects and assign entries to them
- **Stats** — Today / This Week / This Month / All Time totals
- **Filters** — Filter entries by project or date
- **CSV Export** — Export all entries to a spreadsheet-ready `.csv`
- **Persistent** — All data saved in browser `localStorage` (survives page refresh)

## Usage

1. Clone or download this repo
2. Open `index.html` in any modern browser
3. Start tracking!

```bash
git clone https://github.com/YOUR_USERNAME/timelog.git
cd timelog
open index.html   # macOS
# or just double-click index.html on Windows/Linux
```

No build step. No npm install. No dependencies.

## Data Storage

All data is stored in your browser's `localStorage` under the key `timelog_state`. It stays on your machine and never leaves.

To back up your data, use the **↓ CSV** export button.

## Customization

Everything is in a single `index.html` file:
- **Colors**: Edit the CSS variables at the top of the `<style>` block (`:root { ... }`)
- **Default Projects**: Edit the `projects` array in the `state` initialization in the `<script>` block
- **Fonts**: Swap out the Google Fonts import at the top

## License

MIT — do whatever you want with it.
