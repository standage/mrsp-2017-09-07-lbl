---
title: "Compromise"
teaching: 20
exercises: 0
questions:
- "How can I improve my project's development processes without becoming overwhelmed?"
- "Under what circumstances can I suspend best practices?"
objectives:
- "Describe the concept of technical debt."
- "Discuss strategies for principled compromises in software development best practices."
keypoints:
- "Technical debt must often be accrued to get a project off the ground, but must eventually be paid down for a project to grow."
- "Use rapid iterative development to bring a project up to a minimally viable standard."
- "Software engineering best practices are not a goal unto themselves, but means to an end."
- "Ensure the scientific core of your project is sound. Otherwise, fix bugs when they come along, and then get back to science."
---

*   "Technical debt"
    *   dissonance between (constantly refining) conceptual model and the model reflected in code
    *   informed, deliberate suspension of best practices
    *   term popularized by lean startup culture
*   Constant tradeoff
    *   usually necessary to get a project off the ground
    *   complicates sustained development
        *   debt must be paid down
        *   with interest!
*   None of these best practices are a goal unto themselves!
    *   They are means to an end
    *   What are the ends of your project? This will depend on whether the software is
        *   one-time-use code supporting a single research project
        *   a generalized tool for analyzing particular types of data sets
        *   a software library supporting new analytical and methodological developments in a problem domain
    *   Regardless, in science, priorities should be:
        *   accuracy
        *   performance
        *   ...
        *   ...
        *   ...
        *   user experience (we're not building dating apps here)
*   Rapid iterative development strategy
    *   build a quick prototype
    *   evaluate accuracy
    *   if performance is unsatisfactory
        *   profile performance empirically
        *   optimize code surgically
    *   clean up code
*   Incremental improvement
    *   don't try to FIX ALL TEH THINGS AT ONCE!
    *   instead, whenever you touch a function to fix or extend it, clean it up then
        *   check for code clarity
        *   improve documentation and comments
        *   write unit tests
    *   improvements will accumulate quickly
*   Summary: compromise on best practices if you must
    *   but not on version control
    *   and not on automated testing
    *   be deliberate
        *   this is not an excuse to avoid learning or implementing best practices
        *   just be mindful of whether they are helping you toward or distracting you from your highest priorities
*   Winning strategy: stupidity-driven development
    *   Write lots of tests for the scientific core of the code
    *   Start with many fewer tests for everything else
    *   When a bug is encountered
        *   write a new regression test to reproduce the bug
        *   fix the bug
        *   get on with more important things
    *   Mantra: avoid wasting time writing tests for bugs that will never appear!

{% include links.md %}
