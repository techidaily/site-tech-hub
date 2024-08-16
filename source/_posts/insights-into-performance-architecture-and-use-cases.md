---
title: Insights Into Performance, Architecture, and Use Cases
date: 2024-08-15T20:53:51.368Z
updated: 2024-08-16T20:53:51.368Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Insights Into Performance, Architecture, and Use Cases
excerpt: This Article Describes Insights Into Performance, Architecture, and Use Cases
thumbnail: https://thmb.techidaily.com/c64aba238bf38e8dde6a455b091ef6dd75fa774a21d0b3000a42b8339ddfda6c.jpg
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
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Installing Microsoft C++ through Build Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-install-c.jpg)

 Now that you have installed the latest versions of Python3, Git, and Microsoft C++, you can download the Python script to easily query custom local data.

**Download:** [ChatGPT-retrieval script](https://github.com/techleadhd/chatgpt-retrieval) (Free)

 To download the script, click on**Code,** then select**Download ZIP** . This should download the Python script into your default or selected directory.

![Downloading Python script on GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-download-script.jpg)

Once downloaded, we can now set up a local environment.

## Step 2: Set Up the Local Environment

 To set up the environment, you'll need to open a terminal in the chatgpt-retrieval-main folder you downloaded. To do that, open**chatgpt-retrieval-main** folder, right-click, and select**Open in Terminal** .

![Opening terminal on directory folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-open-terminal.jpg)

Once the terminal is open, copy and paste this command:

pip install langchain openai chromadb tiktoken unstructured

 This command uses Python's package manager to[create and manage the Python virtual environment](https://www.makeuseof.com/create-manage-python-virtual-environments/) needed.

 After creating the virtual environment, we need to supply an OpenAI API key to access their services. We'll first need to generate an API key from the[OpenAI API keys site](https://platform.openai.com/account/api-keys) by clicking on**Create new secret key** , adding a name for the key, then hitting the**Create secret key button** .

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Creating secret API key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/generate-api-key.jpg)

 You will be provided with a string of characters. This is your OpenAI API key. Copy it by clicking on the copy icon on the side of the API key. Keep note that this API key should be kept secret. Do not share it with others unless you really intend for them to use it with you.

 Once copied, return to the chatgpt-retrieval-main folder and open constants with**Notepad** . Now replace the placeholder with your API key. Remember to save the file!

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Adding API key as environment variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-api-key.jpg)

 Now that you have successfully set up your virtual environment and added your OpenAI API key as an environment variable. You can now provide your custom data to ChatGPT.

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
## Step 3: Adding Custom Data

 To add custom data, place all your custom text data in the**data** folder within chatgpt-retrieval-main. The format of the text data may be in the form of a PDF, TXT, or DOC.

