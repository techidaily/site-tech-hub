---
title: "Fresh Start: Troubleshooting and Solutions for 'Error 500 (Internal Server Error)' In Google Chrome"
date: 2024-08-15T20:11:48.632Z
updated: 2024-08-16T20:11:48.632Z
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
<li><a href="https://some-knowledge.techidaily.com/new-garmins-action-camera-triumph-a-comprehensible-look-at-ultra-30/"><u>[New] Garmin's Action Camera Triumph - A Comprehensible Look at Ultra 30</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-overcome-noisy-calls-solutions-for-zoom-audio-issues/"><u>[New] Overcome Noisy Calls  Solutions for Zoom Audio Issues</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-uncomplicated-podcast-live-master-the-art-of-livestreaming/"><u>[New] Uncomplicated Podcast Live  Master the Art of Livestreaming</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-enrich-your-viewing-experience-with-these-leading-top-6-tools-to-download-youtubes-short-videos/"><u>[Updated] 2024 Approved  Enrich Your Viewing Experience with These Leading Top 6 Tools to Download YouTubes' Short Videos</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-top-10-stress-relieving-games-for-2024/"><u>[Updated] Top 10 Stress Relieving Games for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-unlock-the-power-of-engagement-to-monetize-facebook-for-2024/"><u>[Updated] Unlock the Power of Engagement to Monetize Facebook for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unlocking-full-screen-with-chrome-pip-on-any-platform/"><u>[Updated] Unlocking Full Screen with Chrome PIP on Any Platform</u></a></li>
<li><a href="https://tech-hub.techidaily.com/101-ai-tips-learning-from-9-beginner-friendly-groups/"><u>101 AI Tips: Learning From 9 Beginner-Friendly Groups</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-camera-accessories-for-travel-cinematography/"><u>2024 Approved  Camera Accessories for Travel Cinematography</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-overcoming-iphones-difficulty-in-auto-focusing-issues/"><u>2024 Approved  Overcoming iPhone's Difficulty in Auto-Focusing Issues</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-prime-picks-best-windows-phone-video-players-list/"><u>2024 Approved  Prime Picks  Best Windows Phone Video Players List</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-samsung-galaxy-a24-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Samsung Galaxy A24 Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/7-key-approaches-to-elevate-chatgpt-interactions/"><u>7 Key Approaches to Elevate ChatGPT Interactions</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-xiaomi-redmi-k70-pro-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Xiaomi Redmi K70 Pro | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/avoid-frustration-with-these-expert-solutions-s-cities-skylines-stability-issues/"><u>Avoid Frustration with These Expert Solutions 'S Cities: Skylines Stability Issues</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1721943143670-discover-how-copilot-harnesses-gpt-4s-power-without-costing-a-penny/"><u>Discover How Copilot Harnesses GPT-4's Power Without Costing a Penny</u></a></li>
<li><a href="https://tech-hub.techidaily.com/enhance-your-android-experience-with-bing-ai-chat-installation-and-tips/"><u>Enhance Your Android Experience with Bing AI Chat: Installation and Tips</u></a></li>
<li><a href="https://tech-hub.techidaily.com/essential-security-risks-to-consider-for-personal-information-when-engaging-with-chatbots/"><u>Essential Security Risks to Consider for Personal Information When Engaging With Chatbots</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ethical-use-of-ai-in-writing-lessons-from-chatgpt-experts/"><u>Ethical Use of AI in Writing: Lessons From ChatGPT Experts</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/1722669333877-experts-weigh-in-the-unparalleled-excellence-of-apples-2018-11-inch-ipad-pro-a-must-have-device/"><u>Experts Weigh In: The Unparalleled Excellence of Apple's 2018 (11-Inch) iPad Pro - A Must-Have Device!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-the-advantages-choose-claude-3-over-chatgpt-for-better-results/"><u>Exploring the Advantages: Choose Claude 3 Over ChatGPT for Better Results</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-the-best-ai-gpt-versus-bing-ai-and-google-bard/"><u>Exploring the Best AI: GPT Versus Bing AI and Google Bard</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-the-operations-of-ai-black-boxes-simplified/"><u>Exploring the Operations of AI Black Boxes Simplified</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-the-world-of-ai-chatbots-why-businesses-and-consumers-love-them/"><u>Exploring the World of AI Chatbots - Why Businesses and Consumers Love Them</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/gauging-cgps-truthfulness-in-health-advice/"><u>Gauging CGP’s Truthfulness in Health Advice</u></a></li>
<li><a href="https://tech-hub.techidaily.com/geoengineerings-promise-or-peril-in-combatting-warming/"><u>Geoengineering's Promise or Peril in Combatting Warming?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/harness-the-power-of-your-voice-to-direct-chatgpt-a-5-step-guide/"><u>Harness the Power of Your Voice to Direct ChatGPT: A 5-Step Guide</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-google-pixel-fold-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Google Pixel Fold? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-on-gionee-f3-pro-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Gionee F3 Pro Devices</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-change-your-apple-id-on-iphone-8-with-or-without-password-by-drfone-ios/"><u>How To Change Your Apple ID on iPhone 8 With or Without Password</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-to-leverage-agentgpt-for-browser-integrated-ai-agent-setup-and-controls/"><u>How to Leverage AgentGPT for Browser-Integrated AI Agent Setup and Controls</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-vivo-y100i-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Vivo Y100i for Free? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-12-pro-max-with-an-apple-watch-and-what-to-do-if-it-doesnt-work-by-drfone-ios/"><u>How to Unlock iPhone 12 Pro Max With an Apple Watch & What to Do if It Doesnt Work</u></a></li>
<li><a href="https://tech-hub.techidaily.com/hugging-face-significance-and-utility/"><u>Hugging Face: Significance & Utility</u></a></li>
<li><a href="https://tech-hub.techidaily.com/impatient-for-chatgpts-release-embrace-this-outstanding-open-source-alternative-right-away/"><u>Impatient for ChatGPT's Release? Embrace This Outstanding Open Source Alternative Right Away!</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-excellent-20-anime-opening-anthems/"><u>In 2024, Excellent 20 Anime Opening Anthems</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-poco-x6-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Poco X6? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-strategic-insights-into-aesthetic-success-for-audio-brands/"><u>In 2024, Strategic Insights Into Aesthetic Success for Audio Brands</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-youtube-income-mastery-latest-policy-guide/"><u>In 2024, YouTube Income Mastery  Latest Policy Guide</u></a></li>
<li><a href="https://tech-hub.techidaily.com/incorporating-your-own-generative-models-into-chatgpt-sessions-a-how-to-approach/"><u>Incorporating Your Own Generative Models Into ChatGPT Sessions: A How-To Approach</u></a></li>
<li><a href="https://tech-hub.techidaily.com/integrating-gpt-into-your-pcs-os/"><u>Integrating GPT Into Your PC's OS</u></a></li>
<li><a href="https://tech-hub.techidaily.com/interactive-learning-getting-started-with-nvidias-advanced-chatbot-using-the-rtx-platform/"><u>Interactive Learning: Getting Started with Nvidia's Advanced Chatbot Using the RTX Platform</u></a></li>
<li><a href="https://tech-hub.techidaily.com/keeping-a-tab-on-chatgpts-operating-health/"><u>Keeping a Tab on ChatGPT's Operating Health</u></a></li>
<li><a href="https://tech-hub.techidaily.com/maintaining-business-secrets-how-to-use-chatgpt-safely-in-your-job/"><u>Maintaining Business Secrets: How to Use ChatGPT Safely in Your Job</u></a></li>
<li><a href="https://tech-hub.techidaily.com/notion-vs-chatgpt-showdown-evaluating-top-contenders-in-the-realm-of-generative-ai-tools/"><u>Notion Vs. ChatGPT Showdown: Evaluating Top Contenders in the Realm of Generative AI Tools</u></a></li>
<li><a href="https://tech-hub.techidaily.com/pros-and-cons-why-choosing-a-local-legal-management-system-matters/"><u>Pros & Cons - Why Choosing a Local Legal Management System Matters</u></a></li>
<li><a href="https://tech-hub.techidaily.com/proving-the-worth-of-other-ais-for-automated-code-generation/"><u>Proving the Worth of Other AIs for Automated Code Generation</u></a></li>
<li><a href="https://tech-hub.techidaily.com/steps-for-accessing-chatgpts-updated-beta-features-with-web-browsing-integration/"><u>Steps for Accessing ChatGPT's Updated Beta Features with Web Browsing Integration</u></a></li>
<li><a href="https://driver-error.techidaily.com/successful-installation-guide-how-to-add-missing-drivers-for-your-device-on-windows-11-8-and-7/"><u>Successful Installation Guide: How to Add Missing Drivers for Your Device on Windows 11, 8 & 7</u></a></li>
<li><a href="https://facebook.techidaily.com/tech-trend-alert-unbundling-giphy-from-facebook-debated/"><u>Tech Trend Alert: Unbundling Giphy From Facebook Debated</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-29-most-advanced-point-of-sale-solutions-not-including-gpt/"><u>The 29 Most Advanced Point-of-Sale Solutions, Not Including GPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-decline-of-chatgpt-hacks-understanding-the-top-7-ineffective-strategies/"><u>The Decline of ChatGPT Hacks: Understanding the Top 7 Ineffective Strategies</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-next-level-of-ai-with-gpt-5-anticipating-4-key-upgrades/"><u>The Next Level of AI with GPT-5: Anticipating 4 Key Upgrades</u></a></li>
<li><a href="https://tech-hub.techidaily.com/theoretical-exploration-rethinking-the-analogy-between-the-internet-and-traditional-libraries/"><u>Theoretical Exploration: Rethinking the Analogy Between the Internet and Traditional Libraries</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-5-methods-for-gratis-entry-into-the-world-of-gpt-4/"><u>Top 5 Methods for Gratis Entry Into the World of GPT-4</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-apps-and-online-tools-to-track-realme-phone-withwithout-imei-number-by-drfone-android/"><u>Top Apps and Online Tools To Track Realme Phone With/Without IMEI Number</u></a></li>
<li><a href="https://tech-hub.techidaily.com/trust-but-verify-why-not-let-ai-handle-your-document-summaries/"><u>Trust, but Verify: Why Not Let AI Handle Your Document Summaries?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiled-at-google-io-202n-top-7-mind-blowing-features-of-the-latest-bard-ai/"><u>Unveiled at Google I/O 202N: Top 7 Mind-Blowing Features of the Latest Bard AI</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-the-power-of-claude-the-ultimate-ai-for-professionals/"><u>Unveiling the Power of Claude: The Ultimate AI for Professionals</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-the-power-of-generative-artifice-intelligence-an-in-depth-exploration/"><u>Unveiling the Power of Generative Artifice Intelligence: An In-Depth Exploration</u></a></li>
<li><a href="https://tech-hub.techidaily.com/why-claude-3-is-worth-your-attention/"><u>Why Claude 3 Is Worth Your Attention</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->