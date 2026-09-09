---
layout: page
title: Research
permalink: /research/
katex: true
---

This is an overview of the research projects I've had the opportunity to be a part of so far.

## Stability of group formation

This project arose from my work at the [2026 Santa Fe Institute Undergraduate Complexity Research (UCR) program](https://santafe.edu/engage/learn/projects/undergraduate-complexity-research-projects). We are studying the mechanisms of group formation in a set of diverse individuals, both at an individual decision-maker's level perspective and a population level. We are addressing questions such as which environmental factors may drive fast/slow commitment to a group, and how important is collective buy-in of cooperation to determine its dynamics. My experience at SFI helped me explore questions and concepts mixing different methods that I wouldn't have tried otherwise.


## Volunteer training at the St. James Food Pantry

I did this project in collaboration with the [St. James Food Pantry](https://www.stjameswabash.org/pantry-services/) in Chicago, as part of Illinois Tech's [SoReMo initiative](https://www.soremo.org/) for the Spring 2026 semester. I studied the problem of coordinating the training process for large groups (relative to the pantry size and staff) of new volunteers. This project was especially impactful for me since I got to experience two sides of the same coin: theory, drawn from models in the volunteer management literature; and practice, comprising the day-to-day operations at the pantry floor. I'm really grateful to the staff at the St. James Food Pantry for their support with this project.

<a href="/assets/docs/SoReMo/SoReMo-report.pdf">See the working paper here.</a>


## Augmenting longitudinal behavioral survey data

I participated in this project as part of the 2025 [Research in Industrial Projects for Students](https://www.ipam.ucla.edu/programs/student-research-programs/research-in-industrial-projects-for-students-rips-2026-los-angeles/) program at UCLA's Institute for Pure and Applied Mathematics (IPAM). We built a framework based on LLMs and Deep & Cross networks to create synthetic samples of longitudinal behavioral survey data preserving broad statistical patterns. We used the RAND Corporation’s FluPaths and COVIDPaths longitudinal studies, which capture respondents’ attitudes surrounding healthcare, influenza, and COVID-19.


**Associated publication:**
Rezvani, J., Hyk, A., Pham, T., Marciaga, L., Liao, C., Vardavas, R., & Mitsopoulos, K. (2026). Semantic Embedding and Synthetic Augmentation for Longitudinal Survey Prediction (Student Abstract). Proceedings of the AAAI Conference on Artificial Intelligence, 40(48), 41365-41367. [https://doi.org/10.1609/aaai.v40i48.42271](https://doi.org/10.1609/aaai.v40i48.42271)


## List coloring, strong chromatic-choosability, and Cartesian products of graphs

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
