# Iris for macOS 👁️✨

<p align="center">
  <img src="docs/app_icon.png" width="128" height="128" alt="Iris macOS App Icon" />
</p>

<p align="center">
  <strong>Native, lightweight macOS break reminder and eye-strain prevention application.</strong><br>
  Protect your eyesight, combat digital eye strain with the 20-20-20 rule, and build mindful work rhythms.
</p>

<p align="center">
  <a href="https://github.com/harshwardhangalande/Iris/releases/latest"><img src="https://img.shields.io/github/v/release/harshwardhangalande/Iris?color=007AFF&style=flat-square" alt="Latest Release"></a>
  <a href="https://github.com/harshwardhangalande/Iris/releases"><img src="https://img.shields.io/github/downloads/harshwardhangalande/Iris/total?color=34C759&style=flat-square" alt="Downloads"></a>
  <img src="https://img.shields.io/badge/platform-macOS%2013.0%2B-lightgrey?style=flat-square" alt="Platform macOS 13+">
  <img src="https://img.shields.io/badge/architecture-Universal%20(Apple%20Silicon%20%26%20Intel)-FF9500?style=flat-square" alt="Architecture Universal">
  <img src="https://img.shields.io/badge/swift-5.9%2B-F05138?style=flat-square" alt="Swift 5.9+">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-Freeware-blue?style=flat-square" alt="License Freeware"></a>
</p>

<p align="center">
  <a href="#-quick-download">Quick Download</a> •
  <a href="#-features">Features</a> •
  <a href="#-screenshots">Screenshots</a> •
  <a href="#-comparison">Comparison</a> •
  <a href="#-faq">FAQ</a> •
  <a href="https://github.com/harshwardhangalande/Iris/releases">Releases</a>
</p>

---

## 🎯 What is Iris?

**Iris** is a lightweight, menu bar resident macOS freeware utility engineered to combat Computer Vision Syndrome (CVS), headaches, and eye fatigue caused by prolonged screen time. 

Built natively in **SwiftUI** and **AppKit** with Apple's Liquid Glass aesthetics, Iris automatically guides you through the scientifically proven **20-20-20 rule**: *every 20 minutes, look at an object 20 feet (6 meters) away for at least 20 seconds*.

Unlike heavyweight Electron alternatives, Iris consumes virtually **zero CPU**, runs entirely without dock clutter (`LSUIElement = true`), respects your privacy with **zero telemetry or analytics**, and integrates deeply with native macOS technologies like **Force Touch Trackpad Haptics**, **IOKit HID Idle Detection**, and **CoreAudio / MediaRemote**.

---

## 📸 Screenshots

| Menu Bar Screen Score & Stats | Menu Bar Resident Now Countdown |
| :---: | :---: |
| <img src="docs/screenshots/popover_stats.png" width="440" alt="Iris Menu Bar Popover with Rainbow Screen Score and Stats" /> | <img src="docs/screenshots/popover_now.png" width="440" alt="Iris Menu Bar Popover Active Work Countdown and Nature Companion" /> |

| Notch Whisper, Swipe Popups & Themes | Full-Screen 20-20-20 Rest Overlay |
| :---: | :---: |
| <img src="docs/screenshots/mascot_showcase.png" width="440" alt="Iris Notch Whisper, Swipeable 2-Second Wellness Habits and Ergonomic Themes" /> | <img src="docs/screenshots/break_overlay.jpg" width="440" alt="Iris Full-Screen 20-20-20 Break Overlay on macOS" /> |

| Scheduled Planned Breaks Editor | Force Touch Trackpad Haptics & Sounds |
| :---: | :---: |
| <img src="docs/screenshots/planned_breaks_editor.png" width="440" alt="Iris Planned Breaks Custom Schedule Editor" /> | <img src="docs/screenshots/haptics_settings.png" width="440" alt="Iris Force Touch Trackpad Haptic Feedback Settings" /> |

---

## ✨ Core Features

