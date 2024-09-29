---
title: Troubleshooting Guide - Unsupported Platform Error During Intel Serial IO Driver Setup
date: 2024-08-24T11:21:35.260Z
updated: 2024-08-25T11:21:35.260Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Troubleshooting Guide - Unsupported Platform Error During Intel Serial IO Driver Setup
excerpt: This Article Describes Troubleshooting Guide - Unsupported Platform Error During Intel Serial IO Driver Setup
thumbnail: https://thmb.techidaily.com/b8679192be865a4926b833c7643d484e4a5289f4dc9b662f4833af51354f1cda.jpg
---

## Troubleshooting Guide - Unsupported Platform Error During Intel Serial IO Driver Setup

While installing Intel® Serial IO host controller driver, if you get error message **“The setup program ended prematurely because of the following error: This platform is not supported”** **,** don’t worry. The error can be easy to fix. The error would occur if I2C is not enabled in BIOS. To resolve the problem, just enable I2C in BIOS.

 [![1028](https://images.drivereasy.com/wp-content/uploads/2015/10/1028-300x244.png)](https://images.drivereasy.com/wp-content/uploads/2015/10/1028.png) 

  Please refer to the guide below how to enable I2C in BIOS.

  1\. Press **F2** during boot to enter BIOS Setup.

 2\. Go to the **Advanced** \> **Devices** \> **Onboard Devices** menu.

On the Legacy Device Configuration pane:

 3\. Set **Pins 13/14** to **I2C0\_SCL/I2C0\_SDA** .

 4\. Set **Pins 15/16** to **I2C1\_SCL/I2C1\_SDA** .

 5\. Press **F10** to save and exit BIOS Setup.

  After enabling I2C in BIOS, you can install the Intel® Serial IO host controller driver again.

 I2C is enabled for the Low Speed Custom Solutions Header. So if you don’t wish to use the Low Speed Custom Solutions Header, you don’t need to install this driver.

  If you use[Driver Easy](https://tools.techidaily.com/drivereasy/download/) to install this driver and meet this problem, follow the guide here and the problem will be resolved. Alternatively, you can skip to install this driver by clicking the arrow button and selecting**Hide this Update** .

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
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->