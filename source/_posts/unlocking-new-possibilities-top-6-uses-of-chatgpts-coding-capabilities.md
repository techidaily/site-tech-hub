---
title: "Unlocking New Possibilities: Top 6 Uses of ChatGPT’s Coding Capabilities"
date: 2025-01-04T01:31:18.265Z
updated: 2025-01-07T02:25:36.871Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [What Is CodeGPT?](https://www.makeuseof.com/code-gpt-can-it-really-write-code/#what-is-codegpt)
* [How Much Does CodeGPT Cost?](https://www.makeuseof.com/code-gpt-can-it-really-write-code/#how-much-does-codegpt-cost)
* [Can CodeGPT Really Write Code?](https://www.makeuseof.com/code-gpt-can-it-really-write-code/#can-codegpt-really-write-code)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* CodeGPT is an AI-powered coding assistant that helps programmers write and fix code, with features like auto-completion and code explanation.
* CodeGPT is available for free, but subscription plans for some features range from $9.99 to $49.99 per month.
* While CodeGPT can write code, its output may not always be error-free or follow best practices, so you should aim to understand and modify the generated code as necessary.

 If you're looking for an AI-powered assistant to help you write code, chances are you've encountered CodeGPT. It's one of many AI-powered tools you can use to assist you when programming. But can CodeGPT actually write code?

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is CodeGPT?

 CodeGPT is a dedicated extension that uses different artificial intelligence (AI) models to help programmers write and fix code. It includes various features geared towards faster and easier programming, including auto-completion, code explanation, refactoring, documentation, unit testing, error-checking, and bug-fixing. It also has a ChatGPT-like interface you can access from your code editor.

 The extension is particularly powerful because it lets you connect to various mainstream[large language models (LLMs)](https://www.makeuseof.com/what-are-large-langauge-models-how-do-they-work/) from different providers like OpenAI and Google. On top of that, CodeGPT lets you create your own AI agents that you can use in your projects or share with others.

 While there are several[code editors for Linux](https://www.makeuseof.com/best-ide-code-editors-for-linux/) , macOS, and Windows, CodeGPT is only available in two. Today, you can either[install and use CodeGPT in VS Code](https://www.makeuseof.com/install-use-codegpt-in-vs-code/) or in Cursor, which is a fork of VS Code.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Much Does CodeGPT Cost?

 You can download and install CodeGPT for free, but using the extension comes at a cost. CodeGPT offers various subscription packages that you can pay for if you need unlimited access.

 CodeGPT Plus has three subscription plans. The Basic plan goes for $9.99/month, followed by Standard ($19.99/month) and Gold ($49.99/month). There's a free trial period available, which you can use to evaluate the extension. Each package gives you access to specific AI agents with unlimited interactions.

 Bear in mind that you'll need to pay for unlimited usage of third-party AI models like OpenAI's GPT-4 model, for example. Although you can[access Open AI's GPT-4 model for free](https://www.makeuseof.com/ways-access-gpt-4-free/) , you cannot do so from within VS Code or Cursor.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-zero.techidaily.com/aptivating-viewers-with-youtubes-visual-polishing/"><u>[New] Captivating Viewers with Youtube's Visual Polishing</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-pinnacle-ai-transcribers-for-speech/"><u>[Updated] 2024 Approved Pinnacle AI Transcribers for Speech</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-easy-ways-to-record-a-powerpoint-presentation-for-2024/"><u>[Updated] Easy Ways to Record a PowerPoint Presentation for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-mastering-youtube-to-mp4-the-ultimate-guide/"><u>[Updated] Mastering YouTube to MP4 The Ultimate Guide</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-unlock-youtube-insights-via-social-blade-mastering-your-video-metrics-for-2024/"><u>[Updated] Unlock YouTube Insights via Social Blade Mastering Your Video Metrics for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/beware-of-ai-written-content-spotting-fake-texts/"><u>Beware of AI-Written Content: Spotting Fake Texts</u></a></li>
<li><a href="https://tech-hub.techidaily.com/business-evolution-unleashing-power-of-chatgpt-and-whisper-apis/"><u>Business Evolution: Unleashing Power of ChatGPT and Whisper APIs</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discover-8-essential-ai-chatgpt-add-ons-for-fitness-enthusiasts/"><u>Discover 8 Essential AI ChatGPT Add-Ons for Fitness Enthusiasts</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exploring-the-smooth-and-user-friendly-world-of-amazon-luna-gaming-streams/"><u>Exploring the Smooth and User-Friendly World of Amazon Luna Gaming Streams</u></a></li>
<li><a href="https://tech-hub.techidaily.com/gpts-evolution-continues-four-key-innovations-we-anticipate-in-gpt-5/"><u>GPT's Evolution Continues: Four Key Innovations We Anticipate in GPT-5</u></a></li>
<li><a href="https://win-solutions.techidaily.com/guide-resolving-persistent-crashing-problems-with-pacific-drive-for-pc-users/"><u>Guide: Resolving Persistent Crashing Problems with Pacific Drive for PC Users</u></a></li>
<li><a href="https://tech-hub.techidaily.com/journey-redefined-chatbot-wisdom-in-car-customization-processes/"><u>Journey Redefined: Chatbot Wisdom in Car Customization Processes</u></a></li>
<li><a href="https://tech-hub.techidaily.com/lexicon-league-up-battle-of-the-best-translator/"><u>Lexicon League-Up: Battle of the Best Translator</u></a></li>
<li><a href="https://extra-skills.techidaily.com/libre-meditation-harmonies-for-2024/"><u>Libre Meditation Harmonies for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-call-from-openais-chief-executive-understanding-the-importance-of-increased-artifice-intelligence-regulation/"><u>The Call From OpenAI's Chief Executive: Understanding the Importance of Increased Artifice Intelligence Regulation</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/the-ultimate-guide-to-surviving-in-days-gone-motorcycle-adventures-amongst-the-dead/"><u>The Ultimate Guide to Surviving in 'Days Gone': Motorcycle Adventures Amongst the Dead</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/top-5-dvd-conversion-techniques-to-mkv/"><u>Top 5 DVD Conversion Techniques to MKV</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-codegpts-potential-inside-your-vs-code-workspace/"><u>Unlocking CodeGPT's Potential Inside Your VS Code Workspace</u></a></li>
<li><a href="https://tech-hub.techidaily.com/zerogpt-mistrust-why-ai-tools-can-fail-too/"><u>ZeroGPT Mistrust: Why AI Tools Can Fail Too</u></a></li>
</ul></div>

