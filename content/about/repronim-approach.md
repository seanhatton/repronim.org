---
title: The ReproNim Approach
type: docs
weight: 90
---

## How does ReproNim help support reproducible neuroimaging?

ReproNim's goal is to improve the reproducibility of neuroimaging science while making the process of capturing and precisely describing all essential study details both easier and more efficient.
ReproNim focuses on practices and tools that support researchers and software engineers in integrating reproducible principles and actions into their own neuroimaging workflow.

![A diagram showing the flow of data through an imaging study.](/images/reprosystem.png)

As outlined this figure, ReproNim's system takes the full cycle of neuroimaging data acquisition, analyses, and publication into account.
The system explicitly includes both data entering into an analysis (data of various types including scanner acquisitions, data converted to BIDS, behavioral data, and outputs of prior analyses), and the metadata and provenance of the analysis (software versions and computer operating system versions used, processing scripts, subject demographics, results descriptions, etc.).
The metadata maintains a link to its associated data, permitting flexibility in how each of these information sources can be used.
To the familiar components of data and analysis environments we also add a means to store and retrieve machine-readable descriptions of metadata associated with the tools in both a local/private store (which we refer to as a _ReproPond_) and a shared/public repository (_ReproLake_).

To get started, see:

* [Getting started with ReproNim](/resources/getting-started/)
* [ReproNim's core tools](/resources/tools/)
* [ReproNim's tutorials](/resources/tutorials/)
