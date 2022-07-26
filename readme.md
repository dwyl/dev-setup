<div align="center">

# A Guide to Setting Up Your Dev Environment

![tianyi-ma-WiONHd_zYI4-unsplash](https://user-images.githubusercontent.com/194400/180770906-938c8083-28fb-4c03-872f-3a636376f15f.jpg)

[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat-square)](https://github.com/dwyl/dev-setup/issues)
[![HitCount](https://hits.dwyl.com/dwyl/dev-setup.svg?style=flat-square)](http://hits.dwyl.com/dwyl/dev-setup)


</div>

- [A Guide to Setting Up Your Dev Environment](#a-guide-to-setting-up-your-dev-environment)
- [Why? 🤷‍♀️](#why-️)
- [What?](#what)
- [Who?](#who)
  - [Why?](#why)
- [How?](#how)
  - [Web Browsers](#web-browsers)
  - [Text Editor](#text-editor)
  - [Git + GitHub](#git--github)
  - [Git and GitHub](#git-and-github)
    - [Basic Git setup](#basic-git-setup)
    - [Learn how to use Git + GitHub](#learn-how-to-use-git--github)
- [Mac](#mac)
  - [Rectangle](#rectangle)
    - [Keyboard Shortcuts](#keyboard-shortcuts)
  - [Homebrew](#homebrew)
  - [`iTerm`](#iterm)
    - [Themes](#themes)
  - [Text Editor](#text-editor-1)
    - [Basic text editor setup](#basic-text-editor-setup)
  - [How to connect Github to Atom step-by-step](#how-to-connect-github-to-atom-step-by-step)
    - [Our most used text editor keyboard shortcuts](#our-most-used-text-editor-keyboard-shortcuts)
    - [Why ?](#why-)
    - [What ?](#what-)
    - [Spectacle Installation](#spectacle-installation)
    - [Spectacle Shortcuts](#spectacle-shortcuts)


# Why? 🤷‍♀️

Setting up a software development computer can take a _long_ time. ⏳ <br />
We need to streamline the process
so that we can start work as quickly as possible. 🏁<br />
This doc outlines all the steps we take to setup 
our typical system. 💻

If you find it helpful,
please 
[⭐](https://github.com/dwyl/dev-setup/stargazers) 
the repo
to let us know.
Thanks.


# What?

This repo contains the tools we use.

Please open issues and pull requests to include anything you think is relevant.

> _Note:_ The intention is **not** to include every fancy script, 
tip and trick under the sun, 
this is about **basic setup and getting going when you're new** 
and already have a _steep_ learning curve!

If you have a tool or setup step
you think we should include/use,
[please open an issue](https://github.com/dwyl/dev-setup/issues)
to let us know! 🙏

# Who?

1. People who are new to coding.    
Particularly people who have learnt online 
using inbuilt browser-based editors and tools 
(often the case in online courses) 
and have **not set up their own environment** before.

## Why?

When we were learning software engineering, 
it took us some time, 
talking to more experienced engineers 
and trying things out to 
**pick up on all the small things that make us more effective**.   
We wanted there to be a single place where new developers could go to find these quickly so they can **get past the setup and down to the business of coding**.


> **Note**: @dwyl we use a specific 
[technology stack](https://github.com/dwyl/technology-stack)
that includes 
[PostgreSQL]() and 
[Elixir]()

**Installing** software [is optional](https://github.com/dwyl/dev-setup/issues/3),
but it does make you more effective so we highly recommend it.  
This repo includes some recommendations of things we favour and use @dwyl._

# How? 

Ensure you have a decent internet connection 
when setting up your machine,
several **gigabytes** will be downloaded.

> **Note**: if you don't have a good internet connection,
> simply skip downloading the browser(s) and other larger Apps.
> But we are _assuming_ that if you are reading this,
> you have _access_ to decent bandwidth to be a Developer/Engineer.
> Please, share your experience if not!
> We are very curious to hear from bandwidth-constrained people! 🙏
> We would like to formulate a "Low Cost / Bandwidth" version 
> of this doc for use on a Raspberry Pi or other lower cost computer.
> We could even create a pre-built SD card with everything required. 💭

## Web Browsers

The reason the word "browsers" is _plural_ is simple:
having _multiple_ browsers lets you use each one for a specific purpose.
e.g:

1. Safari - the default browser on Mac. 
   Keep it "stock" (no plugins/themes), 
   use it for UAT testing web apps 
   to know what they will look & feel like 
   to people who own Macs 
   but don't bother to download another browser.
   Safari is good for personal things too as it has good privacy and speed.
2. Google Chrome - The baseline for web development.




## Text Editor

There are a wide range of text editors 
and integrated devlopment environment (IDEs)
available.

We tend to use:

+ [ ] Atom: 
+ [ ] 
+ [ ] VSCodium https://vscodium.com the Open Source version of VS Code. All Plugins work as expected
but no Tracking from Microsoft.
+ [ ] VS Code: https://code.visualstudio.com as a backup or read-only viewer when we are working on multiple projects concurently.

The reason 


## Git + GitHub

If you don't _already_ have a GitHub account,
sign up for one: 
[github.com/join](https://github.com/join)

  + [ ] Enable 2 Factor Authentication
  ([2FA](https://help.github.com/en/github/authenticating-to-github/about-two-factor-authentication))
  for Github to further protect not only your own account but also any organisations
   that you're a part of from malicious intent
  ![setup-2factor-auth](https://user-images.githubusercontent.com/4185328/79356313-b16e9f80-7f36-11ea-8645-d0ee1ea36853.png)
  + [ ] [Set it up on your computer](#basic-git-setup)
  + [ ] Learn to use Git particularly [on the command line](git-in-the-terminal)
+ [ ] Make sure you're comfortable with your [terminal setup](http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1)

**Next steps?** If you want to [contribute to dwyl projects](https://github.com/dwyl/contributing), get comfortable with [our stack](https://github.com/dwyl/technology-stack) and **open issues whenever you have questions**!

## Git and GitHub

We use Git and 
[Github](https://en.wikipedia.org/wiki/GitHub) 
exclusively for our version control 
and to share our work with the world.   
Understanding the 
[difference between the two](https://www.codefellows.org/blog/git-and-github-what-s-the-difference) 
is also helpful :blush:

### Basic Git setup   
+ Sign up for a [Github account](https://github.com/join)
+ **[Set up Git](https://help.github.com/articles/set-up-git/) on your computer**
  + We recommend you [**authenticate with SSH**](https://help.github.com/articles/set-up-git/#connecting-over-ssh) as this is more secure and means you _won't have to type in your password every time you push to GitHub_
  + _Note:_ This also means that when you _clone_ a repo, you'll need to use the **SSH clone URL** (thanks [@tsop14](https://github.com/tsop14) for the screenshot!)

  ![change-to-ssh](https://user-images.githubusercontent.com/21698271/45860770-00daf280-bd37-11e8-92f8-34bb1ddf8152.png)

### Learn how to use Git + GitHub
+ There are many resources online, [here are a few we like](https://github.com/dwyl/start-here#git--github)
<a name="git-in-the-terminal"/>
+ Although [Git has a desktop client](https://desktop.github.com/) we **recommend that you learn to use it on the command line** - this is _much_ faster in the long run and will serve you well as a developer


# Mac

This section is specific to Mac computers.
Skip it if you are using Linux or 
[Windows](https://www.google.com/search?q=stop+hitting+yourself&tbm=isch).

## Rectangle

[Rectangle](https://rectangleapp.com/) 
is window manager/tiler for Mac,
it gives you keyboard shortcuts for moving/organising your Apps/Windows: 
[rectangleapp.com](https://rectangleapp.com/)

<img width="1115" alt="image" src="https://user-images.githubusercontent.com/194400/180993778-01d42389-9d9c-497c-a469-968e220ec3c7.png">

> **Note**: Rectangle will request/require 
> "accessibility" permissions to control your windows.
> This is normal.

### Keyboard Shortcuts


<img width="884" alt="image" src="https://user-images.githubusercontent.com/194400/180995347-d7838081-9a84-49c6-b45c-0f251e44c719.png">



## Homebrew

If you are seting up a Mac,
you will need to install homebrew 
[brew.sh](https://brew.sh),
the package manager that will download and manage
several other open source software packages.

Install with the following command in your terminal:

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## `iTerm`

The default terminal emulator on Mac is _OK_...
We find that 
[**`iTerm`**](http://www.iterm2.com/) 
is _considerably_ better UX.
e.g: **`iTerm`** allows screen splitting:

![iterm-screen-splitting](https://cloud.githubusercontent.com/assets/4185328/9831158/56d8cb90-5943-11e5-99ec-9fb1a5907f8a.png)

As with Web Browsers, 
it doesn't _hurt_ to have more than one Terminal 
on your Mac. 

Download: https://iterm2.com

### Themes

There are _many_ themes 
which you may have heard of 
(like [Oh My Zsh](http://ohmyz.sh/)) 
that aim to add some functionality 
and shortcuts to your terminal. 
**We _don't_ recommend** 
you use any terminal themes 
when you're starting out
because they are a _distraction_
from the content/code you are crafting.

However, once you know what you're doing in the terminal, 
you can consider _enhancing_ your terminal with themes.
There are _many_ to chose from:
[iterm2colorschemes.com](https://iterm2colorschemes.com/)


## Text Editor

It's entirely up to you which text editor you use, but you will inevitably need one.    
At the time of writing, at _dwyl_ we use [Atom editor](https://atom.io/) (open source, NodeJS based editor) though we work with a lot of people who use [Sublime Text](http://www.sublimetext.com/) (and have used this ourselves in the past).

### Basic text editor setup

**Set up** [**_soft tabs_**](https://opensourcehacker.com/2012/05/13/never-use-hard-tabs/) (indentation) <br />
You can usually set this up in the _Preferences_ or _Settings_ 
of your favourite text editor 
so you never have to think about it again 
(example below for [Atom](https://atom.io/)): 

<img width="507" alt="atom-soft-tab-preferences-menu" src="https://cloud.githubusercontent.com/assets/4185328/9154618/a6598690-3e91-11e5-939b-2c03cf3c7ffc.png">     


+ **Set up a guide (or line) to show on your page at the 80 character mark** so you know [when you go past 80 characters (or columns) on a single line](http://programmers.stackexchange.com/questions/604/is-the-80-character-limit-still-relevant-in-times-of-widescreen-monitors)
  + Useful for _readability_, particularly in code snippets where you would otherwise end up with a scroll bar
  + You should also be able to set this up in your favourite text editor's _Preferences_ (example below again on Atom editor - note, I also like to set up my editor to soft wrap at this line length so I can read other people's code more easily)    
  <img width="511" alt="80-character-line-guide-setup" src="https://cloud.githubusercontent.com/assets/4185328/9826015/45796748-58cf-11e5-8a5d-db7350a8eb82.png">

## How to connect Github to Atom step-by-step

First of all you need to create a Github Account and then create a new repository, name it as you wish.</br>

Now you have a link to your repository and instructions to how to create a new repository in the command line.</br>
Now go to Atom and press cmd+SHIFT+P and you enter Github:clone and then paste your link.

![Screen Shot 2020-01-12 at 22 41 04](https://user-images.githubusercontent.com/27420533/72227070-45277d00-3590-11ea-90f9-6e78998bf30e.png)

A couple a seconds later you have your repository on the left side of the screen.</br>

![Screen Shot 2020-01-12 at 22 42 59](https://user-images.githubusercontent.com/27420533/72227087-638d7880-3590-11ea-920e-643b8433d193.png)


The next thing to do is authorize Github for atom so go to github.atom.io/login.</br>
Just make the login with your information and copy the GitHub token after having your GitHub token copied go to Atom to the GitHub tab in the right lower corner and you will see a login just paste your token there and now you are connected to GitHub.</br>

So now if you create a file and edit with your own text you can upload the file to GitHub by going to the git tab and Stage the changes in your file you have to give a commit message the first time you edit the file.
Then click on Commit to master.


![Screen Shot 2020-01-12 at 23 21 55](https://user-images.githubusercontent.com/27420533/72227281-86209100-3592-11ea-96a2-06ba543fa6a6.png)


Now click on master and then on new branch and call it whatever you want then click on publish.
You will have to enter your credentials again to validate those changes.

![Screen Shot 2020-01-12 at 23 24 13](https://user-images.githubusercontent.com/27420533/72227295-bc5e1080-3592-11ea-95e3-524c86a80757.png)


If you go on your created repository and press F5 you should see those changes.   



+ **Install at least a basic [linter](http://stackoverflow.com/questions/8503559/what-is-linting)** to your editor

### Our most used text editor keyboard shortcuts  
Each person's most used shortcuts will vary of course, but here are some of the things we suggest **learn the keyboard shortcuts for:**
  + Select the current word (usually `cmd + D`)
  + Delete current line (usually `ctrl + shift + K`)
  + Indenting a line or a whole block of code at once
  + [Column editing](https://atom.io/docs/v1.0.11/using-atom-editing-and-deleting-text#multiple-cursors-and-selections)
  + [Moving a line](https://atom.io/docs/v1.0.11/using-atom-editing-and-deleting-text#basic-manipulation) or block of code up and down the page
  + Changing the [syntax highlighting](https://en.wikipedia.org/wiki/Syntax_highlighting) when required
  + Toggle between the different views (e.g. hide/show the file tree view to gain more screen real estate)

### Why ?


So a lot of you may have lots of open windows at once.
   You got code running and then you got the documentation for the code and you got Google stuff opened.
  And then "Stack overflow" to search for errors or doubts.
  Everything becomes a mess and a nightmare with so many pages open.
  The simplest way to organize everything is to use the spectacle.

### What ?

   Spectacle is simply an app that helps you managing your windows.
   Lets you modify whatever you want to do to your windows.
   Keyboard shortcuts are the fastest way to communicate with your computer.
   If you want to be super fast and efficient "You need to learn how to use Spectacle".
   Once you learn some of the shortcuts you will just need to use your "Muscle Memory" to use them.

_Note:_ Spectacle is only for Mac in alternative for windows you have AquaSnap that works the same way.

### Spectacle Installation

First of all access the website :https://www.spectacleapp.com/

![Screen Shot 2020-01-08 at 09 45 50](https://user-images.githubusercontent.com/27420533/71968207-596c2280-31fc-11ea-849c-abff957b4980.png)


After Clicking on 'Download Spectacle' you just need to add to your applications folder.

### Spectacle Shortcuts


![Spectacle](https://i.postimg.cc/sXpXX5Qw/Screen-Shot-2020-01-07-at-09-44-10.png)

You can "Always" edit your own shortcuts going to preferences and click on the shortcut you want to change.

![Spectacle](https://i.postimg.cc/c1tHryYr/Screen-Shot-2020-01-07-at-09-54-22.png)
