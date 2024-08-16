---
title: Train ChatGPT for Personalized Content Creation Like Yourselves
date: 2024-08-15T21:34:14.152Z
updated: 2024-08-16T21:34:14.152Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Train ChatGPT for Personalized Content Creation Like Yourselves
excerpt: This Article Describes Train ChatGPT for Personalized Content Creation Like Yourselves
thumbnail: https://thmb.techidaily.com/6669b51a644a6e6a471c5e95129c578aa098ea11ffbe838822c268118ff95e70.jpg
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

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Downloading Python script on GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-download-script.jpg)

Once downloaded, we can now set up a local environment.

## Step 2: Set Up the Local Environment

 To set up the environment, you'll need to open a terminal in the chatgpt-retrieval-main folder you downloaded. To do that, open**chatgpt-retrieval-main** folder, right-click, and select**Open in Terminal** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
![Opening terminal on directory folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-open-terminal.jpg)

Once the terminal is open, copy and paste this command:

pip install langchain openai chromadb tiktoken unstructured

 This command uses Python's package manager to[create and manage the Python virtual environment](https://www.makeuseof.com/create-manage-python-virtual-environments/) needed.

 After creating the virtual environment, we need to supply an OpenAI API key to access their services. We'll first need to generate an API key from the[OpenAI API keys site](https://platform.openai.com/account/api-keys) by clicking on**Create new secret key** , adding a name for the key, then hitting the**Create secret key button** .

![Creating secret API key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/generate-api-key.jpg)

 You will be provided with a string of characters. This is your OpenAI API key. Copy it by clicking on the copy icon on the side of the API key. Keep note that this API key should be kept secret. Do not share it with others unless you really intend for them to use it with you.

 Once copied, return to the chatgpt-retrieval-main folder and open constants with**Notepad** . Now replace the placeholder with your API key. Remember to save the file!

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![Adding API key as environment variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-api-key.jpg)

 Now that you have successfully set up your virtual environment and added your OpenAI API key as an environment variable. You can now provide your custom data to ChatGPT.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
## Step 3: Adding Custom Data

 To add custom data, place all your custom text data in the**data** folder within chatgpt-retrieval-main. The format of the text data may be in the form of a PDF, TXT, or DOC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
