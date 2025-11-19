# DataDumper
Extract app data without root access using Shizuku.

## How It Works
1. **Select any debuggable app** from your device
2. **Choose export folder** to save the data
3. **Dump app data** into a ZIP file

## Requirements

- [Shizuku](https://github.com/RikkaApps/Shizuku) installed and running
- Debuggable apps

## Screenshots


## Setup

1. Install and start [Shizuku](https://shizuku.rikka.app/)
2. Open DataDumper and grant Shizuku permission
3. Start dumping app data

## Usage

1. Tap **SELECT APP** → Choose a debuggable app
2. Tap **SELECT EXPORT FOLDER** → Pick save location  
3. Tap **DUMP APP DATA** → Extract files to ZIP

Output: `package_name_version_timestamp.zip`

## Make Any App Debuggable 🔓

You can modify apps to add debugging support:
- Add `android:debuggable="true"` to the `<application>` tag in AndroidManifest.xml
- Repack and reinstall the modified APK
- App will appear in DataDumper's list

## Use Cases

- Extract runtime-generated files
- Backup app data without root

Made with fun 😅