# Spoofer Module - Samsung Tab S9 Ultra

## Overview

The **Spoofer Module** modifies any Android device to be recognized as a **Samsung Galaxy Tab S9 Ultra (SM-X916B)**, specifically for games like **Call of Duty Mobile (CODM)**, **PUBG Mobile**, and others. This module alters key system properties to spoof device identification, allowing access to device-specific optimizations or features in these games.

## Features

- **Device Identification Spoofing**: Changes system properties to reflect the Samsung Galaxy Tab S9 Ultra (SM-X916B) model.
- Optimized to work with:
  - **Call of Duty Mobile (CODM)**
  - **PUBG Mobile**
  - Other games and apps that rely on device model identification for access to features or settings.

## Key System Changes

- **Model**: SM-X916B
- **Manufacturer**: Samsung
- **Device**: Galaxy Tab S9 Ultra

Spoofed properties include:
```
ro.product.system.model=SM-X916B
ro.product.model=SM-X916B
```

## Requirements

- **Root Access**: A rooted Android device is required to modify system properties.
- **Magisk (Optional)**: Recommended for easy installation and management.

## Installation

1. **Root your device** if it's not already rooted.
2. **Download the module** from the releases section.
3. **Install via Magisk** (recommended):
   - Open Magisk Manager and go to the "Modules" section.
   - Tap on “Install from storage” and select the downloaded `.zip` file.
   - Reboot your device to apply the changes.

4. **Manual installation** (if not using Magisk):
   - Place the module files in the appropriate `/system` directories.
   - Modify the `build.prop` file with the following lines:
     ```
     ro.product.system.model=SM-X916B
     ro.product.model=SM-X916B
     ```
   - Reboot your device.

## Usage

Once installed and rebooted, your device will be identified as a **Samsung Galaxy Tab S9 Ultra (SM-X916B)** by games like CODM, PUBG, and other apps that check device models for specific features or settings.

## Disclaimer

This module is for educational and testing purposes only. Use at your own risk. Modifying system files can cause instability or unexpected behavior. Always back up your data before making changes.

## Contacts

- [Telegram Channel](https://t.me/rmuxnet)
- [Telegram](https://t.me/mx7111)
