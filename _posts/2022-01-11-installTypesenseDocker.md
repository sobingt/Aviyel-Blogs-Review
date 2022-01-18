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

**Buyer Persona:** [Enter Targeted Reader and/or Buyer Persona]

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

#### Getting started with Typesense docker installation documentation

The main goal of this tutorial is to show you how to use docker to install typesense on your personal computer.

```bash
docker pull typesense/typesense:0.22.1
```
