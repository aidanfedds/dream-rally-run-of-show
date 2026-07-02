# Dream Rally 2026 — Production Schedule

Interactive production planner for the **Okanagan Dream Rally 2026** (August Luxury Motorcars).
Single-file app: `index.html`. Podcast production Jul 22–24, rally day Jul 25. Times Pacific.

## What it does
- Month calendar (July 2026) with each day's blocks shown as chips
- Clean hour-by-hour **day board** — click a day to open it, **double-click a time** or hit **+ Add block** to schedule
- Add / edit / delete blocks: title, day, track (Podcast / Rally / Logistics), start–end, guest, location, crew, gear, notes, status (Locked / Hold / Tentative)
- Auto-built **Podcast Line-Up**, live **countdown** to rally roll-out, and a **conflict detector**
- Auto-saves to the browser; **Export / Import** JSON to move the schedule between people

## Status
Private snapshot / backup of the app. Only the Reklaws blocks are seeded; everything else is filled in live.

### To make it a shared, auto-saving link (pending decision)
- **GitHub auto-sync** — enable GitHub Pages + a browser-side commit-on-save (token stored only in the editor's browser), or
- **Live shared database** — point the app at a free Supabase table so the whole team edits in real time.

Built for Matt August by Aidan Feddersen.
