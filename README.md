# jquery-git-crashcourse

Let's learn about git and jQuery! This is the git repository that we're going to 
use to learn about jQuery and how to collaborate using git. Let's get started

## Prerequisites
- A Computer
- A Text editor 
- A Web browser (preferably Chrome)
  
## Installing git
### Mac using Homebrew
If you have homebrew, you can fire up a terminal and run

```
brew install git
```

### Mac using Installer
If you don't have homebrew setup, you can download and run the 
[git for Mac installer](https://git-scm.com/download/mac)

### Windows using Installer
Download and run the [git for Windows installer](https://git-scm.com/download/win)

## Verify git is working
### Mac 
Open up Terminal (using Spotlight or Applications > Terminal.app) and run git --version

### Windows
Open git bash and run git --version

For both of these situations you should see the version of git you have installed.
Leave this window open we're going to use it again soon.

## Sign up for GitHub

You can think of GitHub as being like the social network for coders. It's where we share
open source software. It's where we find libraries to help us write code. It's amazing.

So, let's visit http://github.com/ and fill out the sign up form.

## Fork and clone your first repository

If you aren't already reading this here, visit 
https://github.com/TechTalkLaramie/jquery-git-crashcourse

Click the Fork button in the top right hand corner. This is going to create your own fork
of this repository. It's yours now, you can do whatever you want with it!

Let's clone it now so we can work with it on our local machine. From the window we made
sure git worked, let's find a friendly home for our projects. You might have this home from
the last crash course. I have a directory called git in my home directory where I keep all my
projects. Wherever you choose to keep your projects, navigate there from the terminal.

```
mkdir ~/git
cd ~/git
```

Now that we're at a friendly home for our projects, let's clone the repository we're going
to use for this class (change MYGITHUBUSERNAME to your username)

```
git clone https://github.com/MYGITHUBUSERNAME/jquery-git-crashcourse.git
cd jquery-git-crashcourse
```

From here you can open up this file with your text editor if you want (README.md)

Let's switch gears over to Javascript land for a bit.

## Javascript Hello World

OK, time to write some code. We'll start in the most classic of ways with a Hello World app.

It's a good idea to open up our new jquery-git-crashcourse folder up in Explorer (not IE 
but the file explorer) for Windows or Finder in Mac.

Double click 1-hello-world.html to open it up in your browser.

Right click 1-hello-world.html to open it up in your text editor of choice.

Now, from your text editor you can see a blank space where you can enter in

```
alert('Hello world')
```

Refresh your web browser and you should see an alert dialog pop up that says Hello World

## jQuery Hello World

Let's dive into jQuery head first. Let's add a twist to our previous Hello World and make 
it so if you press a button, it'll say Hello.

Double click 2-hello-jquery.html to open it up in your browser.

Right click 2-hello-jquery.html to open it up in your text editor of choice.

OK, let's add this to our script section

```
    $(function() {
      $('#press-me').click(function() {
        alert('hello world')
      })
    })
```





