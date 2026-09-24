# Rudra's Day

A calm, private, offline daily log for your little one. One file, no account, no cloud, no ads. It runs on your phone and keeps everything on your device.

## What it is

Rudra's Day is a single `index.html` you can host for free and add to your iPhone or Android home screen. It helps you record the small things through the day (feeds, meals, sleep, nappies, symptoms, medicines, supplements, growth) so that when the pediatrician asks, you have accurate answers instead of a blank.

It is built for the toddler and solids stage, not just newborn feed-sleep-diaper tracking, and it is India-aware (metric by default, WHO growth standards, Indian foods understood in the food-group read).

## Features

- Fast daily logging with meals, snacks, water, feeds (breastfeed, formula, expressed, cow milk), sleep (day and night with duration), nappies, poop, symptoms with temperature, medicines, supplements, and more.
- Pick your own buttons. Every category is available; turn off what you do not use to keep the screen simple.
- Photos on any entry (food, nappy, rash) stored on the device, never in your gallery.
- Growth with WHO percentile charts (the reference Indian pediatricians use for under-5s).
- Insights: at-a-glance daily counts, a day/night sleep summary, and a food-group read.
- Ask: private questions answered from your own log (average sleep, feeds per day, when you started iron, last fever) plus a one-tap Doctor recap.
- Export a full backup (JSON, includes photos), a CSV of every entry, or a printable PDF report. Save photos to Files as a ZIP.
- Works fully offline. Light and dark mode follow your phone.

## Privacy

Everything is stored on your device using the browser's local storage. No account, no server, no analytics, no ads. Nothing is uploaded or shared. If you host this yourself, the public repository contains only the app code, never your logs.

## Install

**iPhone (Safari):** open the site, tap the Share button, then Add to Home Screen. It opens full screen.

**Android (Chrome):** open the site and tap Install when Chrome offers it, or use the menu and choose Install app / Add to Home screen.

## Host it yourself (GitHub Pages)

1. Create a free, public GitHub repository named `rudra-day`.
2. Upload `index.html` to the root of the repo and commit.
3. Open Settings, then Pages. Under Source pick Deploy from a branch, choose `main` and folder `/ (root)`, and Save.
4. After a minute your app is live at `https://<your-username>.github.io/rudra-day/`. Open it on your phone and add it to the home screen.

To update later, replace `index.html` with a newer version and commit. Reopen the app to pick up the change.

## Backups

Your log lives only on the device, and phones can occasionally clear web-app storage, so back up now and then. In Settings, Backup, tap Export backup file and save it to Files or iCloud Drive or Google Drive. The app shows a gentle reminder when it has been a while. Restore merges into whatever is already there and never deletes.

## Quick-add shortcut

Open the app straight into logging a type by adding `?log=` to the URL, for example:

```
https://<your-username>.github.io/rudra-day/?log=feed
```

Valid values include `feed`, `meal`, `snack`, `water`, `poop`, `nap`, `symptom`, `med`, `supplement`, `wake`, `bed`. On iPhone you can make a Shortcut (Open URL) or a second home-screen bookmark so one tap jumps straight to logging a feed.

## Not medical advice

Percentiles and insights are estimates worked out on your phone from your own entries, meant as a memory aid for you and your pediatrician. They are not a diagnosis. Your doctor's assessment is the authority.

## Support

Rudra's Day is free, and always will be. If it helps you and you would like to give something back, here are ways to help, from easiest to kindest:

- Star this repository on GitHub.
- Tell another parent who might find it useful.
- Leave a kind note or a bug report in the repository's Issues.
- If you would like to chip in, you can donate here: **[add your donation link]**.

No pressure at all. Using it and passing it on to another tired parent is support enough.

> Tip: in India a UPI ID or QR works well for donations. For anyone abroad, a Buy Me a Coffee or Ko-fi page is the simplest. GitHub Sponsors is another option if you prefer to keep it all on GitHub.

## License

MIT. See [LICENSE](LICENSE). Copyright (c) 2026 Aanchal Agarwal.
