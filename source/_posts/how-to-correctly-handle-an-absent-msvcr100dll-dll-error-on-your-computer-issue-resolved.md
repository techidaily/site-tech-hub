---
title: How to Correctly Handle an Absent MSVCR100.dll DLL Error on Your Computer (Issue Resolved)
date: 2025-03-02T18:01:11.545Z
updated: 2025-03-05T16:23:01.413Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes How to Correctly Handle an Absent MSVCR100.dll DLL Error on Your Computer (Issue Resolved)
excerpt: This Article Describes How to Correctly Handle an Absent MSVCR100.dll DLL Error on Your Computer (Issue Resolved)
thumbnail: https://thmb.techidaily.com/efbab3d097792aa66f0bd2cf2071c3ef92d9d9dc79fa36684145aac317075ce9.jpg
---

## Error Code 80240020 Deciphered: Easy Steps to Successfully Install Windows 10 without a Glitch

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
<li><a href="https://on-screen-recording.techidaily.com/new-ideal-screencasting-tools-for-enhancing-online-learning/"><u>[New] Ideal Screencasting Tools for Enhancing Online Learning</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/n-2024-discovering-top-10-must-watch-business-video-hubs/"><u>[New] In 2024, Discovering Top 10 Must-Watch Business Video Hubs</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-innovating-imagery-topiary-techniques-for-stellar-iphone-photos/"><u>[Updated] 2024 Approved Innovating Imagery Topiary Techniques for Stellar iPhone Photos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-crafting-a-chorus-of-images-and-sound-on-instagram/"><u>[Updated] Crafting a Chorus of Images & Sound on Instagram</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-nocturnal-nuances-essential-tips-for-moonlit-portraiture/"><u>2024 Approved Nocturnal Nuances Essential Tips for Moonlit Portraiture</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-step-by-step-process-for-capturing-top-tier-presentations/"><u>2024 Approved Step-by-Step Process for Capturing Top-Tier Presentations</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-chatgpts-language-decoder-how-does-it-work-and-why-is-it-vital/"><u>Understanding ChatGPT’s Language Decoder: How Does It Work and Why Is It Vital?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-creative-potential-how-to-navigate-and-utilize-gpt-3-in-the-openai-playground/"><u>Unlocking Creative Potential: How to Navigate and Utilize GPT-3 in the OpenAI Playground</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-artificial-intelligence-exploring-its-potential-risks/"><u>Unveiling Artificial Intelligence: Exploring Its Potential Risks</u></a></li>
<li><a href="https://tech-hub.techidaily.com/what-is-the-paperclip-maximizer-problem-and-how-does-it-relate-to-ai/"><u>What Is the Paperclip Maximizer Problem and How Does It Relate to AI?</u></a></li>
</ul></div>

