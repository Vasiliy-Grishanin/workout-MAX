## https://vasiliy-grishanin.github.io/workout-MAX/

<div align="center">

# 💪 Workout Max

### A gym logbook for iPhone

**No account · No subscription · No internet**

*Log your sets in two taps, see what you lifted last time, and let the rest timer run itself.*

[![Exercises](https://img.shields.io/badge/exercises-622-1E4FD8?style=for-the-badge)](#exercise-catalogue)
[![Offline](https://img.shields.io/badge/works-offline-1F9D55?style=for-the-badge)](#technical-notes)
[![Languages](https://img.shields.io/badge/languages-9-F0851E?style=for-the-badge)](#languages)
[![Price](https://img.shields.io/badge/price-free-6B6F7A?style=for-the-badge)](#)

</div>

---

|   | |
|---|---|
| 🏋️ | **622 exercises** with photos and instructions |
| ⏱️ | **Rest timer**, fixed or progressive, with sound and screen flash |
| 📝 | **Sets pre-filled** from your own history |
| 🏆 | **Personal records** detected as you lift |
| 🔒 | **Everything stays on your phone** |
| 🌍 | **9 languages** |

---

<div align="center">

### 📲 Install

**Open the app in Safari** → **Share** → **Add to Home Screen**

*Works offline from then on.*

</div>

---

<details>
<summary><b>Full documentation</b></summary>

## Contents

- [During a workout](#during-a-workout)
- [Rest timer](#rest-timer)
- [Tracking and stats](#tracking-and-stats)
- [Organisation](#organisation)
- [Exercise catalogue](#exercise-catalogue)
- [Settings](#settings)
- [Data and privacy](#data-and-privacy)
- [Languages](#languages)
- [Technical notes](#technical-notes)
- [Credits](#credits)

## During a workout

Each exercise shows its sets as rows: weight, reps, RIR, and a tick to validate. The **Previous** column shows last time's numbers, and the fields are already filled in with them.

| Feature | What it does |
|---|---|
| Pre-fill | Values come from the last normal session with that exercise |
| Carry-over | Editing one set updates the following ones, unless already validated or edited |
| Set types | Normal, warm-up, drop set, to failure. Warm-ups are excluded from records and volume |
| Supersets | Group exercises; the timer only starts after the last one of the group |
| Live records | Max weight, estimated 1RM, best set, session volume, with a notification when one falls |
| Notes | A persistent note per exercise (seat height, grip) and a free note per session |
| Replace | Swap an exercise for a similar one, reorder the list, remove |
| Off-norm | Mark a session whose values should not be reused next time. Records still count |
| Screen on | The screen stays awake for the whole session |
| Auto-resume | Saved on every action, survives closing the app |

## Rest timer

- **Fixed** or **progressive** duration (start time + increment per set), set per exercise or globally.
- Separate rest after a warm-up set.
- −15 s, +15 s and Skip buttons. Beeps at 3, 2, 1 then at zero, with a screen flash.
- Past zero it keeps counting in orange, so you know how long you actually rested.
- A **transition** timer runs after the last set of an exercise, with no alarm.
- Both timers stop on their own after 15 minutes.

## Tracking and stats

- **Exercise page**: start and end photos, muscle map (front and back), equipment, level, instructions, records, progress chart (max weight, estimated 1RM, volume) over 1 month, 3 months, 1 year or all time, and full history.
- **History**: sessions by month, with details, comparison to the previous one, text sharing, editing and deletion.
- **Stats**: training calendar, weeks in a row, muscles worked this week, sets per muscle group and week, body weight chart.
- **Session summary**: duration, sets, volume, records broken, comparison with last time.

## Organisation

- **Templates**: reusable exercise lists (Push, Pull, Legs…). A template only fixes the list; weights and reps always come from your history.
- **Rotation**: the home screen suggests the next template, but never decides for you.
- **Template update** offered at the end of a session if the exercises changed.
- **Repeat** a past session in one tap, **favourite sessions**, **favourite exercises** listed first.
- **Custom exercises**, with a photo of the machine taken at the gym.

## Exercise catalogue

- 622 strength and powerlifting exercises, each with two photos.
- Search in English or French, filters by muscle group and equipment.
- Tracking modes per exercise: weight and reps, bodyweight, weighted, assisted, duration. Unilateral option.

## Settings

| Section | Options |
|---|---|
| Language | 9 languages |
| Workout | kg or lb, default sets and reps, default rest, RIR column, carry-over, automatic RIR, screen on |
| Rest signal | Over the music, ducking the music, priority, or silent. Screen flash. Beeps at 3, 2, 1 |
| Appearance | Light, dark or automatic theme |
| Backup | JSON export and import, reminder if the last backup is over a month old |

> On iPhone in silent mode, only the "priority" sound plays, and it may briefly interrupt the music. The screen flash always works.

## Data and privacy

Everything is stored in the phone's browser storage. No server, no account, no tracking. Export a backup from the settings now and then: it is the only way to recover your data if you change phone or clear the browser storage.

## Languages

Interface in French, Russian, English, German, Chinese, Spanish, Hindi, Italian and Portuguese. Exercise names and instructions exist in French and English; other languages show them in English.

## Technical notes

- A single self-contained `index.html` (HTML, CSS, JavaScript, data and photos included), around 13 MB.
- No external dependency, no network request at runtime.
- `sw.js` caches the app for offline use; `manifest.webmanifest` and the icons handle the home screen install.
- Hosted on GitHub Pages. To update, replace `index.html` and `sw.js`, then close and reopen the app twice.

## Credits

Exercise photos and source data: [free-exercise-db](https://github.com/yuhonas/free-exercise-db), public domain (Unlicense). French names and instructions written for this project.

</details>
