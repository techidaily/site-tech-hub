---
title: Understanding GPTZero's Function in AI Detection
date: 2024-08-09T19:49:40.439Z
updated: 2024-08-10T19:49:40.439Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Understanding GPTZero's Function in AI Detection
excerpt: This Article Describes Understanding GPTZero's Function in AI Detection
thumbnail: https://thmb.techidaily.com/0a7e98a47c507ce4d17e40879eab668bc44ad83b05fd8fefcba56a2f27460108.jpg
---

## Understanding Word and Character Quotas in AI-Powered Chatbots Like GPT-3

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
### Key Takeaways

* ChatGPT responses are not limitless in length, despite the initial claim. There are hidden limits determined by the token system, past conversations, and system demands.
* The token system used by ChatGPT considers both the length of queries and answers. The available token lengths vary depending on the GPT model used.
* To get longer responses from ChatGPT, you can ask it to continue, break your question into smaller sections, use the regenerate option, specify a word count limit, or start a new conversation. These techniques can help you work around the unofficial limits and receive more complete answers.

 ChatGPT is big news. But how big are the responses you get from this all-purpose chatbot?

 Establishing this is not as simple as you may think. For starters, ask ChatGPT this question, and you will be assured that there are no set limits to the length of its responses.

 However, as we uncover here, it isn't that straightforward. There are hidden limits to the length of a ChatGPT response, but there are also some nifty and simple workarounds to help you get longer answers.

## How Does ChatGPT Determine the Length of a Response?

[How ChatGPT works is complex](https://www.makeuseof.com/how-does-chatgpt-work/) , and the response length varies depending on what is being asked and the level of detail requested. As the next screenshot shows, ChatGPT claims there are no strict limits.

![Screenshot of ChatGPT Declaring No Limits](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-chatgpt-declaring-no-limits.jpg)

 Of course, asking ChatGPT about itself isn't a good idea since it isn't typically objective about its abilities or has limited information. So, we ran some tests to determine the length limits of ChatGPT responses. We asked the chatbot to write a 5000-word article on the history of the FIFA World Cup. ChatGPT's assessment of itself differed from the results we found.

![Asking ChatGPT to write 5000 words article](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/asking-chatgpt-to-write-5000-words-article.jpg)

 ChatGPT is a powerful tool. But maybe 5,000 words was asking a bit too much, so I asked for 2,500 words instead.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Asking ChatGPT to write 2500 words article](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/asking-chatgpt-to-write-2500-words-article.jpg)

 ChatGPT still said it wasn't able to fulfill the request. We worked down to 1,000 words before the chatbot produced the article. But there was another problem: no matter how many times we tried, ChatGPT couldn't produce 1,000 words on the subject. But why? What's limiting the chatbot's ability to produce longer replies?

 Part of the answer as to why this happens lies in something called the token system.

### What Is the Token System ChatGPT Uses?

 When you ask ChatGPT a question, the length of the replies it can provide depends on a token system. Rather than a simple word count to determine the length of both queries and answers, ChatGPT uses this system. Notice something? The length of both "queries and answers" is taken into consideration. The token system breaks down each input and output into a series of tokens to classify the request and response size.

 While word count does play a part in this, it isn't the whole story. For instance, the example below was entered into[OpenAI's Tokenizer tool](https://platform.openai.com/tokenizer) .

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Screenshot of ChatGPT Tokenizer tool test](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-chatgpt-tokenizer-tool-test.jpg)

 The sentence "How many words have I typed" and answer "6" were "tokenized" to a value of nine tokens. This is consistent with OpenAI's "rule of thumb" that one token is equivalent to around three-quarters of a word.

 Here's where things get a little bit tricky. OpenAI's GPT models come in varying token lengths. The standard GPT-4 model that comes with your ChatGPT Plus subscription offers anywhere between 4k and 8k token context length. OpenAI also provides an extended 32k token context length GPT-4 model. The GPT-3.5 series offers even more token variety. There are 4k, 8k, and 16k GPT-3.5 models. However, not all these models are publicly available.

 We used the base GPT-3.5 and supposed GPT-4 8k models for this test. We say "supposed" because the 8k tag didn't check out when we ran a context window test. And then there's the fact that there's no confirmation from official sources that the GPT-4 model at chat.openai.com is an 8k model.

 The base GPT 3.5 4k model is supposed to restrict user questions and replies to 4,097 tokens. Similarly, the GPT-4 8k model is supposed to deliver 8,192 tokens. By OpenAI's reckoning, this equates to about 3,000 words for the GPT-3.5 and around 5,000 to 6,000 words for the GPT-4 8k tokens. But wait a minute. With an approximate 3,000 to 6,000 words capacity on either model, why wasn't ChatGPT able to deliver a 2,500-word or even 1,500-word article when we requested? Why are ChatGPT responses much less than their advertised token count or context length?

