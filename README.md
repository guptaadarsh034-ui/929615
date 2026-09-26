# YT Web Wrapper (Retro / Lightweight Edition)

A minimalist, ultra-lightweight Android WebView wrapper for YouTube, optimized specifically for older devices, low memory (512MB RAM), and legacy Android versions (Android 4.4 KitKat+).

---

## Features

- **Ultra Lightweight:** Minimal APK size and tiny memory footprint.
- **Legacy Compatibility:** Target `minSdkVersion 19` (Android 4.4 KitKat).
- **RAM Optimization:** Automatic cache trimming on low-memory triggers.
- **Ad & Bloat Free Architecture:** Simple native WebView container without extra background services.

---

## Building from Source

This project uses Gradle and can be built easily using GitHub Actions or locally.

### Local Build Commands
```bash
./gradlew assembleDebug
