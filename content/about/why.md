---
title: Why Reproducible Neuroimaging
type: docs
weight: 70
---

Neuroimaging, like many fields of science, has been described as having a "reproducibility crisis."  We most often hear about this crisis in the context of trust in science and the ability to reproduce the results of studies published by others.  It is, of course, frustrating when you waste time and resources trying to replicate others' research only to find that the experiment failed. We know that some of the causes of the current reproducibility crisis are poor study design, including underpowered studies. But it is also true that even in a properly designed neuroimaging study, more and more evidence has emerged that any set of results is very sensitive to even small variations in computational environments, preprocessing steps, statistical models, and analyses used. In fact, as we state in our [2019 paper](https://www.frontiersin.org/journals/neuroinformatics/articles/10.3389/fninf.2019.00001/full), when it comes to reproducibility in neuroimaging, "everything matters."

Reproducible neuroimaging is therefore not only a concern to those outside your lab trying to build on your work, but to you as a researcher, project director, or principal investigator. Can you reproduce your own research? Can your graduate students?  Can your present and future post-docs?  If a reviewer asks you to perform a different analysis on the same data, can you?

## What is reproducible neuroimaging?

### Scientific reproducibility

First, what do we mean when we say that scientific results are reproducible?  _Reproducibility_ is a broad term and is often used casually to mean the replication of the findings of a study at some level.  Here, we use the term _scientific reproducibility_ in general to mean _re-executability_, the ability to obtain the exact same results when the same data is analyzed using the exact same analysis methods.  Re-executability focuses on methodological reproducibility and should be seen as simply the first step in establishing the validity of a given set of results. A _result_, a claim made about the meaning of a study, is fully reproducible when it can be re-executed and generalized independently.  Some of what we are referring to as generalization is referred to as _replication_, defined as repeating an entire study with new data to see if the original results can be replicated.  But as you can see in the graphic below, there are multiple types of replication in the age of open data and tool sharing.  A true biological inference should hold true regardless of the methods used to observe a biological process or the specific sample of the population being studied.

![image](/images/spectrum.png)

### Reproducible neuroimaging

Building on the materials above, reproducible neuroimaging refers to the practice of conducting and disseminating neuroimaging research in a manner that allows others to independently verify and replicate the findings. It encompasses a set of principles, practices, and tools aimed at ensuring transparency, rigor, and accountability in neuroimaging studies. Transparency is achieved through others being able to know precisely what operations were performed on what data.  Remember, the "others" that benefit from reproducible neuroimaging include:

* you, 
* future you, 
* your lab, 
* your colleagues, 
* reviewers, 
* other neuroimagers, 
* data scientists, and 
* AI.
