# Coyotiv &nbsp;<img src="https://avatars2.githubusercontent.com/u/63822051?s=200&v=4" alt="coyotiv-logo" width="30"/>

- [Welcome](#welcome)
- [Chrome](#chrome)
- [Slack](#slack)
- [Visual Studio Code](#visual-studio-code)
- [Terminal](#terminal)
- [Git and Github](#git-and-github)
- [Node.js](#nodejs)
- [Problem Solving](#problem-solving)
- [Course Material](#course-material)
- [Lifetime Learning](#lifetime-learning)

## Welcome

First of all, welcome to Coyotiv Community! 
TODO: Here comes more information about us, our aim - maybe code of conduct link.
TODO: another title for diversity, scholarships, website links. blog link etc etc. quick link to slack ?


We would like to share tools we work with.

## Chrome

[Chrome](https://www.google.com/chrome/) will be the browser of choice, due to its complete developer integrated tools. Make sure that you have the latest version installed on your computer.

## Slack

[Slack](https://slack.com/intl/en-de/) is the messaging tool that we use to communicate during the course:  [macOS Download](https://slack.com/intl/en-de/downloads/mac) | [Windows download](https://slack.com/intl/en-de/downloads/windows).

Important :speaker:: Get your personal invite to our Coyotiv Community slack workspace by typing your email [here](coyotiv-community.slack.com).

On our `#general` channel you will be able to ask questions, get support and share the link of your code so we can review it and give you feedback. If you cannot see it on the left menu of the slack app under **Channels**, you can search for it after clicking on the title.

## Visual Studio Code

[Visual Studio Code](https://code.visualstudio.com/) is the IDE (Integrated Development Environment) we will use during the course. In simpler words, is the tool that we'll use to write code.

[Live Share Extension Pack](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack) is an extension for VS Code that enables real-time collaboration between developers. We will use this extension to code together. We will share a session for coding with a shared debugging and running consoles. Anyone can take control and type code, others can follow their cursor. Note that this extension pack also provides audio and text chat on top of Visual Studio Live Share.

## Terminal

**Terminal**, also known as command line or console, allows us to accomplish and automate tasks on a computer without the use of a GUI or [graphical user interface](https://www.computerhope.com/jargon/g/gui.htm). Even if many tasks can be done by interacting with the GUI (for example deleting or creating folders), there are some actions which are easier and faster to perform through the terminal, especially when working with Git (which we explore in our next point).

On the course we will mainly use the [integrated Terminal in Visual Studio Code](https://code.visualstudio.com/docs/editor/integrated-terminal), but it is basically the same as the one you can find on your computer (macOS). We recommend you to have a basic understanding of how it works. You can take a look to this complete and fun-to-read [guide](https://medium.com/@grace.m.nolan/terminal-for-beginners-e492ba10902a).

**Windows users**: We will mostly be using the integrated terminal of Visual Studio Code. Depending on your Windows version, this will be either `powershell` or `cmd.exe`. Some commands will be a little different to those on macOS and Linux, but you can find helpful info in [this guide](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/).
If you *really* want to use a [bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell)) Terminal (the default macOS and Linux one), you can follow the instructions referenced in the [guide](https://medium.com/@grace.m.nolan/terminal-for-beginners-e492ba10902a) above to enable one.

## Git and Github

[Git](https://git-scm.com/) is a version control system, which allows us to understand the history of a file and how it has progressed (a well-known example would be the Revision History of Google Drive documents).

[Github](https://github.com/) is the tool we use to share and upload our projects. You will need a Github account and a basic knowledge of how to use it.

We recommend you to go through [this guide](https://towardsdatascience.com/getting-started-with-git-and-github-6fcd0f2d4ac6) or [this other one](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners) to learn how to work with both of them. They are a bit long but very complete, and you will get a good understanding on how to use them from scratch. This is important because we will ask you to upload your homeworks on your Github account and share the link with us so we can review it easily.

:raising_hand: Feel free to check our [short intro](https://www.youtube.com/watch?v=NHwiSlz4Bi4&list=PLNBb8OktVDKvAbiQIeQqSo0YFYtn3wLAI&index=2&t=4s) for start getting familiarized with Git.

Now is time to prove your git learnings playing a little! :point_right: [https://learngitbranching.js.org/](https://learngitbranching.js.org/)

## Node.js

Node.js is an open-source, cross-platform, JavaScript run-time environment that executes JavaScript code outside of a browser. In an easier to understand explanation, Node.js is a JavaScript runtime environment that includes everything you need to execute a program written in JavaScript, and is what we will use to create our applications on this course.

On [this website](https://nodejs.org/en/) you can find the links for installing the latest version of Node.js on your Windows or macOS machine.

On macOS you can also install it via [Homebrew](https://brew.sh/).
First run the following command to install Homebrew in your machine (copy and paste it on a Terminal window and click enter):
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Once Homebrew is installed, run:
```
brew install node
```

For Linux users check out [this link](https://nodejs.org/en/download/package-manager/). Or use the following code snippet directly for Debian and Ubuntu based distributions:
```
# Using Ubuntu
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt-get install -y nodejs

# Using Debian, as root
curl -sL https://deb.nodesource.com/setup_12.x | bash -
apt-get install -y nodejs
```

### Confirm that Node.js was properly installed (all platforms)

After you installed your Node.js on your machine (Windows, macOS or Linux), check that it was properly installed typing the following command on the terminal:
```
node -v
```
If you receive the version number (e.g: `v10.16.3`), everything is ok. If not, try the previous steps again or ask on the #general channel for help.

## Problem solving

> The following info will be useful for when you are studying/working on your own. On the class, please raise your hand in the moment you get stuck! There will be several teacher assistants there to help you immediately so you can continue following the class.

One of the skills a developer has to master, and also one of the most difficult to achieve at the beginning, is to find the correct answer for the problem they are facing. You are following the steps, everything seems to be fine and boom, you are receiving a weird error on the console or in VSCode. You have no idea why this is happening! You tried everything... So frustrating. But actually, this problem is faced by experienced programmers on a daily basis. And the solution is... to [Google](https://www.google.com/) it!

You will master this skill with time (what to actually type in google to find the answer you need), but at first you could try to just copy and paste on the google search the error you are receiving (try to only take the meaningful part of the error, for example: `Uncaught SyntaxError: Unexpected identifier`. You will probably get as first result a link to Stack Overflow.

[Stack overflow](https://stackoverflow.com/questions) is a community made by and for developers in which someone asks a question, and other developers answer it. If it's a good answer it gets upvotes, and if it's the answer that solved the problem, the OP (original poster) marks it with a green check. This is very useful for the developer community, because the problem we are currently facing most of the times someone else had it already, therefore here we can find many possible solutions to help with our coding struggles. Take a look [to some of the most entertaining questions](https://tutorialzine.com/2015/12/the-10-most-entertaining-stackoverflow-questions-of-all-time). :smiley:

If you are practising at home, and after researching you are stuck on a problem for more than 20-30 minutes, is time to ask for help in our channel!


## Course Material

Before the course please ensure you follow our [tool setup guide](course/material.md) and get ready :) 

## Lifetime Learning

The most important notion we want to grow within our community and during the bootcamp is Lifetime Learning.
We curated some nice tutorial/documentation/websites for you, we believe they are the best ways existing to learn for some topics. Please check them [here](learning/material.md).