---
toc: true
layout: page
categories: [Typesense]
title: "How to download and install Typesense on windows?"
comments: true
hidden: true
permalink: /download-and-install-typesense-windows/
---

<button class="back-button" onclick="window.history.back()"><< Back</button>

## Outline: [Article Title]

**Keyword:** [Enter Targeted Keyword]

**Keyword MSV:** [Enter Targeted Keyword’s Monthly Search Volume]

**Author:** [Enter Author Name]

**Due Date:** [Enter Due Date]

**Publish Date:** [Enter Desired Publish Date]

**Buyer Persona:** [Enter Targeted Reader and/or Buyer Persona]

<br>

WSL (Windows Subsystem for Linux) is a compatibility layer that allows Windows 10, Windows 11, and Windows Server 2019 to run Linux binary executables natively.

#### Installaing WSL

By running the following command in an administrator PowerShell or Windows Command Prompt and restarting your machine, you can easily install everything you need to run Windows Subsystem for Linux (WSL).

```bash
wsl --install
```

This command will enable the optional components you need, download the most recent Linux kernel, set WSL 2 as your default, and install a Linux distribution for you .A console window will open the first time you launch a newly installed Linux distribution, and you will be asked to wait for files to decompress and be stored on your machine. All future launches should be under a second long.

##### Windows (WSL)(opens new window)

```bash
wsl
wget https://dl.typesense.org/releases/0.22.1/typesense-server-0.22.1-amd64.deb
sudo apt install ./typesense-server-0.22.1-amd64.deb
```

Keep in mind that after installing the typesense-server package, the "installed typesense-server package post-installation script subprocess returned error exit status 1" message will appear. Ignore this message; <mark>apt list --installed | grep typesense</mark> will show that the installation was successful.

## Closing

Typesense was built with several distinctive features primarily aimed at making the developer's job easier while also giving customer as well as user the ability to provide a better search experience as possible.This article may have been entertaining as well as instructive in terms of how to install typesense from the ground up on a variety of platforms. Join Aviyel's community to learn more about the open source project, get tips on how to contribute, and join active dev groups.

## Call-to-Action

Aviyel is a collaborative platform that assists open source project communities in monetizing and long-term sustainability. To know more visit Aviyel.com and find great blogs and events, just like this one! Sign up now for early access, and don't forget to follow us on our socials!
