# A Guide to setting up your developer environment

## Why?
When we were teaching ourselves how to code it took us some time, talking to more experienced developers and trying things out to **pick up on all the small things that make our lives easier as developers**.   
We wanted there to be a single place where new developers could go to find these quickly so they can **get past the setup and down to the business of coding**.

_Note: @dwyl we use full stack Javascript.
This also includes some recommendations of things we personally favour of course!_

Reference: https://github.com/dwyl/start-here/issues/53

## Checklist
+ [ ] Sign up for a [Github account](https://github.com/join) and [learn how to use it](http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1)
+ [ ] Get yourself a [text editor](#text-editor)
  + [ ] Do some [basic setup](#basic-text-editor-setup) to make your life a little easier
  + [ ] Learn a handful of the [most useful keyboard shortcuts](text-editor-keyboard-shortcuts)

## Text Editor
It's entirely up to you which text editor you use, but you will inevitably need one.    
At the time of writing, at _dwyl_ we use [Atom editor](https://atom.io/) (open source, NodeJS based editor) though we work with a lot of people who use [Sublime Text](http://www.sublimetext.com/) (and have used this ourselves in the past).

### Basic text editor setup
+ ** Set up [_soft tabs_](https://opensourcehacker.com/2012/05/13/never-use-hard-tabs/)** (indentation)
  + You can usually set this up in the _Preferences_ or _Settings_ of your favourite text editor so you never have to think about it again (example below on [Atom editor](https://atom.io/))    
<img width="507" alt="atom-soft-tab-preferences-menu" src="https://cloud.githubusercontent.com/assets/4185328/9154618/a6598690-3e91-11e5-939b-2c03cf3c7ffc.png">     


+ **Set up a guide (or line) to show on your page at the 80 character mark** so you know [when you go past 80 characters (or columns) on a single line](http://programmers.stackexchange.com/questions/604/is-the-80-character-limit-still-relevant-in-times-of-widescreen-monitors)
  + Useful for _readability_, particularly in code snippets where you would otherwise end up with a scroll bar
  + You should also be able to set this up in your favourite text editor's _Preferences_ (example below again on Atom editor - note, I also like to set up my editor to soft wrap at this line length so I can read other people's code more easily)
  <img width="511" alt="80-character-line-guide-setup" src="https://cloud.githubusercontent.com/assets/4185328/9826015/45796748-58cf-11e5-8a5d-db7350a8eb82.png">


+ **Install at least a basic [linter](http://stackoverflow.com/questions/8503559/what-is-linting)** to your editor
  
### Most used text editor keyboard shortcuts  
**Learn the keyboard shortcuts for:** 
  + Select the current word (usually `cmd + D`)
  + Delete current line
  + Indenting a line or a whole block of code at once
  + [Column editing](https://atom.io/docs/v1.0.11/using-atom-editing-and-deleting-text#multiple-cursors-and-selections) 
  + [Moving a line](https://atom.io/docs/v1.0.11/using-atom-editing-and-deleting-text#basic-manipulation) or block of code up and down the page
  + Changing the [syntax highlighting](https://en.wikipedia.org/wiki/Syntax_highlighting) when required
  + Toggle between the different views (e.g. hide/show the file tree view to gain more screen real estate)