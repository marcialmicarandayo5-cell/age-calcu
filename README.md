# Age & Date Calculator

A small, dependency-free web tool that works out exact ages and the time between two dates. Everything runs in your browser; no data is sent anywhere.

## Features

- **Age calculator:** exact age in years, months, and days, plus total months, weeks, days, and hours.
- **Birthday info:** the weekday you were born and a countdown to your next birthday.
- **Between two dates:** total days, weeks, weekdays (Mon–Fri), hours, and minutes.
- **Convenient:** live results as you type, works on mobile, supports dark mode.

## Usage

No install or build step. Either:

1. Download `index.html` and open it in any browser, or
2. Host it for free with **GitHub Pages**: *Settings → Pages → Deploy from branch → `main` / root*.

## How it works

- Dates are parsed as local dates, so time zones never shift your result by a day.
- Years/months/days use calendar math (borrowing days from the previous month when needed).
- A birthday on Feb 29 is celebrated on Mar 1 in non-leap years.

## Project structure

```
age-date-calculator/
├── index.html   # the whole app (HTML + CSS + JS)
├── README.md
└── LICENSE
```

## Ideas for improvement

- Add or subtract days, weeks, or months from a date.
- Show zodiac sign or Chinese zodiac year.
- Save recent calculations in `localStorage`.

## License

MIT, see [LICENSE](LICENSE).
