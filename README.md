# WeTaxi Driver App — Releases

  Public distribution repo for the **WeTaxi Driver** Android app. Holds only
  built APKs and their QR codes — no source code lives here.

  The source code is private, in
  [`Tri-Pass/stations-driver-mobile`](https://github.com/Tri-Pass/stations-driver-mobile).
  This repo exists so testers can download the app without needing access to
  that private repo.

  ## Getting the app

  1. Go to the [Releases](../../releases) page.
  2. Pick the latest build.
  3. Scan the QR code with your phone, or download `app-release.apk` directly.

  Android only. For drivers only — not intended for public distribution.

  ## How releases get here

  Every release is published automatically by a GitHub Actions workflow
  (`build-apk.yml`) running in `stations-driver-mobile`, triggered manually from
  that repo's Actions tab. Nothing should be pushed here by hand.
