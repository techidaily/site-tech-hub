---
title: Resolving svchost.exe's Excessive Disk Consumption in Windows 10 Systems
date: 2025-02-26T18:35:48.637Z
updated: 2025-03-05T16:27:22.240Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Resolving svchost.exe's Excessive Disk Consumption in Windows 10 Systems
excerpt: This Article Describes Resolving svchost.exe's Excessive Disk Consumption in Windows 10 Systems
thumbnail: https://thmb.techidaily.com/daa4ddbb9dc17599c8cc745fc4daad052ccf0ddb620b28a0347c7de8e4fb4249.jpg
---

## Error Code 80240020: Comprehensive Troubleshooting Steps for Windows 10 Installation Issues Resolved

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-poco-c65-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Poco C65 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-photos-from-realme-c67-4g-by-fonelab-android-recover-photos/"><u>Best Android Data Recovery - Retrieve Lost Photos from Realme C67 4G.</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatbots-face-off-determining-whether-chatgpt-triumphs-over-gemini-for-coding-wizards/"><u>Chatbots Face-Off: Determining Whether ChatGPT Triumphs Over Gemini for Coding Wizards</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-at-your-service-6-innovations-revolutionizing-smartwatch-tech/"><u>ChatGPT at Your Service: 6 Innovations Revolutionizing Smartwatch Tech</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-intelligence-assessing-the-accusations-of-decreased-smartness/"><u>ChatGPT Intelligence: Assessing the Accusations of Decreased Smartness</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-on-the-mac-app-store-here-are-5-reasons-to-think-twice-before-installing/"><u>ChatGPT on the Mac App Store? Here Are 5 Reasons to Think Twice Before Installing</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-bugs-affecting-pc-experience-civilization-v/"><u>Fixing Bugs Affecting PC Experience, Civilization V</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-giants-of-online-communication-facebook-twitter-instagram-and-youtube/"><u>Navigating the Giants of Online Communication: Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-efficiency-shortcuts-for-windows-11s-microphone/"><u>Unlocking Efficiency: Shortcuts for Windows 11'S Microphone</u></a></li>
</ul></div>

