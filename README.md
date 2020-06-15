# PMBOK document templates
Linked document structure for project management as described in the PMI PMBOK Guide 6th ed.  
Plans, Documents, Processes, Tools and Techniques e.t.c - in markdown.

---

# About

This repository provides easy to edit templates for starting a project documentation using the project management method from the PMI PMBOK Guide 6.0. 

Importantly, the documents are organized by linking **to them** from their respective processes. Hence, you can go to a process and see and jump to project documents that are relevant to that process. This way, you will not miss the documents that one should consult or update while going through the project life cycle.

Obviously, for any specific project, it is not neccessary to use *all* of the documents.

There are separate folders with:
- **Business Documents** - 2 templates. These serve mostly as placeholders for documents that should come from outside.
- **Processes** - list of all the processes in Integration, Scope, Schedule, Cost, Quality, Resources, Communications, Risk, Procurement and stakeholder management. These serve as navigation aid.
- **Project management plans** - 14+6 templates. These are documents that you edit to do method tailoring.
- **Project Documents** (in the PMBOK sense) - 36 templates. These are the documents to edit during your project, that serve as the project documentation. 



The root folder contains the the super-documents:
- Project charter
- EEF (Enterprise Envinromental Factors) template/reminder/list
- OPA (Organisational Process Assets) template/reminder/list



To start off the navigation, I include:

- Linear list of knowledge areas
- Linear list of process groups and processes



You will find that most (editable) documents are nearly empty or a bare stub. This is intended - these documents are supposed to be starting points for project instance notes, and not a recreation of the PMBOK Guide.  Some documents include references to the PMBOK for further explanation. 

Depending on the project size, you might find that merging some documents into one bigger file is appropriate (tailoring). Likewise, if your project is bigger, you might need additional folders, or that a specialized tool might be better for you.

------


# How to use this

1. Clone the repository or copy the files to your own machine
2. Create a "template" branch and a per-project branch
3. Edit and fill the project documents in your per-project branch
4. Edit templates in the templates branch, and then merge into the per-project branch

You can use e.g. https://obsidian.md/ to keep these as a common, linked system. 


# How to contribute

If you can improve these templates, please do! I accept pull requests.

Edit your templates branch and then create a pull request for the changes that you want to submit only.

Please do not submit the per-project branch with Your project-specific data! I

I will most likely accept all improvements that refer to the original PMBOK 6th Edition. Adaptations and extensions of PMBOK process (e.g. for agile mods) might be acceptable on a case-by-case basis.

# To Do

* Complete list of tools and link them from each relevant process
* Make sure all documents have a reference to PMBOK for further explanations
* Convert the link format to make it navigate-able outside obsidian - preferably by means of a python script
* Adapt to [Readthedocs](<https://readthedocs.org/>) publishing (using [Sphinx](<https://www.sphinx-doc.org/en/master/>))
* Figure out what to do with "lost documents" from the folder "0meta_lost_and_found"
* Publish as downloadable zip
* Create some stats  e.g. 'how many links point to this document'
* Begin using it for my next project

# Progress log



2020-06-15: All processes are now complete. The templates are ready to use, altough more can be done to beautify tools section.

2020-06-14: Navigation for chapter 10 (Communications management), and related content

2020-06-14: Navigation for  chapter 9 (Resource management), content for chapers 9.1 through 9.6

2020-06-13: Large chunk of progress and corrections on the navigation side (processes folder), some 20 still to go. Readability upgrades, links to the PMBOK.

2020-06-12: New processes added, corrections. All documents are in, but detailed links to them from processes in chapters 5-12 are not there yet.

2020-06-11: New processes added, corrections. Some files renamed for easier navigation and consistency.

2020-06-10: Chapter 4 - Project integration - docs complete, links complete. Also, I have pre-added all the "project documents" so there is now 36 of them. Note that some of the documents used later in the project are not mentioned in PMBOK 4.2.3.1 Table 4-1

2020-06-09: Chapter 13 - Stakeholder management - docs complete. Some Tools and Techniques ommited.

---

Created using https://obsidian.md/ - and https://typora.io/ where applicable. The intention is to keep it compatible with https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet



also see https://nvie.com/posts/a-successful-git-branching-model/ and https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow. 


# Disclamer:

This is not a part of the  PMBOK guide, nor a reproduction. These document stubs are original freeware side material.

