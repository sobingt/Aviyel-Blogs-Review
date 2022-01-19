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

**Keyword MSV:** [Enter Targeted Keyword’s Monthly Search Volume]

**Author:** [Enter Author Name]

**Due Date:** [Enter Due Date]

**Publish Date:** [Enter Desired Publish Date]

**Buyer Persona:** [Enter Targeted Reader and/or Buyer Persona]

Collection is simply a group of related documents in Typesense. In a relational database, a collection is roughly equivalent to a table.To create a collection we must first create a Collection, give it a name, and describe the fields that will be indexed from our Documents before we can add them to Typesense. This definition is referred to as the collection's schema, which is simply a fancy way of describing the fields (and their data types) in your documents.

Defining a collection's "schema" can be compared to defining "types" in a strongly-typed programming language like Typescript, C, Java, Dart, Rust, and so on. This ensures that the documents you add to your collection have consistent data types and are validated, preventing a whole slew of errors that can occur when data types are mismatched or inconsistent across documents.

A schema can be specified in two ways:

- Typesense can either pre-define all of the fields to be indexed from your documents, or it can detect your fields and data types based on the documents you index.
- The simplest option is with auto schema detection, which eliminates the need to define an explicit schema. However, if you require more fine-grained control and/or validation, you should use with pre-defined schema detection, or even combine the two.

<ul>
<li><p><a href="https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-create-typesense-collection/">How to create a collection in Typesense?</a><p>
<li><p><a href="https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-make-collection-with-schema-typesense/">How to make a collection with a schema in Typesense?</a><p>
<li><p><a href="https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-make-collection-with-predefined-schema-typesense/">How to create a collection with a pre-defined schema?</a><p>
<li><p><a href="https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-retrieve-collection-details-typesense/">How to retrieve collection details in Typesense?</a><p>
<li><p><a href="https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-list-all-collection-details-typesense/"> How to list all the collections in Typesense?</a><p>
<li><p><a href="https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-drop-collection-typesense/">How to drop a collection in Typesense?</a><p>
<br>
