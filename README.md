# APO Android

Android wrapper for:
https://apo-official.github.io/apo-official/

## Included
- APO launcher/splash branding (app only)
- JavaScript + DOM storage
- Firebase/Cloudinary web functionality
- Android file picker for image/video uploads
- Microphone permission bridge for WebRTC and voice messages
- External links open outside the app
- Android back navigation
- targetSdk / compileSdk 36

## Build
Open this folder in Android Studio, let Gradle sync, then:
- Test APK: Build > Build App Bundle(s) / APK(s) > Build APK(s)
- Play bundle: Build > Generate Signed Bundle / APK > Android App Bundle

Before a Play release, test sign-in, chat, uploads, voice messages and voice calls on at least two real devices/networks.

Note: WebRTC peer-to-peer calls using only STUN can fail on some mobile/carrier/NAT networks. Reliable production calling normally needs a TURN service.