## Why Are ChatGPT's Responses Limited?

 While token length looks straightforward and good in theory, there's more to how AI models consider these limits. There are two notable considerations.

1. **Past Conversations** : Because ChatGPT is a conversational chatbot, whenever you ask a question, the chatbot considers older conversations to stay consistent and ensure natural-sounding interactions. This means in longer conversations, older prompts and responses are invariably considered as part of the context window and end up eating your token length. So, it is not just the immediate question and replies that is considered in the context window calculation.
2. **System Demand** :[ChatGPT has quickly become one of the fastest-growing apps of all time](https://www.makeuseof.com/how-chatgpt-became-fastest-growing-app/) . This has generated a huge demand for ChatGPT. To ensure everyone gets a piece of the action, 8k tokens might not always be 8k. Remember, the more tokens to process, the more demand on the system. To lessen the average demand from each user, responses are curtailed to far below the stated limits.

 To stress, this is not a fixed rule—we generated outputs that exceeded this by almost two hundred words. However, this can be considered a safe upper limit to achieve complete answers.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
## How to Get Longer Responses From ChatGPT

 Once you understand that there is a "hidden limit" to ChatGPT's responses, there are some simple ways to help you get more complete responses.

1. **Ask ChatGPT to Continue:** If ChatGPT stops partway through an answer, then one option is to simply ask it to continue. In the example below, we typed "Go on," and it added another two hundred words to the response.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
![Screenshot of ChatGPT being prompted to continue](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-chatgpt-being-prompted-to-continue.jpg)
2. **Break your question into smaller sections:** For instance, we asked it several times to write an essay on the impact of AI on society. One option here is to ask it to bullet-point some topics for an essay on AI, then use the supplied bullet points as individual prompts.  
![Screenshot of ChatGPT response to AI Bullet points](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-chatgpt-response-to-ai-bullet-points.jpg)
3. **Use the Regenerate option:** While this might throw up the same error, with nothing to lose, it is always worth a shot.
4. **Specify an upper limit to your word count in your prompt:** The image below illustrates how this can be used to manipulate the maximum word count in an answer.  
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Screenshot of using a word limit for ChatGPT response](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-using-a-word-limit-for-chatgpt-response.jpg)
5. **Start a new conversation** : starting a new conversation gives you a clean slate to work with. Remember, ChatGPT considers past prompts and responses in a conversation. Starting a new chat gives you unused context to work with.

 These tips will help you to get more complete answers from ChatGPT and work around the unofficial limit in the length of its responses.

