# Clipora Android

Clipora is a reusable theme-based creator for video, thumbnails and static images.

## Implemented in this first runnable source milestone

- Kotlin + Jetpack Compose project
- Login / trial-account placeholder screen
- Home screen
- Create Video flow
- Create Thumbnail / Image flow
- Android system media picker
- Aspect ratios: 9:16, 16:9, 1:1, 4:5, YouTube thumbnail
- Video duration presets: 30 seconds, 60 seconds, 2 minutes
- Theme presets: News, Wedding, Birthday, Business, Custom
- Real image/video preview inside the selected canvas ratio
- Editable headline, ticker/secondary text and logo text
- Reusable shared theme/editor data model

## Deliberately not faked

The MP4 and JPG render/export engines, authentication backend, project persistence and Google Play Billing are not claimed as complete yet. They are the next implementation milestones.

## Open in Android Studio

Open the repository root as a Gradle project. Android Studio can install/sync the required Android SDK and Gradle tooling.

Package name: `com.clipora.app`

## Subscription requirement

Production Clipora will provide a one-month free trial and paid subscription. Entitlement will be account/server-side and verified against Google Play Billing so uninstall/reinstall does not reset trial time.
