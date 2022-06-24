---
title: Preparing data for sharing
teaching: null
exercises: null
questions:
  - What information do I need to include with shared data?
  - How can I make sure my shared data is valuable?
objectives:
  - "Understand the FAIR principles. "
  - "Identify how the FAIR principles might apply to your data. "
  - "Identify resources to support implementing the FAIR principles and
    supporting you with anonymization. "
keypoints:
  - "When sharing data, best practice is to follow the FAIR principles. "
  - "Preparing data for sharing is much easier, if how this will be done is
    planned early on in the pipeline and implemented 'as you go'. "
  - Anonymised data are easier to share legally. Remove direct identifiers and
    reduce precision to stop outliers leading to identification.
  - "\n"
day: 1
order: 209375
missingDependencies: []
dependencies: []
originalRepository: mjaquiery/jspsych-born-open-data
summary: ""
duration: 20

---
Research data should be shared in line with the [FAIR sharing principles](https://www.go-fair.org/fair-principles/):
* **F**indable
* **A**ccessible
  * Data should be saved on an accessible repository such as the [Open Science Framework (OSF)](https://osf.io/) or the [Bristol Research Data Repository](https://www.bristol.ac.uk/staff/researchers/data/publishing-research-data/), where we can give them a DOI
* **I**nteroperable
  * Data should be stored in formats that can be loaded by many different programs
* and **R**eusable
  * By giving our data an appropriate license, we will ensure people are clear about how the data can be used
  * By supplying meta-data (e.g., README, data dictionary) which explains the variables, we will make it possible for others to understand our dataset

To achieve this you will need to consider:
* **File naming conventions**
* **Software accessibility**
* **Metadata** - You will need to provide the maximum amount of information needed to recreate/reproduce this data
* **Quality checks** as you go along (e.g., is it sensible and readable to other people?)
* **Anonymisation** - Anonymisation is the process of turning data from which individual people can be identified into data from which individual people cannot be identified. Pseudonymisation is the process of turning data from which individual people can be identified into data from which individual people can only be identified using other, non-shared information.
{: .checklist}

> > ## Resources
> > * [University of Bristol data management guidance](http://www.bristol.ac.uk/staff/researchers/data/) (for help with metadata)
> > * [UK Data Service guidance for anonymising qualitative data](https://www.ukdataservice.ac.uk/manage-data/legal-ethical/anonymisation/qualitative.aspx)
>> * [UK Data Service guidance for anonymising quantitative data](https://www.ukdataservice.ac.uk/manage-data/legal-ethical/anonymisation.aspx)
> > * [Consortium of European Social Science Data Archives](https://www.cessda.eu/Training/Training-Resources/Library/Data-Management-Expert-Guide/5.-Protect/Anonymisation) (anonymisation guidance)

## Discussion `10 min`
> 
> Think of some recent data you have worked with. What would you need to do to implement the FAIR principles?
> 
{: .discussion}