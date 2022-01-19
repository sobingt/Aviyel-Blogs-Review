---
toc: true
layout: page
categories: [MobSF]
title: "What are the system requirements in Typesense?"
comments: true
hidden: true
permalink: /what-are-the-system-requirements-in-typesense/
---

<button class="back-button" onclick="window.history.back()"><< Back</button>

## Outline: [Article Title]

**Keyword:** [Enter Targeted Keyword]

**Keyword MSV:** [Enter Targeted Keyword’s Monthly Search Volume]

**Author:** [Enter Author Name]

**Due Date:** [Enter Due Date]

**Publish Date:** [Enter Desired Publish Date]

**User Persona:** [Enter Targeted Reader and/or User Persona]

Typesense is an in-memory datastore that focuses on retrieval speed and low latency. To do so, it keeps an in-memory copy of the search index and a disk copy of the raw data. It is critical to choose a good system configuration to get the expected performance characteristics from Typesense.

#### RAM Selection

When no data is indexed, the Typesense process is very light-weight, taking up only about 20MB of RAM. The amount of RAM needed is entirely determined by the size of the data to be indexed.In general, if your dataset is X MB in size, you'll need 2X-3X MB of RAM to index it in Typesense.Consider the following scenario: If your dataset is 1GB in size, you'll need 2GB to 3GB of RAM to keep the entire index in memory.If your dataset contains many documents with overlapping words (or tokens), RAM usage will be low, and it will be high if documents contain words (or tokens) that are unique to them.

#### CPU Capacity Selection

To handle concurrent search traffic and indexing operations, CPU capacity is critical.Typesense is built to be highly scalable right out of the box, requiring no additional configuration. It uses all of the compute capacity available to it automatically. As a result, the maximum number of requests per second a given CPU configuration can handle is entirely dependent on your search query patterns as well as the shape and size of the indexed data. While it's difficult to make an exact recommendation for ideal CPU capacity because it depends on your data, here are some data points to help you visualize your CPU requirements:

- With 2.2 million records, a 4vCPU Typesense node can handle 104 concurrent search queries per second.
- With 28 million records, a 4vCPU Typesense node can handle 46 concurrent search queries per second.
- With 3 million records, an 8vCPU 3-node Typesense cluster can handle 250 concurrent search queries per second.

<mark>Keep in mind that Typesense requires at least two virtual CPUs (vCPUs) to run.</mark>

You can use nodes in Typesense Cloud that have "Burst" vCPU capacity. If your traffic is relatively low for the majority of the day, with the occasional moderate spike during indexing, you can save money by using the "Burst" vCPU options which Typesense provides. If you have a high baseline of traffic or a high indexing volume, this option is not a good fit. If you send a large amount of traffic to the nodes in this offering on a regular basis, response times will begin to slow.

#### Disk Selection

Typesense saves a copy of the raw data to disk and then uses it to create the in-memory index. Then, at search time, it fetches (only) these documents from disk and includes them in the API response after determining the final set of documents to return.To run Typesense, you'll need enough disk space, at least the size of your raw dataset. SSDs are much faster than magnetic disks and are therefore recommended.

Typesense manage disk space for you automatically in Typesense Cloud. It uses NVMEe SSD disks that give you the fastest data transfer rates when you enable the "High Performance Disk" option (available only for Highly-Available Non-Burst configurations).

#### Number of Nodes selection

Typesense can be configured to run on a single node or in a Highly-Available multi-node cluster.In your Production environment, we strongly advise you to run a Highly-Available 3-node or 5-node configuration to ensure that your search service is resilient to inevitable infrastructure issues.Typesense's consensus algorithm is Raft, and because Raft requires a quorum of nodes for consensus, you'll need at least three nodes to tolerate a single node failure. A 5-node cluster can tolerate up to 2 node failures, but at the cost of longer write latencies.

#### Search Delivery Network (SDN) selection

Typesense Cloud allows you to create a Search Delivery Network, which is a Typesense cluster that spans multiple geographic regions around the world (SDN). You'll be given an SDN endpoint, and queries sent to it will be automatically routed to the node that's closest to the origin of the search request.If your users are geographically dispersed across countries (or even states where they have multiple data center options in different cities) and you call Typesense directly from your website/app, choosing an SDN configuration will ensure that your users get consistent ultra-low-latency searches regardless of their location, because the SDN endpoint automatically routes each search query to the data center that is closest to them.

## Closing

Typesense was built with several distinctive features primarily aimed at making the developer's job easier while also giving customer as well as user the ability to provide a better search experience as possible.This article may have been entertaining as well as instructive in terms of how to install typesense from the ground up on a variety of platforms. Join Aviyel's community to learn more about the open source project, get tips on how to contribute, and join active dev groups.

## Call-to-Action

Aviyel is a collaborative platform that assists open source project communities in monetizing and long-term sustainability. To know more visit Aviyel.com and find great blogs and events, just like this one! Sign up now for early access, and don't forget to follow us on our socials!

<br>
