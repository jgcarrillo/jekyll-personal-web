---
title: A Few Weeks Using Linux. This is The Result
layout: post
permalink: /blog/:year/:title/
tags: [tips, os]
---

# A FEW WEEKS USING LINUX. THIS IS THE RESULT

As a Windows user, I never had the necessity of change my actual Operating System (**Windows 10**) because all the task I perform during the day are totally cover by this O.S. However, I felt the desire of give me a chance and try Linux for the first time in my entirely life. The change wasn't easy at all but with time I felt more comfortable using the terminal, commands and all the enviroment that surrounds Linux.

## The Distro

For this test I used **Kubuntu**, a Ubuntu based distribution but with a little bit _differences_ such as a different graphical desktop, a package manager and a file explorer with a lot of options for personalization. You can download it [in its official website](https://kubuntu.org/).

I installed the distro in a **Virtual Machine**, so I don't know what problems will arise if you will do the same but in a physical computer. However, you can install it in dual boot (with Windows, for example), in a partition with free storage or in a manual installation with a root partition (/) and a home partition (/home). There are a lot of tutorials on Youtube about this.

## First steps in Kubuntu

During the installation, I made a mistake because I uncheck the options '_Install this third-party software_' and '_Download updates while installing_'. As a Linux noob, I don't know if any of the packages that I had to install solved that two unchecked options. If you have problems during the installation of the packages, maybe this command solve it.

### Tools

`sudo apt install build-essential`

The `build-essential` package will install other tools used along with `make`.

Later, I installed **neofetch** which is a Terminal-based system information tool to see your distro info in an ASCII format. To install it, you need to do this steps:

- `sudo add-apt-repository ppa:dawidd0811/neofetch`
- `sudo apt update`
- `sudo apt install neofetch`

Another interesting tool is _htop_ to control all the process in your computer. It's so easy to install by executing `sudo apt install htop`.

Both two tools can be accessed by typing `neofetch` or `htop` inside the _Terminal_.

The next step is define the Software source. To do that we need to go to _Muon Package Manager_ , click on _Settings_ and then click on _Configure Software Sources_. You will need to type your root password. In the _Ubuntu Software_ tab we check the first four options, and in 'Download from' we will choose Other > Select Best Server.

Then, go to _Additional Drivers_ and check if you need to install any additional component.

Once we have set that, we need to install **Synaptic** to install packages based on GTK+ graphic interface. Simply search for synaptic and press _install_. Once we have installed it, go to Synaptic and search for:

- `ubuntu-restricted-extras`, and select the appropriate for Kubuntu (addons and extras).
- `openjdk` to install the Java Development Kit (if you need it).

Addicionally, you can install **flatpack**, another utility to install and administrate packages. The installation is very simple, just [check the official website](https://flatpak.org/).

### Programs

In my case, I installed IntelliJ IDEA for Java and VSCode for the rest. These two programs are easy to install but I had serious problems with _Firefox Dev Edition_. In fact, at the moment I am not capable of install it, because you need to do quite a few previous steps that are very confused to me.

I think this is one of the most common problems that I have found on Linux, and it's the fact than, when you need to install any program with **.tar** or **.tar.gz** extensions, you need to unzip the files in various folders using the Terminal and then create an alias to link the programs and the shortcut. I know this is more secure and, actually, this is how Linux works but for a Windows users, this is so complicated.

### Customization

That was one of the features that made me wonder if I could survive with Linux as my day-to-day O.S. I love the _KDE Plasma_ GUI and also the _Dolphin_ file manager.

There are other advantages that you probably know if you are a Linux user: more control of the O.S., more customization, etc. But right now I think I can't do the change to Linux due to several problems that I describe below.

I also found ZSH as a **framework** for the terminal. I installed it simply by following [this tutorial](https://terminaldelinux.com/terminal/introduccion/instalacion-zsh/).

### Problems

Anyway, solved the major problems the next step was to install the environment to PHP development, and that was a completely dissaster.

I tried with LAMPP using the official installer but, when I tried to use the terminal to connect to MYSQL, I get an error. I also tried to installing Apache/PHP/MySQL by separated but I don't feel comfortable with that.

For me, set up a correct environment for PHP development is essential because the backend is one of my greatest interest in web development, so, until I found a better solution, I think I can't choose Linux as my default Operating System.

Other issue that I found was that MSI laptops don't behave as well as I would like with Linux O.S. Different problems such as compatibilities or drivers make changing the O.S. really difficult.

## To Sum Up

I think know Linux is attractive, if you are familiar with commands and terminals you probably will found Linux as a PRO extension of this. In the rest of the cases, it will be very anoying to introduce in it.

The programs share the files, so you don't need to install the same features that are using by different programs, rather than in Linux different programs shares the common resources. This is tremendously interesting but in practice (for me) it's really hard (at leats for programs that are not _.deb_ extension, which are installed as in Windows).

I will keep going in my efforts to understand Linux as much I can, but with a Windows installation to use programs like Photoshop. In other sort of things, Linux is much easier than Windows, for example to install programs using the Terminal, and the security is better administrate.
