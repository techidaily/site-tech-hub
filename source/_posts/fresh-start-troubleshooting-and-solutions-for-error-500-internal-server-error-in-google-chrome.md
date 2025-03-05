---
title: "Fresh Start: Troubleshooting and Solutions for 'Error 500 (Internal Server Error)' In Google Chrome"
date: 2025-03-02T18:18:24.127Z
updated: 2025-03-05T16:05:57.917Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Fresh Start: Troubleshooting and Solutions for 'Error 500 (Internal Server Error)' In Google Chrome"
excerpt: "This Article Describes Fresh Start: Troubleshooting and Solutions for 'Error 500 (Internal Server Error)' In Google Chrome"
thumbnail: https://thmb.techidaily.com/61dcd74c9ca257bd7a3583ce0e08424eaf979002cdc0aa0e847be271477f189f.jpg
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
<li><a href="https://video-capture.techidaily.com/new-the-cost-effective-way-to-capture-every-frame-with-free-tools/"><u>[New] The Cost-Effective Way to Capture Every Frame with Free Tools</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-upload-guide-twitter-video-aspect-ratio-mandated/"><u>[Updated] In 2024, Upload Guide Twitter Video Aspect Ratio Mandated</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-top-10-online-photo-editing-tools-to-unblur-photos-effectively/"><u>[Updated] Top 10 Online Photo Editing Tools to Unblur Photos Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/future-focused-laptop-innovations-at-ifa-2023/"><u>Future-Focused Laptop Innovations at IFA 2023</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-vivo-v30-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Vivo V30</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-ultimate-guide-to-radiowave-plays/"><u>In 2024, Ultimate Guide to Radiowave Plays</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-xiaomi-redmi-13c-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Xiaomi Redmi 13C | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-leading-8-chrome-addons-ai-for-enhanced-productivity/"><u>The Leading 8 Chrome Addons: AI for Enhanced Productivity</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-risks-of-using-chatgpt-from-the-mac-app-store-what-every-user-needs-to-know/"><u>The Risks of Using ChatGPT From the Mac App Store: What Every User Needs to Know</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-5-factors-propelling-chatgpts-unprecedented-rise-as-todays-most-popular-application/"><u>Top 5 Factors Propelling ChatGPT's Unprecedented Rise as Today’s Most Popular Application</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-7-ai-powered-tools-revolutionizing-presentation-creation/"><u>Top 7 AI-Powered Tools Revolutionizing Presentation Creation</u></a></li>
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-blaze-2-pro-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from Blaze 2 Pro</u></a></li>
</ul></div>

