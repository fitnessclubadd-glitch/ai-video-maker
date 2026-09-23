# AI Video Maker Android — Buildable Project

This is a real Android Studio/Gradle project with:
- launcher icon
- app label
- script text editor
- .txt script picker
- scene splitting
- prompt generation
- button to open the free LTX-2 Hugging Face generator

Important: this is an Android app shell + orchestration layer. It does not contain a large text-to-video model because such a model cannot realistically be bundled into a normal zero-cost Android APK.

To build:
- Android Studio: Open this folder and Build > Generate App Bundle/APK > Generate APK.
- Or any compatible Gradle Android build environment.

The resulting APK can be installed on Android.
