| Build Status | Release |
|-------------|---------|
| ![Build](https://github.com/kioshiDesu/MReader/workflows/Build%20and%20Release/badge.svg) | ![Release](https://img.shields.io/github/release/kioshiDesu/MReader.svg?maxAge=3600&label=download) |


# ![app icon](./.github/readme-images/app-icon.png)MangaReader

MangaReader is a free and open source manga reader for Android 6.0 and above. Built from TachiyomiSY, it provides a powerful reading experience with support for multiple sources, extensions, and customizable reading modes.

![screenshots of app](./.github/readme-images/screens.png)

## Features

* Online reading from a variety of sources (via extensions)
* Local reading of downloaded content
* A configurable reader with multiple viewers, reading directions and other settings
* Webtoon/Vertical scroll reading mode
* Download chapters for offline reading
* Cloudflare bypass support
* Tracker support: [MyAnimeList](https://myanimelist.net/), [AniList](https://anilist.co/), [Kitsu](https://kitsu.app/), [MangaUpdates](https://mangaupdates.com), [Shikimori](https://shikimori.one), and [Bangumi](https://bgm.tv/) support
* Categories to organize your library
* Light and dark themes
* Schedule updating your library for new chapters
* Create backups locally to read offline or to your desired cloud service
* Extension system (Tachiyomi-compatible)
* Multi-source search
* Latest tab with up to 5 sources
* Automatic webtoon detection
* Library search with advanced filters
* Source migration
* Batch import of custom sources and extensions
* And more...

## Download

Get the latest APK from the [Releases page](https://github.com/kioshiDesu/MReader/releases/latest).

> ### If you are unsure which version to download then go with `MangaReader.apk`

| Architecture | APK |
|-------------|-----|
| Universal | MangaReader.apk |
| arm64-v8a | MangaReader-arm64-v8a.apk |
| armeabi-v7a | MangaReader-armeabi-v7a.apk |
| x86 | MangaReader-x86.apk |
| x86_64 | MangaReader-x86_64.apk |

## Adding Extension Repos

To add extension repositories:

1. Go to **Settings** → **Extensions**
2. Tap the **Repo** tab
3. Add the following popular extension repos:

- **Keiyoushi** (Recommended): `https://raw.githubusercontent.com/keiyoushi/extensions/repo/index.min.json`
- **Komikku**: `https://kkomikku.github.io/komikku-extensions/index.min.json`

## Building from Source

### Prerequisites
- JDK 17
- Android SDK

### Build Commands

```bash
# Debug APK
./gradlew assembleDevDebug

# Release APK
./gradlew assembleStandardRelease
```

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](./CONTRIBUTING.md) guidelines.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](./LICENSE) file for details.

## Disclaimer

This app is a fork of Tachiyomi. Extension-related issues should be reported to the respective extension maintainers.
