---
title: "Boost Your Linux Productivity: Swap Out Basic Commands for High-Performance Counterparts"
date: 2024-08-29T01:11:23.398Z
updated: 2024-08-30T01:11:23.398Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/00ca8ff6fce624dea66e7545a63f888233e8bb4b7d797baaa5f46d28ff2d3756.jpg
---

## Boost Your Linux Productivity: Swap Out Basic Commands for High-Performance Counterparts

### Key Takeaways

* bat command enhances cat with syntax highlighting, Git integration, and easier page navigation. Use it like cat with bat filename.
* ncdu is user-friendly for disk space analysis compared to du. Navigate the list easily and delete unnecessary files with ncdu commands.
* eza offers a stylish alternative to ls, providing colored files and hyperlink support. Install eza with cargo and use it like ls for file listing.

 As someone looking to get things done quickly and easily, I'm always on the lookout for new Linux tools. There are many handy Linux commands which seem better than the regular commands you're using. In this guide, I'm sharing some of my favorites.

## 1  bat: cat With Syntax Highlighting 

![Using the bat command to display a text file on Linux.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/using-the-bat-command-to-display-a-text-file-on-linux.png) 

[The cat command](https://facebook-record-videos.techidaily.com/techniques-to-achieve-crystal-clear-youtube-soundtracks-for-2024/) on Linux is commonly used to display text content from a file on the terminal. [The bat command](https://github.com/sharkdp/bat) is an enhanced version of cat that supports syntax highlighting, Git integration, and automatic paging. It also shows non-printing characters more clearly than cat.

 To install bat on Debian, Ubuntu, and their derivatives, run:

sudo apt install bat

 Install bat on Fedora with this command:

sudo dnf install bat

 On Arch Linux, run:

sudo pacman -S bat

 Install it on openSUSE running:

sudo zypper install bat

 After installing bat, you simply use it like cat—pass a file name to display its content, like this:

bat file1

 If you installed bat on Debian/Ubuntu using the APT package manager, you'd have to use batcat instead of bat to avoid conflict with another package called bat. So, in that case, run:

batcat file1

 You can use [Bash aliases](https://hardware-help.techidaily.com/download-the-latest-logitech-camera-drivers-at-no-cost-for-windows-users/) to map batcat to bat or even cat if you like. With the bat command, you can change the themes used to display text on the terminal. The --list-themes flag lets you check all the themes. To change to another theme, you use the --theme=theme\_name option. Suppose you want to use the Dracula theme, you use the below command to use it:

batcat --theme=Dracula file1

 If you want to set a theme permanently, you can [set an environment variable](https://media-tips.techidaily.com/effortless-format-transformation-how-to-seamlessly-switch-from-mpeg-4-to-mpeg/) in your .bashrc file. You can also add new themes and syntax definitions to bat.

## 2  ncdu: More User-Friendly Than du 

 The [ncdu (NCurses Disk Usage) command](https://dev.yorhel.nl/ncdu) is a great tool for analyzing your disk space. The traditional du command provides disk usage that's hard to parse. The ncdu command makes it easier to see what's eating up your space.

 To install ncdu on Debian, Ubuntu, and their derivatives, run:

sudo apt install ncdu

 Install ncdu on Fedora with this command:

sudo dnf install ncdu

 On Arch Linux, run:

sudo pacman -S ncdu

 Install it on openSUSE by running:

sudo zypper install ncdu

 If you want to analyze the disk space usage of the current directory, run:

ncdu

![Using the ncdu command to analyze the disk space of the current directory.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/using-the-ncdu-command-to-analyze-the-disk-space-of-the-current-directory.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
 To analyze a specific directory, add that directory path as an argument. For example, if you want to analyze the snap directory, run this command:

ncfu /snap

 Likewise, for a full disk analysis, run:

ncdu /

![Full disk analysis using the ncdu command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/full-disk-analysis-using-the-ncdu-command.png) 

 Once the scanning is done, you'll get an overview of the files and directories in a list structure with their sizes in descending order. You can navigate the list using the arrow buttons, press i to see more information about specific files, and press -d to delete them. If you want to analyze the disk space only of your internal drive and skip any connected storages, run:

ncdu -d /

 When you're done with the analysis, press q to return to the command line.

## 3  eza: Beautiful Alternative to ls 

 eza makes file listing much more useful and cool-looking than [the ls command](https://extra-tips.techidaily.com/in-2024-capturecraft-hd-top-10-freepaid-filters-list/). It offers many intuitive features, such as colored files, hyperlink support, and better readability.

 The easiest way to install eza is by using the cargo package manager, which comes with the Rust development environment. First, install and set up Rust with these commands:

curl https://sh.rustup.rs -sSf | sh

source $HOME/.cargo/env

 If you don't have [curl](https://bypass-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-xiaomi-mix-fold-3-frp-locks-by-drfone-android/) installed, you'll need to install that first. You'll also need the build-essential package before running the next command.

 Then install eza with this command:

cargo install eza

 You can use eza just like ls, without any parameters.

eza

 You can list the items with full details and icons as well. Your system needs to support the icons.

eza -lh --icons

![Using the eza command to list files and directories in the terminal with full details.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/using-the-eza-command-to-list-files-and-directories-in-the-terminal-with-full-details.png) 

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4  fd: Fast and Friendly find 

 The [fd command](https://github.com/sharkdp/fd) isn't a direct replacement for the find command. However, you can perform most of find's functionalities with it. fd has a more intuitive syntax than find and supports regular expressions.

 To install fd on Ubuntu and its derivatives, run:

sudo apt install fd-find

 Install it on Debian with:

sudo apt-get install fd-find

 Install fd on Fedora with this command:

sudo dnf install fd-find

 On Arch Linux, run:

sudo pacman -S fd

 Install it on openSUSE by running:

sudo zypper in fd

 On some distros such as Ubuntu, the command you need to run is **fdfind** instead of **fd** 

 A simple run of the command **fdfind** will return the content of the current directory, like this:

fdfind

![Running the fd command shows the content of the current directory.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/running-the-fd-command-shows-the-content-of-the-current-directory.png) 

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The most basic way to use the fd command is by passing a pattern as an argument. Suppose, you want to search for files that contain the string "file", then you need to pass that as an argument.

fdfind file

![Using the fdfind command to search files using a string.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/using-the-fdfind-command-to-search-files-using-a-string.png) 

 If you want to search in a specific directory, you can pass that directory path as an argument, like this:

fdfind file /folder1

![Using the fdfind command to search files using a string in a specific directory.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/using-the-fdfind-command-to-search-files-using-a-string-in-a-specific-directory.png) 

 Another useful way of using fd is to find files by its extension. For example, if I want to search for bash scripts, I'll search for files with the ".sh" extension. The command for that is:

fdfind -e sh

![Using the fdfind command to search files by extensions.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/using-the-fdfind-command-to-search-files-by-extensions.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
 If you want to learn more, check out our [full fd command guide](https://visual-screen-recording.techidaily.com/updated-2024-approved-unmatched-hdds-for-enhanced-xbox-experience/).

## 5  ripgrep: grep, but Faster 

[ripgrep](https://github.com/BurntSushi/ripgrep/tree/master) is a command-line search tool for recursively searching string patterns in multiple files in the current directory. It offers a better user experience than grep and [is faster in many instances](https://blog.burntsushi.net/ripgrep/). If you're a developer, you can use ripgrep to search for patterns in a codebase.

 To install ripgrep on Debian, Ubuntu, and their derivatives, run:

sudo apt-get install ripgrep

 Install ripgrep on Fedora with this command:

sudo dnf install ripgrep

 On Arch Linux, run:

sudo pacman -S ripgrep

 Install it on openSUSE by running:

sudo zypper install ripgrep

 To demonstrate ripgrep, I've made some demo directories and files containing text. If you already have a codebase or multiple files, then you can use it there. The command for ripgrep is rg. To search inside a single file, you pass the search string inside double quotes and the file name as arguments.

rg "README" README.md

![Using the ripgrep tool to search a string in a single file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/using-the-ripgrep-tool-to-search-a-string-in-a-single-file.png) 

 To search all files in a directory, pass that directory as an argument instead of the file name.

rg "is" demo_project

![Using the ripgrep tool to search a string in a directory](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/using-the-ripgrep-tool-to-search-a-string-in-a-directory.png) 

 If you want to search in a specific type of file, you need to use the --type flag and pass that file extension, like this:

rg "Python" demo_project --type py

![Using the ripgrep tool to search a string in specific file type](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/using-the-ripgrep-tool-to-search-a-string-in-specific-file-type.png) 

 If you have hidden files, directories, ripgrep ignores them while searching.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
## 6  zoxide: Smarter Than cd 

 cd is one of the most [basic Linux commands](https://win11-tips.techidaily.com/precision-adjusting-windows-locksleep-timer/). It's used for navigating through the file system on the terminal. [zoxide](https://github.com/ajeetdsouza/zoxide?tab=readme-ov-file) makes navigating much easier by remembering your most visited directories. You can install zoxide on any Linux distro using the provided installation script. Run this command:

curl -sSfL https://raw.githubusercontent.com/ajeetdsouza/zoxide/main/install.sh | sh

 If you don't have [curl](https://bypass-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-xiaomi-mix-fold-3-frp-locks-by-drfone-android/) installed, you'll need to install that first.

 You can also use the package manager of your distro if you prefer that. Next, you need to initialize it. The command depends on which shell you're using. For Bash, it's this:

echo 'eval "$(zoxide init bash)"' >> ~/.bashrc

    
                    source ~/.bashrc

 Let's take a look at a quick example of how zoxide is better than cd. Suppose you need to navigate into a directory deep inside the system. With zoxide, you do it like this:

z demo1/demo2/demo3/demo4/

![Navigating the Linux file system using zoxide.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/navigating-the-linux-file-system-using-zoxide.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
 Once you do that, zoxide will remember it for the future. You won't have to type the whole directory path and instead write the one you need to enter last.

![An example of faster file system navigation with zoxide.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/an-example-of-faster-file-system-navigation-with-zoxide.png) 

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If there are multiple directories with the same name, you'll see a list of directories, and you can choose from there. For that, you'll need the fzf tool as well.

## 7  btop: More Interactive Than top 

 If you find it hard and boring to use [the top command](https://snapchat-videos.techidaily.com/new-2024-approved-the-new-age-of-entertainment-tiktok-vs-snap-in-the-spotlight/) to [monitor your system](https://program-issues.techidaily.com/quick-solutions-resolving-winwordexe-software-malfunctions/), then btop is a great alternative. With full mouse support and gamified looks, it offers a better user experience.

 To install btop, first download the suitable binary from [the releases page](https://github.com/aristocratos/btop/releases). Then go to the directory where you downloaded the file. Run these commands:

        `tar -xjf btop-x86_64-linux-musl.tbz # The file name should match the one you downloaded  
cd btop/  
./install.sh`
    
![The process of installing btop on Linux.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/installing-btop-on-linux.png) 

 After installing, run:

btop

![An example of btop running on Linux.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/running-btop-on-linux.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
 You can monitor disk usage, RAM usage, battery life, network, processes, and more.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8  tldr: The Simplified Version of man 

 When you're new to Linux and you want to learn more about a command, you're often asked to use [the man command](https://video-capture.techidaily.com/in-2024-masterclass-flawless-powerpoint-screen-recordings/). However, as a beginner, it may seem confusing and intimidating. That's where [the tldr command](https://tldr.sh/) comes in. It simplifies manual pages and provides practical use cases of the command.

 The recommended way to install tldr is using npm, which requires [Node.JS](https://win-dash.techidaily.com/download-latest-sound-card-drivers-compatible-with-windows-os/) installed. Once done, install tldr with this command:

npm install -g tldr

 Pick a command name and pass it as ar argument to see how tldr displays its details. Here's an example for the [rm](https://instagram-video-recordings.techidaily.com/new-avoiding-instagrams-false-facade-for-a-solid-stature/) command:

tldr rm

![Using the tldr command to display the manual page of the rm command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/using-the-tldr-command-to-display-the-manual-page-of-the-rm-command.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## 9  sd: Easier Syntax Than sed 

 The sd command supports commonly used [Regex](https://extra-lessons.techidaily.com/top-10-after-effects-text-presets/) syntax, unlike [the sed command](https://visual-screen-recording.techidaily.com/new-in-2024-forward-thinking-ios-for-ps2-emulation/). It also has a string-literal mode, making it much easier to use. You can install sd using cargo.

cargo install sd

 Let's see how sd is different from sed. I have a file where I'd like to replace 'quick brown fox' with 'swift red fox'. The command for that is as below in both cases:

sed -i 's/quick brown fox/swift red fox/g' paragraph.txt

    
                    sd 'quick brown fox' 'swift red fox' paragraph.txt

![Using the sed command to replace text in a txt file.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/using-the-sed-command-to-replace-text-in-a-txt-file.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 There are many more advanced uses of sd where you can apply complicated search patterns.

---

 While some of these commands can't fully replace the good old ones, they can come in handy in many cases. If you'd like to learn more [important Linux commands](https://buynow-help.techidaily.com/misinterpretation-of-gram-staining-results-can-lead-to-incorrect-identification-affecting-treatment-decisions-in-clinical-settings/), check out our guide for that.

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


