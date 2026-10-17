# Arc 66

A personal 66-day habit program: daily quests, XP and levels, five stats, streaks, Hard Mode, loot, monthly ranks, achievements, and seven tools (focus timer, meditation, journal, workout tracker, calorie tracker, reading log, phone-down timer).

It's a plain web app with no server and no account. Everything is stored on your phone, and it works offline once it has loaded.

## Put it online with GitHub Pages

1. Create a new **public** repository on github.com named `arc66`. Leave it empty, with no README.
2. Upload these files, keeping the `icons` folder.
3. In the repository, open **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, then branch `main` and folder `/ (root)`. Save.
4. After a minute the app is live at `https://<your-username>.github.io/arc66/`.

## Install it on your iPhone

1. Open that address in **Safari**.
2. Tap the **Share** button, then **Add to Home Screen**, then **Add**.
3. Open Arc 66 from the home screen. It runs full-screen and works offline.

## Your data

- Everything lives in this app's storage on your phone. Nothing is sent anywhere.
- Use **Program → Export backup** every week or two, and always before deleting the app. **Import backup** restores it, even on a new phone.
- Data saved in Safari and data saved in the home-screen app are separate on iOS, so always open Arc 66 from the home-screen icon.

## Updating the app

After you change `index.html`, bump `VERSION` in `sw.js` (for example to `arc66-v2`) so phones download the new version. It shows up the next time you open the app.
