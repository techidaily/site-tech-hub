---
title: Is It Feasible to Utilize ChatGPT for Proofreading Purposes?
date: 2024-11-05T17:32:37.906Z
updated: 2024-11-07T22:58:20.886Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Is It Feasible to Utilize ChatGPT for Proofreading Purposes?
excerpt: This Article Describes Is It Feasible to Utilize ChatGPT for Proofreading Purposes?
thumbnail: https://thmb.techidaily.com/453561a8ca0d834b48f18b90c63e8754b707ad468e25eb7e04a5333cdbe19d66.jpg
---

## Is CodeGPT The Future of Coding? Evaluating Its Capability to Compose Code

### Quick Links

* [What Is CodeGPT?](https://www.makeuseof.com/code-gpt-can-it-really-write-code/#what-is-codegpt)
* [How Much Does CodeGPT Cost?](https://www.makeuseof.com/code-gpt-can-it-really-write-code/#how-much-does-codegpt-cost)
* [Can CodeGPT Really Write Code?](https://www.makeuseof.com/code-gpt-can-it-really-write-code/#can-codegpt-really-write-code)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* CodeGPT is an AI-powered coding assistant that helps programmers write and fix code, with features like auto-completion and code explanation.
* CodeGPT is available for free, but subscription plans for some features range from $9.99 to $49.99 per month.
* While CodeGPT can write code, its output may not always be error-free or follow best practices, so you should aim to understand and modify the generated code as necessary.

 If you're looking for an AI-powered assistant to help you write code, chances are you've encountered CodeGPT. It's one of many AI-powered tools you can use to assist you when programming. But can CodeGPT actually write code?

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037346/7443" target="_top" id="2037346">
  <img src="//a.impactradius-go.com/display-ad/7443-2037346" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037346/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What Is CodeGPT?

 CodeGPT is a dedicated extension that uses different artificial intelligence (AI) models to help programmers write and fix code. It includes various features geared towards faster and easier programming, including auto-completion, code explanation, refactoring, documentation, unit testing, error-checking, and bug-fixing. It also has a ChatGPT-like interface you can access from your code editor.

 The extension is particularly powerful because it lets you connect to various mainstream[large language models (LLMs)](https://www.makeuseof.com/what-are-large-langauge-models-how-do-they-work/) from different providers like OpenAI and Google. On top of that, CodeGPT lets you create your own AI agents that you can use in your projects or share with others.

 While there are several[code editors for Linux](https://www.makeuseof.com/best-ide-code-editors-for-linux/) , macOS, and Windows, CodeGPT is only available in two. Today, you can either[install and use CodeGPT in VS Code](https://www.makeuseof.com/install-use-codegpt-in-vs-code/) or in Cursor, which is a fork of VS Code.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657395/16446" target="_top" id="1657395">
  <img src="//a.impactradius-go.com/display-ad/16446-1657395" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657395/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How Much Does CodeGPT Cost?

 You can download and install CodeGPT for free, but using the extension comes at a cost. CodeGPT offers various subscription packages that you can pay for if you need unlimited access.

 CodeGPT Plus has three subscription plans. The Basic plan goes for $9.99/month, followed by Standard ($19.99/month) and Gold ($49.99/month). There's a free trial period available, which you can use to evaluate the extension. Each package gives you access to specific AI agents with unlimited interactions.

 Bear in mind that you'll need to pay for unlimited usage of third-party AI models like OpenAI's GPT-4 model, for example. Although you can[access Open AI's GPT-4 model for free](https://www.makeuseof.com/ways-access-gpt-4-free/) , you cannot do so from within VS Code or Cursor.

<!-- affiliate ads begin -->
<a href="https://bluettifr.pxf.io/c/5597632/2145082/17095" target="_top" id="2145082">
  <img src="//a.impactradius-go.com/display-ad/17095-2145082" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettifr.pxf.io/i/5597632/2145082/17095" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-files.techidaily.com/new-elevating-engagement-with-innovative-techniques-in-fb-lives-for-2024/"><u>[New] Elevating Engagement with Innovative Techniques in FB Lives for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-leading-innovation-vr-controllers-reviewed/"><u>[Updated] Leading Innovation VR Controllers Reviewed</u></a></li>
<li><a href="https://win-guides.techidaily.com/1-reset-disk-dan-meminjuhi-garis-baca-ssd-kumpulan-tahuanku-terbaru/"><u>1. Reset Disk Dan Meminjuhi Garis Baca SSD: Kumpulan Tahuanku Terbaru</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpts-source-material-how-it-formulates-answers-without-stealing-ideas/"><u>ChatGPT's Source Material: How It Formulates Answers Without Stealing Ideas</u></a></li>
<li><a href="https://win-howtos.techidaily.com/conquer-minecraft-setbacks-with-ease-fix-your-encounter-with-error-code-5-today/"><u>Conquer Minecraft Setbacks with Ease – Fix Your Encounter with Error Code 5 Today!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/europes-ai-directive-unveiled-implications-for-chatgpt-systems/"><u>Europe's AI Directive Unveiled: Implications for ChatGPT Systems</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/guide-integrating-pinning-features-into-your-facebook-profile/"><u>Guide: Integrating Pinning Features Into Your Facebook Profile</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/211030487-9781648483059-heal-your-past-to-manifest-your-future/"><u>Heal Your Past to Manifest Your Future | Free Book</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-proficient-is-chatgpt-in-the-art-of-cocktail-recipes/"><u>How Proficient Is ChatGPT in the Art of Cocktail Recipes?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-the-journey-to-well-being-creating-goals-with-assistance-from-chatgpt/"><u>Navigating the Journey to Well-Being: Creating Goals with Assistance From ChatGPT</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/tone-generation-made-simple-5-top-online-options/"><u>Tone Generation Made Simple 5 Top Online Options</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-7-incredible-chatgpt-browser-plugins-for-enhanced-ai-interaction-on-your-chrome/"><u>Top 7 Incredible ChatGPT Browser Plugins for Enhanced AI Interaction on Your Chrome</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unleash-conversational-ai-anywhere-with-chatgpts-latest-ios-application/"><u>Unleash Conversational AI Anywhere with ChatGPT's Latest iOS Application</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visualization-mastery-clearing-images-of-extraneous-elements/"><u>Visualization Mastery: Clearing Images of Extraneous Elements</u></a></li>
</ul></div>

