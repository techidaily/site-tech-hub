---
title: Banish the Blues of Manual Updates in Arch Linux - Mastering Auto-Sync for a Hitchless Pacman Performance
date: 2024-08-29T01:11:22.066Z
updated: 2024-08-30T01:11:22.066Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/hero.png
---

## Banish the Blues of Manual Updates in Arch Linux - Mastering Auto-Sync for a Hitchless Pacman Performance

### Quick Links

* [Why Mirrors Matter](https://facebook-video-share.techidaily.com/the-perfect-proposal-to-perfection-8-best-weddings-online-for-2024/)
* [Updating the Arch Mirror List Manually](https://buynow-reviews.techidaily.com/whisker-wonders-games-galore/)
* [What Is Reflector, and What Does It Do?](https://fake-location.techidaily.com/ispoofer-is-not-working-on-lenovo-thinkphone-fixed-drfone-by-drfone-virtual-android/)
* [Installing Reflector on Arch Linux](https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-narzo-60-pro-5g-phone-without-any-data-loss-by-drfone-android/)
* [Using Reflector on the Command Line](https://digital-screen-recording.techidaily.com/updated-video-sharing-warriors-which-fights-better-obs-or-twitch-studio-in-2024/)
* [Using the Reflector Service](https://windows11.techidaily.com/optimal-pc-performance-tests/)
* [Use the Timer and Update When You Want](https://youtube-clips.techidaily.com/new-dslr-vs-mirrorless-optimal-choice-for-video-production/)

### Key Takeaways

* Mirrors are servers that hold software packages in Linux repositories. Keeping your mirror list up-to-date is crucial for application installations and system updates.
* Updating the Arch mirror list manually involves generating a list of mirrors in your region, pasting it into a file, and saving it for pacman to use.
* Reflector is a utility that generates mirror lists and updates the mirrorlist file. It can be used on the command line or as a service with customizable options.

 Mirrors are servers that replicate a Linux distribution’s repositories. Arch Linux has many mirrors situated around the globe. We show you two ways to select which mirrors your Arch Linux computer uses.

##  Why Mirrors Matter

 All the software packages available to users of a Linux distribution are held in repositories. Repositories are simply internet-accessible servers. When you install an application, your package manager has to connect to a repository so that it can retrieve the installation files.

 Like all cloud-based resources, repositories face challenges with bandwidth and availability. Too many connections and network traffic and the server can become bogged down and sluggish. Hardware failures or scheduled maintenance can take a repository offline.

 Distributions use a network of copycat repositories located around the world. These allow faster connections to users by providing repositories in their regions, instead of forcing everyone to connect to the main repository.

 It’s important to make sure the list of mirrors your computer uses is up-to-date because application installations and [system updates](https://fox-access.techidaily.com/expert-picks-11-easy-waterproof-kids-camcorders-for-vlogging/) depend on them.

##  Updating the Arch Mirror List Manually

 By default, Arch doesn’t automatically update the mirrors list. It creates a mirror list at install time, but unless you take action yourself, that list is never changed.

 Updating the list manually works, but it’s not convenient. Automating the process is the best solution. But you can, if you want, update your mirror list by hand.

 The place to start is the Arch Linux [Pacman Mirrorlist Generator](https://archlinux.org/mirrorlist/). Our objective is to get a list of the mirrors in your region and some from other regions for redundancy.

![The Arch Linux mirror list generator web page](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/2.png) 

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
 I’m selecting "United Kingdom" from the scrolling list and "HTTPS" and "IPV4" from the checkboxes. I’ve selected the "Use Mirror Status" checkbox, so only active mirrors are included in the results.

 To see the results, click the "Generate List" button.

 The matching mirrors are listed. Copy this text and paste it into your editor. Note that all lines start with a hash character "#", meaning they are treated as comments. To activate a mirror, remove the hash from the start of its line.

![A generated mirror list](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/3.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
 You can repeat this process for other regions, pasting the results to your editor each time. I also selected mirrors in Germany and Sweden. That way, should the UK mirrors be down or inaccessible, pacman will try to use the mirrors from Sweden and Germany.

 pacman reads its mirrors from a file called "/etc/pacman.d/mirrorlist." You need to edit that file and replace its contents with the new list.

        `sudo gedit /etc/pacman.d/mirrorlist`
    
![Editing the mirrolist file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/4.png) 

 Replace “gedit” with your favorite editor. Copy and paste the list you’ve just created into the mirrorlist file, replacing the original contents. Save the file and close your editor.

 pacman will now use our new list.

##  What Is Reflector, and What Does It Do?

 Reflector is a utility for generating mirror lists, and optionally updating the mirrorlist file. You can use it on the command line, or as a service.

 You can pass parameters to it to choose the regions you want to use mirrors from, and you can have the results ranked by, say, download speed.

 In Arch Linux, Reflector isn’t installed by default, but in other Arch-based distributions, it might be.

##  Installing Reflector on Arch Linux

 Installing Reflector is simple, as long as you have a working mirror list. If you don’t, pacman won’t work. If that’s the case, you’ll have to go through the steps above to manually create a working mirror list.

 The pacman command is:

        `sudo pacman -S reflector`
    
![Installing Reflector on Arch Linux](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/6.png) 

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
##  Using Reflector on the Command Line

 Using Reflector on the command line can overwrite your existing mirror list, so if you want to preserve your existing mirror list as a backup, make a copy of it before you start.

        `sudo cp /etc/pacman.d/mirrorlist /etc/pacman.d/old-mirrorlist`
    
![Making a copy of the mirrorlist file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/7.png) 

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
 This example _doesn’t_ overwrite your mirror list.

        `reflector --verbose --ipv4 --protocol https --score 10 --sort rate`
    
![A mirror list generated by Reflector in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/8.png) 

 The options we used were:

* **verbose**: Give a more detailed output, where possible.
* **ipv4**: Select mirrors that support the IPv4 protocol.
* **protocol**: Select mirrors that support the specified protocol, such as HTTP, HTTPS, or FTP.
* **score**: Select a number of mirrors that [have the best scores](https://archlinux.org/mirrors/status/tier/1/). Each mirror gets a score, with lower scores being better than higher scores. This is calculated from connection delay times, average connection duration, and the percentage of successfully completed test connections. Note that the “10” in the command line refers to how many best-scored mirrors we want returned. It doesn’t refer to the score itself.
* **sort**: Sorts the results. We have opted to sort by download rate. pacman tries the mirrors in the mirror list from top to bottom, until it finds one that is working, so it makes sense to have the fastest mirror first in the list.

 Reflector supports a lot of command-line options. You won’t find them on Reflector’s man page though, you need to use its help option:

        `reflector --help`
    
![The Reflector help output in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/9.png) 

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
 As we've seen, omitting the --save option lets you dry-run Reflector commands without putting your existing mirror list at risk. Let's include the --save option so that we update our mirrorlist file. You need to use sudo when using this option.

        `sudo reflector --verbose --country DE,SE,GB --protocol https --sort rate --latest 20 --download-timeout 6 --save /etc/pacman.d/mirrorlist`
    
![Reflector generating a mirror list in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/10.png) 

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
 Our new options are:

* **country**: Select the regions we wish to include mirrors from. You can use country codes or country names.
* **latest**: We want to use the 20 most recently updated mirrors.
* **download-timeout**: Sets the duration in seconds before Reflector considers a repository offline.
* **save**: The file the results should be written to. The default location on Arch is "/etc/pacman.d/mirrorlist."

 You can view your mirror list using the cat or less commands.

        `less /etc/pacman.d/mirrorlist`
    
![Using less to view the mirrorlist](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/11.png) 

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Reflector writes a timestamped header, so you can see when the last update happened.

![The contents of the mirrorlist file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/12.png) 

##  Using the Reflector Service

 Reflector provides a service and a timer. If you enable and start the reflector.service, it’ll update your mirror list whenever you boot your computer. The downside is slower boot times.

 A better solution is to enable and start the reflector.timer instead. It’ll run the reflector.service once a week for you.

sudo systemctl enable reflector.timer

    
                    sudo systemctl start reflector.timer

![Enabling and starting the Reflector timer](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/13.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To edit the Reflector configuration file, use your favorite editor in this command:

        `sudo gedit /etc/xdg/reflector/reflector.conf`
    
![Editing the Reflector configuration file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/14.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
 You can see that the command-line options are listed on separate lines.

![The contents of the Reflector configuration file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/15.png) 

 You can change their values or add in the ones you want to use.

 To edit the configuration file for the timer, use:

        `sudo gedit /usr/lib/systemd/system/reflector.timer`
    
![Editing the Reflector timer configuration file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/16.png) 

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
 We've described [how to configure timers in-depth](https://screen-activity-recording.techidaily.com/smooth-video-capture-with-your-laptops-webcam/) in another article.

##  Use the Timer and Update When You Want

 You can manually update your mirror list at any time by running Reflector on the command line. If you turn the command into an alias or a Bash shell function, you won’t need to remember all the parameters.

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


