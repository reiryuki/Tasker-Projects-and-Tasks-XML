# Tasker Projects and Tasks XML

## Descriptions
- My Tasker XML projects and tasks that can be imported to your Tasker app
- Package Information: Monitors application changes. It shows a toast notification whenever an application is installed or uninstalled, providing real-time data on the app name and package name of the affected app.
- Auto Backup: This project automatically manages backups for Tasker data. It monitors the currently active application; if it detects that you are not using Tasker, it triggers a backup to a designated path. It also includes an interactive dialogue for you to set or update your email address for cloud-based backup purposes.
- Auto Brightness: This project provides an intelligent screen brightness management system. It uses the device's light sensor to trigger automatic brightness adjustments. When the ambient light is high, it activates automatic settings; when it is dark, it switches to manual brightness control.
- Battery Alarms: This is a comprehensive battery management system consisting of several modules:
  - Battery Low: Triggers an audio alert when battery levels drop below 15%.
  - Battery Level 100/Full: Notifies the user and plays audio when the battery reaches 100%.
  - Alarm Clock Sahur (in my case): Sets a specialized alarm for the Sahur period then stops the Battery Alarm to prevent conflict.
  - Battery Overheating: Alerts the user if the battery temperature exceeds safe limits.
  - Turn Off Hotspot: Automatically disables the hotspot at midnight to conserve power.
- Connection: This project ensures network stability. It monitors WiFi and Bluetooth states and provides notifications if no active connection is found. Additionally, it features a mechanism to store and attempt to reconnect to previously paired Bluetooth devices.
- Daily Al-Qur-an Verses: This project serves as a daily spiritual suggestion. It randomly selects a chapter (Surah) and verse (Ayat) from the Quran and displays them in a popup scene on your screen.
- Location Mode: This project provides a dashboard via a notification overlay, allowing you to quickly switch between different location modes (High Accuracy, Battery Saving, Device Only, or Off) without opening the system settings.
- Enable Location Mode: This project enables Mobile Data, Location Mode High Accuracy, WiFi scan and Bluetooth scan automatically if a message "enable location mode" (ignore case) is received e.g. SMS.
- Notification Button Overlay: This project adds a floating action button to the screen edge for spesific Launchers if the recents provider is not activated. It is highly interactive: a single tap or swipe gesture expands status bar, a long press changes the button's position (left or right).
- Screenshot: This is a utility for capturing screenshots via Android's Quick Settings. Upon activation, it uses the Accessibility service to capture the screen content and saves the file with a timestamp in the Pictures/Screenshots directory. This can be another solution if an app does not allow screenshots.
- Smule Mic Toggler: Designed specifically for the Smule app, this project adds a floating overlay while Smule is active. It provides a quick toggle to mute or unmute the microphone during singing sessions and manages the required system permissions for audio control.
- Trading Notification: This project is designed for market monitoring. It tracks the TradingView app and provides periodic notifications based on various time frames (1h, 5m, 15m, 4h). It allows you to quickly navigate to the trading app or the configuration menu to adjust settings.
- TriChromeLibrary: This is a maintenance utility for system updates. When it detects an update for Chrome or WebView, it triggers a root-level script to copy the updated TriChrome Library files to a backup location to ensure your system components are safely preserved.

## Changelog

Battery Alarms
v1.2-R2
- Fix Bugs
v1.1
- Improvements

Package Information
v0.1
- Initial release

Auto Backup
v0.2
- Add email input dialog
v0.1
- Initial release

Auto Brightness
v0.3
- Improvements
v0.2
- Improvements

Trading Notification
v0.2
- Add some specifications
v0.1
- Initial release

Daily Al-Qur-an Verses
v1.1
- English
v1.0
- Initial release

Enable Location Mode
v1.1
- Triggers "enable location mode" messages in ignore case
v1.0
- Initial release

Notification Button Overlay
v0.3
- Fix bugs
v0.2
- Fix wrong variable in If No Moto Launcher Recents task

Screenshot
v0.1
- Initial release

Connection
v1.1
- Improvements

Location Mode
v1.1
- Improvements

Smule Mic Toggler
v0.2
- Improvements

TriChromeLibrary
v1.2
- Fix bugs
v1.1
- Simplify
- Android 11 support

## Requirements
Paid Tasker app installed as user app: https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm

## Installation Guide & Download Link
- Install paid Tasker app first at Play Store: https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm
- Download https://devuploads.com/d5bj6ul115gs, extract, and copy the XML files: Ensure the project file (e.g., .prj.xml file) is saved in the internal storage of your device. It is recommended to place it in the Tasker/projects folder for easier access.
- Open Tasker: Launch the Tasker application.
- Import the project: 
  - On the bottom bar, look for the Project tabs (represented by icons).
  - Long-press on an existing Project tab (or on an empty space if you want to create a new one).
  - Select Import from the menu that appears.
- Locate the file: A file explorer will open. Navigate to the folder where you saved the .prj.xml file.
- Select the file: Tap on the project XML file you wish to import. Tasker will automatically load the profiles, tasks, scenes, and variables contained within that project.
- Finalize: Once imported, the project tab will appear with the name defined in the XML file, and all elements will be ready for use.
- If you encounter any issues during the process, try to close the app (using back button, not to force close) and ensure that you have granted Tasker the necessary storage permissions in your Android settings.

## Sponsors
https://t.me/ryukinotes/25


