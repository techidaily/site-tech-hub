---
title: Enhanced Wine 9.0 Brings Major Upgrades to Linux Gaming and Application Experience
date: 2024-08-29T01:11:34.343Z
updated: 2024-08-30T01:11:34.343Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/winelogo.jpg
---

## Enhanced Wine 9.0 Brings Major Upgrades to Linux Gaming and Application Experience

Wine is the compatibility layer for running Windows applications and games on non-Windows platforms, including Linux, Mac, and Android. Wine 9.0 has now been released after a year of development, improving compatibility and adding some great new features.

 The Wine project announced the update this week in a blog post, saying, "This release represents a year of development effort and over 7,000 individual changes." The most important new feature might be support for WoW64, which allows 32-bit Windows software to run on a purely 64-bit operating system—before now, 32-bit applications ran in a separate 32-bit Unix process, which wasn't always an option. For example, macOS has not supported 32-bit software, and the proprietary [CrossOver compatibility layer](https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-vivo-y100a-drfone-by-drfone-virtual-android/) (based on Wine) had its own custom solution for translation. It's not enabled by default, though, because it breaks compatibility with 16-bit code and reduces OpenGL performance.

 Wine 9.0 also includes experimental support for [Wayland](https://screen-capture.techidaily.com/updated-splitcam-review/), the display system replacing X11 on many Linux distributions. Instead of running in the XWayland environment, it can do basic window management, multiple monitors, high-DPI scaling, motion events, and Vulkan support directly through Wayland. The Wayland support is not enabled by default, but once it's ready, Wine should feel more responsive on modern Linux computers with better display scaling.

 Performance and Windows compatibility is improved in Wine 9.0 as well. There's an updated Vulkan driver, a built-in Windows Media Video (WMV) decoder, and improved Direct3D support.

 Wine 9.0 is rolling out to package managers and front-ends now. It's not clear when [Valve's Proton compatibility layer](https://youtube-tips.techidaily.com/ed-in-2024-professional-level-youtube-content-via-adobe-premiere/) will be updated with the new base, but whenever that happens, Steam on Linux should work more reliably with more Windows games.

 Source: [WineHQ](https://gitlab.winehq.org/wine/wine/-/releases/wine-9.0), [OMG! Ubuntu!](https://www.omgubuntu.co.uk/2024/01/wine-9-0-released-with-new-wow64-mode-experimental-wayland-driver)

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



<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->