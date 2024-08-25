---
title: "Auto-GPT for Ubuntu Users: Easy Install Guide"
date: 2024-08-24T11:31:32.674Z
updated: 2024-08-25T11:31:32.674Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: "This Article Describes Auto-GPT for Ubuntu Users: Easy Install Guide"
excerpt: "This Article Describes Auto-GPT for Ubuntu Users: Easy Install Guide"
thumbnail: https://thmb.techidaily.com/e0fa0d67e26442f6514904daf3cc23134382c2cc52f88c01d78e6b3f6c28c68c.jpg
---

## Llama ˈLocal-Ization' Guide: How to Install and Use It Yourself

 Meta released Llama 2 in the summer of 2023\. The new version of Llama is fine-tuned with 40% more tokens than the original Llama model, doubling its context length and significantly outperforming other open-sourced models available. The fastest and easiest way to access Llama 2 is via an API through an online platform. However, if you want the best experience, installing and loading Llama 2 directly on your computer is best.

 With that in mind, we've created a step-by-step guide on how to use Text-Generation-WebUI to load a quantized Llama 2 LLM locally on your computer.

## Why Install Llama 2 Locally

 There are many reasons why people choose to run Llama 2 directly. Some do it for privacy concerns, some for customization, and others for offline capabilities. If you're researching, fine-tuning, or integrating Llama 2 for your projects, then accessing Llama 2 via API might not be for you. The point of running an LLM locally on your PC is to reduce reliance on[third-party AI tools](https://www.makeuseof.com/best-ai-web-apps/) and use AI anytime, anywhere, without worrying about leaking potentially sensitive data to companies and other organizations.

 With that said, let's begin with the step-by-step guide to installing Llama 2 locally.

## Step 1: Install Visual Studio 2019 Build Tool

 To simplify things, we will use a one-click installer for Text-Generation-WebUI (the program used to load Llama 2 with GUI). However, for this installer to work, you need to download the Visual Studio 2019 Build Tool and install the necessary resources.

