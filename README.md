# Prezto Theme - prompt.iam.setup

![Screenshot](http://i.imgur.com/C3hgY1l.jpg)

I recently made the jump from BASH to ZSH ([this helped me get started](http://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/)), and settled on [Prezto](https://github.com/sorin-ionescu/prezto) as my configuration framework. I worked my way through every theme I could find, but none of them did *exactly* what I wanted. So I started fiddling around, and cobbled together my favorite bits of functionality from the different themes I came across. 

Despite being a theme for [Oh-My-ZSH](https://github.com/robbyrussell/oh-my-zsh), I ended up using [itg.zsh-theme](https://github.com/itsthatguy/itg.zsh-theme) as my starting point. I was really intrigued by the GitHub status display, and wanted to try and replicate something similar using [Prezto](https://github.com/sorin-ionescu/prezto)'s Git module. Still working on that. 

I pulled a few pieces from Steve Losh's [Extravagent ZSH Prompt](http://stevelosh.com/blog/2010/02/my-extravagant-zsh-prompt/), namely the right-prompt battery status. 


## Installation

To install the themes, copy the prompt_iam_setup file into your ~/.zprezto/modules/prompt/functions folder. 

To install the battery status script, place the file in your ~/bin/ (make sure it's in your path), and you'll be good to go. 
