# Zin AI Android WebView App (v3)

This is a ready-to-build Android Studio project that wraps your Zin AI web app in a WebView.

## Build APK (1-2 minutes)

### Option A — Android Studio (easiest)
1. Open this folder in **Android Studio** (File → Open).
2. Wait for Gradle sync.
3. **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
4. APK appears in `app/build/outputs/apk/release/`.

### Option B — Command line
```bash
./gradlew assembleRelease
```

The unsigned APK is at `app/build/outputs/apk/release/app-release-unsigned.apk`.

## Configured
- Target URL: https://zin-ai.lovable.app
- Version: 3
- Package: com.zin.ai
