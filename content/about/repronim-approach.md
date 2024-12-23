---
title: The ReproNim Approach
type: docs
weight: 90
---

## How does ReproNIM help support reproducible neuroimaging?

[ReproNim](https://www.repronim.org/)’s goal is to improve the reproducibility of neuroimaging science, while making the process of capturing and precisely describing all essential/necessary experimental details both easier and more efficient for investigators.
ReproNIM focuses on practices and tools that support researchers and software engineers in integrating reproducible principles and actions into their own neuroimaging workflow.
We call this operational framework for reproducible analysis the ReproSystem.

![image](/images/reprosystem.png)

As outlined in the accompanying figure, the ReproSystem framework takes the full experimental cycle of neuroimaging data acquisition, analyses, and publication into account.
This system explicitly includes both data (any of various types, such as scanner acquisition, data converted to BIDS, behavioral data, output of prior analysis) entering into an analysis, and the metadata+provenance (i.e. software versions and computer operating system versions used, processing script, subject demographics, results description, etc.) of the analysis. 
The metadata maintains a link to its associated data permitting flexibility regarding how each of these types of information sources can be used.
To the familiar components of data and analysis environments, we also add to the framework a means to store and retrieve machine-readable description of metadata associated with the tools in both a local/private store (which we refer to as a ReproPond) and a shared/public repository (ReproLake).

To get started, see:

* [Getting started with ReproNim](/resources/getting-started/)
* The ReproGuide to [tools and use cases](/resources/tools/)
