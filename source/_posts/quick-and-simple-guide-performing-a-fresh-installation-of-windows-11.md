---
title: "Quick & Simple Guide: Performing a Fresh Installation of Windows 11"
date: 2024-08-15T20:11:03.654Z
updated: 2024-08-16T20:11:03.654Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Quick & Simple Guide: Performing a Fresh Installation of Windows 11"
excerpt: "This Article Describes Quick & Simple Guide: Performing a Fresh Installation of Windows 11"
thumbnail: https://thmb.techidaily.com/90cf06f9730c5591652ae4f421f62950743940a3b49411aac162c7581850732b.jpg
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
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-from-pilot-to-producer-editing-mastery-in-drone-filmmaking/"><u>[Updated] 2024 Approved  From Pilot to Producer  Editing Mastery in Drone Filmmaking</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-unlocking-instagrams-top-spot-in-minutes/"><u>[Updated] 2024 Approved  Unlocking Instagram's Top Spot in Minutes</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-elevate-your-game-saves-with-advanced-overwatch-recording-for-2024/"><u>[Updated] Elevate Your Game Saves with Advanced Overwatch Recording for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-grasp-free-to-use-vimeo-editing-techniques/"><u>2024 Approved  Grasp Free-to-Use Vimeo Editing Techniques</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-premier-solutions-highest-rated-vimeo-downloaders/"><u>2024 Approved  Premier Solutions  Highest Rated Vimeo Downloaders</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-top-5-economical-game-ready-keyboards/"><u>2024 Approved  Top 5 Economical Game-Ready Keyboards</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-ultimate-guide-9-premier-video-translators-for-accurate-global-communication/"><u>2024 Approved  Ultimate Guide  9 Premier Video Translators for Accurate Global Communication</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ai-security-alert-unpacking-the-workings-and-dangers-of-prompt-injection-attacks/"><u>AI Security Alert: Unpacking the Workings & Dangers of Prompt Injection Attacks</u></a></li>
<li><a href="https://tech-hub.techidaily.com/battle-of-the-ais-notion-ai-versus-gpt-3-in-writing/"><u>Battle of the AIs: Notion AI Versus GPT-3 in Writing</u></a></li>
<li><a href="https://tech-hub.techidaily.com/building-bridges-in-isolation-through-ai-dialogue/"><u>Building Bridges in Isolation Through AI Dialogue</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-confidentiality-methods-for-conversation-camouflage-without-deletion/"><u>ChatGPT Confidentiality: Methods for Conversation Camouflage Without Deletion</u></a></li>
<li><a href="https://tech-hub.techidaily.com/comparing-the-capabilities-how-does-mistral-ais-le-chat-measure-up-to-chatgpt/"><u>Comparing the Capabilities: How Does Mistral AI’s Le Chat Measure Up to ChatGPT?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/demystifying-generative-ai-what-you-need-to-know-about-this-innovative-tech/"><u>Demystifying Generative AI: What You Need To Know About This Innovative Tech</u></a></li>
<li><a href="https://tech-hub.techidaily.com/does-chatgpt-ever-tread-the-line-of-plagiarism-a-deep-dive-into-its-data-practices/"><u>Does ChatGPT Ever Tread the Line of Plagiarism? A Deep Dive Into Its Data Practices.</u></a></li>
<li><a href="https://tech-hub.techidaily.com/effortless-conversations-simplifying-your-use-of-chatgpt-with-this-handy-chrome-add-on/"><u>Effortless Conversations: Simplifying Your Use of ChatGPT with This Handy Chrome Add-On</u></a></li>
<li><a href="https://tech-hub.techidaily.com/effortless-cover-letter-writing-using-chatgpt-top-strategies-revealed/"><u>Effortless Cover Letter Writing Using ChatGPT: Top Strategies Revealed</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722971839600-find-and-update-your-windows-rndis-driver-with-ease-fixes-included/"><u>Find and Update Your Windows RNDIS Driver with Ease – Fixes Included!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/from-generic-to-personalized-ai-constructing-a-tailored-chatgpt-experience/"><u>From Generic to Personalized AI: Constructing a Tailored ChatGPT Experience</u></a></li>
<li><a href="https://tech-hub.techidaily.com/has-oversight-over-chatgpt-became-an-issue-for-openai/"><u>Has Oversight Over ChatGPT Became an Issue for OpenAI?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-does-huggingchat-compare-to-chatgpt-a-low-cost-open-source-option/"><u>How Does HuggingChat Compare to ChatGPT: A Low-Cost, Open Source Option</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-to-ensure-authenticity-of-ai-chat-apps-before-purchasing-on-iphoneipad-platform/"><u>How to Ensure Authenticity of AI Chat Apps Before Purchasing on iPhone/iPad Platform</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-7-essential-tips-for-flawless-underwater-filming/"><u>In 2024, 7 Essential Tips for Flawless Underwater Filming</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-4-ways-to-trace-oppo-k11-5g-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 4 Ways to Trace Oppo K11 5G Location | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/innovative-ways-to-integrate-ai-in-writing-software/"><u>Innovative Ways to Integrate AI in Writing Software</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-your-data-safe-with-chatgpt-understanding-privacy-concerns/"><u>Is Your Data Safe with ChatGPT: Understanding Privacy Concerns</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-gpt-written-language-and-web-integration/"><u>Mastering GPT' Written Language and Web Integration</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-your-schedule-top-4-techniques-with-chatgpt/"><u>Mastering Your Schedule: Top 4 Techniques with ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/maximizing-impact-crafting-social-media-posts-with-chatgpt/"><u>Maximizing Impact: Crafting Social Media Posts with ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-through-openais-bug-bounty-scheme-eligibility-processes-and-earning-potential/"><u>Navigating Through OpenAI’s Bug Bounty Scheme: Eligibility, Processes, and Earning Potential</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/reimagining-ppts-with-todays-webcam-capabilities-for-2024/"><u>Reimagining PPTs with Today's Webcam Capabilities for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/rethinking-trust-a-closer-look-at-zerogpt/"><u>Rethinking Trust: A Closer Look at ZeroGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/rewriting-the-rulebook-on-language-models-meet-palm-2-by-google/"><u>Rewriting the Rulebook on Language Models – Meet PaLM 2 by Google</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-complete-overview-of-artificial-intelligence-advancements-unveiled-in-apples-wwdc-24/"><u>The Complete Overview of Artificial Intelligence Advancements Unveiled in Apple's WWDC '24</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-next-ai-leap-when-do-experts-predict-gpt-5-will-debut/"><u>The Next AI Leap – When Do Experts Predict GPT-5 Will Debut?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-power-of-chatgpt-in-providing-reliable-health-guidance-unveiling-seven-key-points/"><u>The Power of ChatGPT in Providing Reliable Health Guidance: Unveiling Seven Key Points</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-verdict-on-using-bots-for-economic-planning/"><u>The Verdict on Using Bots for Economic Planning</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-5-virtual-therapists-the-bot-revolution/"><u>Top 5 Virtual Therapists: The Bot Revolution</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-gptzeros-function-in-ai-detection/"><u>Understanding GPTZero's Function in AI Detection</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlock-the-power-of-ai-conversations-with-chatgpts-new-ios-application/"><u>Unlock the Power of AI Conversations with ChatGPT's New iOS Application!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlock-the-power-of-chatgpt-in-any-language-you-speak/"><u>Unlock the Power of ChatGPT in Any Language You Speak</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-artificial-intelligence-understanding-its-nature-and-potential-risks/"><u>Unveiling Artificial Intelligence: Understanding Its Nature & Potential Risks</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-progress-elons-ai-venture/"><u>Unveiling Progress: Elon's AI Venture</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->