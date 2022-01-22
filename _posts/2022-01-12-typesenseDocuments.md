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

- [How to index and upsert a document in Typesense?](https://aviyelverse.github.io/Aviyel-Blogs-Review/how-to-index-upsert-document-typesense/)

#### Upserting a document in Typesense

If a document with the same id already exists, the endpoint will replace it; if a document with the same id does not exist, the endpoint will create one but if you need to upsert a large number of documents at once, it is recommended to use the import documents endpoint with action=upsert, which is designed for bulk upserts. For example, if you have 100 documents, upserting them all at once using the import endpoint will be much faster than upserting them one at a time.Simply click the link below to learn more about how to upsert a document in Typesense.

- [How to index and upsert a document in Typesense?](https://aviyelverse.github.io/Aviyel-Blogs-Review/how-to-index-upsert-document-typesense/)

#### Upserting a document in Typesense

<ul>
<li><p><a href="https://aviyelverse.github.io/Aviyel-Blogs-Review/how-to-index-upsert-document-typesense/">How to index and upsert a document in Typesense?</a><p>
<li><p><a href="https://aviyelverse.github.io/Aviyel-Blogs-Review/how-to-retrieve-document-collection-typesense/">How to retrieve a document collection in Typesense?</a><p>
<li><p><a href="https://aviyelverse.github.io/Aviyel-Blogs-Review/how-to-update-document-collection-typesense/">How to update a document collection in Typesense?</a><p>
<li><p><a href="https://aviyelverse.github.io/Aviyel-Blogs-Review/how-to-delete-document-collection-typesense/">How to delete a document collection in Typesense?</a><p>
<li><p><a href="https://aviyelverse.github.io/Aviyel-Blogs-Review/how-to-delete-document-collection-query-typesense/">How to delete a documents collection by a query in Typesense?</a><p>
<li><p><a href="https://aviyelverse.github.io/Aviyel-Blogs-Review/how-to-export-documents-typesense/">How to export documents in Typesense?</a><p>
<li><p><a href="https://aviyelverse.github.io/Aviyel-Blogs-Review/how-to-import-documents-typesense/">How to import documents in Typesense?</a><p>
<li><p><a href="https://aviyelverse.github.io/Aviyel-Blogs-Review/how-to-index-dirty-data-typesense/">How to index a document with dirty data in Typesense?</a><p>
<li><p><a href="https://aviyelverse.github.io/Aviyel-Blogs-Review/what-is-typesense-documents/">What is Typesense Document?</a><p>
<li><p><a href="https://aviyelverse.github.io/Aviyel-Blogs-Review/how-to-curate-document-typesense/">How to curate Documents in Typesense?</a><p>
