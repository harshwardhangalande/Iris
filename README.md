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

**Iris** is an open-source, menu bar resident macOS utility engineered to combat Computer Vision Syndrome (CVS), headaches, and eye fatigue caused by prolonged screen time. 

Built natively in **SwiftUI** and **AppKit** with Apple's Liquid Glass aesthetics, Iris automatically guides you through the scientifically proven **20-20-20 rule**: *every 20 minutes, look at an object 20 feet (6 meters) away for at least 20 seconds*.

Unlike heavyweight Electron alternatives, Iris consumes virtually **zero CPU**, runs entirely without dock clutter (`LSUIElement = true`), respects your privacy with **zero telemetry or analytics**, and integrates deeply with native macOS technologies like **Force Touch Trackpad Haptics**, **IOKit HID Idle Detection**, and **CoreAudio / MediaRemote**.

---

## 📸 Screenshots

| Menu Bar Screen Score & Stats | Menu Bar Resident Now Countdown |
| :---: | :---: |
| <img src="docs/screenshots/popover_stats.png" width="440" alt="Iris Menu Bar Popover with Rainbow Screen Score and Stats" /> | <img src="docs/screenshots/popover_now.png" width="440" alt="Iris Menu Bar Popover Active Work Countdown and Nature Companion" /> |

| Unified 5-in-1 Mascot Popups | Full-Screen 20-20-20 Rest Overlay |
| :---: | :---: |
| <img src="docs/screenshots/mascot_showcase.png" width="440" alt="Iris Nature Mascot Companions with Unified 5-in-1 Wellness Popups" /> | <img src="docs/screenshots/break_overlay.jpg" width="440" alt="Iris Full-Screen 20-20-20 Break Overlay on macOS" /> |

| Scheduled Planned Breaks Editor | Force Touch Trackpad Haptics & Sounds |
| :---: | :---: |
| <img src="docs/screenshots/planned_breaks_editor.png" width="440" alt="Iris Planned Breaks Custom Schedule Editor" /> | <img src="docs/screenshots/haptics_settings.png" width="440" alt="Iris Force Touch Trackpad Haptic Feedback Settings" /> |

---

## ✨ Core Features

### 1. Liquid Glass Menu Bar Popover & Animated Screen Score
* **Live Resident Countdown**: Displays remaining work time (`18m`) or break duration (`20s`) directly in the macOS menu bar.
* **Fluid Sliding Tab Carousel**: Seamless spring glide between the resident **Now** countdown and detailed **Stats** dashboard, with a locked segmented control indicator and synchronized direction-aware sliding content.
* **Animated Rainbow Screen Score Gauge**: Sweeps in with a cascading circular semicircle on opening, featuring live real-time score count-up, multi-arc health breakdown, and ambient neon glow.
* **4 Interchangeable Flanking Layouts**: Personalize your Stats tab in Settings with:
  * 📊 **7-Day Sparkline**: Daily volume trend bars with rolling 7-day average and personal best.
  * 🐨 **Companion Buddy**: Active mascot character avatar with daily motivational wellness wisdom.
  * 🌈 **Arc Breakdown**: Dual concentric gauge arcs displaying Break Compliance and Daily Wellness ratio.
  * 🏷️ **Legend Grid**: Color-coded score category index (Optimal, Good, Moderate, High Strain).
  * 🎯 **Minimal**: Pure focus on the central circular rainbow gauge.
* **Accurate Ocular Health Calculation**: Penalties are deducted strictly for skipped breaks with recovery credits awarded for completed wellness micro-habits—eliminating misleading 100% scores.
* **Symmetrical 16pt Card Border Padding**: Balanced, uniform padding across both Now and Stats tabs for a clean, native macOS look.
* **Zero-Overlap Native Glass**: Built with macOS `NSVisualEffectView` behind-window blending for blur and depth matching macOS Sonoma & Sequoia.

