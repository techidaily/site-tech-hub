---
title: "Maintain Peak Performance: A Tutorial on Installing New Drivers in Windows 11"
date: 2024-08-15T20:17:53.837Z
updated: 2024-08-16T20:17:53.837Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Maintain Peak Performance: A Tutorial on Installing New Drivers in Windows 11"
excerpt: "This Article Describes Maintain Peak Performance: A Tutorial on Installing New Drivers in Windows 11"
thumbnail: https://thmb.techidaily.com/33bb4081d4eeefa2b002761f140e6d8a1ab23c4b8fc2690daa04e9c88bdd81bd.jpg
---

## Effective Winsxs Directory Management: Free Up Disk Space on Windows 11 in a Flash

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_59759c33baabd.png)

 This is among the usually asked questions: can I delete WinSxS folder to free up some disk space?

The answer is, no.

 Nor can you delete everything in the WinSxS folder, because some of the files are important for Windows to run and update. Basically, WinSxS folder is where the files needed for your Windows are, as well as backups and/or updates of those files.

 But there are many ways you can use to reduce the size for your WinSxS folder on Windows 10\. In this post, we will be introducing two of them. So you will at least have one option that works.

[**1. Use Disk Cleanup**](https://tools.techidaily.com/drivereasy/download/)

[**2. Use DISM Tool**](https://tools.techidaily.com/drivereasy/download/)

**WARNING** : It is never suggested that you use a third-party tool to cleanup your WinSxS file, since faulty deleting the whole folder or some files in the folder might end up breaking your computer, making it impossible to boot or update.

## **1\. Use Disk Cleanup**

 Disk cleanup is a built-in tool that helps you delete temporary files. To run it, just follow:

 1) On your keyboard, press**Windows logo** button, then type in**disk cleanup** . Then choose**Disk Cleanup** from the list.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b754c83e3.png)

 2) If you haven’t changed the location where you placed your system file, choose**(C:)** and click**OK** . If you have changed the file location before, choose the correct file directory accordingly.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b948ea778.png)

 3) Under**Files to delete** sector, tick the boxes before the files you don’t need anymore and then hit**OK** to delete them. Select to highlight the file name to see more detailed information if you want.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bc59c244b.png)

 4) If you need to free more space, you can also choose**Clean up system files** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf02990e3.png)

 Then you will be prompted to choose which system drive you want to clean up. Choose accordingly and the clean process will start right away.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf68b4ff6.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## **2\. Use DISM Tool**

**DISM**  stands for Deployment Image & Servicing Management. It is a tool that allows you to make changes to Windows features, packages, drivers, and international settings. In this case, we will use it to help us clean up our WinSxS folder.

 The process may take a long time. It some cases, it could take up to 30 minutes. Please don’t worry when it’s not finished after a long time. Please be patient until the process finishes.

 1) On your keyboard, press **Windows logo key**   and **X**   at the same time, then choose **Command Prompt (Admin)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1bb42138.png)
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 When prompted with the UAC, hit **Yes** to continue.

 2) In DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup

 This command helps you clean up files when your system is not in use.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1fc428ac.png)

 3) Check for possible typo. Then hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c4b394177.png)
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) In the same DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup /ResetBase

 This command helps you remove all superseded versions of every component in the component store.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c546794f7.png)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 5) Make sure you have made no typo and hit**Enter** . Wait for it to finish.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c55d520c4.png)

 6) Still in the same window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /SPSuperseded

 This command helps you reduce the amount of space used by a Service Pack.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5c8b3c70.png)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7) Make sure that you have made no typo and hit Enter.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5eb65aaf.png)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->

 If you need more assistance, feel free to leave us comment and we will see what else we can do to help.

Hope your problem solved!

