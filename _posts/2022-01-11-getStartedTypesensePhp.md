---
toc: true
layout: page
categories: [Typesense]
title: "How to Get Started with Typesense and PHP?"
comments: true
hidden: true
permalink: /how-to-get-started-with-typesense-php/
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

You'll learn how to use Typesense with PHP applications in this tutorial. As an example, we'll use a Laravel application, but you can use any PHP codebase as long as you know what you're doing.

#### Typesense in Action

Before we get started programming the app, let's take a look at how Typesense works. Typesense is written in C++ and comes as a pre-compiled application, as previously stated. You can download the application and run it as a server on your server or local machine. The Typesense server works in the same way as any other web server, with a user-friendly REST API interface. HTTP requests are used to communicate with this server. Consider the following scenario: you run an online bookstore and you're looking for a book called Clean Code. You can do so by running the following CURL command:

```bash
curl -H "X-TYPESENSE-API-KEY: ${TYPESENSE_API_KEY}" \
"${TYPESENSE_HOST}/
collections/books/documents/search?q=clean+code&query_by=title"
```

Follow the article link below to learn more about integrating typesense in PHP in depth.

- [Getting Started with PHP API Clients on Typesense](https://aviyel.com/post/1288/building-a-search-ui-with-typesense)

## Closing

Typesense was built with several distinctive features primarily aimed at making the developer's job easier while also giving customer as well as user the ability to provide a better search experience as possible.This article may have been entertaining as well as instructive in terms of how to install typesense from the ground up on a variety of platforms. Join Aviyel's community to learn more about the open source project, get tips on how to contribute, and join active dev groups.

## Call-to-Action

Aviyel is a collaborative platform that assists open source project communities in monetizing and long-term sustainability. To know more visit Aviyel.com and find great blogs and events, just like this one! Sign up now for early access, and don't forget to follow us on our socials!
