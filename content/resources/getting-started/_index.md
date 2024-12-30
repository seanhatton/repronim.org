---
title: Getting Started with ReproNim
weight: 2
---

**The ReproNim philosophy**:  Incorporate reproducible practices into the typical neuroimaging workflow.  These practices ensure more robust, well documented studies at the end for you, your colleagues and your peers.

ReproNim offers best practices, tools and training to implement reproducible neuroimaging in your lab.  Here is a brief overview of our website:

* **New to reproducible neuroimaging?**
  * Why reproducible neuroimaging
  * What is reproducible neuroimaging?
* **Wondering what ReproNim can do for you?**
  * Meet our exemplary user personas and the issues they face in running neuroimaging studies
  * View our introduction to the ReproNim way, step-by-step guides on some steps you can take using ReproNim tools to improve your ability to perform robust and shareable neuroimaging studies
* **Tools and how-to guide:**
  * Our ReproGuide provides descriptions of our tools and how to use them
* **Training:**
  * [On-line training course](https://www.repronim.org/teach.html) on a range of basic and more advanced topics related to reproducible neuroimaging
  * ReproNim Fellows Program:  Become a ReproNim fellow through our train the trainer program

## Meet our users personas

To introduce you to ReproNim, we have created a set of exemplary user personas that represent some typical users and given them a face (through the magic of AI), a set of skills and interests. We then produced a set of basic use cases that showcased how adopting the principles of neuroimaging and ReproNim tools can help them in their goals.

Who would you like to hear from?

<link rel="stylesheet" href="/css/personas.css">
<div class="persona">
    <a href="#sarah">
        <img src="/images/sarah.jpg" alt="Sarah">
    </a>
    <p>
        Hi, I’m Sarah.  I’m an early- to mid-career researcher.  I’m  interested in applying best practices to my day-to-day research workflow.  <a href="#sarah">Read more.</a>
    </p>
</div>

<div class="persona">
    <a href="#richard">
        <img src="/images/richard.jpg" alt="Richard">
    </a>
    <p>
        Hi, I’m Richard.  I’m a research software engineer.  I want to incorporate more standards into the technical operations of my lab and also learn more about how to effectively share workflows with my clients.  <a href="#richard">Read more.</a>
    </p>
</div>

<div class="persona">
    <a href="#john">
        <img src="/images/john.jpg" alt="John">
    </a>
    <p>
        Hi, I’m John.  I'm a university-based computational neuroscientist and teacher.  I would like to see what resources are available for my teaching about rigor and reproducibility. <a href="#john">Read more.</a>
    </p>
</div>

<div class="persona">
    <a href="#evelyn">
        <img src="/images/evelyn.jpg" alt="Evelyn">
    </a>
    <p>
      Hi, I’m Evelyn.  I'm the director of a multi-center distributed project.  My interest is in harmonizing the research being performed at several sites. <a href="#evelyn">Read more.</a>
    </p>
</div>

### Sarah

<img src="/images/sarah.jpg" alt="Sarah" style="width: 250px; height: auto;">

I’m Sarah, an early- to mid-career researcher.  I’m interested in applying best practices to my day-to-day research workflow.

I'm fluent in modern technologies and comfortable both at the bench and behind a computer, and I spend my days engaged in the hands-on aspects of studies. As I build my career, I want to keep up-to-date with the latest trends and tools, but I don't dwell on technology for its own sake. Efficiency is important, but not if it sacrifices rigor.

I would like support for making my workflow development more efficient: How do I go from my 'garden path' trial workflow development, lock into a 'final' workflow, and then efficiently apply this workflow to my complete dataset? My workflow might change, so I'd like to efficiently update and re-apply the new workflow. I've heard versioning will be important for this, but I'm not handy with these technologies. Publishing my data would be nice for some additional impact and complying with the NIH data sharing mandate support.

**How can ReproNim help?**

ReproNim can help Sarah learn more about data and software management and other best practices for reproducible neuroimaging,  and introduce her to tools and practices for versioning workflows. When data and software are managed throughout the neuroimaging workflow, publishing data, and the pipelines that produced it,  effectively and efficiently is much easier to do.

**Tutorials that might be interesting to Sarah**:

* Creating a [neuroimaging data management and sharing plan](/resources/tutorials/data-management-and-sharing/)
  * Principle \= planning
* Implementing data management basics:  Using ReproNim tools to [convert data to the BIDS standard](/resources/tutorials/dicom-to-bids/) and [create a data dictionary](/resources/tutorials/data-dictionary/)
  * Principle:  Data and metadata management
  * Foundations:  Standards, Annotation
* Implementing software management basics:  [Using Git to manage workflow/pipeline versions](/resources/tutorials/git/)
  * Principle:  Software management
  * Foundations:  Versioning
* Publishing your work as a “Re-executable paper”( \= text, data, code):  Standards-based data sharing through OpenNeuro
  * Principle:  Publishing re-executable papers
  * Foundations: Standards, Annotation

### Richard

<img src="/images/richard.jpg" alt="Richard" style="width: 250px; height: auto;">

Hi, I’m Richard, a research software engineer.  I want to incorporate more standards into the technical operations of my lab and also learn more about how to effectively share workflows with my clients.

I'm responsible for developing the software in support of my lab’s research. I'm given high-level requirements but I then have the freedom to decide how to implement solutions. I don't code exclusively but spend time researching and planning my work since I have to balance software engineering best practices with the limited resources available for research software engineering.

I would like to generate software products that incorporate community standards for data ingestion and export. I'm aware of BIDS for standard input data representation, but I need to learn about output standards such as BIDS derivatives and standardized output descriptions (like NIDM).  I have heard that containerizing software can make it easier to deliver it to my local clients (and for them to share with others who want to reproduce their work) and easier to support compared to a bare metal software solution.

**How can ReproNim Help?**

ReproNim can help Richard learn how standards such as BIDS and NIDM can help with better data management.  ReproNim can provide Richard with demos and use cases to show why containerization is worth the effort.

**Tutorials that might be interesting to Richard**:

* Advanced data management: Putting your derived data into BIDS derivatives and creating a semantically-enriched  data dictionary using NIDM, a standard for annotating neuroimaging data
  * Principles:  Data management
  * Foundations:  Standards, annotation
* Working with containers:  Using Neurodocker to containerize computational
  * Principles:  Re-executability
* Advanced data and software management: [DataLad containers/run \+, YODA principles](/resources/tutorials/repronim-containers/)
  * Principles:  Re-executability

### John

<img src="/images/john.jpg" alt="John" style="width: 250px; height: auto;">

Hi, I’m John.  I'm a university-based computational neuroscientist and teacher.  I would like to see what resources are available for my teaching about rigor and reproducibility.

I have both lab and teaching responsibilities. I'd like my lab members to understand and utilize principles of re-executable annotated workflows.  I also wonder whether whether the ReproNim fellowship program might be appropriate for someone in my lab (perhaps as a way to train others in the lab thereafter). As a teacher, I'm interested in broadly educating my students on reproducibility, including exposure to key concepts, tools, and educational materials.

I'm interested in whether ReproNim provides up-to-date teaching materials that I can use in my own teaching.  I'm also interested in resources that might help my students and/or lab.

**How can ReproNim Help?**

**Educational resources that might be interesting to John and his students**:

* John should point his students to the [Why Reproducible Neuroimaging](/about/why/) sections of our website for a high level overview of issues around reproducible neuroimaging.
* For more in-depth training, ReproNim has created a [modular on-line course](/resources/training/) that covers basic and advanced topics in reproducible neuroimaging.  Each module contains tutorials and hands on exercises.
* ReproNim also offers a [Fellows Program](/fellowship/), a one year train-the-trainer program in reproducible neuroimaging

ReproNim provides a [catalog of our main tools](/resources/tools/), with links to help materials and on-line forums.

→ For hands on experience, his students can follow [tutorials](/resources/tutorials/) recommended for Sarah, Richard and Evelyn

### Evelyn

<img src="/images/evelyn.jpg" alt="Evelyn" style="width: 250px; height: auto;">

Hi, I’m Evelyn.  I'm the director of a multi-center distributed project.  My interest is in harmonizing the research being performed at several sites.

I've been a researcher my whole career, and now I direct a multi-center distributed project. My responsibilities include oversight for integrated data sharing and cross-site analyses within the project, as well as making all data ultimately publicly accessible and reusable. I'm interested in options for facilitating and streamlining data acquisition, use, and reuse for varied purposes, both within and beyond the bounds of the project itself. I have the authority and responsibility to make recommendations for infrastructure that would serve a multidisciplinary multi-site project well.

I think ReproNim might address many of my priorities, but I'd really like an end-to-end platform for data acquisition, data management, and dissemination. I need to distribute common analyses to all of the project's sites. I'd like it to be easy for the sites to give me results from this analysis that are easy to aggregate and harmonize. As the sites are also collecting their own subjects, I need common demographic, clinical, and behavioral data to be collected and shared in a way that is also easy to aggregate and harmonize.

**How can ReproNim help?**

ReproNim is not an end to end platform, but has several tools that can take her current data workflow and make it easy to share FAIR data and analyses across multiple sites.

**Use cases that might be of interest to Evelyn:**

* Planning and data management:  Learn how a data collection and annotation framework for behavioral data to be collected can be set up using [ReproSchema and shared across multiple sites](https://repronim.netlify.app/resources/tutorials/reproschema/).
  * Principles:  planning, data management
  * Foundations:  standards, annotations
* Basic software management for distributed data: [Curating and processing a single study to generate standardized, analysis-ready data to participate in distributed projects using Nipoppy](/resources/tutorials/nipoppy/)
  * Principles:  Software management
  * Standards:  Standards, annotation
* Advanced data management:  Adding standards and semantics to data dictionaries to promote data harmonization and findability
  * Principles:  data management, FAIR
  * Foundations:  Standards, Annotation
* Advanced metadata management: [Searching and sharing metadata through ReproPond and ReproLake](/resources/tutorials/pond-lake/)
  * Principles:  Metadata management
  * Foundations:  Standards, Annotation