## ChatGPT: Quality Over Quantity

 While there is no official information on the maximum length of ChatGPT responses, in practice, there are hidden constraints. The token system, influenced by past conversations and system demand, all impact how long ChatGPT's answers can be. However, by asking ChatGPT to continue, breaking questions into parts, regenerating responses, specifying word counts, and starting new chats, you can often get more complete, longer replies. Though not perfect, being aware of these unofficial limits and using the right techniques can help you get the most out of this powerful AI chatbot.


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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-insta-reversal-unlock-the-power-of-video-rotation/"><u>[New] 2024 Approved  Insta-Reversal  Unlock the Power of Video Rotation</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-elevate-mobile-streaming-with-obs-studio-android-edition/"><u>[New] Elevate Mobile Streaming with OBS Studio Android Edition</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-premium-cut-tools-the-top-8-linux-apps/"><u>[New] Premium Cut Tools  The Top 8 Linux Apps</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-snagit-screen-recorder-review-and-alternatives-for-2024/"><u>[New] Snagit Screen Recorder Review and Alternatives for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-game-masters-top-ten-female-gaming-influencers/"><u>[Updated] 2024 Approved  Game Masters  Top Ten Female Gaming Influencers</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-the-dynamic-world-of-digital-gifts-a-complete-guide-to-snapchat-gifs/"><u>[Updated] 2024 Approved  The Dynamic World of Digital Gifts  A Complete Guide to Snapchat Gifs</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-streaming-wars-whos-leading-vimeo-or-popular-online-platforms/"><u>[Updated] Streaming Wars  Who's Leading – Vimeo or Popular Online Platforms?</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-art-of-visual-excellence-leveraging-enhancer-22/"><u>[Updated] The Art of Visual Excellence - Leveraging Enhancer 2.2</u></a></li>
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
<li><a href="https://extra-tips.techidaily.com/discovering-budget-friendly-framed-imagery/"><u>Discovering Budget-Friendly Framed Imagery</u></a></li>
<li><a href="https://extra-resources.techidaily.com/harmony-hunters-dive-into-free-online-beat-tracker/"><u>Harmony Hunters  Dive Into Free, Online Beat Tracker</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/hdr-tech-showdown-sns-vs-alternatives/"><u>HDR Tech Showdown  SNS vs Alternatives</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-audio-ambition-realized-cutting-edge-recording-methods-for-minecraft-players/"><u>In 2024, Audio Ambition Realized  Cutting-Edge Recording Methods for Minecraft Players</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-oppo-find-x7-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Oppo Find X7 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-excellent-20-anime-opening-anthems/"><u>In 2024, Excellent 20 Anime Opening Anthems</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-guffaw-guide-the-leading-text-generator-companions/"><u>In 2024, Guffaw Guide  The Leading Text Generator Companions</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-quick-tips-for-effective-android-video-chatting/"><u>In 2024, Quick Tips for Effective Android Video Chatting</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-unlock-the-potential-of-your-podcast-covers-now/"><u>In 2024, Unlock the Potential of Your Podcast Covers Now</u></a></li>
<li><a href="https://some-techniques.techidaily.com/innovative-tools-top-cell-phones-for-creatives-for-2024/"><u>Innovative Tools  Top Cell Phones for Creatives for 2024</u></a></li>
<li><a href="https://buynow-help.techidaily.com/mastering-performance-why-the-alienware-aurora-r11-is-your-best-bet-in-gaming-pcs-of-2021/"><u>Mastering Performance: Why the Alienware Aurora R11 Is Your Best Bet in Gaming PCs of 2021</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/navigating-home-weather-solutions-expert-picks-for-the-best-in-24/"><u>Navigating Home Weather Solutions: Expert Picks for The Best in '24</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-honor-magic-5-lite-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Honor Magic 5 Lite? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/podcast-sharing-instagram-stories-and-posts-tutorial-for-2024/"><u>Podcast Sharing  Instagram Stories & Posts Tutorial for 2024</u></a></li>
<li><a href="https://driver-download.techidaily.com/simple-steps-installing-the-wacom-intuos-pro-drivers-on-windows-11/"><u>Simple Steps: Installing the Wacom Intuos Pro Drivers on Windows 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/start-immediately-with-these-8-bespoke-gpt-applications-for-enhanced-productivity/"><u>Start Immediately with These 8 Bespoke GPT Applications for Enhanced Productivity</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/techniques-to-increase-instagram-content-playback-speed/"><u>Techniques to Increase Instagram Content Playback Speed</u></a></li>
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
<li><a href="https://buynow-help.techidaily.com/which-is-better-an-iphone-or-a-samsung-phone-an-in-depth-comparison/"><u>Which Is Better, an iPhone or a Samsung Phone?: An In-Depth Comparison</u></a></li>
</ul></div>
