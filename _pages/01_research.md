---
layout: page
title: Research
permalink: /research/
katex: true
---

### Optimizing client flow in food pantries

I'm doing this project in collaboration with the [St. James Food Pantry](https://www.stjameswabash.org/pantry-history/), 
located near the Illinois Tech campus in Chicago, as part of Illinois Tech's [SoReMo initiative](https://www.soremo.org/) for the Spring 2026 semester.
Food pantries need to balance uncertainty in both client demand and volunteer staff supply,
which in particular impacts client waiting times. On the other hand, the St. James Food Pantry follows a [client-choice model](https://www.endhungerinamerica.org/getting-started/client-choice-food-pantries/), allowing each client to choose food items suited to their needs. Therefore, both system throughput and service autonomy are crucial to guarantee an effective and dignified service to clients.

I'm developing a tool using discrete-event simulation to understand the process workflow of the food pantry under uncertain conditions to help pantry managers identify potential improvements and study the performance of alternative process workflows. <a href="/assets/docs/Optimizing client flow in food pantries.pdf">Here is the initial presentation</a> I gave at the Spring 2026 kickoff event of the SoReMo initiative.


### Augmenting longitudinal behavioral survey data

I participated in this project as part of the 2025 [Research in Industrial Projects for Students](https://www.ipam.ucla.edu/programs/student-research-programs/research-in-industrial-projects-for-students-rips-2026-los-angeles/) program at UCLA's Institute for Pure and Applied Mathematics (IPAM).

Epidemic simulation models require accurate and up-to-date survey data to reflect population behaviors, but collecting such data is often costly and time-consuming. This creates a need for methods to augment existing data to integrate into such models, although there exist several challenges for such methods to overcome. In particular, longitudinal survey data often presents challenges for traditional time series modeling methods, such as data sparsity due to attrition, or changing survey question texts over time.

We address these issues through a framework involving Deep & Cross Networks, LLM‐derived semantic question embeddings, wave‐local cluster analysis, and an LLM-based synthetic data generation pipeline. We used the RAND Corporation's FluPaths and COVIDPaths longitudinal studies, which capture respondents' attitudes surrounding healthcare, influenza, and COVID-19.

**Associated publication:**
Rezvani, J., Hyk, A., Pham, T., Marciaga, L., Liao, C., Vardavas, R., Mitsopoulos, K. _Semantic Embedding and Synthetic Augmentation for Longitudinal Survey Prediction (Student Abstract)._ In _Proceedings of the 40th AAAI Conference on Artificial Intelligence (AAAI-26)._ Singapore. (in press).



### List coloring, strong chromatic-choosability, and Cartesian products of graphs

I'm working with Professors [Hemanshu Kaul](https://www.math.iit.edu/~kaul/index.html) and [Jeffrey Mudrock](https://jmudrock.weebly.com/) in this project. 

We consider the problem of _list coloring_, a generalization of classical graph coloring, introduced in the 1970s independently by Vizing (1976) and Erdős, Rubin, and Taylor (1979). Here, each vertex has its own "color palette." That is, for a graph $G = (V, E)$, we consider a _list assignment_ $L$ on $V$; then $L(v)$ is the "color palette" of the vertex $v \in V$. The goal is to produce a _proper coloring_ $f$ such that $f(v) \in L(v)$ for each $v \in V$ and such that no two adjacent vertices are assigned the same color.

Thus, we can define an analogue of the classical _chromatic number_. A list assignment $L$ is a _$k$-assignment_ when $\lvert L(v) \rvert = k$ for all $v \in V(G)$. We say that $G$ is _$k$-choosable_ if $G$ is $L$-colorable for any $k$-assignment $L$. The _list chromatic number_ of $G$, denoted $\chi_{\ell}(G)$, is the smallest $k$ such that $G$ is $k$-choosable. That is, we seek the smallest "palette size" on each vertex such that no matter their contents, we can always find a proper coloring.

We explore how the list chromatic number behaves under the _Cartesian product_ of certain families of graphs, especially _strongly chromatic-choosable_ graphs.

<p align="center" class="photo" width="100%">
    <img src="/assets/images/K24_not_2_colorable.png" alt="K_2,4 is not 2-colorable" width="75%"/>
    <br>
    A classical example in list coloring: the bipartite graph $K_{2, 4}$ is not 2-colorable.
</p>

**Associated publication:**
Kaul, H., Marciaga, L., and Mudrock, J. _List Coloring the Cartesian Product of a Complete Graph and Complete Bipartite Graph._ Enumerative Combinatorics and Applications, 6 (2026), article S2R5. Available at [https://doi.org/10.54550/ECA2026V6S1R5](https://doi.org/10.54550/ECA2026V6S1R5).
