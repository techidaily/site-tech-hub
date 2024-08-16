---
title: "Troubleshooting Guide: Solving 'Drag & Drop' Issues in Windows"
date: 2024-08-15T20:11:19.222Z
updated: 2024-08-16T20:11:19.222Z
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-finding-the-sweet-spot-optimal-youtube-video-upload-rates-for-growth/"><u>[New] 2024 Approved  Finding the Sweet Spot  Optimal YouTube Video Upload Rates for Growth</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-2024-approved-mastering-images-in-your-instagram-profile/"><u>[New] 2024 Approved  Mastering Images in Your Instagram Profile</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-dissecting-video-self-presentation-uncovering-truthfulness-needs/"><u>[New] Dissecting Video Self-Presentation  Uncovering Truthfulness Needs</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-facebooks-most-noteworthy-tweaks-for-todays-users/"><u>[Updated] In 2024, Facebook's Most Noteworthy Tweaks for Today’s Users</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-instantly-enhance-your-facebook-experience-with-collage/"><u>[Updated] Instantly Enhance Your Facebook Experience with Collage</u></a></li>
<li><a href="https://tech-hub.techidaily.com/5-ai-powered-book-recommendation-sites-and-apps-to-find-your-next-read/"><u>5 AI-Powered Book Recommendation Sites and Apps to Find Your Next Read</u></a></li>
<li><a href="https://tech-hub.techidaily.com/comprehensive-breakdown-how-gpt4all-works/"><u>Comprehensive Breakdown: How GPT4All Works</u></a></li>
<li><a href="https://tech-hub.techidaily.com/decoding-bert-an-introduction-to-its-unique-approach-in-natural-language-processing-compared-to-gpt/"><u>Decoding BERT: An Introduction to Its Unique Approach in Natural Language Processing Compared to GPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/demystifying-generative-ai-essential-information-everyone-should-know/"><u>Demystifying Generative AI: Essential Information Everyone Should Know</u></a></li>
<li><a href="https://tech-hub.techidaily.com/disable-chatgpts-memory-retention-tips-for-securing-personal-exchange-records/"><u>Disable ChatGPT's Memory Retention: Tips for Securing Personal Exchange Records</u></a></li>
<li><a href="https://sound-issues.techidaily.com/disabling-enhanced-audio-options-in-windows-10-for-optimal-sound-quality/"><u>Disabling Enhanced Audio Options in Windows 10 for Optimal Sound Quality</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discover-these-6-powerful-no-cost-ais-similar-to-sora-from-openai/"><u>Discover These 6 Powerful, No-Cost AIs Similar to Sora From OpenAI</u></a></li>
<li><a href="https://tech-hub.techidaily.com/diving-into-deep-learning-utilizing-gpt-nate-within-openais-interactive-platform/"><u>Diving Into Deep Learning: Utilizing GPT-Nate Within OpenAI’s Interactive Platform</u></a></li>
<li><a href="https://tech-hub.techidaily.com/eagerly-anticipating-the-chatgpt-desktop-release-discover-an-amazing-open-source-option/"><u>Eagerly Anticipating the ChatGPT Desktop Release? Discover an Amazing Open Source Option</u></a></li>
<li><a href="https://tech-hub.techidaily.com/elevating-chatgpt-a-guide-to-10-custom-tweaks/"><u>Elevating ChatGPT: A Guide to 10 Custom Tweaks</u></a></li>
<li><a href="https://tech-hub.techidaily.com/explore-leading-artificial-intelligence-tools-for-advanced-online-search-experience/"><u>Explore Leading Artificial Intelligence Tools for Advanced Online Search Experience</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-the-dilemma-how-do-we-ensure-ai-acts-with-human-values/"><u>Exploring the Dilemma: How Do We Ensure AI Acts with Human Values?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-variants-how-does-gpt-4-turbo-stack-up-against-standard-gpt-4/"><u>Exploring Variants: How Does GPT- 4 Turbo Stack Up Against Standard GPT-4?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/harnessing-artifice-intelligence-top-5-mental-health-assistance-apps-with-bot-counselors/"><u>Harnessing Artifice Intelligence: Top 5 Mental Health Assistance Apps with Bot Counselors</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-to-use-chatgpt-as-a-language-translation-tool/"><u>How to Use ChatGPT as a Language Translation Tool</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-xiaomi-redmi-13c-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Xiaomi Redmi 13C | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-x-flip-pin-codepattern-lockpassword-by-drfone-android/"><u>In 2024, How to Unlock Vivo X Flip PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-ais-forecast-accurate-can-chatgpt-outshine-traditional-horoscopes-in-predicting-the-future/"><u>Is AI's Forecast Accurate: Can ChatGPT Outshine Traditional Horoscopes in Predicting the Future?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-gpt-suitable-for-editing-text/"><u>Is GPT Suitable for Editing Text?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-there-a-preset-character-or-word-quota-for-replies-generated-by-chatgpt/"><u>Is There a Preset Character or Word Quota for Replies Generated by ChatGPT?</u></a></li>
<li><a href="https://extra-information.techidaily.com/jocular-joke-crafting-a-step-by-step-guide-to-memelore/"><u>Jocular Joke-Crafting  A Step-by-Step Guide to Memelore</u></a></li>
<li><a href="https://tech-hub.techidaily.com/laughter-algorithm-computing-milestones-and-privacy-in-the-cloud/"><u>Laughter Algorithm: Computing Milestones & Privacy in the Cloud</u></a></li>
<li><a href="https://tech-hub.techidaily.com/leading-8-gpt-directives-for-diminishing-online-disturbances/"><u>Leading 8 GPT Directives for Diminishing Online Disturbances</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-creative-thinking-generating-ideas-using-mindmaps-and-chatgpt/"><u>Mastering Creative Thinking: Generating Ideas Using Mindmaps & ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-chatgpt-for-kids-five-child-friendly-practices/"><u>Navigating ChatGPT for Kids: Five Child-Friendly Practices</u></a></li>
<li><a href="https://tech-hub.techidaily.com/new-editing-functionality-added-to-dall-e-3-yet-refinement-is-essential/"><u>New Editing Functionality Added to DALL-E 3, Yet Refinement Is Essential</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/pinnacle-performance-comparison-hero5-black-and-hero4-silver-for-2024/"><u>Pinnacle Performance Comparison  Hero5 Black and Hero4 Silver for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/premium-vs-code-add-ons-elevating-your-gpt-interaction/"><u>Premium VS Code Add-Ons: Elevating Your GPT Interaction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-the-situation-when-another-software-overrides-speakers/"><u>Remedying the Situation When Another Software Overrides Speakers</u></a></li>
<li><a href="https://tech-hub.techidaily.com/seamless-customer-service-enhancement-merging-chatgpt-with-whatsapp/"><u>Seamless Customer Service Enhancement: Merging ChatGPT with WhatsApp</u></a></li>
<li><a href="https://tech-hub.techidaily.com/simplify-data-interpretation-4-ways-with-chatgpt-for-pdfs/"><u>Simplify Data Interpretation: 4 Ways with ChatGPT for PDFs</u></a></li>
<li><a href="https://tech-hub.techidaily.com/step-by-step-guide-to-enhancing-skills-through-chatgpt-from-classic-board-games-to-modern-graphic-design/"><u>Step-by-Step Guide to Enhancing Skills Through ChatGPT: From Classic Board Games to Modern Graphic Design</u></a></li>
<li><a href="https://tech-hub.techidaily.com/strategizing-for-secure-interactions-with-adaptive-ai/"><u>Strategizing for Secure Interactions with Adaptive AI</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-intersection-of-paperclip-algorithms-and-artificial-intelligence/"><u>The Intersection of Paperclip Algorithms & Artificial Intelligence</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-lowdown-on-grok-ai-what-elon-musks-new-tech-can-do-and-how-much-it-will-set-you-back/"><u>The Lowdown on Grok AI - What Elon Musk's New Tech Can Do & How Much It Will Set You Back?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-ultimate-list-of-crypto-chatgpt-bot-enhancements-boosting-interaction-and-engagement/"><u>The Ultimate List of Crypto ChatGPT Bot Enhancements: Boosting Interaction and Engagement</u></a></li>
<li><a href="https://tech-hub.techidaily.com/transform-your-workday-with-chatgpt-discover-the-seven-secrets-to-supercharged-performance/"><u>Transform Your Workday with ChatGPT: Discover the Seven Secrets to Supercharged Performance</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-ai-chatbots-how-do-they-work-and-their-rising-popularity/"><u>Understanding AI Chatbots: How Do They Work & Their Rising Popularity</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unleashing-artificnial-intelligence-navigating-bing-app-on-your-android-phone/"><u>Unleashing Artificnial Intelligence: Navigating Bing App on Your Android Phone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlock-the-potential-of-enhanced-communication-crucial-new-features-added-to-chatgpt/"><u>Unlock the Potential of Enhanced Communication: Crucial New Features Added to ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlock-the-power-of-conversation-talk-with-chatgpt-today/"><u>Unlock the Power of Conversation: Talk with ChatGPT Today</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-truthgpt-coin-a-comprehensive-guide-to-assess-its-authenticity/"><u>Unveiling TruthGPT Coin: A Comprehensive Guide to Assess Its Authenticity</u></a></li>
<li><a href="https://tech-hub.techidaily.com/what-is-grok-ai-from-elon-musk-inside-look-at-its-potential-and-price-points/"><u>What Is Grok AI From Elon Musk? Inside Look at Its Potential and Price Points</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->