### 2. Nature Mascots & Playful Mode
* **5 Unique Nature Companions**: Choose your favorite desk buddy in Settings:
  * 🦉 **Ollie the Owl**: Wise, observant guide with expressive animated blinks and encouraging glances.
  * 🐸 **Pip the Tree Frog**: Cheerful, vibrant companion with leafy accents and gentle bouncing idle poses.
  * 🐨 **Koa the Zen Koala**: Calm eucalyptus lover reminding you to breathe, relax your jaw, and un-clench.
  * 🐰 **Barnaby the Bunny**: Curious and energetic friend celebrating every micro-habit completion.
  * 🦦 **Finley the Sea Otter**: Playful swimmer with aquatic micro-expressions cheering you through work sprints.
* **Unified 5-in-1 Mascot Popups**: Selecting any character immediately presents all 5 wellness reminders together (Posture, Water, Blink, Stretch, and Breath) in a tactile 3D card stack tailored to that character with custom emoji badges and accessory titles (`SPINE ALIGN`, `OWL HYDRATE`, `LILYPAD POISE`, `ZEN TEA`, `PERK EARS`, `SEA SPLASH`).
* **In-Settings Character Showcase**: Interactive character switcher cards with real-time mood expression tester (*Idle*, *Break*, *Celebrate*, *Sleepy*) and a unified 5-card popup preview gallery.
* **Pressable 3D Tactile Buttons**: Chunky, rounded buttons with physical spring depth and haptic depress on click.
* **Daily Streaks & Milestone Celebrations**: Flame counter tracking consecutive days of eye care discipline, daily break goals, and full-screen confetti bursts upon break completion.
* **Playful / Classic Switcher**: One-click style toggle in Settings to switch between tactile Playful visuals and sleek Apple Liquid Glass minimalism.

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
* **Firm**: Requires holding the skip button for 3 seconds to prevent accidental or impulsive skips.
* **Strict**: Unskippable break screen ensuring full eye relaxation.

### 8. Floating Wellness HUD Reminders
* Micro-reminders for **Blinking**, **Drinking Water**, **Deep Breathing**, and **Posture Correction**.
* Five physical animation styles: *Playful Mascot Bounce*, *Liquid Glass Pill*, *Glowing Glass Orb*, *Hold-to-Complete*, and *Combined Stack*.
* **Custom Screen Positioning**: In-app vertical (2% to 90%) and horizontal position sliders with smooth, unclipped ambient bloom.

---

## 📊 Feature Comparison

| Feature | Iris (Free & Open Source) | LookAway ($19-$29) | Time Out | Generic Pomodoro |
| :--- | :---: | :---: | :---: | :---: |
| **Price** | **100% Free & Open Source** | Commercial / Paid | Freemium | Free / Paid |
| **Native macOS Architecture** | **SwiftUI + AppKit (Universal)** | Swift | Swift | Often Electron |
| **Force Touch Trackpad Haptics** | **Yes (Heartbeat, ticks, snaps)** | No | No | No |
| **Liquid Glass Menu Bar UI** | **Yes (Sonoma/Sequoia blur)** | Yes | No | No |
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
* ⬇️ **[Download Iris-v2.0.0.dmg](https://github.com/harshwardhangalande/Iris/releases/download/v2.0.0/Iris-v2.0.0.dmg)**
* Open the DMG and drag **Iris** to your **Applications** folder.

### Option 3: Direct Zip
* ⬇️ **[Download Iris-v2.0.0.zip](https://github.com/harshwardhangalande/Iris/releases/download/v2.0.0/Iris-v2.0.0.zip)**
* Extract and move `Iris.app` into `/Applications`.

### Option 4: Terminal One-Liner
```bash
curl -sL "https://github.com/harshwardhangalande/Iris/releases/download/v2.0.0/Iris-v2.0.0.dmg" -o "/tmp/Iris.dmg" && \
hdiutil attach "/tmp/Iris.dmg" -nobrowse -mountpoint "/Volumes/Iris" && \
cp -R "/Volumes/Iris/Iris.app" "/Applications/" && \
hdiutil detach "/Volumes/Iris" && rm "/tmp/Iris.dmg"
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