### 1. Liquid Glass Menu Bar Popover, Notch Whisper & Animated Screen Score
* **Live Resident Countdown & Hideable Timer**: Displays remaining work time (`18m`) or break duration (`20s`) alongside the monochrome Iris template emblem, with an option in Settings & the gear menu to hide the countdown text.
* **Adaptive Notch Whisper**: Subtle obsidian bezel lip that peeks out smoothly below your MacBook notch (or top-center menu bar) ahead of breaks and on pause resume, expanding on hover with **Rest Now** and **Snooze 5m** controls—and toggleable on/off in Settings.
* **Fluid Sliding Tab Carousel & 4-Node Constellation**: Seamless spring glide between the **Now** view (clickable mascot pet reactions, identity rank, Rest Shield indicator, and 4-node daily **Eyes · Water · Posture · Move** constellation) and the **Stats** dashboard.
* **Animated Rainbow Screen Score Gauge**: Sweeps in with a cascading circular semicircle on opening, styled in the **Biophilic Sage & Hearth Amber** ergonomic palette on low-halation graphite surfaces (`#181C23`) with 5 layout options (*Ring Breakdown*, *Mascot Companion*, *7-Day Sparkline*, *Activity Legend*, *Minimal*).
* **Accurate Ocular Health Calculation & Rest Shields**: Penalties apply strictly for skipped breaks, recovery credits reward completed micro-habits, and **Rest Shields** (plus **Crunch / Weekend Pause**) protect your daily streak from unexpected crunch days.
* **Zero-Overlap Native Glass**: Built with macOS `NSVisualEffectView` behind-window blending and symmetrical card padding matching macOS Ventura, Sonoma & Sequoia.

### 2. Nature Mascots, Companion Sanctuary & Behavioral Psychology
* **5 Unique Nature Companions & 25 Choreographed Emotes**: Choose between **Ollie (Owl)**, **Pip (Tree Frog)**, **Koa (Zen Koala)**, **Barnaby (Bunny)**, and **Finley (Sea Otter)**—each performing **5 unique articulated emotes** across Posture, Water, Blink, Stretch, and Breath popups.
* **Sequential Swipe-to-Dismiss Popups & 2-Second Tiny Habits**: Popups appear one by one without overlap, adapt copy to time of day and focus rhythm, include a frictionless **2s Tiny Win** quick-credit chip (`2s Sip`, `3× Blink`, `Drop Shoulders`, `Quick Reach`, `1 Exhale`), and dismiss cleanly with a **right swipe** on trackpad or mouse.
* **Companion Sanctuary & Reflective Identity**: Completed rests permanently unlock desk habitat props (*Matcha Mug*, *Sage Fern*, *Amber Lamp*, *Horizon Star*, *Zen Cushion*) and advance your Identity Rank (*Mindful Starter* → *Master of Flow*).
* **Eye-Ergonomic Color Themes & Tactile 3D Buttons**: Select between **Sage & Amber** *(Option A default)*, **Indigo & Apricot**, and **Matcha & Iris** palettes, paired with pressable 3D spring buttons and **Peak-End Break Finale** celebrations.
* **Playful / Classic Switcher**: One-click style toggle in Settings to switch between Playful mode and sleek Classic Liquid Glass minimalism.

### 3. 20-20-20 Rest & Long Breaks
* **Short Breaks (20-20-20 Rule)**: Automatically triggers every 20 minutes for 20 seconds with breathing and distance relaxation prompts.
* **Long Rest Cycles**: Configurable longer breaks (e.g. 5 minutes every hour) to stretch, hydrate, and move.
* **Multi-Display Coverage**: Covers all connected external monitors and laptops simultaneously at `.screenSaver` window level.
* **Visual Themes**: Choose between ambient fluid animations (*Aurora Glow*, *Flowing Waves*, *Floating Fireflies*, *Frosted Glass*) or tactile screen-split textures (*Leather*, *Linen*, *Cutting Mat*, *Brushed Metal*).

### 4. Scheduled Planned Breaks
* **Fixed Daily Routines**: Schedule recurring breaks for Gym, Lunch, Dinner, Walks, or Evening Wind Down.
* **Rich Inline Editor**: Customize start times (24h format), durations (5m to 2h), custom SF Symbols, and day-of-week repeat rules (Every Day, Weekdays, Weekends).

