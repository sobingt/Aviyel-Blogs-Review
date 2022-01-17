---
toc: true
layout: page
categories: [Typesense]
title: "How to install and self-host Typesense?"
comments: true
hidden: true
permalink: /how-to-install-and-self-host-typesense/
---

<button class="back-button" onclick="window.history.back()"><< Back</button>

## Outline: [How to install and self-host Typesense?]

**Keyword:** Typesense

**Keyword MSV:** [Enter Targeted Keyword’s Monthly Search Volume]

**Author:** [Enter Author Name]

**Due Date:** [Enter Due Date]

**Publish Date:** [Enter Desired Publish Date]

**Buyer Persona:** [Enter Targeted Reader and/or Buyer Persona]

<!-- <br> -->

## Introduction

Typesense is a C++-based search engine that claims to be very fast, typo-tolerant, highly configurable, and very handy and easy to use. The Typesense project provides its own hosting service as a commercial product, but the engine itself is open source and can be installed locally on a variety of platforms such as windows linux and mac. It comes with a GLP 3 license, which is adequate if the server code is not changed.They provide several pre-built artifacts for running Typesense in Production or locally. DEB, RPM, and pre-built binaries for Linux (X86 64) and macOS which are freely available to download on their official [downloads](https://typesense.org/downloads/) page.

Typesense is a very popular tech stack tool in the Search as a Service category. It is completely open source, with 8.8K GitHub stars and 235 GitHub forks. It is widely used and widely popular, with [Storipress CMS](https://storipress.com/) and our own [Aviyel](https://aviyel.com/) platform being two of the most prominent users. This article will cover a variety of installation guides for typesense on various different platforms.The official Docker images for Typesense are also available on [Docker Hub](https://hub.docker.com/r/typesense/typesense).We will go over and try to cover the installation guide for typesense from absolute scratch.

## Getting started

Installing typesense is simple and straightforward; everything is well documented on their documentation page, so you can jump right in. Typesense offers a variety of installation options for a variety of platforms, including macOS, Linux, Windows, and Docker, as well as it has number of pre-built binary packages available for download for other platforms as well.

## How to install Typesense?

Typesense installation is simple, quick, and straightforward. So, for example, if you want to install Typesense on a Mac, Linux, Windows, or any other platform, simply use or copy paste the following command into your platform's command line, and you're ready to launch your very own search engine.

##### Mac Binary

```bash
curl -O https://dl.typesense.org/releases/0.22.1/typesense-server-0.22.1-darwin-amd64.tar.gz
```

##### Linux Binary

```bash
wget https://dl.typesense.org/releases/0.22.1/typesense-server-0.22.1-linux-amd64.tar.gz
```

##### Docker

```bash
docker pull typesense/typesense:0.22.1
```

##### DEB package on Ubuntu/Debian

```bash
wget https://dl.typesense.org/releases/0.22.1/typesense-server-0.22.1-amd64.deb
sudo apt install ./typesense-server-0.22.1-amd64.deb
```

##### RPM package on CentOS/RHEL

```bash
wget https://dl.typesense.org/releases/0.22.1/typesense-server-0.22.1-1.x86_64.rpm
sudo yum install ./typesense-server-0.22.1.x86_64.rpm
```

##### Windows (WSL)(opens new window)

```bash
wsl
wget https://dl.typesense.org/releases/0.22.1/typesense-server-0.22.1-amd64.deb
sudo apt install ./typesense-server-0.22.1-amd64.deb
```

## Inspecting server healt status and some configuration tips

Once you've completed the installation, you can check the health of your server by calling the /health API end-point to see if it's ready to accept requests.

```bash
curl http://localhost:8108/health
{"ok":true}
```

Using command line arguments, you can also entirely customize various Typesense Server settings. More information on [How To Configure Typesense Server](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-configure-typesense-server/) can be found in this reference [article](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-configure-typesense-server/).

## Closing

Typesense was built with several distinctive features primarily aimed at making the developer's job easier while also giving customer as well as user the ability to provide a better search experience as possible.This article may have been entertaining as well as instructive in terms of how to install typesense from the ground up on a variety of platforms. Join Aviyel's community to learn more about the open source project, get tips on how to contribute, and join active dev groups.

## Call-to-Action

Aviyel is a collaborative platform that assists open source project communities in monetizing and long-term sustainability. To know more visit Aviyel.com and find great blogs and events, just like this one! Sign up now for early access, and don't forget to follow us on our socials!

<br>

<ul>
<li><p><a href="https://aviyeldevrel.github.io/Aviyel-Blogs-Review/download-and-install-typesense-Mac/">How to download and install Typesense on Mac?</a><p>
<li><p><a href="https://aviyeldevrel.github.io/Aviyel-Blogs-Review/download-and-install-typesense-linux/">How to download and install Typesense on Linux?</a><p>
<li><p><a href="https://aviyeldevrel.github.io/Aviyel-Blogs-Review/download-and-install-typesense-windows/">How to download and install Typesense on Windows?</a><p>
<li><p><a href="https://aviyeldevrel.github.io/Aviyel-Blogs-Review/download-and-install-typesense-ubuntu/">How to download and install Typesense on Ubuntu?</a><p>
<li><p><a href="https://aviyeldevrel.github.io/Aviyel-Blogs-Review/download-and-install-typesense-centos/">How to download and install Typesense on CentOS?</a><p>
<li><p><a href="https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-run-typesense-docker-image/">How to run Typesense from the Docker Image?</a></p>
