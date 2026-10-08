# DeviceHarbor

Your phone's files and logs, right on your Mac. Plug in an Android phone or an iPhone: copy files both ways, install
APKs, and read each app's logs live — no terminal, no Android File Transfer.

**[Download for Mac](https://github.com/loicsacre/deviceharbor/releases/latest/download/DeviceHarbor.dmg)** ·
[Website](https://loicsacre.github.io/deviceharbor/) · macOS 12 or later · Apple Silicon and Intel · English and French

This repository only hosts the releases.

## Get started

1. Open the DMG and drag DeviceHarbor into Applications.
2. First launch: right-click the app › Open › Open, or System Settings › Privacy & Security › Open Anyway. The app is
   not notarized by Apple, so macOS asks once.
3. On the Android phone (once): Settings › About phone › Software information › tap "Build number" 7 times, then
   Settings › Developer options › turn on "USB debugging".
4. Plug it in and tap "Allow" on the phone.

iPhone: install the libimobiledevice tools once with `brew install libimobiledevice ideviceinstaller`, then plug in,
unlock and tap "Trust".

DeviceHarbor includes `adb` from the Android SDK Platform-Tools; its notices are in
`DeviceHarbor.app/Contents/Resources/platform-tools/NOTICE.txt`.
