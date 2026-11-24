# Trackpad Buddy

Trackpad Buddy is a macOS menu bar app that prevents accidental pointer input while you type. After every keystroke, trackpad and mouse input is suppressed for a short time window, so a stray palm brush can’t move the cursor, click, or scroll in the middle of your typing. The moment the time expires, your pointer works normally again.

## Download

Get the latest **Trackpad-Buddy-x.y.dmg** from the [Releases](https://github.com/stevescherf/Trackpad-Buddy-Releases/releases/latest) page.

**Requires macOS 14.6 or later.** The app is signed with Developer ID and notarized by Apple.

## Install

1. Open the downloaded DMG.
2. Drag **Trackpad Buddy** onto the **Applications** folder.
3. Launch Trackpad Buddy from Applications. It appears as a trackpad icon in the menu bar.
4. Grant Accessibility access when prompted: **System Settings → Privacy & Security → Accessibility**, then turn on Trackpad Buddy. macOS requires this before any app can filter input.

Left-click the menu bar icon for options; right-click it for the menu. Turn on **Launch at Login** in the options to start it automatically.

## Options

- **Disable pointer for** — how long pointer input stays blocked after each keystroke (0.1–2.0 seconds).
- **Suppress** — *Mouse Clicks* blocks clicks and drags only; *All Pointer Input* also freezes the cursor and blocks scrolling.
- **Disable Trackpad Buddy** — pause blocking without quitting.

## Uninstall

1. Right-click the menu bar icon and choose **Quit Trackpad Buddy**.
2. Delete **Trackpad Buddy** from the Applications folder.
3. Optionally, remove it from **System Settings → Privacy & Security → Accessibility** (select it and click **−**).
