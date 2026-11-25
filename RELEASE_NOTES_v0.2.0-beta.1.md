# WorthIt v0.2.0-beta.1 (build 383)

Pre-release. Not a claim that automated market valuation is complete.

## File
- `WorthIt-v0.2.0-beta-build383.apk`
- versionName 0.2.0, versionCode 38301, package `com.worthit.app`
- SHA-256 of the APK: `b7212d2d365dea00da1247e7eb1b0ba3a694865fb84a842635bae46539f837ec`
- Signing certificate SHA-256: `11:AE:F7:70:5A:57:35:B3:5E:13:31:6E:74:DE:F4:D6:7B:EB:FF:94:07:0D:8E:20:7E:F2:EF:70:7D:9B:41:F6`

## What is new
- Device lookup now works when the model name includes storage or RAM (for example "Galaxy S23 Ultra 256GB").
- Three separate result states: device not confirmed, device found but not enough price evidence, evaluated.
- Settings > About shows version, build and release channel.
- Builds are now signed with one permanent key, so future versions install as normal updates.

## Known limitations
- No licensed automatic source of used-phone market prices yet. Automated market-price coverage is incomplete.
- A verdict needs at least 3 comparable listings that you enter yourself (interim path). Without them you get "not enough price evidence", never a guessed price.
- The device catalog does not cover every phone.
- Arabic and Spanish texts are not yet reviewed by native speakers. In Arabic the score shows mixed digit styles.
- Tested by automated tests and CI renders. Physical-device testing is limited.
- Phones only. Tablets, laptops and other categories are planned.

## Languages
English, Arabic (RTL), Spanish.

## Install (first time)
1. Download the `.apk` on your Android phone or tablet (Android 8.0 or newer).
2. Open it. Android asks to allow installs from your browser or file manager. Allow it for this install.
3. Tap Install. If Play Protect warns about an app it has not seen, choose to install anyway only if you downloaded it from this page.
4. Compare the SHA-256 above with the file if you want to check it (a checksum app or `sha256sum`).

## Update from an earlier build
Open the new `.apk` and tap Install. Your settings are kept. Builds made before 0.2.0 that were signed with a temporary key cannot be updated in place: Android shows a "package conflict" message. In that case uninstall the old app once (you lose only your theme and language settings), then install this one. Later versions update normally.
