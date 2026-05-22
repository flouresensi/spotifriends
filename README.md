# 🎧 Spotifriends

> See what your Spotify friends are listening to — in real time.

![Android](https://img.shields.io/badge/Platform-Android-green)
![Kotlin](https://img.shields.io/badge/Language-Kotlin-blue)
![Spotify](https://img.shields.io/badge/Spotify-Premium-1DB954)
![License](https://img.shields.io/badge/License-MIT-gray)

---

## Features

| Feature | Description |
|---|---|
| 👥 Friend Activity | See what your friends are playing right now |
| 🎵 Now Playing | Your current track always pinned at the top |
| 📊 Top Stats | Your top artists & tracks — 4 weeks, 6 months, all time |
| 🔄 Auto Refresh | Activity updates every 30 seconds automatically |
| 🎨 Dynamic Palette | Album art colors theme the card backgrounds |

---

## Installation

1. Go to [Releases](../../releases) and download the latest `.apk`
2. On your Android device, enable **Install unknown apps**
3. Install the APK and open the app
4. Login with your Spotify account
5. Done — your friends' activity will appear automatically

---

## Requirements

- Android 8.0 (API 26) or higher
- Spotify Premium account
- Friends with **"Share my listening activity"** enabled on Spotify

---

## How it works

Spotifriends authenticates using your Spotify session cookie to access
the same friend activity data shown in the Spotify desktop app sidebar.
No data is collected or sent to any external server — everything runs
directly on your device.

---

## Built with

- [Kotlin](https://kotlinlang.org/) — Android development
- [OkHttp](https://square.github.io/okhttp/) — HTTP requests
- [Glide](https://github.com/bumptech/glide) — Image loading
- [Coroutines](https://kotlinlang.org/docs/coroutines-overview.html) — Async operations

---

## Disclaimer

> This app is not affiliated with, endorsed by, or connected to Spotify AB.
> It is intended for personal use only. Use at your own risk.

---

## License

MIT License — see [LICENSE](LICENSE) for details.
