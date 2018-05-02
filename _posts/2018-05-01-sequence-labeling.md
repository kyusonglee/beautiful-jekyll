---
layout: post
title: Sequence Labeling
subtitle: How to setup non-interactive tests in DialCrowd Admin
tags: [sequence labeling, crowdsourcing, name entity recognition]
---

-  **Goals and Expectations:** The goal of this crowdsourcing feature is to categorize different types of entities. After entering the website of sequence labeling, the worker will be asked to select specific words or a phrase in a sentence and choose the corresponding type of entity that phrase can be categorized into to using the buttons below the sentence. If the worker is not sure which type of entity it belongs to, choose "other".

# Sequence Labeling
![Image](../img/noninteractive1.png)
**Figure 1**
Figure 1 shows an overall process of creating a project of sequence labeling using DialCrowd:

- First, select a type of evaluation: non-interactive testing.
- Second, choose "Sequence Labeling"
- Third, click the "New Project" button and name the new project. Please also input your name and set the password.
- Finally, if you successfully create the "New project", you will see your project in the table. Please click the enter (edit) icon to start. We provide several examples that you can follow.

![Image](../img/noninteractive2.png)
**Figure 2**

## (1) Basic information 
In order to setup a new sequence labeling project, requesters need to fill out the following information:
```
ex)
- Generic Introduction: Please select one of dialog acts.....
- Number of task per HIT: 10
- Number of sentence per task: 5 
- Number of worker per sentence: 3
```
The above example indicates that 5 sentences will be shown to workers per page. They have to finish 10 pages. Thus, a worker has to annotate total 50 sentences (Number of task per worker(10) * Number of sentences per page(5)= 50). (Number of worker per sentence: 3) mean one sentence will be annotated by 3 workers. 


## (2) Upload your data
The data can be uploaded by uploading a .txt file that contains the sentences for the workers to analyze using sequence labeling.
```
Has onihime vs been made into an anime
What percent of 25 is 23
What does C K mean
How do you say eggs with bacon and toast in spanish
Is cat litter safe for concrete to melt ice
U-235 and Pu-239 are both what
Did Hannibal Lecter kill Allegra Pazzi
```

## (3) Add Class
You need to define class categories (e.g., inform, request, confirm, etc) and example sentences for workers.  
These exmaples will be shown in DialCrowd Workers. 

## (4) Save your project
## (5) Test and deploy
You can download the format for uploading your data. You can preview the DialCrowd Worker's website.





