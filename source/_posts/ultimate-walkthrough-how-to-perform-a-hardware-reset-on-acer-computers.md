---
title: "Ultimate Walkthrough: How to Perform a Hardware Reset on Acer Computers"
date: 2024-08-15 12:58:28
updated: 2024-08-16 10:52:34
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Ultimate Walkthrough: How to Perform a Hardware Reset on Acer Computers"
excerpt: "This Article Describes Ultimate Walkthrough: How to Perform a Hardware Reset on Acer Computers"
thumbnail: https://thmb.techidaily.com/3376b29faa2d3197bcfcb2a2edc1961849ab5554465668491f874fa276d36a0e.jpg
---

## The Complete Walkthrough to Initiate Safe Mode on Windows 10 - Learn With Pictures

![How to start Windows 10 in Safe Mode feature image](https://images.drivereasy.com/wp-content/uploads/2016/03/How-to-start-Windows-10-in-Safe-Mode-feature-image-1200x675.jpg)

 Safe Mode is a way to run Windows in its most basic form. It uses only absolutely essential files and drivers.

 For example, in Safe Mode, your screen will display only 16 colors and a very low resolution, and you won’t be able to print documents or hear audio. It also won’t load many programs in the background.

Safe Mode is designed to help you troubleshoot computer problems.

 Sometimes Windows 10 will automatically start in Safe Mode (e.g. if it has a problem loading normally). But sometimes you’ll need to start it in Safe Mode manually (e.g. if you get a blue screen error every time you start Windows).

This article explains how to manually start Windows 10 in safe mode.

## 4 ways to start Windows 10 in Safe Mode

1. [**Start Safe Mode by pressing F8 at startup**](https://tools.techidaily.com/drivereasy/download/)
2. **[Start Safe Mode by turning off your PC 3 times](https://tools.techidaily.com/drivereasy/download/)**
3. **[Start Safe Mode using the System Configuration tool](https://tools.techidaily.com/drivereasy/download/)**
4. **[Start Safe Mode from the login screen](https://tools.techidaily.com/drivereasy/download/)**
5. **[Can’t solve the problem? Try this fix…](https://tools.techidaily.com/drivereasy/download/)**

---

## **Method 1: Start Safe Mode by pressing F8 at startup**

**IMPORTANT:** This method must be manually enabled from within Windows. If you haven't already enabled it, and you can't access Windows to do so, [skip to method 2 below](https://tools.techidaily.com/drivereasy/download/).

### First, you have to enable the F8 key method

 On Windows 7, you could press the F8 key as your computer was booting to access the Advanced Boot Options menu. From there, you could access Safe Mode.

 But on Windows 10, the F8 key method doesn’t work by default. You have to manually enable it.

Here’s how to get the F8 key to start Safe Mode in Windows 10:

 1) Click the**Windows start menu** and type**cmd** , then click**Run as administrator** :

![](https://images.drivereasy.com/wp-content/uploads/2021/08/Start-command-prompt-as-admin.png)

2) Copy this command:

**bcdedit /set {default} bootmenupolicy legacy**

 3) Paste the copied command into the Command Prompt (right-click in the Command Prompt to paste), then press the**Enter** key on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/bcdedit-1.jpg)

4) Reboot your PC.

### Now you can start Safe Mode using the F8 key

 Now that you’ve enabled the F8 method, you can use it to start Safe Mode:

1) Ensure your computer is turned off.

2) Turn your computer on.

3) Before anything appears on your screen, press**F8** repeatedly until the Boot Options menu below displays. Then select**Safe Mode** .

![](https://images.drivereasy.com/wp-content/uploads/2019/12/safe-mode-1.jpg)

 If the Boot Options menu above doesn’t display, and instead Windows just launches normally, it’s likely that you didn’t press F8 early enough.

---

## **Method 2: Start Safe Mode by turning off your PC 3 times**

 If you’re unable to launch Windows, and you haven’t enabled the F8 method above, this is how to start Safe Mode:

1) Ensure your computer is off.

2) Press the power button to turn on your PC, and when you see the small spinning circle of dots that indicates Windows is starting, press and hold the power button until your PC shuts down. You’ll have to hold it for 4-5 seconds.

 Do this again, and then again. After you’ve done it 3 times, start your computer again and let it run. It should now go into Automatic Repair mode:

![](https://images.drivereasy.com/wp-content/uploads/2016/03/preparing-automatic-repair-screen.jpg)

3) Wait for Windows to diagnose your PC:

