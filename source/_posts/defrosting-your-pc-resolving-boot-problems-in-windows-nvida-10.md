---
title: "Defrosting Your PC: Resolving Boot Problems in Windows Nvida 10"
date: 2025-02-27T17:36:17.354Z
updated: 2025-03-05T18:48:44.057Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Defrosting Your PC: Resolving Boot Problems in Windows Nvida 10"
excerpt: "This Article Describes Defrosting Your PC: Resolving Boot Problems in Windows Nvida 10"
thumbnail: https://thmb.techidaily.com/485fa639637af95e40bb39955015be2d5660936e6475a435b4a4c85695223b88.jpg
---

## Resolving Windows 10 Installation Issue - Fix Error Code 80 #

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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-step-by-step-transferring-snapshots-from-social-platform-to-device/"><u>[New] 2024 Approved Step-by-Step Transferring Snapshots From Social Platform to Device</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-discover-the-best-in-igtv-every-week/"><u>2024 Approved Discover the Best in IGTV Every Week</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/apple-expands-its-discontinued-mac-lineup-with-9-more-models-implications-for-consumers-and-tech-enthusiasts-detailed-analysis-by-zdnet/"><u>Apple Expands Its Discontinued Mac Lineup with 9 More Models - Implications for Consumers and Tech Enthusiasts | Detailed Analysis by ZDNet</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/discover-top-affordable-video-editors-of-2023-today-in-2024/"><u>Discover Top Affordable Video Editors of 2023 Today, In 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-does-the-new-ai-regulation-in-europe-influence-chatgpt/"><u>How Does the New AI Regulation in Europe Influence ChatGPT?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-to-train-custom-chatgpt-models-with-company-specific-information/"><u>How to Train Custom ChatGPT Models With Company-Specific Information</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-it-worth-exploring-auto-gpt-while-anticipating-the-release-of-gpt-4/"><u>Is It Worth Exploring Auto-GPT While Anticipating the Release of GPT-4?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-truthgpt-coin-genuine-or-fraudulent-uncovering-the-facts/"><u>Is TruthGPT Coin Genuine or Fraudulent? Uncovering the Facts</u></a></li>
<li><a href="https://tech-hub.techidaily.com/life-made-effortless-unlocking-the-power-of-chatgpt-in-9-ways/"><u>Life Made Effortless: Unlocking the Power of ChatGPT in 9 Ways</u></a></li>
<li><a href="https://fox-glue.techidaily.com/macs-high-resolution-vision-the-ultimate-10-screen-companions-for-2024/"><u>Mac's High-Resolution Vision The Ultimate #10 Screen Companions for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/maintaining-confidentiality-with-chatgpt-at-the-office-a-comprehensive-guide/"><u>Maintaining Confidentiality with ChatGPT at the Office: A Comprehensive Guide</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-chatgpt-the-ultimate-guide-to-writing-winning-prompts-for-excellent-outcomes/"><u>Mastering ChatGPT: The Ultimate Guide to Writing Winning Prompts for Excellent Outcomes</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/mastering-live-participation-in-tiktok-a-step-by-step-guide-for-2024/"><u>Mastering Live Participation in TikTok A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-relaxation-managing-anxiety-using-chatgpt/"><u>Mastering Relaxation: Managing Anxiety Using ChatGPT</u></a></li>
<li><a href="https://extra-tips.techidaily.com/tech-talk-optimizing-for-the-apple-store/"><u>Tech Talk Optimizing for the Apple Store</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/unique-locations-enhancing-youtube-traction/"><u>Unique Locations Enhancing YouTube Traction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-and-resolving-windows-store-issue-code-0x00000000/"><u>Unraveling and Resolving Windows Store Issue Code 0X00000000</u></a></li>
</ul></div>

