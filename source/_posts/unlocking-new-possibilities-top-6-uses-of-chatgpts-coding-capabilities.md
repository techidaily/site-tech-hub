---
title: "Unlocking New Possibilities: Top 6 Uses of ChatGPT’s Coding Capabilities"
date: 2024-08-24T11:26:00.745Z
updated: 2024-08-25T11:26:00.745Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: "This Article Describes Unlocking New Possibilities: Top 6 Uses of ChatGPT’s Coding Capabilities"
excerpt: "This Article Describes Unlocking New Possibilities: Top 6 Uses of ChatGPT’s Coding Capabilities"
thumbnail: https://thmb.techidaily.com/dbe86f0410f8e9bad5bf3228390b329f698cfe445d25a553d85696ff0b2a85a2.jpg
---

## Is CodeGPT The Future of Coding? Evaluating Its Capability to Compose Code

### Quick Links

* [What Is CodeGPT?](https://www.makeuseof.com/code-gpt-can-it-really-write-code/#what-is-codegpt)
* [How Much Does CodeGPT Cost?](https://www.makeuseof.com/code-gpt-can-it-really-write-code/#how-much-does-codegpt-cost)
* [Can CodeGPT Really Write Code?](https://www.makeuseof.com/code-gpt-can-it-really-write-code/#can-codegpt-really-write-code)

### Key Takeaways

* CodeGPT is an AI-powered coding assistant that helps programmers write and fix code, with features like auto-completion and code explanation.
* CodeGPT is available for free, but subscription plans for some features range from $9.99 to $49.99 per month.
* While CodeGPT can write code, its output may not always be error-free or follow best practices, so you should aim to understand and modify the generated code as necessary.

 If you're looking for an AI-powered assistant to help you write code, chances are you've encountered CodeGPT. It's one of many AI-powered tools you can use to assist you when programming. But can CodeGPT actually write code?

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
## What Is CodeGPT?

 CodeGPT is a dedicated extension that uses different artificial intelligence (AI) models to help programmers write and fix code. It includes various features geared towards faster and easier programming, including auto-completion, code explanation, refactoring, documentation, unit testing, error-checking, and bug-fixing. It also has a ChatGPT-like interface you can access from your code editor.

 The extension is particularly powerful because it lets you connect to various mainstream[large language models (LLMs)](https://www.makeuseof.com/what-are-large-langauge-models-how-do-they-work/) from different providers like OpenAI and Google. On top of that, CodeGPT lets you create your own AI agents that you can use in your projects or share with others.

 While there are several[code editors for Linux](https://www.makeuseof.com/best-ide-code-editors-for-linux/) , macOS, and Windows, CodeGPT is only available in two. Today, you can either[install and use CodeGPT in VS Code](https://www.makeuseof.com/install-use-codegpt-in-vs-code/) or in Cursor, which is a fork of VS Code.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Much Does CodeGPT Cost?

 You can download and install CodeGPT for free, but using the extension comes at a cost. CodeGPT offers various subscription packages that you can pay for if you need unlimited access.

 CodeGPT Plus has three subscription plans. The Basic plan goes for $9.99/month, followed by Standard ($19.99/month) and Gold ($49.99/month). There's a free trial period available, which you can use to evaluate the extension. Each package gives you access to specific AI agents with unlimited interactions.

 Bear in mind that you'll need to pay for unlimited usage of third-party AI models like OpenAI's GPT-4 model, for example. Although you can[access Open AI's GPT-4 model for free](https://www.makeuseof.com/ways-access-gpt-4-free/) , you cannot do so from within VS Code or Cursor.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Can CodeGPT Really Write Code?

 To evaluate this, we'll use the extension to help us generate two different code samples in Python.

 First, we ask the model to generate a stack data structure in Python with all the relevant methods. We used this prompt:

> Create a stack in Python and include all the necessary methods

The model generated the following response:

        `class Stack:  
    def __init__(self):  
        self.stack = []  
​  
    def push(self, item):  
        self.stack.append(item)  
​  
    def pop(self):  
        if self.is_empty():  
            raise IndexError("Pop from empty stack")  
        return self.stack.pop()  
​  
    def peek(self):  
        if self.is_empty():  
            raise IndexError("Peek from empty stack")  
        return self.stack[-1]  
​  
    def is_empty(self):  
        return len(self.stack) == 0  
​  
    def size(self):  
        return len(self.stack)`

 This sample shows that CodeGPT is clever enough to create the stack using a**class** and include the necessary checks to handle specific errors that may arise. For instance, the code throws informative errors if you try to**peek** or**pop** an empty stack.

 In a second challenge, we asked CodeGPT to save a response formatted in JSON from the[JSONPlaceholder](https://jsonplaceholder.typicode.com/) API to a CSV file. For context, the response from the JSONPlaceholder API looks like this:

        `{  
 'userId': 1,  
 'id': 1,  
 'title': 'sunt aut facere repellat provident occaecati excepturi optio reprehenderit',  
 'body': 'quia et suscipit\nsuscipit recusandae consequuntur expedita et cum\nreprehenderit molestiae ut ut quas totam\nnostrum rerum est autem sunt rem eveniet architecto'  
}`

We asked CodeGPT the following:

> I've made a request to an external API at <https://jsonplaceholder.typicode.com/posts/1> and I'm getting a response back. I've formatted the response as json, how can I save it in a csv file?

The code that CodeGPT responded with was:

        `import csv  
import requests  
  
# Make a GET request to the API  

response = requests.get('<https://jsonplaceholder.typicode.com/posts/1>')  

# Convert the response to JSON format  

data = response.json()  
  
# Since we're receiving a dictionary, we need to turn it into a list of one dictionary  

data = [data]  
  
# Open (or create) a CSV file to write the data  

with open('output.csv', 'w', newline='') as output_file:  
   # Create a CSV writer object  
   writer = csv.DictWriter(output_file, fieldnames=data[0].keys())  
   # Write the CSV headers  
   writer.writeheader()  
   # Write the data to the CSV file  
   writer.writerows(data)  
`

 Generally, this response is good; it doesn't need any tweaking to work. CodeGPT also added comments explaining the purpose of the various lines of code, which is useful if you're doing something for the first time.

 The only issue here is the response doesn't specify an encoding type while calling**open()** . While a default will automatically be included, specifying an encoding type is recommended and considered best practice when[writing to files in Python](https://www.makeuseof.com/write-print-to-file-python/) . This might save you from incorrect interpretation, leading to jumbled text.

 So: CodeGPT can write code, but you should be careful because it won't always give you the best output. What you get might be error-prone and might not follow the best practices. Whenever you use CodeGPT or any other AI-powered tool to write code, strive to understand what the code does first. Don't just copy and paste.


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
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-essential-photo-and-film-capture-apps-iphone-and-android-edition/"><u>[New] In 2024, Essential Photo & Film Capture Apps  IPhone & Android Edition</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-brief-but-impactful-which-social-platform-leads-for-short-video-content/"><u>[Updated] In 2024, Brief but Impactful  Which Social Platform Leads for Short Video Content?</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-best-5-ios-backdrop-swappers-x87-edition/"><u>2024 Approved  Best 5 iOS Backdrop Swappers  X/8/7 Edition</u></a></li>
<li><a href="https://tech-hub.techidaily.com/can-user-exchanges-enhance-chatgpts-knowledge-base/"><u>Can User Exchanges Enhance ChatGPT's Knowledge Base?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/challenger-emerges-googles-gemini-rises-against-openais-chatgpt/"><u>Challenger Emerges: Google's Gemini Rises Against OpenAI’s ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpts-privacy-landscape-explored/"><u>ChatGPT's Privacy Landscape Explored</u></a></li>
<li><a href="https://games-able.techidaily.com/dealing-with-switch-dysfunction-restore-or-replace/"><u>Dealing with Switch Dysfunction: Restore or Replace?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/deciphering-ai-unveiling-the-hidden-threats/"><u>Deciphering AI: Unveiling The Hidden Threats</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discover-how-you-can-supercharge-your-workflow-with-our-top-eb-of-9-chatgpt-plugins-get-started-today/"><u>Discover How You Can Supercharge Your Workflow With Our Top Eb of 9 ChatGPT Plugins - Get Started Today!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/does-chatgpt-have-weaknesses-to-exploit/"><u>Does ChatGPT Have Weaknesses to Exploit?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/does-chatgpt-have-what-it-takes-to-brew-perfect-cocktails/"><u>Does ChatGPT Have What It Takes to Brew Perfect Cocktails?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/enhance-your-video-games-with-chatgpt-6-essential-tips-for-writers/"><u>Enhance Your Video Games with ChatGPT: 6 Essential Tips for Writers</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-8-surprising-ways-artificial-intelligence-merges-fact-with-fiction/"><u>Exploring 8 Surprising Ways Artificial Intelligence Merges Fact with Fiction</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-the-capabilities-of-chatgpt-in-proofreading-content/"><u>Exploring the Capabilities of ChatGPT in Proofreading Content</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-the-capabilities-of-nvidias-ai-foundation-an-insight-into-its-modifiable-generative-ai-offering/"><u>Exploring the Capabilities of NVIDIA's AI Foundation: An Insight Into Its Modifiable Generative AI Offering</u></a></li>
<li><a href="https://tech-hub.techidaily.com/from-amateur-to-expert-elevating-your-notes-management-using-chatgpt/"><u>From Amateur to Expert: Elevating Your Notes Management Using ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/future-horizons-in-artificial-intelligence-unveiling-the-potential-of-new-age-generative-bots-and-chat-technologies/"><u>Future Horizons in Artificial Intelligence: Unveiling the Potential of New-Age Generative Bots and Chat Technologies</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-to-optimize-3d-printing-techniques-with-ai-assistant-chatgpt/"><u>How to Optimize 3D Printing Techniques with AI Assistant ChatGPT</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-remove-passcode-from-iphone-7-complete-guide-by-drfone-ios/"><u>How To Remove Passcode From iPhone 7? Complete Guide</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-poco-c50-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Poco C50 | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-forgot-iphone-6s-plus-backup-password-heres-what-to-do-drfone-by-drfone-ios/"><u>In 2024, Forgot iPhone 6s Plus Backup Password? Heres What to Do | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/innovative-strategies-for-revamping-your-video-covers-on-fb-for-2024/"><u>Innovative Strategies for Revamping Your Video Covers on FB for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/innovative-workout-designs-gpt-integration/"><u>Innovative Workout Designs: GPT Integration</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/laughterbox-easy-entry-endless-entertainment-for-2024/"><u>LaughterBox  Easy Entry, Endless Entertainment for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-the-nuances-how-gpt-and-bert-differ-in-advancing-natural-language-processing/"><u>Navigating the Nuances: How GPT and BERT Differ in Advancing Natural Language Processing</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-the-world-of-ai-chatbots-how-does-censorship-shape-your-communications/"><u>Navigating the World of AI Chatbots: How Does Censorship Shape Your Communications?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/parameters-you-must-evaluate-before-choosing-your-bot-servicer/"><u>Parameters You Must Evaluate Before Choosing Your Bot Servicer</u></a></li>
<li><a href="https://tech-hub.techidaily.com/preserve-your-virtual-discussions-with-gpt/"><u>Preserve Your Virtual Discussions with GPT</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-itel-p55-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Itel P55 | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/seamless-stress-relief-track-drivers-fixed/"><u>Seamless Stress Relief: Track Drivers Fixed</u></a></li>
<li><a href="https://tech-hub.techidaily.com/simplifying-complexity-pythons-role-in-gpt-3/"><u>Simplifying Complexity: Python's Role in GPT-3</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-future-is-open-source-understanding-gpt-4-and-its-global-reach/"><u>The Future Is Open Source: Understanding GPT-4 and Its Global Reach</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-intricacies-of-protecting-artificve-works-by-ai-legal-insights/"><u>The Intricacies of Protecting Artificve Works by AI: Legal Insights</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-path-to-a-perfect-life-integrating-chatgpt-techniques/"><u>The Path to a Perfect Life: Integrating ChatGPT Techniques</u></a></li>
<li><a href="https://tech-hub.techidaily.com/tips-on-recognizing-and-responding-to-fake-chatgpt-portals/"><u>Tips on Recognizing and Responding to Fake ChatGPT Portals</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-strategies-for-students-avoiding-common-pitfalls-with-chatgpt/"><u>Top Strategies for Students: Avoiding Common Pitfalls with ChatGPT</u></a></li>
<li><a href="https://tech-hub.techidaily.com/training-for-tech-writing-compelling-chatbot-queries/"><u>Training for Tech: Writing Compelling Chatbot Queries</u></a></li>
<li><a href="https://tech-hub.techidaily.com/transformative-writing-for-pinterest-descriptions-chatgpt/"><u>Transformative Writing for Pinterest Descriptions (ChatGPT)</u></a></li>
<li><a href="https://tech-hub.techidaily.com/trustworthy-techniques-confirming-accuracy-of-medical-info-from-chatbots-and-ai-systems/"><u>Trustworthy Techniques: Confirming Accuracy of Medical Info From Chatbots & AI Systems</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unleashing-digital-potential-discover-why-perplexity-ai-is-your-ultimate-go-to-ai-driven-google-search-assistant/"><u>Unleashing Digital Potential: Discover Why Perplexity AI Is Your Ultimate Go-To AI-Driven Google Search Assistant!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-the-fraudulent-chatgpt-clones-that-threaten-to-hijack-your-information/"><u>Unveiling the Fraudulent ChatGPT Clones That Threaten to Hijack Your Information</u></a></li>
<li><a href="https://tech-hub.techidaily.com/voice-enabled-chatgpt-from-openai-a-leap-forward-in-interactive-prompt-responses/"><u>Voice-Enabled ChatGPT From OpenAI: A Leap Forward in Interactive Prompt Responses</u></a></li>
<li><a href="https://tech-hub.techidaily.com/windows-compatible-no-cost-alternative-to-chatgpt-mastering-freedomgpt-installation-and-use/"><u>Windows-Compatible, No-Cost Alternative to ChatGPT: Mastering FreedomGPT Installation & Use</u></a></li>
</ul></div>
