# MealBoard

<p align="center"><img src="assets/readme-banner.svg" alt="MealBoard animated banner" width="100%"></p>

A simple weekly meal planner that turns meal ingredients into a consolidated grocery list.

## Features
- Plan meals for all seven days
- Add comma-separated ingredients for each meal
- Automatically combine repeated ingredient names
- Copy or export a grocery list as a text file
- JSON backup and restore
- Local browser storage; no account, server, or external dependency
- Responsive interface

## Run it
1. Download **Code → Download ZIP** and extract the folder.
2. Open `index.html` in a modern browser.
3. Add meals and ingredients. Your plan is saved in this browser.

Optional local server: run `python -m http.server 8000`, then visit `http://localhost:8000`.

## Data & privacy
Your plan is stored in local browser storage. Clearing browser data may remove it, so export a JSON backup when needed. Grocery quantities are not inferred; repeated ingredient names are counted across meals.

## License
MIT — see [LICENSE](LICENSE).
