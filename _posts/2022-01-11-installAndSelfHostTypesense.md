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

Typesense is a simple, lightweight, and powerful search engine, as we all know. Get through their official [downloads](https://typesense.org/downloads/) page to get official DEB, RPM, and pre-built binaries for Linux (X86 64) and macOS which are freely available to download. This article covers getting Typesense up and running, ingesting a variety of data sources into multiple collections, and getting a feel for the Typesense search interfaces locally. Typesense's official Docker images are also available on [Docker Hub](https://hub.docker.com/r/typesense/typesense). We'll go over the typesense installation guide step by step and try to cover everything.This article will cover a variety of installation guides for typesense on various different platforms.The official Docker images for Typesense are also available on .We will go over and try to cover the installation guide for typesense from absolute scratch.

## Getting started

Installing typesense is simple and straightforward; everything is well documented on their [documentation page](https://typesense.org/docs/guide/install-typesense.html), so you can jump right in. Typesense offers a variety of installation options for a variety of platforms, including macOS, Linux, Windows, and Docker, as well as it has number of pre-built binary packages available for download for other platforms as well.

## How to install Typesense?

Typesense installation is simple, quick, and straightforward. So, for example, if you want to install Typesense on a Mac, Linux, Windows, or any other platform, simply use or copy paste the following command into your platform's command line, and you're ready to launch your very own search engine.

##### Windows (WSL)(opens new window)

Typesense can be installed on Windows using the [windows WSL](https://docs.microsoft.com/en-us/windows/wsl/install) which lets developers run a GNU/Linux environment including most command-line tools, utilities, and applications directly on Windows, unmodified, without the overhead of a traditional virtual machine or dualboot setup. This can install Typesense directly on the windows platform itself. Simply click the link below to learn more about how to install Typesense inside Windows.

- [How to download and install Typesense on Windows?](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/download-and-install-typesense-windows/)

##### Mac Binary

Typesense can be installed directly on Mac using the help of simple [cURL](https://curl.se/) command which is a command-line tool for getting or sending data including files using URL syntax.This can install Typesense directly on the Mac platform itself. Simply click the link below to learn more about how to install Typesense inside Mac.

- [How to download and install Typesense on Mac?](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/download-and-install-typesense-Mac)

##### Linux Binary

Typesense is available to download as a .tar.gz archive for Linux platform.It can be simply installed in linux platform with the help of [wget](https://www.gnu.org/software/wget/) which is a command-line utility for downloading files from the web.This can install Typesense directly on the Linux platform itself. Simply click the link below to learn more about how to install Typesense inside Linux.

- [How to download and install Typesense on Linux?](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/download-and-install-typesense-linux/)

##### Docker Image

Typesense is also available as Docker images. A list of all published Docker images and tags is available at [https://hub.docker.com/r/typesense/typesense/](https://hub.docker.com/r/typesense/typesense/). The source files are in [Github](https://github.com/typesense/typesense).

- [How to run Typesense from the Docker Image?](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-run-typesense-docker-image/)

##### DEB package on Ubuntu/Debian

The Debian package for Typesense can be downloaded from the official Typesense website or from the APT repository of Typesense. It can be used to install Typesense on any Debian-based system such as Debian and Ubuntu.

- [How to download and install Typesense on Ubuntu?](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/download-and-install-typesense-ubuntu/)

##### RPM package on CentOS/RHEL

- [How to download and install Typesense on CentOS?](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/download-and-install-typesense-centos/)

## Inspecting server health status and some configuration tips

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
