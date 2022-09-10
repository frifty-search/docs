# Installing Git

## What is Version Control? <a href="#4ffe" id="4ffe"></a>

A Version Control System (VCS) allows you to revert files back to a previous state, revert the entire project back to a previous state, review changes made over time, see who last modified something that might be causing a problem, who introduced an issue and when, and more. Using a VCS also means that if you screw things up or lose files, you can generally recover easily. And sometimes you just want to know **“who wrote this crap”**, and having access to that information is worthwhile 😈.



## So What is Git? <a href="#13d5" id="13d5"></a>

Git is a version-control system for tracking changes in computer files and coordinating work on those files among multiple people. Git is a _**Distributed Version Control System**_. So Git does not necessarily rely on a central server to store all the versions of a project’s files. Instead, every user “clones” a copy of a repository (a collection of files) and has the _**full**_ history of the project on their own hard drive. This clone has _all_ of the metadata of the original while the original itself is stored on a self-hosted server or a third-party hosting service like GitHub.

Git helps you _**keep track of the changes**_ you make to your code. It is basically the history tab for your code editor(With no incognito mode 🌚). If at any point while coding you hit a fatal error and don’t know what’s causing it you can always revert back to the stable state. So it is very helpful for debugging. Or you can simply see what changes you made to your code over time.

## Setting Up Your Git Environment

### Step 0:  Make a GitHub Account.

If you have a GitHub, You can skip these steps. \
\
You can easily make an account by going through this [link](https://github.com/join).



### Step 1: Make sure you have Git installed on your machine.

If you are on your machine, fire up the terminal and enter the following command:

```bash
$ git --version
```

You can install git by downloading [it](https://git-scm.com/download/) from their binary page. Or You could do any package manager.

{% embed url="https://youtu.be/J_Clau1bYco" %}
Installing Git in Windows MAchine
{% endembed %}

{% embed url="https://youtu.be/hMEyBtsuAJE" %}
Installing Git on Mac
{% endembed %}

If you are using a Linux device, You probably have git installed. Otherwise, you can follow this [article](https://mcilis.medium.com/how-to-install-git-on-linux-4340e5bd598c).&#x20;

### Step 2: Tell Git who you are. <a href="#d9ed" id="d9ed"></a>

Introduce yourself. Slide in. Seriously, mention your Git username and email address, since every Git commit will use this information to identify you as the author.

```bash
$ git config --global user.name "YOUR_USERNAME" 
$ git config --global user.email "im_satoshi@musk.com"
$ git config --global --list # To check the info you just provided
```

### Step 3: Resource to Learn

{% embed url="https://youtu.be/8JJ101D3knE" %}
