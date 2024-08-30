---
title: "Free Up Storage: How to Regain Lost Disk Space in Your Linux VirtualBox Machine"
date: 2024-08-29T01:11:47.248Z
updated: 2024-08-30T01:11:47.248Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/c26754d00328593cefb7ceb60f51391dcd2a8dd934a3e89af40244a078e590d9.jpg
---

## Free Up Storage: How to Regain Lost Disk Space in Your Linux VirtualBox Machine

### Key Takeaways

* VirtualBox doesn't automatically shrink Linux guest disks, but you can manually reclaim disk space by zeroing out data and compacting the volume.
* You should enable dynamic allocation in VirtualBox and back up your data before proceeding with the disk compacting process.
* Use the "dd" command to zero-out empty space in the Linux guest and then use VBoxManage to compact the virtual disk image.

 VirtualBox lets you run Linux in a virtual machine, and you'll often find your virtual disks continually growing in size, even though you've been clearing them of files. I'll show you how to shrink these volumes back down to size, compacting them and saving your disk space.

##  Why Your VirtualBox Linux Guest Isn’t Automatically Shrinking

 If you've used [VirtualBox](https://remote-screen-capture.techidaily.com/updated-2024-approved-little-gamers-treasure-trove-of-joy/) with Windows guests (in virtual machine terminology the "guest" is the operating system running within the virtual machine), you're probably used to your VirtualBox disk volumes shrinking as you delete files from them, so that they only use up as much space on your physical disk as they need to contain the files in them.

 This is the intended purpose of VirtualBox's dynamic allocation feature, but it doesn't work with [Linux guests](https://extra-guidance.techidaily.com/updated-snapshot-sophistication-editing-to-dazzle/). When using a Linux guests, many users find the disks grow to their full size, and then never shrink back down as files are deleted from them.

 This is due to how Linux manages its filesystems and how it interacts with its VirtualBox host. Linux doesn't "zero out" (overwrite with empty data) files when they are deleted for performance reasons, so VirtualBox has no way to tell what data on a virtual disk is active data and which is deleted.

 You can solve this issue by zeroing that data yourself, and telling VirtualBox to compact the volume, bringing it back down to its actual size. Here's how it's done.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Reclaim Disk Space From a Linux Virtual Machine in VirtualBox

 The first thing you need to do to reclaim disk space from your Linux guests' virtual disks is ensure that dynamic allocation is enabled. If it is not, you will need to [convert your disk to a dynamically allocated disk](https://fox-info.techidaily.com/new-visualize-verve-vocalize-laughter-kapwings-toolkit/).

![How to find out whether 'Dynamically allocated storage' is enabled for your virtual disk.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/vbox-dynamic-disk-1.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
 Next, [back up your virtual disk](https://extra-information.techidaily.com/mac-and-pcs-top-10-supercharged-srt-systems-unveiled/). If something goes wrong (like a mistyped command, or your power going out part way through the process), you risk losing all the data in your Linux guest.

 Next, on your Linux guest [run the following command in the terminal](https://vimeo-videos.techidaily.com/updated-boost-your-income-with-effective-vimeo-monetization-techniques-for-2024/):

sudo dd if=/dev/zero of=/var/deleteme

 This command will write zero'd out (empty) data to the file /var/deleteme until the disk is completely full. This overwrites all of your previously deleted files, solving the problem that Linux doesn't overwrite deleted data automatically.

 Be careful using the dd command as it will overwrite data without warning! Check your commands and paths carefully before running them.

 This process could take some time depending on the size of the volume, so be patient and do not interrupt it. Once it has finished, the process will exit (possibly with an error saying that it is out of space). Once this has happened, you can delete the zeroed-out file and shut down your Linux guest:

sudo rm -rf /var/deleteme

    
                    sudo shutdown now -h

 Now the unused space on your virtual disk is zeroed out and VirtualBox will be able to reclaim the space on your host by shrinking it. The final step is to use the vboxmanage command to compact the virtual disk image. Do this by running:

        `vboxmanage modifymedium disk /path/to/image.vdi -compact`
    
 You must change /path/to/image.vdi to the path of the virtual disk you want to compact. If you are on Windows, you will need to use VBoxManage.exe like so:

VBoxManage.exe modifymedium disk /path/to/image.vdi -compact

 If VBoxManage.exe is not available from the command line on your Windows system, read on for instructions on how to enable it.

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  What Did the dd Linux Command Do?

 This method for compacting a VirtualBox Linux guest utilizes the dd command to write an empty file to disk so that empty space can be identified by VirtualBox.

 The [dd](https://ss64.com/bash/dd.html) (data duplicator) command converts and copies files, and can also be used to write data. The "if" option passed to it supplies the input file (in this case /dev/zero supplies a constant stream of zero-value data or null data). The "of" option specifies the output file, and this stream of zero data is written to it. This will continue until the disk is full as /dev/zero never stops providing null data.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Using VboxManage.exe in Windows

 By default, VBoxManage.exe isn't available on the Windows command line. You can add it by [updating your Windows system path](https://screen-mirroring-recording.techidaily.com/updated-ideal-systems-for-recording-and-streaming-athletic-competitions-for-2024/) to include the VirtualBox installation directory, or calling the full path to the executable when using it:

& "C:/Path/To/VBoxManage.exe" modifymedium disk /path/to/image.vdi -compact

 The "&" symbol, called the call operator, that executes the quoted command. This lets you use spaces in path to the executable.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
##  More About Managing VirtualBox Guests

 As your guests grow, you can [increase the size](https://tech-recovery.techidaily.com/the-ultimate-guide-16-best-free-sources-for-learning-american-sign-language/) of their virtual disks as well as [reduce them](https://screen-video-capture.techidaily.com/new-vocalvoyage-listening-and-recording-expedition-for-2024/). [Snapshotting](https://facebook-video-recording.techidaily.com/updated-fb-video-downloader-extraordinaire-mp4-transformation-for-2024/) lets you take the state of your virtual machine at a certain point in time and save it; if you later want to go back to how things were at that exact moment (for example after testing a configuration change), you can simply roll back and everything will be as it was.

 VirtualBox is a powerful virtualization tool that is used both professionally by developers to build and test software, and home users to run older software and games on modern computers, or run other operating systems without having to purchase a second machine. You can run [Windows](https://some-skills.techidaily.com/the-secrets-of-selecting-a-powerful-streaming-device-for-2024/), [Linux](https://extra-guidance.techidaily.com/updated-snapshot-sophistication-editing-to-dazzle/), [ChromeOS](https://ios-unlock.techidaily.com/in-2024-unlocking-iphone-xs-max-passcode-without-a-computer-by-drfone-ios/), Android, and other operating systems on MacOS, Windows, and Linux Hosts.

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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-the-ultimate-zenith-of-pc-gameplay/"><u>[New] 2024 Approved  The Ultimate Zenith of PC Gameplay</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-download-mp3-from-social-network-posts-for-2024/"><u>[New] Download Mp3 From Social Network Posts for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-dissecting-the-ispring-screencap-magic/"><u>[New] In 2024, Dissecting the iSpring Screencap Magic</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-innovative-strategies-for-vimeo-video-recording/"><u>[Updated] Innovative Strategies for Vimeo Video Recording</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-the-smart-approach-to-video-marketing-for-smbs-for-2024/"><u>[Updated] The SMART Approach to Video Marketing for SMBs for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-nokia-150-2023-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Nokia 150 (2023) | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-nokia-130-music-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Nokia 130 Music | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/artistic-ambitions-meet-technological-titans-bz-and-ms-merger-and-ais-creative-potential-innovation-analysis/"><u>Artistic Ambitions Meet Technological Titans: BZ & MS Merger and AI's Creative Potential [Innovation Analysis]</u></a></li>
<li><a href="https://tech-hub.techidaily.com/auto-gpt-benefits-in-absence-of-gpt-4/"><u>Auto-GPT Benefits in Absence of GPT-4</u></a></li>
<li><a href="https://tech-hub.techidaily.com/boosting-your-job-search-with-these-6-tips-for-leveraging-chatgpt/"><u>Boosting Your Job Search with These 6 Tips for Leveraging ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-and-vpn-can-they-work-together-seamlessly/"><u>ChatGPT and VPN: Can They Work Together Seamlessly?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-desktop-app-coming-soon-dont-wait-experience-our-top-open-source-choice-instead/"><u>ChatGPT Desktop App Coming Soon? Don't Wait, Experience Our Top Open-Source Choice Instead</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-your-guide-to-crafting-engaging-text-based-roleplay-games/"><u>ChatGPT: Your Guide to Crafting Engaging Text-Based Roleplay Games</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/complete-guide-of-top-video-language-translators/"><u>Complete Guide of Top Video Language Translators</u></a></li>
<li><a href="https://tech-hub.techidaily.com/comprehensive-guide-on-solving-chatgpts-plugin-communication-issues/"><u>Comprehensive Guide on Solving ChatGPT's Plugin Communication Issues</u></a></li>
<li><a href="https://tech-hub.techidaily.com/crafting-control-in-ai-alignment-quest/"><u>Crafting Control in AI Alignment Quest</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/creative-filmmaking-on-a-budget-using-smartphones-as-webcams/"><u>Creative Filmmaking on a Budget  Using Smartphones as Webcams</u></a></li>
<li><a href="https://tech-hub.techidaily.com/debunking-the-idea-why-chatgpt-cant-replace-human-writers-completely/"><u>Debunking the Idea: Why ChatGPT Can't Replace Human Writers Completely</u></a></li>
<li><a href="https://tech-hub.techidaily.com/empower-yourself-against-loneliness-using-chatgpt-strategies/"><u>Empower Yourself Against Loneliness Using ChatGPT Strategies</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/ensure-seamless-wifi-on-pc-latest-drivers-for-tp-link-devices-supports-win7-to-win10/"><u>Ensure Seamless WiFi on PC: Latest Drivers for TP-Link Devices (Supports Win7 to Win10)</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exciting-gpt-5-updates-awaiting-your-discovery/"><u>Exciting GPT-5 Updates Awaiting Your Discovery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-diagnosing-and-correcting-the-0x80072efd-glitch-in-windows-11-systems/"><u>Expert Advice on Diagnosing and Correcting the 0X80072EFD Glitch in Windows 11 Systems</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-to-utilize-chatgpt-for-tailoring-your-watchlist-choices/"><u>How to Utilize ChatGPT for Tailoring Your Watchlist Choices</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-tecno-pop-7-pro-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Tecno Pop 7 Pro Lock Screen Password?</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-vivo-s17e-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Vivo S17e? | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-the-definitive-iphone-podcast-download-guide/"><u>In 2024, The Definitive iPhone Podcast Download Guide</u></a></li>
<li><a href="https://tech-hub.techidaily.com/leading-ai-based-web-search-engines-and-applications-to-boost-your-online-research/"><u>Leading AI Based Web Search Engines and Applications to Boost Your Online Research</u></a></li>
<li><a href="https://tech-hub.techidaily.com/leveraging-ai-conversational-agents-for-productive-online-meetings/"><u>Leveraging AI Conversational Agents for Productive Online Meetings</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-image-format-change-with-dall-e-webp-output/"><u>Mastering Image Format Change with DALL-E WebP Output</u></a></li>
<li><a href="https://win-dash.techidaily.com/mastering-the-update-process-newest-hp-elitebook-8460p-drivers-for-windows-uncovered/"><u>Mastering the Update Process: Newest HP EliteBook 8460P Drivers for Windows Uncovered</u></a></li>
<li><a href="https://tech-hub.techidaily.com/maximize-productivity-integrating-chatgpt-into-your-online-team-gatherings/"><u>Maximize Productivity: Integrating ChatGPT Into Your Online Team Gatherings</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/navigate-funimates-complexities-with-ease-for-2024/"><u>Navigate Funimate's Complexities with Ease for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/openai-unveils-revolutionary-gpt-4-ai-changing-the-rules-of-technology/"><u>OpenAI Unveils Revolutionary GPT-4 AI: Changing the Rules of Technology</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/personalized-branding-made-easy-use-free-logo-templates-and-edit-for-2024/"><u>Personalized Branding Made Easy  Use Free Logo Templates and Edit for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/preserving-your-creations-shielding-art-from-generative-ai-with-nightshades/"><u>Preserving Your Creations: Shielding Art From Generative AI with Nightshades</u></a></li>
<li><a href="https://tech-hub.techidaily.com/protecting-intellectual-property-strategies-for-securely-leveraging-chatgpt-in-the-office/"><u>Protecting Intellectual Property: Strategies for Securely Leveraging ChatGPT in the Office</u></a></li>
<li><a href="https://tech-hub.techidaily.com/rediscovering-lost-ai-conversations/"><u>Rediscovering Lost AI Conversations</u></a></li>
<li><a href="https://tech-hub.techidaily.com/sculpting-the-future-originality-in-ai-visuals-with-copilot-mastery/"><u>Sculpting the Future: Originality in AI Visuals with Copilot Mastery</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/securely-save-your-favorite-facebook-films-on-chrome-for-2024/"><u>Securely Save Your Favorite Facebook Films on Chrome for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/speak-to-drive-mercedes-benz-enables-chatgpt-voice-control-on-wheels/"><u>Speak to Drive: Mercedes-Benz Enables ChatGPT Voice Control on Wheels</u></a></li>
<li><a href="https://tech-hub.techidaily.com/step-by-step-guide-implementing-and-operating-chatgpt-add-ons/"><u>Step-by-Step Guide: Implementing & Operating ChatGPT Add-Ons</u></a></li>
<li><a href="https://tech-hub.techidaily.com/streamline-your-viewing-experience-using-chatgpt-recommendations/"><u>Streamline Your Viewing Experience Using ChatGPT Recommendations</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-claudians-advantage-uncovering-claudes-best-features-over-gpt/"><u>The Claudians Advantage: Uncovering Claude's Best Features Over GPT</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/the-elite-selection-best-cordless-computer-mice-for-this-year/"><u>The Elite Selection: Best Cordless Computer Mice for This Year</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-future-of-mental-health-care-can-ai-provide-better-support/"><u>The Future of Mental Health Care: Can AI Provide Better Support?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-ultimate-resource-all-inclusive-openai-information-compendium/"><u>The Ultimate Resource - All-Inclusive OpenAI Information Compendium</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-9-imitation-chatgpt-scams-how-they-could-compromise-your-information/"><u>Top 9 Imitation ChatGPT Scams: How They Could Compromise Your Information</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-generative-artifice-intelligence-what-you-need-to-know/"><u>Understanding Generative Artifice Intelligence: What You Need to Know</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-new-possibilities-top-6-uses-of-chatgpts-coding-capabilities/"><u>Unlocking New Possibilities: Top 6 Uses of ChatGPT’s Coding Capabilities</u></a></li>
<li><a href="https://ai-voice.techidaily.com/updated-2024-approved-a-detailed-review-and-alternatives-of-vocaloid6-voice-generator/"><u>Updated 2024 Approved A Detailed Review & Alternatives of VOCALOID6 Voice Generator</u></a></li>
<li><a href="https://sound-issues.techidaily.com/windows-10-speakers-not-working-solved/"><u>Windows 10 Speakers Not Working [SOLVED]</u></a></li>
</ul></div>