![Adding custom data for ChatGPT](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-data.jpg)

 As you can see from the screenshot above, I've added a text file containing a made-up personal schedule, an article I wrote on[AMD's Instinct Accelerators](https://www.makeuseof.com/what-are-amd-instinct-ai-accelerators/) , and a PDF document.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## Step 4: Querying ChatGPT Through Terminal

 The Python script allows us to query data from the custom data we've added to the data folder and the internet. In other words, you will have access to the usual ChatGPT backend and all the data stored locally in the data folder.

 To use the script, run the python[chatgpt.py](http://chatgpt.py) script and then add your question or query as the argument.

python [chatgpt.py](http://chatgpt.py) "YOUR QUESTION"

Make sure to put your questions in quotation marks.

 To test if we have successfully fed ChatGPT our data, I'll ask a personal question regarding the**Personal Sched.txt** file.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Testing ChatGPT with custom data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/visit.jpg)

 It worked! This means ChatGPT was able to read the Personal Sched.txt provided earlier. Now let's see if we have successfully fed ChatGPT with information it does not know due to its knowledge cutoff date.

![Asking custom ChatGPT about topic outside knowledge cut off data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/m250x.jpg)

 As you can see, it correctly described the AMD Instinct MI250x, which was released after ChatGPT -3's knowledge cutoff date.

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-tips.techidaily.com/udget-friendly-bundles-startup-channels-for-newcomers/"><u>[New] Budget-Friendly Bundles  Startup Channels for Newcomers</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-master-your-fb-video-archive-with-1-5-choices/"><u>[New] In 2024, Master Your FB Video Archive with #1-5 Choices</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-full-reviewed-evaluation-hero4-black-capabilities/"><u>[Updated] Full Reviewed Evaluation  Hero4 Black Capabilities</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-securely-capturing-and-storing-itunes-media-content/"><u>[Updated] Securely Capturing and Storing iTunes Media Content</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-blueprint-for-thriving-in-virtual-events-stream-success-tips/"><u>2024 Approved  Blueprint for Thriving In Virtual Events  Stream Success Tips</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-navigating-to-your-distinctive-tiktok-tag/"><u>2024 Approved  Navigating to Your Distinctive TikTok Tag</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-creative-vanguard-top-6-redefining-digital-arts/"><u>2024 Approved  The Creative Vanguard  Top 6 Redefining Digital Arts</u></a></li>
<li><a href="https://tech-hub.techidaily.com/5-essential-reasons-why-authentic-content-writers-shouldnt-depend-on-ai-powered-chatbots/"><u>5 Essential Reasons Why Authentic Content Writers Shouldn't Depend on AI-Powered Chatbots</u></a></li>
<li><a href="https://tech-hub.techidaily.com/8-ways-ai-enhances-the-future-of-teaching/"><u>8 Ways AI Enhances the Future of Teaching</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ai-revolutionaries-clash-palm-2-versus-gpt-4/"><u>AI Revolutionaries Clash: PaLM 2 Versus GPT-4</u></a></li>
<li><a href="https://tech-hub.techidaily.com/boosting-efficiency-the-ultimate-guide-to-using-chatgpt-effectively/"><u>Boosting Efficiency: The Ultimate Guide to Using ChatGPT Effectively</u></a></li>
<li><a href="https://tech-hub.techidaily.com/can-advanced-language-models-provide-essential-tips-for-outdoor-emergencies/"><u>Can Advanced Language Models Provide Essential Tips for Outdoor Emergencies?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/can-ai-contribute-positively-or-negatively-to-mental-health-care-advancements/"><u>Can AI Contribute Positively or Negatively to Mental Health Care Advancements?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ceo-swap-at-ai-hub-the-future-of-chatgpt-inquiry/"><u>CEO Swap at AI Hub, The Future of ChatGPT Inquiry</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-and-malware-an-ethical-perspective/"><u>ChatGPT & Malware: An Ethical Perspective</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-api-essentials-beginners-roadmap-to-implementation/"><u>ChatGPT API Essentials: Beginner's Roadmap to Implementation</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpts-capability-in-mixing-drinks/"><u>ChatGPT's Capability in Mixing Drinks</u></a></li>
<li><a href="https://tech-hub.techidaily.com/computational-algebra-gpts-role/"><u>Computational Algebra: GPT's Role</u></a></li>
<li><a href="https://tech-hub.techidaily.com/conversational-breakthrough-us-ai-enhanced-with-chatgpt-plus-us20mo/"><u>Conversational Breakthrough: U.S. AI Enhanced with ChatGPT Plus (US$20/Mo)</u></a></li>
<li><a href="https://tech-hub.techidaily.com/crafting-imaginative-realms-with-gpt-3/"><u>Crafting Imaginative Realms with GPT-3</u></a></li>
<li><a href="https://tech-hub.techidaily.com/crafting-success-in-an-algorithmically-augmented-world/"><u>Crafting Success in an Algorithmically Augmented World</u></a></li>
<li><a href="https://tech-hub.techidaily.com/crafting-unforgettable-chat-experiences-5-best-techniques-for-tailored-gpt-commands/"><u>Crafting Unforgettable Chat Experiences: 5 Best Techniques for Tailored GPT Commands</u></a></li>
<li><a href="https://tech-hub.techidaily.com/deciphering-the-distinctions-between-language-processors/"><u>Deciphering the Distinctions Between Language Processors</u></a></li>
<li><a href="https://tech-hub.techidaily.com/decoding-the-mechanics-of-chatgpt-shared-links-an-insightful-exploration/"><u>Decoding the Mechanics of ChatGPT Shared Links - An Insightful Exploration</u></a></li>
<li><a href="https://tech-hub.techidaily.com/decoding-the-phenomenon-of-ai-hallucinations-tips-to-detect-them-effectively/"><u>Decoding the Phenomenon of AI Hallucinations – Tips to Detect Them Effectively</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discover-how-chatgpt-facilitates-effortless-website-building-with-these-4-tactics/"><u>Discover How ChatGPT Facilitates Effortless Website Building with These 4 Tactics</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-cards-of-google-without-puk-codes-by-drfone-android/"><u>In 2024, How To Unlock SIM Cards Of Google Without PUK Codes</u></a></li>
<li><a href="https://vp-tips.techidaily.com/launching-laughter-hilarious-initiation-hints/"><u>Launching Laughter  Hilarious Initiation Hints</u></a></li>
<li><a href="https://driver-install.techidaily.com/streamlining-driver-updates-for-wacom-tablets-in-win-oss-7-10-11/"><u>Streamlining Driver Updates for Wacom Tablets in Win OSs 7-10-11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-essentials-of-artificeal-intelligence-transfer-learning-explained/"><u>The Essentials of Artificeal Intelligence Transfer Learning Explained</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-future-of-education-can-ai-replace-classic-essay-writing-for-students/"><u>The Future of Education: Can AI Replace Classic Essay Writing for Students?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-mystery-of-gptbot-blockage-insights-into-its-function-and-website-restrictions/"><u>The Mystery of GPTBot Blockage: Insights Into Its Function and Website Restrictions</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-writers-dilemma-balancing-human-skill-with-ai-assistance/"><u>The Writers' Dilemma: Balancing Human Skill with AI Assistance</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-5-gpt4-hacks-streamlining-boring-hr-duties/"><u>Top 5 GPT4 Hacks: Streamlining Boring HR Duties</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-7-tools-like-chatgpt-for-autonomous-code-generation/"><u>Top 7 Tools Like ChatGPT for Autonomous Code Generation</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unauthorized-tactics-for-ai-communication-tools/"><u>Unauthorized Tactics for AI Communication Tools</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unleash-creativity-with-these-6-applications-of-chatgpts-code-interpretation-feature/"><u>Unleash Creativity with These 6 Applications of ChatGPT's Code Interpretation Feature</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-4-compelling-reasons-to-embrace-claude-3-over-chatgpt-for-enhanced-interaction/"><u>Unveiling 4 Compelling Reasons to Embrace Claude 3 Over ChatGPT for Enhanced Interaction</u></a></li>
<li><a href="https://tech-hub.techidaily.com/virtual-therapist-tools-safe-ai-for-mental-health/"><u>Virtual Therapist Tools: Safe AI for Mental Health</u></a></li>
<li><a href="https://tech-hub.techidaily.com/waiting-on-the-official-release-of-chatgpt-for-desktops-explore-our-recommended-open-source-solution-now/"><u>Waiting on the Official Release of ChatGPT for Desktops? Explore Our Recommended Open-Source Solution Now!</u></a></li>
</ul></div>
