+++
categories = ["Go"]
date = "2024-04-02"
description = ""
featured = "pic02.jpg"
featuredalt = ""
featuredpath = "date"
linktitle = ""
slug = "How can I create a good documentation?"
title = "How can I create a good documentation?"
type = ["posts","post"]
[ author ]
  name = "Notes"   
+++

## All content below are notes extracted from course about API documentation. It is available on:   

[OPEN SOURCE TECHNICAL DOCUMENTATION ESSENTIALS (LFC111)](https://trainingportal.linuxfoundation.org/courses/open-source-technical-documentation-essentials-lfc111)  


An API or tool that is easier to explain is also easier to learn and easier to use.

View point of user

User-Oriented Design
 you must carefully consider who will use your product, what tasks they will need to do  
 
 
 
Who is the intended audience for the information;
What background they are expected to have;
Where they can go to get that background;
How you expect them to use the documentation.  


Maybe zora needs this: [conreibuition policies] Your contribution policies should include information about subject matter experts in all areas that need documentation.  

essential for docs

* A detailed element reference;
* A high-level technical overview;
* Instructions for installation or access;
* Requirements for authorization and authentication;
* A “Hello World” or "Getting Started" example.  


sections (must-haves):

[API reference manual] - API reference is to provide the precise syntax of the language and to explain the intended use of each element, with just enough conceptual context for readers to understand the basic usage, and to clarify the relationships between the elements of the language and among functional areas or subsystems. 

[Technical overview] - explains what the technology is, what it does, who should use it, what differentiates it, and most importantly, the unique benefits it can deliver. People will only pay attention to your technology if they can see compelling benefits.   

A technical overview, whether it is a standalone piece or an introduction to an API reference, should answer these questions:

What does the product or service do?
- Placement within the domain
- Expected background of typical users
How does the API fit in?
- Placement within the product
- Placement within workflows
What can you do with the API?
- Main features
- Typical use cases


[Installation or access guide] - This guide should include everything needed for setup and configuration, things that you think are obvious, but often are a complete mystery to newcomers. You might even have different versions of this, one for internal developers, one for external developers, one for partners, and so on.
 
 
 ["Getting Started"/"Hello World"] - A getting-started guide usually includes a “Hello World” recipe (more information about recipes will follow shortly). If you aren’t familiar with “Hello World”, it’s the shortest functional program that you can write using an API. The program is a complete coding example that a developer can compile, execute, run, and see simple results. Originally, these programs ran just enough code to produce the message “Hello World” on a screen or printer.  
 
 
 Recommend "maybe must have"
 
 - [Glossary of terms] - auto explain
 - [Usage recommendations and example code ]  auto explain
 - [Conceptual and procedural documents] (Usage guides (Programmers Guide, Design Guide, Developers Guide) explain important concepts and advise on recommended usage. Tutorials help users learn the product and implement common use cases.)

 - [release notes]  - the release notes should include a list of features, overview of documentation, known problems, and how to get support. For following releases, release notes should include new features, changes, deprecations, deprecation policy, and upgrade/migration instructions 
 
 - [Migration/Integration guides] - document expalin how to migrate. Don’t assume that your user will be able to figure it out on their own. Even if it is easy to do, create the short guide that saves them the time it will take to determine that it is easy.  
 
 
 
## Best Practices for Producing Quality Software Documentation
  
  Tasks:
  
  Define a user layer to ensure complete coverage: This is the set of features and clearly identified public API elements that are available to users, which you are prepared to support across versions. 
  
  Review and test to ensure accurate content: Technical errors in the documentation undermine a reader's confidence in your product and in themselves, and make it much less likely that they will adopt and use your API successfully.
  
  Maintain a glossary of terms to ensure adequate description:  For someone to learn your system, you must ensure that the specific technical details are supported by high-level description that places those details in context. When you tell people how to use an element, you must also tell them why and when to use it.
  
  Follow a style guide to ensure discoverability: Your documents must include indexes, tables of contents, and cross-references that help the reader get to the right place from wherever they happen to land. The information should be available.  
  
  
 ### Documentation as a Contribution Area:
 
- Create a documentation label or tag for doc issues.
- Identify and prioritize your project's specific documentation needs.
- Provide policies and support services for documentation contributors.
- Identify subject-matter experts who can answer questions from writers and review documentation proposals in different areas.  


Checklist for ensure that the documentation has been succefull 

[ ] - All user-level elements and features included.
[ ] - Accurate content
[ ] - All details are correct.
[ ] - Adequate description
[ ] - Details are unambiguous and placed in context.
[ ] - Discoverability
[ ] - Readers can find the information they need.
 

Essencial characteristics


 * A clearly-defined user layer (public API elements).
 * Complete coverage and accurate syntax details of all public elements and features.
 * Useful semantic description of every element and feature.
 * Introductory description at every level that places information in the appropriate context.
 * Consistent use of terminology, conforming to an explicit glossary.
 * Consistent presentation and use of language.
 * Navigational aids that keep readers oriented and make it easy for users to find the information they need when they need it.
 * Clear indications of intended audience, prerequisites, and assumptions.  
 
 
 
 ### Guiideline for write documentation:

https://github.com/cncf/techdocs/blob/main/assessments/criteria.md

  
  
  
 
 

