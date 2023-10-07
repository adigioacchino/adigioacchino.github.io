+++
title = "Research"
+++
@def tags = ["syntax", "code"]

# Research interests
The guiding principle of my research activity is the **interdisciplinarity**: in most of my research efforts, I use ideas and techniques developed in the context of **statistical physics** to model problems coming from different research areas.

As a first example, during my PhD I focused on **combinatorial optimization problems**, and in particular how the embedding on problems in low-dimensional Euclidean space (such as in 1 or 2 dimensions) affects the statistical properties of the solutions.

Then, during my first year of postdoc, I moved toward biological applications and in particular **computational approaches to molecular biology**. This led me to learn how to build **data-driven models** and how to obtain their parameters with **Bayesian inference** techniques, tools which I consider now a central feature of my profile as a researcher.

Successively the main focus of my research shifted towards exploring effects of **virus-host interactions** at the level of their genomes, on topics such as the evolution of the nucleotide usage of viruses after **host shifts**, the determination of nucleotide patterns in viruses recognized by the host **immune system**, and the discovery of **virus-associated molecular patterns** in the human genome.

More recently I started working on viruses of bacteria, the so-called bacteriophages or phages, and on machine learning methods to design optimal phages and phage cocktails for **phage therapy**.

# Publications
Here I list my scientific publications, whether they are actually published in peer-reviewed journals or only available in preprint servers. 

For each paper I also try to explain briefly what we did and why. 

