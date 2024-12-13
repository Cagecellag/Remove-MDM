# Updated step by step guide to cracking a school iPad (MDM)

## Some stuff you should keep in mind: 
- This presses will delete all the contents of the iPad, so make sure you exported all your files and photos to a cloud storage, or just airdrop it to another device.
- There is a easy way to enrol the iPad back in to the school system (aka, let your school take control of your iPad again.
- So far I haven't been couth yet, my guess is that my iPad is still listen in there DB but its just always offline.
- This guide was built upon a older jamf system, idk if it will work for other MDM or on a newer jamf system. There is a good chance it will always work, my guess is that apple stages its installations so the restrictions come later.
- I wrote this guide with the assumption that you use windows.
- This guide also needs you to download a app, if i where you i would delete iBackupBot right after you're done with the cracking. I did it because it fucked my middle mouse button.

- Connect your iPad to a pc via a cable
- Do a complete wipe of the iPad (located: General > Transfer or Reset iPad > Erase All Contents and Settings), 
- After the reset, a welcome screen will appear,
- Go thru the menus until you come to the Wi-Fi screen
- Make sure to connect your iPad with a hot spot or a network you can turn of in a instant (you will see why in future steps)
- After pressing continue, there is a chance that a screen will show up and tell you that there is still some configuration stuff left,  
- Just to be sure click on erase all contents (you can skip this but idk if it would still work, if you want to skip this step jump forward to step 10)
- this will bring you back to the welcome screen
- Go thru the menus again and connect your hot spot and click continue
- There might be a chance the prompt from step 6 will still appear, (if it does appear again you can ignore it)
- The next page will show a installation request for the MDM just click continue
- Now this is where you get your turn off button for the hot spot ready
- The second you see the home screen, turn off your hot spot (this will block any restrictions from downloading)
- You can go to the settings and check if it downloaded any restrictions, General > VPN & Device Management >  jamf profile, if you don't see a restrictions tab then you're all set,
- Go to your pc and open iTunes, open the device menu,
- In the backups section, select this computer and click back up now
- Wait for the backup to complete,
- In the meantime you can head over to https://www.icopybot.com/download.htm, make sure you download the iBackupBot for Windows
- Dabble click the exe and install the program
- After installation open iBackupBot and wait for it to load
- After loading, in the top left corner there should be a backup called Admin's iPad
- Click on the small + button on the side to extend its contents
- Click on system files so you open its contents in the middle of the screen 
- On the top bar there should be a search box, search for "config"
- This is where the jankiness begins, 
- Delete all the contents of these files, "config, UserConfiguraionsProfiles, ConfigurationProfiles" (note, idfk what you're deleting here, the only this that matters is that it works)
- After deleting the files you can head over to iTunes, in the Backups section click the "Restore Backup" button
- Select the "Admin's iPad" and click continue

- Wait until the restoration is complete
- Now setup your iPad like you just got a new one and your done.
