# 🏎️ Car Lottery Game - Setup Instructions

## What You've Got

A complete, ready-to-use car lottery game that runs entirely on GitHub Pages (FREE!).

## Files Included

1. **index.html** - The main game page
2. **admin.html** - Admin dashboard to view winners
3. **correct.html** - Page shown for correct answers
4. **wrong.html** - Page shown for wrong answers
5. **README.md** - This file

## How to Set It Up (SUPER EASY!)

### Step 1: Create a GitHub Account (if you don't have one)
1. Go to https://github.com
2. Click "Sign up"
3. Follow the steps

### Step 2: Create a New Repository
1. Click the "+" icon in top right → "New repository"
2. Name it: `car-lottery` (or anything you want)
3. Make it **Public**
4. Check "Add a README file"
5. Click "Create repository"

### Step 3: Upload Your Files
1. Click "Add file" → "Upload files"
2. Drag all 4 HTML files into the upload area
3. Scroll down and click "Commit changes"

### Step 4: Enable GitHub Pages
1. Click "Settings" (top menu)
2. Click "Pages" (left sidebar)
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait 1-2 minutes

### Step 5: Get Your URLs
Your game will be at:
```
https://YOUR-USERNAME.github.io/car-lottery/
```

For the question game flow:
- **Correct answer**: `https://YOUR-USERNAME.github.io/car-lottery/correct.html`
- **Wrong answer**: `https://YOUR-USERNAME.github.io/car-lottery/wrong.html`
- **Admin page**: `https://YOUR-USERNAME.github.io/car-lottery/admin.html`

## How to Use It

### Running a Game on Twitter

**Tweet Example:**
```
🏎️ NEW CAR LOTTERY GAME! 🏎️

Question: Is this a Mustang or an E-Type?

👉 Mustang: [link to wrong.html]
👉 E-Type: [link to correct.html]

Win amazing prizes! 🏆
```

### How It Works
1. Someone clicks the correct answer link
2. They're redirected to the game page
3. They click "Generate My Ticket"
4. They instantly see if they won
5. Winners get a unique code
6. They DM you the code to claim their prize

### Viewing Winners
1. Go to your admin page: `https://YOUR-USERNAME.github.io/car-lottery/admin.html`
2. You'll see all winners with their codes
3. Click "Export CSV" to download the list
4. Verify codes when people DM you

## Important Notes

⚠️ **Current Setup:**
- Winners are stored in the browser's localStorage
- This means data is stored on each player's device
- You can see winners when they share their codes
- For serious competitions, you'll need a backend (I can help with this later)

✅ **What Works Now:**
- Unlimited plays per person
- Automatic winner detection
- Unique winner codes
- Admin dashboard
- CSV export
- Twitter sharing
- Mobile-friendly
- Completely free

## Customization

### To Change the Twitter Handle in wrong.html:
1. Open `wrong.html`
2. Find line with `https://twitter.com/YourHandle`
3. Change `YourHandle` to your actual Twitter handle
4. Save and upload

### To Change Game Number:
1. Open `index.html`
2. Find `<h1>🏎️ Car Lottery Game #1</h1>`
3. Change `#1` to `#2`, `#3`, etc.
4. Save and upload

## Tips for Running Games

1. **Pin the grid** - Tweet the full 25-car grid image and pin it
2. **Link to it** - In game tweets, link to your pinned tweet
3. **Multiple questions** - Run several questions per game to give out more tickets
4. **Track manually** - Keep a spreadsheet of valid winner codes
5. **Set deadlines** - "Claim your prize within 24 hours!"

## Need Help?

The game is designed to be totally automatic and foolproof. Just:
1. Upload files to GitHub
2. Enable Pages
3. Share the correct/wrong answer links on Twitter
4. Check admin page for winners

That's it! No coding required from you.

## Future Upgrades (If You Want Them)

Later, I can help you add:
- Backend server to track all winners centrally
- Email notifications when someone wins
- Automatic winner verification
- Limit plays per person
- Multiple simultaneous games
- Analytics and stats

But for now, this works perfectly for small prizes and casual games!

---

**Questions?** Just ask - I'll walk you through any step!
