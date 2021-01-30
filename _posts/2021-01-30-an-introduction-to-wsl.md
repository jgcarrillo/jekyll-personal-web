---
title: An Introduction to WSL
layout: post
permalink: /blog/:year/:title/
tags: [tips, development]
---

# AN INTRODUCTION TO WSL

If you always wanted to use **Linux** but you feel unconfortable with any partition tool or you don't want to try Linux in a clean installation in your computer, you are so lucky. Windows 10 adds a new feature call **subsystems**, which allows to install a basic Linux distro in our system without compromise your computer. If you want to give it a try, keep reading!

## Installing Windows 10 Terminal

First of all, it is neccesary to install this tool. It's not compulsory but upgrade the classical **cmd** with a most powerful tool. By this, we can open several terminals like _tabs_ in our browsers. You can continue by using the default terminal, but for me it's more useful this tool.

To install, go to Windows Store and search for _Windows Terminal_. You can install manually too, but by this way you will need to install new builds regularly by yourself.

## Installing WSL

Before any installation it is necessary to activate two features of Windows 10 to avoid errors. First of all, go to _Configuration > Update and security > For developers (left panel) and check developer mode_. It's probably that the computer need to install some files.

Next step is go to _Control Panel > Programs & features > Turn Windows features on or off (left panel) and check Windows Subsystem for Linux_ at the end of the list.

With all these steps completed, we need to go to Windows Store. In my case I have installed **Ubuntu**. You only need to search for the appropriate distro and install it. It's important to say you have to install only the app with the name _Ubuntu_ without any version in the name.

A download will start (this process take a while). When it's finished we will start it. It will request us a username and a password.

We need to install some packets by `sudo apt update` and a `sudo apt upgrade`. From here we could install the packages that we want, whether they are programs or characteristics of the distro.

If all the steps are correct (maybe you need to restart your computer), by open Windows Terminal you can choose **Ubuntu as a new terminal** in the dropdown menu.

## Customizing the terminal

Congratulations, you can use the most powerful features of Linux without having installed such a distro. However, if you want to unlock all the advantages maybe you could install the full distro. The next step is customize the terminal, so we will install some plugins or themes by the command:

`sh -c "$(curl -fsSL https://raw.github.com/ohmybash/oh-my-bash/master/tools/install.sh)"`

The configuration of the Windows Terminal is possible by a JSON file where we can define the characteristics to use. In my case, I added `"fontFace": "Cascadia Code"` and the theme _Dracula_ by `"colorScheme": "Dracula"`. It is also possible to add a theme for each terminal, as well as custom colors, emojis and so long.

From here the possibilities are endless. I hope you found it interesting 😀
