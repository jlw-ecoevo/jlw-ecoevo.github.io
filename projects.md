
We develop new tools to infer complex microbial traits from environmentally-derived 
DNA and apply these tools to large genomic and metagenomic datasets in order to 
assess the distribution of traits across species and environments. In doing so, 
we hope to answer questions about (1) what microbes are doing/can do in different 
habitats, (2) which microbes in a habitat perform particular functions and whether
microbial communities can be represented as a simplified set of functional guilds, 
(3) how to integrate our genomic trait-based understanding of microbial communities
into ecological and biogeochemical models, and (4) how complex traits evolve across the tree of life.

In order to accomplish these goals, in addition to developing **novel bioinformatics approaches** 
and **predictive models** to analyze genomic and metagenomic data, we develop **dynamical models** 
to construct precise hypotheses about trait evolution and collaborate with experimentalists and 
field biologists to test these hypotheses.

We have made considerable progress towards the above goals by building tools capable 
of resolving a taxon’s multidimensional growth phenotype directly from genomic data. 
Our lab develops and maintains the software [gRodon](https://github.com/jlw-ecoevo/gRodon2), 
a bioinformatic trait-prediction tool that enables the accurate prediction of the maximum growth rate of an organism 
or community directly from its genome or metagenome sequence.


# Below is a sampling of ongoing projects at the mGAMUT Lab:

## Inferring Microbial Traits to Understand a Changing Climate

**TL;DR - We develop computational tools to infer complex microbial traits (i.e., those** 
**that can't be reduced to gene presence/absence) directly from genomic and metagenomic** 
**data in order to better represent these microbes in global biogeochemical models**

![gRodon concept](/img/biogeo_concept.png)

<details>

<summary>Click here for more info</summary>

<p><i>
Hey! Does this all seem a bit technical? Check out our article in
<a href="https://kids.frontiersin.org/article/10.3389/frym.2022.714713">Frontiers Young Minds</a>
for an explanation of how we use DNA to predict how fast bacteria grow that should be accessible to all ages
</i></p>

<p>DNA sequencing costs have dropped precipitously 
over the last two decades and it has become routine to collect, sequence, and analyze 
environmental metagenomes – even from highly complex environments like soils. Yet, 
we currently lack the ability to turn these rich datasets into ecologically relevant 
insights on microbial traits and environmental preferences and to capture how the behaviors 
of environmental microbiomes will feed back into the broader earth system. Our ability 
to genomically survey microbial traits in situ is limited at best and is largely 
restricted to analyzing the presence or absence of particular metabolic pathways 
across metagenomes.  The next generation of bioinformatic software for probing 
microbiome dynamics will need to resolve complex microbial traits, beyond gene 
presence or absence, to build a comprehensive understanding of how microbiomes 
modulate global biogeochemical cycles. The long-term goal of my group’s work is 
to reliably link genomic information to emergent community properties via ‘omics-based 
inference of complex traits and life-history strategies. </p>

<p>A specific area of emphasis for us is understanding the dynamics of microbial communities
in thawing permafrost soils. Permafrost soils 
worldwide store approximately 50% of global soil carbon, and the microbes that consume this carbon
when permafrost thaws have the potential to reshape carbon dynamics across our planet. Yet, the specifics of how 
communities of permafrost microbes respond to thaw and the factors that contribute 
to an organism’s success during this process remain largely undetermined. This ongoing work is funded by the 
<a href="https://www.nsf.gov/awardsearch/show-award?AWD_ID=2546537">National Science Foundation</a>.</p>


<p>We also are working to leverage our trait-inference approaches for data integration with ocean biogeochemical
models. This ongoing work is supported in part by our collaboration
with the <a href="https://ccomp-stc.org/">Chemical Currencies of a Microbial Planet (C-CoMP)</a> NSF Center.</p>

</details>

&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;

## Inferring Microbial Traits to Predict the Dynamics of the Human Microbiome

**TL;DR - We develop new AI/ML-based methods for trait inference in human microbiomes.** 
**We will leverage these trait inference methods to subsequently build and parameterize mathematic models** 
**of microbiome dynamics to predict how the composition of individual microbiomes will change in response to perturbation.** 

![growth signatures](/img/growth_signatures.png)

<details>

<summary>Click here for more info</summary>

<p>
The long-term goal of our group’s work is to reliably link genomic information to 
emergent microbial community properties via inference of complex traits and life-history 
strategies at the community level. In doing so, we aim to address a major challenge in microbiome sciences, 
that of developing a mechanistic understanding of the dynamics of host-associated microbiomes. 
Increasingly, researchers studying the human microbiome are generating high-resolution time-series 
data to capture community turnover in response to environmental perturbations (e.g., antibiotic use, 
infection, cancer treatment). Yet, the high-dimensional nature of the microbiome, which comprises 
hundreds or thousands of taxa, resists easy description by existing ecological modeling frameworks. 
To bridge this gap, we propose to develop a mechanistic, trait-based understanding of microbial dynamics, 
asking whether differences in the predicted growth strategies and environmental preferences of individual 
organisms in a community can be used to inform ecological models of bacterial community dynamics 
in response to perturbation. 
</p>

<p>This ongoing work is funded by the National Institutes of Health (NIGMS R35).</p>

</details>

&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;


## Microbial Antiviral Defense Systems

**TL;DR - We combine mathematical models with comparative genomics to better understand the forces shaping the evolution of anti-viral defenses in microbes**

![Defense](/img/immune_approaches.png)

<details>

<summary>Click here for more info</summary>

<p><i>
Hey! Does this all seem a bit technical? Check out our article in 
<a href="https://kids.frontiersin.org/article/10.3389/frym.2019.00102">Frontiers Young Minds</a>
for an explanation of CRISPR immunity that should be accessible to all ages
</i></p>

<p>Viruses that infect microbes severely impact their hosts’ population and evolutionary dynamics. In an
ecological context, these viruses lead to the release of important nutrients back into the environment and
play a role in maintaining community-level diversity. In an evolutionary context, viruses drive the evolution
of host immune strategy, often leading to iterative co-evolutionary dynamics. In the microbial world these
two contexts are not distinct, with demographic and genetic changes occurring at similar rates, making
any separation of scales infeasible. This is especially true at the interface of viral-host interactions, where
the set of host defense and viral anti-defense strategies is diverse and fast-evolving. Extensive research has
profiled the diversity of host and viral communities, but we know relatively little about the distribution of
host defense and viral anti-defense strategies across environments.</p>

<p>What drives selection favoring a particular defense strategy? What new defense systems are still waiting to
be discovered? How do defense systems coevolve with pathogens over time, and how does this coevolution
feed back into the dynamics of host-virus interactions? A central theme of our previous and ongoing
work is the application of tools from the fields of machine learning and complex systems science, alongside
more traditional approaches from population genetics and theoretical ecology, to understand the ecology and
evolution of antiviral defense strategies.</p>

</details>

&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;

## Metagenomics with Community Biologists in NYC 

**TL;DR - Our lab frequently collaborates with Genspace, a community biology laboratory in Brooklyn, NY to study microbial communities around the city.**

![Oysters](/img/bush_terminal.png)

<details>

<summary>Click here for more info</summary>

<p>In one recent project, we collaborated with the Billion Oyster Project and GenSpace, 
a community biology laboratory also based in Sunset Park, to coordinate volunteer-led 
sampling and processing of a microbial metagenomic time series from waters in and 
around the Bush Terminal Piers Park. Bush Terminal Park is a quiet community park 
nestled in an industrial area of Sunset Park, Brooklyn, a historically working-class 
immigrant neighborhood. This waterfront park, developed on a former brownfield, 
is subject to storm- and sea level rise-related flooding, is a social and environmental 
amenity for area residents, and, in combination with efforts to rezone nearby industrial 
areas for mixed-use development, is impacted by the contested forces of gentrification. 
Notably, this park is already an active site of ecological research. The Billion Oyster 
Project, a community organization building artificial oyster reefs across the New York Harbor, 
has an active community-maintained reef in a lagoon at this site and plans to build another.</p> 

<p>Our project was funded by Con Edison and 
<a href="https://experiment.com/projects/predicting-the-impact-of-billion-oysters-on-microbially-driven-biogeochemical-cycling-in-new-york-city-waterways">Experiment.com</a>
to coordinate sampling of microbial communities living near these reefs.</p>

<p>Our work with Genspace continues to be funded by Con Edison, specifically a project
working with urban seaweed and their microbiomes. Our recent permafrost NSF grant also funds
community science-art programming at Genspace.</p>

</details>

&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
