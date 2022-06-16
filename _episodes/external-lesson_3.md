---
title: Where to share your data
teaching: null
exercises: null
duration: 20
summary: A discussion about data licensing - what kind of options are there, and
  what are the pros and cons?
questions:
  - What is a license?
  - What licenses are there?
  - How do I choose a license?
objectives:
  - Understand the main issues in licensing.
  - Know what license suits your data.
keypoints:
  - Licenses let you control who can do what with your work.
  - Licenses are not a substitute for strong community norms.
  - Using a well-known license makes it easier for users and automated systems
    to understand and respect.
is-break: null
ukrn_wb_rules: []
day: 1
order: 225000
missingDependencies: []
dependencies: []
originalRepository: mjaquiery/ukrn-wb-lesson-examples

---
## Things to consider when choosing a data repository
- Disciplinary norms
- Funder policy
- Do you need to regulate access?
- Personal preferences

## A few repository options to explore...
- Bristol data repository: [data.bris](https://www.bristol.ac.uk/staff/researchers/data/publishing-research-data/)
- [ReShare](https://reshare.ukdataservice.ac.uk/) (UK data service)
- [Open Science Framework](https://osf.io/)

## What is the OSF?

The OSF  is an online collaboration and project management platform for research projects. 
The OSF is built and supported by the Center for Open Science ([https://cos.io/](https://cos.io/)), a non-profit organisation for increasing the openness, integrity, and reproducibility of research.

The OSF platform allows researchers to organise projects, store data, create registrations, and publish preprints. 
Projects can be subdivided into components, for which public and private sharing, collaborations, licensing, and DOIs can be individually managed.

## What can the OSF do for me?

The key capabilities of the OSF which matter to most researchers are project management, data storage, and collaboration.
The aim of the OSF is to be useful enough _to working researchers_ that the sharing and registration features are simply useful additions.
![OSF My Projects page screenshot]({% include installedFile.lqd path='/fig/osf-my-projects.jpg' %})

### Project management

The OSF platform allows you to create projects, which can have include files and directories, a license, a wiki, and third-party components (like Google Drive folders, Zotero libraries, and much, much more).
![OSF Exploring Social Metacognition project screenshot]({% include installedFile.lqd path='/fig/osf-esm.jpg' %})

Each project can have any number of components, which are exactly like projects - they can also have files and directories, licenses, etc., and they can have different collaborators and be made public or private independently of the main project.
Components can also have other components.

### Data storage

You can store data directly on the OSF platform, in a section in Files called 'OSF Storage'.
You can store data in one of three locations, including Frankfurt, Germany, in the EU.
Private projects can store up to 5gb of data per component (but you can have as many components as you like); public projects can have up to 50gb/component.
You can also link several other storage platforms, like Google Drive or DropBox, which will list your files in your project without counting towards your used space.
Any files listed, even those in external storage, are assigned their own unique URL, and the OSF previewer will do its best to generate a preview of the file at that URL, as well as allowing visitors to download the file.
[Here, for example, is one of the data dictionary files from the project shown above.](https://osf.io/kjm9h/)

### Collaboration

The OSF is designed with sharing and collaboration in mind. 
This means that even if you aren't ready to share your project with the public, you can easily add collaborators and define what they are allowed to do with your project.
Collaborators on the project can be listed as bibliographic contributors, meaning they get included in the citation.
![OSF Contributors management screenshot]({% include installedFile.lqd path='/fig/osf-contributors.jpg' %})

You can even share a view-only version of your project anonymously: e.g. to allow for blind peer review. 

### Sharing

If and when you feel like it, you can make individual components or your entire project public, to share your work with the world. 
Because the platform records when things were uploaded, it can establish primacy of ideas even if you do not share the work until later.

### Registration

At any stage, you can create a frozen copy of your project as a registration, alongside a registration document which details your current plans for your project.
This is a good way of tracing the evolution of a project and ensuring that confirmatory tests are distinct from exploratory tests.

## No matter where you decide to share your data, you will need to choose a license.

## What is a license?

Roughly, in lay terms, when you put in work to create or curate something, you acquire _rights_ over that thing. 
Your rights include things like the right to be identified as the author.
When other people use your work, they may do things that infringe upon your rights. 
To help them understand what they can and can't do, and to give them a legal basis on which to interact with your work, you can apply a _waiver_ or a _license_ to your work.

* A _waiver_ gives up rights, meaning that those rights cannot be infringed. 
* A _license_ specifies how someone can use your work. 
	* Generally, this adds to what people can do
	* But it can also require them to do some things, such as credit you as the author

If you don't include a waiver or a license people will not know how they can legally and appropriately use your work.
**Include a license**.

## How do I choose a license?

* Licenses used by others in your field
* Funder/Institution/Government requirements/guidance
* [License picker tool](http://ufal.github.io/public-license-selector/)

## What common data licenses are there to choose?

There are several _families of licenses_ which offer suites of similar licenses that place different restrictions on the users.
The families covered here are _Creative Commons_ (**CC-x**), _Open Data Commons_ (**ODC-x**), and _(UK) Government License_ (**xGL**).
Each subheading below addresses a different use case.

### No restrictions

To make your data maximally reusable, at the cost of losing the (legal) right to attribution and any control over how it is used, apply a public domain license. 
Public domain licenses can consist of a waiver, giving up all your rights, and a permissive license in case the waiver is not acceptable.
These licenses avoid the _attribution stacking_ problem of attribution licenses, but can only be used where 

* CC-0 4.0
* **PDDL**: Open Data Commons Public Domain Dedication and License
	* The PDDL includes attribution-sharealike requests as community norms, but not as legal requirements

> ## Community norms
> Just because you're legally _allowed_ to do something, doesn't mean you should.
> It's within the license terms of a public domain release to include a work verbatim without attribution, but many communities have strong norms against plagarism.
> 
> If the norms of your community cover your concerns, and you're not especially worries about how your work is used outside your community, you can use a public domain license even if you would _like_ attribution (you just don't _require_ it).
{: .notification}

### Attribution

You can require that people attribute your work to you when they use it.
This is a common requirement, and modern licenses usually make it clear what constitutes attribution (e.g. a URL for a page with attribution information).
A disadvantage to requiring attribution is that it can lead to _attribution stacking_, where attribution lists become unweildy because each derivative of a work must attribute the creators of each previous incarnation.

* **CC-BY 4.0**
* **ODC-By**
* **OGL** is designed to minimise attribution stacking by requiring a very basic attribution statement

### Share-alike (copyleft)

You can require that people share derivative works as openly as the original.
This can be awkward in practice because many copyleft licenses are incompatible with one another, meaning that it can be very difficult to find a way to release resources that include multiple components with sharealike licenses.

* **CC-BY-SA 4.0**
* **ODC-ODbL** allows products derived from a database to be released on an attribution basis, but requires new _databases_ derived from a database to be released on a sharealike basis

### No commercial use

You can require that people release derivatives of your work free of charge.
It is quite common for work with a non-commercial license to include an alternative license for use by those who wish to use work commercially (acquisition of the work under the more permissive license usually costs money). 
The definition of commercial can vary - in some cases textbooks or academic articles may count as commercial (even if the person producing the derivative work doesn't get the money). 

* **CC-BY-NC 4.0**
* **CC-BY-NC-SA 4.0** includes a sharealike clause alongside the non-commerical requirement
* **NCGL** is designed to minimise attribution stacking with a minimal acknowledgement notice, and has no sharealike requirement

> ## Discussion `10 min`
> Which repository seems most appropriate for your data?
>
> Which licensing approach seems most relevant for your data? You can use the liscence tool to help with this! Note that this might differ between projects...
> 

{: .discussion}

## Further reading
* [Digital Curation Centre Data License Guide](https://www.dcc.ac.uk/guidance/how-guides/license-research-data)
* [CESSDA License Training](https://www.cessda.eu/Training/Training-Resources/Library/Data-Management-Expert-Guide/6.-Archive-Publish/Publishing-with-CESSDA-archives/Licensing-your-data)
* [Data Carpentry Licensing Blogpost](https://datacarpentry.org/blog/2016/06/data-licensing)