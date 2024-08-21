---
title: How to Delete Your ChatGPT Account
date: 2024-08-20T11:00:24.128Z
updated: 2024-08-21T11:00:24.128Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes How to Delete Your ChatGPT Account
excerpt: This Article Describes How to Delete Your ChatGPT Account
thumbnail: https://thmb.techidaily.com/fa206782af9b714e31a62f7ae5d0a20ed9b7932652ed0826ec0104cd05df9774.jpg
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
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
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
4. A terminal will open and start the setup. Early on, the setup will pause and ask you what GPU you are using. Select the appropriate type of GPU installed on your computer and hit enter. For those without a dedicated graphics card, select**None (I want to run models in CPU mode)** . Keep in mind that running on CPU mode is much slower when compared to running the model with a dedicated GPU.  
![Selecting GPU hardware installed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/5-select-gpu-settings.jpg)
5. Once the setup is complete, you can now launch Text-Generation-WebUI locally. You can do so by opening your preferred web browser and entering the provided IP address on the URL.  
![How to launch-Text-Generation-WebUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/6-launch-text-generation-webui.jpg)
6. The WebUI is now ready for use.  
![Text-Generation-WebUI ](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/7-text-generation-webui-view.jpg)

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
 However, the program is only a model loader. Let's download Llama 2 for the model loader to launch.

## Step 3: Download the Llama 2 Model

 There are quite a few things to consider when deciding which iteration of Llama 2 you need. These include parameters, quantization, hardware optimization, size, and usage. All of this information will be found denoted in the model's name.

