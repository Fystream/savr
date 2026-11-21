# Savr

Keep track of your money and build your savings.

A real Android app (Capacitor). All app files and data live inside the app — no website or Chrome needed.

## Get the APK
Every push to `main` builds the app on GitHub Actions.
Go to **Actions → latest "Build Savr APK" run → Artifacts → Savr-test-apk**, download, unzip, and install `app-debug.apk`.

## Signed release (for Google Play)
Add these repository secrets (Settings → Secrets and variables → Actions):
- `SAVR_KEYSTORE_BASE64` – your signing.keystore, base64-encoded
- `SAVR_STORE_PASSWORD`, `SAVR_KEY_ALIAS`, `SAVR_KEY_PASSWORD`

Never commit the keystore or its passwords.
