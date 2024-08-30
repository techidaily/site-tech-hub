---
title: "Complete Guide: Uninstalling Print Devices From Windows 11 and 10 Systems"
date: 2024-08-26 13:33:38
updated: 2024-08-29 12:43:24
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/3c7adb8361f107e7e2513d0c6a87960b8e0bf54d4d26d72af2668f6ed0487010.jpg
---

## Complete Guide: Uninstalling Print Devices From Windows 11 and 10 Systems

### Quick Links

* [Three Ways to Uninstall a Printer](https://driver-install.techidaily.com/windows-compatibility-download-pro-4-drivers/)
* [Uninstall the Printer Using the Settings App](https://screen-recording.techidaily.com/new-cutting-edge-fullscreen-capture-programs/)
* [Uninstall a Printer Using Device Manager](https://extra-approaches.techidaily.com/prime-focus-best-photo-viewing-win11-app-for-2024/)
* [Use PowerShell to Remove a Printer](https://screen-capture.techidaily.com/new-selecting-the-perfect-no-fee-video-communication-tools/)
* [Delete the Printer's Installed Apps](https://digital-screen-recording.techidaily.com/new-in-2024-best-online-meeting-capture-the-leading-5-gadgets/)
* [Clean Up the Print Spooler and Leftover Registry Keys](https://instagram-videos.techidaily.com/new-crescendo-creations-adding-audio-magic-to-instagram-stories/)

### Key Takeaways

* To remove just printer and not its drivers, go to Settings > Bluetooth & Devices > Printers & Scanners. Click the printer to delete and choose "Remove."
* To remove the printer along with its drivers, open Device Manager, right-click the printer, select "Uninstall Device," enable the option to remove the printer drivers, and select "Uninstall."
* You can also remove a printer with PowerShell using the Remove-Printer command.

 If you don’t use a printer anymore and wish to remove it, or you want to uninstall and reinstall a printer to fix its problems, both Windows 11 and Windows 10 make it super easy to uninstall printers. We’ll show you how to do that using two graphical and one command line method.

##  Three Ways to Uninstall a Printer

 There are three different ways to remove a printer from a Windows PC. 

1. If you’re only looking to remove the printer’s connection from your PC and without deleting the printer’s drivers, use the Settings app method. This method ensures the selected printer doesn’t appear in any print dialog boxes.
2. If you want to completely remove a printer (and the associated drivers), use the Device Manager method. This is helpful if you’re [troubleshooting issues with the printer](https://pokemon-go-android.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-realme-gt-5-pro-drfone-by-drfone-virtual-android/).
3. The third method is a command line method that removes the printer’s connection from your PC, just like the Settings app does.

##  Uninstall the Printer Using the Settings App 

 If you’re on a Windows 11 PC, head into Settings > Bluetooth & Devices > Printers & Scanners. On Windows 10, navigate to Settings > Devices > Printers & Scanners.

!['Printers & Scanners' highlighted in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-printers-scanners-windows-11-settings.jpg) 

 Find and select the printer to remove. On Windows 11, choose "Remove." On Windows 10, select "Remove Device" and click "Yes."

!['Remove' highlighted for a printer in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-remove-printer-windows-11.jpg) 

 Windows has removed the selected printer.

##  Uninstall a Printer Using Device Manager

 To remove a Printer with Device Manager, first [open Device Manager](https://desktop-recording.techidaily.com/updated-2024-approved-easily-record-lenovo-laptop-screen-activity/) by right-clicking the Start Menu icon and selecting "Device Manager."

!['Device Manager' highlighted in Power User Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-open-windows-device-manager.jpg) 

 Select "View" in the menu bar, then enable "Show Hidden Devices" to ensure your printer appears even if it's hidden. 

!['Show Hidden Devices' highlighted in Device Manager.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-view-hidden-devices-device-manager.jpg) 

 In the same window, expand "Printers" and find your printer. If you can't find your printer, expand "Print Queues" and look for it there. Once you've located it, right-click the printer's name and select "Uninstall Device."

!['Uninstall Device' highlighted for a printer in Device Manager.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-uninstall-printer-device-manager.jpg) 

 In the "Uninstall Device" window, enable the "Attempt to Remove the Driver for This Device" (Windows 11) or "Delete the Driver Software for This Device" (Windows 10) option. Then, click "Uninstall."

![Delete a printer and its drivers in Device Manager.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-delete-printer-driver-device-manager.jpg) 

 Wait while Device Manager uninstalls the selected printer. Then, bring the changes into effect by [restarting your Windows 11](https://screen-video-capture.techidaily.com/updated-in-2024-addressing-mute-problems-in-obs-live-recording/) or [Windows 10](https://article-posts.techidaily.com/comparing-the-creme-de-la-creme-gopro-hero5-black-to-hero4-silver-for-2024/) PC.

##  Use PowerShell to Remove a Printer

 Open the Start Menu, search for **PowerShell**, and select "[Run as Administrator](https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual/)."

!['Run as Administrator' highlighted for PowerShell in Start Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-run-powershell-as-admin.jpg) 

 In the User Account Control (UAC) prompt, select "Yes."

 In PowerShell, list the available printers by typing the following command and pressing Enter:

Get-Printer

!['Get-Printer' typed in PowerShell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-view-installed-printers-powershell.jpg) 

 From the listed printers, note the name of the printer you want to remove. Then, type the following command, replacing "PrinterName" with the noted name, and press Enter. Make sure the printer’s name is enclosed in double quotes.

Remove-Printer -Name “PrinterName”

!['Remove-Printer' typed in PowerShell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-remove-printer-powershell.jpg) 

 PowerShell has removed the specified printer. You can run **Get-Printer** again to confirm that it has been removed. 

##  Delete the Printer's Installed Apps

 Most printers (if not all) install their own manufacturer apps when you add a printer to your PC. If you’ve gotten rid of your printer for good, you should remove these installed apps as well. Here’s how to do that.

###  On Windows 11

 Open Settings using Windows+i and navigate to Apps > Installed apps.

!['Installed apps' highlighted in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/10-installed-apps-windows-11.jpg) 

 Find your printer’s app on the list. Next to the app, click the three dots and choose "Uninstall."

!['Uninstall' highlighted for a printer app in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/11-delete-printer-app-windows-11.jpg) 

 Select "Uninstall" in the prompt.

###  On Windows 10

 Launch Settings using Windows+i and select "Apps."

!['Apps' highlighted in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/12-apps-windows-10-settings.jpg) 

 Find and select your printer app on the list. Choose "Uninstall" and select "Uninstall."

!['Uninstall' highlighted for a printer app in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/13-remove-printer-app-windows-10-settings.jpg) 

##  Clean Up the Print Spooler and Leftover Registry Keys

 After removing the printer, [clean up any pending print jobs](https://facebook-record-videos.techidaily.com/new-in-2024-cooking-crusaders-youtube-stars-serving-up-deliciousness/) and leftover registry keys. This ensures all traces of your printer are gone from your PC.

###  Clean Up the Print Spooler

 Open Run by pressing Windows+R, type the following command, and press Enter:

services.msc

 Find the service named Print Spooler. Right-click it and select "Stop." Keep the Services window open.

!['Stop' highlighted for the 'Print Spooler' service.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/14-stop-print-spooler-service.jpg) 

 Open Run again (using Windows+R), type the following path, and press Enter:

C:\Windows\System32\spool\PRINTERS

[Enable hidden items in File Explorer](https://tech-hub.techidaily.com/learn-ai-prompt-engineering-with-our-top-5-expert-led-online-courses/). On Windows 11, from the top bar, select View > Show and click "Hidden Items." On Windows 10, open the "View" tab and enable "Hidden Items." Select all files in the folder by pressing Ctrl+A, right-click a selected file, and choose the trash can icon (or "Delete" on Windows 10).

![The trash can icon highlighted for the print spooler files.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/15-delete-print-spooler-files.jpg) 

 Return to the Services window we opened previously, right-click "Print Spooler" again, and select "Start."

###  Remove the Deleted Printer’s Leftover Registry Keys

 Be cautious of deleting things in the Windows Registry, and follow our instructions carefully. Deleting or modifying the wrong key can cause issues with your PC. 

 Open the Start Menu, search for **Registry Editor**, and launch the utility.

![Registry Editor highlighted in Start Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/16-open-registry-editor.jpg) 

 In the User Account Control prompt, select "Yes."

 Navigate to the following path in Registry Editor or paste it into the address bar:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Print\Printers

 In the left sidebar, find the folder for your printer. It should have your printer’s name. Right-click the folder and select "Delete."

!['Delete' highlighted for a printer's keys in Registry Editor.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/17-delete-printer-keys-registry-editor.jpg) 

 Quit Registry Editor and [restart your computer](https://instagram-clips.techidaily.com/2024-approved-15-must-use-hashtags-for-popularity-on-instagram-feed/). And you’ve successfully removed a printer from your Windows machine.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