![](https://images.drivereasy.com/wp-content/uploads/2016/03/diagnose-your-pc-1.jpg)

 4) Click**Advanced Options** :

![](https://images.drivereasy.com/wp-content/uploads/2016/03/advanced-options-2-1.jpg)

 5) Click**Troubleshoot** :

![](https://images.drivereasy.com/wp-content/uploads/2016/03/troubleshoot.jpg)

 6) Click**Advanced options** :

![](https://images.drivereasy.com/wp-content/uploads/2016/03/troubleshoot-screen.jpg)

 7) Click**Startup Settings** :

![](https://images.drivereasy.com/wp-content/uploads/2016/03/startup-settings.jpg)

 8) Click**Restart** .

![](https://images.drivereasy.com/wp-content/uploads/2016/03/restart.jpg)

 Your computer will restart and present a list of different startup options.

 9) On your keyboard, press the number**4** key to enter Safe Mode without internet access or the number**5** key to enter Safe Mode with internet access:

![](https://images.drivereasy.com/wp-content/uploads/2016/03/enable-safe-mode.jpg)

---

## Method 3: Start Safe Mode using the System Configuration tool

**IMPORTANT:** If you follow these instructions, Windows will start in Safe Mode every time it restarts, until you undo your changes.

 If you’re able to launch Windows normally, you can boot into Safe Mode using the System Configuration tool:

 1) Click the**Windows start menu** and type**msconfig** , then click**Open** :

![](https://images.drivereasy.com/wp-content/uploads/2021/08/Start-System-Configuration-tool.png)

 2) Select the **Boot**  tab, then check **Safe boot**  and  click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2019/12/safe-boot.jpg)

 3) When you’re prompted to restart your computer to apply these changes, click **Restart**  and you’ll boot into Safe Mode.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/restart-computer.jpg)

### To turn off Safe Mode and go back to normal mode

 When you want to return Windows to normal mode, you just have to undo your changes:

 1) Click the**Windows start menu** and type**msconfig** , then click**Open** :

![](https://images.drivereasy.com/wp-content/uploads/2021/08/Start-System-Configuration-tool.png)

 2) Select the **Boot**  tab, then UNcheck **Safe boot**  and  click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2019/12/safe-boot-2.jpg)

 3) When you’re prompted to restart your computer to apply these changes, click **Restart**  and you’ll boot into normal mode.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/restart-computer.jpg)

---

## Method 4: Start Safe Mode from the login screen

If you can boot to the login screen, you can enter Safe Mode from there:

 1) On your keyboard, hold down the**Shift** key.

 2) While holding down the**Shift** key, click the power button at the bottom right of the screen, then select**Restart** .

![](https://images.drivereasy.com/wp-content/uploads/2019/12/login-screen.jpg)

The Windows RE (Recovery environment) screen will then display.

 3) Click **Troubleshoot** :

![](https://images.drivereasy.com/wp-content/uploads/2019/12/troubleshoot-2.jpg)

 4) Click **Advanced options** :

![](https://images.drivereasy.com/wp-content/uploads/2019/12/advanced-options-screen.jpg)

 5) Click **Startup Settings** :

![](https://images.drivereasy.com/wp-content/uploads/2019/12/startup-settings.jpg)

 6) Click **Restart** .

![](https://images.drivereasy.com/wp-content/uploads/2019/12/restart.jpg)

 Your computer will then restart and another screen opens showing a lot of different startup options.

 7) On your keyboard, press the number**4** key to enter Safe Mode without internet access or the number**5** key to enter Safe Mode with internet access:

![](https://images.drivereasy.com/wp-content/uploads/2019/12/enable-safe-mode.jpg)

---

## Can’t solve the problem? Try Driver Easy

 If you couldn’t solve your computer problem in Safe Mode but you can still run Windows normally, give **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  a try.

 Many computer problems are caused by outdated device drivers. So updating your drivers should always be one of the first fixes you try.

 Driver Easy will automatically update all your device drivers to the latest correct version with just a couple of clicks. It will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee):

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)** [](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.

 2) Run Driver Easy and click**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_594b60655cf90.png)

 3) Click the**Update** button next to any flagged device to automatically download and install the correct version of that driver (you can do this with the FREE version).

 Or click**Update All**  to automatically download and install the correct version of**_all_** the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58febfb1a2a71.jpg)

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
