---
title: 10 Custom GPTs That Actually Make ChatGPT Better
date: 2024-08-15T20:21:05.190Z
updated: 2024-08-16T20:21:05.190Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes 10 Custom GPTs That Actually Make ChatGPT Better
excerpt: This Article Describes 10 Custom GPTs That Actually Make ChatGPT Better
thumbnail: https://thmb.techidaily.com/6050aa5ce58a3d916a0355d32e6800af8938ccf6ad706af2327feef0ddd5dc8b.jpg
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

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Python3 and Microsoft C++ Installation Notes

 When installing Python3, make sure that you tick the**Add python.exe to PATH** option before clicking**Install Now** . This is important as it allows you to access Python in any directory on your computer.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
![Adding Python to PATH](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/1-download-python.jpg)

 When Installing Microsoft C++, you'll want to install**Microsoft Visual Studio Build Tools** first. Once installed, you can tick the**Desktop development with C++** option and click**Install** with all the optional tools automatically ticked on the right sidebar.

![Installing Microsoft C++ through Build Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-install-c.jpg)

 Now that you have installed the latest versions of Python3, Git, and Microsoft C++, you can download the Python script to easily query custom local data.

**Download:** [ChatGPT-retrieval script](https://github.com/techleadhd/chatgpt-retrieval) (Free)

 To download the script, click on**Code,** then select**Download ZIP** . This should download the Python script into your default or selected directory.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
![Downloading Python script on GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-download-script.jpg)

Once downloaded, we can now set up a local environment.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
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

![Creating secret API key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/generate-api-key.jpg)

 You will be provided with a string of characters. This is your OpenAI API key. Copy it by clicking on the copy icon on the side of the API key. Keep note that this API key should be kept secret. Do not share it with others unless you really intend for them to use it with you.

 Once copied, return to the chatgpt-retrieval-main folder and open constants with**Notepad** . Now replace the placeholder with your API key. Remember to save the file!

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
![Adding API key as environment variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-api-key.jpg)

 Now that you have successfully set up your virtual environment and added your OpenAI API key as an environment variable. You can now provide your custom data to ChatGPT.

## Step 3: Adding Custom Data

 To add custom data, place all your custom text data in the**data** folder within chatgpt-retrieval-main. The format of the text data may be in the form of a PDF, TXT, or DOC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
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

![Asking custom ChatGPT about topic outside knowledge cut off data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/m250x.jpg)

 As you can see, it correctly described the AMD Instinct MI250x, which was released after ChatGPT -3's knowledge cutoff date.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
## Limitations of Custom ChatGPT

 Although feeding GPT-3.5 with custom data opens more ways to apply and use the LLM, there are a few drawbacks and limitations.

 Firstly, you need to provide all the data yourself. You can still access all the knowledge of GPT-3.5 until its knowledge cutoff date; however, you must provide all the extra data. This means if you want your local model to be knowledgeable of a certain subject on the internet that GPT-3.5 don't already know, you'll have to go to the internet and scrape the data yourself and save it as a text on the data folder of chatgpt-retrieval-main.

 Another issue is that querying ChatGPT like this takes more time to load when compared to asking ChatGPT directly.

 Lastly, the only model currently available is GPT-3.5 Turbo. So even if you have access to GPT-4, you won't be able to use it to power your custom ChatGPT instance.

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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-30-must-have-youtube-intros-tools-for-beginners-all-free/"><u>[New] 2024 Approved  30 Must-Have YouTube Intros Tools for Beginners, All Free</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-bandicam-revolutionizing-screen-capture-for-modern-media/"><u>[New] Bandicam  Revolutionizing Screen Capture for Modern Media</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-navigating-through-top-film-makers-landscape/"><u>[Updated] Navigating Through Top Film Makers' Landscape</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-direct-downloading-of-audio-content-from-vimeo-videos/"><u>2024 Approved  Direct Downloading of Audio Content From Vimeo Videos</u></a></li>
<li><a href="https://facebook.techidaily.com/7-ideal-planning-platforms-for-content-release-management/"><u>7 Ideal Planning Platforms for Content Release Management</u></a></li>
<li><a href="https://fake-location.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-motorola-moto-g-5g-2023-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Motorola Moto G 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/beyond-capabilities-gpts-excluded-commands/"><u>Beyond Capabilities: GPT's Excluded Commands</u></a></li>
<li><a href="https://tech-hub.techidaily.com/boost-your-writing-workflow-with-these-8-powerful-ai-resources/"><u>Boost Your Writing Workflow with These 8 Powerful AI Resources</u></a></li>
<li><a href="https://tech-hub.techidaily.com/can-you-depend-on-chatgpt-for-accurate-health-insights-and-tips/"><u>Can You Depend on ChatGPT for Accurate Health Insights and Tips?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatbots-and-coins-elevating-your-crypto-game-with-gpt/"><u>Chatbots and Coins: Elevating Your Crypto Game with GPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-gains-a-tongue-unveiling-openais-breakthrough-in-speaking-prompt-interaction/"><u>ChatGPT Gains a Tongue: Unveiling OpenAI's Breakthrough in Speaking Prompt Interaction</u></a></li>
<li><a href="https://tech-hub.techidaily.com/debunking-digital-health-misinformation-check-for-accuracy/"><u>Debunking Digital Health Misinformation: Check for Accuracy</u></a></li>
<li><a href="https://tech-hub.techidaily.com/deceptive-gpt-extension-rips-off-fb-credentials/"><u>Deceptive GPT Extension: Rips Off FB Credentials</u></a></li>
<li><a href="https://tech-hub.techidaily.com/deciphering-codegpt-the-future-of-programming-with-ai/"><u>Deciphering CodeGPT: The Future of Programming with AI?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/deciphering-forefront-ai-versus-chatgpt-which-leads-the-way-in-ai-innovation/"><u>Deciphering Forefront AI Versus ChatGPT - Which Leads the Way in AI Innovation?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/does-the-traditional-turing-test-still-hold-up-exploring-current-alternatives/"><u>Does The Traditional Turing Test Still Hold Up? Exploring Current Alternatives</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/effective-strategies-for-twitter-marketing-for-2024/"><u>Effective Strategies for Twitter Marketing for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/enhance-efficiency-with-ai-master-the-art-of-automated-writing-with-hix-and-gpt-narratives/"><u>Enhance Efficiency with AI: Master the Art of Automated Writing with HIX and GPT-Narratives</u></a></li>
<li><a href="https://tech-hub.techidaily.com/enhancing-creativity-and-writing-with-chatgpt-a-guide-for-better-content/"><u>Enhancing Creativity & Writing with ChatGPT: A Guide for Better Content</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ensuring-data-privacy-with-ai-safeguarding-against-potential-leaks-in-tailored-gpt-technologies/"><u>Ensuring Data Privacy with AI: Safeguarding Against Potential Leaks in Tailored GPT Technologies</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ensuring-reliable-health-insights-from-ai-platforms/"><u>Ensuring Reliable Health Insights From AI Platforms</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-chatgpt-copilot-functions-and-capabilities-explained/"><u>Exploring ChatGPT Copilot: Functions & Capabilities Explained</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-the-impact-of-microsofts-strategic-move-to-acquire-blizzard-ai-artistry-and-translation-tech-podcast-spotlight/"><u>Exploring the Impact of Microsoft's Strategic Move to Acquire Blizzard, AI Artistry, & Translation Tech - Podcast Spotlight</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/fb-video-downloader-extraordinaire-mp4-transformation-for-2024/"><u>FB Video Downloader Extraordinaire - MP4 Transformation for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/fixing-the-save-function-in-chatgpt-expert-advice-and-tricks/"><u>Fixing the Save Function in ChatGPT: Expert Advice and Tricks</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-honor-x50iplus-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Honor X50i+ | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/gpt-powered-insights-googles-data-transformation/"><u>GPT-Powered Insights: Google's Data Transformation</u></a></li>
<li><a href="https://tech-hub.techidaily.com/guardians-of-tomorrow-mastering-chatgpt-and-generative-artificam-to-guide-your-children/"><u>Guardians of Tomorrow: Mastering ChatGPT and Generative Artificam to Guide Your Children</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-safe-are-addons-enhancing-chatgpt-experience/"><u>How Safe Are Addons Enhancing ChatGPT Experience?</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/how-to-record-tv-shows-on-windows-pc-with-free-video-recording-software-in-2024/"><u>How to Record TV Shows on Windows PC with Free Video Recording Software, In 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-apple-iphone-15-pro-activation-lock-by-drfone-ios/"><u>How to Remove Apple iPhone 15 Pro Activation Lock</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-track-apple-iphone-14-pro-location-without-installing-software-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Track Apple iPhone 14 Pro Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-accessing-chatgpt-compatible-with-virtual-private-networks-find-out-here/"><u>Is Accessing ChatGPT Compatible With Virtual Private Networks? Find Out Here!</u></a></li>
<li><a href="https://driver-download.techidaily.com/lenovo-x1-carbon-effortless-driver-downloads-compatible-with-windows-11-and-7/"><u>Lenovo X1 Carbon: Effortless Driver Downloads Compatible with Windows 11 and 7</u></a></li>
<li><a href="https://tech-hub.techidaily.com/leveraging-chatgpts-ai-to-create-persuasive-and-effective-proposals/"><u>Leveraging ChatGPT's AI to Create Persuasive and Effective Proposals</u></a></li>
<li><a href="https://tech-hub.techidaily.com/maximizing-efficiency-top-4-chatgpt-strategies-for-productivity-boost/"><u>Maximizing Efficiency: Top 4 ChatGPT Strategies for Productivity Boost</u></a></li>
<li><a href="https://tech-hub.techidaily.com/maximizing-productivity-at-work-with-chatgpt-discover-7-effective-techniques/"><u>Maximizing Productivity at Work with ChatGPT: Discover 7 Effective Techniques</u></a></li>
<li><a href="https://tech-hub.techidaily.com/maximizing-remote-collaboration-leveraging-chatgpt-in-virtual-team-gatherings/"><u>Maximizing Remote Collaboration: Leveraging ChatGPT in Virtual Team Gatherings</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-policy-four-strategies-for-oversight-of-ai-systems-by-government-entities/"><u>Navigating Policy: Four Strategies for Oversight of AI Systems by Government Entities</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-tomorrows-career-landscape-the-sevenfold-impact-of-generative-ai-on-global-labor/"><u>Navigating Tomorrow's Career Landscape: The Sevenfold Impact of Generative AI on Global Labor</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-free-avi-video-rotators-a-roundup-of-the-best-tools-for-all-platforms/"><u>New In 2024, Free AVI Video Rotators A Roundup of the Best Tools for All Platforms</u></a></li>
<li><a href="https://tech-hub.techidaily.com/protecting-sensitive-data-a-guide-to-using-chatgpt-responsibly-in-the-workplace/"><u>Protecting Sensitive Data: A Guide to Using ChatGPT Responsibly in the Workplace</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/0-guides-for-crafting-stellar-music-reactions-on-youtube/"><u>Top 10 Guides for Crafting Stellar Music Reactions on YouTube</u></a></li>
</ul></div>
