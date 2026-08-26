# Kinder Prima Help

Kinder Prima Help is an offline-first learning companion for Year 1 pupils. It includes interactive exercises, subject progress tracking, encouragement, parent-friendly reports, and a playful 3D learning interface.

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
