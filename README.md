# Kinder Prima Help

Kinder Prima Help is an offline-first learning companion for Year 1 pupils. It includes interactive exercises, subject progress tracking, encouragement, parent-friendly reports, and a playful 3D learning interface.

## What is this project?

This project helps young pupils practise Year 1 learning activities in a friendly, game-like environment. It works without an Internet connection after the HTML file or Android app has been opened.

Pupils can choose a subject, answer practice questions, receive instant feedback, collect progress, and revisit topics that need more practice. Parents or teachers can review the locally saved progress report.

## How to use it

### Web version

1. Download or clone this repository.
2. Open `KinderPrimaHelp_eStudyKit_Year1_v2026-08-25.html` in a modern web browser.
3. Enter the access password provided by the administrator.
4. Select the pupil name, choose a subject, and start learning.

Progress is saved automatically on that device and browser. To keep a backup, use the progress export option in the pupil profile.

### Android version

1. Open the `android-app` folder in Android Studio.
2. Allow Android Studio to install any required Android components.
3. Choose **Build > Build APK(s)**.
4. Install the generated APK on an Android device.

The Android app opens the same learning content from inside the app and works offline. It does not request Internet permission.

## For parents and teachers

- Open the pupil profile to view the progress tools.
- Export progress before changing devices or browsers.
- Import an exported progress file to restore it on the same app version.
- Use the parent report to see completed topics, overall accuracy, practice needs, and learning streaks.

## Adding more learning pages

Future HTML pages can be added to `android-app/app/src/main/assets/`. For example, save a new page as `lesson-two.html` and link to it with `href="lesson-two.html"`.

## 3D motion experience

The learning interface uses original CSS-only 3D motion designed for young learners. The dashboard features a layered study desk with books, a screen, pencil, sticky note, and floating learning orbs. The objects respond gently to pointer movement for depth, while cards tilt slightly on desktop to feel tactile and playful.

The opening screen also includes an animated 3D ABC book with floating stars. All motion is offline, uses no copied external artwork, and automatically turns off for devices that request **Reduce motion**. On smaller screens, the decorative 3D elements reduce or hide so that reading and learning content stays clear.

## What is included

- Standalone web edition: `KinderPrimaHelp_eStudyKit_Year1_v2026-08-25.html`
- Android app shell: `android-app/`
- Offline content packaged in the Android app at `android-app/app/src/main/assets/index.html`

## Android app

Open `android-app` in Android Studio, allow it to install the required Android components, then use **Build > Build APK(s)**. The app runs the learning content entirely offline and does not request Internet permission.

To add another HTML page later, place it in `android-app/app/src/main/assets/` and link to it with a relative address, for example `lesson-two.html`.

## Development notes

The current app stores learning progress locally on the device. It is designed for personal or classroom use, not as a secure authentication or cloud-synchronisation system.

## License

This project is released under the MIT License. See [LICENSE](LICENSE).
