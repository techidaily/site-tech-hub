---
title: Design Personalized Language Agents
date: 2024-08-15T20:38:57.073Z
updated: 2024-08-16T20:38:57.073Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Design Personalized Language Agents
excerpt: This Article Describes Design Personalized Language Agents
thumbnail: https://thmb.techidaily.com/9d6bb2044f5f33dd6b599b386099f3868d77bd593d3d88e2cde5996f7415935f.jpg
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Installing Microsoft C++ through Build Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-install-c.jpg)

 Now that you have installed the latest versions of Python3, Git, and Microsoft C++, you can download the Python script to easily query custom local data.

**Download:** [ChatGPT-retrieval script](https://github.com/techleadhd/chatgpt-retrieval) (Free)

 To download the script, click on**Code,** then select**Download ZIP** . This should download the Python script into your default or selected directory.

![Downloading Python script on GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-download-script.jpg)

Once downloaded, we can now set up a local environment.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Step 2: Set Up the Local Environment

 To set up the environment, you'll need to open a terminal in the chatgpt-retrieval-main folder you downloaded. To do that, open**chatgpt-retrieval-main** folder, right-click, and select**Open in Terminal** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Opening terminal on directory folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-open-terminal.jpg)

Once the terminal is open, copy and paste this command:

pip install langchain openai chromadb tiktoken unstructured

 This command uses Python's package manager to[create and manage the Python virtual environment](https://www.makeuseof.com/create-manage-python-virtual-environments/) needed.

 After creating the virtual environment, we need to supply an OpenAI API key to access their services. We'll first need to generate an API key from the[OpenAI API keys site](https://platform.openai.com/account/api-keys) by clicking on**Create new secret key** , adding a name for the key, then hitting the**Create secret key button** .

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Creating secret API key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/generate-api-key.jpg)

 You will be provided with a string of characters. This is your OpenAI API key. Copy it by clicking on the copy icon on the side of the API key. Keep note that this API key should be kept secret. Do not share it with others unless you really intend for them to use it with you.

 Once copied, return to the chatgpt-retrieval-main folder and open constants with**Notepad** . Now replace the placeholder with your API key. Remember to save the file!

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Adding API key as environment variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-api-key.jpg)

 Now that you have successfully set up your virtual environment and added your OpenAI API key as an environment variable. You can now provide your custom data to ChatGPT.

## Step 3: Adding Custom Data

 To add custom data, place all your custom text data in the**data** folder within chatgpt-retrieval-main. The format of the text data may be in the form of a PDF, TXT, or DOC.

