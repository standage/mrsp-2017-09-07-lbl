---
title: "Introduction"
teaching: 15
exercises: 10
questions:
- "What are the key differences between research software and 'normal' projects?"
- "What does 'done' look like for a research software project?"
- "What are the goals of this class?"
objectives:
- "Compare and contrast research software projects and 'normal' software projects."
- "Name and explain key features of a mature research software project."
keypoints:
- "Requirements for small research software projects are typically emergent."
- "Research software is 'good enough' when people other than its authors can use it with confidence and extend it with reasonable effort."
---

## Overview

*   Scientific disciplines across the board are becoming more compute intensive
    *   modeling, simulation, data analysis, data management
*   Few scientists have any formal training in programming
*   Much more to a research software project than just code:
    *   Data
    *   Organization
    *   Communication
    *   Process
*   This class will discuss:
    *   What a research software project needs to achieve its goals
    *   How to go from ad hoc solo project to reliable small-team project

## Key differences between research software and "normal" projects

*   Requirements may be either:
    *   Discovered as we go along (exploring)
    *   Relatively stable (engineering)
*   Problem is *subtle* as well as *complicated*
    *   Control flow may be very simple...
    *   ...but figuring out exactly what coefficients and indexes to use can be very hard
*   Staff are often [research software engineers][what-is-rse] (RSEs)
    *   Combine expertise in programming with an in-depth understanding of research
    *   Typically have:
        *   An advanced degree in a research discipline
        *   Lots of experience developing software (often acquired while working on their thesis)...
        *   ...but little or no formal training in software engineering
    *   "The astronomers who build telescopes so that others can study stars"

## What does "done" look like?

1.  Software can be used by people other than original authors
    *   Reproducibility meaningless without this
2.  Reasonably confident that results are correct
    *   As trustworthy as physical experiment
3.  Small changes and extensions are easy
    *   I.e., researchers can safely make small changes to code
4.  Fast enough to be useful
5.  Can be maintained by people other than its original author(s)
    *   I.e., it is *sustainable*
6.  Has a citable publication described in an easy-to-find way
    so that users can credit the project in an academically-digestible form

## For our purposes:

*   3x6: three people for six months
*   Contributors are frequently time-slicing other projects
*   "Everybody makes coffee"

> ## Create a Value Proposition for Your Project
>
> Fill in the template below for your current project.
>
> 1.  For *[description of target users*]
> 2.  who want to *[statement of their need(s)]*,
> 3.  *[project name]*
> 4.  provides *[statement of key benefits]*.
> 5.  Unlike *[name of alternative solutions(s)]*,
> 6.  our project enables users to *[key differentiator]*.
{: .challenge}

> ## Describe How Your Project is Managed
>
> Write a short point-form description (5-6 bullets) of how your current project is managed:
>
> 1.  Who uses the software?
> 2.  How?
> 3.  How do they find the software?
> 4.  How do they set it up?
> 5.  Who decides what to change and when?
> 6.  How are decisions and changes circulated?
{: .challenge}

{% include links.md %}
