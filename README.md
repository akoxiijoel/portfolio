# Joel — Motion Design & Video Editing Portfolio

60-second motion design & talking-head videos for AI, SaaS, and app
startups and coaches. This is the full site: `index.html` + `videos/`
(10 web-compressed samples). No build step, no dependencies.

## Get your live GitHub link (about 2 minutes)

### Option A — no coding, all in the browser
1. Go to https://github.com/new (create a free account if needed).
2. Repository name: `portfolio` (or anything). Set it to **Public**. Click **Create repository**.
3. On the new repo page, click **uploading an existing file**.
4. Drag `index.html` AND the whole `videos` folder into the upload box.
   (If your browser won't take the folder, upload index.html first,
   then click **Add file → Upload files**, type `videos/` in front of
   the filename area by dragging the videos in — GitHub keeps the folder.)
5. Click **Commit changes** and wait for the upload to finish.
6. Go to **Settings → Pages** (left sidebar).
7. Under "Branch", pick `main`, folder `/ (root)`, click **Save**.
8. Wait ~1 minute. Your site is live at:
   `https://YOUR-USERNAME.github.io/portfolio/`

### Option B — command line (if you have git installed)
```
cd path/to/this/folder
git init
git add .
git commit -m "Launch portfolio"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/portfolio.git
git push -u origin main
```
Then do steps 6–8 above to turn on Pages.

## Before you launch
- Replace the `#` in the "Book a call" button with your Calendly/booking link.
- Replace `hello@example.com` with your real email.
- To reorder videos: move a `<figure class="card">` line in index.html.
- To swap a video: drop the new .mp4 into `videos/` and update the `src`.

## What's inside
- Swipeable video decks (touch swipe, mouse drag, arrows, keyboard)
- Videos auto-pause when swiped away; only one plays at a time
- Scroll-linked timecode bar (the page "plays" like a 60s video)
- Fonts: Montserrat ExtraBold / SF Pro / Apple Garamond (EB Garamond fallback)
