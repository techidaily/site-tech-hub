---
title: Keep Personal Details Clear From AI Screens
date: 2024-09-06T21:42:45.461Z
updated: 2024-09-07T21:42:45.461Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Keep Personal Details Clear From AI Screens
excerpt: This Article Describes Keep Personal Details Clear From AI Screens
thumbnail: https://thmb.techidaily.com/eda53d482272507886f33101cf7c17fbcff2ff9c0e3000602465b544e6ae7c53.jpg
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
<a href="https://smilemakers.pxf.io/c/5597632/2123899/26106" target="_top" id="2123899">
  <img src="//a.impactradius-go.com/display-ad/26106-2123899" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123899/26106" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Python3 and Microsoft C++ Installation Notes

 When installing Python3, make sure that you tick the**Add python.exe to PATH** option before clicking**Install Now** . This is important as it allows you to access Python in any directory on your computer.

![Adding Python to PATH](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/1-download-python.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135411/19272" target="_top" id="2135411">
  <img src="//a.impactradius-go.com/display-ad/19272-2135411" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 When Installing Microsoft C++, you'll want to install**Microsoft Visual Studio Build Tools** first. Once installed, you can tick the**Desktop development with C++** option and click**Install** with all the optional tools automatically ticked on the right sidebar.

![Installing Microsoft C++ through Build Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-install-c.jpg)

 Now that you have installed the latest versions of Python3, Git, and Microsoft C++, you can download the Python script to easily query custom local data.

**Download:** [ChatGPT-retrieval script](https://github.com/techleadhd/chatgpt-retrieval) (Free)

 To download the script, click on**Code,** then select**Download ZIP** . This should download the Python script into your default or selected directory.

![Downloading Python script on GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-download-script.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Once downloaded, we can now set up a local environment.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115911/19272" target="_top" id="2115911">
  <img src="//a.impactradius-go.com/display-ad/19272-2115911" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115911/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Step 2: Set Up the Local Environment

 To set up the environment, you'll need to open a terminal in the chatgpt-retrieval-main folder you downloaded. To do that, open**chatgpt-retrieval-main** folder, right-click, and select**Open in Terminal** .

![Opening terminal on directory folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-open-terminal.jpg)

Once the terminal is open, copy and paste this command:

pip install langchain openai chromadb tiktoken unstructured

 This command uses Python's package manager to[create and manage the Python virtual environment](https://www.makeuseof.com/create-manage-python-virtual-environments/) needed.

 After creating the virtual environment, we need to supply an OpenAI API key to access their services. We'll first need to generate an API key from the[OpenAI API keys site](https://platform.openai.com/account/api-keys) by clicking on**Create new secret key** , adding a name for the key, then hitting the**Create secret key button** .

![Creating secret API key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/generate-api-key.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137218/26400" target="_top" id="2137218">
  <img src="//a.impactradius-go.com/display-ad/26400-2137218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137218/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You will be provided with a string of characters. This is your OpenAI API key. Copy it by clicking on the copy icon on the side of the API key. Keep note that this API key should be kept secret. Do not share it with others unless you really intend for them to use it with you.

 Once copied, return to the chatgpt-retrieval-main folder and open constants with**Notepad** . Now replace the placeholder with your API key. Remember to save the file!

![Adding API key as environment variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-api-key.jpg)

 Now that you have successfully set up your virtual environment and added your OpenAI API key as an environment variable. You can now provide your custom data to ChatGPT.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130528/26400" target="_top" id="2130528">
  <img src="//a.impactradius-go.com/display-ad/26400-2130528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130528/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Step 3: Adding Custom Data

 To add custom data, place all your custom text data in the**data** folder within chatgpt-retrieval-main. The format of the text data may be in the form of a PDF, TXT, or DOC.

![Adding custom data for ChatGPT](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-data.jpg)

 As you can see from the screenshot above, I've added a text file containing a made-up personal schedule, an article I wrote on[AMD's Instinct Accelerators](https://www.makeuseof.com/what-are-amd-instinct-ai-accelerators/) , and a PDF document.

<!-- affiliate ads begin -->
<span id="1328679">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328679.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328679">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328679.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328679%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328679/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Step 4: Querying ChatGPT Through Terminal

 The Python script allows us to query data from the custom data we've added to the data folder and the internet. In other words, you will have access to the usual ChatGPT backend and all the data stored locally in the data folder.

 To use the script, run the python[chatgpt.py](http://chatgpt.py) script and then add your question or query as the argument.

python [chatgpt.py](http://chatgpt.py) "YOUR QUESTION"

Make sure to put your questions in quotation marks.

 To test if we have successfully fed ChatGPT our data, I'll ask a personal question regarding the**Personal Sched.txt** file.

![Testing ChatGPT with custom data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/visit.jpg)

 It worked! This means ChatGPT was able to read the Personal Sched.txt provided earlier. Now let's see if we have successfully fed ChatGPT with information it does not know due to its knowledge cutoff date.

![Asking custom ChatGPT about topic outside knowledge cut off data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/m250x.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014851/22899" target="_top" id="2014851">
  <img src="//a.impactradius-go.com/display-ad/22899-2014851" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014851/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 As you can see, it correctly described the AMD Instinct MI250x, which was released after ChatGPT -3's knowledge cutoff date.

## Limitations of Custom ChatGPT

 Although feeding GPT-3.5 with custom data opens more ways to apply and use the LLM, there are a few drawbacks and limitations.

 Firstly, you need to provide all the data yourself. You can still access all the knowledge of GPT-3.5 until its knowledge cutoff date; however, you must provide all the extra data. This means if you want your local model to be knowledgeable of a certain subject on the internet that GPT-3.5 don't already know, you'll have to go to the internet and scrape the data yourself and save it as a text on the data folder of chatgpt-retrieval-main.

 Another issue is that querying ChatGPT like this takes more time to load when compared to asking ChatGPT directly.

 Lastly, the only model currently available is GPT-3.5 Turbo. So even if you have access to GPT-4, you won't be able to use it to power your custom ChatGPT instance.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115951/19272" target="_top" id="2115951">
  <img src="//a.impactradius-go.com/display-ad/19272-2115951" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115951/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-smart-snap-strategies-insta-story-zoom-101/"><u>[New] 2024 Approved Smart Snap Strategies Insta Story Zoom 101</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-select-the-best-cameras-beyond-your-gopro-companion/"><u>[New] Select the Best Cameras Beyond Your GoPro Companion</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-most-engaging-ar-games-for-phones-revealed/"><u>[New] The Most Engaging AR Games for Phones Revealed</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-tech-savvy-tips-for-recording-video-calls/"><u>[Updated] 2024 Approved Tech-Savvy Tips for Recording Video Calls</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-use-video-titles-and-youtube-tags/"><u>[Updated] In 2024, How to Use Video Titles and YouTube Tags?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-framework-for-visual-storytelling/"><u>2024 Approved Framework for Visual Storytelling</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-masterful-manipulation-speedy-stylization-techniques-for-win10-apps/"><u>2024 Approved Masterful Manipulation Speedy Stylization Techniques for WIN10 Apps</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-sharecast-extracting-fb-media/"><u>2024 Approved ShareCast Extracting Fb Media</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-oneplus-nord-ce-3-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your OnePlus Nord CE 3 5G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/boost-your-office-efficiency-with-onlyoffice-docspaces-innovative-chatgpt-toolset/"><u>Boost Your Office Efficiency with ONLYOFFICE DocSpace's Innovative ChatGPT Toolset</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-steps-for-soothing-the-soul/"><u>ChatGPT Steps for Soothing the Soul</u></a></li>
<li><a href="https://tech-hub.techidaily.com/decoding-googles-ai-vision-an-exploration-into-geminis-mission-and-scope/"><u>Decoding Google's AI Vision - An Exploration Into Gemini’s Mission and Scope</u></a></li>
<li><a href="https://tech-hub.techidaily.com/demystifying-claude-3-and-its-potential/"><u>Demystifying Claude 3 and Its Potential</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discover-7-cost-free-chatbot-applications-for-quick-travel-planning-assistance/"><u>Discover 7 Cost-Free Chatbot Applications for Quick Travel Planning Assistance</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discover-the-power-of-chatgpt-in-personal-healthcare-learn-why-its-worth-considering-now/"><u>Discover the Power of ChatGPT in Personal Healthcare – Learn Why It's Worth Considering Now</u></a></li>
<li><a href="https://tech-hub.techidaily.com/educational-tips-how-to-properly-leverage-chatgpt-as-a-learner/"><u>Educational Tips: How to Properly Leverage ChatGPT as a Learner</u></a></li>
<li><a href="https://tech-hub.techidaily.com/effective-fixes-for-chatgpt-is-busy-errors-in-microsoft-windows-environments/"><u>Effective Fixes for 'ChatGPT Is Busy' Errors in Microsoft Windows Environments</u></a></li>
<li><a href="https://tech-hub.techidaily.com/essential-plugins-to-skip-in-gpt-enhancements/"><u>Essential Plugins to Skip in GPT Enhancements</u></a></li>
<li><a href="https://tech-hub.techidaily.com/evaluating-the-value-of-chatgpt-plus-membership/"><u>Evaluating the Value of ChatGPT Plus Membership</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/first-footsteps-into-frame-finesse-a-novices-guide-to-hd-content-for-2024/"><u>First Footsteps Into Frame Finesse A Novice's Guide to HD Content for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-do-vector-databases-enhance-machine-learning/"><u>How Do Vector Databases Enhance Machine Learning?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-universal-unlock-pattern-for-lava-agni-2-5g-by-drfone-android/"><u>In 2024, Universal Unlock Pattern for Lava Agni 2 5G</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-it-possible-to-earn-extra-cash-with-these-8-chatgpt-assisted-jobs/"><u>Is It Possible to Earn Extra Cash with These 8 ChatGPT-Assisted Jobs?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/master-the-art-of-ai-discover-7-proven-prompting-methods-for-successful-interactions/"><u>Master the Art of AI: Discover 7 Proven Prompting Methods for Successful Interactions</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-through-openais-api-landscape-a-complete-users-handbook/"><u>Navigating Through OpenAI's API Landscape: A Complete User's Handbook</u></a></li>
<li><a href="https://games-able.techidaily.com/reconnecting-issues-revive-your-gaming-experience-with-headsets/"><u>Reconnecting Issues? Revive Your Gaming Experience with Headsets</u></a></li>
<li><a href="https://tech-hub.techidaily.com/silicon-smile-stimulators-can-giggle-codecs-engage-emotion/"><u>Silicon Smile Stimulators: Can Giggle Codecs Engage Emotion?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-6-benefits-of-mastering-chatgpt-a-game-changer-for-job-hunters-and-professionals/"><u>Top 6 Benefits of Mastering ChatGPT: A Game-Changer for Job Hunters & Professionals</u></a></li>
<li><a href="https://tech-hub.techidaily.com/transform-your-digital-experience-creating-customized-gpt-models-after-chatgpts-update/"><u>Transform Your Digital Experience: Creating Customized GPT Models After ChatGPT's Update</u></a></li>
<li><a href="https://tech-hub.techidaily.com/transform-your-living-space-with-intelligent-chatgpt-controls/"><u>Transform Your Living Space With Intelligent ChatGPT Controls</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-ai-prompt-engineering-is-this-profession-future-proof/"><u>Understanding AI Prompt Engineering: Is This Profession Future-Proof?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-the-competition-testing-and-contrasting-mistral-ais-le-chat-with-chatgpt/"><u>Unveiling the Competition: Testing and Contrasting Mistral AI’s Le Chat with ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-the-mystery-how-does-chatgpts-shared-link-feature-function/"><u>Unveiling the Mystery: How Does ChatGPT's Shared Link Feature Function?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/zero-registration-full-access-discover-how-to-use-chatgpt-instantly-5-tricks/"><u>Zero Registration, Full Access: Discover How to Use ChatGPT Instantly [5 Tricks]</u></a></li>
</ul></div>
