# Syncthing-Fork - Google Play release channel

[![License: MPLv2](https://img.shields.io/badge/License-MPLv2-blue.svg)](https://opensource.org/licenses/MPL-2.0)
<a href="https://github.com/Catfriend1/syncthing-android/releases/latest" alt="GitHub release"><img src="https://img.shields.io/github/v/release/Catfriend1/syncthing-android" /></a>
<a href="https://play.google.com/store/apps/details?id=com.github.catfriend1.syncthingandroid" alt="GitHub Stats"><img src="https://img.shields.io/badge/GPlay_Downloads-100.000+-brightgreen.svg" /></a>
<a href="https://hosted.weblate.org/projects/syncthing/android/catfriend1/"><img src="https://hosted.weblate.org/widget/syncthing/android/catfriend1/fork-stringsxml/svg-badge.svg" alt="Translation status" /></a>
[![Build App](https://github.com/nel0x/syncthing-android-gplay/actions/workflows/build-app.yaml/badge.svg)](https://github.com/nel0x/syncthing-android-gplay/actions/workflows/build-app.yaml)

A wrapper of [Syncthing](https://github.com/syncthing/syncthing) for Android.

This repository produces and publishes the Google Play build of Syncthing-Fork shown on <a href="https://play.google.com/store/apps/details?id=com.github.catfriend1.syncthingandroid">this listing</a>.
It regularly mirrors the <a href="https://github.com/Catfriend1/syncthing-android">upstream project</a> and applies only changes required to stay compliant with Google Play policies.

<img src="app/src/main/play/listings/en-US/graphics/phone-screenshots/1.png" alt="screenshot 1" width="200" /> · <img src="app/src/main/play/listings/en-US/graphics/phone-screenshots/2.png" alt="screenshot 2" width="200" /> · <img src="app/src/main/play/listings/en-US/graphics/phone-screenshots/4.png" alt="screenshot 3" width="200" />

## Switching from the (now deprecated) official version

Switching is easier than you may think!

- On Syncthing on the official app, go into the settings and create a backup.
- Confirm you can see that backup in your files.
- Now stop the official app entirely using the system app settings for Syncthing (force stop the app basically - we need to ensure it's not running).
- Install Syncthing-Fork [v1.29.7.1](https://github.com/Catfriend1/syncthing-android/releases/tag/v1.29.7.1)
- Now start Syncthing-Fork.
- In the Syncthing-Fork settings, restore the backup you created earlier.
- Like magic, everything should be as it was in Syncthing official.
- Confirm everything looks good.
- Uninstall the official Syncthing app.
- Delete the syncthing configuration backup from `backups/syncthing`.
- Upgrade to the [latest Syncthing-Fork version](https://github.com/Catfriend1/syncthing-android/releases/latest)

## Wiki and Useful Articles

Our knowledge base is published [here](https://github.com/Catfriend1/syncthing-android/tree/main/wiki#readme).

Our [release history and changelog](https://github.com/Catfriend1/syncthing-android/blob/main/wiki/CHANGELOG.md) can be found on the wiki.

## Building and Development Notes

See [detailed info](https://github.com/Catfriend1/syncthing-android/blob/main/wiki/Building-and-Development.md).

## Acknowledgments

This project was forked from [syncthing/syncthing-android](https://github.com/syncthing/syncthing-android).

Special thanks to the former maintainers:

- [imsodin](https://github.com/imsodin)
- [nutomic](https://github.com/nutomic)

## Privacy Policy

See our document on privacy: [privacy-policy.md](https://github.com/Catfriend1/syncthing-android/blob/main/privacy-policy.md).

## License

The project is licensed under [MPLv2](LICENSE).
