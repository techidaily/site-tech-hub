---
title: "Resolving Snipping Tool Issues in Windows 10 & 11: A Comprehensive Fix Guide"
date: 2024-08-15T20:15:19.368Z
updated: 2024-08-16T20:15:19.368Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Resolving Snipping Tool Issues in Windows 10 & 11: A Comprehensive Fix Guide"
excerpt: "This Article Describes Resolving Snipping Tool Issues in Windows 10 & 11: A Comprehensive Fix Guide"
thumbnail: https://thmb.techidaily.com/78af3078c80b8e3712553330740f219cdae8af451a75522402de746ab069fea1.jpg
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
<li><a href="https://youtube-web.techidaily.com/erfecting-your-videos-farewell-scene/"><u>[New] Perfecting Your Video's Farewell Scene</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-lurk-to-leader-a-guide-to-impactful-reddit-interaction/"><u>[Updated] From Lurk to Leader  A Guide to Impactful Reddit Interaction</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-premier-top-5-minimalist-action-cameras-review/"><u>2024 Approved  Premier Top 5 Minimalist Action Cameras Review</u></a></li>
<li><a href="https://tech-hub.techidaily.com/assessing-potential-risks-is-chatgpt-compromising-your-privacy/"><u>Assessing Potential Risks: Is ChatGPT Compromising Your Privacy?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/browse-empower-deploying-ais-with-agentgpt/"><u>Browse, Empower: Deploying AIs with AgentGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatbot-interaction-patterns-for-realistic-discussions/"><u>Chatbot Interaction Patterns for Realistic Discussions</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-alert-6-cyber-threats-to-consider/"><u>ChatGPT Alert: 6 Cyber Threats to Consider</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-goes-mobile-discover-why-the-desktop-application-outshines-its-website-equivalent/"><u>ChatGPT Goes Mobile: Discover Why The Desktop Application Outshines Its Website Equivalent</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpts-impact-across-industries-7-key-uses-unveiled/"><u>ChatGPT's Impact Across Industries: 7 Key Uses Unveiled</u></a></li>
<li><a href="https://tech-hub.techidaily.com/cultivating-a-digital-writer-with-gpt-3-adaptability/"><u>Cultivating a Digital Writer with GPT-3 Adaptability</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discover-top-benefits-why-choose-chatgpt-for-your-medical-queries/"><u>Discover Top Benefits: Why Choose ChatGPT for Your Medical Queries</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discovering-what-you-can-achieve-with-claude-3-an-in-depth-look/"><u>Discovering What You Can Achieve with Claude 3: An In-Depth Look</u></a></li>
<li><a href="https://tech-hub.techidaily.com/easy-installation-and-effective-use-of-chatgpt-plugin-tools/"><u>Easy Installation and Effective Use of ChatGPT Plugin Tools</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-llama-2-features-uses-and-advantages/"><u>Exploring LLAMA 2: Features, Uses & Advantages</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-the-world-of-gpt-4all-insights-into-its-design-and-working-principles/"><u>Exploring the World of GPT-4All: Insights Into Its Design & Working Principles</u></a></li>
<li><a href="https://tech-hub.techidaily.com/harnessing-advanced-conversation-integrate-nvidias-rtx-chatbot-into-your-pc-experience/"><u>Harnessing Advanced Conversation: Integrate NVIDIA's RTX Chatbot Into Your PC Experience</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-honor-x50-drfone-by-drfone-virtual-android/"><u>How to Find iSpoofer Pro Activation Key On Honor X50? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-vivo-t2-5g-to-pc-drfone-by-drfone-android/"><u>How to Screen Mirroring Vivo T2 5G to PC? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-12-pro-with-a-mask-on-drfone-by-drfone-ios/"><u>How to Unlock iPhone 12 Pro with a Mask On | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-a-comprehensive-tutorial-for-customizing-video-covers-on-social-media/"><u>In 2024, A Comprehensive Tutorial for Customizing Video Covers on Social Media</u></a></li>
<li><a href="https://tech-hub.techidaily.com/innovative-study-strategies-using-chatgpt-to-boost-learning-in-schools/"><u>Innovative Study Strategies Using ChatGPT to Boost Learning in Schools</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ipogo-will-be-the-new-ispoofer-on-nokia-g310-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Nokia G310? | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-it-possible-to-use-chatgpt-for-managing-a-smart-home-system/"><u>Is It Possible to Use ChatGPT for Managing a Smart Home System?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-using-gpt-plugins-secure/"><u>Is Using GPT Plugins Secure?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/practical-ai-tips-for-peak-performance/"><u>Practical AI Tips for Peak Performance</u></a></li>
<li><a href="https://tech-hub.techidaily.com/preventing-personal-discussions-from-being-stored-by-gpt/"><u>Preventing Personal Discussions From Being Stored by GPT</u></a></li>
<li><a href="https://win-solutions.techidaily.com/red-dead-redemption-effective-solutions-to-fix-frame-drops-and-improve-gaming-speed/"><u>Red Dead Redemption ²: Effective Solutions to Fix Frame Drops & Improve Gaming Speed</u></a></li>
<li><a href="https://tech-hub.techidaily.com/reliable-or-risky-assessing-chatgpt-plugins-security/"><u>Reliable or Risky: Assessing ChatGPT Plugins' Security</u></a></li>
<li><a href="https://tech-hub.techidaily.com/seasons-change-global-warming-doesnt-follow-suit/"><u>Seasons Change, Global Warming Doesn't Follow Suit</u></a></li>
<li><a href="https://tech-hub.techidaily.com/security-audit-are-there-gaps-in-chatgpt/"><u>Security Audit: Are There Gaps in ChatGPT?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/superior-8-chatgpt-questions-for-reducing-technological-interruptions/"><u>Superior 8 ChatGPT Questions for Reducing Technological Interruptions</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-ai-evolution-at-work-6-insightful-strategies-for-survival-and-success/"><u>The AI Evolution at Work: 6 Insightful Strategies for Survival and Success</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-appeal-of-artificial-intelligence-chatbots-in-todays-digital-age/"><u>The Appeal of Artificial Intelligence Chatbots in Today's Digital Age</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-quintet-of-ai-advantages-in-cyber-fraudulence/"><u>The Quintet of AI Advantages in Cyber Fraudulence</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-ultimate-guide-to-gpt-3-in-openai-playground/"><u>The Ultimate Guide to GPT-3 in OpenAI Playground</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-troubleshooting-tips-for-missing-d3dx926dll-errors/"><u>The Ultimate Troubleshooting Tips for Missing d3dx9_26.dll Errors</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-the-drawbacks-of-ai-generated-windows-11-key-codes/"><u>Understanding the Drawbacks of AI-Generated Windows 11 Key Codes</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-the-power-of-chatgpt-in-scholarly-research-and-essay-development/"><u>Unlocking the Power of ChatGPT in Scholarly Research and Essay Development</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unmasking-deception-the-real-risk-in-googles-bard-update/"><u>Unmasking Deception: The Real Risk in Google’s Bard Update</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unpacking-microsofts-big-play-in-gaming-with-blizzard-podcast-discussion-on-innovative-ai-and-translation-tech/"><u>Unpacking Microsoft's Big Play in Gaming with Blizzard: Podcast Discussion on Innovative AI and Translation Tech</u></a></li>
<li><a href="https://tech-hub.techidaily.com/using-gpt-right-away-unlocking-real-time-power-of-chatgpts-advanced-model/"><u>Using GPT-Right Away: Unlocking Real-Time Power of ChatGPT's Advanced Model</u></a></li>
<li><a href="https://tech-hub.techidaily.com/what-is-huggingchat-unveiling-the-cost-effective-substitute-for-chatgpt/"><u>What Is HuggingChat? Unveiling the Cost-Effective Substitute for ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/which-is-more-effective-github-copilot-or-chatgpt-in-software-development/"><u>Which Is More Effective? GitHub Copilot or ChatGPT in Software Development</u></a></li>
<li><a href="https://tech-hub.techidaily.com/why-choose-the-chatgpt-desktop-version-over-the-web-interface-top-advantages/"><u>Why Choose the ChatGPT Desktop Version Over the Web Interface: Top Advantages</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->