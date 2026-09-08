# Big Sur Roadbook

A polished, responsive, dependency-free dashboard for planning a Big Sur camper van trip. It includes editable **example data** for a five-day coast route, itinerary, campsites, budget, packing, reservations, and calendar.

## Run locally

No installation is required.

1. Open `index.html` directly in a browser, or serve the folder with a simple local web server.
2. For example, with Node.js installed: `npx serve .`
3. Open the local address shown by the server.

## Customize it

All seeded trip data lives at the top of `app.js` in the `trip` object. Edit that object to replace destinations, dates, activities, reservations, packing items, and budget values. The app labels the displayed content as example data so it is safe to tailor before travel.

Interactive touches:

- Check packing items to update progress (current session).
- Add an expense with the Budget button (current session).
- Save a personal trip note, which is kept in your browser’s local storage.
- Use **Print trip** for a clean printable roadbook.

## Notes

The route map and forecast are illustrative. Confirm road conditions, campground requirements, reservation details, and weather close to departure.
