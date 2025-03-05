---
title: "Troubleshooting Guide: Solving 'Drag & Drop' Issues in Windows"
date: 2025-02-28T17:05:07.463Z
updated: 2025-03-05T17:03:19.301Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Troubleshooting Guide: Solving 'Drag & Drop' Issues in Windows"
excerpt: "This Article Describes Troubleshooting Guide: Solving 'Drag & Drop' Issues in Windows"
thumbnail: https://thmb.techidaily.com/6b81d20b1d6e26d0457009bbfe739603019d02e6b0e9205be931fb19bdb3ed9f.jpg
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
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-examining-the-potential-of-4-second-subscriptions/"><u>[Updated] In 2024, Examining the Potential of 4-Second Subscriptions</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-inverting-photo-colors-with-advanced-tools-for-2024/"><u>[Updated] Inverting Photo Colors with Advanced Tools for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unveiling-the-quintessential-five-strategic-moves-for-youtube-marketing-success/"><u>2024 Approved Unveiling the Quintessential Five Strategic Moves for YouTube Marketing Success</u></a></li>
<li><a href="https://discover-docs.techidaily.com/1725286043731-pc/"><u>前十個最好的PC影片編碼程式：完美切換列表</u></a></li>
<li><a href="https://tech-hub.techidaily.com/experience-cutting-edge-ai-search-on-the-go-with-bings-new-app-support-for-android-and-ios/"><u>Experience Cutting-Edge AI Search on the Go with Bing's New App Support for Android and iOS!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-new-horizons-with-chatgpt-enabling-beta-browsing-and-plugin-functions-for-an-upgraded-online-journey/"><u>Exploring New Horizons with ChatGPT: Enabling Beta Browsing and Plugin Functions for an Upgraded Online Journey</u></a></li>
<li><a href="https://tech-hub.techidaily.com/flavor-and-fitness-ai-powered-meal-prepping-tips/"><u>Flavor & Fitness: AI-Powered Meal Prepping Tips</u></a></li>
<li><a href="https://tech-hub.techidaily.com/hack-alert-activision-breach-exposed-are-chatgpt-infused-ai-taking-our-jobs/"><u>Hack Alert: Activision Breach Exposed, Are ChatGPT-Infused AI Taking Our Jobs?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-does-gpt-4-differ-from-its-cousins-a-deep-dive-into-gpt-4-vs-gpt-4-turbo-vs-gpt-4o/"><u>How Does GPT-4 Differ From Its Cousins? A Deep Dive Into GPT-4 Vs. GPT-4 Turbo Vs. GPT-4o</u></a></li>
<li><a href="https://change-location.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-xiaomi-redmi-a2plus-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Xiaomi Redmi A2+? | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-top-8-youtube-images-that-captivate-and-convert-viewers/"><u>In 2024, Top 8 YouTube Images That Captivate and Convert Viewers</u></a></li>
<li><a href="https://tech-hub.techidaily.com/inside-googles-cutting-edge-initiative-the-gemini-ai-project-explained/"><u>Inside Google's Cutting-Edge Initiative: The Gemini AI Project Explained</u></a></li>
<li><a href="https://tech-hub.techidaily.com/installation-made-easy-running-gpt-on-windows/"><u>Installation Made Easy: Running GPT on Windows</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ntly-professional-masterful-thumbnails-created-fast-for-2024/"><u>Instantly Professional Masterful Thumbnails Created Fast for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-the-turing-test-outdated-5-turing-test-alternatives/"><u>Is the Turing Test Outdated? 5 Turing Test Alternatives</u></a></li>
<li><a href="https://tech-hub.techidaily.com/llama-2-the-next-level-in-automation-tools/"><u>Llama 2: The Next Level in Automation Tools</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolved-defeating-obs-software-glitches-on-windows-systems-for-optimal-streaming/"><u>Resolved! Defeating OBS Software Glitches on Windows Systems for Optimal Streaming</u></a></li>
<li><a href="https://app-tips.techidaily.com/singapore-invests-24-billion-in-enhancing-ict-frameworks-and-digital-service-offerings-a-deep-dive-into-the-national-strategy/"><u>Singapore Invests $2.4 Billion in Enhancing ICT Frameworks & Digital Service Offerings: A Deep Dive Into the National Strategy</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/unleash-creativity-the-10-most-popular-animated-text-creators/"><u>Unleash Creativity The 10 Most Popular Animated Text Creators</u></a></li>
</ul></div>

