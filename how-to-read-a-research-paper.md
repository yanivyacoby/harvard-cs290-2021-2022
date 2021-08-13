---
layout: page
title: How to Read a Research Paper
permalink: /materials/how-to-read-a-research-paper/
---

**About:** 
Reading research papers is challenging; research papers are often **dense**, assuming significant **prior knowledge** about the field and about related work. 
As such, it is important to
1. expect that it will be a **learning process** -- that it might take a while at first, but with practice you will improve! and
2. to adopt and practice **paper-reading strategies**.

In this tutorial, we outline a general strategy for paper reading. 
We hope that you will find it useful, and encourage you to ask your peers, colleagues and mentors for more insights about how they read papers.

**Acknowledgements:** This tutorial is adapted from [Margo Seltzer’s course on OS Research](https://www.seltzer.com/margo/teaching/CS508.21/intro.html) and from  [Weiwei Pan’s course on Stochastic Methods](https://docs.google.com/document/d/1MPEOSairUkktoZmX1N8zcIaENjyirt-JgRfSD-HBymk/edit).


## Paper-Reading Strategies

### Research papers are **not** meant to be read top-to-bottom, like a book. 
* **First, skim.** Focus on the **high-level ideas**, jot down high-level questions you may have about the **story** told by the paper.
* **Then, a deeper read** (if the paper seems relevant). 
* **Don't read top-down -- answer "guiding questions" instead.** For every paper, answer the "guiding questions" below -- answers to these questions will allow you to construct a **story / narrative** the paper is telling.
* **When confused...** You may be missing information assumed to be "commonly known" by the intended research community / audience. We recommend that you try to **fill in the gap** by looking for related papers (e.g. ones cited by the paper you’re reading, ones that share key-terms on google), wikipedia pages, blog-posts, lectures on youtube, etc. There’s no formula here, but going back and forth between reading related material and the original paper of interest can help you get unstuck.

### Stay organized -- keep track of what you’ve already read:
* Save your future-self time and take notes that will help you dig deeper every time you re-visit the paper. 
* Different people find different organizational methods useful, but some common ones are:
  - Taking notes on the paper, underlining, without focus on being neat -- this can help you understand the paper better as you go!
  - Keeping a **searchable doc** online (e.g. Evernote) in which you summarize the paper / answer the paper-reading questions below -- this will help you pick up a paper where you left off.
  - Using a **citation manager** (e.g. Zotero) to keep lists of paper and easily create latex bibliographies -- this will save you time when writing your own paper.
* For every paper, especially focus on recording:
  - The “big ideas”
  - Relevant buzz words
  - Story / narrative (answers to the "guiding questions")

### Ask lots and lots of questions:
* You’re here to **learn** how to read papers and are *not expected to already know how to do it*.
* Reading research papers is challenging: they are often very dense and assume significant prior knowledge about the field and about related work. It is important to ask questions about the paper you read, and actively look for tips about others’ paper-reading strategies! 
* It is expected and normal that when you first start reading research papers in a new field, it will take you several hours to get through a paper. If it takes you a long time to read a paper, you're not alone!


## Guiding Questions

We recommend of thinking of "paper reading" as the process of answering the following guiding questions.
Whether you are skimming or deep-reading, these guiding questions will help you re-construct the narrative told by the paper.
By practicing answering these questions for every paper you read, you will practice quickly honing in on the meaning behind the paper instead of being bogged down by details. 

### What kind of paper are you reading? 
* Big idea 
* Unifying theme 
* Small idea with evaluation (most papers)
* Measurement
* Comparison
* Retrospective or experience paper

### Motivation and Potential Impact 
* What is the problem the paper addresses?
* Why is this problem important?
* Related Work and Contributions 
* How is the problem traditionally solved?
* Why are existing approaches not good enough?
* At a high level, how does the paper address the problem?

### Results (Theory and/or Experiments)
* Theory
  - What are the main theorems in the paper?
  - Is there a new proof technique?
  - At a high level, how do the theorems relate to earlier results?
* Experiments
  - How does the paper define success?
  - How is success measured?
  - What approaches does the paper compare against (and why?)
  - At a high level, what are the results?

### Broader Impact
* Identify the relevant socio-technical systems
  - Where could the technology be deployed, or which kind of technology is informed by the paper (if a theoretical paper)?
  - How would this technology be used?
* Identify the stakeholders
  - Who would be the users?
  - Who would be the affected communities (are these the users)?
* What types of good can this technology do?
  - What kinds of needs do these users/businesses/communities have?
  - What kinds of constraints do these users/businesses/communities have?
* What types of harm can this technology do?
  - What kinds of failures can this technology have?
  - What kinds of direct harm can these failures cause?
  - What kinds of harm can be caused by the broader, socio-technical system?

### What questions do you have? E.g.,
* What “holes” are there in your understanding of the paper’s narrative? (e.g. the paper claims that traditional methods cannot solve the problem, but you don’t see why they don’t suffice? The paper claims the problem is important, but you don’t see why?, etc.)
* What are unfamiliar terms used in the paper that seem important?

### Lastly, what did you learn from the paper?


## How to Critique a Paper

* **The ideas:**
  - Do the ideas make sense?
  - Are the ideas well-motivated?
* **The methodology:**
  - Are the high-level ideas behind the proposed approach / method sound (i.e. do they seem plausible)?
  - If a **theoretical** paper, does the theory presented support the claims of the paper:
    - Are the theorems proved the “right ones” to support the claims? If not, do the authors discuss why they proved this theorem and not another one?
    - Do the proofs appear to be complete, and are they reasonably clear to read?
    - Is the theory adequately situated in the context of the existing literature?
  - If an **experimental** paper, do the results support the claims of the paper:
    - Are the problem instances studied suitably representative? 
    - Do the baselines represent state-of-the art approaches to this problem?
    - Are the evaluation metrics measuring the right things? 
    - Do the experiments provide evidence that it is the innovations introduced in this paper that provide the improved performance?
* Presentation
 - Is the paper well-written?