---------------------
* **_Designing molecular RNA switches with Restricted Boltzmann machines_**, in collaboration with _Jorge Fernandez-de-Cossio-Diaz, Pierre Hardouin, Francois-Xavier Lyonnet du Moutier, Bertrand Marchand, Yann Ponty, Bruno Sargueil, Remi Monasson_, and _Simona Cocco_, available in [*bioRxiv*](https://www.biorxiv.org/content/10.1101/2023.05.10.540155.abstract).
    > Machine learning tools can be used to discover meaningful patterns in biological sequences, such as RNA molecules, that are related to the molecule functions. In this work we show how to use a specific type of machine learning tool, called Restricted Boltzmann Machines, to design RNA molecules that can switch between two different structures, and we show that the designed molecules are able to perform the desired function in vitro. 

---------------------
* **_Repeats Mimic Pathogen-Associated Patterns Across a Vast Evolutionary Landscape_**, in collaboration with _Petr Šulc, Alexander Solovyov, Sajid A Marhon, Siyu Sun, Håvard T Lindholm, Raymond Chen, Amir Hosseini, Hua Jiang, Bao-Han Ly, Parinaz Mehdipour, Omar Abdel-Wahab, Nicolas Vabret, John LaCava, Daniel D De Carvalho Rémi Monasson, Simona Cocco_, and _Benjamin D Greenbaum_, available in [*bioRxiv*](https://www.biorxiv.org/content/10.1101/2021.11.04.467016v2.abstract).
    > In this work we analyze the human genome using statistical-physics inspired computational tools to detect regions (which in most cases are in the so-called "non-coding genome") that have viral-like patterns, and that could play a role in interacting with the innate immune system. We also discuss their evolution within and outside the human genome, pointing out cases where possibly immunogenic patterns seems to be conserved during genome evolution or across organisms. 

---------------------
* **_A transfer-learning approach to predict antigen immunogenicity and T-cell receptor specificity_**, in collaboration with _Barbara Bravi, Andrea Di Gioacchino, Jorge Fernandez-de-Cossio-Diaz, Aleksandra M Walczak, Thierry Mora, Simona Cocco_, and _Rémi Monasson_, published in [*eLife*](https://elifesciences.org/articles/85126) on 2023 (open access).
    > In this work we show how to use an implementation of transfer learning using Restricted Boltzmann Machines to analyze the changes between two datasets, and we apply this idea to predict antigen immunogenicity and T-cell receptor specificity, two well-known open problems in immunology.

---------------------
* **_Generative and interpretable machine learning for aptamer design and analysis of in vitro sequence selection_**, in collaboration with _Jonah Procyk, Marco Molari, Jonh S Schreck, Yu Zhou, Yan Liu, Rémi Monasson, Simona Cocco_, and _Petr Šulc_, published in [*PLoS Computational Biology*](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1010561) on 2022 (open access).
    > Aptamers are small DNA or RNA molecules selected in the lab to interact specifically with some relevant protein. For instance [thrombin-binding aptamers](https://en.wikipedia.org/wiki/Anti-thrombin_aptamers) have been developed and tested as anti-coagulant agents to be used during surgery. In this work we show how, using machine learning, we are able to better understand the results of the experiments done to obtain new aptamers, and that we can use this added knowledge to design new aptamers with the wanted properties. 

---------------------

* **_sgDI-tector: defective interfering viral genome bioinformatics for detection of coronavirus subgenomic RNAs_**, in collaboration with _Rachel Legendre, Yannis Rahou, Valérie Najburg, Pierre Charneau, Benjamin D Greenbaum, Frédéric Tangy, Sylvie van der Werf, Simona Cocco_, and _Anastassia V Komarova_, published in [*RNA*](https://rnajournal.cshlp.org/content/28/3/277.short) on 2022 (open access).
    > SARS-CoV-2, as other coronaviruses, has a complex mechanism to translate its genetic code into proteins, that results in many sub-populations of fragments of viral genome (subgenomic RNAs), which are replicated and translated independently from each other. Is it possible to detect these fragments and to quantify their expression level from the sequencing data coming out of infected cells? In this work, we took a pre-existing bioinformatic tool (DI-tector) and modified it to accomplish this task. We show that the resulting algorithm, sgDI-tector, works as well as other state-of-the-art approaches (and sometimes better), and we made the software publicly available to help other research groups in detecting subgenomic RNAs.

---------------------

* **_The heterogeneous landscape and early evolution of pathogen-associated CpG dinucleotides in SARS-CoV-2_**, in collaboration with _Petr Šulc, Anastassia V Komarova, Benjamin D Greenbaum, Rémi Monasson_, and _Simona Cocco_, published in [*Molecular Biology and Evolution*](https://academic.oup.com/mbe/article/38/6/2428/6130826) on 2021 (open access).
    > Viruses and hosts evolve together, modifying their genetic code and adapting it to the changing environment. This process takes tens to hundreds of years and it is particularly apparent when a virus jumps from an host to another. A well-known example is the usage of cytosines followed by guanines in the genome: humans have a surprising low number of these short motifs (called CpG motifs) in their genome, and can detect as external any genome with too many CpG motifs. For this reason, if a virus jumps into human hosts, it must have a low enough number of CpG motifs, and it will adapt by loosing more and more such motifs. In this work, we discuss this virus-host interaction for SARS-CoV-2, and exploit the incredibly large public database of viral genomes to show that, in genomic regions with high level of CpG motifs, the adaptation process of the virus to the human host had immediately begun. 

---------------------

* **_Perils of embedding for sampling problems_**, in collaboration with _Jeffrey Marshall_ and _Eleanor G Rieffel_, published in [*Physical Review Research*](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.2.023020) on 2020 (open access).
    > Quantum annealer are analog quantum computers (that is, computers exploiting directly quantum phenomena to perform computations) that have been proposed as a tool to solve more efficiently hard combinatorial optimization problem. More recently, they have also been proposed as tools to _sample_ from probability distributions, a known very hard problem in its most general setting. The quantum annealers that we have now, however, need a specific preprocessing called _minor embedding_ to deal with arbitrary problems, that can introduce errors as ambiguities in the sample obtained. While many works have focused on how to mitigate these errors when the objective consists in solving a combinatorial optimization problem, here we focus on the case of sampling. We show that the errors introduced through embedding are expected to be very relevant in the case of sampling, especially for large interesting problems. Moreover, we suggest an empirical procedure involving a post-processing through classical (as opposed to quantum) hardware to mitigate these issues. 

---------------------

* **_Large deviation of the free energy in the p-spin glass spherical model_**, in collaboration with _Mauro Pastore_ and _Pietro Rotondo_, published in [*Physical Review Research*](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.1.033116) on 2019 (open access).
    > In statistical physics of disordered systems the focus is typically on estimating average values of relevant observables of the system for relevant values of the parameters. Here we used the technical tools developed for spin glasses together with the theory of large deviations to describe fluctuations far away from the average values, in the pedagogical case of the spherical p-spin model. In an attempt to better understand the approximations and assumptions usually done in spin glass computations, we also discuss an alternative view of some technical problems suggesting that a replica symmetry breaking scheme is at play. 

---------------------

* **_Selberg integrals in 1D random Euclidean optimization problems_**, in collaboration with _Sergio Caracciolo, Enrico M Malatesta_, and _Luca G Molinari_, published in [*Journal of Statistical Mechanics: Theory and Experiment*](https://iopscience.iop.org/article/10.1088/1742-5468/ab11d7) on 2019 (preprint available in [arXiv](https://arxiv.org/abs/1810.00587)).
    > Selberg integrals are a famous family of integrals introduced by [Atle Selberg](https://en.wikipedia.org/wiki/Atle_Selberg). In this quite technical paper, we show how to use an extension of these integrals to compute the cost of some euclidean combinatorial optimization problems, such has the assignment, in one spatial dimension, for any number of points.

---------------------

* **_Average optimal cost for the Euclidean TSP in one dimension_**, in collaboration with _Sergio Caracciolo, Enrico M Malatesta_, and _Carlo Vanoni_, published in [*Journal of Physics A: Mathematical and Theoretical*](https://iopscience.iop.org/article/10.1088/1751-8121/ab1600) on 2019 (preprint available in [arXiv](https://arxiv.org/abs/1811.08265)).
    > In this work we consider the classic version of the Traveling Salesman Problem (different from the _bipartite_ version that we considered in previous papers), and we manage to describe the geometry of the solution when the points are uniformly chosen at random on a line. Although this version of the problem is in general more difficult to deal to with our methods, we still have been able to obtain the average cost of the solution in the limit of large number of points.

---------------------


* **_Exact value for the average optimal cost of the bipartite traveling salesman and two-factor problems in two dimensions_**, in collaboration with _Riccardo Capelli, Sergio Caracciolo_, and _Enrico M Malatesta_, published in [*Physical Review E*](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.98.030101) on 2018 (preprint available in [arXiv](https://arxiv.org/abs/1807.03559)).
    > Solving the Traveling Salesman Problem in two dimensions means to be able to tell, for any possible position of $N$ cities on a (flat) map, the shortest path traveling to all of them and coming back to the starting point. This is hard, and indeed solving this problem would allow anybody to get a reward of a million dollars from the Clay Mathematics Institute (more info [here](https://www.claymath.org/millennium-problems/p-vs-np-problem)). In this paper, we consider a variant of this problem (which is at least as hard as the problem itself), and showed that, for large number of cities, we can compute the length of the optimal tour by solving a much simpler problem (and no, this is not enough to win the prize!).

---------------------

* **_Plastic number and possible optimal solutions for an Euclidean 2-matching in one dimension_**, in collaboration with _Sergio Caracciolo_ and _Enrico M Malatesta_, published in [*Journal of Statistical Mechanics: Theory and Experiment*](https://iopscience.iop.org/article/10.1088/1742-5468/aad3f7) on 2018 (preprint available in [arXiv](https://arxiv.org/abs/1805.07178)).
    > In this work we consider a combinatorial optimization problem known as the 2-matching. It consists, given a set of points, in joining them in loops (with more than 2 points) so that the total length (or, better, cost, which is a function of the length) of the loops is the smallest possible. This problem is somehow intermediate between the matching problem (where we have segments connecting points instead of loops) and the traveling salesman problem (where the loop has to be a single one). We showed that the solution, when the points are on a line, is composed by loops involving a little number of points, and depending on the specific points positions it can be any of a large number of solution (the so-called _plastic number_ to the number of points). Even if we could not characterize exactly the solution for general point positions, we have been able to compute the average cost of the solution when the number of points goes to infinity.

---------------------

* **_Solution for a bipartite Euclidean traveling-salesman problem in one dimension_**, in collaboration with _Sergio Caracciolo, Marco Gherardi_, and _Enrico M Malatesta_, published in [*Physical Review E*](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.97.052109) on 2018 (preprint available in [arXiv](https://arxiv.org/abs/1802.01545)).
    > Euclidean combinatorial optimization problems are everywhere: for instance, they are routinely solved by Google Maps to find shortest routes to go to work, or to a party. Here we considered the problem of finding a cycle passing through a set of points on a line so that a given cost, which depends on the points' distances, is minimized. To do so, we proved some geometrical properties of the optimal solution for arbitrary points' positions, and managed to use these properties to compute the average cost of the solution when points are randomly placed on a line.

---------------------

* **_Unified Fock space representation of fractional quantum Hall states_**, in collaboration with _Luca G Molinari, Vittorio Erba_, and _Pietro Rotondo_, published in [*Physical Review B*](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.95.245123) on 2017 (preprint available in [arXiv](https://arxiv.org/abs/1705.07073)).
    > The fractional quantum Hall effect (FQHE) is a physical phenomenon described in 1982, which is still the topic of active research in present days. Here we contribute to this line of research, showing how to use a single framework to describe two distinct cases of the simplest FQHE theory (the _bosonic_ and _fermionic_ Laughlin wave functions), and elucidating where (mathematically speaking) the differences in these two cases come from.


# Conferences
I co-organized a conference in Paris about Innate and Adaptive Recognition of Antigens and NeoAntigens, more info at the [conference website](https://sites.google.com/view/qbio-iarana/home-page).