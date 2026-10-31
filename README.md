# Adiblar — Writers and Literature

An Android literature application for browsing writer biographies and maintaining a personal library. The repository's historical name is `Booking`; the source application is organized around writers and literature.

## What it demonstrates

- Browse writer collections and search authors.
- Display writer biographies and library screens.
- Add writer information and images through Firebase-backed forms.
- Google and phone authentication flows backed by Firebase Authentication.

## Explore the code

- `app/src/main/java/com/chsd/adiblar/ui/` — writer browsing, search, library, authentication, and editing screens.
- `app/src/main/java/com/chsd/adiblar/models/Writer.kt` — writer data model.
- `app/src/main/java/com/chsd/adiblar/adapters/` — list and pager adapters.

## Open and build

Open the repository in Android Studio and use a Gradle JDK compatible with its checked-in Android Gradle Plugin. Install Android SDK Platform 31 and let the Gradle wrapper resolve the project dependencies.

Connect your own Firebase project and provide its `app/google-services.json`. The source uses Authentication, Firestore, and Storage; enable the providers and access rules required by your environment.

```bash
./gradlew :app:assembleDebug
```

Run the `app` configuration on a device or emulator. On Windows, use `gradlew.bat`.

## Project status

This repository is a learning project. Its original dependency versions are retained; dependency resolution and behavior on current Android versions may require maintenance. Firebase service availability and permissions must be configured separately.

