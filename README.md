# Prayer Times, Athan & Islamic Reminders for Obsidian

A full-featured Obsidian plugin that provides **accurate prayer times**, **Athan playback**, **Hijri calendar**, **fasting alerts**, and **daily Islamic reminders**, designed to work reliably on both **desktop and Android**.

This plugin is built for users who want prayer awareness inside their knowledge system, without relying on external apps.

---

## Features

### Prayer Times
- Fetches prayer times using the **AlAdhan API**
- Supports **named calculation methods** (e.g. Algeria, Umm Al-Qura, ISNA, MWL)
- Displays:
  - Fajr, Dhuhr, Asr, Maghrib, Isha
  - Sunrise
  - Midnight
  - Last third of the night
- Offline fallback using **cached prayer times**

---

### Athan & Notifications
- Full Athan playback at prayer time
- **Pre-Athan reminder** (user-defined minutes before prayer)
- Separate custom sounds for:
  - Athan
  - Pre-Athan notification
  - Iqama
- Automatic fallback to Athan sound if a custom sound is not provided
- Desktop notices + mobile system notifications

---

### Iqama Support
- User-defined Iqama delay (minutes after prayer)
- Optional custom Iqama sound per prayer

---

### Status Bar Widget (Desktop)
- Displays:
  - Hijri date
  - Next prayer
  - Live countdown
- Automatically updates every 30 seconds
- Desktop-only (Obsidian limitation)

---

### Prayer Panel (Mobile & Desktop)
- Dedicated in-app panel (Option B)
- Works on Android and desktop
- CSS-styled UI with:
  - Highlighted current and next prayer
  - Live countdown
  - Swipe-friendly layout
  - Dark / light theme adaptation

---

### Hijri Calendar
- Accurate Hijri date from AlAdhan
- Used across:
  - Status bar
  - Prayer panel
  - Notifications

---

### Fasting Features
- Custom fasting alerts with user-defined sound
- Choose fasting days by:
  - Day of week (e.g. Monday / Thursday)
  - Hijri dates (e.g. 13th of every Hijri month)
- Alert timing relative to a prayer:
  - Before or after a selected prayer

---

### Islamic Reminders (Built-in)
Three ready-made reminder systems:
1. **Morning supplication**
   - Before or after sunrise
2. **Evening supplication**
   - Before sunset or after Asr
3. **Night supplication**
   - After Isha

Each reminder supports:
- Custom audio file
- Time offset configuration

---

### Reliability (Especially on Android)
- Background-safe scheduling
- Duplicate trigger prevention
- Notification-based fallback when background audio is restricted
- Single scheduler, single source of truth

---

## Configuration

All settings are available under:

You can configure:
- Location (city / country)
- Calculation method (named list)
- Enabled prayers
- Notification timings
- Audio file paths
- Fasting days and alerts
- Reminder schedules

---

## Known Limitations

- Status bar widget is **not available on mobile** (Obsidian limitation)
- Background audio on Android depends on OS policies
- iOS background execution is limited by the platform

---

## Roadmap (Possible Extensions)

- Per-note prayer triggers
- Localization (Arabic / French)
- Multiple Athan profiles
- Prayer analytics in daily notes
- Persistent Android notification widget

---

## Philosophy

This plugin is designed to be:
- Transparent
- Configurable
- Respectful of religious practice
- Technically robust

---

## Installation

### Manual Installation
1. Download or clone this repository
2. Place it in:
3. Enable the plugin from:

### Requirements
- Obsidian `≥ 1.5.0`
- Internet connection for initial prayer time fetch
- Audio files must be stored inside the vaul

# Support me
> Pray for me that I may be well and guided.
