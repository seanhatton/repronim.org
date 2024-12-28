---
title: Reproducible Neuroimaging in Practice
type: docs
weight: 80
---

## ReproNim's principles of reproducible neuroimaging

<!--
The style section will cause the sub-lists to be labeled with lowercase 
letters.

Use care when modifying the principles since there are hard coded 
references to them (by NUMBER.LETTER) on other pages.
-->

<style>
    ol ol li { list-style-type: lower-alpha; }
</style>

1. Study planning:
    1. Implement good science basics, e.g., power analysis, statistical consult
    2. Consider using pre-existing data for planning and/or analysis
    3. Create an [NIH-compliant data management and sharing plan](https://sharing.nih.gov/data-management-and-sharing-policy/planning-and-budgeting-for-data-management-and-sharing/writing-a-data-management-and-sharing-plan#after)
    4. Adopt [open consent](https://open-brain-consent.readthedocs.io/en/stable/) to allow broad sharing of data
    5. [Pre-register](https://www.cos.io/initiatives/prereg) your study

1.  Data and metadata management:
    1. Use **standard** data formats and extend them to meet your needs.
    2. Use **version control** from start to finish
    3. **Annotate** data using standard, reproducible procedures

1.  Software management:
    1. Use released versions of open source software tools.
    2. Use **version control** from start to finish
    3. Automate the installation of your code and its dependencies
    4. Automate the execution of your data analysis
    5. **Annotate** your code and workflows using standard, reproducible procedures
    6. Use **containers** where reasonable

1.  Publishing everything:  publishing re-executable publications
    1. Plans should be shared (pre-registration)
    2. Software should be shared
    3. Data should be shared
    4. All research objects should be FAIR

In turn, as indicated by the blue highlights in the above figure,  **four core actions** are key to implementing these principles:

## ReproNim's 4 Core Actions

1) **Use of Standards:** Using standard data formats and extending them to meet specific research needs is important for *data and metadata management* in reproducible neuroimaging.

2) **Annotation and provenance:** Annotating data using standard, reproducible procedures ensures clarity and transparency in data management (*data and metadata management*). **Provenance** refers to the origin and history of data and processes, enabling researchers to track how data was generated, modified, and analyzed (*data and metadata management*, *software management*, and *publishing everything*). This is essential for understanding the context of data and ensuring reproducibility.

3) **Implementing version control:** Version control is crucial for both data and software management. It allows researchers to track changes over time, revert to previous versions if necessary, and collaborate effectively.

   For data, version control helps manage different versions of datasets and track modifications made during processing and analysis (*data and metadata management*).

   For software, version control helps track code changes, manage different versions of analysis scripts, and ensure that the correct version of the code is used for each analysis (*software management*).

   And even publications can be versioned (*publishing everything*).

4) **Use of Containers:** Containers provide a portable and self-contained environment for running software, ensuring that the analysis can be executed consistently across different computing environments (*software management*). They encapsulate all the software dependencies needed to run an analysis, making it easier to share software (*publishing everything*) and reproduce results.

![image](/images/principles-of-neuroimaging.jpg)