* [system](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-best-practices-for-capturing-vimeo-content/"><u>[New] 2024 Approved  Best Practices for Capturing Vimeo Content</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-unveiling-the-past-essential-historical-yt-creators-for-students/"><u>[New] 2024 Approved  Unveiling the Past  Essential Historical YT Creators for Students</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-dive-into-the-world-of-interactive-video-features-on-youtube/"><u>[New] Dive Into the World of Interactive Video Features on YouTube</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-snapchat-spotlight-101-understanding-its-impact/"><u>[New] Snapchat Spotlight 101  Understanding Its Impact</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-15-youtube-originals-premium-unboxing-sessions/"><u>[New] Top 15 YouTube Originals  Premium Unboxing Sessions</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-viewers-delight-discovering-top-6-engaging-content-formats-for-2024/"><u>[New] Viewer's Delight  Discovering Top 6 Engaging Content Formats for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-essential-editing-techniques-for-yt-channel-summaries/"><u>[Updated] 2024 Approved  Essential Editing Techniques for YT Channel Summaries</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-digital-storyboard-studio/"><u>[Updated] Digital Storyboard Studio</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-lyric-video-creation-secrets-unveiled-by-lyric-video-maker/"><u>[Updated] Lyric Video Creation Secrets Unveiled by Lyric Video Maker</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-navigating-through-windows-11s-new-frontier/"><u>[Updated] Navigating Through Windows 11'S New Frontier</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-tall-tales-reimagined-edits-for-vt-videos-on-fcpx/"><u>2024 Approved  Tall Tales Reimagined  Edits for VT Videos on FCPX</u></a></li>
<li><a href="https://tech-hub.techidaily.com/5-serious-risks-why-you-should-avoid-medical-advice-from-chatgpt/"><u>5 Serious Risks: Why You Should Avoid Medical Advice From ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/bing-brings-cutting-edge-ai-to-your-fingertips-for-improved-iphone-and-android-searches/"><u>Bing Brings Cutting-Edge AI to Your Fingertips for Improved iPhone & Android Searches</u></a></li>
<li><a href="https://tech-hub.techidaily.com/boost-productivity-a-step-by-nstep-tutorial-on-linking-chatgpt-to-your-office-suite-documents/"><u>Boost Productivity: A Step-by-nStep Tutorial on Linking ChatGPT to Your Office Suite Documents</u></a></li>
<li><a href="https://tech-hub.techidaily.com/can-computers-predict-your-future-like-astrology/"><u>Can Computers Predict Your Future Like Astrology?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-and-its-code-translator-a-deep-dive-into-why-it-matters/"><u>ChatGPT and Its Code Translator - A Deep Dive Into Why It Matters</u></a></li>
<li><a href="https://tech-hub.techidaily.com/choosing-between-direct-chatgpt-and-enhanced-gpt-tools/"><u>Choosing Between Direct ChatGPT & Enhanced GPT Tools</u></a></li>
<li><a href="https://tech-hub.techidaily.com/choosing-between-local-or-not-for-your-legal-matter-pros-vs-cons-explained/"><u>Choosing Between Local or Not for Your Legal Matter - Pros vs Cons Explained</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-the-opportunities-in-openais-bug-bounty-program-how-to-join/"><u>Exploring the Opportunities in OpenAI’s Bug Bounty Program – How To Join?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-effective-is-chatgpt-in-overseeing-your-smart-home-ecosystem/"><u>How Effective Is ChatGPT in Overseeing Your Smart Home Ecosystem?</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-realme-v30t-frp-in-3-different-ways-by-drfone-android/"><u>How To Bypass Realme V30T FRP In 3 Different Ways</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-oppo-a1x-5g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Oppo A1x 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-data-from-apple-iphone-7-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Data from Apple iPhone 7? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-honor-x50-gt-contacts-an-easy-method-explained-by-fonelab-android-recover-contacts/"><u>How to Restore Deleted Honor X50 GT Contacts  An Easy Method Explained.</u></a></li>
<li><a href="https://tech-hub.techidaily.com/human-expertise-outshines-flawed-algorithms/"><u>Human Expertise Outshines Flawed Algorithms</u></a></li>
<li><a href="https://tech-hub.techidaily.com/immediate-access-to-8-unique-gpt-models-perfectly-suited-for-your-needs/"><u>Immediate Access to 8 Unique GPT Models, Perfectly Suited for Your Needs</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-honor-x9afrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Honor X9aFRP Lock</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-role-of-slug-lines-in-seo-and-marketing/"><u>In 2024, The Role of Slug Lines in SEO & Marketing</u></a></li>
<li><a href="https://tech-hub.techidaily.com/inside-ais-evolution-identifying-5-fundamental-variances-of-gpt-4-over-gpt-35/"><u>Inside AI's Evolution: Identifying 5 Fundamental Variances of GPT-4 over GPT-3.5</u></a></li>
<li><a href="https://tech-hub.techidaily.com/interpreting-sentiments-the-rise-of-emotive-computation/"><u>Interpreting Sentiments: The Rise of Emotive Computation</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-chatgpt-plus-a-valuable-investment-or-just-another-gimmick/"><u>Is ChatGPT Plus a Valuable Investment or Just Another Gimmick?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-mindfulness-against-stress-using-chatgpt-tools/"><u>Mastering Mindfulness Against Stress Using ChatGPT Tools</u></a></li>
<li><a href="https://extra-tips.techidaily.com/mastering-youtube-titulos-con-algoritmos/"><u>Mastering YouTube Títulos Con Algoritmos</u></a></li>
<li><a href="https://tech-hub.techidaily.com/maximizing-chatgpts-potential-with-usechatgpt-co-pilot-extension/"><u>Maximizing ChatGPT's Potential with UseChatGPT Co-Pilot Extension</u></a></li>
<li><a href="https://tech-hub.techidaily.com/pc-assembly-advice-for-enthusiasts-boost-your-setup-with-insider-know-how/"><u>PC Assembly Advice for Enthusiasts: Boost Your Setup with Insider Know-How</u></a></li>
<li><a href="https://tech-hub.techidaily.com/reducing-chimeric-ai-outputs-with-six-prompt-adjustments/"><u>Reducing Chimeric AI Outputs with Six Prompt Adjustments</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/resolving-non-receipt-issues-for-your-inbox-on-yahoo-mail-platform/"><u>Resolving Non-Receipt Issues for Your Inbox on Yahoo Mail Platform</u></a></li>
<li><a href="https://tech-hub.techidaily.com/revealing-your-virtual-persona-a-comprehensive-look-into-the-enigma-of-online-interactions-and-digital-dead-beliefs/"><u>Revealing Your Virtual Persona: A Comprehensive Look Into the Enigma of Online Interactions & 'Digital Dead' Beliefs</u></a></li>
<li><a href="https://tech-hub.techidaily.com/revolutionize-how-you-find-answers-bings-cutting-edge-ai-integration-ready-for-smartphones/"><u>Revolutionize How You Find Answers: Bing's Cutting-Edge AI Integration Ready for Smartphones!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/revolutionizing-customer-service-8-ways-to-use-chatgpt-effectively/"><u>Revolutionizing Customer Service: 8 Ways to Use ChatGPT Effectively</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-risks-of-relying-on-artificial-intelligence-for-creating-windows-11-product-keys/"><u>The Risks of Relying on Artificial Intelligence for Creating Windows 11 Product Keys</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-top-6-factors-to-consider-before-using-chatgpt-for-mental-health/"><u>The Top 6 Factors to Consider Before Using ChatGPT for Mental Health</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-ultimate-list-4-must-try-ai-tools-for-crafting-stories-instantly/"><u>The Ultimate List: 4 Must-Try AI Tools for Crafting Stories Instantly</u></a></li>
<li><a href="https://tech-hub.techidaily.com/trustful-talkers-integrating-chatgpt-safely/"><u>Trustful Talkers: Integrating ChatGPT Safely</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-ai-weak-points-the-science-behind-prompt-injection-attacks/"><u>Understanding AI Weak Points: The Science Behind Prompt Injection Attacks</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unfreeze-your-iphones-chatgpt-with-these-efficient-steps/"><u>Unfreeze Your iPhone's ChatGPT with These Efficient Steps</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-ai-potential-7-effective-strategies-explained/"><u>Unlocking AI Potential: 7 Effective Strategies Explained</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-free-usage-top-5-strategies-to-leverage-chatgpt-without-signing-up/"><u>Unlocking Free Usage: Top 5 Strategies to Leverage ChatGPT without Signing Up</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-chatgpts-native-tools/"><u>Unveiling ChatGPT’s Native Tools</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-the-distinctions-nlp-vs-machine-learning-explained/"><u>Unveiling the Distinctions: NLP Vs. Machine Learning Explained</u></a></li>
<li><a href="https://tech-hub.techidaily.com/what-sets-googles-new-palm-2-large-language-model-apart-from-previous-versions/"><u>What Sets Google's New PaLM 2 Large Language Model Apart From Previous Versions?</u></a></li>
<li><a href="https://facebook.techidaily.com/whatsapp-wont-limit-account-functionality-if-you-dont-accept-its-new-privacy-policy/"><u>WhatsApp Won't Limit Account Functionality If You Don't Accept Its New Privacy Policy</u></a></li>
<li><a href="https://tech-hub.techidaily.com/winning-the-focus-battle-how-these-8-chatgpt-cues-tame-distractions/"><u>Winning the Focus Battle: How These 8 ChatGPT Cues Tame Distractions</u></a></li>
</ul></div>
