MDM Removal Guide for School iPads
Last Tested: December 13, 2024, on iOS 17.6.1

⚠️ Disclaimer: Use this guide responsibly and at your own risk. This process deletes all data on the iPad and may have other unintended consequences. Always back up your data beforehand.

Important Notes
All data will be erased. Export your files and photos to cloud storage or another device before proceeding.
Re-enrollment is possible. This method does not prevent the school from regaining control if the iPad reconnects to their system.
Compatibility: This guide is designed for older Jamf MDM systems on Windows PCs. Success with newer systems or macOS is not guaranteed.
Required App: You will need iBackupBot. Uninstall it after use to avoid potential issues.
Instructions
Option 1: Start from Scratch
Wipe the iPad

Go to Settings > General > Transfer or Reset iPad > Erase All Content and Settings.
Proceed through the setup screens until you reach the Wi-Fi page.
Connect to a hotspot or a network you can turn off instantly.
Block MDM Installation

Continue setup until the MDM configuration request appears.
Important: When you reach the home screen, immediately turn off your hotspot to block restrictions from downloading.
Verify MDM is not installed:
Go to Settings > General > VPN & Device Management.
If no restrictions appear, you’re good to proceed.
Back Up the iPad

Connect the iPad to a PC using a Lightning/USB-C cable.
Open iTunes, go to the Backups section, select This Computer, and click Back Up Now.
Modify the Backup

Download and install iBackupBot.
Open iBackupBot and locate the backup named Admin’s iPad.
Expand System Files and search for “config.”
Delete these files:
config
UserConfigurationsProfiles
ConfigurationProfiles
Restore the Modified Backup

Return to iTunes, select Restore Backup, and choose the modified backup.
Complete the setup process as if the iPad is new.
Option 2: Using a Pre-Cracked Backup
If you already have a modified backup:

Wipe the iPad

Go to Settings > General > Transfer or Reset iPad > Erase All Content and Settings.
Proceed to the setup screens until the welcome screen appears.
Restore the Cracked Backup

Connect your iPad to a PC.
Place the cracked backup in the directory:
C:\Users\Admin\AppData\Roaming\Apple Computer\MobileSync\Backup
Open iTunes, select Restore Backup, and choose the cracked backup.
Complete the setup process as if the iPad is new.

Support
If you encounter issues or need help, feel free to reach out:
Email: cagecell@proton.me
