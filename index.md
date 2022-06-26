---
layout: default
title: About
---

Welcome to the **Microbial G*enomes* A*nd* M*etagenomes* *to* U*nravel* T*raits* (GAMUT) Lab** at **[Chapman University](https://www.chapman.edu/scst/undergraduate/bs-biological-sciences.aspx)**, led by **Dr. JL Weissman** (starting 2023).

We develop new tools to infer complex microbial traits from environmentally-derived DNA and apply these tools to large datasets in order to assess the distribution of traits across species and environments. In doing so, we hope to answer questions about (1) what microbes are doing/can do in different habitats, (2) which microbes in a habitat perform particular functions, (3) how certain traits may lead to a fitness benefit/detriment in a particular environmental context, and (4) how complex traits evolve across the tree of life.

In order to accomplish these goals, in addition to developing **novel bioinformatics approaches** and **predictive models** to analyze genomic and metagenomic data, we develop **dynamical models** to construct precise hypotheses about trait evolution and collaborate with experimentalists and field biologists to test these hypotheses.

We are always looking for new traits to play with (we are interested in the whole GAMUT of microbial lifestyles, ha ha), but in the past, two traits in particular have grabbed our attention:

## 1. The Maximum Growth Rates of Bacteria, Archaea, and Eukaryotes

**Hey! Does this all seem a bit technical? Check out our article in [Frontiers Young Minds](https://kids.frontiersin.org/article/10.3389/frym.2022.714713) for an explanation of how we use DNA to predict how fast bacteria grow that should be accessible to all ages**

To-date efforts to functionally annotate metagenomes have largely been concerned with reconstructing 
the metabolic potential of communities. While microbial metabolism is incredibly diverse and
an important aspect of functional ecology, microbes are more than just the metabolic pathways
they encode. We have built both genomic predictors and curated trait
databases to help characterize the distribution of
traits like maximal growth rate in natural communities. 

![Maximum Growth Rate](/img/fym_growth_doublingtime.png)

For example, we built a novel [genomic
estimator of maximal growth rate](https://doi.org/10.1073/pnas.2016810118) based on codon usage statistics that outperforms previous methods. 

![gRodon](/img/growth.jpg)

In turn, we used this estimator to
build a comprehensive database of over 200,000 growth rate estimates from genomes,
metagenomes, and single-cell amplified genomes to survey growth potential across the
range of prokaryotic diversity. The distribution of growth potentials suggested a natural divide
between oligotrophs and coptiotrophs, and led us to propose a redefinition of these broad classes of
microbes in terms of their selective environment. Additionally, our database revealed how culture
collections, particularly of marine microbes, are strongly biased towards fast-growing organisms,
with most environmentally-derived genomes on average having much slower predicted maximal
growth rates than cultured isolates, illustrating that the current picture of microbial diversity is
not only incomplete, but also highly skewed. 

We have implemented our growth-rate estimator in a user-friendly R package called [gRodon](https://github.com/jlw-
ecoevo/gRodon2). More recent developments have allowed us to apply gRodon to both
[microbial eukaryotes](https://doi.org/10.1101/2021.10.15.464604), as well as [mixed-species communities of organsisms using metagenomics](https://doi.org/10.1101/2022.04.12.488109).

Moving forward, we hope to leverage large phenotypic datasets to build improved
genomic predictors for a variety of microbial traits - ultimately building an unbiased picture of
microbial form and function in natural environments.

## 2. Microbial Antiviral Defense Systems

**Hey! Does this all seem a bit technical? Check out our article in [Frontiers Young Minds](https://kids.frontiersin.org/article/10.3389/frym.2019.00102) for an explanation of CRISPR immunity that should be accessible to all ages**

Viruses that infect microbes severely impact their hosts’ population and evolutionary dynamics. In an
ecological context, these viruses lead to the release of important nutrients back into the environment and
play a role in maintaining community-level diversity. In an evolutionary context, viruses drive the evolution
of host immune strategy, often leading to iterative co-evolutionary dynamics. In the microbial world these
two contexts are not distinct, with demographic and genetic changes occurring at similar rates, making
any separation of scales infeasible. This is especially true at the interface of viral-host interactions, where
the set of host defense and viral anti-defense strategies is diverse and fast-evolving. Extensive research has
profiled the diversity of host and viral communities, but we know relatively little about the distribution of
host defense and viral anti-defense strategies across environments. 

What drives selection favoring a particular defense strategy? What new defense systems are still waiting to
be discovered? How do defense systems coevolve with pathogens over time, and how does this coevolution
feed back into the dynamics of host-virus interactions? A central theme of our previous and ongoing
work is the application of tools from the fields of machine learning and complex systems science, alongside
more traditional approaches from population genetics and theoretical ecology, to understand the ecology and
evolution of antiviral defense strategies.

For example, the CRISPR adaptive immune system allows microbes to record "memories" of past infection in the form of short viral sequences stored on the host genome:

![CRISPR](/img/crispr.jpg)

CRISPR is found in most groups of microbes, but many organisms lack this immune system:

![Tree](/img/tree.jpg)

Why? If CRISPR is so great why doesn't every microbe have it?

![Question](/img/question.jpg)

We look at how different environments and lifestyles lead to selection for or against particular defense strategies, like CRISPR.

## Synthesis

An outstanding question is how growth potential and antiviral defense strategies are related across organisms, with some of our previous work suggesting that the maximum growth rate of an organism may effect [which antiviral defense genes that organism has](https://doi.org/10.1073/pnas.2016810118) and [whether those genes are beneficial](https://doi.org/10.1098/rspb.2021.1555).

As we add traits to our repertoire, we ask: How do these traits covary across species? Are there major axes of trait variation across microbial species?
