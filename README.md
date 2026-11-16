# Holiday Roulette ✈️🎰

Pick where you're flying from, a budget and a vibe, then spin the wheel to find out where you're going on holiday.

**Live:** https://invo-mwiseman.github.io/holiday-roulette/

- 93 destinations across 5 budget tiers (Shoestring → Money No Object), including theme parks (Disney, Universal, Legoland, PortAventura…), Turkey and pool & resort holidays
- 25 starting points (incl. 8 UK airports): flight time, stops, fares and all prices in your local currency
- Adults & children, meal plan (room only → all-inclusive), family-friendly filter and a "weekend away" mode
- "Know before you go": live 5-day weather, season check, time difference & landing time, live exchange rate, entry-rules link, estimated cheapest months
- Globe flight animation, scratch-off reveal in mystery mode, ambient soundscapes, trip countdown with packing list, passport book with badges
- Vibe filters (beach, city, adventure, culture, foodie, snow), with a top-up from nearby budgets if a combo is thin
- Each result shows four things to do with photos, a trip total, and a date picker with Booking.com flight and hotel searches pre-filled (airports, dates, travellers)
- Lock in a destination for an animated passport stamp (with sound effects)
- Mystery mode, no-repeat spins and saved passport stamps

It's a static site: `index.html`, photos in `img/` and `vendor/` (d3-array, d3-geo, Natural Earth land outlines), with no build step. Live weather comes from [Open-Meteo](https://open-meteo.com) and exchange rates from [ExchangeRate-API](https://www.exchangerate-api.com); both are free and need no key.

## Notes

- Prices and flight times are rough estimates, not live quotes. From the UK they're hand-checked; from other cities they're estimated from distance and airport size.
- Activity photos are openly licensed (CC0, public domain, CC BY, CC BY-SA) via [Openverse](https://openverse.org) and [Wikimedia Commons](https://commons.wikimedia.org). Each photo is credited in the app, and full source details are in `photos.json`.

## License

The app code is released under the [MIT License](LICENSE). These parts keep their own licences:

- **Photos (`img/`)**: each is openly licensed (CC0, public domain, CC BY or CC BY-SA). The author, licence and source of every photo are credited in the app and listed in `photos.json`.
- **d3-array and d3-geo (`vendor/`)**: ISC licence, see [`vendor/LICENSE-d3.txt`](vendor/LICENSE-d3.txt).
- **Land outlines (`vendor/land.js`)**: [Natural Earth](https://www.naturalearthdata.com) via world-atlas, public domain.
