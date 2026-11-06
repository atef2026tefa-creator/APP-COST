# Smart Cost Pro — Android App

Native Android financial app built with Kotlin, Jetpack Compose, and Material 3.

## Repository layout

- `app/` — Android application source and unit tests.
- `backend/` — Node.js/Express REST API and PostgreSQL schema.
- `oracle/` — Oracle Cloud deployment documentation.

## Android build

1. Open the project in Android Studio (Ladybug or newer).
2. Sync Gradle.
3. Run the app on an emulator or device (minSdk 24+).

```bash
./gradlew assembleDebug
./gradlew testDebugUnitTest
```

## Backend

See `oracle/SETUP_ORACLE.md` for deployment instructions. Copy `backend/.env.example` to `backend/.env` and supply your own secrets; never commit the real `.env` file.

## License

MIT — see `LICENSE`.