* **Parameters:** The number of parameters used to train the model. Bigger parameters make more capable models but at the cost of performance.
* **Usage:** Can either be standard or chat. A chat model is optimized to be used as a chatbot like ChatGPT, while the standard is the default model.
* **Hardware Optimization:** Refers to what hardware best runs the model. GPTQ means the model is optimized to run on a dedicated GPU, while GGML is optimized to run on a CPU.
* **Quantization:** Denotes the precision of weights and activations in a model. For inferencing, a precision of q4 is optimal.
* **Size:** Refers to the size of the specific model.

 Note that some models may be arranged differently and may not even have the same types of information displayed. However, this type of naming convention is fairly common in the[HuggingFace](https://www.makeuseof.com/what-is-hugging-face-and-what-is-it-used-for/) Model library, so it's still worth understanding.

![HuggingFace model naming convention](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/huggingface-model-naming-convention-1.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
 In this example, the model can be identified as a medium-sized Llama 2 model trained on 13 billion parameters optimized for chat inferencing using a dedicated CPU.

 For those running on a dedicated GPU, choose a**GPTQ** model, while for those using a CPU, choose**GGML** . If you want to chat with the model like you would with ChatGPT, choose**chat** , but if you want to experiment with the model with its full capabilities, use the**standard** model. As for parameters, know that using bigger models will provide better results at the expense of performance. I would personally recommend you start with a 7B model. As for quantization, use q4, as it's only for inferencing.

**Download:** [GGML](https://huggingface.co/localmodels/Llama-2-7B-ggml/tree/main) (Free)

**Download:** [GPTQ](https://huggingface.co/localmodels/Llama-2-7B-Chat-GPTQ/tree/main) (Free)

 Now that you know what iteration of Llama 2 you need, go ahead and download the model you want.

 In my case, since I'm running this on an ultrabook, I'll be using a GGML model fine-tuned for chat,**llama-2-7b-chat-ggmlv3.q4\_K\_S.bin.**

![Downloading Llama 2 model of your preference](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/8-download-llama-2-model.jpg)

 After the download is finished, place the model in**text-generation-webui-main** \>**models** .

![Placing Llama 2 model to model folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/9-place-model-to-model-folder.jpg)

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now that you have your model downloaded and placed in the model folder, it's time to configure the model loader.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
## Step 4: Configure Text-Generation-WebUI

Now, let's begin the configuration phase.

1. Once again, open Text-Generation-WebUI by running the**start\_(your OS)** file (see the previous steps above).
2. On the tabs located above the GUI, click**Model.** Click the refresh button at the model dropdown menu and select your model.
3. Now click on the dropdown menu of the**Model loader** and select**AutoGPTQ** for those using a GTPQ model and**ctransformers** for those using a GGML model. Finally, click on**Load** to load your model.  
![Setting model loader](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/10-select-model-loader.jpg)
4. To use the model, open the Chat tab and start testing the model.  
![Testing Llama 2 locally](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/12-testing-llama-2-locally.jpg)

 Congratulations, you've successfully loaded Llama2 on your local computer!

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://screen-mirroring-recording.techidaily.com/1716069669499-new-in-2024-using-inbuilt-recorders-for-screen-capture-on-huaweis-mate-and-p-series-devices/"><u>[New] In 2024, Using Inbuilt Recorders for Screen Capture on Huawei's Mate and P Series Devices.</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-instagram-sounds-ownership-policy/"><u>[New] Instagram Sounds Ownership Policy</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-top-picks-for-remote-work-best-secure-video-services/"><u>[New] Top Picks for Remote Work  Best Secure Video Services</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-building-brand-identity-with-instagram-video-content/"><u>[Updated] 2024 Approved  Building Brand Identity with Instagram Video Content</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-maximizing-engagement-in-post-facebook-algorithm-world/"><u>[Updated] 2024 Approved  Maximizing Engagement in Post-Facebook Algorithm World</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-from-blank-page-to-airwaves-writing-engaging-podcast-episodes/"><u>[Updated] From Blank Page to Airwaves  Writing Engaging Podcast Episodes</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-harvesting-high-returns-ginger-valley-farming-tips/"><u>[Updated] In 2024, Harvesting High Returns  Ginger Valley Farming Tips</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-samsung-galaxy-s21-fe-5g-2023-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Samsung Galaxy S21 FE 5G (2023)</u></a></li>
<li><a href="https://tech-hub.techidaily.com/behind-the-scenes-of-truthgpt-uncover-police-crackdown-on-mullvad-vpn-ultimate-free-pc-game-picks-and-comprehensive-guide-to-mechanical-keyboards/"><u>Behind the Scenes of TruthGPT: Uncover Police Crackdown on Mullvad VPN; Ultimate Free PC Game Picks & Comprehensive Guide to Mechanical Keyboards</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-undelete-lost-call-logs-from-y78-5g-by-fonelab-android-recover-call-logs/"><u>Best Android Data Recovery - undelete lost call logs from Y78 5G</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-honor-x9b-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Honor X9b Hard Reset | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/best-performance-showdown-evaluating-results-from-three-chatbots-on-the-same-challenge/"><u>Best Performance Showdown: Evaluating Results From Three Chatbots on the Same Challenge</u></a></li>
<li><a href="https://vp-tips.techidaily.com/boost-your-tunes-quickly-top-phone-app-selection-for-2024/"><u>Boost Your Tunes Quickly  Top Phone App Selection for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/bridging-knowledge-gaps-what-sets-apart-natural-language-processing-from-machine-learning/"><u>Bridging Knowledge Gaps: What Sets Apart Natural Language Processing From Machine Learning?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/can-i-rely-on-ai-technology-like-chatgpt-to-enhance-my-proofreading-skills/"><u>Can I Rely On AI Technology, Like ChatGPT, To Enhance My Proofreading Skills?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/challenges-in-ai-the-8-core-issues-with-chatgpt/"><u>Challenges in AI: The 8 Core Issues with ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/decision-time-freelancers-guide-to-chatbot-selectionbing-vs-chatgpt/"><u>Decision Time! Freelancer's Guide to ChatBot Selection—Bing Vs. ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discover-the-power-of-gpt-automation-with-these-8-essential-tips/"><u>Discover the Power of GPT Automation with These 8 Essential Tips</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/easily-connect-to-the-cloud-and-post-from-your-camera-roll/"><u>Easily Connect to the Cloud and Post From Your Camera Roll</u></a></li>
<li><a href="https://tech-hub.techidaily.com/elevate-your-enterprise-an-experts-list-of-8-ways-to-employ-chatgpt/"><u>Elevate Your Enterprise: An Expert's List of 8 Ways to Employ ChatGPT</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/expert-advice-how-to-securely-get-and-update-lenovo-thinkpad-drivers/"><u>Expert Advice: How to Securely Get & Update Lenovo ThinkPad Drivers</u></a></li>
<li><a href="https://tech-hub.techidaily.com/factors-shaping-the-careers-of-future-prompt-designers/"><u>Factors Shaping the Careers of Future Prompt Designers</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-quiet-foes-in-hearthstone-restoring-audio-for-ultimate-gaming-experience/"><u>Fixing Quiet Foes in Hearthstone - Restoring Audio for Ultimate Gaming Experience!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/generative-ais-evolving-threat-spectrum/"><u>Generative AI's Evolving Threat Spectrum</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-tecno-spark-20withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Tecno Spark 20with/without a PC</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-xiaomi-redmi-12-5g-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Xiaomi Redmi 12 5G To Phone | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-peak-performance-sd-card-for-sony-a7s-series/"><u>In 2024, Peak Performance SD Card for Sony A7S Series</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-the-cash-flow-of-creative-content-youtubers-earnings-per-sponsored-video/"><u>In 2024, The Cash Flow of Creative Content  Youtuber's Earnings per Sponsored Video?</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-the-functionality-of-instagram-story-features/"><u>In 2024, The Functionality of Instagram Story Features</u></a></li>
<li><a href="https://tech-hub.techidaily.com/innovative-intervention-can-ai-transform-therapy/"><u>Innovative Intervention: Can AI Transform Therapy?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-ai-the-new-stand-up-artist-discovering-chatgpts-humorous-side/"><u>Is AI the New Stand-Up Artist? Discovering ChatGPT's Humorous Side</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-chatgpt-a-trustworthy-source-for-medical-insights/"><u>Is ChatGPT a Trustworthy Source for Medical Insights?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/leveraging-chatgpt-technology-for-easy-web-app-development/"><u>Leveraging ChatGPT Technology for Easy Web App Development</u></a></li>
<li><a href="https://howto.techidaily.com/oppo-a78-screen-unresponsive-heres-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Oppo A78 Screen Unresponsive? Heres How to Fix It | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/risk-and-revelation-10-roguelike-game-selection/"><u>Risk and Revelation  #10 Roguelike Game Selection</u></a></li>
<li><a href="https://tech-hub.techidaily.com/stay-alert-against-false-ai-apps-uncovering-the-dangers-of-these-9-misleading-chatgpt-viruses-capable-of-data-breach/"><u>Stay Alert Against False AI Apps: Uncovering the Dangers of These 9 Misleading ChatGPT Viruses Capable of Data Breach</u></a></li>
<li><a href="https://tech-hub.techidaily.com/streamline-your-ai-interactions-tools-for-sharing-chatgpt-dialogues-online/"><u>Streamline Your AI Interactions: Tools for Sharing ChatGPT Dialogues Online</u></a></li>
<li><a href="https://tech-hub.techidaily.com/tech-tales-of-triumph-repairing-your-pc-with-chatai/"><u>Tech Tales of Triumph - Repairing Your PC with ChatAI</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-role-of-chatgpt-in-cultivating-greater-emotional-awareness-and-understanding/"><u>The Role of ChatGPT in Cultivating Greater Emotional Awareness and Understanding</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-the-potential-of-googles-gemini-ai-in-light-of-chatgpt/"><u>Unveiling the Potential of Google's Gemini AI in Light of ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-the-secrets-of-bert-the-next-evolution-beyond-gpt-for-text-comprehension/"><u>Unveiling the Secrets of BERT: The Next Evolution Beyond GPT for Text Comprehension</u></a></li>
<li><a href="https://tech-hub.techidaily.com/which-is-superior-notion-ai-versus-chatgpt-in-the-arena-of-generative-ai-tools/"><u>Which Is Superior? Notion AI Versus ChatGPT in the Arena of Generative AI Tools</u></a></li>
<li><a href="https://tech-hub.techidaily.com/who-holds-the-reins-of-power-in-artificeal-intelligence-regulation/"><u>Who Holds the Reins of Power in Artificeal Intelligence Regulation?</u></a></li>
</ul></div>
