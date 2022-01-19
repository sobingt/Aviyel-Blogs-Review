---
toc: true
layout: page
categories: [Typesense]
title: "What is Typesense Collection?"
comments: true
hidden: true
permalink: /what-is-typesense-collection/
---

<button class="back-button" onclick="window.history.back()"><< Back</button>

## Outline: [Article Title]

**Keyword:** [Enter Targeted Keyword]

**Keyword MSV:** [Enter Targeted Keywords Monthly Search Volume]

**Author:** [Enter Author Name]

**Due Date:** [Enter Due Date]

**Publish Date:** [Enter Desired Publish Date]

**User Persona:** [Enter Targeted Reader and/or User Persona]

Collection is simply a group of related documents in Typesense. In a relational database, a collection is roughly equivalent to a table.To create a collection we must first create a Collection, give it a name, and describe the fields that will be indexed from our Documents before we can add them to Typesense. This definition is referred to as the collection's schema, which is simply a fancy way of describing the fields (and their data types) in your documents.Simply click on the link below to learn more about How to create a collection in Typesense.

- [How to create a collection in Typesense?](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-create-typesense-collection/)

Defining a collection's "schema" can be compared to defining "types" in a strongly-typed programming language like Typescript, C, Java, Dart, Rust, and so on. This ensures that the documents you add to your collection have consistent data types and are validated, preventing a whole slew of errors that can occur when data types are mismatched or inconsistent across documents.

A schema can be specified in two ways:

- Typesense can either pre-define all of the fields to be indexed from your documents, or it can detect your fields and data types based on the documents you index.
- The simplest option is with auto schema detection, which eliminates the need to define an explicit schema. However, if you require more fine-grained control and/or validation, you should use with pre-defined schema detection, or even combine the two.

#### Creating a collection with a pre-defined schema

Let's start by making a collection with a pre-defined schema.This option allows you to fine-tune the data types of your document fields and configures your collection to reject documents that don't match your schema's data types (by default).Skip to auto-schema detection if you want Typesense to automatically detect your schema for you.Simply click on the link below to learn more about how to create a collection with a pre-defined schema.

- [How to create a collection with a pre-defined schema?](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-make-collection-with-predefined-schema-typesense/)

#### Creating a collection with auto schema detection

Auto-schema detection should help you if your field names are dynamic and not known ahead of time, or if you just want to keep things simple and index all fields you send in your documents by default. With the name, you can create a wildcard field. When you add documents to the collection, Typesense will automatically detect the type of the fields if you type auto. In fact, any RegEx expression can be used to name a field.Simply refer to the link below to learn more about how to make a collection with auto-schema detection in Typesense.

## Closing

Typesense was built with several distinctive features primarily aimed at making the developer's job easier while also giving customer as well as user the ability to provide a better search experience as possible.This article may have been entertaining as well as instructive in terms of how to install typesense from the ground up on a variety of platforms. Join Aviyel's community to learn more about the open source project, get tips on how to contribute, and join active dev groups.

## Call-to-Action

Aviyel is a collaborative platform that assists open source project communities in monetizing and long-term sustainability. To know more visit Aviyel.com and find great blogs and events, just like this one! Sign up now for early access, and don't forget to follow us on our socials!

<ul>
<li><p><a href="https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-make-collection-with-auto-schema-typesense/">How to make a collection with auto-schema detection in Typesense?</a><p>
<li><p><a href="https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-retrieve-collection-details-typesense/">How to retrieve collection details in Typesense?</a><p>
<li><p><a href="https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-list-all-collection-details-typesense/"> How to list all the collections in Typesense?</a><p>
<li><p><a href="https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-drop-collection-typesense/">How to drop a collection in Typesense?</a><p>
<br>
