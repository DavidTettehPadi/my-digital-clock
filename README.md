# My Digital Clock

A responsive browser-based clock dashboard with a live local time and date, an interactive stopwatch, and a scheduled alarm.

## Live Demo

[Open My Digital Clock](https://davidtettehpadi.github.io/my-digital-clock/)

## Features

- Live 24-hour clock and localized date, refreshed every second
- Stopwatch with start, pause, reset, and lap tracking
- Date-and-time alarm that validates future times
- Repeating alarm tone generated with the Web Audio API
- Responsive layout for desktop and mobile
- Reduced-motion support and visible keyboard focus styles

## Built With

- HTML5
- CSS3
- Vanilla JavaScript
- Web Audio API

No package installation or build step is required. Google Fonts are loaded from Google Fonts when an internet connection is available; system fallbacks are provided.

## Run Locally

Open `index.html` in a modern browser, or serve the project directory over HTTP:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`. Browsers may require a user interaction before alarm audio can play.

## Repository

[View the source on GitHub](https://github.com/DavidTettehPadi/my-digital-clock)