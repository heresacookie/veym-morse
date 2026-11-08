# VEYM Morse: home practice app

A free app that runs in a phone's browser and can be added to the home screen. It works offline after the first visit. Daily missions, a streak, scripture badges, the tree, quizzes, a speed trainer, and the whistle signals.

## Put it online (GitHub Pages, about 10 minutes)

1. Make a free account at github.com. Create a new **public** repository named `veym-morse`.
2. Click **Add file > Upload files**. Drag in everything inside this folder: `index.html`, `config.js`, `manifest.webmanifest`, `sw.js`, and the `icons` folder. Click **Commit changes**.
3. Go to **Settings > Pages**. Under Build and deployment choose **Deploy from a branch**, pick `main` and `/ (root)`, and click **Save**.
4. Wait one or two minutes. Your link is `https://YOURNAME.github.io/veym-morse/`.
5. Turn the link into a QR code (any free QR generator) and put it on a slide and a handout.

## Personalize it (no coding)

Open `config.js` on GitHub, click the pencil, type your chapter name, motto, and this week's goal between the quotes, and commit. Phones pick it up the next time they open the app online.

## Update it later

When you replace `index.html`, also open `sw.js` and change `veym-morse-v6` to `veym-morse-v7` (then v3, and so on). That tells phones to download the new copy.

## What kids do

- **iPhone (Safari):** Share, then Add to Home Screen.
- **Android (Chrome):** menu, then Install app.
- Open it once with Wi-Fi or data. After that it works offline.

## Privacy

Streaks, names, and badges stay on each phone. The app sends nothing to any server. Because the repository is public, do not upload rosters or photos to it.

## Check before using

Verse references were written from memory. Check each against your approved Catholic Bible translation.
