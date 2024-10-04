---
title: Essential Steps to Uplift GPT's Integrated Plugin Platform
date: 2024-09-29T08:48:34.082Z
updated: 2024-10-03T23:55:53.113Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Essential Steps to Uplift GPT's Integrated Plugin Platform
excerpt: This Article Describes Essential Steps to Uplift GPT's Integrated Plugin Platform
thumbnail: https://thmb.techidaily.com/f29f99d4419c1c54f223ae0fe4e25f224aa2e0b29936958ff74ebecc1f44d1d0.png
---

## Transform Personal Datasets Into an Intelligent, Customized ChatBot – Learn How

 Providing GPT technology in a powerful and easy-to-use chatbot, ChatGPT has become the world's most popular AI tool. Many people use ChatGPT to provide engaging conversations, answer queries, offer creative suggestions, and aid in coding and writing. However, ChatGPT is limited as you cannot store your data for long-term personal use, and its September 2021 knowledge data cutoff point.

 As a workaround, we can use OpenAI's API and LangChain to provide ChatGPT with custom data and updated info past 2021 to create a custom ChatGPT instance.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148642/16836" target="_top" id="2148642">
  <img src="//a.impactradius-go.com/display-ad/16836-2148642" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148642/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now that you have installed the latest versions of Python3, Git, and Microsoft C++, you can download the Python script to easily query custom local data.

**Download:** [ChatGPT-retrieval script](https://github.com/techleadhd/chatgpt-retrieval) (Free)

 To download the script, click on**Code,** then select**Download ZIP** . This should download the Python script into your default or selected directory.

![Downloading Python script on GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-download-script.jpg)

Once downloaded, we can now set up a local environment.

<!-- affiliate ads begin -->
<span id="1983475">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983475.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983475">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983475.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983475%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983475/22993" style="position:absolute;visibility:hidden;" border="0" />
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

 Now that you have successfully set up your virtual environment and added your OpenAI API key as an environment variable. You can now provide your custom data to ChatGPT.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037358/7443" target="_top" id="2037358">
  <img src="//a.impactradius-go.com/display-ad/7443-2037358" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037358/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Step 3: Adding Custom Data

 To add custom data, place all your custom text data in the**data** folder within chatgpt-retrieval-main. The format of the text data may be in the form of a PDF, TXT, or DOC.

![Adding custom data for ChatGPT](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-data.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925549/19272" target="_top" id="1925549">
  <img src="//a.impactradius-go.com/display-ad/19272-1925549" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925549/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036467/19272" target="_top" id="2036467">
  <img src="//a.impactradius-go.com/display-ad/19272-2036467" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036467/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 As you can see, it correctly described the AMD Instinct MI250x, which was released after ChatGPT -3's knowledge cutoff date.

## Limitations of Custom ChatGPT

 Although feeding GPT-3.5 with custom data opens more ways to apply and use the LLM, there are a few drawbacks and limitations.

 Firstly, you need to provide all the data yourself. You can still access all the knowledge of GPT-3.5 until its knowledge cutoff date; however, you must provide all the extra data. This means if you want your local model to be knowledgeable of a certain subject on the internet that GPT-3.5 don't already know, you'll have to go to the internet and scrape the data yourself and save it as a text on the data folder of chatgpt-retrieval-main.

 Another issue is that querying ChatGPT like this takes more time to load when compared to asking ChatGPT directly.

 Lastly, the only model currently available is GPT-3.5 Turbo. So even if you have access to GPT-4, you won't be able to use it to power your custom ChatGPT instance.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115921/19272" target="_top" id="2115921">
  <img src="//a.impactradius-go.com/display-ad/19272-2115921" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115921/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-clips.techidaily.com/new-best-hashtags-for-youtube-to-get-your-views-to-6-figures/"><u>[New] Best Hashtags for YouTube To Get Your Views to 6 Figures</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-find-your-digital-companion-the-top-6-youtube-personality-puzzles-for-2024/"><u>[New] Find Your Digital Companion The Top 6 YouTube Personality Puzzles for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-celebrated-20-independent-pubg-photo-sequences/"><u>[Updated] Celebrated 20 Independent PUBG Photo Sequences</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-on-apple-iphone-12-pro-max-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code On Apple iPhone 12 Pro Max</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-oppo-reno-11-5g-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Oppo Reno 11 5G | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-switching-on-windows-11s-adaptive-hdr-option/"><u>In 2024, Switching On Windows 11'S Adaptive HDR Option</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/instagram-stories-incorporating-natural-bokeh-effects/"><u>Instagram Stories Incorporating Natural Bokeh Effects</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-it-worth-exploring-auto-gpt-while-anticipating-the-release-of-gpt-4/"><u>Is It Worth Exploring Auto-GPT While Anticipating the Release of GPT-4?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-truthgpt-coin-genuine-or-fraudulent-uncovering-the-facts/"><u>Is TruthGPT Coin Genuine or Fraudulent? Uncovering the Facts</u></a></li>
<li><a href="https://tech-hub.techidaily.com/life-made-effortless-unlocking-the-power-of-chatgpt-in-9-ways/"><u>Life Made Effortless: Unlocking the Power of ChatGPT in 9 Ways</u></a></li>
<li><a href="https://tech-hub.techidaily.com/maintaining-confidentiality-with-chatgpt-at-the-office-a-comprehensive-guide/"><u>Maintaining Confidentiality with ChatGPT at the Office: A Comprehensive Guide</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-chatgpt-the-ultimate-guide-to-writing-winning-prompts-for-excellent-outcomes/"><u>Mastering ChatGPT: The Ultimate Guide to Writing Winning Prompts for Excellent Outcomes</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-relaxation-managing-anxiety-using-chatgpt/"><u>Mastering Relaxation: Managing Anxiety Using ChatGPT</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-persistent-problems-ensuring-stability-in-your-microsoft-outlook-experience/"><u>Resolving Persistent Problems: Ensuring Stability in Your Microsoft Outlook Experience</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722878305339-what-does-a-502-bad-gateway-issue-mean-a-simple-fixing-manual/"><u>What Does a 502 Bad Gateway Issue Mean? A Simple Fixing Manual.</u></a></li>
</ul></div>

