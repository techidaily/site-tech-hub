---
title: "Step-by-Step Tutorial: How To Manually Control Device Driver Updates on Windows 10"
date: 2024-08-15T20:13:54.393Z
updated: 2024-08-16T20:13:54.393Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Step-by-Step Tutorial: How To Manually Control Device Driver Updates on Windows 10"
excerpt: "This Article Describes Step-by-Step Tutorial: How To Manually Control Device Driver Updates on Windows 10"
thumbnail: https://thmb.techidaily.com/a34b3784d5ea8d0b2be6eaec5083d1cf0c7c6de5e3aae650ea39b1f4ae6fa12f.jpg
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
<li><a href="https://instagram-video-files.techidaily.com/new-cutting-down-video-lengths-the-ultimate-mac-guide-for-insta-for-2024/"><u>[New] Cutting Down Video Lengths  The Ultimate Mac Guide for Insta for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-unpacking-features-a-deep-dive-into-free2xs-tools-for-2024/"><u>[New] Unpacking Features  A Deep Dive Into Free2X's Tools for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-enhancing-yt-experience-handling-several-videos-at-a-time-for-2024/"><u>[Updated] Enhancing YT Experience  Handling Several Videos at a Time for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-unlock-your-view-best-bargain-cam-recording-apps/"><u>[Updated] In 2024, Unlock Your View  Best Bargain Cam Recording Apps</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-perilous-pathways-decades-10-adventures/"><u>[Updated] Perilous Pathways  Decade’s #10 Adventures</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-personalized-video-setups-a-beginners-guide-to-selfies-on-youtube/"><u>[Updated] Personalized Video Setups  A Beginner's Guide to Selfies on YouTube</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-grasping-social-media-success-basic-facebook-statistics/"><u>2024 Approved  Grasping Social Media Success  Basic Facebook Statistics</u></a></li>
<li><a href="https://extra-information.techidaily.com/64gb-ideal-for-light-video-content-for-2024/"><u>64Gb  Ideal for Light Video Content for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/a-compreenas-remove-old-ps5-saved-files-and-backups-quickly/"><u>A Compreenas Remove Old PS5 Saved Files and Backups Quickly</u></a></li>
<li><a href="https://tech-hub.techidaily.com/a-freelancers-guide-to-optimizing-chatgpt-in-your-writing-projects/"><u>A Freelancer’s Guide to Optimizing ChatGPT in Your Writing Projects</u></a></li>
<li><a href="https://tech-hub.techidaily.com/a-step-by-step-guide-to-empower-your-spreadsheets-using-chatgpt-and-google-sheets-synergy/"><u>A Step-by-Step Guide to Empower Your Spreadsheets Using ChatGPT & Google Sheets Synergy</u></a></li>
<li><a href="https://tech-hub.techidaily.com/are-there-word-limits-to-stay-within-when-using-chatgpt/"><u>Are There Word Limits to Stay Within when Using ChatGPT?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/artificial-intelligence-and-job-uncertainty/"><u>Artificial Intelligence and Job Uncertainty</u></a></li>
<li><a href="https://tech-hub.techidaily.com/artists-claim-vindication-against-openaimeta-in-court/"><u>Artists Claim Vindication: Against OpenAI/Meta in Court</u></a></li>
<li><a href="https://tech-hub.techidaily.com/beyond-preset-limits-advantages-of-more-chatgpt-tokens/"><u>Beyond Preset Limits: Advantages of More ChatGPT Tokens</u></a></li>
<li><a href="https://tech-hub.techidaily.com/boost-your-bids-write-better-leveraging-chatgpt-for-winning-proposals/"><u>Boost Your Bids, Write Better: Leveraging ChatGPT for Winning Proposals</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpts-latest-update-lets-you-create-completely-custom-gpt-models/"><u>ChatGPT's Latest Update Lets You Create Completely Custom GPT Models</u></a></li>
<li><a href="https://tech-hub.techidaily.com/choosing-your-co-pilot-understanding-the-variances-between-copilot-vs-copilot-pro-upgrade-worthy/"><u>Choosing Your Co-Pilot: Understanding the Variances Between Copilot Vs. Copilot Pro - Upgrade Worthy?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/connecting-to-ai-the-ultimate-guide-to-using-quoras-poe-for-enhanced-chatbot-accessibility/"><u>Connecting to AI: The Ultimate Guide to Using Quora's POE for Enhanced Chatbot Accessibility</u></a></li>
<li><a href="https://tech-hub.techidaily.com/customizing-your-own-chatgpt-with-generative-pre-trained-transformer-gpt-a-step-by-step-guide/"><u>Customizing Your Own ChatGPT with Generative Pre-Trained Transformer (GPT): A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-hub.techidaily.com/cybersecurity-analysis-why-has-chatgpt-became-the-latest-focus-for-online-intruders/"><u>Cybersecurity Analysis: Why Has ChatGPT Became the Latest Focus for Online Intruders?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/device-based-learning-techniques-unveiled-an-explanation/"><u>Device-Based Learning Techniques Unveiled: An Explanation</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discover-the-impact-of-palm-2-on-refining-googles-innovative-bard-ai/"><u>Discover the Impact of PaLM 2 on Refining Google's Innovative Bard AI</u></a></li>
<li><a href="https://games-able.techidaily.com/efficient-typing-the-interplay-of-speed-and-accuracy/"><u>Efficient Typing: The Interplay of Speed & Accuracy</u></a></li>
<li><a href="https://tech-hub.techidaily.com/engage-in-privacy-focused-conversations-with-duckduckgos-ai-chat-featuring-chatgpt-and-beyond/"><u>Engage in Privacy-Focused Conversations with DuckDuckGo's AI Chat Featuring ChatGPT and Beyond</u></a></li>
<li><a href="https://tech-hub.techidaily.com/enhancing-pc-interaction-with-nvidias-ai-assistant/"><u>Enhancing PC Interaction with Nvidia’s AI Assistant</u></a></li>
<li><a href="https://tech-hub.techidaily.com/experience-the-ultimate-crime-solving-adventure-with-these-4-ai-murder-puzzles/"><u>Experience the Ultimate Crime Solving Adventure with These 4 AI Murder Puzzles</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-gptplus-subscription-merits/"><u>Exploring GPT+ Subscription Merits</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-how-natural-language-processing-differs-from-machine-learning/"><u>Exploring How Natural Language Processing Differs From Machine Learning</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-the-effects-of-machine-learning-on-emotional-health-and-therapertive-resources/"><u>Exploring the Effects of Machine Learning on Emotional Health and Therapertive Resources</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-the-world-of-chatgpt-shared-links-and-their-operation-explained/"><u>Exploring the World of ChatGPT Shared Links and Their Operation Explained</u></a></li>
<li><a href="https://tech-hub.techidaily.com/fourfold-superiority-of-claude-ai-chatbot-compared-to-chatgpt/"><u>Fourfold Superiority of Claude AI Chatbot Compared to ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1722124800989-genuine-vs-faux-chatbots-detect-and-protect-your-data/"><u>Genuine Vs. Faux ChatBots: Detect and Protect Your Data</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-do-we-tackle-the-issue-of-keeping-advanced-ai-on-track/"><u>How Do We Tackle The Issue of Keeping Advanced AI on Track?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-to-overcome-the-most-recurrebling-chatgpt-mistakes-a-guide/"><u>How to Overcome the Most Recurrebling ChatGPT Mistakes - A Guide</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-androids-premier-tools-for-fast-fixing-vid/"><u>In 2024, Android's Premier Tools for Fast-Fixing Vid</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-remove-apple-iphone-11-sim-lock-by-drfone-ios/"><u>In 2024, How to Remove Apple iPhone 11 SIM Lock?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/leveraging-artificial-intelligence-with-chatgpt-steps-to-transforming-your-vehicle-accordingly/"><u>Leveraging Artificial Intelligence with ChatGPT: Steps to Transforming Your Vehicle Accordingly</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-narrative-skills-a-guide-to-using-chatgpt-for-enhanced-storytelling-techniques/"><u>Mastering Narrative Skills: A Guide to Using ChatGPT for Enhanced Storytelling Techniques</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mercedes-enhances-driving-experience-with-chatgpt-voice-control-technology/"><u>Mercedes Enhances Driving Experience with ChatGPT Voice Control Technology</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigate-the-job-market-with-confidence-mastering-chatgpt-for-successful-applications/"><u>Navigate the Job Market with Confidence: Mastering ChatGPT for Successful Applications</u></a></li>
<li><a href="https://tech-hub.techidaily.com/overcome-chatgpt-restrictions-with-these-4-key-insights-for-regaining-entry/"><u>Overcome ChatGPT Restrictions with These 4 Key Insights for Regaining Entry</u></a></li>
<li><a href="https://tech-hub.techidaily.com/potential-pitfalls-seven-critical-concerns-when-considering-generative-ai-for-messaging-solutions/"><u>Potential Pitfalls: Seven Critical Concerns When Considering Generative AI for Messaging Solutions</u></a></li>
<li><a href="https://tech-hub.techidaily.com/protecting-ai-communications-insights-into-why-hackers-are-drawn-to-chatgpt-systems/"><u>Protecting AI Communications: Insights Into Why Hackers Are Drawn to ChatGPT Systems</u></a></li>
<li><a href="https://tech-hub.techidaily.com/reimagining-search-the-ai-driven-path-of-microsoft-bing/"><u>Reimagining Search: The AI-Driven Path of Microsoft Bing</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolved-discordance-nvidia-and-nforce-within-windows/"><u>Resolved Discordance: Nvidia & nForce Within Windows</u></a></li>
<li><a href="https://tech-hub.techidaily.com/reviving-your-chatgpt-iphone-experience-with-nine-essential-fixes/"><u>Reviving Your ChatGPT iPhone Experience with Nine Essential Fixes</u></a></li>
<li><a href="https://tech-hub.techidaily.com/seamless-strategies-connecting-chatgpt-with-whatsapp-for-enhanced-customer-service/"><u>Seamless Strategies: Connecting ChatGPT with WhatsApp for Enhanced Customer Service</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-creativity-in-freelancing-with-chatgpts-six-methods/"><u>Unlocking Creativity in Freelancing with ChatGPT's Six Methods</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-the-best-ways-to-refine-your-chatgpt-interactions/"><u>Unveiling the Best Ways to Refine Your ChatGPT Interactions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->