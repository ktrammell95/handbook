# Get your Computer ready


"A good craftsmans knows his tools". This is double so for software developers. Follow the steps to prepare your computer for the course. As a rule of thumb, if your computer has a CD drives, its too old for the course and an update is needed

**Reach out to SDG Staff on Slack or email if you get stuck here!!!**

## Dev machine

The suggested computer for students is an Apple MacBook Pro laptop **less than two years old**.
Minimum requirements:
- 8GB of RAM
- 500GB HDD
- macOS High Sierra (10.13)
or Windows 10, subject to approval (see below)

_Why a Mac?_ All of our students being on the same platform enables us to move at a much
quicker pace. Processes like setting up new tools experience reduced friction because the
same workflows apply to everyone.

Additionally, The open source and web development communities are invested in tools and
libraries that work best with POSIX based operating systems like UNIX, Linux, and Apple’s
macOS (BSD Unix). In short, we believe using the macOS best prepares our students to work in
the web development industry.

Students who choose to study .NET development with us may also find substantial benefit from using macOS. The development skills learned on UNIX based system (like macOS) will help build good developer habits. A PC laptop can be approved for class use on a case by case basis during the interview process.

## Required Software 

### Slack 

We will be using Slack extensively throughout the cohort and beyond, It is highly recommended to download the app for your laptop and (if you have one) for your smart phone. 

Head over here to download it: https://slack.com/downloads

### Visual Studio Code

For the first part of the program, we will learning various front end technologies. These languages are best used from a light weight editor. Visual Studio Code is Microsoft's new lightweight text editor. It is a powerful IDE (integrated development environment) that offers an outstanding tool set, while staying out of your way. 

Download it here: https://code.visualstudio.com/download

BONUS CHALLENGE: As developers, we love the command line. We always try to find ways to better utilize the power of the command line. So as a bonus, try to set your environment to open VS Code from the command line by typing the command:

``` 
code . 
```

## Mac Setup

### HomeBrew

### Node & Yarn

---
### Feedback

Let me know how it went here
https://goo.gl/forms/b4c9HX8n3dbCgtGu1

**and if you need help, ping an instructor or alumni on slack!!!!**


---

## Windows 10 Set up

### Powershell

As developers, you will be using a vareity of IDE (code editors) through out your career. But, one constant is the terminal. One Windows, there are 2 different terminals, Command Line and PowerShell. We will be using Powershell. This will let you control your PC by typing commands. Powershell already comes install on all Windows PC. You can open it by using the `Start` menu.

---
### Node.js

#### What

Node is a runtime for javascript. This means that with node, we can run javascript on our machines without having to be in a browser

#### Why

For the first part of the training, we are concentrating on the HTML/CSS and JavaScript. Many useful tools for those languages are built with node. 

#### How

Run the installer here:
<br/>
[https://nodejs.org/en/](https://nodejs.org/en/)

---
### Yarn 
#### What

Yarn is a package manager for node packages. This means that we can install and use libraries that are written in node.

#### Why

We will be using this to run our scripts and as well as installing packages. This will be more useful the more we dive deeper in JavaScript

#### How


Follow these instructions: 

[https://yarnpkg.com/lang/en/docs/install/](https://yarnpkg.com/lang/en/docs/install/)

---
### Surge

#### What 

Surge is a static website hosting company. It allows for easy deploy of your websites so they are on the web!

#### Why

We will use this to host some projects to see how the deploy process works

#### How

Once you have node installed, run the following command in powershell.

``` 
npm install --global surge
```

---

### Git

#### What 

Git is a distributed source control system. This allows us to work on and collaborate on different projects with little to no headache.

#### Why

Git is how we will be managing our files and sharing code between each other. It will seem rough at first but with practice, you will never know how any else shares documents

#### How

Go here and download the install: 
[https://gitforwindows.org/](https://gitforwindows.org/)

---
### Posh-git

#### What 

`post-git` is a extension for powershell that allows easy management for git. It will give very useful information for us.

#### How

Follow these instructions
https://github.com/dahlbyk/posh-git#installation

to move on, you should be able to run `Import-Module posh-git` in a git repo and get a display.

_NOTE:_ This will be the hardest item to install. It is recommended to do this last.

### Set up to run everytime you open up powershell

- in powershell run, `code %UserProfile%\My Documents\WindowsPowerShell\profile.ps1`
- in the file that opens, add `Import-Module posh-git`. 
- save and close file
- restart powershell

---
### Hub

#### What
 Hub is command line helper for github. It allows for easy github manipulation from powershell.

#### How
Download and run this installer: 
[https://github.com/github/hub/releases/download/v2.3.0-pre9/hub-windows-amd64-2.3.0-pre9.zip](https://github.com/github/hub/releases/download/v2.3.0-pre9/hub-windows-amd64-2.3.0-pre9.zip)

---
---
### Feedback

Let me know how it went here
https://goo.gl/forms/b4c9HX8n3dbCgtGu1

**and if you need help, ping an instructor or alumni on slack!!!!**
