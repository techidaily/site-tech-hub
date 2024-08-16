---
title: "GPT-4: Open to All; Yet, Premium Users Reap 6 Exclusive Advantages"
date: 2024-08-15T21:27:54.767Z
updated: 2024-08-16T21:27:54.767Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: "This Article Describes GPT-4: Open to All; Yet, Premium Users Reap 6 Exclusive Advantages"
excerpt: "This Article Describes GPT-4: Open to All; Yet, Premium Users Reap 6 Exclusive Advantages"
thumbnail: https://thmb.techidaily.com/7c14c2521c5a7d6f2586dc7cce48c3b4142cae653643556f77f854f0ef38defc.jpg
---

## Transform Personal Datasets Into an Intelligent, Customized ChatBot – Learn How

 Providing GPT technology in a powerful and easy-to-use chatbot, ChatGPT has become the world's most popular AI tool. Many people use ChatGPT to provide engaging conversations, answer queries, offer creative suggestions, and aid in coding and writing. However, ChatGPT is limited as you cannot store your data for long-term personal use, and its September 2021 knowledge data cutoff point.

 As a workaround, we can use OpenAI's API and LangChain to provide ChatGPT with custom data and updated info past 2021 to create a custom ChatGPT instance.

## Why Provide ChatGPT with Custom Data?

 Feeding ChatGPT with custom data and providing updated information beyond its knowledge cutoff date provides several benefits over just using ChatGPT as usual. Here are a few of them:

* **Personalized Interactions:** By providing ChatGPT with custom data, users can create a more customized experience. The model can be trained on specific datasets relevant to individual users or organizations, resulting in responses tailored to their unique needs and preferences.
* **Domain-Specific Expertise:** Custom data integration allows ChatGPT to specialize in particular domains or industries. It can be trained on industry-specific knowledge, terminology, and trends, enabling more accurate and insightful responses within those specific areas.
* **Current and Accurate Information:** Access to updated information ensures that ChatGPT stays current with the latest developments and knowledge. It can provide accurate responses based on recent events, news, or research, making it a more reliable source of information.

 Now that you understand the importance of providing custom data to ChatGPT, here's a step-by-step on how to do so on your local computer.

## Step 1: Install and Download Software and Pre-Made Script

 Please note the following instructions are for a Windows 10 or Windows 11 machine.

 To provide custom data to ChatGPT, you'll need to install and download the latest Python3, Git, Microsoft C++, and the ChatGPT-retrieval script from GitHub. If you already have some of the software installed on your PC, make sure they are updated with the latest version to avoid any hiccups during the process.

Start by installing:

