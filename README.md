# Days Clear

A simple tracker that shows how many days it has been since you quit something. Enter what you quit and the date, and the app displays the running day count.

## Features

- Add one or more things you have quit, each with a quit date
- Live day count for each entry
- Remove entries you no longer want to track
- Data is saved in your browser, so it persists between visits
- Quit dates cannot be set in the future

## Usage

No install or build step is needed.

1. Clone the repository:
   ```
   git clone https://github.com/kiiplagat/days-clear.git
   ```
2. Open `index.html` in any browser.

## How it works

The app is a single `index.html` file with plain HTML, CSS and JavaScript. Entries are stored in the browser's `localStorage`. Days are counted from local midnight, so the count does not shift with timezones.

## Limitations

- Data lives in one browser on one device. Clearing site data removes it.
- There is no account system or sync across devices.

## Possible improvements

- Milestone markers at 7, 30 and 90 days
- Export and import of entries
- Backend storage for syncing across devices

## License

MIT
