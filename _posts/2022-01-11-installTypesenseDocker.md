---
toc: true
layout: page
categories: [Typesense]
title: "How to run Typesense from the Docker Image?"
comments: true
hidden: true
permalink: /how-to-run-typesense-docker-image/
---

<button class="back-button" onclick="window.history.back()"><< Back</button>

## Outline: [Article Title]

**Keyword:** [Enter Targeted Keyword]

**Keyword MSV:** [Enter Targeted Keyword’s Monthly Search Volume]

**Author:** [Enter Author Name]

**Due Date:** [Enter Due Date]

**Publish Date:** [Enter Desired Publish Date]

**User Persona:** [Enter Targeted Reader and/or User Persona]

<br>

Docker is a containerization platform that is free and open source. It allows developers to package applications into containers, which are standardized executable components that combine application source code with the OS libraries and dependencies needed to run that code in any environment. Containers make distributing distributed applications easier, and they're becoming more popular as companies move to cloud-native development and hybrid cloud environments.

##### Docker Image

Let's start with a basic understanding of containers before moving on to the utility of Docker.A container is a standard software unit that packages code and all of its dependencies so that an application can run quickly and reliably in different computing environments.During the development phase, this tool is extremely useful. Because there are so many developers involved in the process, setting up the environment to run the project can be a daunting task, especially since each project has its own set of dependencies and versions.

#### Docker container

A Docker container image is a small, standalone software package that contains everything needed to run an application, including code, runtime, system tools, system libraries, and settings. At runtime, container images become containers, and when Docker containers run on Docker Engine, images become containers.

Visit the following website for more information on Docker containers:

- [https://www.docker.com/resources/what-container](https://www.docker.com/resources/what-container)

You can download the basic docker desktop from this [Link](https://www.docker.com/products/docker-desktop).

The following is a list of prerequisites for creating and running Docker containers:

- Docker Engine which is a program that runs on the host machine and allows you to build and run containers.
- Docker Daemon which is a daemon that runs on top of Docker and also it is in charge of Docker containers.
- Docker Client executes commands. The REST API is used to translate the command and deliver it to the Docker Daemon.
- Docker Compose which is a tool that allows you to put together in a container.

  Progressing forward, we'll walk you through the Docker installation process on Windows.

#### Docker Installation on Windows

- Download the docker file from [Here](https://docs.docker.com/docker-for-windows/install/) and always keep in mind that to run Docker on Windows 10, you'll need a 64-bit processor and 4GB of system RAM.
- Then, to run the installer, double-click on Docker Desktop-Installer.exe and remember that if you don't have the installer file, you can get it from Docker Hub and run it whenever you need it.
- On the Configuration page, always enable Hyper-V Windows Feature once the installation process begins.
- Finally, to allow the installer, go through the installation process and wait until it's finished.
- Click Close and restart after the installation process is completed.

#### Launching the Docker Desktop Tool on windows.

The tool does not start automatically after the installation process is completed. To use the Docker tool, look for it in your desktop search results and select Docker Desktop.Docker provides an onboarding tutorial before you begin using the application. The tutorial walks you through the steps of creating a Docker image and running a container, Now you can see docker Desktop is now running on Windows successfully.Then, to install the Docker engine on your system, follow the steps below.

- To verify the version of Docker installed on the system, go to Docker CLI and run the Docker version command.

Bravo, your Docker installation on Windows is complete, and you are now ready to create and run Docker images and containers within the Docker inside the windows platform.

#### Docker Installation on Linux/Ubuntu

The following are the steps to install Docker:

- On Ubuntu, open the terminal.
- Use the following command to remove any Docker files that are currently running in the system:After you've entered the command stated below, you'll need to enter the root password and hit enter.

```bash
$ sudo apt-get remove docker docker-engine docker.io
```

- Use the following command to see if the system is fully up to date:

```bash
$ sudo apt-get update
```

- Use the following command inside the terminal to install Docker. You'll then be given the option of choosing between yes/no; select yes.

```bash
$ sudo apt install docker.io
```

- Use the following command to install all of the dependency packages:

```bash
$ sudo snap install docker
```

- Once you start testing Docker, run the following command to see what version you have installed:

```bash
$ docker --version
```

- Using the following command to pull an docker image from the Docker hub.:

```bash
$ sudo docker run hello-world
```

- Use the following command to see if the docker image has been pulled and is present in your linux/ubuntu:

```bash
$ sudo docker images
```

- Use the following command to see all the containers that have been pulled:

```bash
$ sudo docker ps -a
```

- Use the following command to see if any containers are running:

```bash
$ sudo docker ps
```

Bravo, your Docker installation on Linux/Ubuntu is complete, and you are now ready to create and run Docker images and containers within the Docker inside the Linux platform.

#### Docker Installation on Mac

Docker Desktop for Mac is now generally available. This allows for the development of applications in a variety of local development environments, as well as the extension of development pipelines for ARM-based applications.Docker Desktop also supports multi-platform images, allowing developers to create and run images for both x86 and ARM architectures without the need to set up a complicated cross-compilation environment. In addition, docker buildx can be used to seamlessly integrate multi-platform builds into the build pipeline, and Docker Hub can be used to find and share multi-platform image repositories.

Docker developers have removed the hard requirement to install Rosetta 2 starting with Docker Desktop 4.3.0. When using Darwin/AMD64, a few optional command line tools still require Rosetta 2. However, installing Rosetta 2 is recommended for the best experience. Run the following command to manually install Rosetta 2 directly from the command line:

```bash
 softwareupdate --install-rosetta
```

- First step [click here](https://desktop.docker.com/mac/main/arm64/Docker.dmg?utm_source=docker&utm_medium=webreferral&utm_campaign=docs-driven-download-mac-arm64) to download the docker desktop binary file.
- To open the installer, open Docker.dmg, then drag the Docker icon to the Applications folder.
- To start Docker, open Docker.app in the Applications folder.
- The Docker Subscription Service Agreement window can be found in the Docker menu (whale like menu). It includes a modification to Docker Desktop's terms of service. Docker Desktop opens the Quick Start Guide if you've only recently installed the app.

Bravo, your Docker installation on Linux/Ubuntu is complete, and you are now ready to create and run Docker images and containers within the Docker inside the Linux platform.

Now that you've successfully installed Docker on your computer, let's begin pulling the typesense image and building our own search engine with it.

#### Getting started with Typesense docker installation documentation

The main goal of this tutorial is to show you how to use docker to install typesense on your personal computer.

```bash
docker pull typesense/typesense:0.22.1
```

## Closing

Typesense was built with several distinctive features primarily aimed at making the developer's job easier while also giving customer as well as user the ability to provide a better search experience as possible.This article may have been entertaining as well as instructive in terms of how to install typesense from the ground up on a variety of platforms. Join Aviyel's community to learn more about the open source project, get tips on how to contribute, and join active dev groups.

## Call-to-Action

Aviyel is a collaborative platform that assists open source project communities in monetizing and long-term sustainability. To know more visit Aviyel.com and find great blogs and events, just like this one! Sign up now for early access, and don't forget to follow us on our socials!
