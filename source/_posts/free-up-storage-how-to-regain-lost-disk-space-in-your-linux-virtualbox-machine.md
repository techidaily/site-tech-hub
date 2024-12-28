---
title: "Free Up Storage: How to Regain Lost Disk Space in Your Linux VirtualBox Machine"
date: 2024-12-21T23:01:12.999Z
updated: 2024-12-28T06:32:46.241Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Why Your VirtualBox Linux Guest Isn’t Automatically Shrinking

 If you've used [VirtualBox](https://remote-screen-capture.techidaily.com/updated-2024-approved-little-gamers-treasure-trove-of-joy/) with Windows guests (in virtual machine terminology the "guest" is the operating system running within the virtual machine), you're probably used to your VirtualBox disk volumes shrinking as you delete files from them, so that they only use up as much space on your physical disk as they need to contain the files in them.

 This is the intended purpose of VirtualBox's dynamic allocation feature, but it doesn't work with [Linux guests](https://extra-guidance.techidaily.com/updated-snapshot-sophistication-editing-to-dazzle/). When using a Linux guests, many users find the disks grow to their full size, and then never shrink back down as files are deleted from them.

 This is due to how Linux manages its filesystems and how it interacts with its VirtualBox host. Linux doesn't "zero out" (overwrite with empty data) files when they are deleted for performance reasons, so VirtualBox has no way to tell what data on a virtual disk is active data and which is deleted.

 You can solve this issue by zeroing that data yourself, and telling VirtualBox to compact the volume, bringing it back down to its actual size. Here's how it's done.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  How to Reclaim Disk Space From a Linux Virtual Machine in VirtualBox

 The first thing you need to do to reclaim disk space from your Linux guests' virtual disks is ensure that dynamic allocation is enabled. If it is not, you will need to [convert your disk to a dynamically allocated disk](https://fox-info.techidaily.com/new-visualize-verve-vocalize-laughter-kapwings-toolkit/).

![How to find out whether 'Dynamically allocated storage' is enabled for your virtual disk.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/vbox-dynamic-disk-1.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

##  What Did the dd Linux Command Do?

 This method for compacting a VirtualBox Linux guest utilizes the dd command to write an empty file to disk so that empty space can be identified by VirtualBox.

 The [dd](https://ss64.com/bash/dd.html) (data duplicator) command converts and copies files, and can also be used to write data. The "if" option passed to it supplies the input file (in this case /dev/zero supplies a constant stream of zero-value data or null data). The "of" option specifies the output file, and this stream of zero data is written to it. This will continue until the disk is full as /dev/zero never stops providing null data.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Using VboxManage.exe in Windows

 By default, VBoxManage.exe isn't available on the Windows command line. You can add it by [updating your Windows system path](https://screen-mirroring-recording.techidaily.com/updated-ideal-systems-for-recording-and-streaming-athletic-competitions-for-2024/) to include the VirtualBox installation directory, or calling the full path to the executable when using it:

& "C:/Path/To/VBoxManage.exe" modifymedium disk /path/to/image.vdi -compact

 The "&" symbol, called the call operator, that executes the quoted command. This lets you use spaces in path to the executable.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fo4lNZ84x9Q?si=WdcYPZp-9VJnZEnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-crafting-compelling-proposals-a-famebit-guide-to-channel-ads/"><u>[Updated] 2024 Approved Crafting Compelling Proposals A FameBit Guide to Channel Ads</u></a></li>
<li><a href="https://fox-place.techidaily.com/1-free-quicktime-recording-capture-videos-and-audios-at-no-cost/"><u>1. Free QuickTime Recording: Capture Videos and Audios at No Cost</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-tecno-spark-20-pro-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Tecno Spark 20 Pro | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/best-remedies-for-windows-11s-stuck-taskbar-dilemma-an-expert-guide/"><u>Best Remedies for Windows 11'S Stuck Taskbar Dilemma – An Expert Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-realme-narzo-60x-5g-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Realme Narzo 60x 5G | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/streamline-your-presence-optimal-obs-use-on-facebook-feed-for-2024/"><u>Streamline Your Presence Optimal OBS Use on Facebook Feed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-bypass-difficulty-in-installing-version-22h2-of-win11-updater/"><u>Techniques to Bypass Difficulty in Installing Version 22H2 of Win11 Updater</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-5-artificial-intelligence-tools-altering-commerce-landscape/"><u>Top 5 Artificial Intelligence Tools Altering Commerce Landscape</u></a></li>
<li><a href="https://tech-hub.techidaily.com/transform-interaction-5-innovative-ways-to-direct-chatgpt-through-voice-commands/"><u>Transform Interaction: 5 Innovative Ways to Direct ChatGPT Through Voice Commands</u></a></li>
<li><a href="https://tech-hub.techidaily.com/troubleshoot-your-chatgpt-connection-with-these/"><u>Troubleshoot Your ChatGPT Connection with These</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/twitters-emoji-free-linuss-unmasking-insights-trojans-explored-and-chatgpt-flaws-highlighted/"><u>Twitters Emoji-Free, Linus's Unmasking Insights, Trojans Explored, & ChatGPT Flaws Highlighted</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unbelievable-discovery-communicating-with-chatgpt/"><u>Unbelievable Discovery: Communicating With ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-ai-language-the-top-29-terminologies-to-familiarize-yourself-with/"><u>Understanding AI Language: The Top 29 Terminologies to Familiarize Yourself With</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-generative-artificial-intelligence-functionality-and-business-implementations/"><u>Understanding Generative Artificial Intelligence – Functionality and Business Implementations</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-the-potential-of-unique-ai-visuals-with-microsofts-image-creator-tool/"><u>Unlocking the Potential of Unique AI Visuals with Microsoft's Image Creator Tool</u></a></li>
</ul></div>

