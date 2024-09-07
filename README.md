# Battery Notifier

## Description

`battery_notifier.ps1` is a PowerShell script designed to monitor your laptop's battery level and provide notifications to help you manage charging. The script checks the battery level and charging status periodically. If the battery is below 20% and not charging, or if it is 90% or more and charging, it displays an appropriate notification.

- Provides two types of notifications:
  - Persistent notification in the middle of the screen that requires user interaction (click "OK") to dismiss the middle-screen notification (uncommented version).
  - Notification in the bottom-right corner of the screen (commented version).
  - Use whatever you want just make sure that script is uncommented and comment out or remove the other script.


## Prerequisites

- Windows operating system
- PowerShell (included by default in Windows)
- No additional libraries required

## Usage

1. **Save the Script:**
   Save the `battery_notifier.ps1` script to a location on your computer, such as the Desktop.


2. **Run the Script:**
   Open PowerShell and navigate to the directory where you saved the script. Run the script with the following command:

   ```powershell
   powershell -ExecutionPolicy Bypass -File .\battery_notifier.ps1
   



