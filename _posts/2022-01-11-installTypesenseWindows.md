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

##### Windows (WSL)(opens new window)

```bash
wsl
wget https://dl.typesense.org/releases/0.22.1/typesense-server-0.22.1-amd64.deb
sudo apt install ./typesense-server-0.22.1-amd64.deb
```

Keep in mind that after installing the typesense-server package, the "installed typesense-server package post-installation script subprocess returned error exit status 1" message will appear. Ignore this message; <mark>apt list --installed | grep typesense</mark> will show that the installation was successful.
