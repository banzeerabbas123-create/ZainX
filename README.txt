# The Learning Academy Gilgit — Sports Management Site

A responsive, multi-section sports management website built with HTML, CSS and vanilla JavaScript.

## Included
- Responsive desktop, laptop, tablet and mobile layout
- Dashboard, teams, players, rankings, points table, match centre, past results, notice board, CSV export and developers sections
- Admin login and admin workspace
- Create, edit and delete teams, players, matches and notices
- Match score entry and automatic league points: win = 3, draw = 1, loss = 0
- Optional manual point adjustments
- CSV export of player directory
- Dark/light theme toggle
- Search and filtering
- Local browser storage so records persist on the same browser/device
- Animated hover effects including the sliding underline on navigation/buttons

## Run
1. Extract the ZIP file.
2. Open `index.html` in a modern browser.
3. For the best experience, use a local web server or static hosting. No build step is required.

## Admin access
Password: `Tla@12345`

## Important deployment note
This is a front-end starter build. Data is stored in that browser's `localStorage`; it is not shared automatically between devices or users. The admin password is visible in the JavaScript source and is **not secure for a public production website**. Before public deployment or real multi-user use, connect a backend/database and server-side authentication (for example, Firebase/Supabase or a custom API), add role-based permissions, and set up backups. No external API or live sports feed is included, so "live" match status is managed by an authorised admin rather than a real-time sports data provider.
