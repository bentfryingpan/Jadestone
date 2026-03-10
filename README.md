# Jadestone
Jadestone is a rating/informative application for Destiny 2 Gambit players. The application analyzes gambit statistics to assess player performance in detail and provides historical data to identify trends and areas for improvement.
Special thanks to Dredgen Despair, Tricky, Aspect, Wardies, Scielle, and Leinth for giving feedback and testing alpha builds of Jadestone!
Welcome to Jadestone 

Note on Antivirus Warnings: Jadestone is a compiled Python application (via PyInstaller). Because it is an independent, open-source project without an expensive Microsoft Publisher Certificate, Windows Defender or your browser will likely flag it as "Suspicious" or "Unrecognized." This is a false positive. To use the app, click "More Info" -> "Run Anyway" when prompted by Windows SmartScreen.

Here is your complete guide to mastering the Jadestone dashboard.

Getting Started

1. The Initial Sync

When you first open the app, it will silently download and optimize the Destiny 2 Manifest Database in the background. Once the bottom left status bar says "System Ready", you are good to go!

2. Fetching Your History

Enter your Bungie Name in the Your Name box (e.g., Guardian#1234).

(Optional) Adjust the Fetch Limit. By default, it pulls up to 1000 games to build your career profile, but you can set this lower for a faster sync.

Click Sync Profile. Jadestone will securely download your match history, calculate your EGO Ratings, and save everything to your local, private database.

The Main Dashboard

Once your data is loaded, the dashboard comes alive.

Dynamic Stat Cards (Top Middle)

You will see 5 large stat blocks at the top of the screen.

Customizable and Interactive Stat Boxes: Click the title of any card (e.g., "Average Score") to change what metric it displays. You can track your Highest K/D, Most Motes Denied, Total Primeval Damage, and more. Click on the actual number inside any of these cards! The app will instantly jump to the specific match where you achieved that stat, highlighting it in the table and loading its exact details.

The History Table (Bottom Left)

This table displays your loaded matches chronologically.

Click any row to load that match's detailed data into the right-side panels.

Use the Filter Stack Size buttons at the top right to instantly filter this table (and all your graphs) to show only Solo games, 4-Stack games, or your Saved Favorites.

The Analytics Tabs (Bottom Right)

When you click a match in the History Table, these tabs break down exactly what happened.

Trend & Efficiency (PEM)

Trend: Visualizes your raw EGO Score over time.

Efficiency: Tracks your Performance Efficiency Multiplier (PEM). This multiplier rewards you for banking safely and maintaining a high K/D, and actively penalizes you for losing motes or dying frequently.

Breakdown

Breaks your overall rating down into four core pillars:

PvE: Add clear and Primeval damage.

PvP: Invading and Invader shutdown.

Banking: Motes deposited and denied.

Medals: Bonus points for high-tier plays (Army of One, Half-Banked, etc.).

Match Details

It shows your exact stats, your equipped exotic armor for that was likely equipped, and the complete lobby roster sorted by Jadestone Rating. (JAdestone cannot see your exotic armor from matches; it simply pulls the current one you have equipped)

It also tells you your Team Role (e.g., if you were a Hard Carry, a Solid Contributor, or if you were Carried by your team).

Save to Favorites: Click this button at the top right of the Match tab to permanently save this game to your local database so it never gets wiped!

Alignment

A scatter plot that analyzes your playstyle over the selected matches to determine your dominant Gambit role: Reaper, Invader, Collector, or Sentry.

Career (Local)

Every time you sync, Jadestone saves the matches to a tiny database on your computer to build a massive lifetime profile.

Map Stats: See which maps yield your highest win rates and average scores.

Weapon Synergy: Tracks your win rates and average ratings based on the top weapons you had equipped.

Teammates & Rivals: Jadestone remembers everyone you play with. It tracks your encounters to crown your Best Teammate and your ultimate Nemesis.

Double-click any player's name in the Teammates & Rivals list to instantly set them as a comparison target and fetch their match history!

Receipts

Want to brag about a specific game?

Select a game from the History Table.

Go to the Receipts tab.

Toggle the exact metrics you want to show off (Kills, Motes, Damage, Efficiency, K/D, Loadout).

Click Export PNG to instantly generate a sleek, high-quality image of your stat card, ready to drop into Discord or Twitter.

Advanced Tools

Live Tracker: Check the "Live Tracker" box at the top right while you play. Jadestone will automatically fetch your newest matches every 5 minutes and update your dashboard in real-time.

Compare Vs: Enter a friend's (or rival's) Bungie Name in the purple box at the top left. Jadestone will fetch both of your histories and overlay your data on all the graphs so you can see who the superior Gambit player really is.

Fetch Specific Game: Have an old match URL from DestinyTracker? Paste it into the blue box and click "Fetch Specific Game" to run the Jadestone algorithm on it instantly.

Export CSV: Click the blue button at the top right to dump your current view into a spreadsheet for your own custom data crunching.
