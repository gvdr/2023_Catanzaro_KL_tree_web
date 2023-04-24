# Introduction

Species communities, in their composition and structure, are the outcome of both ecological and evolutionary processes.
Darwin's remark about _endless forms most beautiful and most wonderful_ can easily be extended to food webs and the intricated nature of species interactions.
Indeed, the network nature of species communities is a costitutive component of biodiversity.
That is, different ecosystems differ not only in the identity and abundance of species that compose them but, also, in the web of mutual dependencies, cooperation, and competition that those species draw.

Yet, because of the complexity of the information we deal with when we handle networks, the network facet of biodiversity, and its dependency on ecological and evolutionary processes, it's still largely unexplored. Even the fundamental task of assessing how much the evolutionary history of a community of species is reflected in the set of its ecological interactions has not found a satisfactory methodological answer. In particular, while the _bipartite_ case---where species can be assigned to two distinct groups---has been treated in more extent,for the _unipartite_ case---say, food webs---we don't have convincing macro-evolutionary, mechanistic model of network temporal change (not a consensus one, at least). The lack of sucha model, and even more the lack of easily available data (that is, assembled phylogenies for food webs), made it hard to explore the evolutionary signature of food webs.

It is, then, not surprising that more refined questions, such as a stricter or loser adherence to the evolutionary signature of individual species---that is, do species play the ecological role we expect them to play given their evolutionary history?---are unanswered. We claim that these questions, both at species and community leve, would enrich our view of biodiversity, complementing assessment in terms of evolutionary distinctiveness.

Here, we introduced a robust and computationally performing framework to investigate the evolutionary signal of food webs, and assessing individual species contribution, building on Information Theory and a statistical model of complex networks, namely Random Dot Product Graphs. Doing this, we introduced a notion of eco-evolutionary surprise: we quantify how much additional information the observation of a food web (and, at the species level, the realised interactions of a species) we gain, if we already knew the evolutionary history of the species in the food web.

Random Dot Product Graphs simplify the study of complex network by representing them as low dimensional embeddings: nodes are mapped to points in a pair of metric space---that is, geometric spaces where pairwise distances are meaningful; interaction probability are then encoded by distances between points.
This framework is well established in the statistical literature, and proved successfull for link prediction in bipartite networks.
The modelling of unipartite ecological networks, and in particular food webs, through low dimensional embeddings has shown to offer valuable insight for the ecologist.
In particular, Dalla Riva and Stouffer showed that XXX.
Later, a fruitful connection with phylogenetics was showcased by Strydom et al.
In fact, Strydom et al. proved that ecological interaction information can be transfered, through a common phylogeny, from the embedding of an observed food web, to the embedding of an unobserved one, so predicting whole communities food web structure.
This latter result is underpinned by a _compatibility_ of the network structure and phylogenetic histories.
More than that, the result was obtained by assuming a simplistic model for the evolution of network interactions, namely, a branching Brownian motion.
That is, a model of evolution where lineages evolve without any interaction: not a strong candidate for the evolution of ecological interactions.
Yet, the empirical success suggest the presence of a signal strong enough to be detectable even under a wrongly specified (but useful) model.

Information theoretical approaches are not new in phylogenetic.
Catanzaro et al. showed that the tree reconstruction under the assumptions of _Balanced Minimum Evolution_ corresponds to a _cross-entropy_ minimization problem.

Building on these ideas, we quantify the surprise of a ecological network given a phylogenetic tree as XXX.
In addition, the surprise of a species is given by the species contribution to the surprise of the ecological network.
And we interpret the surprise of a species as the amount of additional information provided by the species ecological interaction, given its phylogenetic history.

Here, we focus on unipartite food webs and phylogenetic trees.
However, the generalization to phylogenetic network, and the case of bipartite webs is possible.

# Methods

From phylogeny to distance matrix to distribution.

From ecological networks to distance matrix (through RDPG) to distribution.

Compute Dkl of the two distributions.

Permanova by reshuffling tips on tree.

Decomposition on species level.

Figure 1: diagram of method.

# Data

Tanzania National Park

Marine food webs 

# Results

Tanzania National Park

Tanzania Surprising Species

Figure 2: permanova test || suprise of species || inlet of most suprising species.

Marine food webs 

Marine surp spec

Figure 3: permanova test || suprise of species || inlet of most suprising species

# Conclusion

# References
