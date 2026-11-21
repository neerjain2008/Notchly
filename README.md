<div align="center">

<img src="assets/icon.png" width="128" height="128" alt="Notchly Icon" style="border-radius: 28px; box-shadow: 0 16px 36px rgba(0,0,0,0.4);" />

# Notchly

**A native macOS Dynamic Island, desktop constellation lyric visualizer, and daily-driver utility.**

[![macOS 13+](https://img.shields.io/badge/macOS-13.0%2B%20(Ventura%2C%20Sonoma%2C%20Sequoia)-black?style=for-the-badge&logo=apple)](https://www.apple.com/macos/)
[![Apple Silicon & Intel](https://img.shields.io/badge/Universal%20Binary-Apple%20Silicon%20%2F%20Intel-blue?style=for-the-badge)](https://www.apple.com)
[![Privacy First](https://img.shields.io/badge/Privacy-Zero%20Microphone%20Access-emerald?style=for-the-badge)](https://github.com/neerjain2008/Notchly)

<br/>

### [⬇️ Download Notchly v1.0 (.dmg)](https://github.com/neerjain2008/Notchly/releases/latest)

<br/>

![Notchly Desktop](assets/preview.png)

</div>

---

## 🌟 The Ultimate Music & Notch Companion for Mac

**Notchly** transforms your MacBook's hardware camera notch into a fluid, ambient Dynamic Island and brings your desktop to life with live constellation lyrics and sound-reactive edge lighting. Crafted purely in Swift & SwiftUI for high-performance macOS workflows, it operates with zero impact on battery life and respects your privacy with strictly local system audio capture.

---

## ✨ Features

### 🏝️ Notch-Hugging Dynamic Island
* **Seamless Bezel Silhouette**: Hugs the physical camera notch on 14" & 16" MacBook Pro and MacBook Air displays, reserving the hardware cutout with zero occlusion.
* **Fluid Spring Expansion**: Hover over the notch or press <kbd>⌥ Option</kbd> + <kbd>N</kbd> to reveal a rich 480pt media console with full playback controls, interactive track scrubbing, and volume/brightness sliders.
* **Smart Album Artwork**: Displays high-resolution square album artwork in the expanded notch, an animated spinning vinyl record in the collapsed notch wing, and a fallback music badge when offline.

### ⚡ Real-Time Beat Edge Glow
* **System-Audio Beat Detection**: Analyzes live system audio output in real-time via `ScreenCaptureKit` to pulse vibrant ambient light around your display's edges.
* **Zero Microphone Access Required**: Operates strictly on system audio output—Notchly **never** requests or accesses your physical microphone.
* **Adaptive Color Harmony**: The edge glow palette automatically adapts to the vibrant dominant colors of the song currently playing.

### 🌌 Desktop Constellation Lyrics
* **Wallpaper-Layer Star Visualizer**: Projects synchronized lyrics directly over your desktop wallpaper as glowing star nodes connected by delicate constellation lines.
* **High-Contrast Typography**: The active singing word illuminates in a bold 34pt glow with a protective dark text shadow for effortless readability over bright or detailed wallpapers.
* **Smart Title & Lyric Resolution**: Automatically cleans up title clutter (such as Bollywood/soundtrack tags and remastered suffixes) and searches lrclib.net with automatic local caching for instantaneous 0ms repeat loads.
* **60fps Interpolation**: Uses high-precision local time interpolation between playback syncs for butter-smooth word transitions without AppleScript lag.

### 💽 Draggable Desktop Turntable
* **Retro Desktop Vinyl Platter**: A vintage vinyl record player widget anchored to your desktop layer.
* **Interactive & Movable**: Drag the turntable anywhere on your screen; click the spinning record to toggle play and pause.
* **Rotating Album Label**: Center label features the active track's cover art and rotates at a realistic 33⅓ RPM with an animated metallic tonearm.

### 🗂️ Notch File Shelf
* **Instant Drag-and-Drop Holding Area**: Drag any file, screenshot, or URL up to the notch to automatically expand the Dynamic Island and store the item in a temporary shelf.
* **Fast Multi-App Workflow**: Easily drag files back out into Mail, Slack, Discord, or Finder, open them directly, or clear the shelf with a single click.

### ⏱️ 25-Minute Focus Timer
* **Built-in Pomodoro Mode**: Start, pause, and reset 25-minute focus sessions directly from the expanded notch.
* **Glanceable Wing Badge**: Displays a discrete live countdown timer (`24:15`) in the collapsed notch wing while you work.

### 🔋 MagSafe & Battery HUD
* **Charging Alerts**: Displays a subtle MagSafe-style HUD banner (`⚡ Charging • 84%`) beneath the camera notch whenever AC power is connected or disconnected.
* **AirPods & Bluetooth Level**: Shows connected headphone names and real-time battery percentages automatically.

---

## ⌨️ Global Keyboard Shortcuts

Control your media system-wide from any app or fullscreen workspace:

| Shortcut | Action | Description |
| :--- | :--- | :--- |
| <kbd>⌥ Option</kbd> + <kbd>Space</kbd> | **Play / Pause** | Toggle playback in Spotify, Apple Music, or Browser media |
| <kbd>⌥ Option</kbd> + <kbd>→</kbd> | **Next Track** | Skip to the next song |
| <kbd>⌥ Option</kbd> + <kbd>←</kbd> | **Previous Track** | Return to the previous song or restart current track |
| <kbd>⌥ Option</kbd> + <kbd>N</kbd> | **Toggle Notch** | Instantly expand or collapse the Notchly Dynamic Island |

---

## 🎧 Supported Music Sources

* **Spotify** (Desktop App)
* **Apple Music**
* **Safari & Google Chrome** (YouTube & YouTube Music tabs)

---

## 📥 Quick Installation (macOS 13+)

1. **Download Notchly**: Grab the latest **[Notchly.dmg](https://github.com/neerjain2008/Notchly/releases/latest)** installer.
2. **Install**: Open `Notchly.dmg` and drag the **Notchly** app icon into your **Applications** folder.
3. **First Launch (Gatekeeper)**:
   * Because Notchly is independently distributed, **Right-Click** (or Control-click) `Notchly.app` in `/Applications` and select **Open**.
   * Click **Open** in the macOS confirmation dialog. (You only need to do this once).
4. **Grant Audio Permission for Beat Glow**:
   * On first launch or when toggling Beat Glow, macOS will request **Screen & System Audio Recording** access.
   * Open **System Settings → Privacy & Security → Screen & System Audio Recording** and toggle **Notchly** to **ON**.
   * *Note: Notchly uses this permission exclusively to capture system audio output for the edge visualizer. It never records your screen video or uses your microphone.*
5. **Start Listening**: Play any track in Spotify, Apple Music, or YouTube and watch Notchly come alive!

---

<div align="center">

Built by **Neer Jain** ([@neerjain2008](https://github.com/neerjain2008)) • All Rights Reserved.

</div>
