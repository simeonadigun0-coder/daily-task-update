# Daily Task Update Tool

A lightweight standup tracker for teams — works on laptop and phone.

## Features
- Team member login screen
- Submit daily task updates with progress, blockers, and next steps
- **Log & Setup tabs visible to Simeon only**
- Optional Google Sheets sync
- Export to CSV

---

## Deploy to Vercel (one-time setup)

### Step 1 — Push to GitHub
1. Go to [github.com](https://github.com) → **New repository**
2. Name it e.g. `daily-task-update`
3. Keep it **Private** (recommended)
4. Click **Create repository**
5. Upload these two files: `index.html` and `vercel.json`
   - Click **Add file → Upload files** and drag both in
   - Commit changes

### Step 2 — Deploy on Vercel
1. Go to [vercel.com](https://vercel.com) → **Sign up / Log in with GitHub**
2. Click **Add New → Project**
3. Find and **Import** your `daily-task-update` repo
4. Leave all settings as default — click **Deploy**
5. In ~30 seconds you'll get a live URL like `https://daily-task-update.vercel.app`

### Step 3 — Share the link
Send the Vercel URL to your team. Works on any browser, laptop or phone.

---

## Admin notes
- **Log** and **Setup** tabs are only visible when logged in as **Simeon**
- All other team members only see the Submit Update form
- Data is stored in the browser's localStorage per device
- To sync across devices, connect Google Sheets in the Setup tab (Simeon only)

---

## Updating the app
Any time you push a change to GitHub, Vercel auto-redeploys within ~30 seconds.
