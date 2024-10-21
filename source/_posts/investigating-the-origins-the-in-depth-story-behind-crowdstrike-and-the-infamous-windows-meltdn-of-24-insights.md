---
title: "Investigating the Origins: The In-Depth Story Behind CrowdStrike and the Infamous Windows Meltdn of '24 | Insights"
date: 2024-10-20T18:18:50.883Z
updated: 2024-10-21T18:19:09.417Z
tags:
  - apple
categories:
  - tech
thumbnail: https://thmb.techidaily.com/b30e132a57c74da538cd27310069cce3986f42cbd47e2bf72282d9f64808baa3.jpg
---

## Unveiling the Origins: How CrowdStrike Triggered the Windows Meltdnomaous Event of 2024 – A Historical Insight

![blue screens of death](https://www.zdnet.com/a/img/resize/eac9d76c42c0a34ae6e396e98f44792477293162/2024/07/22/8a1c7b1d-5462-44b0-ad87-f790f10be8d9/gettyimages-2162005028.jpg?auto=webp&width=1280)

Harun Ozalp/Anadolu via Getty Images

_\[Updated 24-July with details from CrowdStrike's preliminary post-incident review\]_

Microsoft Windows powers more than a billion PCs and millions of servers worldwide, many of them playing key roles in facilities that serve customers directly. So, what happens when a trusted software provider delivers an update that causes those PCs to immediately stop working?

As of July 19, 2024, we know the answer to that question: Chaos ensues.

**Also: [7 password rules to live by in 2024, according to security experts](https://www.zdnet.com/article/7-password-rules-to-live-by-in-2024-according-to-security-experts/)**

In this case, the trusted software developer is a firm called CrowdStrike Holdings, whose previous claim to fame was being the security firm that analyzed the 2016 hack of servers owned by the Democratic National Committee. That's just a quaint memory now, as the firm will forever be known as The Company That Caused [The Largest IT Outage In History](https://www.zdnet.com/article/crowdstrike-causes-windows-outage-chaos-for-airports-banks-and-more-heres-what-happened/). It grounded airplanes, cut off access to some banking systems, disrupted major healthcare networks, and threw at least one news network off the air.

[Microsoft estimates](https://blogs.microsoft.com/blog/2024/07/20/helping-our-customers-through-the-crowdstrike-outage/) that the CrowdStrike update affected 8.5 million Windows devices. That's a tiny percentage of the worldwide installed base, but as David Weston, Microsoft's Vice President for Enterprise and OS Security, notes, "the broad economic and societal impacts reflect the use of CrowdStrike by enterprises that run many critical services." According to [a Reuters report](https://www.reuters.com/technology/cybersecurity/crowdstrike-update-that-caused-global-outage-likely-skipped-checks-experts-say-2024-07-20/), "Over half of Fortune 500 companies and many government bodies such as the top US cybersecurity agency itself, the Cybersecurity and Infrastructure Security Agency, use the company's software."

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What happened?

CrowdStrike, which sells security software designed to keep systems safe from external attacks, pushed a faulty ["sensor configuration update"](https://www.crowdstrike.com/blog/falcon-update-for-windows-hosts-technical-details/) to the millions of PCs worldwide running its Falcon Sensor software. That update was, according to CrowdStrike, a "Channel File" whose function was to identify newly observed, malicious activity by cyberattackers.

Although the update file had a .sys extension, it was not itself a kernel driver. It communicates with other components in the Falcon sensor that run in the same space as the Windows kernel, the most privileged level on a Windows PC, where they interact directly with memory and hardware. CrowdStrike says a "logic error" in that code caused Windows PCs and servers to crash within seconds after they booted up, displaying a STOP error, more colloquially known as the Blue Screen of Death (BSOD).

**Also: [Microsoft is changing how it delivers Windows updates: 4 things you need to know](https://www.zdnet.com/article/microsoft-is-changing-how-it-delivers-windows-updates-4-things-you-need-to-know/)**

In a [Preliminary Post Incident Review](https://www.crowdstrike.com/falcon-content-update-remediation-and-guidance-hub/) posted on its website July 24, CrowdStrike confirmed some details about the incident that had previously been reported and added a few more. The code that failed was part of the Falcon sensor, which runs in the Windows kernel space. Version 7.11 of the sensor was released on February 28, 2024\. According to CrowdStrike, this release introduced "a new \[InterProcess Communication (IPC)\] Template Type to detect novel attack techniques that abuse Named Pipes. This release followed all Sensor Content testing procedures..."

Three additional instances of the IPC Template Type were deployed between April 8 and April 24, without incident. On July 19, the company says, "two additional IPC Template Instances were deployed. Due to a bug in the Content Validator, one of the two Template Instances passed validation despite containing problematic content data." Those instances were deployed into production. "When received by the sensor and loaded into the Content Interpreter," the report continues, "problematic content in Channel File 291 resulted in an out-of-bounds memory read triggering an exception. This unexpected exception could not be gracefully handled, resulting in a Windows operating system crash (BSOD)."

**Also: [Who needs ransomware when a faulty software update can shut down critical infrastructure?](https://www.zdnet.com/article/who-needs-ransomware-when-a-faulty-software-update-can-shut-down-critical-infrastructure/)**

Repairing the damage from a flaw like this is a painfully tedious process that requires manually rebooting every affected PC into the Windows Recovery Environment and then deleting the defective file from the PC using the old-school command line interface. If the PC in question has its system drive protected by Microsoft's BitLocker encryption software, as virtually all business PCs do, the fix requires one extra step: entering a unique 48-character BitLocker recovery key to gain access to the drive and allow the removal of the faulty CrowdStrike driver.

If you know anyone whose job involves administering Windows PCs in a corporate network that uses the CrowdStrike code, you can be confident they are very busy right now, and will be for days to come.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484910/16446" target="_top" id="1484910">
  <img src="//a.impactradius-go.com/display-ad/16446-1484910" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484910/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## We've seen this movie before

When I first heard about this catastrophe (and I am not misusing that word, I assure you), I thought it sounded familiar. On Reddit's Sysadmin Subreddit, user u/externedguy [reminded me why](https://www.reddit.com/r/sysadmin/comments/1e7488p/turns%5Fout%5Fceo%5Fof%5Fcrowdstrike%5Fis%5Fformer%5Fcto%5Fof/). Maybe you remember this story from 14 years ago:

> **["Defective McAfee update causes worldwide meltdown of XP PCs."](https://www.zdnet.com/article/defective-mcafee-update-causes-worldwide-meltdown-of-xp-pcs/)**
> 
> Oops, they did it again.
> 
> At 6AM today, McAfee released an update to its antivirus definitions for corporate customers that had a slight problem. And by "slight problem," I mean the kind that renders a PC useless until tech support shows up to repair the damage manually. As I commented on Twitter earlier today, I'm not sure any virus writer has ever developed a piece of malware that shut down as many machines as quickly as McAfee did today.

In that case, McAfee had delivered a faulty virus definition (DAT) file to PCs running Windows XP. That file falsely detected a crucial Windows system file, Svchost.exe, as a virus and deleted it. The result, according to [a contemporary report](https://isc.sans.edu/diary/McAfee+DAT+5958+Update+Issues/8656), is that "affected systems will enter a reboot loop and \[lose\] all network access."

**Also: [The best VPN services: Expert tested and reviewed](https://www.zdnet.com/article/best-vpn/)**

The parallels between that 2010 incident and this year's CrowdStrike outage are uncanny. At its core was a defective update, pushed to millions of PCs running a powerful software agent, causing the affected devices to stop working. Recovery required manual intervention on every single device. Plus, the flawed code was pushed out by a public security company desperately trying to grow in a brutally competitive marketplace.

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

The timing was particularly unfortunate for McAfee. Intel had [announced its intention to acquire McAfee for $7.68 billion](https://www.intc.com/news-events/press-releases/detail/733/intel-to-acquire-mcafee) on April 19, 2010\. The defective DAT file was released two days later, on April 21.

That 2010 McAfee screw-up was a big deal, kneecapping Fortune 500 companies (including Intel!) as well as universities and government/military deployments worldwide. It knocked 10% of the cash registers at Australia's largest grocery chain offline, forcing the closure of 14 to 18 stores.

**Also: [5 ways to save your Windows 10 PC in 2025 - and most are free](https://www.zdnet.com/article/5-ways-to-save-your-windows-10-pc-in-2025-and-most-are-free/)**

In the You Can't Make This Up Department… CrowdStrike's founder and CEO, George Kurtz, was McAfee's Chief Technology Officer during that 2010 incident.

What makes the 2024 sequel so much worse is that it also affected Windows-based servers running in the cloud, on Microsoft Azure and on AWS. Just as with the many laptops and desktop PCs that were bricked by this faulty update, the cloud-based servers require time-consuming manual interventions to recover.

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/1943647/22993" target="_top" id="1943647">
  <img src="//a.impactradius-go.com/display-ad/22993-1943647" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943647/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## CrowdStrike's QA failed

Surprisingly, this isn't CrowdStrike's first faulty Falcon sensor update this year.

Less than a month earlier, [according to a report from The Stack](https://www.thestack.technology/crowdstrike-bug-maxes-out-100-of-cpu-requires-windows-reboots/), CrowdStrike released a detection logic update for the Falcon sensor that exposed a bug in the sensor's Memory Scanning feature. "The result of the bug," CrowdStrike wrote in a customer advisory, "is a logic error in the CsFalconService that can cause the Falcon sensor for Windows to consume 100% of a single CPU core." The company rolled back the update, and customers were able to resume normal operations by rebooting.

**Also: [When Windows 10 support runs out, you have 5 options but only 2 are worth considering](https://www.zdnet.com/article/when-windows-10-support-ends-you-have-5-options-but-only-2-are-worth-considering/)**

At the time, computer security expert Will Thomas [noted on X/Twitter](https://x.com/BushidoToken/status/1806630671051378868), "\[T\]his just goes to show how important it is to download new updates to one machine to test it first before rolling out to the whole fleet!" 

In that 2010 incident, the root cause turned out to be [a complete breakdown of the QA process](https://www.zdnet.com/article/mcafee-admits-inadequate-quality-control-caused-pc-meltdown/). It seems self-evident that a similar failure in QA is at work here. Were these two CrowdStrike updates not tested before they were pushed out to millions of devices?

Part of the problem might be a company culture that's long on tough talk. In the most recent CrowdStrike earnings call, CEO George Kurtz boasted about the company's ability to "ship game-changing products at a rapid pace," taking special aim at Microsoft:

> And more recently, following yet another major Microsoft breach in CIS' Cyber Safety Review Board's findings, we received an outpouring of requests from the market for help. We decided enough is enough, there's a widespread crisis of confidence among security and IT teams within the Microsoft security customer base.
> 
> \[…\]
> 
> Feedback has been overwhelmingly positive. CISAs now have the ability to reduce monoculture risk from only using Microsoft products and cloud services. Our innovation continues at breakneck pace multiplying the reasons for the market to consolidate on Falcon. Thousands of organizations are consolidating on the Falcon platform.

Given recent events, some of those customers might be wondering whether that "breakneck pace" is part of the problem.

As part of its initial response, CrowdStrike says it plans to take additional measures to improve "software resiliency and testing." More importantly, it plans to implement a "staggered deployment strategy ... in which updates are gradually deployed to larger portions of the sensor base, starting with a canary deployment." The company also committed to provide customers with "greater control over the delivery of Rapid Response Content updates by allowing granular selection of when and where these updates are deployed."

Meanwhile, the United States House of Representatives Homeland Security Committee plans to call CrowdStrike's CEO up for hearings on what went wrong, and CrowdStrike's Chief Security Officer, Shawn Henry, [posted an apology on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7220983915421806592/), admitting "On Friday, we failed you. ... The confidence we built in drips over the years was lost in buckets within hours, and it was a gut punch."

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123508/26400" target="_top" id="2123508">
  <img src="//a.impactradius-go.com/display-ad/26400-2123508" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123508/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How much fault should Microsoft shoulder?

It's impossible to let Microsoft completely off the hook. After all, the Falcon sensor problems were unique to Windows PCs, as admins of Linux and Mac-focused shops were quick to remind us.

Partly, that's an architectural issue. Developers of system-level apps for Windows, including security software, historically implement their features using kernel extensions and drivers. As this example illustrates, faulty code running in the kernel space can cause unrecoverable crashes, whereas code running in user space can't.

**Also: [7 ways to make Windows 11 less annoying](https://www.zdnet.com/article/seven-ways-to-make-windows-11-less-annoying/)**

That used to be the case with MacOS as well, but in 2020, with MacOS 11, Apple changed the architecture of its flagship OS to [strongly discourage the use of kernel extensions](https://support.apple.com/guide/security/securely-extending-the-kernel-sec8e454101b/web). Instead, developers are urged to write system extensions that run in user space rather than at the kernel level. On MacOS, CrowdStrike [uses Apple's Endpoint Security Framework](https://ir.crowdstrike.com/news-releases/news-release-details/crowdstrike-bolsters-endpoint-protection-platform-new) and says using that design, "Falcon achieves the same levels of visibility, detection, and protection exclusively via a user space sensor."

Could Microsoft make the same sort of change for Windows? Perhaps, but doing so would certainly bring down the wrath of antitrust regulators, especially in Europe. The problem is especially acute because Microsoft has a lucrative enterprise security business, and any architectural change that makes life more difficult for competitors like CrowdStrike would be rightly seen as anticompetitive.

Indeed, a Microsoft spokesperson told the Wall Street Journal that it can't follow Apple's lead because of antitrust concerns. [According to the WSJ report](https://www.wsj.com/tech/cybersecurity/microsoft-tech-outage-role-crowdstrike-50917b90?st=n4q3srxshb10vz3&reflink=desktopwebshare%5Fpermalink), "In 2009, Microsoft agreed it would give makers of security software the same level of access to Windows that Microsoft gets." That concern might be open for debate, but given Microsoft's history with EU regulators, it's understandable why the company hasn't wanted to get tangled up in that argument. 

Microsoft currently [offers APIs for Microsoft Defender for Endpoint](https://learn.microsoft.com/en-us/defender-endpoint/api/apis-intro), but competitors aren't likely to use them. They'd much rather argue that their software is superior, and using the "inferior" offering from Microsoft would be hard to explain to customers.

Nonetheless, this incident, which caused many billions of dollars' worth of damage, should be a wake-up call for the entire IT community. At a minimum, CrowdStrike needs to step up its testing game, and customers need to be more cautious about allowing this sort of code to deploy on their networks without testing it themselves.

#### Featured

[Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)](https://www.zdnet.com/article/why-im-recommending-the-standard-iphone-16-over-the-pro-this-year-and-im-not-alone/ "Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)")

[Is OneDrive messing with your files? How to get your Windows storage under control](https://www.zdnet.com/article/is-onedrive-messing-with-your-files-how-to-get-your-windows-storage-under-control/ "Is OneDrive messing with your files? How to get your Windows storage under control")

[Best early Prime Day deals under $50 to shop in October 2024](https://www.zdnet.com/article/best-early-prime-day-deals-under-50/ "Best early Prime Day deals under $50 to shop in October 2024")

[Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other](https://www.zdnet.com/article/rust-in-linux-now-progress-pitfalls-and-why-devs-and-maintainers-need-each-other/ "Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other")

* [Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)](https://www.zdnet.com/article/why-im-recommending-the-standard-iphone-16-over-the-pro-this-year-and-im-not-alone/ "Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)")
* [Is OneDrive messing with your files? How to get your Windows storage under control](https://www.zdnet.com/article/is-onedrive-messing-with-your-files-how-to-get-your-windows-storage-under-control/ "Is OneDrive messing with your files? How to get your Windows storage under control")
* [Best early Prime Day deals under $50 to shop in October 2024](https://www.zdnet.com/article/best-early-prime-day-deals-under-50/ "Best early Prime Day deals under $50 to shop in October 2024")
* [Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other](https://www.zdnet.com/article/rust-in-linux-now-progress-pitfalls-and-why-devs-and-maintainers-need-each-other/ "Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other")

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
<li><a href="https://youtube-webster.techidaily.com/ptimizing-content-visibility-premier-tracking-applications-for-youtubers-for-2024/"><u>[New] Optimizing Content Visibility - Premier Tracking Applications for YouTubers for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-separate-visual-elements-videos-to-pics-via-windows-10-photos/"><u>2024 Approved Separate Visual Elements Videos to Pics via Windows 10 Photos</u></a></li>
<li><a href="https://tech-hub.techidaily.com/airpods-pro-review-do-these-earbuds-justify-the-hype-insights-from-a-tech-expert-on-zdnet/"><u>AirPods Pro Review: Do These Earbuds Justify the Hype? Insights From a Tech Expert on ZDNet</u></a></li>
<li><a href="https://discover-excellent.techidaily.com/boosting-readership-through-shares-seamlessly-promote-your-page-flipping-ebooks-on-facebook-twitter-and-linkedin-with-flipbuilder/"><u>Boosting Readership Through Shares: Seamlessly Promote Your Page-Flipping eBooks on Facebook, Twitter, and LinkedIn with FlipBuilder</u></a></li>
<li><a href="https://win-latest.techidaily.com/comment-transferer-en-douce-voie-les-photographies-de-votre-mac-vers-une-disquette-externe-strategies-efficaces/"><u>Comment Transférer en Douce Voie Les Photographies De Votre Mac Vers Une Disquette Externe : Stratégies Efficaces</u></a></li>
<li><a href="https://tech-hub.techidaily.com/comparing-top-tech-giants-apple-vs-dell-in-the-ultimate-2024-computer-showdown-insights/"><u>Comparing Top Tech Giants: Apple Vs. Dell in the Ultimate 2024 Computer Showdown - Insights</u></a></li>
<li><a href="https://tech-hub.techidaily.com/expert-insights-on-ipad-air-with-m2-chip-the-best-tablet-to-invest-in-according-to-apple-enthusiasts/"><u>Expert Insights on iPad Air with M2 Chip: The Best Tablet to Invest in According to Apple Enthusiasts</u></a></li>
<li><a href="https://tech-hub.techidaily.com/face-off-between-the-oculus-quest-3-and-apple-glasses-was-zuckerberg-right-tech-analysis-by-zdnet/"><u>Face-Off Between the Oculus Quest 3 and Apple Glasses: Was Zuckerberg Right? | Tech Analysis by ZDNet</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-enable-usb-debugging-on-a-locked-poco-m6-pro-4g-phone-by-drfone-android/"><u>How To Enable USB Debugging on a Locked Poco M6 Pro 4G Phone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-icloud-lock-on-your-apple-iphone-12-pro-max-and-ipad-by-drfone-ios/"><u>How to fix iCloud lock on your Apple iPhone 12 Pro Max and iPad</u></a></li>
<li><a href="https://techidaily.com/is-your-vivo-v30-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Vivo V30 working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/key-decision-points-avoiding-pitfalls-in-monitor-shopping/"><u>Key Decision Points: Avoiding Pitfalls in Monitor Shopping</u></a></li>
<li><a href="https://tech-hub.techidaily.com/revolutionary-eye-controlled-technology-unveiled-by-apple-for-ios-devices-zdnet/"><u>Revolutionary Eye-Controlled Technology Unveiled by Apple for iOS Devices - ZDNet</u></a></li>
<li><a href="https://tech-hub.techidaily.com/secure-your-early-access-get-the-latest-apple-watch-series-10-in-advance-tips-for-savings-and-pre-ordering-process-insights/"><u>Secure Your Early Access: Get the Latest Apple Watch Series 10 in Advance! Tips for Savings & Pre-Ordering Process - Insights</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-3-essential-gadgets-to-maintain-the-fresh-look-of-your-iphone-13-a-guide-by-zdnet/"><u>Top 3 Essential Gadgets to Maintain the Fresh Look of Your iPhone 13: A Guide by ZDNet</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ultimate-guide-securely-syncing-and-backing-up-your-iphone-using-icloudmac-tips/"><u>Ultimate Guide: Securely Syncing and Backing Up Your iPhone Using iCloud/Mac - Tips</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-if-you-want-to-know-the-best-apps-to-animate-text-on-your-phone-check-it-out-for-2024/"><u>Updated If You Want to Know the Best Apps to Animate Text on Your Phone, Check It Out for 2024</u></a></li>
</ul></div>

