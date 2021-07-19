---
layout: default
title: About
---

## Research Themes 

### An Ongoing Battle Between Microbes and Their Viruses

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
feed back into the dynamics of host-virus interactions? The central theme of my previous and ongoing
work is the application of tools from the fields of machine learning and complex systems science, alongside
more traditional approaches from population genetics and theoretical ecology, to understand the ecology and
evolution of antiviral defense strategies.

### Trait-Based Analysis of Natural Microbial Communities

To-date efforts to functionally annotate metagenomes have largely been concerned with reconstructing 
the metabolic potential of communities. While microbial metabolism is incredibly diverse and
an important aspect of functional ecology, microbes are more than just the metabolic pathways
they encode. For example, even in the context of growth, extremely broad distributions of minimal doubling
times are observed for microbial species with similar metabolic capacity (from under ten minutes
to multiple days). I have built both genomic predictors and curated trait
databases to help characterize the distribution of
traits like maximal growth rate in natural communities. 

[Most recently I built a novel genomic
estimator of maximal growth rate based on codon usage statistics that outperforms previous methods, including in a community context where I implemented 
a novel species abundance correction for metagenomes.](https://doi.org/10.1073/pnas.2016810118) In turn, I used this estimator to
build a comprehensive database of over 200,000 growth rate estimates from genomes,
metagenomes, and single-cell amplified genomes to survey growth potential across the
range of prokaryotic diversity. The distribution of growth potentials suggested a natural divide
between oligotrophs and coptiotrophs, and led me to propose a redefinition of these broad classes of
microbes in terms of their selective environment. Additionally, my database revealed how culture
collections, particularly of marine microbes, are strongly biased towards fast-growing organisms,
with most environmentally-derived genomes on average having much slower predicted maximal
growth rates than cultured isolates, illustrating that the current picture of microbial diversity is
not only incomplete, but also highly skewed. I
have implemented my growth-rate estimator in a user-friendly R package called [gRodon](https://github.com/jlw-
ecoevo/gRodon). 

Moving forward, I hope to leverage large phenotypic datasets to build improved
genomic predictors for a variety of microbial traits - ultimately building an unbiased picture of
microbial form and function in natural environments.

### Background and Education

**As of March 2020 I'm a [Simons Foundation Postdoctoral Fellow in Marine Microbial Ecology](https://www.simonsfoundation.org/grant/simons-postdoctoral-fellowships-in-marine-microbial-ecology/?tab=awardees) in the [Fuhrman Lab](https://dornsife.usc.edu/labs/fuhrmanlab) at USC.**

Previously, I defended my PhD in [Behavior, Ecology, Evolution, and Systematics  (BEES) at the University of Maryland College Park](https://www.bisi.umd.edu/bees-1) coadvised by [Philip LF Johnson](http://science.umd.edu/biology/plfj/) (population genetics) and [Bill Fagan](http://science.umd.edu/biology/faganlab/) (theoretical ecology). I was a [COMBINE network science fellow (NSF)](https://www.combine.umd.edu/), and before that a [GAANN fellow](https://www2.ed.gov/programs/gaann/index.html) in mathematical biology (US Dept. Ed.).
My graduate training was broadly interdisciplinary with a heavy computational and theoretical emphasis, and I was lucky to have the opportunity
to attend summer schools in [Complex Systems Science at the Santa Fe Institute](https://wiki.santafe.edu/index.php/Complex_Systems_Summer_School_2017) and in
[Microbial Diversity at the Woods Hole Marine Biological Laboratory](https://www.mbl.edu/microbialdiversity/).

I received a BA in mathematics and biology from [Bard College](https://www.bard.edu/) in 2015 with a [senior thesis](https://digitalcommons.bard.edu/senproj_s2015/39/) advised by [Bruce Robertson](https://www.bard.edu/faculty/details/?id=3226) (biology) and [Csilla Szabo](https://www.skidmore.edu/mathematics/faculty/szabo.php) (mathematics). As an undergraduate, I
performed research under the supervision of faculty at Bard College, the [Virginia Bioinformatics Institute](http://systemsmedicine.pulmonary.medicine.ufl.edu/profile/laubenbacher-reinhard/), the [Arizona State University Mathematics Department](https://math.la.asu.edu/~milner/welc_eng.html), and the [Kavli Institute for Cosmological Physics at the University of Chicago](https://www.cmu.edu/physics/people/faculty/dodelson.html).

