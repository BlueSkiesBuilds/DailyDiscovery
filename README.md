# DailyDiscovery

A personalised daily discovery feed for articles, videos, podcasts and audio.
Built for Android by BlueSkiesBuild.

## Building

GitHub Actions builds the APK automatically on every push to `main`.

1. Go to the **Actions** tab in this repo
2. Click the latest **Build APK** run
3. Download the `DailyDiscovery-debug` artifact
4. Unzip to get `app-debug.apk`
5. Copy to your Android phone and install

## First run

On first launch, go to **Settings** and enter your Anthropic API key
(get one at console.anthropic.com). Your key is stored only on your device.

## Features

- Live web search across articles, YouTube, podcasts and audio
- Learns your preferences from ratings
- Automatically expands your source list over time
- Drive sync to share your profile across devices
- All profile data stored locally - no external database
