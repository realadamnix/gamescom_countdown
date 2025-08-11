# 🎮 Start of Gamescom Trip Countdown

A live HTML5 Canvas countdown to **12:45 AM (Europe/Dublin) on August 19th, 2025** with a game-style design and Gamescom-inspired logo.

## 📂 File Structure
gamescom_countdown/
│
├── index.html # Main countdown file (open this in a browser)
└── README.md # This file

shell
Copy
Edit

## 🌐 Hosting
To make the countdown accessible at:
https://adamnix.ie/gamescom_countdown/
1. Rename the HTML file to **`index.html`** (already done here).
2. Upload it to the `/gamescom_countdown` folder in your hosting setup.
3. Your web server will automatically load `index.html` when visiting the folder URL.

## 💻 Local Viewing
You can also view it locally without internet:
1. Download the folder to your computer.
2. Double-click **index.html** to open it in your web browser.

## ✨ Features
- Full-screen HTML5 Canvas background with animated particles and grid
- Live countdown with **days, hours, minutes, seconds**
- Gamescom-inspired SVG logo
- Works fully offline

## 🛠 Customizing the Target Time
If you want to change the target date/time:
1. Open `index.html` in a text editor.
2. Search for:
   ```javascript
   const targetUTC = Date.UTC(2025, 7, 18, 23, 45, 0);
