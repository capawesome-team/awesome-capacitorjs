# Awesome Capacitor [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome things related to Capacitor.

> Capacitor is a cross-platform native runtime that makes it easy to build modern web apps that run natively on iOS, Android, and the Web. ([Source](https://capacitorjs.com/docs))

<div class="capawesome-z29o10a">
  <a href="https://cloud.capawesome.io/" target="_blank">
    <img alt="Deliver Live Updates to your Capacitor app with Capawesome Cloud" src="https://cloud.capawesome.io/assets/banners/cloud-deploy-real-time-app-updates.png?t=1" />
  </a>
</div>

## Contents

- [Official](#official)
- [Guides](#guides)
- [Learnings](#learnings)
- [Plugins](#plugins)
    - [Official Plugins](#official-plugins)
    - [Community Plugins](#community-plugins)
- [Tools](#tools)
- [Related Lists](#related-lists)

--------------------

## Official

- [Website](https://capacitorjs.com/)
- [Documentation](https://capacitorjs.com/docs)
- [CLI](https://capacitorjs.com/docs/cli)
- [Community](https://capacitorjs.com/community)
- [Blog](https://capacitorjs.com/blog)
- [Enterprise](https://capacitorjs.com/enterprise)
- [Repository](https://github.com/ionic-team/capacitor)
- [Twitter](https://twitter.com/capacitorjs)

## Guides

- [Creating Plugins](https://capacitorjs.com/docs/plugins/creating-plugins)
- [Creating Splash Screens and Icons](https://capacitorjs.com/docs/guides/splash-screens-and-icons)
- [App Deployment and Realtime Updates](https://capacitorjs.com/docs/guides/deploying-updates)
- [CI/CD for Capacitor Apps](https://capacitorjs.com/docs/guides/ci-cd)
- [Data Storage in Capacitor](https://capacitorjs.com/docs/guides/storage)
- [Security Best Practices for Capacitor](https://capacitorjs.com/docs/guides/security)
- [Using Push Notifications with Firebase in an Ionic + Angular App](https://capacitorjs.com/docs/guides/push-notifications-firebase)
- [Saving Plugin Calls](https://capacitorjs.com/docs/core-apis/saving-calls)
- [Mocking Capacitor Plugins](https://capacitorjs.com/docs/guides/mocking-plugins)
- [The Push Notifications Guide for Capacitor](https://capawesome.io/blog/the-push-notifications-guide-for-capacitor/)

## Learnings

- [Ionic Academy Capacitor Crash Course](https://ionicacademy.com/capacitor-crash-course/)

## Platforms

- [@capacitor/android](https://github.com/ionic-team/capacitor)
- [@capacitor/ios](https://github.com/ionic-team/capacitor)
- [@capacitor-community/electron](https://github.com/capacitor-community/electron)

## Plugins

- [Proposals](https://github.com/capacitor-community/proposals)

### Official Plugins

- [@capacitor/action-sheet](https://capacitorjs.com/docs/apis/action-sheet) - Provides access to native Action Sheets.
- [@capacitor/app](https://capacitorjs.com/docs/apis/app) - The App API handles high level App state and events.
- [@capacitor/app-launcher](https://capacitorjs.com/docs/apis/app-launcher) - The AppLauncher API allows your app to open other apps.
- [@capacitor/browser](https://capacitorjs.com/docs/apis/browser) - The Browser API provides the ability to open an in-app browser and subscribe to browser events.
- [@capacitor/clipboard](https://capacitorjs.com/docs/apis/clipboard) - The Clipboard API enables copy and pasting to/from the system clipboard.
- [@capacitor/device](https://capacitorjs.com/docs/apis/device) - The Device API exposes internal information about the device.
- [@capacitor/dialog](https://capacitorjs.com/docs/apis/dialog) - The Dialog API provides methods for triggering native dialog windows for alerts, confirmations, and input prompts.
- [@capacitor/filesystem](https://capacitorjs.com/docs/apis/filesystem) - The Filesystem API provides a NodeJS-like API for working with files on the device.
- [@capacitor/file-viewer](https://capacitorjs.com/docs/apis/file-viewer) - The FileViewer API provides mechanisms for opening files and previewing media.
- [@capacitor/file-transfer](https://capacitorjs.com/docs/apis/file-transfer) - The FileTransfer API provides mechanisms for downloading and uploading files.
- [@capacitor/geolocation](https://capacitorjs.com/docs/apis/geolocation) - The Geolocation API provides simple methods for getting and tracking the current position of the device using GPS.
- [@capacitor/haptics](https://capacitorjs.com/docs/apis/haptics) - The Haptics API provides physical feedback to the user through touch or vibration.
- [@capacitor/keyboard](https://capacitorjs.com/docs/apis/keyboard) - The Keyboard API provides keyboard display and visibility control, along with event tracking when the keyboard shows and hides.
- [@capacitor/local-notifications](https://capacitorjs.com/docs/apis/local-notifications) - The Local Notifications API provides a way to schedule device notifications locally.
- [@capacitor/motion](https://capacitorjs.com/docs/apis/motion) - The Motion API tracks accelerometer and device orientation.
- [@capacitor/network](https://capacitorjs.com/docs/apis/network) - The Network API provides network and connectivity information.
- [@capacitor/push-notifications](https://capacitorjs.com/docs/apis/push-notifications) - The Push Notifications API provides access to native push notifications.
- [@capacitor/screen-reader](https://capacitorjs.com/docs/apis/screen-reader) - The Screen Reader API provides access to TalkBack/VoiceOver/etc.
- [@capacitor/share](https://capacitorjs.com/docs/apis/share) - The Share API provides methods for sharing content in any sharing-enabled apps the user may have installed.
- [@capacitor/splash-screen](https://capacitorjs.com/docs/apis/splash-screen) - The Splash Screen API provides methods for showing or hiding a Splash image.
- [@capacitor/status-bar](https://capacitorjs.com/docs/apis/status-bar) - The StatusBar API Provides methods for configuring the style of the Status Bar, along with showing or hiding it.
- [@capacitor/storage](https://capacitorjs.com/docs/apis/storage) - The Storage API provides a simple key/value persistent store for lightweight data.
- [@capacitor/text-zoom](https://capacitorjs.com/docs/apis/text-zoom) - The Text Zoom API provides the ability to change Web View text size for visual accessibility.
- [@capacitor/toast](https://capacitorjs.com/docs/apis/toast) - The Toast API provides a notification pop up for displaying important information to a user.

### Community Plugins

- [@aparajita/capacitor-biometric-auth](https://github.com/aparajita/capacitor-biometric-auth) - Easy access to native biometric auth APIs on iOS and Android.
- [@aparajita/capacitor-dark-mode](https://github.com/aparajita/capacitor-dark-mode) – Universal, reliable dark mode support for Capacitor apps on the web, iOS and Android.
- [@aparajita/capacitor-ios-silent-notifications](https://github.com/aparajita/capacitor-ios-silent-notifications) – Silent (AKA remote) notification support for Capacitor apps on iOS.
- [@aparajita/capacitor-logger](https://github.com/aparajita/capacitor-logger) – Better logging for the web and native Ionic/Capacitor apps.
- [@aparajita/capacitor-secure-storage](https://github.com/aparajita/capacitor-secure-storage) - Secure, flexible storage for Capacitor apps using iOS Keychain and Android Keystore.
- [@capacitor-community/vue-cli-plugin-capacitor](https://github.com/capacitor-community/vue-cli-plugin-capacitor) - A Vue CLI 3/4 Plugin for Capacitor.
- [@capacitor-community/twitter](https://github.com/capacitor-community/twitter) - Capacitor plugin to enable TwitterKit.
- [@capacitor-community/fcm](https://github.com/capacitor-community/fcm) - Enable Firebase Cloud Messaging for Capacitor apps.
- [@capacitor-community/intercom](https://github.com/capacitor-community/intercom) - Enable Intercom for Capacitor apps.
- [@capacitor-community/media](https://github.com/capacitor-community/media) - Capacitor plugin to activate extra media features.
- [@capacitor-community/firebase-analytics](https://github.com/capacitor-community/firebase-analytics) - Enable Firebase Analytics for Capacitor Apps.
- [@capacitor-community/camera-preview](https://github.com/capacitor-community/camera-preview) - Capacitor plugin that allows camera interaction from HTML code.
- [@capacitor-community/date-picker](https://github.com/capacitor-community/date-picker) - Native DateTime Picker Plugin for Capacitor Apps.
- [@capacitor-community/firebase-crashlytics](https://github.com/capacitor-community/firebase-crashlytics) - Capacitor plugin for Firebase Crashlytics.
- [@capacitor-community/sqlite](https://github.com/capacitor-community/sqlite) - Community plugin for native & electron SQLite databases.
- [@capacitor-community/stripe](https://github.com/capacitor-community/stripe) - Stripe Mobile SDK wrapper for Capacitor.
- [@capacitor-community/react-hooks](https://github.com/capacitor-community/react-hooks) - React hooks for Capacitor.
- [@capacitor-community/keep-awake](https://github.com/capacitor-community/keep-awake) - Capacitor plugin to prevent devices from dimming or locking the screen.
- [@capacitor-community/http](https://github.com/capacitor-community/http) - Community plugin for native HTTP.
- [@capacitor-community/text-to-speech](https://github.com/capacitor-community/text-to-speech) - Capacitor plugin for synthesizing speech from text.
- [@capacitor-community/native-audio](https://github.com/capacitor-community/native-audio) - Capacitor community plugin for playing sounds.
- [@capacitor-community/firebase-remote-config](https://github.com/capacitor-community/firebase-remote-config) - Capacitory community plugin for Firebase Remote Config.
- [@capacitor-community/in-app-purchases](https://github.com/capacitor-community/in-app-purchases) - WIP: In App Purchases plugin for Capacitor.
- [@capacitor-community/native-market](https://github.com/capacitor-community/native-market) - Capacitor community plugin for native market for Play Store/App Store.
- [@capacitor-community/capacitor-googlemaps-native](https://github.com/capacitor-community/capacitor-googlemaps-native) - Capacitor Plugin using native Google Maps SDK for Android and iOS.
- [@capacitor-community/contacts](https://github.com/capacitor-community/contacts) - Contacts Plugin for Capacitor.
- [@capacitor-community/apple-sign-in](https://github.com/capacitor-community/apple-sign-in) - Sign in with Apple Support.
- [@capacitor-community/flipper](https://github.com/capacitor-community/flipper) - Capacitory community plugin for Flipper.
- [@capacitor-community/facebook-login](https://github.com/capacitor-community/facebook-login) - Facebook Login support.
- [@capacitor-community/admob](https://github.com/capacitor-community/admob) - Community plugin for using Google AdMob.
- [@capacitor-community/speech-recognition](https://github.com/capacitor-community/speech-recognition) - Capacitor community plugin for speech recognition.
- [@capacitor-community/realm](https://github.com/capacitor-community/realm) - Capacitor community plugin for native Realm.
- [@capacitor-community/auth0](https://github.com/capacitor-community/auth0) - A native plugin for Auth0 authentication provider.
- [@capacitor-community/barcode-scanner](https://github.com/capacitor-community/barcode-scanner) - A fast and efficient (QR) barcode scanner for Capacitor.
- [@capacitor-community/background-geolocation](https://github.com/capacitor-community/background-geolocation) - Capacitor plugin which lets you receive geolocation updates even while the app is backgrounded.
- [@capacitor-community/bluetooth-le](https://github.com/capacitor-community/bluetooth-le) - Capacitor plugin for Bluetooth Low Energy.
- [@capacitor-community/uxcam](https://github.com/capacitor-community/uxcam) - UXCam and FullStory app analytics.
- [@capacitor-community/privacy-screen](https://github.com/capacitor-community/privacy-screen) - Capacitor plugin that protects your app from displaying a screenshot in Recents screen/App Switcher.
- [@capacitor-community/screen-brightness](https://github.com/capacitor-community/screen-brightness) - Capacitor community plugin for controlling screen brightness on iOS and Android devices.
- [@capacitor-community/app-icon](https://github.com/capacitor-community/app-icon) - Capacitor plugin for managing an iOS app's icon.
- [@capacitor-community/card-scanner](https://github.com/capacitor-community/card-scanner) - Simple card scanner for Capacitor Applications.
- [@capacitor-community/safe-area](https://github.com/capacitor-community/safe-area) - A plugin to expose the safe area insets from the native iOS/Android device to your web project.
- [@capacitor-community/appcenter-sdk-capacitor](https://github.com/capacitor-community/appcenter-sdk-capacitor) - Capacitor Plugin for Microsoft's Visual Studio App Center SDK.
- [@capacitor-community/photoviewer](https://github.com/capacitor-community/photoviewer) - PhotoViewer table images with fullscreen and sharing capabilities.
- [@capacitor-firebase/analytics](https://capawesome.io/plugins/firebase/analytics/) - Capacitor plugin for Firebase Analytics.
- [@capacitor-firebase/app](https://capawesome.io/plugins/firebase/app/) - Capacitor plugin for Firebase App.
- [@capacitor-firebase/app-check](https://capawesome.io/plugins/firebase/app-check/) - Capacitor plugin for Firebase App Check.
- [@capacitor-firebase/authentication](https://capawesome.io/plugins/firebase/authentication/) - Capacitor plugin for Firebase Authentication.
- [@capacitor-firebase/crashlytics](https://capawesome.io/plugins/firebase/crashlytics/) - Capacitor plugin for Firebase Crashlytics.
- [@capacitor-firebase/firestore](https://capawesome.io/plugins/firebase/firestore/) - Capacitor plugin for Firebase Cloud Firestore.
- [@capacitor-firebase/functions](https://capawesome.io/plugins/firebase/cloud-functions/) - Capacitor plugin for Firebase Cloud Functions.
- [@capacitor-firebase/messaging](https://capawesome.io/plugins/firebase/messaging/) - Capacitor plugin for Firebase Cloud Messaging.
- [@capacitor-firebase/performance](https://capawesome.io/plugins/firebase/performance/) - Capacitor plugin for Firebase Performance Monitoring.
- [@capacitor-firebase/remote-config](https://capawesome.io/plugins/firebase/remote-config/) - Capacitor plugin for Firebase Remote Storage.
- [@capacitor-firebase/storage](https://capawesome.io/plugins/firebase/storage/) - Capacitor plugin for Firebase Cloud Storage.
- [@capacitor-mlkit/barcode-scanning](https://capawesome.io/plugins/mlkit/barcode-scanning/) - Unofficial Capacitor plugin for ML Kit Barcode Scanning.
- [@capacitor-mlkit/document-scanner](https://capawesome.io/plugins/mlkit/document-scanner/) - Unofficial Capacitor plugin for ML Kit Document Scanner.
- [@capacitor-mlkit/face-detection](https://capawesome.io/plugins/mlkit/face-detection/) - Unofficial Capacitor plugin for ML Kit Face Detection.
- [@capacitor-mlkit/face-mesh-detection](https://capawesome.io/plugins/mlkit/face-mesh-detection/) - Unofficial Capacitor plugin for ML Kit Face Mesh Detection.
- [@capacitor-mlkit/selfie-segmentation](https://capawesome.io/plugins/mlkit/selfie-segmentation/) - Unofficial Capacitor plugin for ML Kit Selfie Segmentation.
- [@capacitor-mlkit/subject-segmentation](https://capawesome.io/plugins/mlkit/subject-segmentation/) - Unofficial Capacitor plugin for ML Kit Subject Segmentation.
- [@capacitor-mlkit/translation](https://capawesome.io/plugins/mlkit/translation/) - Unofficial Capacitor plugin for ML Kit Translation.
- [@cartona/capacitor-google-play-availability](https://github.com/cartona/capacitor-google-play-availability) - Capacitor plugin to verify that Google Play services is installed and enabled, and request enabling Google Play services on device.
- [@codetrix-studio/capacitor-google-auth](https://github.com/CodetrixStudio/CapacitorGoogleAuth) - Capacitor plugin for Google Auth.
- [@capawesome-team/capacitor-android-dark-mode-support](https://capawesome.io/plugins/android-dark-mode-support) - Capacitor plugin to support dark mode on Android.
- [@capawesome-team/capacitor-android-foreground-service](https://capawesome.io/plugins/android-foreground-service) - Capacitor plugin to run a foreground service on Android.
- [@capawesome-team/capacitor-audio-recorder](https://capawesome.io/plugins/audio-recorder/) - Capacitor plugin for seamless audio recording using the device's microphone.
- [@capawesome-team/capacitor-barometer](https://capawesome.io/plugins/barometer/) - Capacitor plugin to obtain the static air pressure, which is measured in hectopascals (hPa).
- [@capawesome-team/capacitor-biometrics](https://capawesome.io/plugins/biometrics/) - Capacitor plugin to request biometric authentication, such as using face recognition or fingerprint recognition.
- [@capawesome-team/capacitor-bluetooth-low-energy](https://capawesome.io/plugins/bluetooth-low-energy/) - Capacitor plugin for Bluetooth Low Energy (BLE) communication.
- [@capawesome-team/capacitor-contacts](https://capawesome.io/plugins/contacts/) - Capacitor plugin to read, write, or select device contacts.
- [@capawesome-team/capacitor-datetime-picker](https://capawesome.io/plugins/datetime-picker) - Capacitor plugin that let the user easily enter both a date and a time.
- [@capawesome-team/capacitor-file-compressor](https://capawesome.io/plugins/file-compressor) - Capacitor plugin for compressing files.
- [@capawesome-team/capacitor-file-opener](https://capawesome.io/plugins/file-opener) - Capacitor plugin to open a file with the default application.
- [@capawesome-team/capacitor-nfc](https://capawesome.io/plugins/nfc) - Capacitor plugin for reading and writing NFC tags.
- [@capawesome-team/capacitor-printer](https://capawesome.io/plugins/printer) - Capacitor plugin for printing.
- [@capawesome-team/capacitor-secure-preferences](https://capawesome.io/plugins/secure-preferences/) - Capacitor plugin to securely store key/value pairs.
- [@capawesome-team/capacitor-speech-recognition](https://capawesome.io/plugins/speech-recognition/) - Capacitor plugin to transcribe speech into text.
- [@capawesome-team/capacitor-speech-synthesis](https://capawesome.io/plugins/speech-synthesis/) - Capacitor plugin for synthesizing speech from text.
- [@capawesome-team/capacitor-wifi](https://capawesome.io/plugins/wifi/) - Capacitor plugin to manage Wi-Fi connectivity.
- [@capawesome-team/capacitor-zip](https://capawesome.io/plugins/zip/) - Capacitor plugin to zip and unzip files and directories.
- [@capawesome/capacitor-android-battery-optimization](https://capawesome.io/plugins/android-battery-optimization) - Capacitor plugin to access battery optimization settings on Android.
- [@capawesome/capacitor-android-edge-to-edge-support](https://capawesome.io/plugins/android-edge-to-edge-support/) - Capacitor plugin to support edge-to-edge display on Android.
- [@capawesome/capacitor-app-review](https://capawesome.io/plugins/app-review/) - Capacitor plugin that allows users to submit app store reviews and ratings.
- [@capawesome/capacitor-app-shortcuts](https://capawesome.io/plugins/app-shortcuts/) - Capacitor plugin to manage app shortcuts and quick actions.
- [@capawesome/capacitor-app-update](https://capawesome.io/plugins/app-update) - Capacitor plugin that assists with app updates.
- [@capawesome/capacitor-asset-manager](https://capawesome.io/plugins/asset-manager/) - Capacitor plugin to access native asset files.
- [@capawesome/capacitor-background-task](https://capawesome.io/plugins/background-task) - Capacitor plugin for running background tasks.
- [@capawesome/capacitor-badge](https://capawesome.io/plugins/badge) - Capacitor plugin to access and update the badge number of the app icon.
- [@capawesome/capacitor-cloudinary](https://capawesome.io/plugins/cloudinary) - Unofficial Capacitor plugin for Cloudinary SDK.
- [@capawesome/capacitor-file-picker](https://capawesome.io/plugins/file-picker) - Capacitor plugin that allows the user to select a file.
- [@capawesome/capacitor-live-update](https://capawesome.io/plugins/live-update/) - Capacitor plugin that allows you to update your app remotely in real-time without requiring users to download a new version from the app store, known as Over-the-Air (OTA) updates.
- [@capawesome/capacitor-managed-configurations](https://capawesome.io/plugins/managed-configurations) - Capacitor plugin to access managed configuration settings.
- [@capawesome/capacitor-photo-editor](https://capawesome.io/plugins/photo-editor) - Capacitor plugin that allows the user to edit a photo.
- [@capawesome/capacitor-posthog](https://capawesome.io/plugins/posthog/) - Unofficial Capacitor plugin for PostHog.
- [@capawesome/capacitor-screen-orientation](https://capawesome.io/plugins/screen-orientation) - Capacitor plugin to lock/unlock the screen orientation.
- [@capawesome/capacitor-screenshot](https://capawesome.io/plugins/screenshot/) - Capacitor plugin for taking screenshots.
- [@capawesome/capacitor-torch](https://capawesome.io/plugins/torch/) - Capacitor plugin for switching the flashlight on and off.
- [@capgo/camera-preview](https://github.com/Cap-go/camera-preview) - Capacitor plugin that allows camera interaction from HTML code (fork).
- [@capgo/capacitor-crisp](https://github.com/Cap-go/capacitor-crisp) - Crisp chat SDK for your app.
- [@capgo/capacitor-flash](https://github.com/Cap-go/capacitor-flash) - Switch the Flashlight / Torch of your device.
- [@capgo/inappbrowser](https://github.com/Cap-go/capacitor-inappbrowser) - Browser In app browser with urlChangeEvent.
- [@capgo/capacitor-updater](https://github.com/Cap-go/capacitor-updater) - Live update for capacitor app.
- [@capgo/capacitor-mute](https://github.com/Cap-go/capacitor-mute) - Detect silent mode and mute audio.
- [@capgo/native-audio](https://github.com/Cap-go/native-audio) - Capacitor plugin for native audio engine (fork).
- [@capgo/nativegeocoder](https://github.com/Cap-go/capacitor-nativegeocoder) - Native forward and reverse geocoding.
- [@capgo/native-market](https://github.com/Cap-go/native-market) - Capacitor community plugin for native market for Play Store/App Store.
- [@capgo/capacitor-screen-recorder](https://github.com/Cap-go/capacitor-screen-recorder) - Record screen and save to pelicule.
- [@ebarooni/capacitor-calendar](https://github.com/ebarooni/capacitor-calendar) - Capacitor plugin for interacting with calendar and reminders.
- [@revenuecat/purchases-capacitor](https://github.com/RevenueCat/purchases-capacitor) - Capacitor in-app purchases and subscriptions made easy with RevenueCat.
- [@teamhive/capacitor-video-recorder](https://github.com/TeamHive/capacitor-video-recorder) - Video recorder plugin for Capacitor.
- [@wahr/capacitor-websocket-client](https://github.com/OrdinarySF/capacitor-websocket-client) - Capacitor WebSocket Client Plugin.
- [capacitor-app-attest](https://github.com/ludufre/capacitor-app-attest) - Apple Attest with Ionic Capacitor
- [capacitor-bing-translator](https://github.com/sabereen/capacitor-bing-translator) - A simple and free API for using Bing Translator.
- [capacitor-data-storage-sqlite](https://github.com/jepiqueau/capacitor-data-storage-sqlite) - Capacitor Data Storage SQlite Plugin.
- [capacitor-firebase-auth](https://github.com/baumblatt/capacitor-firebase-auth) - Capacitor Firebase Authentication Plugin.
- [capacitor-live-activities](https://github.com/ludufre/capacitor-live-activities) - Capacitor plugin to use Live Activities on iOS 16.2+.
- [capacitor-lottie-splash-screen](https://github.com/ludufre/capacitor-lottie-splash-screen) - Capacitor plugin to use Lottie animations as splash screen.
- [capacitor-plugin-safe-area](https://github.com/AlwaysLoveme/capacitor-plugin-safe-area) - Get SafeArea info on Android and IOS.
- [capacitor-screenshot](https://github.com/ludufre/capacitor-screenshot) - Capacitor plugin to take screenshots.
- [capacitor-video-player](https://github.com/jepiqueau/capacitor-video-player) - Capacitor Video Player Plugin.
- [send-intent](https://github.com/carsten-klaffke/send-intent) - This is a Capacitor plugin meant to be used in Ionic applications for checking if your App was targeted as a share goal.


## Demo Apps

- [capacitor-plugin-demo](https://github.com/robingenz/capacitor-plugin-demo) - Simple Ionic Angular app to demonstrate the use of certain Capacitor plugins.
- [capacitor-firebase-plugin-demo](https://github.com/robingenz/capacitor-firebase-plugin-demo) - Simple Ionic Angular app to demonstrate the use of certain Capacitor Firebase plugins.
- [capacitor-testapp](https://github.com/ionic-team/capacitor-testapp) - The Capacitor TestApp is used to develop new features and verify bug fixes in Capacitor and the official plugins.

## Tools

- [@capacitor/docgen](https://github.com/ionic-team/capacitor-docgen) - Docs Readme Markdown and JSON Generator for Capacitor Plugins.
- [@capacitor/plugin](https://github.com/ionic-team/create-capacitor-plugin) - Create a new Capacitor plugin.
- [cordova-res](https://github.com/ionic-team/cordova-res) - Local Cordova icon/splash screen resource generation tool.

## Related Lists

- [Alexintosh/Awesome-Ionic](https://github.com/Alexintosh/Awesome-Ionic) 
- [candelibas/awesome-ionic](https://github.com/candelibas/awesome-ionic)
