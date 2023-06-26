---
layout: default
title: About This Project
nav_order: 2
---

<p align="center">
  <img width="650" height="200" src="../assets/HeaderAboutThisProject.png">
</p>

<h1 align="center">What is this for?</h1>

This repository and its contents are to be a continuation of my work on [LegacyOSXKVM](https://github.com/royalgraphx/LegacyOSXKVM). The goal of that project was to allow anyone to quickly revisit some of their favorite versions of Mac OS X as it was known to many for years with its various releases. Snow Leopard was the main focus of that project, and as such had the most effort put into it. Nowadays we need to be on modern versions of macOS to enjoy the latest and greatest offered from Apple. The focus has now shifted to providing an Up-to-Date, Out of Box (OOB), Clean Template for creating Virtual Machines of the latest versions offered by Apple. As of writing this, you can create a powerful VM of macOS Ventura, Monterey, and even Sonoma works. The guides in this repository will help you continuously work on your virtual machine to make it the perfect experience. Things will not work right away, you will slowly keep fixing them as you discover what must be fixed.

<h1 align="center">Who is this for?</h1>

This is for experienced users. You should already be familiar with 3 core concepts: [Virtualization](https://libvirt.org/)/[QEMU](https://www.qemu.org/docs/master/), [OpenCore](https://dortania.github.io/OpenCore-Install-Guide/), and [macOS](https://en.wikipedia.org/wiki/MacOS). If you feel as though you are not up to speed on any of these concepts, please take the time to first gain adequate knowledge as it will vastly improve your chances of having a working system you can daily drive. This guide is written completely from my perspective as I've learned throughout my time in the Hackintosh community. What you would typically do if you wanted to run macOS on your system you would have to use the OpenCore bootloader to provide macOS with the necessary information it needs. A Virtual Machine is no different. In theory, what we are simply doing is creating an OpenCore disk image that acts as if it were the equivalent of a USB or an EFI partition post-installation. While there exist many projects that utilize QEMU/KVM, for daily driving you must have a compatible GPU. What this means for the user of any projects that are seen as the equivalent to "Prebuilt EFI's" is that there is no learning involved. This causes the user to not understand why certain things are broken on their system and possibly may never fix those issues, potentially leaving them in the background. This guide is for those who are looking to properly create a macOS Virtual Machine from the ground up. <b>PLEASE READ CAREFULLY.</b> Try not to ask for support before rereading, many times you will misread something on accident or are simply not paying enough attention to what it's instructing you to do. 

<h1>You can now proceed to the <a href="/docs/02-0-HostPreparations">Host Preparations</a> section!</h1>