### 5. Apple Force Touch Trackpad Haptics
* **Physical Tactile Feedback**: Uses macOS `NSHapticFeedbackManager` to deliver subtle physical sensations directly to your MacBook Force Touch trackpad.
* **Sensory Highlights**:
  * *Break Completion Heartbeat*: Physical latch click (`.alignment`) followed by a gentle secondary echo pulse.
  * *Break Start Snap*: Mechanical snap when entering rest mode.
  * *Final 3-Second Ticks*: Stepping notch clicks (`.levelChange`) on 3, 2, 1 countdown.
  * *Control Taps*: Crisp feedback for buttons, toggles, and date navigation.

### 6. Smart Pause & System Intelligence
* **Meeting & Call Detection**: Automatically pauses break reminders during Zoom, Google Meet, Microsoft Teams, Webex, FaceTime, and Slack calls.
* **Screen Sharing & Recording**: Suppresses prompts when sharing screens via OBS, QuickTime, or conferencing tools.
* **Automatic Video Playback Muting**: Detects active full-screen video playback (YouTube, Netflix, QuickTime, VLC, etc.) and automatically mutes reminder audio to prevent interruptions.
* **Screen Edge Warning Glow**: Displays a gentle ambient edge glow 5s–60s prior to break start with smooth multi-stop gradient falloff.
* **System Idle Detection**: Uses `IOHIDSystem` (`HIDIdleTime`) to detect when you walk away from your desk, automatically pausing and resetting counters upon your return.
* **Automatic Media Pause**: Integrates with macOS MediaRemote to pause music or video on break start, and seamlessly resume when the break finishes.

### 7. Discipline Modes
* **Gentle**: Skip breaks with a single tap or the `Esc` key.
* **Firm**: Enforces a 3-second cooldown before skipping (plus configurable Double-`Esc` skip/snooze action) to prevent accidental or impulsive skips.
* **Strict**: Unskippable break screen with emergency exit (`⌘⇧Esc`) only.

### 8. Compact Swipeable Wellness Popups & 2s Tiny Habits
* One-by-one sequential, compact, tick-free micro-reminders for **Posture Correction**, **Drinking Water**, **Eye Blinking**, **Stretching**, and **Deep Breathing**, starring all 5 mascots with 25 bespoke animated emotes.
* **Right-Swipe to Dismiss & 2-Second Tiny Habits**: Tap anywhere on a popup pill to complete, swipe right to dismiss previews, or tap the compact habit chip (`2s Sip`, `3× Blink`, `Drop`, `Reach`, `Exhale`) for instant wellness credit.
* **Custom Screen Positioning**: In-app vertical (2% to 90%) and horizontal position sliders with smooth, unclipped ambient bloom.

---

## 📊 Feature Comparison

| Feature | Iris (Freeware) | LookAway ($19-$29) | Time Out | Generic Pomodoro |
| :--- | :---: | :---: | :---: | :---: |
| **Price** | **100% Free for Personal Use** | Commercial / Paid | Freemium | Free / Paid |
| **Native macOS Architecture** | **SwiftUI + AppKit (Universal)** | Swift | Swift | Often Electron |
| **Force Touch Trackpad Haptics** | **Yes (Heartbeat, ticks, snaps)** | No | No | No |
| **Liquid Glass Menu Bar UI** | **Yes (Sonoma/Sequoia blur)** | Yes | No | No |
| **Adaptive Notch Whisper** | **Yes (Hover Expand + Toggle)** | No | No | No |
| **Swipe Popups & 25 Mascot Emotes** | **Yes (5 Companions + Sanctuary)** | No | No | No |
| **Rest Shields & Ergonomic Palettes** | **Yes (3 Palettes + Peak-End Finale)** | No | No | No |
| **Multi-Display Fullscreen Overlay** | **Yes** | Yes | Yes | Rarely |
| **Meeting & Screen Share Auto-Pause** | **Yes** | Yes | Partial | No |
| **Hardware HID Idle Detection** | **Yes** | Yes | Yes | No |
| **Planned Scheduled Breaks** | **Yes (Gym, Lunch, Wind Down)** | Yes | No | No |
| **Telemetry & Tracking** | **Zero (100% Offline)** | Proprietary | Proprietary | Varies |

