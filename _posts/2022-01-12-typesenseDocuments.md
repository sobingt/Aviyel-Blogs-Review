---
toc: true
layout: page
categories: [Typesense]
title: "What is Typesense Document?"
comments: true
hidden: true
permalink: /what-is-typesense-documents/
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

In Typesense, each record you index is referred to as a Document.

#### Indexing a documents in Typesense

A document that is to be indexed in a collection must follow the collection's schema.If the document contains a string id field, Typesense will use that field as the document's identifier. Otherwise, Typesense will assign the document an auto-generated identifier.

#### Indexing a single documents in Typesense

The single document create endpoint can be used to index a document in response to a user action in your application.If you need to index a large number of documents at once, the import documents endpoint, which is optimized for bulk imports, is the way to go. For example, if you have 100 documents, indexing them all at once using the import endpoint will be much faster than indexing them one at a time.Simply click the link below to learn more about how to index a document in Typesense.

- [How to index and upsert a document in Typesense?](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-index-upsert-document-typesense/)

#### Upserting a document in Typesense

If a document with the same id already exists, the endpoint will replace it; if a document with the same id does not exist, the endpoint will create one but if you need to upsert a large number of documents at once, it is recommended to use the import documents endpoint with action=upsert, which is designed for bulk upserts. For example, if you have 100 documents, upserting them all at once using the import endpoint will be much faster than upserting them one at a time.Simply click the link below to learn more about how to upsert a document in Typesense.

- [How to index and upsert a document in Typesense?](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-index-upsert-document-typesense/)

#### Retrieving a document collection in Typesense

Simply click the link below to learn more about how to retrieve a document collection in Typesense.

- [How to retrieve a document collection in Typesense?](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-retrieve-document-collection-typesense/)

#### Updating a document collection in Typesense

Simply click the link below to learn more about how to update a document collection in Typesense.

- [How to update a document collection in Typesense?](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-update-document-collection-typesense/)

#### Deleteing a document collection in Typesense

Simply click the link below to learn more about how to delete a document collection in Typesense.

- [How to delete a document collection in Typesense?](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-delete-document-collection-typesense/)

#### Deleteing a document collection by a query in Typesense

Simply click the link below to learn more about how to delete a documents collection by a query in Typesense.

- [How to delete a documents collection by a query in Typesense?](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-delete-document-collection-query-typesense/)

#### Importing a documents in Typesense

Simply click the link below to learn more about how to import documents in Typesense.

- [How to import documents in Typesense?](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-import-documents-typesense/)

#### Exporting a documents in Typesense

Simply click the link below to learn more about how to export documents in Typesense.

- [How to export documents in Typesense?](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-export-documents-typesense/)

#### Indexing a documents with Dirty Data in Typesense

When the type of a field being indexed does not match the previously inferred type for that field or the one defined in the collection's schema, the dirty_values parameter determines what Typesense should do.Simply click the link below to learn more about how to index a document with dirty data in Typesense.

- [How to index a document with dirty data in Typesense?](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-index-dirty-data-typesense/)

#### Curating a documents in Typesense

Simply click the link below to learn more about how to curate Documents in Typesense.

- [How to curate Documents in Typesense?](https://aviyeldevrel.github.io/Aviyel-Blogs-Review/how-to-curate-document-typesense/)

## Closing

Typesense was built with several distinctive features primarily aimed at making the developer's job easier while also giving customer as well as user the ability to provide a better search experience as possible.This article may have been entertaining as well as instructive in terms of how to install typesense from the ground up on a variety of platforms. Join Aviyel's community to learn more about the open source project, get tips on how to contribute, and join active dev groups.

## Call-to-Action

Aviyel is a collaborative platform that assists open source project communities in monetizing and long-term sustainability. To know more visit Aviyel.com and find great blogs and events, just like this one! Sign up now for early access, and don't forget to follow us on our socials!
