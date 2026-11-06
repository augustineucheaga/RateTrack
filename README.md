# RateTrack

A clean currency converter with live exchange rates and rate-history charts. Built as a single HTML file with no dependencies.

**Live app:** https://rate-track.vercel.app/

## Features

- 150+ currencies with flag emojis
- Live rates from three free APIs, with automatic fallback, so a conversion rarely fails
- Rate history chart for any currency pair: 7, 30 or 90 days, with high, low and percentage change
- Swap button to flip the two currencies
- Quick-amount chips: 100, 500, 1K, 5K and 10K
- Mobile-first, responsive layout

## Rate sources

All free, no API key needed.

| API | Used for | Currencies |
|---|---|---|
| [fawazahmed0 Exchange API](https://github.com/fawazahmed0/exchange-api) | Live rates and history | 150+ |
| [Frankfurter](https://www.frankfurter.app) | Live rates (fallback) | 30+ major |
| [Open ER API](https://www.exchangerate-api.com/docs/free) | Live rates (fallback) | 160+ |

## Run it locally

There is nothing to build. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 3000
```

then open http://localhost:3000.

## Use it like an app

Open the live site on your phone and choose **Add to Home Screen** (Share menu in Safari, ⋮ menu in Chrome). On desktop Chrome or Edge, use the install icon in the address bar.

## Credits

Designed and built by Kidddarts (Augustine Ucheaga). Contact: augustineucheaga@gmail.com