![Adding custom data for ChatGPT](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-data.jpg)

 As you can see from the screenshot above, I've added a text file containing a made-up personal schedule, an article I wrote on[AMD's Instinct Accelerators](https://www.makeuseof.com/what-are-amd-instinct-ai-accelerators/) , and a PDF document.

## Step 4: Querying ChatGPT Through Terminal

 The Python script allows us to query data from the custom data we've added to the data folder and the internet. In other words, you will have access to the usual ChatGPT backend and all the data stored locally in the data folder.

 To use the script, run the python[chatgpt.py](http://chatgpt.py) script and then add your question or query as the argument.

python [chatgpt.py](http://chatgpt.py) "YOUR QUESTION"

Make sure to put your questions in quotation marks.

 To test if we have successfully fed ChatGPT our data, I'll ask a personal question regarding the**Personal Sched.txt** file.

![Testing ChatGPT with custom data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/visit.jpg)

 It worked! This means ChatGPT was able to read the Personal Sched.txt provided earlier. Now let's see if we have successfully fed ChatGPT with information it does not know due to its knowledge cutoff date.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Asking custom ChatGPT about topic outside knowledge cut off data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/m250x.jpg)

 As you can see, it correctly described the AMD Instinct MI250x, which was released after ChatGPT -3's knowledge cutoff date.

## Limitations of Custom ChatGPT

 Although feeding GPT-3.5 with custom data opens more ways to apply and use the LLM, there are a few drawbacks and limitations.

 Firstly, you need to provide all the data yourself. You can still access all the knowledge of GPT-3.5 until its knowledge cutoff date; however, you must provide all the extra data. This means if you want your local model to be knowledgeable of a certain subject on the internet that GPT-3.5 don't already know, you'll have to go to the internet and scrape the data yourself and save it as a text on the data folder of chatgpt-retrieval-main.

 Another issue is that querying ChatGPT like this takes more time to load when compared to asking ChatGPT directly.

 Lastly, the only model currently available is GPT-3.5 Turbo. So even if you have access to GPT-4, you won't be able to use it to power your custom ChatGPT instance.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
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
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-unlock-the-full-potential-of-snapkit-in-business-ads/"><u>[New] In 2024, Unlock the Full Potential of SnapKit in Business Ads</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-selective-screen-time-topping-youtube-movies/"><u>[New] Selective Screen Time  Topping YouTube Movies</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-deciphering-the-function-of-the-blue-icon-in-messenger-for-2024/"><u>[Updated] Deciphering the Function of the Blue Icon in Messenger for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-reviving-obs-sound-capture-steps/"><u>[Updated] In 2024, Reviving OBS Sound Capture Steps</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-noshadowedit-advanced-background-shadow-elimination/"><u>2024 Approved  NoShadowEdit  Advanced Background Shadow Elimination</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-step-into-new-dimensions-with-jaunt-vr-review/"><u>2024 Approved  Step Into New Dimensions with Jaunt VR Review</u></a></li>
<li><a href="https://some-techniques.techidaily.com/for-novices-a-primer-on-av1-technology-for-2024/"><u>For Novices  A Primer on AV1 Technology for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-15-to-other-iphone-12-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 15 to other iPhone 12 devices? | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ready-for-a-challenge-dive-into-chatgpts-selection-of-the-6-greatest-games/"><u>Ready for a Challenge? Dive Into ChatGPT’s Selection of the 6 Greatest Games</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-files-back-from-infinix-gt-10-pro-by-fonelab-android-recover-data/"><u>Simple ways to get lost files back from Infinix GT 10 Pro</u></a></li>
<li><a href="https://tech-hub.techidaily.com/simplify-problem-solving-in-mathematics-using-our-selection-of-the-top-7-ai-systems/"><u>Simplify Problem-Solving in Mathematics Using Our Selection of the Top 7 AI Systems</u></a></li>
<li><a href="https://fix-guide.techidaily.com/spotify-keeps-crashing-a-complete-list-of-fixes-you-can-use-on-vivo-y28-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Spotify Keeps Crashing A Complete List of Fixes You Can Use on Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/steer-clear-from-the-hacked-google-bard-software-a-risky-malware-threat/"><u>Steer Clear From The Hacked 'Google Bard' Software - A Risky Malware Threat</u></a></li>
<li><a href="https://tech-hub.techidaily.com/step-into-a-world-of-anytime-anywhere-ai-support-mastering-chatgpt-through-universal-accessibility-with-chatgpt-everywhere/"><u>Step Into a World of Anytime, Anywhere AI Support - Mastering ChatGPT Through Universal Accessibility with ChatGPT Everywhere</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-resolving-shelldll-missing-files-issues-effectively/"><u>Step-by-Step Guide: Resolving Shell.DLL Missing Files Issues Effectively</u></a></li>
<li><a href="https://tech-hub.techidaily.com/talk-titans-duo-comparing-gpt-and-bings-virtual-voices/"><u>Talk Titans Duo: Comparing GPT & Bing's Virtual Voices</u></a></li>
<li><a href="https://tech-hub.techidaily.com/tapping-into-chatgpt-potential-with-its-api/"><u>Tapping Into ChatGPT Potential with Its API</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-evolution-of-college-assignments-in-the-age-of-artificial-intelligence-are-students-written-works-becoming-outdated/"><u>The Evolution of College Assignments in the Age of Artificial Intelligence: Are Students' Written Works Becoming Outdated?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-showdown-is-forefront-ai-a-superior-alternative-to-chatgpt/"><u>The Showdown: Is Forefront AI a Superior Alternative to ChatGPT?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-ultimate-guide-4-innovative-uses-of-chnagpt-for-mastering-your-time/"><u>The Ultimate Guide: 4 Innovative Uses of Chnagpt for Mastering Your Time</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-ultimate-way-to-reach-chatgpt-from-any-device-with-chatgpt-everywhere/"><u>The Ultimate Way to Reach ChatGPT From Any Device with ChatGPT Everywhere</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-ai-prompt-crafting-and-assessing-its-viability-as-a-long-term-profession/"><u>Understanding AI Prompt Crafting and Assessing Its Viability as a Long-Term Profession</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-popularity-in-the-era-of-digital-companions/"><u>Understanding Popularity in the Era of Digital Companions</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-the-professional-landscape-for-ai-interaction-experts/"><u>Understanding the Professional Landscape for AI Interaction Experts</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-ai-understanding-the-ultimate-compendium-of-29-crucial-terms-explained/"><u>Unlocking AI Understanding: The Ultimate Compendium of 29 Crucial Terms Explained</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-imagination-a-guide-to-using-chatgpt-and-dall-e-for-dungeons-and-dragons-characters/"><u>Unlocking Imagination: A Guide to Using ChatGPT and DALL-E for Dungeons & Dragons Characters</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-linguistic-mastery-the-power-of-chatgpt-plus-in-your-language-learning-journey/"><u>Unlocking Linguistic Mastery: The Power of ChatGPT Plus in Your Language Learning Journey</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-new-opportunities-how-businesses-benefit-from-the-latest-chatgpt-and-whisper-api-integrations/"><u>Unlocking New Opportunities: How Businesses Benefit From the Latest ChatGPT & Whisper API Integrations</u></a></li>
<li><a href="https://win-able.techidaily.com/unlocking-powerful-ammo-tactics-a-deep-dive-into-fps-changes-for-me-le-players/"><u>Unlocking Powerful Ammo Tactics: A Deep Dive Into FPS Changes for ME LE Players</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-the-future-the-anticipated-arrival-of-gpt-5-explained/"><u>Unveiling the Future: The Anticipated Arrival of GPT-5 Explained</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-the-latest-insights-into-apples-artificial-intelligence-announcements-at-wwdc-2024/"><u>Unveiling the Latest Insights Into Apple's Artificial Intelligence Announcements at WWDC 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-the-power-of-shapley-explanations-in-machine-learning-with-openais-shape/"><u>Unveiling the Power of Shapley Explanations in Machine Learning with OpenAI's ShapE</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-the-top-5-innovative-tools-to-generate-advanced-ai-dialogue-starters/"><u>Unveiling the Top 5 Innovative Tools to Generate Advanced AI Dialogue Starters</u></a></li>
<li><a href="https://tech-hub.techidaily.com/weaving-tales-gpt-3-and-world-design/"><u>Weaving Tales: GPT-3 and World Design</u></a></li>
</ul></div>