---

## 📥 Quick Download

### Option 1: Homebrew (Recommended)
```bash
brew install --cask harshwardhangalande/iris/iris
```

### Option 2: DMG Installer
Download the latest disk image from the [Releases Page](https://github.com/harshwardhangalande/Iris/releases/latest):
* ⬇️ **[Download Iris-v3.0.0.dmg](https://github.com/harshwardhangalande/Iris/releases/download/v3.0.0/Iris-v3.0.0.dmg)**
* Open the DMG and drag **Iris** to your **Applications** folder.

### Option 3: Direct Zip
* ⬇️ **[Download Iris-v3.0.0.zip](https://github.com/harshwardhangalande/Iris/releases/download/v3.0.0/Iris-v3.0.0.zip)**
* Extract and move `Iris.app` into `/Applications`.

### Option 4: Terminal One-Liner
```bash
TMPDIR_IRIS=$(mktemp -d) && MNT_IRIS=$(mktemp -d) && \
curl -fsSL "https://github.com/harshwardhangalande/Iris/releases/download/v3.0.0/Iris-v3.0.0.dmg" -o "$TMPDIR_IRIS/Iris.dmg" && \
hdiutil attach "$TMPDIR_IRIS/Iris.dmg" -nobrowse -mountpoint "$MNT_IRIS" && \
cp -R "$MNT_IRIS/Iris.app" "/Applications/" && \
hdiutil detach "$MNT_IRIS" && rm -rf "$TMPDIR_IRIS" "$MNT_IRIS"
```

---

## ❓ Frequently Asked Questions (FAQ)

### What is the 20-20-20 rule and why does it help prevent eye strain?
The 20-20-20 rule is an optometry guideline recommended by the American Academy of Ophthalmology: every 20 minutes spent looking at a digital screen, look at an object at least 20 feet away for at least 20 seconds. Looking into the distance allows the ciliary muscles in your eyes to completely relax, preventing dry eyes, blurred vision, headaches, and computer fatigue.

### How does Iris differ from standard Pomodoro timers?
Standard Pomodoro apps focus strictly on 25-minute productivity sprints and task management. Iris is specifically engineered for **ocular health and ergonomics**: it enforces rapid 20-second distance-focus breaks, offers micro-reminders to blink and hydrate, monitors camera/mic activity to avoid interrupting client meetings, and calculates a personalized daily Eye Health Score.

### Does Iris work across multiple monitors?
Yes. Iris automatically detects all active screens, including built-in Retina displays, external 4K/5K monitors, and Sidecar iPads, presenting synchronous relaxation overlays across all connected displays simultaneously.

### Does Iris consume battery or run heavy background processes?
No. Iris is written in pure native Swift with no web wrappers (Electron/Chromium). When not in a break, Iris is purely event-driven and draws virtually 0.0% CPU, making it battery-friendly for MacBook users on the go.

### Is my activity tracked or sent to the cloud?
No. Iris operates 100% locally on your machine. All settings and eye health scores are stored locally in macOS `UserDefaults`. No network requests are made, no user analytics are collected, and no accounts are required.

---

## 🤝 Feedback & Community
Feature suggestions, feedback, and bug reports are warmly welcome!
* Submit bug reports and feature requests on [GitHub Issues](https://github.com/harshwardhangalande/Iris/issues).
* Join discussions and share feedback on [GitHub Discussions](https://github.com/harshwardhangalande/Iris/discussions).

---

## 📄 License & Distribution
Iris for macOS is distributed freely for personal use as a compiled binary application.

**Copyright © 2026 Harshwardhan Galande. All rights reserved.**  
Unauthorized commercial distribution, repackaging, resale, or publishing on third-party app stores without express prior written consent is strictly prohibited.
