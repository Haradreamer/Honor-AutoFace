# 🟣 AutoFace

**Haradreamer Tools · Android · No root**

[🇬🇧 English](README.md) · [🇷🇺 Русский](README.ru.md) · [📥 Download](../../releases/latest)

**Automatically confirms successful face recognition on supported HONOR phones.**

AutoFace is a small, free Android utility made by **Haradreamer**. On some HONOR phones, successful face recognition is followed by an extra **OK / Confirm** button. AutoFace detects the supported HONOR system confirmation window and presses that button for you.

It **does not perform or bypass biometric authentication**. The phone must recognize your face first.

## 📥 Download

**Version: 2.0.2** (Android APK)

**[Download AutoFace 2.0.2](../../releases/latest)** **Do not download modified APKs from unofficial mirrors.**

> This repository is for official binary distribution and documentation. Source code and signing keys are kept in a separate private development repository.

## ✨ Features

- Automatically taps the confirmation button after supported HONOR face recognition succeeds.
- Adjustable additional delay: **0–100 ms** (default **10 ms**).
- Light, dark, and system appearance.
- App language selection at first launch and later in Settings.
- Languages: **Russian, English, Simplified Chinese, Spanish, Brazilian Portuguese, Arabic, Turkish, Indonesian**, plus automatic system-language selection.
- No root, ADB, account, or internet permission needed.
- Local-only processing, with an on-device action counter.

## 📱 Compatibility

**Tested:** HONOR Magic9 Pro Max (WKL-AN20), MagicOS 11.

Other HONOR phones displaying the same system confirmation screen may work, but are **not yet verified**. HUAWEI / EMUI / HarmonyOS compatibility is **unverified**. Please report your model and firmware if you test them.

## ⚙️ Installation

1. Download the **signed APK** from GitHub Releases and install it.
2. Launch AutoFace and select your language.
3. Review the explanation of the Accessibility permission.
4. Open **Accessibility settings** from AutoFace and enable its service.
5. Return to the app and enable automatic confirmation.
6. Optionally configure App launch management and Battery optimization for reliability.

### Accessibility toggle is disabled?

Some HONOR / MagicOS versions restrict Accessibility access for sideloaded apps.

1. Tap the unavailable AutoFace toggle and dismiss the system warning.
2. Open **Settings → Apps → App management → AutoFace**.
3. Find **Allow restricted settings** (wording/location varies by MagicOS version) near the top of its app information page and enable it.
4. Return to Accessibility settings and enable AutoFace.

**Security note:** Accessibility can inspect accessible screen contents and perform touches. Only grant this powerful permission if you trust the APK and its source. This is an Android safeguard, not a step you should take for unknown apps.

## 🔐 Privacy & security

AutoFace does not request the Android **INTERNET** permission. Recognition checks, confirmations, and the diagnostic counter are performed locally. It does not capture, store, or transmit facial biometric data; face recognition is performed by the HONOR operating system.

AutoFace uses Android's AccessibilityService specifically to detect a supported system confirmation window and press its confirmation control. It cannot guarantee compatibility with every firmware or lock-screen implementation.

Release updates are signed using the same dedicated signing key to permit in-place upgrades. Never publish or share signing keys or passwords.

## 💬 Feedback

For a compatibility report or bug, please open a [GitHub Issue](https://github.com/Haradreamer/Honor-AutoFace/issues) with:

- Phone model and region (CN / global).
- MagicOS / EMUI / HarmonyOS version.
- AutoFace version.
- Whether face recognition completes and an OK button appears.
- What happens when AutoFace is enabled (screenshots if helpful).

**Independent project. Not affiliated with HONOR or HUAWEI.**

## 🌐 Other Haradreamer Tools projects

- 🔵 [Isle](https://github.com/Haradreamer/Isle-HONOR-app) — Magic Capsule & AOD
- 🟢 [MagicOS CN Tool](https://github.com/Haradreamer/Honor-Tools-CN) — HONOR configuration
- 🟠 [Magic Hub](https://github.com/Haradreamer/Magic-Hub-app) — Google gestures

## 💬 Community & support

[Telegram](https://t.me/isle_universal) · [4PDA](https://4pda.to/forum/index.php?showtopic=1119615&view=findpost&p=145819882) · [Report a bug](../../issues) · [Boosty](https://boosty.to/haradreamer)

Free independent project. Support is voluntary. Not affiliated with HONOR, HUAWEI or Google.

**Haradreamer**