* **Download:** [Python3](https://www.python.org/downloads/) (Free)
* **Download:** [Git](https://git-scm.com/downloads) (Free)
* **Download:** [Microsoft Visual Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/) (Free)

### Python3 and Microsoft C++ Installation Notes

 When installing Python3, make sure that you tick the**Add python.exe to PATH** option before clicking**Install Now** . This is important as it allows you to access Python in any directory on your computer.

![Adding Python to PATH](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/1-download-python.jpg)

 When Installing Microsoft C++, you'll want to install**Microsoft Visual Studio Build Tools** first. Once installed, you can tick the**Desktop development with C++** option and click**Install** with all the optional tools automatically ticked on the right sidebar.

![Installing Microsoft C++ through Build Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-install-c.jpg)

 Now that you have installed the latest versions of Python3, Git, and Microsoft C++, you can download the Python script to easily query custom local data.

**Download:** [ChatGPT-retrieval script](https://github.com/techleadhd/chatgpt-retrieval) (Free)

 To download the script, click on**Code,** then select**Download ZIP** . This should download the Python script into your default or selected directory.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
![Downloading Python script on GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-download-script.jpg)

Once downloaded, we can now set up a local environment.

## Step 2: Set Up the Local Environment

 To set up the environment, you'll need to open a terminal in the chatgpt-retrieval-main folder you downloaded. To do that, open**chatgpt-retrieval-main** folder, right-click, and select**Open in Terminal** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
![Opening terminal on directory folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-open-terminal.jpg)

Once the terminal is open, copy and paste this command:

pip install langchain openai chromadb tiktoken unstructured

 This command uses Python's package manager to[create and manage the Python virtual environment](https://www.makeuseof.com/create-manage-python-virtual-environments/) needed.

 After creating the virtual environment, we need to supply an OpenAI API key to access their services. We'll first need to generate an API key from the[OpenAI API keys site](https://platform.openai.com/account/api-keys) by clicking on**Create new secret key** , adding a name for the key, then hitting the**Create secret key button** .

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
![Creating secret API key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/generate-api-key.jpg)

 You will be provided with a string of characters. This is your OpenAI API key. Copy it by clicking on the copy icon on the side of the API key. Keep note that this API key should be kept secret. Do not share it with others unless you really intend for them to use it with you.

 Once copied, return to the chatgpt-retrieval-main folder and open constants with**Notepad** . Now replace the placeholder with your API key. Remember to save the file!

![Adding API key as environment variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-api-key.jpg)

 Now that you have successfully set up your virtual environment and added your OpenAI API key as an environment variable. You can now provide your custom data to ChatGPT.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
## Step 3: Adding Custom Data

 To add custom data, place all your custom text data in the**data** folder within chatgpt-retrieval-main. The format of the text data may be in the form of a PDF, TXT, or DOC.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
![Adding custom data for ChatGPT](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-data.jpg)

 As you can see from the screenshot above, I've added a text file containing a made-up personal schedule, an article I wrote on[AMD's Instinct Accelerators](https://www.makeuseof.com/what-are-amd-instinct-ai-accelerators/) , and a PDF document.

## Step 4: Querying ChatGPT Through Terminal

 The Python script allows us to query data from the custom data we've added to the data folder and the internet. In other words, you will have access to the usual ChatGPT backend and all the data stored locally in the data folder.

 To use the script, run the python[chatgpt.py](http://chatgpt.py) script and then add your question or query as the argument.

python [chatgpt.py](http://chatgpt.py) "YOUR QUESTION"

Make sure to put your questions in quotation marks.

 To test if we have successfully fed ChatGPT our data, I'll ask a personal question regarding the**Personal Sched.txt** file.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Testing ChatGPT with custom data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/visit.jpg)

 It worked! This means ChatGPT was able to read the Personal Sched.txt provided earlier. Now let's see if we have successfully fed ChatGPT with information it does not know due to its knowledge cutoff date.

![Asking custom ChatGPT about topic outside knowledge cut off data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/m250x.jpg)

 As you can see, it correctly described the AMD Instinct MI250x, which was released after ChatGPT -3's knowledge cutoff date.

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Limitations of Custom ChatGPT

 Although feeding GPT-3.5 with custom data opens more ways to apply and use the LLM, there are a few drawbacks and limitations.

 Firstly, you need to provide all the data yourself. You can still access all the knowledge of GPT-3.5 until its knowledge cutoff date; however, you must provide all the extra data. This means if you want your local model to be knowledgeable of a certain subject on the internet that GPT-3.5 don't already know, you'll have to go to the internet and scrape the data yourself and save it as a text on the data folder of chatgpt-retrieval-main.

 Another issue is that querying ChatGPT like this takes more time to load when compared to asking ChatGPT directly.

 Lastly, the only model currently available is GPT-3.5 Turbo. So even if you have access to GPT-4, you won't be able to use it to power your custom ChatGPT instance.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
## Custom ChatGPT Is Awesome But Limited

 Providing custom data to ChatGPT is a powerful way to get more out of the model. Through this method, you can feed the model with any text data you want and prompt it just like regular ChatGPT, albeit with some limitations. However, this will change in the future as it becomes easier to integrate our data with the LLM, along with access to the latest GPT-4 model.


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
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-top-30-beginner-pro-facebook-strategies-for-boosting-sales/"><u>[New] In 2024, Top 30 Beginner-Pro Facebook Strategies for Boosting Sales</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-key-components-in-upgrading-from-standard-to-4k-lenses/"><u>[New] Key Components in Upgrading From Standard to 4K Lenses</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-snapshot-styles-a-guide-to-using-old-school-vhs-in-modern-editing/"><u>[New] Snapshot Styles  A Guide to Using Old-School VHS in Modern Editing</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-the-complete-guide-to-selecting-and-raising-valheim-crops-for-2024/"><u>[New] The Complete Guide to Selecting & Raising Valheim Crops for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-top-tier-funny-editing-tool/"><u>[New] Top-Tier Funny Editing Tool</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-breaking-down-whatsapps-voice-call-features/"><u>[Updated] In 2024, Breaking Down WhatsApp's Voice Call Features</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-facebook-in-flashes-sharing-briefly/"><u>[Updated] In 2024, Facebook in Flashes  Sharing Briefly</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-exploring-the-genesis-and-evolution-of-windows-movie-maker/"><u>2024 Approved  Exploring the Genesis and Evolution of Windows Movie Maker</u></a></li>
<li><a href="https://tech-hub.techidaily.com/a-beginners-guide-to-adding-and-working-with-chatgpt-addons/"><u>A Beginner's Guide to Adding and Working with ChatGPT Addons</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-zte-axon-40-lite-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your ZTE Axon 40 Lite</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ai-evolution-differentiating-between-gpt-4-gpt-4-turbo-and-gpt-e-models/"><u>AI Evolution: Differentiating Between GPT-4, GPT-4 Turbo & GPT-E Models</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ai-or-astrology-can-chatgpt-deliver-better-prophecies-than-your-favorite-zodiac-columnist/"><u>AI or Astrology? Can ChatGPT Deliver Better Prophecies than Your Favorite Zodiac Columnist?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ai-showdown-on-skype-delving-into-8-major-varianebetween-snapchat-my-ai-and-microsofts-bing-chat/"><u>AI Showdown on Skype: Delving Into 8 Major Varianebetween Snapchat My AI and Microsoft's Bing Chat</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ai-powered-search-engines-and-their-potential-to-transform-online-visibility/"><u>AI-Powered Search Engines and Their Potential to Transform Online Visibility</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ais-secret-weapon-unveiling-the-strategy-behind-transfer-learning/"><u>AI's Secret Weapon: Unveiling the Strategy Behind Transfer Learning</u></a></li>
<li><a href="https://tech-hub.techidaily.com/are-advancements-in-generative-ai-leading-us-towards-an-era-of-digital-deception/"><u>Are Advancements in Generative AI Leading Us Towards an Era of Digital Deception?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/battle-of-the-brains-spotlighting-8-distinctive-features-between-snapchat-my-ai-and-bing-chat-on-skype/"><u>Battle of the Brains: Spotlighting 8 Distinctive Features Between Snapchat My AI and Bing Chat on Skype</u></a></li>
<li><a href="https://tech-hub.techidaily.com/behind-the-closure-of-new-chatgpt-sign-ups-reasons-and-predicted-openings/"><u>Behind the Closure of New ChatGPT Sign-Ups – Reasons & Predicted Openings</u></a></li>
<li><a href="https://tech-hub.techidaily.com/best-ai-sidekicks-for-everyday-life-is-it-claude-or-chatgpt/"><u>Best AI Sidekicks for Everyday Life – Is It Claude or ChatGPT?</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/-the-ice-how-to-make-a-hit-youtube-reaction-in-just-15-minutes-or-less/"><u>Break the Ice - How to Make a Hit YouTube Reaction in Just 15 Minutes or Less</u></a></li>
<li><a href="https://tech-hub.techidaily.com/building-connections-through-ai-how-chatgpt-can-help-fight-feelings-of-isolation/"><u>Building Connections Through AI: How ChatGPT Can Help Fight Feelings of Isolation</u></a></li>
<li><a href="https://tech-hub.techidaily.com/can-i-depend-on-chatgpt-for-credible-health-answers/"><u>Can I Depend on ChatGPT for Credible Health Answers?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/can-we-fully-reliance-on-zerogpt-doubts-remain/"><u>Can We Fully Reliance On ZeroGPT? Doubts Remain</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-and-the-unanswerable-7-examples-that-push-its-limits/"><u>ChatGPT and the Unanswerable: 7 Examples That Push Its Limits</u></a></li>
<li><a href="https://tech-hub.techidaily.com/confidential-chats-meet-ai-innovation-try-your-hand-at-duckduckgo-and-more/"><u>Confidential Chats Meet AI Innovation: Try Your Hand at DuckDuckGo and More</u></a></li>
<li><a href="https://tech-hub.techidaily.com/copilot-vs-copilot-pro-showdown-features-benefits-and-when-to-consider-an-upgrade/"><u>Copilot Vs. Copilot Pro Showdown: Features, Benefits, and When to Consider an Upgrade</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/delete-gmail-account-withwithout-password-on-realme-gt-5-pro-by-drfone-android/"><u>Delete Gmail Account With/Without Password On Realme GT 5 Pro</u></a></li>
<li><a href="https://tech-hub.techidaily.com/diving-into-claude-the-next-generation-ai-whats-possible/"><u>Diving Into Claude The Next Generation AI - What's Possible?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/enhancing-ai-with-efficient-vector-database-architecture/"><u>Enhancing AI with Efficient Vector Database Architecture</u></a></li>
<li><a href="https://tech-hub.techidaily.com/guide-easy-steps-to-register-and-use-chatgpt-add-ons/"><u>Guide: Easy Steps to Register and Use ChatGPT Add-Ons</u></a></li>
<li><a href="https://tech-hub.techidaily.com/hidden-capability-interact-with-ai-chatgpt/"><u>Hidden Capability: Interact with AI ChatGPT</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/hit-the-floor-with-optimal-posting-hours/"><u>Hit the Floor with Optimal Posting Hours</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-might-digital-intelligence-secure-safety-in-remote-wilderness-settings/"><u>How Might Digital Intelligence Secure Safety In Remote Wilderness Settings?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-vivo-y78-5g-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>How to Cast Vivo Y78 5G to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-polaroid-cubeplus-action-camera-review/"><u>In 2024, Polaroid Cube+ Action Camera Review</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-revolutionize-slack-discussions-with-10-free-recorders/"><u>In 2024, Revolutionize Slack Discussions with 10 Free Recorders</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-is-ipogo-not-working-on-tecno-spark-go-2023-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Tecno Spark Go (2023)? Fixed | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/innovative-npc-designs-in-dandd-via-chatgpt-and-dall-e-integration/"><u>Innovative NPC Designs in D&D via ChatGPT and DALL-E Integration</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-it-worth-it-to-upgrade-from-copilot-to-copilot-pro-a-comprehensive-breakdown/"><u>Is It Worth It to Upgrade From Copilot to Copilot Pro? A Comprehensive Breakdown</u></a></li>
<li><a href="https://driver-install.techidaily.com/new-graphic-driver-release-hp-and-windows-11/"><u>New Graphic Driver Release: HP & Windows 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1721977911872-revolutionize-your-ai-dialogues-powered-by-google-chrome/"><u>Revolutionize Your AI Dialogues, Powered by Google Chrome</u></a></li>
<li><a href="https://tech-hub.techidaily.com/what-is-gpt4all-and-how-does-it-work/"><u>What Is GPT4All and How Does It Work?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/whisperings-from-beyond-cyberspace-unraveling-who-youre-really-engaging-with-in-the-age-of-digital-phantoms/"><u>Whisperings From Beyond Cyberspace: Unraveling Who You're Really Engaging With in the Age of Digital Phantoms</u></a></li>
<li><a href="https://tech-hub.techidaily.com/why-cant-we-break-free-analyzing-the-seven-pillars-keeping-chatgpt-jailbreaks-at-bay/"><u>Why Can't We Break Free? Analyzing the Seven Pillars Keeping ChatGPT Jailbreaks at Bay</u></a></li>
</ul></div>
