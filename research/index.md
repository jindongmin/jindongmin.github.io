---
layout: page
title:
excerpt: ""
modified: 
image:
  feature:
  credit:
---
I started by working with plants and plastid genomes. I found the coevolutionary dynamices between nuclear and plastid genomes very interesting during my work with plastome structure variations and plant phylogeny. 

After joined nyu, I started to explore more about host-symbiosis interactions in the context of human & microbes.

## Estimating disease similarity with metagenomic data of the human gut

This work was inspired by the observation that individuals with autism spectrum disorder experience higher chance of gastrointesinal disturbances, such as constipation, diarrhea or abdominal pain. Besides, assessing disease similarity is an essential step preceding disease-based approach for drug repositioning. Our study provides a modest first step in underscoring the potential of integrating microbiome insights into the disease similarity assessment. Recent microbiome research has mainly focused on analyzing individual disease to understand its unique characteristics, which by design excludes comorbidities individuals. We analyzed shotgun metagenomic data from existing studies and identified previously unknown similarities between diseases. Our [pipeline](https://www.biorxiv.org/content/10.1101/2024.02.27.582333v1) represents an initial effort that utilize both interpretable machine learning and differential abundance analysis to assess microbial similarity between diseases.

<figure style="text-align: center;">
	<a href="/assets/images/disease_similarity.png">
		<img src="/assets/images/disease_similarity.png"
		alt="image"
		width="500px">
	</a>
  <figcaption>The overall design and data analysis workflow.</figcaption>
</figure>

## Profiling of the disruption of the gut-brain axis in autism spectrum disorder

Gut microbiome has been considered as the second genome in our body due to its significant impact on our health and well-being. Autism spectrum disorder (ASD) is heterogeneous neurological condition that has been implicated to be associated with disruptions in the gut-brain axis ([GBA](https://www.nature.com/articles/s41579-020-00460-0)) although with limited reproducibility across studies.

I worked with [Dr. James Morton,](https://www.simonsfoundation.org/people/james-morton/) [Dr. Gaspar Taroncher-Oldenburg,](https://www.sfari.org/people/gaspar-taroncher-oldenburg/) and [Dr. Richard Bonneau](https://www.simonsfoundation.org/people/richard-bonneau/) on this collaborative project. [This study](https://www.nature.com/articles/s41593-023-01361-0) proposed a Bayesian differential ranking algorithm based framework to leverage multi-omic datasets and investigated how the GBA affects ASD. Within this project, I led the data processing for shotgun metagenomics samples and RNA expression data. We found that microbial profiles are predictive of ASD except in the sibling-matched cohorts. I also did co-cooccurrence analysis to identify candidate viral-microbe interactions. Our results found that *Prevotella copri* and *Bacteroides fragilis* both co-occurred with phages enriched in children with ASD or in neurotypical children. 


<figure style="text-align: center;">
	<a href="/assets/images/dasd.png">
		<img src="/assets/images/asd.png"
		alt="image"
		width="500px">
	</a>
  <figcaption>Held-out gradient boosting ASD classifier performance measured by AUROC.</figcaption>
</figure>

## Plastome structure variations of Malpighiales
[Plastome](https://link.springer.com/article/10.1007/s11103-011-9762-4) plays essential roles in plant biology and functionality. Plastomes of heterotrophic plants are generally highly rearranged, while plastomes of autotrophic angiosperms are relatively conserved. I worked with [Dr. Tingshuang Yi](http://groups.english.kib.cas.cn/GBOS/yts/) and [Dr. Jianjun Jin](https://e3b.columbia.edu/post-doc/jianjun-jin/) at Kunming Institute of Botany, Chinese Academy of Sciences, and investigated structural variations of plastomes in autotrophic angiosperm. We used genome skimming data of species from the order Malpighiales. The Malpighiales is a diverse order comprise one of the largest orders of flowering plants. Some examples of well-known species from this order include cassava, willows, passionfruit, mangosteen, and poplars. We found novel plastid genomic rearrangement events in families including [Hypericaceae, Podostemaceae](https://www.nature.com/articles/s41598-020-66024-7),[Lophopyxidaceae, Putranjivaceae](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2020.00942/full), Caryocaraceae, and Euphroniaceae.

<figure style="text-align: center;">
	<a href="{{ site.url }}/assets/images/AssemblyGraph.png">
		<img src="{{ site.url }}/assets/images/AssemblyGraph.png" 
			alt="assembly graph"
			width = "500px">
	</a>
	<figcaption>The assembly graph of <em>Caryocar glabrum</em> viewed in Bandage. Two paths are supported by reads mapping: A B C D E -C F -D -C -B; -A B C D E -C F -D -C -B. These two paths represent the isomers maintained by the flip-flop recombination mediated by the Inverted Repeats.</figcaption>
</figure>