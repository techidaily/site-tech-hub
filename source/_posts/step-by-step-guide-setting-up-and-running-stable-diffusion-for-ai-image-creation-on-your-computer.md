---
title: "Step-by-Step Guide: Setting Up and Running Stable Diffusion for AI Image Creation on Your Computer"
date: 2024-08-28 18:45:16
updated: 2024-08-29 11:54:43
tags:
  - cutting-edge
categories:
  - tech
thumbnail: https://thmb.techidaily.com/8e8fd391ef433874750ab325d9bce417e7f1e76eddd6075f48e66d463a68738d.jpg
---

## Step-by-Step Guide: Setting Up and Running Stable Diffusion for AI Image Creation on Your Computer

###### [Read update](https://screen-capture.techidaily.com/investing-in-the-right-keyboard-for-low-cost-maximum-output-for-2024/) 

* Prefer a graphical interface? Try [our guide to running Stable Diffusion with a GUI on your PC](https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-tecno-spark-go-2023-phone-by-drfone-android/).

### Quick Links

* [What Is Stable Diffusion?](https://twitter-videos.techidaily.com/updated-2024-approved-transforming-tweets-into-animated-gifs-a-step-by-step-guide/)
* [What Do You Need to Run Stable Diffusion on Your PC?](https://bypass-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-tecno-frp-android-10111213-by-drfone-android/)
* [How to Install and Run Stable Diffusion on Windows](https://easy-unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-motorola-moto-g04-phone-by-drfone-android/)
* [How to Use Stable Diffusion](https://android-transfer.techidaily.com/in-2024-how-i-transferred-messages-from-oppo-reno-11-5g-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/)

### Key Takeaways

 To run Stable Diffusion locally on your PC, download Stable Diffusion from GitHub and the latest checkpoints from HuggingFace.co, and install them. Then run Stable Diffusion in a special python environment using Miniconda.

 Artificial Intelligence (AI) art is currently all the rage, but most AI image generators run in the cloud. Stable Diffusion is different --- [you can run it on your very own PC](https://extra-information.techidaily.com/5-highest-rated-vr-gear-for-uavs-for-2024/) and generate as many images as you want. Here's how you can install and use Stable Diffusion on Windows.

##  What Is Stable Diffusion?

[Stable Diffusion is an open-source machine learning model](https://extra-information.techidaily.com/5-highest-rated-vr-gear-for-uavs-for-2024/) that can generate images from text, modify images based on text, or fill in details on low-resolution or low-detail images. It has been trained on billions of images and can produce results that are comparable to the ones you'd get from DALL-E 2 and [MidJourney](https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-motorola-moto-g73-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/). It's developed by [Stability AI](https://stability.ai/) and was first [publicly released](https://stability.ai/blog/stable-diffusion-public-release) on August 22, 2022.

Related: [How to Create Synthetic AI Art With Midjourney](https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-motorola-moto-g73-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/) 

 Stable Diffusion doesn't have a tidy user interface (yet) like some AI image generators, but it has an extremely permissive license, and --- best of all --- it is completely free to use on your own PC (or Mac.)

###  UPDATE: 9/16/22

 Prefer a graphical interface? Try [our guide to running Stable Diffusion with a GUI on your PC](https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-tecno-spark-go-2023-phone-by-drfone-android/).

Related: [How to Run Stable Diffusion Locally With a GUI on Windows](https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-tecno-spark-go-2023-phone-by-drfone-android/) 

 Don't be intimidated by the fact that Stable Diffusion currently runs in a command-line interface (CLI). Getting it up and running is pretty straight-forward. If you can double-click an executable and type in a box, you can have it running in a few minutes.

##  What Do You Need to Run Stable Diffusion on Your PC?

 Stable Diffusion won't run on your phone, or most laptops, but it will run on the average gaming PC in 2022\. Here are the requirements:

* A GPU with at least 6 gigabytes (GB) of [VRAM](https://extra-support.techidaily.com/new-premium-selection-of-apple-and-android-camera-slow-motion-apps/)  
   * This includes most modern NVIDIA GPUs
* 10GB (ish) of storage space on your [hard drive](https://instagram-videos.techidaily.com/new-in-2024-dominate-social-media-sales-5-strategic-moves-for-instagram-experts/) or [solid-state drive](https://some-approaches.techidaily.com/updated-the-gradual-glide-out-technique-for-audio-in-adobe-premiere-pro/)
* [The Miniconda3 installer](https://docs.conda.io/en/latest/miniconda.html)
* [The Stable Diffusion files from GitHub](https://github.com/CompVis/stable-diffusion)
* The Latest Checkpoints (Version 1.4, as of the time of writing, but 1.5 should be released soon)
* [The Git Installer](https://git-scm.com/download/win)
* Windows 8, 10, or 11  
   * Stable Diffusion can also be run on Linux and macOS

Related: [The Best AI Image Generators You Can Use Right Now](https://fox-info.techidaily.com/new-synthesize-stellar-titles-using-ai-insights/) 

 If you don't have the hardware, consider [using a web-based AI image generator](https://fox-info.techidaily.com/new-synthesize-stellar-titles-using-ai-insights/). You can even run [a demo of Stable Diffusion](https://huggingface.co/spaces/stabilityai/stable-diffusion) on the web.

##  How to Install and Run Stable Diffusion on Windows

 There are two pieces of software you need: Git and Miniconda3.

 Git and Miniconda3 are both safe programs produced by reputable organizations. You don't need to worry about malware with them provided that you download them from the official sources linked in this article.

###  Installing Git

[Git](https://git-scm.com/download/win) is a tool that allows developers to manage different versions of the software they're developing. They can maintain multiple versions of the software they're working on in a central repository simultaneously and allow other developers to contribute to the project.

Related: [How to Install Git on Windows](https://techtrends.techidaily.com/ultimate-guide-to-popular-samsung-smart-tv-apps-of-2024/) 

 If you're not a developer, [Git](https://git-scm.com/download/win) provides a convenient way to access and download these projects, and that's how we'll use it in this case. [Download the Windows x64 installer](https://git-scm.com/download/win) from the Git website, then run it to [install Git](https://techtrends.techidaily.com/ultimate-guide-to-popular-samsung-smart-tv-apps-of-2024/).

 There are several options you'll be prompted to select while the installer runs --- leave them on their default settings. One option page, "Adjusting Your PATH Environment," is particularly important. It must be set to "Git From The Command Line And Also From 3rd-Party Software."

![Make sure that &quot;Git From The Command Line And Also From 3rd-Party Software&quot; is selected.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/git-install-option.png) 

###  Installing Miniconda3

 Stable Diffusion draws on a few different [Python libraries](https://youtube-data.techidaily.com/024-approved-conveniently-connect-with-others-via-your-playlist/). If you don't know much about Python, don't worry too about this --- suffice it to say, the libraries are just software packages that your computer can use to perform specific functions, like transform an image, or do complex math.

Related: [What Is Python?](https://youtube-data.techidaily.com/024-approved-conveniently-connect-with-others-via-your-playlist/) 

 Miniconda3 is basically a convenience tool. It lets you download, install, and manage all of the libraries required for Stable Diffusion to function without very much manual intervention. It'll also be how we actually use Stable Diffusion.

 Head over to [the Miniconda3 download page](https://docs.conda.io/en/latest/miniconda.html) and click "Miniconda3 Windows 64-bit" to get the latest installer.

![Click &quot;Miniconda3 Windows 64-bit&quot; to start the download.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/miniconda3-64-bit.png) 

 Double-click the executable once it has downloaded to start the installation. Miniconda3's installation involves less clicking through pages than Git did, but you need to watch out for this option:

![Tick the box that says &quot;All Users.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/all-users.png) 

 Make sure that you select "All Users" before clicking next and finishing up the installation.

 You'll be prompted to restart your computer after installing Git and Miniconda3\. We didn't find it to be necessary, but it won't hurt if you do.

###  Download the Stable Diffusion GitHub Repository and the Latest Checkpoint

 Now that we've installed the pre-requisite software, we're ready to download and install Stable Diffusion.

[Download the latest checkpoint](https://huggingface.co/CompVis/stable-diffusion#model-access) first --- version 1.4 is nearly 5GB, so it might take a while. You need to create an account to download the checkpoint, but they only require a name and email address. Everything else is optional.

 At the time of writing (September 2, 2022), the latest checkpoint is version 1.4\. If there is a newer version, download that instead.

![Click &quot;Stable-diffusion-v-1-4-original,&quot; or whatever the current highest version is.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/model-access.png) 

 Click "sd-v1-4.ckpt" to start the download.

 The other file, "sd-v1-4-full-ema.ckpt", might provide better results, but it is about twice the size. You can use either.

![Click &quot;sd-v1-4.ckpt&quot; to start the download.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/click-sd-v1-4.png) 

 You then need to [download Stable Diffusion](https://github.com/CompVis/stable-diffusion) from GitHub. Click on the green "Code" button, then click "Download ZIP." Alternatively, you can use [this direct download link](https://github.com/CompVis/stable-diffusion/archive/refs/heads/main.zip).

![Click the green &quot;Code&quot; button, then click &quot;Download ZIP.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/click-code-click-download-ZIP.png) 

 Now we need to prepare a few folders where we'll unpack all of Stable Diffusion's files. Click the Start button and type "miniconda3" into the Start Menu search bar, then click "Open" or hit Enter.

![Type &quot;miniconda3&quot; into the Start Menu search, then click &quot;Open.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/start-click-open.png) 

 We're going to create a folder named "stable-diffusion" using the command line. Copy and paste the code block below into the Miniconda3 window, then press Enter.

        `cd C:/mkdir stable-diffusioncd stable-diffusion`
    
 Almost any time you paste a block of code into a terminal, like Miniconda3, you need to hit Enter at the end to run the last command.

 If everything went well, you'll see something like this:

![Minoconda3 terminal showing commands executing successfully.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/create-stable-diffusion.png) 

 Keep the Miniconda3 window open, we'll need it again in a minute.

 Open up the ZIP file, "stable-diffusion-main.zip," that you downloaded from GitHub in your[favourite file archiving program](https://android-location.techidaily.com/easy-ways-to-manage-your-huawei-nova-y91-location-settings-drfone-by-drfone-virtual/). Alternatively, Windows can also open ZIP files by itself if you don't have one. Keep the ZIP file open in one window, then open another [File Explorer](https://facebook-video-content.techidaily.com/updated-in-2024-facebook-media-extractor-quick-mp3-downloads/) window and navigate to the "C:\\stable-diffusion" folder we just made.

Related: [Get Help With File Explorer on Windows 10](https://facebook-video-content.techidaily.com/updated-in-2024-facebook-media-extractor-quick-mp3-downloads/) 

 Drag and drop the folder in the ZIP file, "stable-diffusion-main," into the "stable-diffusion" folder.

![Drag and drop the contents of the ZIP file into the stable-diffusion folder.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/drag-and-drop-the-files-1.png) 

 Go back to Miniconda3, then copy and paste the following commands into the window:

        `cd C:\stable-diffusion\stable-diffusion-main  
conda env create -f environment.yaml  
conda activate ldmm  
kdir models\ldm\stable-diffusion-v1`
    
![Wait for the download to finish.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/conda-prompt.png) 

 Don't interrupt this process. Some of the files are larger than a gigabyte, so it could take a bit to download. If you do interrupt the process accidentally, you'll need to delete the environment folder and run `conda env create -f environment.yaml` again. If that happens, navigate to "C:\\Users\\(Your User Account)\\.conda\\envs" and delete the "ldm" folder, then run the previous command.

`So, what did we just do? Python lets you sort coding projects into "Environments." Each environment is separate from other environments, so you can load different Python libraries into different environments without having to worry about conflicting versions. It is invaluable if you're working on multiple projects on one PC.`

``

``

``

` The lines we ran created a new environment named "ldm," downloaded and installed [all of the necessary Python libraries for Stable Diffusion to work](https://github.com/CompVis/stable-diffusion/blob/main/environment.yaml), activated the ldm environment, then [changed the directory](https://extra-information.techidaily.com/quick-and-easy-iphone-burst-techniques/) to a new folder.` 

`We're on the last step of the installation. Navigate to "C:\stable-diffusion\stable-diffusion-main\models\ldm\stable-diffusion-v1" in File Explorer, then copy and paste the checkpoint file (sd-v1-4.ckpt) into the folder.`

`![Copy the model file into the stable-diffuse-v1 folder.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/copy-and-paste.png) 

`

` Wait for the file to finish transferring, right-click "sd-v1-4.ckpt" and then click "Rename." Type "model.ckpt" into the highlighted box, then hit Enter to change the file name.` 

`[If you're running Windows 11, you won't see "rename" in the right-click context menu](https://video-screen-grab.techidaily.com/updated-how-to-facetime-on-android-easily/). There is an icon that looks like a miniature text field instead.` 

`Related: [Windows 11's Tiny Context Menu Buttons Will Confuse People](https://video-screen-grab.techidaily.com/updated-how-to-facetime-on-android-easily/) `

`![Rename the model file &quot;model.ckpt&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/model-name.png) 

`

` And that's it --- we're done. We are ready to actually use Stable Diffusion now. ` 

## `How to Use Stable Diffusion` 

``  The ldm environment we created is essential, and you need to activate it any time you want to use Stable Diffusion. Enter `conda activate ldm` into the Miniconda3 window and hit "Enter." The (ldm) on the left-hand side indicates that the ldm environment is active. `` 

`You only need to enter that command when you open Miniconda3. The ldm environment will remain active as long as you do not close the window.` 

``

`![Activate the ldm environment.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/activate-thing.png) 

`

``  Then we need to change the directory (thus the command`cd`) to "C:\stable-diffusion\stable-diffusion-main" before we can generate any images. Paste `cd C:\stable-diffusion\stable-diffusion-main` into command line.  `` 

### `How to Make an Image with Stable Diffusion` 

` We're going to call a script, txt2img.py, that allows us to convert text prompts into 512x512 images. Here is an example. Try this out to make sure everything is working correctly: ` 

        `python scripts/txt2img.py --prompt "a close-up portrait of a cat by pablo picasso, vivid, abstract art, colorful, vibrant" --plms --n_iter 5 --n_samples 1`
    
` Your console will give you a progress indicator as it produces the pictures.`

`![Stable Diffusion generating images.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/console-producing-results.png) 

 That command will produce five cat images, all located at "C:\stable-diffusion\stable-diffusion-main\outputs\txt2img-samples\samples".

![A cat in the style of Pablo Picasso.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/gato.png) 

 It isn't perfect, but it distinctly resembles the style of Pablo Picasso, just like we specified in the prompt. Your images should look similar but not necessarily identical.

`

``  Any time you want to change what image is generated you just need to change the text contained in the double-quotation marks following `--prompt`. `` 

`Don't rewrite the entire line every time. Use the arrow keys to move the text cursor around and just replace the prompt.` 

`` 

        `python scripts/txt2img.py --prompt "<strong>YOUR, DESCRIPTIONS, GO, HERE</strong>" --plms --n_iter 5 --n_samples 1`
    
 Say we wanted to generate a realistic looking gopher in a magical forest wearing a wizard's hat. We could try the command:

        `python scripts/txt2img.py --prompt "a photograph of a gopher wearing a wizard hat in a forest, vivid, photorealistic, magical, fantasy, 8K UHD, photography" --plms --n_iter 5 --n_samples 1`
    
![A gopher with a purple wizard hat.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/gopher.png) 

 It really is that easy --- just describe what you want as specifically as you can. If you want something photorealistic, make sure to include terms relating to a realistic image. If you want something inspired by the style of a specific artist, specify the artist.

 Stable Diffusion isn't limited to portraits and animals either, it can also produce striking landscapes.

![A calm lake with mountains around it, and a dramatic sky.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/00042.png) 

###  What Do the Arguments in the Command Mean?

 Stable Diffusion has an enormous number of settings and arguments that you can provide to customize your results. The few included here are basically necessary to ensure Stable Diffusion will run on an average gaming computer.

* \--plms --- Specifies how the images will be sampled. [There is a paper about it, if you want to check out the math](https://doi.org/10.48550/arXiv.2202.09778).
* \--n\_iter --- specifies the number of iterations you want to generate for each prompt. 5 is a decent number to see what kind of results you're getting.
* \--n\_samples --- specifies the number of samples that will be generated. The default is 3, but most computers do not have enough VRAM to support that. Stick with 1 unless you have a specific reason to change it.

 Of course, Stable Diffusion has a ton of different arguments that you can implement to tweak your results. Run

        `python scripts/txt2img.py --help`
    
 to get an exhaustive list of arguments that you can use.

 There is a ton of trial and error involved in getting great results, but that is at least half of the fun. Make sure you write down or save arguments and descriptions that return results you like. If you don't want to do all of the experimenting yourself, there are growing [communities on Reddit](https://www.reddit.com/r/StableDiffusion/) (and elsewhere) dedicated to exchanging pictures and the prompts that generated them.

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
