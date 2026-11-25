# WorthIt (public beta)

WorthIt helps you check whether the asking price of a used phone looks fair. You enter the phone and the price you were offered. WorthIt compares that price with the comparable listings you give it and tells you plainly what it found, and what it could not find.

This repository only hosts the app downloads (APK files) and release notes. It does not contain source code.

## Status: public beta
- This is a beta. Do not treat a result as financial advice.
- Automated market-price coverage is incomplete. WorthIt does not yet have a licensed, automatic source of used-phone prices. It never invents a price.
- Today a price check needs at least 3 comparable listings that you add yourself. This is an interim step until legitimate market-price sources are available.
- If WorthIt cannot confirm the device, or has too little price evidence, it says so instead of showing a verdict.

## What it does
- Device lookup: pick a phone from the built-in catalog or type its name.
- Three honest outcomes: device not confirmed, device found but not enough price evidence, or evaluated (a deal verdict with a confidence level and a fair-value range).
- Every number shows where it came from and when.

## Languages
English, Arabic (right-to-left) and Spanish. The Arabic and Spanish texts have not yet been reviewed by native speakers, so some wording may be rough.

## Download
Go to the latest release on the Releases page and download the `.apk` file. See the release notes for the install and update steps, the version and the file checksum.

## Requirements
Android 8.0 (API 26) or newer. Not available on Google Play yet. It has not been tested on every device.

## Privacy
- No accounts, no sign-in, no ads, no analytics, no crash reporting, no tracking.
- Stored on your device: your theme choice and your language choice. Nothing else is written to the app's storage. The phone details and listings you type are used only while you check a price. Android may keep the form temporarily while the app is in the background, as it does for any app.
- Backups: Android cloud backup is turned off for this app.
- Network: the only internet request WorthIt makes is a lookup to Wikidata (www.wikidata.org) to identify a phone. It sends the phone's brand and model name as you typed or picked it, the language code "en", and a short app identifier. It does not send your asking price, your listings, your condition notes, your location or any device identifier. Wikidata, like any website, can see your IP address.
- The built-in phone catalog works offline. Links you add to listings are never opened by the app.
- Permissions: internet access only. No camera, location, contacts, storage or notification permissions.

## Feedback
Open an issue in this repository.