![Adding custom data for ChatGPT](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-data.jpg)

 As you can see from the screenshot above, I've added a text file containing a made-up personal schedule, an article I wrote on[AMD's Instinct Accelerators](https://www.makeuseof.com/what-are-amd-instinct-ai-accelerators/) , and a PDF document.

## Step 4: Querying ChatGPT Through Terminal

 The Python script allows us to query data from the custom data we've added to the data folder and the internet. In other words, you will have access to the usual ChatGPT backend and all the data stored locally in the data folder.

 To use the script, run the python[chatgpt.py](http://chatgpt.py) script and then add your question or query as the argument.

python [chatgpt.py](http://chatgpt.py) "YOUR QUESTION"

Make sure to put your questions in quotation marks.

 To test if we have successfully fed ChatGPT our data, I'll ask a personal question regarding the**Personal Sched.txt** file.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![Testing ChatGPT with custom data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/visit.jpg)

 It worked! This means ChatGPT was able to read the Personal Sched.txt provided earlier. Now let's see if we have successfully fed ChatGPT with information it does not know due to its knowledge cutoff date.

![Asking custom ChatGPT about topic outside knowledge cut off data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/m250x.jpg)

 As you can see, it correctly described the AMD Instinct MI250x, which was released after ChatGPT -3's knowledge cutoff date.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Limitations of Custom ChatGPT

 Although feeding GPT-3.5 with custom data opens more ways to apply and use the LLM, there are a few drawbacks and limitations.

 Firstly, you need to provide all the data yourself. You can still access all the knowledge of GPT-3.5 until its knowledge cutoff date; however, you must provide all the extra data. This means if you want your local model to be knowledgeable of a certain subject on the internet that GPT-3.5 don't already know, you'll have to go to the internet and scrape the data yourself and save it as a text on the data folder of chatgpt-retrieval-main.

 Another issue is that querying ChatGPT like this takes more time to load when compared to asking ChatGPT directly.

 Lastly, the only model currently available is GPT-3.5 Turbo. So even if you have access to GPT-4, you won't be able to use it to power your custom ChatGPT instance.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
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
<li><a href="https://screen-recording.techidaily.com/new-jumping-into-the-virtual-discussions-via-google-for-2024/"><u>[New] Jumping Into the Virtual Discussions via Google for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-10-best-hashtag-tracker-for-facebook-twitter-and-instagram/"><u>[Updated] 2024 Approved  10 Best Hashtag Tracker for Facebook, Twitter and Instagram</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-pixelhalve-critique/"><u>[Updated] 2024 Approved  PixelHalve Critique</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-discreetly-streaming-top-8-video-tools-of-the-year-2023-for-2024/"><u>[Updated] Discreetly Streaming  Top 8 Video Tools of the Year, 2023 for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-beginners-bible-to-your-youtube-audio-visual-arsenal/"><u>[Updated] In 2024, Beginner's Bible to Your YouTube Audio-Visual Arsenal</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-mastering-sound-on-your-apple-device-top-picks/"><u>[Updated] In 2024, Mastering Sound on Your Apple Device (Top Picks)</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-win-11s-best-practices-the-ultimate-guide-to-saving-mov-files/"><u>[Updated] Win 11'S Best Practices  The Ultimate Guide to Saving MOV Files</u></a></li>
<li><a href="https://tech-hub.techidaily.com/18-next-level-sales-management-applications-beyond-gpts-realm/"><u>18 Next-Level Sales Management Applications Beyond GPT's Realm</u></a></li>
<li><a href="https://tech-hub.techidaily.com/a-comprehensive-guide-to-claude-pro-and-its-relationship-with-microsofts-chatgpt-plus/"><u>A Comprehensive Guide to Claude Pro and Its Relationship with Microsoft’s ChatGPT Plus</u></a></li>
<li><a href="https://tech-hub.techidaily.com/a-step-by-step-approach-to-chatgpt-with-iphones-siri/"><u>A Step-by-Step Approach to ChatGPT with iPhone's Siri</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ai-and-the-quest-for-textual-awareness-investigating-why-chatgpt-fails-to-detect-its-own-prose/"><u>AI and the Quest for Textual Awareness: Investigating Why ChatGPT Fails to Detect Its Own Prose</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ai-date-coach-chatgpt-for-romance/"><u>AI Date Coach: ChatGPT for Romance</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigate-the-world-of-dating-smarter-with-ai-assisted-tips-from-chatgpt/"><u>Navigate the World of Dating Smarter with AI-Assisted Tips From ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/need-to-know-if-chatgpt-works-today-try-out-these-n-five-proven-techniques/"><u>Need to Know If ChatGPT Works Today? Try Out These N Five Proven Techniques</u></a></li>
<li><a href="https://tech-hub.techidaily.com/next-viewing-destination-mastering-the-art-of-using-chatgpt-for-film-and-show-recommendations/"><u>Next Viewing Destination: Mastering the Art of Using ChatGPT for Film and Show Recommendations</u></a></li>
<li><a href="https://tech-hub.techidaily.com/power-players-the-5-most-exciting-developments-in-artificial-intelligence-hardware/"><u>Power Players: The 5 Most Exciting Developments in Artificial Intelligence Hardware</u></a></li>
<li><a href="https://tech-hub.techidaily.com/revolutionize-your-web-chats-with-these-7-must-have-chatgpt-browser-extensions/"><u>Revolutionize Your Web Chats with These 7 Must-Have ChatGPT Browser Extensions</u></a></li>
<li><a href="https://tech-hub.techidaily.com/script-synergy-6-creative-uses-for-chatgpt-in-video-games/"><u>Script Synergy: 6 Creative Uses for ChatGPT in Video Games</u></a></li>
<li><a href="https://tech-hub.techidaily.com/seize-opportunities-in-openais-challenge-for-error-discovery/"><u>Seize Opportunities in OpenAI’s Challenge for Error Discovery</u></a></li>
<li><a href="https://tech-hub.techidaily.com/simplify-your-prompting-technique-using-this-powerful-chatgpt-chrome-tool/"><u>Simplify Your Prompting Technique Using This Powerful ChatGPT Chrome Tool</u></a></li>
<li><a href="https://tech-hub.techidaily.com/smart-studying-without-dependence-on-chatgpt/"><u>Smart Studying Without Dependence on ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/step-by-step-guide-setting-up-microsoft-copilot-on-your-apple-computer/"><u>Step-by-Step Guide: Setting Up Microsoft Copilot on Your Apple Computer</u></a></li>
<li><a href="https://tech-hub.techidaily.com/textual-journeys-gameplay-mastery-through-chatgpt/"><u>Textual Journeys: Gameplay Mastery Through ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-art-of-acoustic-synthesis-leveraging-chatgpt-for-unique-sounds-in-digital-audio-workstations/"><u>The Art of Acoustic Synthesis: Leveraging ChatGPT for Unique Sounds in Digital Audio Workstations</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-enduring-impact-and-future-role-of-the-turing-test/"><u>The Enduring Impact and Future Role of the Turing Test</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/the-fundamentals-of-video-localization-how-to-dub-your-films-in-wondershare-filmora/"><u>The Fundamentals of Video Localization How to Dub Your Films in Wondershare Filmora</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-perspectives-of-10-global-tech-visionaries-on-the-evolution-of-ai/"><u>The Perspectives of 10 Global Tech Visionaries on the Evolution of AI</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-ultimate-list-of-7-ai-programs-enhancing-your-ability-to-solve-math-puzzles/"><u>The Ultimate List of 7 AI Programs Enhancing Your Ability to Solve Math Puzzles</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-5-risks-of-relying-on-chatgpt-for-health-consultations/"><u>Top 5 Risks of Relying on ChatGPT for Health Consultations</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-reasons-to-steer-clear-of-chatgpt-applications-in-your-macs-marketplace/"><u>Top Reasons to Steer Clear of ChatGPT Applications in Your Mac's Marketplace</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ultimate-rankings-top-free-pc-gaming-experiences-and-the-ultimate-guide-to-mechanical-keyboards/"><u>Ultimate Rankings: Top Free PC Gaming Experiences and the Ultimate Guide to Mechanical Keyboards</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-ai-chatbots-their-rise-in-popularity-explained/"><u>Understanding AI Chatbots: Their Rise in Popularity Explained</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unleashing-chatgpts-potential-on-your-mac-computer/"><u>Unleashing ChatGPT's Potential on Your Mac Computer</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-ai-assistance-an-in-depth-look-at-chatgpt-copilots-features/"><u>Unlocking AI Assistance: An In-Depth Look at ChatGPT Copilot's Features</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-convenience-how-to-implement-bing-ai-assistance-directly-on-your-phones-typing-interface/"><u>Unlocking Convenience: How to Implement Bing AI Assistance Directly on Your Phone’s Typing Interface</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-new-possibilities-for-your-business-with-chatgpt-and-whisper-api-integration/"><u>Unlocking New Possibilities for Your Business with ChatGPT & Whisper API Integration</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-the-best-ai-is-it-gemini-pro-or-chatgptplus/"><u>Unveiling the Best AI: Is It Gemini Pro or ChatGPT+?</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-top-10-best-cartoon-video-maker-apps-on-android-and-iphone/"><u>Updated Top 10 Best Cartoon Video Maker Apps on Android and iPhone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/updating-graphics-drivers-the-amd-way-compatible-with-windows-10-8-and-vista/"><u>Updating Graphics Drivers: The AMD Way - Compatible with Windows 10, 8 & Vista</u></a></li>
<li><a href="https://tech-hub.techidaily.com/what-exactly-is-codegpt-can-this-ai-reliably-write-software-code/"><u>What Exactly Is CodeGPT? Can This AI Reliably Write Software Code?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/which-is-superior-for-software-development-github-copilot-or-chatgpt-face-off/"><u>Which Is Superior for Software Development? GitHub Copilot or ChatGPT Face-Off</u></a></li>
<li><a href="https://howto.techidaily.com/why-is-my-honor-x50-offline-troubleshooting-guide-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Is My Honor X50 Offline? Troubleshooting Guide | Dr.fone</u></a></li>
</ul></div>
