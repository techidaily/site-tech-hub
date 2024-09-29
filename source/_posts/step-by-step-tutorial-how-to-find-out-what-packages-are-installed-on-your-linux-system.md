---
title: "Step-by-Step Tutorial: How to Find Out What Packages Are Installed on Your Linux System"
date: 2024-08-29T01:11:12.608Z
updated: 2024-08-30T01:11:12.608Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/6c30e06757b848b8822a0592ade3cd707135548fc958e44df6b196388e83adbe.jpg
---

## Step-by-Step Tutorial: How to Find Out What Packages Are Installed on Your Linux System

### Quick Links

* [What Are Packages on Linux Systems?](https://android-location-track.techidaily.com/top-5-tracking-apps-to-track-nokia-g22-without-them-knowing-drfone-by-drfone-virtual-android/)
* [Apt: List Installed Packages on Ubuntu](https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-apple-iphone-13-pro-to-enjoy-more-fun-drfone-by-drfone-virtual-ios/)
* [DNF: List Installed Packages on Fedora](https://extra-hints.techidaily.com/comprehensive-tutorial-inserting-text-into-photographs-on-oses/)
* [Pacman: List Installed Packages on Arch](https://fox-access.techidaily.com/updated-in-2024-visual-excellence-evaluation-selecting-between-ultrawide-and-uhd-4k/)
* [Flatpak: List Installed Packages on Any Distro](https://facebook-video-footage.techidaily.com/updated-in-2024-channel-cashflow-effective-tactics-for-monetizing-on-mobile-devices/)
* [Snap: List Installed Packages on Any Distro](https://youtube-videos.techidaily.com/protecting-data-while-transforming-youtube-videos-into-mp3-files/)
* [Why Check Installed Packages and Applications?](https://snapchat-videos.techidaily.com/updated-securing-your-snapchat-memories-mobile-recording-tips/)
* [Make Informed Decisions](https://tech-recovery.techidaily.com/enabling-extra-protection-a-guide-to-turning-on-gmails-2fa/)

### Key Takeaways

* To see installed apps on Ubuntu, use the "apt list --installed" command in your terminal, or "dnf list installed" for Fedora.
* On an Arch-based system, you can use the "pacman -Q" command.
* If you use Flatpaks or Snaps, try the "flatpak list" or "snap list" commands.

 With thousands of free Linux applications, it's easy to lose track of what you once installed but no longer use. Here's how to list the installed applications on the major Linux families, and a few methods that don't depend on your Linux distribution.

##  What Are Packages on Linux Systems?

 Packages on Linux are similar to apps or program installers on macOS and Windows—broadly speaking. They come bundled in an archive file that you typically download from a central repository. Different [Linux distributions](https://extra-approaches.techidaily.com/new-next-level-action-gopro-hero5-black-meets-hero4-silver/) use different formats to deliver these files to you—[Debian and Ubuntu](https://ai-video-apps.techidaily.com/updated-2024-approved-in-this-article-we-will-introduce-you-vn-video-editor-pro-apk-download-and-bring-you-some-of-its-alternatives/) use [DEB](https://facebook-video-share.techidaily.com/new-2024-approved-capturing-contentment-a-practical-guide-to-daily-vlogging/) files, for example, while RHEL and [Fedora](https://unlock-android.techidaily.com/full-guide-to-unlock-your-tecno-spark-20-pro-by-drfone-android/) use [RPM](https://extra-resources.techidaily.com/analyzing-the-financial-gains-of-podcasting/) files.

 Packages aren't necessarily complete, precompiled programs, however. Sometimes they're [libraries](https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-motorola-moto-g24-drfone-by-drfone-virtual-android/), which provide important functionality to other applications on your PC.

 Packages are typically installed, updated, and removed using a [package manager](https://screen-capture.techidaily.com/updated-the-ultimate-guide-to-screen-capture-tools-for-2024/). The package manager will also try to grab any dependencies when you install an application, too, so you don't need to manually hunt down every single piece of code any given application requires to operate.

 There are a few major package managers that you'll commonly encounter. Red Hat-derived distributions (like Fedora) use the `dnf` package manager, Debian-derived distributions (like Ubuntu) use `apt`, and Arch-based distributions use `pacman`. There are also a few distribution-agnostic package managers like [Snap](https://some-guidance.techidaily.com/in-2024-top-10-innovative-mobile-layering-apps-for-android-and-iphone/) and Flatpak that you can use on most any Linux system.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Apt: List Installed Packages on Ubuntu

 The `apt` command allows you to use the [package manager for the Debian distribution](https://blog-min.techidaily.com/how-to-repair-system-issues-of-iphone-xs-max-drfone-by-drfone-ios-system-repair-ios-system-repair/) and the many distributions that have sprung from it, including [Ubuntu](https://common-error.techidaily.com/overcoming-graphics-card-not-supported-hurdles-in-fortnite-for-windows-users/).

 Apt is the [replacement for the older apt-get](https://youtube-lab.techidaily.com/024-approved-best-practices-for-designing-compelling-youtube-video-thumbnails/) command. Apt and apt-get share most of their syntax, so if you find instructions that call for apt-get, you can usually substitute apt without any issue.

 To see the list of installed packages, use this command:

apt list --installed

![listing installed apps with apt](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/6-2.png) 

 As expected, the output is long and scrolls past quickly.

![The output from the apt list command](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/7-1.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To see how many entries there are, we can pipe through `wc`, as we did before.

apt list --installed | wc -l

![counting installed apps with apt and wc](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/8-1.png) 

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To find packages of interest, we can use `grep` and part of the name or topic we're interested in.

apt list --installed | grep xfonts

![Using grep to search for specific entries in the apt output](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/10-1.png) 

 To investigate a single package, use the `apt show` command with the name of the package.

apt show xml-core

![Getting the details of a single app with apt](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/9-1.png) 

Related: [apt vs. apt-get: What's the Difference on Linux?](https://youtube-lab.techidaily.com/024-approved-best-practices-for-designing-compelling-youtube-video-thumbnails/) 

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
##  DNF: List Installed Packages on Fedora

 Fedora is the most successful of the RedHat-derived desktop distributions. We'll use that to discuss listing installed applications with the `dnf` package manager.

 To list the installed packages with `dnf`, run the following command:

dnf list installed

![listing installed apps with dnf](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/1-3.png) 

 This produces an avalanche of information.

![Listing of installed apps from dnf](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/2-2.png) 

 To see how many packages were listed, we can pass the output through `wc`, with the `-l` (lines) option.

![counting the installed apps with dnf and wc](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/3-3.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 This tells us `dnf` found 1,968 installed packages. To make the output more manageable you could [pipe it into grep](https://screen-recording.techidaily.com/updated-10-superior-choices-high-end-video-conferencing-software-for-2024/), and search for packages of interest.

dnf list installed | grep terminal

![Using grep to search for specific entries in the output from dnf](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/4-1.png) 

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
 You could also [pipe the output into less](https://win-amazing.techidaily.com/hp-scanjet-driver-updates-available-install-now-for-enhanced-performance-on-windows-systems/) and use the search function within `less` to find what you are looking for.

 If you see a package in the list that you want to know more about—which is a good idea if you're considering removing it—you can use the `dnf info` command.

 You need to provide the name of the package without the platform architecture details. For example, to see the details of the package "gnome-terminal.x86\_64" you'd type:

dnf info gnome-terminal

![getting the details of a single application with dnf](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/5-2.png) 

##  Pacman: List Installed Packages on Arch

 The `pacman` package manager is used on Arch Linux and its derivatives, such as [Manjaro](https://extra-approaches.techidaily.com/in-2024-prospective-leaders-in-titling-the-top-5-online-masters-revealed/) and [EndeavourOS](https://technical-tips.techidaily.com/revive-your-macs-network-capabilities-a-step-by-step-guide-to-reconfiguring-connections/).

 To list packages using `pacman` we need to use the `-Q` (query) option.

pacman -Q

![Listing installed apps with pacman](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/11-1.png) 

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The list of packages is displayed in the terminal window.

![List of installed applications from pacman](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/12-1.png) 

 Installing a single application is likely to cause multiple packages to be installed, because of unmet dependencies. If the application requires a particular library and it isn't present on your computer, the installation will provide it. Similarly, uninstalling an application can cause several packages to be removed. So the number of applications isn't the same as the number of packages.

 To count the installed packages, we pipe the output through `wc` and use the `-l` (lines) option, as before.

pacman -Q | wc -l

![counting the installed apps with pacman and wc](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/13-1.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
 The `-i` (info) option lets us look at the details of a package.

pacman -Qi bash

![Getting information on a single app with pacman](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/14-1.png) 

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Adding the `-i` option twice can provide a bit more information, if any is available.

pacman -Qii bash

![Using the -i option twice with pacman](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/15-1.png) 

 In this case, there are some extra lines at the bottom of the listing that show where the ".bash\_profile" and ".bash\_logout" template files are located.

![extra information provided by using the -i option twice with pacman](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/16-1.png) 

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Flatpak: List Installed Packages on Any Distro

 There are ways to install applications that are [distribution](https://win11.techidaily.com/the-art-of-merging-your-guide-to-windows-efficiency/) agnostic. They're designed to be universal package managers. They install sandboxed versions of apps, including any dependencies they have. This makes it easy to install different versions of an application without having to worry about incompatibilities or cross-contamination from version to version.

 From the software developer's perspective, using a universal package manager means they only have to package their application once and they've got all distributions covered.

 The `flatpak` system is one of the two most popular universal installers. If you've used `flatpak` on your computer, you can still list the installed applications with the following command:

flatpak list

![listing installed apps with flatpak](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/17.png) 

 This lists the installed applications and the associated runtimes that have been installed to satisfy the dependencies of those applications. To see just the applications, add the `--app` option.

flatpak list --app

![listing apps and excluding supporting files using flatpak](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/18.png) 

 To see the details of an individual application, use the `info` command and the application ID of the package, not the application name.

flatpak info org.blender.Blender

![Seeing the details of a single flatpak app](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/19.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
##  Snap: List Installed Packages on Any Distro

 The other popular universal package manager is [called snap](https://some-guidance.techidaily.com/in-2024-top-10-innovative-mobile-layering-apps-for-android-and-iphone/). It is a Canonical initiative. It is used by default in the Ubuntu Software application on recent Ubuntu releases and `snap` can be installed on other distributions too.

 To list the applications that have been installed using `snap`, use this command:

snap list

![listing installed applications with snap](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/20.png) 

 To see the details for a single application, use the snap info command and the name of the application.

snap info firefox

![getting the details of a single snap app](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/06/21.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Why Check Installed Packages and Applications?

 The choice of free and [open-source applications](https://facebook-videos.techidaily.com/new-leveraging-social-media-power-optimal-use-of-hash-tags-on-fb/) available to Linux users is astonishing. For a newcomer to Linux it can be overwhelming. But it's also part of the fun. If you have a particular need, you search for a piece of software to address that need. If you don't get along with the one you find, that's no problem. There are likely to be dozens more that you can try until you find one that ticks all of your boxes.

 If you're not scrupulous about uninstalling the ones you know you won't use, they'll sit in your system [using up hard drive space](https://desktop-recording.techidaily.com/amd-gpu-revival-suite-for-2024/). If you're a programmer you'll also have unused toolkits and libraries dotted around your computer. On a desktop computer, with today's [reasonably cheap, high-capacity drives](https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-zte-nubia-z60-ultra-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/), that might not in itself be too much of a problem. On [laptops](https://location-social.techidaily.com/in-2024-how-to-changeadd-location-filters-on-snapchat-for-your-oppo-find-x6-pro-drfone-by-drfone-virtual-android/), it is more of a concern because of their smaller storage capacities.

 But whether you have the hard drive space to spare or not, hoarding unused software means software updates will take longer because you're updating all of those unused applications along with the ones that you actually do use. [System images](https://extra-approaches.techidaily.com/updated-live-links-debate-is-software-superior-to-gear/) and other [backups](https://blog-min.techidaily.com/how-to-downgrade-iphone-6-plus-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/) will be larger than necessary, will take longer to complete, and will consume more backup media.

 There's also the possibility of incompatibilities between components of installed and forgotten applications and new ones you try to install.

 In order to manage the situation, the obvious first step is to find out what is installed. Once you know what, you can review the list and decide what stays and what goes.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Make Informed Decisions

`dnf`, `apt`, and `pacman` have options that automatically find and delete orphaned and unneeded packages. But they won't find old packages that you just don't use anymore. That requires human intervention and the knowledge of what requires uninstalling. That's where these handy commands come in.

 After clearing up space, you may be interested in learning how to [install Android apps on your Linux device](https://tech-haven.techidaily.com/how-effective-and-safe-are-workout-plans-designed-by-chatgpt-for-your-unique-needs/).

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


