---
title: "Updating Your Mac OS Applications: A Tutorial on Two Effective Methods - Insights"
date: 2024-10-02T20:58:10.986Z
updated: 2024-10-09T16:14:23.006Z
tags:
  - apple
categories:
  - tech
thumbnail: https://thmb.techidaily.com/b918b2416ccc3c3bc24e5dbb4922efd59cd6316c83a82113344d8ae306f1223c.jpg
---

## Two Effective Methods for Updating Applications on macOS Explained

![fullscreen-1-4-24-7-23pm](https://www.zdnet.com/a/img/resize/4d0754ca50eca284946b9049b2a02512354bb4c1/2024/01/05/f413ba01-74e1-4edb-8d1e-41b8aa539d45/fullscreen-1-4-24-7-23pm.jpg?auto=webp&width=1280)

Screen Sharing on MacOS Sonoma

Jason Perlow/ZDNET

Any time I see updates available for my MacOS machines, I immediately apply them. Why? Because those updates often contain security patches that keep my computers safe. Those updates might also contain new features for apps or performance and reliability improvements. Either way, I find these updates to be an essential part of [maintaining the security of my devices](https://www.zdnet.com/article/how-to-update-every-apple-device/) and keeping my mind at ease.

**Also: [How I purged over 175GB of files from my Mac in under a minute (and you can too)](https://www.zdnet.com/article/how-i-purged-over-175gb-of-files-from-my-mac-in-under-a-minute/)**

When I go to update a MacOS device, I know there's more than one way to approach the task -- from the App Store (via the MacOS GUI) or from the command line. Because I've spent decades [working with Linux](https://www.zdnet.com/article/thinking-about-switching-to-linux-things-you-need-to-know/), I'm 100% comfortable using the command line, so I will sometimes open the terminal app, check for upgrades, and then run them when they're available. Or, if I'm feeling a bit lazy, I'll just go the App Store route.

Let me show you both approaches.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to update MacOS apps from the App Store

**What you'll need:** The only things you'll need are an Apple device (a MacBook or iMac) and a valid user account on the machine. That's it. Let's get to the updates.

## 1\. Open the App Store

The fastest way to check and see if there are any updates available is by clicking the Apple button in the upper-left corner, where you might see something like _2 updates_ listed (indicating you have two apps that have updates available). Click that entry to open the App Store.

I have two available updates on my MacBook Pro.

Screenshot by Jack Wallen/ZDNET

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082521/7443" target="_top" id="2082521">
  <img src="//a.impactradius-go.com/display-ad/7443-2082521" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082521/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Update your apps

When the App Store opens, you can either update the apps individually (by clicking the Update button associated with the app in question) or update them all at once (by clicking Update All). During the update process, you might be prompted to close an app (or even a related app) if it's blocking the update from continuing. Should that be the case, close the app in question, return to the App Store, and click Continue from the pop-up warning.

These two apps on my MacBook Pro have pending updates.

Screenshot by Jack Wallen/ZDNET

Once the update is completed, close the App Store and you're done.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/1062447/7443" target="_top" id="1062447">
  <img src="//a.impactradius-go.com/display-ad/7443-1062447" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/1062447/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to update MacOS apps from the command line

This is a bit more complicated, for two reasons: first, you have to find out what apps are available for updating, and, second -- as with Linux -- the app names are case-sensitive.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925484/19272" target="_top" id="1925484">
  <img src="//a.impactradius-go.com/display-ad/19272-1925484" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925484/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Open the Terminal app

To run commands, you must first open the terminal app, which can be done from the Launchpad. Click the Launchpad icon in your Dock and then type _terminal_. Click the launcher to open the Terminal app.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123731/7443" target="_top" id="2123731">
  <img src="//a.impactradius-go.com/display-ad/7443-2123731" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123731/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Check for available updates

Next, you need to run the command to check for updates. The command in question is _softwareupdate_ and is used for both checking and running the updates. To check for available updates, issue the command:

sudo softwareupdate -l

You will be prompted for your sudo password (which is your MacOS user password). 

**Also: [How to update every Apple device (iPhone, iPad, Apple Watch, Mac, more)](https://www.zdnet.com/article/how-to-update-every-apple-device/)**

The -l option stands for _list_. This will print out any available app updates and, if required, it will inform you if a restart is needed to complete any recent OS updates. If you see such a warning, make sure to do the reboot to complete the process.

## 3\. Update the apps

Let's say the command lists that Apple Mail has an update available, which should be listed as _Mail_ (remember, case sensitivity). Before you update the app, make sure to close it first. Once closed, update the app with a command like this:

sudo softwareupdate -i Mail

After successfully typing your sudo password, the update will proceed. When the update completes, you may or may not have to restart the machine. (You will be informed if a reboot is necessary.) You can then re-open the app you just updated and enjoy whatever fresh features or security patches the update applied.

**Also: [The Apple products you shouldn't buy this month](https://www.zdnet.com/article/the-apple-products-you-shouldnt-buy-this-month/)** 

This is about as simple a method as you'll find to help keep your MacOS machines running smoothly and securely. Never leave an app update lingering because it often contains security patches, which are required for the health and well-being of your operating system.

#### Apple

[iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get](https://www.zdnet.com/article/iphone-16-pro-and-pro-max-hands-on/ "iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get")

[My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)](https://www.zdnet.com/article/my-biggest-regret-with-upgrading-my-iphone-to-ios-18-and-im-not-alone/ "My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)")

[We've used every iPhone 16 model and here's our best buying advice for 2024](https://www.zdnet.com/article/iphone-16-pro-max-buying-advice-2024/ "We've used every iPhone 16 model and here's our best buying advice for 2024")

[6 iOS 18 settings I changed immediately - and why you should too](https://www.zdnet.com/article/6-ios-18-settings-i-changed-immediately-and-why-you-should-too/ "6 iOS 18 settings I changed immediately - and why you should too")

* [iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get](https://www.zdnet.com/article/iphone-16-pro-and-pro-max-hands-on/ "iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get")
* [My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)](https://www.zdnet.com/article/my-biggest-regret-with-upgrading-my-iphone-to-ios-18-and-im-not-alone/ "My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)")
* [We've used every iPhone 16 model and here's our best buying advice for 2024](https://www.zdnet.com/article/iphone-16-pro-max-buying-advice-2024/ "We've used every iPhone 16 model and here's our best buying advice for 2024")
* [6 iOS 18 settings I changed immediately - and why you should too](https://www.zdnet.com/article/6-ios-18-settings-i-changed-immediately-and-why-you-should-too/ "6 iOS 18 settings I changed immediately - and why you should too")

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
<li><a href="https://screen-video-capture.techidaily.com/updated-groundbreiting-recording-solutions-for-environmental-films/"><u>[Updated] Groundbreiting Recording Solutions for Environmental Films</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-ideal-audio-recording-equipment-for-idevices-enthusiasts-for-2024/"><u>[Updated] Ideal Audio Recording Equipment for iDevices Enthusiasts for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-kinemaster-android-an-in-depth-gaming-guide-review/"><u>2024 Approved KineMaster Android An In-Depth Gaming Guide Review</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-watermark-wisdom-the-10-best-apps-reviewed/"><u>2024 Approved Watermark Wisdom The 10 Best Apps Reviewed</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discerning-dialogue-dynamos-is-gemini-pro-or-plus-chatgpt-superior/"><u>Discerning Dialogue Dynamos: Is Gemini Pro or Plus-ChatGPT Superior?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-artificial-intelligence-illusions-recognizing-and-diagnosing-hallucinations-in-ai-systems/"><u>Exploring Artificial Intelligence Illusions: Recognizing and Diagnosing Hallucinations in AI Systems</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-chatgpts-inbuilt-extensions-applications-and-uses-explained/"><u>Exploring ChatGPT's Inbuilt Extensions: Applications and Uses Explained</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-realme-12-pro-5g-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Realme 12 Pro 5G 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-accurate-is-chatgpts-medical-information-quality/"><u>How Accurate Is ChatGPT's Medical Information Quality?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-can-i-use-chatgpt-to-automate-my-homes-smart-systems/"><u>How Can I Use ChatGPT to Automate My Home's Smart Systems?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-do-these-seven-innovative-apps-harness-gpt-4-for-enhanced-performance/"><u>How Do These Seven Innovative Apps Harness GPT- 4 for Enhanced Performance?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-effective-is-chatgpt-in-regulating-smart-home-devices/"><u>How Effective Is ChatGPT in Regulating Smart Home Devices?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-to-save-your-chatgpt-chats-for-later/"><u>How to Save Your ChatGPT Chats for Later</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-generative-ai-becoming-a-new-tool-for-disinformation/"><u>Is Generative AI Becoming a New Tool for Disinformation?</u></a></li>
<li><a href="https://games-able.techidaily.com/optimal-vision-protection-eyegear/"><u>Optimal Vision Protection Eyegear</u></a></li>
<li><a href="https://hardware-help.techidaily.com/samsungs-latest-contender-the-galaxy-buds-3-pro-vs-apples-airpods-pro/"><u>Samsung's Latest Contender: The Galaxy Buds 3 Pro Vs. Apple's AirPods Pro</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-big-four-of-social-networking-fb-tw-insta-yt/"><u>The Big Four of Social Networking: FB, TW, INSTA, YT</u></a></li>
<li><a href="https://app-tips.techidaily.com/1723620194671-transform-your-android-photos-into-masterpieces-with-these-top-10-gallery-app-picks/"><u>Transform Your Android Photos Into Masterpieces with These Top 10 Gallery App Picks</u></a></li>
<li><a href="https://win11.techidaily.com/users-guide-to-the-leading-free-tool-for-downloading-vimeo-content-without-hassle/"><u>User's Guide to the Leading Free Tool for Downloading Vimeo Content Without Hassle</u></a></li>
</ul></div>

