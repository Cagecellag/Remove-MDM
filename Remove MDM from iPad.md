# <ins>**Read everything here, ik its a lot but if you don't something might go wrong or wont work.**</ins>

If for some reason you lost the URL to the GitHub page you can click [here]((https://github.com/Cagecellag/Remove-MDM)).

# **Some stuff you need to know first,**

- If you already have a backup with all the stuff removed go to the second set of instructions (If you have no idea what I mean by this just ignore it and continue reading down below.)

# **Updated step by step guide to cracking a school iPad (MDM)**

<span style="color:red"> **Last tested and working 13.12.2024 on iOS 17.6.1** </span>

## **Some stuff you should keep in mind:**

- This way of removing the MDM will delete all the contents of the iPad, so make sure you exported all your files and photos to a cloud storage, or just airdrop it to another device.
- There is a easy way to enrol the iPad back in to the school system (aka, let your school take control of your iPad again.
- So far I haven't been couth yet, my guess is that my iPad is still listen in there DB but its just always offline.
- This guide was built upon a older jamf system, idk if it will work for other MDM or on a newer jamf system. There is a good chance it will always work, my guess is that apple stages its installations so the restrictions come later.
- I wrote this guide with the assumption that you use windows.
- This guide also needs you to download a app, if i where you i would delete iBackupBot right after you're done with the cracking. I did it because it fucked my middle mouse button.

## **--First set of instructions--**

1. Do a complete wipe of the iPad (located: General > Transfer or Reset iPad > Erase All Contents and Settings),
1. After the reset, a welcome screen will appear,
1. Go thru the menus until you come to the Wi-Fi screen
1. Make sure to connect your iPad with a hot spot or a network you can turn of in a instant (you will see why in future steps)
1. After pressing continue, there is a chance that a screen will show up and tell you that there is still some configuration stuff left,  
1. Just to be sure click on erase all contents (you can skip this but idk if it would still work, if you want to skip this step jump forward to step 10)
1. this will bring you back to the welcome screen
1. Go thru the menus again and connect your hot spot and click continue
1. There might be a chance the prompt from step 6 will still appear, (if it does appear again you can ignore it)
1. The next page will show a installation request for the MDM just click continue
11. Now this is where you get your turn off button for the hot spot ready
11. The second you see the home screen, turn off your hot spot (this will block any restrictions from downloading)
11. You can go to the settings and check if it downloaded any restrictions, General > VPN & Device Management >  jamf profile, if you don't see a restrictions tab then you're all set,
11. Connect your iPad to a pc via a cable lighting or usb c
11. Go to your pc and open iTunes, open the device menu,
11. In the backups section, select this computer and click back up now
11. Wait for the backup to complete,
11. In the meantime you can head over to[https://www.icopybot.com/download.htm,](https://www.icopybot.com/download.htm) make sure you download the **iBackupBot for Windows**
11. Dabble click the exe and install the program
11. After installation open iBackupBot and wait for it to load
11. After loading, in the top left corner there should be a backup called Admin's iPad
11. Click on the small + button on the side to extend its contents
11. Click on system files so you open its contents in the middle of the screen
11. On the top bar there should be a search box, search for "config"
11. This is where the jankiness begins,
11. Delete all the contents of these files, "config, UserConfiguraionsProfiles, ConfigurationProfiles" (note, idfk what you're deleting here, the only this that matters is that it works)
11. After deleting the files you can head over to iTunes, in the Backups section click the "Restore Backup" button
11. Select the "Admin's iPad" and click continue
11. Wait until the restoration is complete
11. Now setup your iPad like you just got a new one and your done.

## **--Second set of instructions--**

- This set of instructions is for when you already have a backup with all the stuff deleted.
- This set will repeat the first three step
- The backup directory: C:\Users\Admin\AppData\Roaming\Apple Computer\MobileSync\Backup
- Important note: this step has many variations, I'm going to try too list of as many as I know if you're case isn't listed then try to contact me by Email: <cagecell@proton.me>
- I highlighted the parts where both instructions are the same

## **Type one**

31. Do a complete wipe of the iPad (located: General > Transfer or Reset iPad > Erase All Contents and Settings),
31. After the reset, a welcome screen will appear,
31. Connect your iPad to a pc via a cable
31. Open iTunes,
31. If no setup screen appears just select the iPad icon in the top left
31. Make sure you have the cracked backup in the backup folder, if you didn't do that yet do it and re plug in you're iPad so iTunes can detect your backup
31. Select restore backup
31. Select the "cracked backup" and install it
39. The welcome/welcome screen should come up on the iPad
39. And you're done.

## **Type two**

41. Do a complete wipe of the iPad (located: General > Transfer or Reset iPad > Erase All Contents and Settings),
41. After the reset, a welcome screen will appear,
41. Connect your iPad to a pc via a cable
41. Open iTunes, it should welcome you to a setup screen,
41. Select restore backup
41. Select the "cracked backup" and install it
41. The welcome/welcome screen should come up on the iPad
41. And you're done.
