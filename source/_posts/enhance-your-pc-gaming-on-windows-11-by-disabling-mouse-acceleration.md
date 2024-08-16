---
title: Enhance Your PC Gaming on Windows 11 by Disabling Mouse Acceleration
date: 2024-08-13 22:16:10
updated: 2024-08-16 12:45:27
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Enhance Your PC Gaming on Windows 11 by Disabling Mouse Acceleration
excerpt: This Article Describes Enhance Your PC Gaming on Windows 11 by Disabling Mouse Acceleration
thumbnail: https://thmb.techidaily.com/d8d6563b1e83446e0eb6eee844ba3f9b3df6929eaff9c17a0488818cf8023092.jpg
---

## Disable Driver Signature Enforcement on Windows 10 Easily

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b52a003bb57.jpg)

 On Windows 8 and Windows 10 (64-bit), Microsoft has included a feature,**driver signature enforcement** . It is a feature that is designed to ensure that users of Microsoft can only load drivers that have been signed by Microsoft.

 As much security driver signature enforcement brings us, it does also bring with it some inconveniences. For instance, when you want to use some less official drivers, old unsigned drivers or drivers developed by yourself, this feature needs to be disabled first before you can move on.

 In this post, we will show you two different methods to disable this feature by yourself.

**NOTE** : Please be aware that disabling this feature and using or installing driver that were not officially signed could cause damage to your PC. Please only do so when you fully understand what you are about to do.

[**Method One: Enable Test Signing Mode**](https://tools.techidaily.com/drivereasy/download/)
[**Method Two: Advanced Boot Option**](https://tools.techidaily.com/drivereasy/download/)

 **Method One: Enable Test Signing Mode**

 This method allows you to disable driver signature enforcement**completely** if you don’t enable it again manually.

 1) Press**Windows key** and**X** at the same time, then choose**Command Prompt(Admin)** from the list of choice.

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b52400287b2.png)
  
 When prompted with administrator permission, just click**Yes** to move on.

 2) In the command prompt window, type in the following command:

bcdedit /set testsigning on

 Make sure you have made no typo and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b5256f2d41d.jpg)

 3) Restart your computer to enter test mode. You will be able to see the watermark saying**Test Mode** on the bottom right corner of your desktop.

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b526cd6a758.jpg)

 Now you can install or use the driver you want.

 4) If you want to leave Test Mode, repeat step 1) to enter Command Prompt with administrative permission. Then in the command prompt window, type in the following command:

bcedit /set testsigning off

 Make sure you have made no typo and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b5277821eea.jpg)

 Then restart your computer into normal mode.

**Method Two: Advanced Boot Option**

 This method allows you to shut off driver signature enforcement feature for once. It is not a permanent change. Restart your computer and this feature is back on again.

 1) Press**Start** button, and then click the icon for Restart and Shut down. Now, press and hold**Shift** key when you choose**Restart** .

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b5290902f87.png)
  
 2) Choose**Troubleshoot** .

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b52950e64a6.jpg)

 3) Choose**Advanced options** .

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b52981a7af8.jpg)

 4) Now choose**Startup Settings** .

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b529a600eb2.jpg)

 5) Click the**Restart** button here.

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b529d3d6368.jpg)

 6) Press**F7** key on your keyboard to go**Disable driver signature enforcement** .

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b52a003bb57.jpg)

 7) Your PC will restart now and the driver signature enforcement feature will be disabled. You are free to install unsigned drivers as you want. As mentioned above, this is not a permanent fix and it will be gone the next time you restart your computer.

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
