---
problem_id: problem-7
author: BrianMarcus
date: '2016-11-10T11:51:00-08:00'
---
(For part a.) Let $(\Omega, T)$ be an Axiom A basic set. Then there is a
Markov partition given by rectangles $\\{R_i\\}_i$ and an adjacency matrix $A$
for the associated SFT $\Sigma_A$. Assume that the maximum diameter of the
rectangles is at most 1/2 of an expansive constant for $T$. Let $\pi: \Sigma_A
\rightarrow \Omega$ be the factor map: $\pi(x) = \cap_i T^{-i}(R_{x_i})$. Via
$\pi$, $(\Omega, T)$ is topologically conjugate to $(Y,S)$ where $Y$ is the
quotient of $\Sigma_A$ by the equivalence relation $x \sim x'$ iff for all
$i$, $R_{x_i} \cap R_{x'_i} \ne \emptyset$ and $S$ is the map induced on the
quotient by the shift. So, up to conjugacy, $(\Omega, T)$ is completely
determined by the matrices $A$ and $R$ where $R_{ij} = 1$ if $R_i \cap R_j \ne
\emptyset$ and 0 otherwise. The problem: classify Axiom A basic sets up to
conjugacy by the matrices $A$ and $R$. This problem was mentioned in the
syllabus for a seminar course that Rufus taught in Fall, 1973. Related
material is contained in Fried {{< cite fried1987finitely >}} and Boyle-Buzzi
{{< cite boyle2014almost >}}.

