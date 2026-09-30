# FasterTimer

Make your timer feel slower or faster.

FasterTimer is an Android countdown timer where **what the timer shows** and **how long it really runs** are set separately. Set the apparent duration (say 25:00 on screen) and the actual duration (the real time until the alarm), and it scales the countdown to match: ×1.00 is real time, higher runs faster, lower runs slower. Useful for training yourself against a tougher clock, like practising a 3-hour exam in 2½ hours without doing the maths.

## Features

- Separate **apparent** (displayed) and **actual** (real) durations, with a live time-scale readout
- Native **alarm scheduling**, so the alarm still fires when the app is in the background
- Clean offline UI (a bundled WebView page, no internet needed)

## Get the APK

The Android project is in [`FasterTimer_alarm_ready.zip`](FasterTimer_alarm_ready.zip). To build it on GitHub:

1. Open **Actions → Build FasterTimer APK → Run workflow**.
2. When it finishes, download the **FasterTimer-APK** artifact and install it.

To build locally, unzip the project and run `./gradlew assembleDebug` inside `FasterTimer/` (JDK 17 and the Android SDK needed).

The same timer is also built into [ExamSim](https://github.com/yatharth1011/jee-adv-paper).
