# K-Tube Automator - Android APK Build

## 📱 Project Info
- **App Name:** K-Tube Automator
- **Package:** com.ktube.automator
- **Version:** 2.0.0
- **Server:** https://ktube-automator.onrender.com
- **Min Android:** 7.0 (API 24)

## 🔨 BUILD OPTION 1: Android Studio (Easiest)
1. Download Android Studio: https://developer.android.com/studio
2. Open this project folder: `C:\Users\kvari\OneDrive\Desktop\youtube\apk_build\KTubeAutomator`
3. Wait for Gradle sync to complete
4. Click ▶ Run → Select your phone or emulator
5. APK will be at: `app/build/outputs/apk/release/app-release.apk`

## 🔨 BUILD OPTION 2: Command Line (Gradle)
```bash
cd C:\Users\kvari\OneDrive\Desktop\youtube\apk_build\KTubeAutomator
./gradlew assembleRelease
```
APK output: `app/build/outputs/apk/release/app-release.apk`

## 🔨 BUILD OPTION 3: Online (No Install)
1. Go to https://www.pwabuilder.com
2. Enter your deployed URL: https://ktube-automator.onrender.com
3. Click "Package for stores" → Android → Download APK
   This works because we have full PWA setup (manifest + service worker)

## 🔨 BUILD OPTION 4: ApkTool (Quick unsigned)
1. Go to https://appetize.io or https://gonative.io
2. Enter URL: https://ktube-automator.onrender.com
3. Download generated APK

## 📲 Install on Phone
1. Transfer APK to phone via WhatsApp/Telegram/USB
2. Enable "Install from Unknown Sources" in Settings
3. Tap the APK to install
