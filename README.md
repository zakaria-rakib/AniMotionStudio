# Animotion Studio

Animotion Studio is an Android 2D animation editor built with Kotlin and Jetpack Compose.

## Current editor capabilities
- Project home with recent saved projects and new-project setup (name, canvas size, FPS, background).
- Vector path drawing/editing, brush, eraser, lasso selection, text, image import, fill, shading and colour sampling.
- Two-finger canvas zoom and pan, fit-to-canvas, rulers, selection transforms and flip.
- Frame timeline, duplicate/add/delete/reorder frame operations, layers, onion skin and camera keyframes.
- Vector object motion tweening between keyframes.
- Project save/open/share and PNG sequence, GIF and MP4 export.

## Branding
The app uses an original scalable SVG brand mark at [brand/AniMotionStudio-Logo.svg](brand/AniMotionStudio-Logo.svg).

## Build
GitHub Actions builds a debug APK on each push to `main`. Open the repository's Actions tab and download the `AniMotionStudio-debug-apk` artifact from a successful run.

The workflow also publishes an editable `AniMotionStudio-source-snapshot` artifact so the Android source can be downloaded independently.

## Known limitations in this iteration
This is an evolving editor, not a one-to-one copy of another app. Video import is currently converted to still frames (up to 60). Audio support is a single attached playback track; MP4 export currently has no audio mix. Recording, multi-track audio editing, full perspective/morph mesh warping and a complete professional raster-fill pipeline remain future work. Device testing across Android models is still needed.
