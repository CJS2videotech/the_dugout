# The Dugout - 2026 Season Tracker ⚾

A custom, stylized Cubs & Brewers live baseball tracker featuring native MLB API telemetry, dynamic team-based viewer themes, a responsive Emoji Reaction Engine, and a comprehensive Head-to-Head Season Trophy Math Pipeline!

## Core Features

- **Dynamic Theme Architecture**: Clicking the top Avatar instantly transforms the entire application's color tokens, backgrounds, and layout aesthetics between a deep "Cubs Blue / Crimson" theme for CJ and a vibrant "Brewers Gold / Navy" theme for Andrea.
- **Season-Long Leaderboard & Trophy Cabinet**: The backend engine natively aggregates historical MLB linescores spanning from Opening Day. It identifies matches where both teams played, totals all Regular Season Runs and Hits, automatically adjudicates Daily Trophy match-ups using Runs as the ultimate tie-breaker, and visualizes a massive season-to-date Head-to-Head trophy cabinet.
- **Yesterday's Recap Toggle**: One click seamlessly pulls the MLB data backward 24 hours to display yesterday's complete box scores without refreshing the page. 
- **Multimedia Reaction Engine**: A high-performance, native "emoji rainfall" engine. Clicking dynamic reaction buttons (Winning, Losing, Home Runs, Bad Call) visually floods the DOM with beautifully animated cascading emojis representing the active sentiment.
- **Responsive Dynamic Banners**: Includes proportional native GIF integration bridging the layout columns, instantly swapping team-contextual graphics based on the active viewer state.

## Asset Customization

To completely remap the personalized visuals, simply replace the following files located directly inside your `/assets/` directory (ensure you keep the exact file names and extensions):

*   `andrea.jpg` & `cj.jpg` *(The dynamic circle avatar toggles)*
*   `cubs-banner.gif` & `brewers-banner.gif` *(The layout roster banners)*
*   `Cubs field.jpg` & `Brewers field.jpg` *(Desktop landscape backgrounds)*
*   `Cubs field mobile.jpg` & `Brewers field mobile.jpg` *(Mobile portrait backgrounds—the engine detects your phone format and swaps to these automatically!)*
*   `andrea and cj button.jpg` *(The application favicon/bookmark icon)*

## GitHub Pages Deployment

To put your tracker live natively on the web for your phone's home screen:
1. Go to github.com and create a new repository (e.g. `the-dugout`).
2. Drag and drop **all files** inside this folder (*including the `assets` folder*) directly into your new repository.
3. Commit the changes.
4. Go to the repository **Settings** tab.
5. Click **Pages** on the left sidebar.
6. Under Build and deployment, make sure Source is set to **Deploy from a branch**.
7. Set the branch to **main**, keep the folder as **/ (root)**, and click **Save**.
8. In a few minutes, GitHub will give you a live URL to open your app natively anywhere!
