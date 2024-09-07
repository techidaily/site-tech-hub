---
title: Transform Personal Datasets Into an Intelligent, Customized ChatBot – Learn How
date: 2024-09-06T21:48:06.381Z
updated: 2024-09-07T21:48:06.381Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Transform Personal Datasets Into an Intelligent, Customized ChatBot – Learn How
excerpt: This Article Describes Transform Personal Datasets Into an Intelligent, Customized ChatBot – Learn How
thumbnail: https://thmb.techidaily.com/104a8ce1329a7cadce28c36353075eec1970039296b8147989b16ec309b7b44b.jpg
---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115913/19272" target="_top" id="2115913">
  <img src="//a.impactradius-go.com/display-ad/19272-2115913" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115913/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<span id="1304648">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1304648.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1304648">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1304648.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1304648%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1304648/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Step 1: Install and Download Software and Pre-Made Script

 Please note the following instructions are for a Windows 10 or Windows 11 machine.

 To provide custom data to ChatGPT, you'll need to install and download the latest Python3, Git, Microsoft C++, and the ChatGPT-retrieval script from GitHub. If you already have some of the software installed on your PC, make sure they are updated with the latest version to avoid any hiccups during the process.

Start by installing:

* **Download:** [Python3](https://www.python.org/downloads/) (Free)
* **Download:** [Git](https://git-scm.com/downloads) (Free)
* **Download:** [Microsoft Visual Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/) (Free)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Python3 and Microsoft C++ Installation Notes

 When installing Python3, make sure that you tick the**Add python.exe to PATH** option before clicking**Install Now** . This is important as it allows you to access Python in any directory on your computer.

![Adding Python to PATH](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/1-download-python.jpg)

 When Installing Microsoft C++, you'll want to install**Microsoft Visual Studio Build Tools** first. Once installed, you can tick the**Desktop development with C++** option and click**Install** with all the optional tools automatically ticked on the right sidebar.

![Installing Microsoft C++ through Build Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-install-c.jpg)

 Now that you have installed the latest versions of Python3, Git, and Microsoft C++, you can download the Python script to easily query custom local data.

**Download:** [ChatGPT-retrieval script](https://github.com/techleadhd/chatgpt-retrieval) (Free)

 To download the script, click on**Code,** then select**Download ZIP** . This should download the Python script into your default or selected directory.

![Downloading Python script on GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-download-script.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123478/16836" target="_top" id="2123478">
  <img src="//a.impactradius-go.com/display-ad/16836-2123478" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123478/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Once downloaded, we can now set up a local environment.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Step 2: Set Up the Local Environment

 To set up the environment, you'll need to open a terminal in the chatgpt-retrieval-main folder you downloaded. To do that, open**chatgpt-retrieval-main** folder, right-click, and select**Open in Terminal** .

![Opening terminal on directory folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-open-terminal.jpg)

Once the terminal is open, copy and paste this command:

pip install langchain openai chromadb tiktoken unstructured

 This command uses Python's package manager to[create and manage the Python virtual environment](https://www.makeuseof.com/create-manage-python-virtual-environments/) needed.

 After creating the virtual environment, we need to supply an OpenAI API key to access their services. We'll first need to generate an API key from the[OpenAI API keys site](https://platform.openai.com/account/api-keys) by clicking on**Create new secret key** , adding a name for the key, then hitting the**Create secret key button** .

![Creating secret API key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/generate-api-key.jpg)

 You will be provided with a string of characters. This is your OpenAI API key. Copy it by clicking on the copy icon on the side of the API key. Keep note that this API key should be kept secret. Do not share it with others unless you really intend for them to use it with you.

 Once copied, return to the chatgpt-retrieval-main folder and open constants with**Notepad** . Now replace the placeholder with your API key. Remember to save the file!

![Adding API key as environment variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-api-key.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139121/17108" target="_top" id="2139121">
  <img src="//a.impactradius-go.com/display-ad/17108-2139121" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139121/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now that you have successfully set up your virtual environment and added your OpenAI API key as an environment variable. You can now provide your custom data to ChatGPT.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115918/19272" target="_top" id="2115918">
  <img src="//a.impactradius-go.com/display-ad/19272-2115918" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115918/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Step 3: Adding Custom Data

 To add custom data, place all your custom text data in the**data** folder within chatgpt-retrieval-main. The format of the text data may be in the form of a PDF, TXT, or DOC.

![Adding custom data for ChatGPT](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-data.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2135473/26400" target="_top" id="2135473">
  <img src="//a.impactradius-go.com/display-ad/26400-2135473" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2135473/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

## Limitations of Custom ChatGPT

 Although feeding GPT-3.5 with custom data opens more ways to apply and use the LLM, there are a few drawbacks and limitations.

 Firstly, you need to provide all the data yourself. You can still access all the knowledge of GPT-3.5 until its knowledge cutoff date; however, you must provide all the extra data. This means if you want your local model to be knowledgeable of a certain subject on the internet that GPT-3.5 don't already know, you'll have to go to the internet and scrape the data yourself and save it as a text on the data folder of chatgpt-retrieval-main.

 Another issue is that querying ChatGPT like this takes more time to load when compared to asking ChatGPT directly.

 Lastly, the only model currently available is GPT-3.5 Turbo. So even if you have access to GPT-4, you won't be able to use it to power your custom ChatGPT instance.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137972/21526" target="_top" id="2137972">
  <img src="//a.impactradius-go.com/display-ad/21526-2137972" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137972/21526" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-unwatched-to-watched-top-10-reasons-and-solutions-for-no-views/"><u>[New] 2024 Approved From Unwatched to Watched Top 10 Reasons & Solutions for No Views</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-excellent-mac-bandicam-substitutes-5/"><u>[New] Excellent Mac Bandicam Substitutes [#5]</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-unleash-creativity-youtube-videos-on-instagram-snapshits/"><u>[Updated] 2024 Approved Unleash Creativity YouTube Videos on Instagram Snapshits</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-enhancing-instagram-communications-through-video-engagement/"><u>[Updated] In 2024, Enhancing Instagram Communications Through Video Engagement</u></a></li>
<li><a href="https://video-capture.techidaily.com/5-outstanding-racing-simulations-for-gamers/"><u>5 Outstanding Racing Simulations for Gamers</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-tecno-spark-go-2023-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Tecno Spark Go (2023)</u></a></li>
<li><a href="https://extra-resources.techidaily.com/accelerated-photography-browser-for-11-os-users-for-2024/"><u>Accelerated Photography Browser for 11 OS Users for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/beginners-roadmap-to-creating-your-perfect-home-sound-experience/"><u>Beginner's Roadmap to Creating Your Perfect Home Sound Experience</u></a></li>
<li><a href="https://tech-hub.techidaily.com/boost-your-resume-with-chatgpt-tips-and-tricks-for-an-effective-cover-letter/"><u>Boost Your Resume with ChatGPT: Tips and Tricks for an Effective Cover Letter</u></a></li>
<li><a href="https://tech-hub.techidaily.com/can-ai-powered-chatgpt-create-personalized-risk-free-exercise-programs-perfectly-suited-to-your-needs/"><u>Can AI-Powered ChatGPT Create Personalized, Risk-Free Exercise Programs Perfectly Suited to Your Needs?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/can-artificial-intelligence-genuinely-grasp-the-complexity-of-human-emotions-through-emotion-ai-technologies/"><u>Can Artificial Intelligence Genuinely Grasp the Complexity of Human Emotions Through Emotion AI Technologies?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/can-generative-artificial-intelligence-become-a-disinformation-powerhouse/"><u>Can Generative Artificial Intelligence Become a Disinformation Powerhouse?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/comparing-copilot-vs-copilot-pro-is-an-upgrade-worth-it/"><u>Comparing Copilot Vs. Copilot Pro: Is an Upgrade Worth It?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/content-stealthy-escape-detectors-at-a-standstill/"><u>Content Stealthy Escape: Detectors at a Standstill</u></a></li>
<li><a href="https://tech-hub.techidaily.com/create-stunning-visuals-8-prompt-ideas-using-dall-e-3/"><u>Create Stunning Visuals: 8 Prompt Ideas Using DALL-E 3</u></a></li>
<li><a href="https://tech-hub.techidaily.com/creating-unique-workout-plans-through-gpt/"><u>Creating Unique Workout Plans Through GPT</u></a></li>
<li><a href="https://fox-info.techidaily.com/cutting-edge-mini-drones-for-the-savvy-buyer/"><u>Cutting-Edge Mini Drones for the Savvy Buyer</u></a></li>
<li><a href="https://tech-hub.techidaily.com/effective-strategies-utilizing-chatgpt-for-personal-automotive-modification-assistance/"><u>Effective Strategies: Utilizing ChatGPT for Personal Automotive Modification Assistance</u></a></li>
<li><a href="https://tech-hub.techidaily.com/efficient-techniques-on-how-to-backup-your-chat-history-with-chatgpt/"><u>Efficient Techniques on How to Backup Your Chat History with ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/enhanced-ai-interaction-why-you-should-opt-for-the-chatgpt-desktop-application-instead-of-browsing-the-site/"><u>Enhanced AI Interaction – Why You Should Opt for the ChatGPT Desktop Application Instead of Browsing the Site</u></a></li>
<li><a href="https://tech-hub.techidaily.com/essential-dos-and-donts-mastering-chatgpt-in-your-academic-journey/"><u>Essential Dos and Don'ts: Mastering ChatGPT in Your Academic Journey</u></a></li>
<li><a href="https://tech-hub.techidaily.com/evaluating-the-value-of-a-chatgpt-plus-membership/"><u>Evaluating the Value of a ChatGPT Plus Membership</u></a></li>
<li><a href="https://tech-hub.techidaily.com/fusing-language-and-creativity-with-chatgpt/"><u>Fusing Language and Creativity with ChatGPT</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-find-download-and-apply-the-latest-amd-vega-hemenade-56-driver-update-for-your-windows-machine/"><u>How to Find, Download, and Apply the Latest AMD Vega Hemenade 56 Driver Update for Your Windows Machine</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/immediate-capture-in-zoom-conferences-via-snap-for-2024/"><u>Immediate Capture in Zoom Conferences via Snap for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/improving-upon-dall-e-3s-recent-addition-of-editing-instruments/"><u>Improving upon DALL-E 3'S Recent Addition of Editing Instruments</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-from-xiaomi-redmi-note-13-5g-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock from Xiaomi Redmi Note 13 5G Devices</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-immerse-in-windows-11s-photo-quality-filter-options-and-music-playlists/"><u>In 2024, Immerse in Windows 11'S Photo Quality Filter Options and Music Playlists</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-slowly-suppressing-audio-loudness/"><u>In 2024, Slowly Suppressing Audio Loudness</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-chatgpt-vision-discover-8-effective-applications-for-your-work/"><u>Mastering ChatGPT Vision: Discover 8 Effective Applications for Your Work</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-chatgpt-five-essential-tips-for-writing-winning-prompts/"><u>Mastering ChatGPT: Five Essential Tips for Writing Winning Prompts</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-crypto-conversations-with-chatgpt-10-expert-approved-prompts/"><u>Mastering Crypto Conversations with ChatGPT: 10 Expert-Approved Prompts</u></a></li>
<li><a href="https://tech-hub.techidaily.com/revamp-your-cars-performance-using-ai-powered-suggestions-from-chatgpt/"><u>Revamp Your Car's Performance Using AI-Powered Suggestions From ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-ultimate-guide-harnessing-the-power-of-chatgpt-for-academic-success/"><u>The Ultimate Guide: Harnessing the Power of ChatGPT for Academic Success</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/things-you-should-know-when-unlocking-total-wireless-of-apple-iphone-11-pro-max-by-drfone-ios/"><u>Things You Should Know When Unlocking Total Wireless Of Apple iPhone 11 Pro Max</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-computer-components-expert-reviews-and-buying-guides/"><u>Tom's Computer Components - Expert Reviews and Buying Guides</u></a></li>
<li><a href="https://buynow-info.techidaily.com/top-rated-key-trackers/"><u>Top Rated Key Trackers</u></a></li>
<li><a href="https://tech-hub.techidaily.com/transforming-3d-design-to-production-with-chatgpt-insights/"><u>Transforming 3D Design to Production with ChatGPT Insights</u></a></li>
<li><a href="https://tech-hub.techidaily.com/transforming-your-interview-game-insights-for-leveraging-chatgpt/"><u>Transforming Your Interview Game - Insights for Leveraging ChatGPT</u></a></li>
<li><a href="https://buynow-info.techidaily.com/turbocharge-your-drive-exploring-the-cutting-edge-car-code-readers-and-articles-released-so-far-in-los-angeles-rev/"><u>Turbocharge Your Drive: Exploring the Cutting Edge Car Code Readers and Articles Released So Far In Los Angeles (Rev.)</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/twitter-treatment-creating-gifs-without-spending-a-dime/"><u>Twitter Treatment Creating GIFs Without Spending a Dime</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-gpt-3-activating-the-latest-beta-functionality-for-web-exploration-and-extension-compatibility/"><u>Unlocking GPT-3: Activating the Latest Beta Functionality for Web Exploration and Extension Compatibility</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-my-ai-on-snapchat-the-powerful-tool-that-goes-beyond-simple-entertainment/"><u>Unveiling My AI on Snapchat: The Powerful Tool That Goes Beyond Simple Entertainment</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/youtube-live-selling-boost-your-sales-with-these-tips-for-2024/"><u>YouTube Live Selling Boost Your Sales With These Tips for 2024</u></a></li>
</ul></div>
