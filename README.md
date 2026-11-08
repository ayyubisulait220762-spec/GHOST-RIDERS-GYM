# Ghost Riders Gym

A 6-day old-school gym plan as a phone app. Every muscle (chest, back, legs, shoulders, biceps, triceps) is trained every day with one exercise, rotating through heavy, medium and pump days.

## Features

- **36 animated exercises.** A moving figure shows each lift at the right tempo, with the working muscle highlighted.
- **Muscle names.** Simple name and proper name side by side (for example *Front thigh / Quadriceps*).
- **Voice coach.** Counts down, counts every rep, then runs your rest timer with beeps.
- **Guided warm-up.** 4 minutes, timed, with voice.
- **Set tracker and rest timer.** Rest time changes with the type of day (2 min heavy, 90 s medium, 60 s pump).
- **Weight log.** Shows what you lifted last time and when to add weight.
- **Swap button.** Machine busy? Pick another exercise for the same muscle.
- **Progress.** Streak, monthly calendar, body weight chart and your best lifts.
- **4-week cycle.** Week 4 drops to 2 sets automatically for recovery.
- **Works offline** and installs on your phone like an app.
- **Trainer tips in Hinglish** for every exercise.

All data stays on your phone (browser storage). Nothing is sent anywhere.

## The plan

| | Sat | Sun | Mon | Tue | Wed | Thu |
|---|---|---|---|---|---|---|
| Legs | Back Squat (H) | Romanian Deadlift (M) | Leg Extension (P) | Smith Squat (H) | Walking Lunges (M) | Leg Press (P) |
| Chest | Incline DB Press (M) | Cable Crossover (P) | Flat Bench (H) | Decline Bench (M) | DB Flyes (P) | Chest Dips (H) |
| Back | Lat Pulldown (P) | Bent-Over Row (H) | One-Arm Row (M) | Seated Cable Row (P) | Deadlift (H) | T-Bar Row (M) |
| Shoulders | Seated DB Press (H) | Arnold Press (M) | Lateral Raise (P) | Smith Press (H) | Face Pull (M) | Rear Delt Fly (P) |
| Triceps | Diamond Push-Ups (M) | Rope Pushdown (P) | Close-Grip Bench (H) | Overhead Extension (M) | Bench Dips (P) | Skull Crushers (H) |
| Biceps | Cable Curl (P) | Barbell Curl (H) | Incline DB Curl (M) | Rope Hammer Curl (P) | Hammer Curl (H) | Concentration Curl (M) |

Friday is rest. H = Heavy 6–8 reps, M = Medium 8–12, P = Pump 12–15. 3 sets each.

## Put it online for free (GitHub Pages)

1. Create a free account at github.com.
2. Click **New repository**, name it `ghost-riders-gym`, set it to **Public**, and create it.
3. Click **uploading an existing file**. Select all 10 files in this folder at once and click **Commit changes**.
4. Go to **Settings → Pages**. Under *Branch*, choose `main` and `/ (root)`, then **Save**.
5. Wait 1–2 minutes. Your app is live at `https://YOUR-USERNAME.github.io/ghost-riders-gym/`.

## Install on your phone

- **Android (Chrome):** open the link, tap the ⋮ menu, then **Add to Home screen** or **Install app**.
- **iPhone (Safari):** open the link, tap **Share**, then **Add to Home Screen**.

It now opens full screen with its own icon and works in the gym without internet.

## Updating the app

Change the files, upload them again, and change `VERSION` in `sw.js` (for example `grg-v2`) so phones pick up the new version.

## Files

```
index.html             the whole app (HTML, CSS, JavaScript)
manifest.webmanifest   app name, colors and icons for installing
sw.js                  offline support
icon-*.png, icon.svg   app icons
```

## Safety

This plan is general fitness guidance, not medical advice. Learn heavy lifts with a trainer, use a spotter on heavy bench press, and stop if you feel joint pain.

License: MIT
