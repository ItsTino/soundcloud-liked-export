# SoundCloud Liked Export

Export your SoundCloud liked tracks to a CSV file containing artist name, song title, and direct links.

## What It Does

This bookmarklet extracts all your liked tracks from SoundCloud and exports them to a CSV file with the following columns:
- Artist
- Song Name
- URL

## Usage Instructions

### Step 1: Navigate to Your Likes

Go to your SoundCloud likes page:
```
https://soundcloud.com/you/likes
```

### Step 2: Switch to List View

Make sure you're viewing your likes in **list mode** (not grid mode). Click the list view icon.

### Step 3: Load All Tracks

Scroll all the way down to the bottom of the page, ensuring all your liked tracks are loaded. SoundCloud loads tracks dynamically as you scroll, so this step is important to capture all your likes.

### Step 4: Add the Bookmarklet to Your Browser

#### Chrome / Edge / Brave:
1. Show your bookmarks bar (Ctrl+Shift+B on Windows/Linux, Cmd+Shift+B on Mac)
2. Right-click on the bookmarks bar and select "Add page" or "Add bookmark"
3. Name it "Export SoundCloud Likes" (or any name you prefer)
4. In the URL field, copy and paste the entire code from `soundcloud-bookmarklet.js`
5. Save the bookmark

#### Firefox:
1. Show your bookmarks toolbar (Ctrl+Shift+B on Windows/Linux, Cmd+Shift+B on Mac)
2. Right-click on the bookmarks toolbar and select "New Bookmark"
3. Name it "Export SoundCloud Likes" (or any name you prefer)
4. In the Location field, copy and paste the entire code from `soundcloud-bookmarklet.js`
5. Save the bookmark

#### Safari:
1. Show your favorites bar (View → Show Favorites Bar)
2. Drag any link to the favorites bar, then right-click it and select "Edit Address"
3. Name it "Export SoundCloud Likes" (or any name you prefer)
4. In the address field, copy and paste the entire code from `soundcloud-bookmarklet.js`
5. Save

### Step 5: Run the Export

Once all your tracks are loaded, simply click the bookmarklet in your bookmarks bar. A CSV file named `soundcloud-likes.csv` will automatically download to your default downloads folder.

## Files

- `soundcloud-bookmarklet.js` - The minified bookmarklet code (copy this to your bookmark)
- `script-unminified.js` - Unminified source code for reference/modification

## Notes

- Make sure you're logged in to SoundCloud
- The export only includes tracks that are currently loaded on the page
- The CSV file can be opened in Excel, Google Sheets, or any text editor