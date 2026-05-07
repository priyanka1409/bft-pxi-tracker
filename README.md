# BFT PXI Tracker

A beautiful, mobile-optimized calendar app to track your monthly BFT workout scores and plan ahead.

## Features

✅ **Calendar View** — Click any date to log a PXI score or plan a future session  
✅ **Dual Tracking** — See logged workouts (green) vs planned sessions (yellow) at a glance  
✅ **Smart Stats** — Auto-calculates remaining PXI, sessions completed, and average PXI needed  
✅ **Persistent Storage** — Your data saves automatically with `localStorage`  
✅ **Mobile-First Design** — Optimized for iPhone + Safari  
✅ **Add to Home Screen** — Feels like a native app on your phone  
✅ **No Login Required** — All data stays on your device  
✅ **Offline Ready** — Works without internet (for reading, at least)

## How to Use

### Log a Workout
1. Click any date on the calendar
2. Tap "Log PXI"
3. Enter your PXI score
4. Save — it immediately updates your progress

### Plan a Session
1. Click a future date
2. Tap "Plan Session"
3. Save — marks it as planned (no score yet)
4. Later, click the same date and tap "Log PXI" to convert it to a logged workout

### Edit or Delete
- Click any logged or planned date
- Choose "Edit PXI" or "Delete"

### View Progress
- **Total PXI** — Progress ring shows how close you are to 1800
- **Remaining** — How many points you still need
- **Sessions** — Green = completed, Yellow = planned
- **Avg PXI Needed** — Based on your remaining planned sessions

## Installation

### Option 1: Use the Live Version
Just visit: `https://priyanka1409.github.io/bft-pxi-tracker/`

### Option 2: Add to iPhone Home Screen
1. Open the link in Safari
2. Tap the Share button
3. Tap "Add to Home Screen"
4. Name it "BFT Tracker"
5. Tap "Add"

Now it appears as an app icon on your home screen!

## How It Works

- **React** — Powers the interactive UI
- **Babel** — Compiles JSX in the browser
- **localStorage** — Saves your data automatically between sessions
- **Pure HTML/CSS/JS** — No build step needed, works anywhere

## Data Storage

Your workout data is stored in your browser's `localStorage` — it's private, on-device, and persists forever (or until you clear browser data).

## Customization

Want to change the target PXI (currently 1800)? Edit this line in `index.html`:
```javascript
const TARGET_PXI = 1800;
```

Want to change colors? Look for the hex codes like `#ff6b35` (orange) and `#22c55e` (green).

## Browser Support

- ✅ Safari (iOS 12+)
- ✅ Chrome
- ✅ Firefox
- ✅ Edge

## Troubleshooting

**Data not saving?**
- Make sure you're not in Private/Incognito mode (disables `localStorage`)
- Try clearing browser cache and refreshing
- Check that you have storage space on your device

**App not loading on phone?**
- Make sure GitHub Pages is enabled in your repo Settings
- Double-check the URL (should be `https://priyanka1409.github.io/bft-pxi-tracker/`)
- Try a hard refresh (Safari: swipe down from top, pull to refresh)

## License

Open source, do whatever you want with it. 🏋️

---

**Built for crushing BFT goals.** 💪