**Download:** [Visual Studio 2019](https://learn.microsoft.com/en-us/visualstudio/releases/2019/release-notes) (Free)

1. Go ahead and download the community edition of the software.
2. Now install Visual Studio 2019, then open the software. Once opened, tick the box on**Desktop development with C++** and hit install.  
![Install-Desktop-Development-With-C++](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/2-install-desktop-development-with-c.jpg)

 Now that you have Desktop development with C++ installed, it's time to download the Text-Generation-WebUI one-click installer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
## Step 2: Install Text-Generation-WebUI

 The Text-Generation-WebUI one-click installer is a script that automatically creates the required folders and sets up the Conda environment and all necessary requirements to run an AI model.

 To install the script, download the one-click installer by clicking on**Code** \>**Download ZIP.**

**Download:** [Text-Generation-WebUI Installer](https://github.com/oobabooga/text-generation-webui/tree/main) (Free)

1. Once downloaded, extract the ZIP file to your preferred location, then open the extracted folder.
2. Within the folder, scroll down and look for the appropriate start program for your operating system. Run the programs by double-clicking the appropriate script.  
   * If you are on Windows, select**start\_windows** batch file  
   * for MacOS, select**start\_macos** shell scrip  
   * for Linux,**start\_linux** shell script.  
   ![Select operating system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/4-select-operating-system.jpg)
3. Your anti-virus might create an alert; this is fine. The prompt is just an[antivirus false positive](https://www.makeuseof.com/what-is-antivirus-false-result/) for running a batch file or script. Click on**Run anyway** .
<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. A terminal will open and start the setup. Early on, the setup will pause and ask you what GPU you are using. Select the appropriate type of GPU installed on your computer and hit enter. For those without a dedicated graphics card, select**None (I want to run models in CPU mode)** . Keep in mind that running on CPU mode is much slower when compared to running the model with a dedicated GPU.  
![Selecting GPU hardware installed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/5-select-gpu-settings.jpg)
5. Once the setup is complete, you can now launch Text-Generation-WebUI locally. You can do so by opening your preferred web browser and entering the provided IP address on the URL.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
![How to launch-Text-Generation-WebUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/6-launch-text-generation-webui.jpg)
6. The WebUI is now ready for use.  
![Text-Generation-WebUI ](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/7-text-generation-webui-view.jpg)

 However, the program is only a model loader. Let's download Llama 2 for the model loader to launch.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
## Step 3: Download the Llama 2 Model

 There are quite a few things to consider when deciding which iteration of Llama 2 you need. These include parameters, quantization, hardware optimization, size, and usage. All of this information will be found denoted in the model's name.

* **Parameters:** The number of parameters used to train the model. Bigger parameters make more capable models but at the cost of performance.
* **Usage:** Can either be standard or chat. A chat model is optimized to be used as a chatbot like ChatGPT, while the standard is the default model.
* **Hardware Optimization:** Refers to what hardware best runs the model. GPTQ means the model is optimized to run on a dedicated GPU, while GGML is optimized to run on a CPU.
* **Quantization:** Denotes the precision of weights and activations in a model. For inferencing, a precision of q4 is optimal.
* **Size:** Refers to the size of the specific model.

 Note that some models may be arranged differently and may not even have the same types of information displayed. However, this type of naming convention is fairly common in the[HuggingFace](https://www.makeuseof.com/what-is-hugging-face-and-what-is-it-used-for/) Model library, so it's still worth understanding.

![HuggingFace model naming convention](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/huggingface-model-naming-convention-1.jpg)

 In this example, the model can be identified as a medium-sized Llama 2 model trained on 13 billion parameters optimized for chat inferencing using a dedicated CPU.

 For those running on a dedicated GPU, choose a**GPTQ** model, while for those using a CPU, choose**GGML** . If you want to chat with the model like you would with ChatGPT, choose**chat** , but if you want to experiment with the model with its full capabilities, use the**standard** model. As for parameters, know that using bigger models will provide better results at the expense of performance. I would personally recommend you start with a 7B model. As for quantization, use q4, as it's only for inferencing.

**Download:** [GGML](https://huggingface.co/localmodels/Llama-2-7B-ggml/tree/main) (Free)

**Download:** [GPTQ](https://huggingface.co/localmodels/Llama-2-7B-Chat-GPTQ/tree/main) (Free)

 Now that you know what iteration of Llama 2 you need, go ahead and download the model you want.

 In my case, since I'm running this on an ultrabook, I'll be using a GGML model fine-tuned for chat,**llama-2-7b-chat-ggmlv3.q4\_K\_S.bin.**

![Downloading Llama 2 model of your preference](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/8-download-llama-2-model.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
 After the download is finished, place the model in**text-generation-webui-main** \>**models** .

![Placing Llama 2 model to model folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/9-place-model-to-model-folder.jpg)

 Now that you have your model downloaded and placed in the model folder, it's time to configure the model loader.

## Step 4: Configure Text-Generation-WebUI

Now, let's begin the configuration phase.

1. Once again, open Text-Generation-WebUI by running the**start\_(your OS)** file (see the previous steps above).
2. On the tabs located above the GUI, click**Model.** Click the refresh button at the model dropdown menu and select your model.
3. Now click on the dropdown menu of the**Model loader** and select**AutoGPTQ** for those using a GTPQ model and**ctransformers** for those using a GGML model. Finally, click on**Load** to load your model.  
![Setting model loader](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/10-select-model-loader.jpg)
4. To use the model, open the Chat tab and start testing the model.  
![Testing Llama 2 locally](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/12-testing-llama-2-locally.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
 Congratulations, you've successfully loaded Llama2 on your local computer!

## Try Out Other LLMs

 Now that you know how to run Llama 2 directly on your computer using Text-Generation-WebUI, you should also be able to run other LLMs besides Llama. Just remember the naming conventions of models and that only quantized versions of models (usually q4 precision) can be loaded on regular PCs. Many quantized LLMs are available on HuggingFace. If you want to explore other models, search for TheBloke in HuggingFace's model library, and you should find many models available.


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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-whispering-through-screens-a-private-story-journey/"><u>[New] 2024 Approved  Whispering Through Screens  A Private Story Journey</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-greatest-copyright-free-pubg-image-anthology/"><u>[New] Greatest Copyright-Free PUBG Image Anthology</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-polishing-the-final-product-perfect-for-instagrams-audience/"><u>[Updated] Polishing the Final Product  Perfect for Instagram's Audience</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1-free-and-updated-kindle-ebook-drm-stripping-calibre-add-on-get-started-today/"><u>1. Free and Updated Kindle eBook DRM-Stripping Calibre Add-On - Get Started Today!</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-xiaomi-redmi-12-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Xiaomi Redmi 12</u></a></li>
<li><a href="https://fox-helps.techidaily.com/a-visual-extravaganza-detailed-examination-of-lg-ud88-uhd-tv-for-2024/"><u>A Visual Extravaganza  Detailed Examination of LG UD88-UHD TV for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-setup-service-via-command-line-utilities/"><u>Adjusting Setup Service via Command-Line Utilities</u></a></li>
<li><a href="https://extra-information.techidaily.com/allocating-budget-for-youtube-video-success-for-2024/"><u>Allocating Budget for YouTube Video Success for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discover-the-best-no-cost-audiobook-sites-for-young-readers-and-adolescents/"><u>Discover the Best No-Cost Audiobook Sites for Young Readers and Adolescents</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discover-the-ultimate-picks-top-6-audiobook-subscriptions-in-one-place/"><u>Discover The Ultimate Picks: Top 6 Audiobook Subscriptions in One Place!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/easy-steps-transforming-cbr-documents-into-editable-pdf-format/"><u>Easy Steps: Transforming CBR Documents Into Editable PDF Format</u></a></li>
<li><a href="https://tech-hub.techidaily.com/easy-tips-and-tricks-for-transforming-audiobooks-into-mp3-files/"><u>Easy Tips and Tricks for Transforming Audiobooks Into MP3 Files</u></a></li>
<li><a href="https://tech-hub.techidaily.com/efficient-audio-format-shift-switch-your-audible-aax-library-to-mp3-at-unprecedented-speeds-60x-faster/"><u>Efficient Audio Format Shift: Switch Your Audible AAX Library to MP3 at Unprecedented Speeds (60X Faster!)</u></a></li>
<li><a href="https://tech-hub.techidaily.com/effortless-strategies-for-understanding-acsm-texts-with-kobo-ereader-technology/"><u>Effortless Strategies for Understanding ACSM Texts with Kobo eReader Technology</u></a></li>
<li><a href="https://tech-hub.techidaily.com/enhance-calibre-appearance-step-by-step-tutorial-for-modifying-icon-schemes-in-the-main-interface/"><u>Enhance Calibre Appearance: Step-by-Step Tutorial for Modifying Icon Schemes in the Main Interface</u></a></li>
<li><a href="https://tech-hub.techidaily.com/enhancing-vocabulary-on-your-kindle-tutorial-for-addingchanging-dictionaries/"><u>Enhancing Vocabulary on Your Kindle: Tutorial for Adding/Changing Dictionaries</u></a></li>
<li><a href="https://tech-hub.techidaily.com/enhancing-your-affiliate-program-with-constructive-partner-evaluations/"><u>Enhancing Your Affiliate Program with Constructive Partner Evaluations</u></a></li>
<li><a href="https://some-techniques.techidaily.com/examining-storage-space-for-bulk-movie-files-64128gb-for-2024/"><u>Examining Storage Space for Bulk Movie Files, 64/128Gb for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/explore-convenient-and-enjoyable-reading-with-top-ranking-kobo-devices/"><u>Explore Convenient and Enjoyable Reading with Top-Ranking Kobo Devices</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-your-hands-on-no-cost-asrock-ab350-pro4-drivers-for-windows-systems/"><u>Get Your Hands on No-Cost ASRock AB350 Pro4 Drivers for Windows Systems!</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-determine-your-windows-11-powershell-version-quickly-and-accurately/"><u>How to Determine Your Windows 11 PowerShell Version Quickly & Accurately</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-to-optimize-content-a-comprehensive-guide-to-effective-activation-strategies/"><u>How to Optimize Content: A Comprehensive Guide to Effective Activation Strategies</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-to-video-tutorial-transforming-ebooks-from-adobe-digital-editions-into-pdf-format/"><u>How-To Video Tutorial: Transforming eBooks From Adobe Digital Editions Into PDF Format</u></a></li>
<li><a href="https://tech-hub.techidaily.com/immediate-guide-how-to-remove-nooks-digital-rights-management-drm-securely/"><u>Immediate Guide: How to Remove Nook's Digital Rights Management (DRM) Securely</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Best Anti Tracker Software For OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-itel-a05s-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Itel A05s Is Unlocked</u></a></li>
<li><a href="https://tech-hub.techidaily.com/insights-on-the-most-frequently-asked-questions-user-inquiries-explained/"><u>Insights on the Most Frequently Asked Questions: User Inquiries Explained</u></a></li>
<li><a href="https://tech-hub.techidaily.com/integrating-dropbox-into-your-kindle-fire-experience-essential-steps-and-tips/"><u>Integrating Dropbox Into Your Kindle Fire Experience: Essential Steps and Tips</u></a></li>
<li><a href="https://tech-hub.techidaily.com/master-book-compatibility-use-kobo-converter-for-seamless-ebook-conversion-to-pdf-kindle-format-and-epub/"><u>Master Book Compatibility - Use Kobo Converter for Seamless Ebook Conversion to PDF, Kindle Format and EPUB!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-the-art-of-pdf-reading-a-comprehensive-guide-for-your-amazon-kindle/"><u>Mastering the Art of PDF Reading: A Comprehensive Guide for Your Amazon Kindle</u></a></li>
<li><a href="https://tech-hub.techidaily.com/maximizing-e-reader-performance-effective-strategies-for-preserving-kindle-battery/"><u>Maximizing E-Reader Performance: Effective Strategies for Preserving Kindle Battery</u></a></li>
<li><a href="https://tech-hub.techidaily.com/overcoming-book-conversion-challenges-success-strategies/"><u>Overcoming Book Conversion Challenges: Success Strategies</u></a></li>
<li><a href="https://tech-hub.techidaily.com/potential-problems-with-extended-names-in-file-management-systems/"><u>Potential Problems with Extended Names in File Management Systems</u></a></li>
<li><a href="https://tech-hub.techidaily.com/procedures-faciles-le-moyen-de-lire-vos-livres-kindle-numeriques-directement-sur-un-ipad/"><u>Procédures Faciles : Le Moyen De Lire Vos Livres Kindle Numériques Directement Sur Un iPad</u></a></li>
<li><a href="https://tech-hub.techidaily.com/schnellere-konvertierung-von-audible-aax-zu-mp3-erfahre-die-60x-geschwindigkeitssteigerung/"><u>Schnellere Konvertierung Von Audible-AAX Zu MP3: Erfahre Die 60X Geschwindigkeitssteigerung</u></a></li>
<li><a href="https://tech-hub.techidaily.com/seamless-ebook-enjoyment-shifting-your-reading-experience-from-barnes-and-nobles-nook-to-amazons-kindle-devices/"><u>Seamless Ebook Enjoyment: Shifting Your Reading Experience From Barnes & Noble's Nook to Amazon's Kindle Devices</u></a></li>
<li><a href="https://tech-hub.techidaily.com/seamless-integration-steps-how-to-easily-implement-new-software-features/"><u>Seamless Integration Steps: How to Easily Implement New Software Features</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-realme-narzo-60-pro-5g-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Realme Narzo 60 Pro 5G Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
</ul></div>
