# continuous-methods-for-combinatorial-problems-in-graphs

Undergraduate thesis for my computer science degree at Universidad nacional de Colombia
In this monograph, we present an introduction to the use of linear and convex optimization
methods to combinatorial problems in graphs, which can serve as a starting point for 
understanding some of the recent advancements in the area of graph theory, we begin with
some background in linear algebra and spectral graph theory, then we introduce laplacian
systems, that is, systems of the form Lx = b with L the laplacian matrix of a graph, we 
will develop fast methods for solving them using conjugate gradient with an efficient
preconditioner, achieving an almost linear running time, in particular we focus on low stretch
spanning trees and approximate cholesky factorization including some of the recent research
by Gao, Kyng and Spielman, we then show how having a fast laplacian solver can be used to
make fast algorithms for the maximum flow problem, by using it as a subroutine in the
multiplicative weights algorithm, finally we introduce the interior point method applied
to the minimum cost flow problem, and show how we can make the algorithm faster by
calculating each step by solving a laplacian system.
