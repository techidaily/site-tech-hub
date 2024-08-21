---
title: Assessing the Capability of ChatGPT for Mathematical Computation
date: 2024-08-20T11:04:48.473Z
updated: 2024-08-21T11:04:48.473Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Assessing the Capability of ChatGPT for Mathematical Computation
excerpt: This Article Describes Assessing the Capability of ChatGPT for Mathematical Computation
thumbnail: https://thmb.techidaily.com/a13a6e974ab2cc36089a6059bc5652aa7fea0848996089325ea48fd7dd51fd22.jpg
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
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## What Is CodeGPT?

 CodeGPT is a dedicated extension that uses different artificial intelligence (AI) models to help programmers write and fix code. It includes various features geared towards faster and easier programming, including auto-completion, code explanation, refactoring, documentation, unit testing, error-checking, and bug-fixing. It also has a ChatGPT-like interface you can access from your code editor.

 The extension is particularly powerful because it lets you connect to various mainstream[large language models (LLMs)](https://www.makeuseof.com/what-are-large-langauge-models-how-do-they-work/) from different providers like OpenAI and Google. On top of that, CodeGPT lets you create your own AI agents that you can use in your projects or share with others.

 While there are several[code editors for Linux](https://www.makeuseof.com/best-ide-code-editors-for-linux/) , macOS, and Windows, CodeGPT is only available in two. Today, you can either[install and use CodeGPT in VS Code](https://www.makeuseof.com/install-use-codegpt-in-vs-code/) or in Cursor, which is a fork of VS Code.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## How Much Does CodeGPT Cost?

 You can download and install CodeGPT for free, but using the extension comes at a cost. CodeGPT offers various subscription packages that you can pay for if you need unlimited access.

 CodeGPT Plus has three subscription plans. The Basic plan goes for $9.99/month, followed by Standard ($19.99/month) and Gold ($49.99/month). There's a free trial period available, which you can use to evaluate the extension. Each package gives you access to specific AI agents with unlimited interactions.

 Bear in mind that you'll need to pay for unlimited usage of third-party AI models like OpenAI's GPT-4 model, for example. Although you can[access Open AI's GPT-4 model for free](https://www.makeuseof.com/ways-access-gpt-4-free/) , you cannot do so from within VS Code or Cursor.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-enabling-speech-to-text-on-powerpoint-essential-steps/"><u>[New] 2024 Approved  Enabling Speech-to-Text on PowerPoint  Essential Steps</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-from-downloading-setting-up-to-using-obs-effectively-on-macos/"><u>[New] 2024 Approved  From Downloading, Setting Up, to Using OBS Effectively on macOS</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-gaming-income-optimization-tips/"><u>[New] 2024 Approved  Gaming Income Optimization Tips</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-maximizing-social-reach-with-tiktok-to-facebook-integration/"><u>[New] 2024 Approved  Maximizing Social Reach with TikTok to Facebook Integration</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-social-media-impact-tiktoks-viral-tweets-at-the-forefront/"><u>[New] 2024 Approved  Social Media Impact  TikTok's Viral Tweets at the Forefront</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-expert-guide-implementing-time-loops-in-obs/"><u>[New] In 2024, Expert Guide  Implementing Time Loops in OBS</u></a></li>
<li><a href="https://tech-hub.techidaily.com/solved-bluetooth-keyboard-stop-working-in-windows-10/"><u>[Solved] Bluetooth Keyboard Stop Working in Windows 10</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-essential-techniques-for-quick-and-reliable-recording-of-online-classes/"><u>[Updated] 2024 Approved  Essential Techniques for Quick and Reliable Recording of Online Classes</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-adding-a-cinematic-touch-ken-burns-in-camtasa-9-for-2024/"><u>[Updated] Adding a Cinematic Touch  Ken Burns in Camtasa 9 for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-experts-picks-top-5-webcams-revolutionizing-game-streaming/"><u>[Updated] Expert's Picks  Top 5 Webcams Revolutionizing Game Streaming</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-top-12-best-animal-simulator-games-for-android/"><u>[Updated] In 2024, Top 12 Best Animal Simulator Games for Android</u></a></li>
<li><a href="https://tech-hub.techidaily.com/a-comprehensive-guide-to-configuring-miracast-on-your-pc-with-windows-1011-and-resolving-issues/"><u>A Comprehensive Guide to Configuring Miracast on Your PC with Windows 10/11 and Resolving Issues</u></a></li>
<li><a href="https://tech-hub.techidaily.com/best-torrenting-platforms-for-gaming-enthusiasts-ranked-and-reviewed/"><u>Best Torrenting Platforms for Gaming Enthusiasts: Ranked and Reviewed!</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/comprehensive-apple-tv-4k-analysis-experience-next-gen-super-high-definition-viewing-and-seamless-voice-assistant-navigation/"><u>Comprehensive Apple TV 4K Analysis: Experience Next-Gen, Super High-Definition Viewing & Seamless Voice Assistant Navigation</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1723807925014-directx-refresh-tutorial-for-windows-11-and-10-fast-and-effortless-process/"><u>DirectX Refresh Tutorial for Windows 11 & 10: Fast & Effortless Process</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-nubia-z50s-pro-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Nubia Z50S Pro | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-simplify-meetings-a-comprehensive-guide-to-skype-call-recorders/"><u>In 2024, Simplify Meetings  A Comprehensive Guide to Skype Call Recorders</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1723808314030-in-laminar-flow-the-velocity-profile-across-a-pipe-section-is-parabolic-with-maximum-velocity-at-the-center/"><u>In Laminar Flow, the Velocity Profile Across a Pipe Section Is Parabolic with Maximum Velocity at the Center</u></a></li>
<li><a href="https://tech-hub.techidaily.com/maintain-peak-performance-a-tutorial-on-installing-new-drivers-in-windows-11/"><u>Maintain Peak Performance: A Tutorial on Installing New Drivers in Windows 11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/mastering-media-an-intuitive-approach-to-pc-mac-and-mobile-movies-for-2024/"><u>Mastering Media  An Intuitive Approach to PC, Mac & Mobile Movies for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-multi-tasking-a-guide-to-splitting-your-ipads-screen/"><u>Mastering Multi-Tasking: A Guide to Splitting Your iPad's Screen</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-window-10-strategies-for-ultimate-optimization-and-improvement/"><u>Mastering Window 10: Strategies for Ultimate Optimization and Improvement</u></a></li>
<li><a href="https://tech-hub.techidaily.com/maximizing-your-pcs-bluetooth-connectivity-tips-and-tricks-for-windows-10-and-11/"><u>Maximizing Your PC's Bluetooth Connectivity: Tips & Tricks for Windows 10 and 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/optimize-your-privacy-with-chromes-best-vpn-services-instant-easy-configuration/"><u>Optimize Your Privacy with Chrome's Best VPN Services - Instant, Easy Configuration</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1723808075442-play-fallout-3-seamlessly-on-windows-11-tips-and-tricks-inside/"><u>Play Fallout 3 Seamlessly on Windows 11 – Tips & Tricks Inside!</u></a></li>
<li><a href="https://fox-helps.techidaily.com/professional-tips-for-high-quality-video-disc-production-on-mac-for-2024/"><u>Professional Tips for High-Quality Video Disc Production on Mac for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/quick-and-simple-guide-reset-your-facebook-password-instantly/"><u>Quick and Simple Guide: Reset Your Facebook Password Instantly</u></a></li>
<li><a href="https://tech-hub.techidaily.com/quick-fix-for-a-malfunctioning-logitech-k520-keyboard-easy-tips-inside/"><u>Quick Fix for a Malfunctioning Logitech K520 Keyboard – Easy Tips Inside!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/quick-fix-for-removing-windows-10-lock-screen-a-user-friendly-approach/"><u>Quick Fix for Removing Windows 10 Lock Screen - A User-Friendly Approach</u></a></li>
<li><a href="https://tech-hub.techidaily.com/quick-guide-identifying-and-verifying-your-windows-10-os-version-instantly/"><u>Quick Guide: Identifying and Verifying Your Windows 10 OS Version Instantly</u></a></li>
<li><a href="https://tech-hub.techidaily.com/recovering-access-steps-to-restore-a-forgotten-ipad-passcode-and-unlock-securely/"><u>Recovering Access: Steps to Restore a Forgotten iPad Passcode and Unlock Securely</u></a></li>
<li><a href="https://tech-hub.techidaily.com/resolve-excessive-tiworkerexe-cpu-and-memory-consumption-in-windows-11/"><u>Resolve Excessive tiworker.exe CPU and Memory Consumption in Windows 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1723808155320-skype-cant-connect-5-ways-to-fix-on-windows-10-easily/"><u>Skype Can't Connect: 5 Ways to Fix on Windows 10 Easily</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/sound-sculpting-on-android-the-7-ultimate-audio-editing-apps/"><u>Sound Sculpting on Android  The 7 Ultimate Audio Editing Apps</u></a></li>
<li><a href="https://tech-hub.techidaily.com/speed-hacks-supercharge-minecraft-gameplay/"><u>Speed Hacks - Supercharge Minecraft Gameplay!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/step-by-step-guide-efficiently-clearing-your-entire-google-search-log/"><u>Step-by-Step Guide: Efficiently Clearing Your Entire Google Search Log</u></a></li>
<li><a href="https://tech-hub.techidaily.com/step-by-step-guide-executing-the-admin-version-of-command-prompt-on-a-windows-pc/"><u>Step-by-Step Guide: Executing the Admin Version of Command Prompt on a Windows PC</u></a></li>
<li><a href="https://tech-hub.techidaily.com/step-by-step-tutorial-for-backing-up-drivers-before-refreshing-or-replacing-windows-operating-systems-windows-11-7-8-etc/"><u>Step-by-Step Tutorial for Backing Up Drivers Before Refreshing or Replacing Windows Operating Systems (Windows 11, 7, 8, Etc.)</u></a></li>
<li><a href="https://tech-hub.techidaily.com/step-by-step-tutorial-for-driver-backup-on-windows-1110-systems/"><u>Step-by-Step Tutorial for Driver Backup on Windows 11/10 Systems</u></a></li>
<li><a href="https://buynow-help.techidaily.com/the-top-non-firetv-gaming-consoles/"><u>The Top Non-FireTV Gaming Consoles</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-ultimate-choice-of-chrome-vpns-and-quick-installation-tips/"><u>The Ultimate Choice of Chrome VPNs & Quick Installation Tips</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1723808168062-trouble-with-your-logitech-clicker-heres-how-you-can-make-it-work-again/"><u>Trouble with Your Logitech Clicker? Here's How You Can Make It Work Again</u></a></li>
<li><a href="https://tech-hub.techidaily.com/troubleshooting-full-screen-grayscale-on-windows-11-solution/"><u>Troubleshooting Full-Screen Grayscale on Windows 11 (Solution)</u></a></li>
<li><a href="https://tech-hub.techidaily.com/troubleshooting-guide-ensuring-your-usb-drives-work-with-windows-11/"><u>Troubleshooting Guide: Ensuring Your USB Drives Work with Windows 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/troubleshooting-non-sleep-functionality-in-windows-11-systems/"><u>Troubleshooting Non-Sleep Functionality in Windows 11 Systems</u></a></li>
<li><a href="https://tech-hub.techidaily.com/troubleshooting-tips-how-to-easily-leave-safe-mode-on-your-windows-11-pc/"><u>Troubleshooting Tips: How to Easily Leave Safe Mode on Your Windows 11 PC</u></a></li>
<li><a href="https://tech-hub.techidaily.com/turbulent-flow-is-characterized-by-chaotic-fluid-motion-and-occurs-at-reynolds-numbers-greater-than-approximately-4000-for-pipe-flows/"><u>Turbulent Flow Is Characterized by Chaotic Fluid Motion and Occurs at Reynolds Numbers Greater than Approximately 4000 for Pipe Flows.</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ultimate-guide-capturing-screen-images-on-windows-7-8-and-10/"><u>Ultimate Guide: Capturing Screen Images on Windows 7, 8 & 10</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ultimate-guide-step-by-step-process-to-flush-browser-and-system-cache-in-windows-10/"><u>Ultimate Guide: Step-by-Step Process to Flush Browser and System Cache in Windows 10</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ultimate-list-of-top-game-torrent-websites-find-the-latest-releases/"><u>Ultimate List of Top Game Torrent Websites – Find the Latest Releases!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlock-the-secrets-of-pc-maintenance-how-to-conduct-a-hard-reboot-and-restore-performance-on-windows-10/"><u>Unlock the Secrets of PC Maintenance: How to Conduct a Hard Reboot and Restore Performance on Windows 10</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlock-the-secrets-of-windows-11s-task-manager-easy-tutorial/"><u>Unlock the Secrets of Windows 11'S Task Manager - Easy Tutorial</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1723807952921-voice-recorder-windows-10-how-to-use-it-and-fix-issues-with-it/"><u>Voice Recorder Windows 10 — How to Use It & Fix Issues with It?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/vpn-for-mac-how-to-setup-vpn-on-mac-quickly-and-easily/"><u>VPN for Mac | How to Setup VPN on Mac | Quickly & Easily</u></a></li>
<li><a href="https://tech-hub.techidaily.com/what-is-rundll32exe-comprehensive-guide-for-protection-and-management/"><u>What Is rundll32.exe? Comprehensive Guide for Protection & Management</u></a></li>
<li><a href="https://tech-hub.techidaily.com/windows-10-time-wrong-issue-solved/"><u>Windows 10 Time Wrong Issue [Solved]</u></a></li>
</ul></div>
