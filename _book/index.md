--- 
title: "Evaluating and conducting intervention studies: a guide for speech and language therapists"
author: "Dorothy V.M. Bishop and Paul A. Thompson"
date: "2020-01-31"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
description: "Introduction to methods for evaluating effectiveness of interventions in medical related fields"
---

# Preface {-}

## Why did we write this book? {-}

Methods for evaluating effectiveness of interventions have been developed in the field of medicine, where practitioners who wish to run clinical trials typically have access to expert statisticians and methodologists. However, in many fields, professionals with expertise in administering interventions have little or no training in research design and statistics. 

The idea for this book was prompted by DVMB attending a conference on interventions for children with developmental language disorders. As the meeting there were many committed practitioners who were passionate about trying to improve outcomes for these children, and who wanted to engage in studies to show that their interventions were effective. However, all too often they did studies in a way that could not show the effect they were interested in, and conclusions about the benefits of their interventions seemed over-optimistic. DVMB realised that the dedication and skill of these practitioners was not matched by a deep understanding of the difficulties of intervention research; in particular, the clinical training of these professionals did not usually include adequate instruction in basics of research methodology and statistics. It seemed, therefore that there was a need for a basic text that would explain the pitfalls of intervention research, as well as providing a template for good practice in the evaluation and design of intervention studies.

As we shall see, demonstrating that an intervention has an impact is much harder than it appears at first sight. There are all kinds of issues that can arise to mislead us into thinking that we have an effective treatment when this is not really the case. Much of the attention of methodologists has focused on how to recognise and control for unwanted factors that can affect outcomes of interest. But, as a psychologist, DVMB is also particularly interested in our own human biases that can be just as important in leading us astray. Good, objective intervention research is vital if we are to improve the lot of those we work with, but it is really difficult to do well, and to do so we have to overcome our natural impulses to interpret evidence in biased ways.

## Who is this book for? {-}

Although the inspiration for the book came from interactions with speech and language therapists, and the illustrative cases are from that discipline, the basic principles covered here are relevant for any field where a practitioner aims to influence outcomes of those they work with. This includes those working in professions allied to medicine and education.

## What is covered? {-}

Our main goal is to instil in the reader awareness of the numerous sources of bias that can lead to mistaken conclusions when evaluating interventions. Real-life examples are provided with the aim of providing an intuitive understanding of these issues. 

We expect that many readers will have little or no background in statistics. Lack of statistical training is a massive obstacle to practitioners who want to do intervention research: it not only makes design and analysis of a study daunting, but it also limits what a potential researcher can take from the existing literature. This book should be seen as complementing rather than substituting for a technical introduction to statistics. Many readers may be reluctant to study statistics in more depth, but it is hoped that the account given here will give them confidence to approach statistics in the published literature with a more critical eye, to recognise when the advice of a professional statistician is needed, and to communicate more effectively with statisticians.

Having said that, we hope that at least a subset of readers will consider engaging with the exercises that we have included using the programming language R. These are optional and the book has been written to be comprehensible without needing to learn any programming skills. But I think you will take more away from it if you do learn some 'coding' – as the experts call it.

R has the advantage of being free to download, and there is a huge community of R users, which means that you can Google any question you might want to ask about it, and you are likely to find that someone has answered it. R is not, however, easy to learn, and it can be off-putting on first encounter. The huge advantage of R over more familiar and user-friendly statistics packages is that is that it is fairly easy to simulate data – that is, to generate artificial data with particular properties. For example, you could generate fictitious results from two groups  - one who had an intervention and one who didn't. That probably seems like an odd thing to want to do – surely what you need is real data! The reason for doing it should become more apparent as you proceed through the exercises. With simulated data you can see the effects of the various biases that we will consider.  For instance, you can see how easy it is to get a false positive 'significant' result if you run a large number of statistical tests on the same sample. And you can see how it is possible to mistakenly conclude that an intervention is ineffective if you use too small a sample size in a study. 

Intervention research is a branch of science, and you can't do good science without adopting a critical perspective – to the research of yourself as well as others. We hope this book will make it easier to do that and so to improve intervention research in speech and language therapy as well as other fields. 

Dorothy Bishop \& Paul Thompson
