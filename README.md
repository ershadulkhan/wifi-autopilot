# Wi-Fi Autopilot

Switches between Wi-Fi and mobile data on Android phones by itself.

- Leave Wi-Fi: Wi-Fi turns off, mobile data turns on.
- Reach a saved Wi-Fi: Wi-Fi turns on, mobile data turns off.
- Keeps working after restarts and is light on battery.
- No accessibility service, so it works alongside bKash and other banking apps.

## Download

**[Download the latest APK](https://github.com/ershadulkhan/wifi-autopilot/releases/latest/download/WifiAutopilot.apk)**

Open the file on your phone and tap **Install** (or **Update**). The app walks you through the one-time setup.

## How this repository works

`WifiAutopilot.zip` holds the app's source code. Every time a new zip is uploaded, GitHub Actions builds the APK and publishes it on the [Releases](https://github.com/ershadulkhan/wifi-autopilot/releases) page. The download link above always gives the newest build.

To publish a new version: **Add file → Upload files**, choose the new `WifiAutopilot.zip`, then **Commit changes**.

Personal-use app, not on Google Play. Made by Md Ershadul Haque Khan.
