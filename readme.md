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
- [How?](#how)
  - [Web Browsers](#web-browsers)
  - [Git + GitHub](#git--github)
    - [2 Factor Authentication (2FA)](#2-factor-authentication-2fa)
    - [Basic Git setup](#basic-git-setup)
    - [Learn how to use Git + GitHub](#learn-how-to-use-git--github)
- [Mac 🍏](#mac-)
  - [PostgresApp](#postgresapp)
  - [PGAdmin](#pgadmin)
  - [Rectangle](#rectangle)
    - [Keyboard Shortcuts](#keyboard-shortcuts)
  - [Homebrew](#homebrew)
  - [`iTerm`](#iterm)
    - [Themes](#themes)
- [Linux 🐧](#linux-)
- [_Everyone_](#everyone)
  - [Text Editor](#text-editor)
    - [Basic text editor setup](#basic-text-editor-setup)
  - [How to connect Github to Atom step-by-step](#how-to-connect-github-to-atom-step-by-step)
    - [Our most used text editor keyboard shortcuts](#our-most-used-text-editor-keyboard-shortcuts)


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

1. People who are **`new`** to software engineering.    
Particularly people who have learnt online 
using inbuilt browser-based editors and tools 
(often the case in online courses) 
and have **not set up their own environment** before.



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
having _multiple_ web browsers 
allows you to segment your use of each one
for a specific purpose.
e.g:

1. Safari - the default browser on Mac. 
   Keep it "stock" (no plugins/themes), 
   use it for UAT testing web apps 
   to know what they will look & feel like 
   to people who own Macs 
   but don't bother to download a different browser.
   Safari is good for personal things too as it has good privacy and speed.
2. Google Chrome: 
   [google.com/chrome](https://www.google.com/chrome/)
   The baseline for web development. Great Dev Tools, profiling etc.
3. Firefox: 
   [mozilla.org/firefox](https://www.mozilla.org/en-US/firefox/new/)
   We use Firefox for testing our Web apps because
   it has the best support for Web Standards.
   It's fast, free and surfaces potential bugs 
   in our code better than other browsers.

In addition to these 
there are _many_ other browsers you can install/use,
for example:

4. Brave: 
   [brave.com/download](https://brave.com/download/)
   Based on Chrome but with built-in ad-blocker.
   Use brave to watch YouTube lectures/tutorials without Ads.
5. Google Chrome Canary: 
   [google.com/chrome/canary/](https://www.google.com/chrome/canary/)
   Chrome but with all latest features.
6. Firefox Developer Edition: 
   [mozilla.org/firefox/developer/](https://www.mozilla.org/en-US/firefox/developer/)
   Useful for debugging and testing web apps.
   We have it installed as a backup browser
   for when we need to test multiple clients concurrently.
7. Microsoft Edge: 
   [microsoft.com/edge](https://www.microsoft.com/en-us/edge)
   Based on Google Chrome but with a few enhancements.

As noted in
[#9](https://github.com/dwyl/dev-setup/issues/9#issuecomment-1193409980)
we have several web browsers installed and use them for specific purposes:

<img width="475" alt="image" src="https://user-images.githubusercontent.com/194400/180669042-91cd806d-2a3b-488a-b9cd-1ca0e8d8f20d.png">

Given that Microsoft now owns GitHub
and can read _everything_ we do on the platform
(_both `public` and `private`..._)
we use **`Edge`** for all our GitHub
interactions (e.g. reading notifications, responding to issues/questions, etc.)
That we know **`Edge`** is our "GitHub browser".

You are free to come up with your own system,
but having multiple browsers and segmenting your use
can mean you have fewer tabs in your "work" browser
and can easily separate any personal stuff.


## Git + GitHub

We use Git and 
[Github](https://en.wikipedia.org/wiki/GitHub) 
exclusively for our version control 
and to share our work with the world.   
Understanding the 
[difference between the two](https://www.codefellows.org/blog/git-and-github-what-s-the-difference) 
is also helpful.

If you don't _already_ have a GitHub account,
sign up for one: 
[github.com/join](https://github.com/join)

### 2 Factor Authentication (2FA)

[2FA](https://help.github.com/en/github/authenticating-to-github/about-two-factor-authentication)
protects your Github account
and also any organisations you are member of
from malicious intent.

![setup-2factor-auth](https://user-images.githubusercontent.com/4185328/79356313-b16e9f80-7f36-11ea-8645-d0ee1ea36853.png)

+ [ ] Learn to use Git particularly [on the command line](git-in-the-terminal)
+ [ ] Make sure you're comfortable with your [terminal setup](http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1)

**Next steps?** If you want to 
[contribute to dwyl projects](https://github.com/dwyl/contributing), 
you can easily do so _without_
knowing _any_ of our  
[tech stack](https://github.com/dwyl/technology-stack).
Simply use the 
[App](https://github.com/dwyl/app)
and **open issues whenever you have questions**!


### Basic Git setup   

Follow the official 
[**set up Git guide**](https://help.github.com/articles/set-up-git/)
to get it working on your computer.

Setup 
[**ssh authentication**](https://help.github.com/articles/set-up-git/#connecting-over-ssh) 
as it is more secure 
and means you _won't have to type in your password 
every time you push to GitHub.

> **Note**: This also means that when you _clone_ a repo, 
> you'll need to use the **SSH clone URL** 
> (thanks [@tsop14](https://github.com/tsop14) for the screenshot!)

![change-to-ssh](https://user-images.githubusercontent.com/21698271/45860770-00daf280-bd37-11e8-92f8-34bb1ddf8152.png)

### Learn how to use Git + GitHub

There are many resources online:
[start-here#git](https://github.com/dwyl/start-here#git--github)

Although [Git has a desktop client](https://desktop.github.com/), 
we **recommend that you learn to use it on the command line**. 
This is _much_ faster in the long run and will serve you well
when you need to understand how things work.


# Mac 🍏

This section is _specific_ to Mac computers.
Skip it if you are using Linux or 
[Windows](https://www.google.com/search?q=stop+hitting+yourself&tbm=isch).

## PostgresApp 

We find PostgresApp to be the easiest way 
to manage PostgreSQL on Mac.
It gives us a basic graphical user interface (GUI)
and menu bar icon that informs us of the status of the DB.

Download: https://postgresapp.com/

## PGAdmin

Postgres 
https://www.pgadmin.org/


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

Using Rectangle is fastest via the keyboard shortcuts:

<img width="884" alt="image" src="https://user-images.githubusercontent.com/194400/180995347-d7838081-9a84-49c6-b45c-0f251e44c719.png">

You can add your own shortcuts if you prefer.
We haven't found the need to yet.


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

<br />

# Linux 🐧

At present several members of our team/community 
use a Linux distro as their primary operating system. 

If this is _you_,
please help: 
[dev-setup/issues/49](https://github.com/dwyl/dev-setup/issues/49)



<br />

# _Everyone_

The following applies to all people 
regardless of their operating system
(Linux, Mac & Windows)

## Text Editor

It's your choice which text editor you use, 
but you will inevitably need (at least) one editor.
At the time of writing, 
`@dwyl` we use 
[Atom](https://atom.io/) 
(Open Source, Electron/NodeJS based editor).

There are a wide range of text editors 
and integrated devlopment environment (IDEs)
available.

We tend to use:

+ Atom: https://atom.io Open Source and has many plugins for language and framework support.
  Download and install it even if you only use it as a "backup" editor.
  VSCodium https://vscodium.com the Open Source version of VS Code. All Plugins work as expected
but no Tracking from Microsoft.
+ VS Code: https://code.visualstudio.com as a backup or read-only viewer when we are working on multiple projects concurently.
+ Sublime Text: [sublimetext.com](http://www.sublimetext.com) - fast and free-ish 
  (you will be reminded to purchase a license ... but the license is perpetual not annual!)
+ [WebStorm](https://www.jetbrains.com/webstorm/buy/#personal) - we hear good things about WebStorm.
  


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


Install at least a [linter](http://stackoverflow.com/questions/8503559/what-is-linting) in your editor.

### Our most used text editor keyboard shortcuts  
Each person's most used shortcuts will vary of course, but here are some of the things we suggest **learn the keyboard shortcuts for:**
  + Select the current word (usually `cmd + D`)
  + Delete current line (usually `ctrl + shift + K`)
  + Indenting a line or a whole block of code at once
  + [Column editing](https://atom.io/docs/v1.0.11/using-atom-editing-and-deleting-text#multiple-cursors-and-selections)
  + [Moving a line](https://atom.io/docs/v1.0.11/using-atom-editing-and-deleting-text#basic-manipulation) or block of code up and down the page
  + Changing the [syntax highlighting](https://en.wikipedia.org/wiki/Syntax_highlighting) when required
  + Toggle between the different views (e.g. hide/show the file tree view to gain more screen real estate)