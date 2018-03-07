---
layout: post
title: Interactive vs. Non-interactive tests
subtitle: What template should I select?
tags: [books, test]
---

The toolkit will include tests that are both interactive and non-interactive. 
The simplest tests, **non-interactive tests**, present some part of a dialog for worker evaluation. We want these to be as easy as possible to run.  Given a dialog log format, the experiment designer selects the set of turns and the context they wish to present, perhaps with optional follow up replies. Then a website automatically becomes available and, given a userid, presents the examples in randomized order and collects the necessary statistics. Thus, for example, if Jane wants to use a well-defined measure, such as acceptability of system utterances, she could quickly get 50 workers to see 20 different examples in randomized order and collect their agreement on the acceptability of these utterances. DialCrowd will simply make it easy to run it as a web app for direct use on a crowdsourcing site.

**Interactive tests** ask the worker to actually interact with a dialog system. There may be scenario instructions, and/or constraints on the worker’s interactions. There will probably be different conditions for each dialog class. Again the Toolkit will make it easy to run 50 users through 10 scenarios with 3 different conditions by creating the web front end, collecting the data, and keeping track of which worker has done what. Beyond these two types of tests, we will eventually find other types that enable more novel studies. They will be added as needed.
