💰 Intelligent Budget Tracker
A simple, powerful personal finance tool that helps you split your income, track your spending, and manage your money across different buckets — all running in your browser with no internet required after the first load.
---
✨ Features
Automatic Income Splitting — Enter any amount and it splits automatically into your three buckets based on your chosen percentages
Three Money Buckets — Spending Fund, Savings & Invest, and Needs — each tracked separately
Physical Wallet Tracking — Tracks where your money actually is (MoMo/Bank or Physical Cash)
Deduction with Purpose — Every deduction requires a description (e.g. Bought food, Transport) so you always know where your money went
Date & Time Stamped Transactions — Every entry shows the exact date and time it was recorded
Transaction Log — Full history of every split, addition and deduction
Backup & Restore — Export your data as a `.json` file to Google Drive or anywhere, and restore it anytime
Auto Update Alert — If a new version of the app is available, a banner appears notifying you to update
Custom Split Rules — Change your percentage split anytime (default is 50/30/20)
Works Offline — All data is saved in your browser automatically
---
🚀 How to Use
Opening the App
Download the `index.html` file
Open it in any browser (Chrome recommended)
Or visit the hosted link: `https://yourusername.github.io/budget-app`
Splitting Income
Enter the amount you received in the Amount (GHS) field
Select whether it came via MoMo/Bank or Physical Cash
Click Split Money — it automatically divides into your three buckets
Adding or Deducting from a Bucket
Click Add or Deduct on any bucket card
Enter the amount
For deductions — enter a description of what you spent on (required)
Select the wallet the money came from
Click Confirm Changes
Backup Your Data
Click the Backup button in the top header
A `.json` file will download to your device
Save it to Google Drive, WhatsApp to yourself, or anywhere safe
Restoring a Backup
Click the Restore button in the top header
Select your previously saved `.json` backup file
All your data, history and settings will be restored instantly
Changing Your Split Percentages
Edit the three percentage boxes in the header (must add up to 100)
Click Update Rule
Future income splits will use the new percentages
Resetting Everything
Click Reset All Balances at the bottom of the left panel
This clears all balances, history and settings permanently
---
🔔 Update System
This app has a built-in update checker. When a newer version is available:
A blue banner appears at the top of the app
Click the link in the banner to download the new version
Replace your old file with the new one
For developers / app owner:
Every time you update the app, increase the version number in the code:
```javascript
var APP_VERSION = 1.0;  // change to 1.1, 1.2 etc on each update
```
Then update the check URL to point to your hosted file:
```javascript
var VERSION_CHECK_URL = 'https://raw.githubusercontent.com/yourusername/budget-app/main/index.html';
```
---
🛠️ Tech Stack
HTML — structure
Tailwind CSS (CDN) — styling
Font Awesome (CDN) — icons
Vanilla JavaScript — all logic
localStorage — data persistence (no backend, no database)
No frameworks. No installation. No server needed. Just one HTML file.
---
📁 File Structure
```
budget-app/
│
├── index.html        ← The entire app (rename from Budget.html)
└── README.md         ← This file
```
---
🌐 Hosting on GitHub Pages
Create a new GitHub repository e.g. `budget-app`
Upload `Budget.html` and rename it `index.html`
Upload this `README.md` file
Go to Settings → Pages → Branch: main → Save
Your app will be live at: `https://yourusername.github.io/budget-app`
Share this link with anyone — they always get the latest version
---
📌 Version History
Version	Date	Changes
1.0	June 2026	Initial release — income splitting, deductions with purpose, backup/restore, update checker
---
👤 Owner
Built for personal use. Feel free to share the link with friends and family.
