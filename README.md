# Discrete Math at SPbSU

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/alexanderskulikov/discrete-math/master)

A collection of interactive notebooks for the 
Discrete Math course at SPbSU 
(click the badge above to launch the interactive environment). 
The interactive notebooks complement live lecture by providing 
visualizations and additional resources, but are not meant to 
replace the lectures (in particular, contain almost no proofs).

## Materials
* [Draft of the book by Vyalii, Podolskii, Rubtsov, Shwartz, Shen](http://rubtsov.su/public/hse/2017/DM-HSE-Draft.pdf)
* [Introduction to Discrete Mathematics for Computer Science Specialization at Coursera](https://www.coursera.org/specializations/discrete-mathematics)
* [Interactive Puzzles](http://dm.compsciclub.ru/app/list)

## Program

1. **Induction (September 5, 2018)**
* Warm-up: coloring the plane, arithmetic series, sum of squares, change problem, triangualtion.
* Bernoulli's inequality.
* Inequality of arithmetic and geometric means.
* Systems of homogeneous linear equations.
* Gray code.
* Hall's theorem.

2. **Combinatorics (September 12, 2018)**
* Sum rule, inclusion-exclusion formula.
* Receurrence relations, Fibonacci numbers, number of paths on a grid.
* Product rule, tuples.
* Permutations.
* Combinations, Pascal's triangle, symmetries.
* Binomial theorem.

3. **Catalan numbers (September 19, 2018)**
* The formula via mirrorings and bad paths.
* The formula via cyclis shifts.
* Applications: triangulations, associative computations.

4. **Graphs I (September 26, 2018)**
* Handshaking lemma, total degree formula.
* Knights transposition: board cell graph, configuration graph.
* Eulerian cycles: bridges of Königsberg, criterion for undirected and directed graphs.
* Hamiltonian cycles: no known simple criterion.
* Genome assembly: shortest common superstring problem, reduction to the Hamiltonian path problem,
special case: k-spectrum of an unknown string, reduction to Eulerian path problem, de Bruijn graphs.

5. **Graphs II (October 3, 2018)**
* Connected components in undirected graphs: lower bound, the heaviest stone problem.
* Trees: four definitions, their equivalence.
* Paths: reachability, cuts, properties of shortest paths.
* Bipartite graphs: 2-coloring, odd cycles, Hall's theorem.
* Ramsey numbers: R(3,3)=6, general upper bound.
* Directed acyclic graphs and topological ordering.
* Strongly connected components in directed graphs: metagraph/condensation, 2-satisfiability.

6. **Graphs III (October 10, 2018)**
* Planar graphs: Euler formula, E<3V-5, every planar graph has a node of degree at most 5, non-planarity of K_{3,3} and K_5, theorems of Kuratowski–Pontryagin and Wagner (without a proof).
* Coloring: chromatic number, simple bounds, Brooks theorem (without a proof), Appel–Haken theorem (without a proof), 6-colorability of a planar graph, 3-coloring, 3-recoloring.
* Cliques and independent sets: Mantel theorem, Turán theorem (without a proof).
* Vertex cover: relation to independent set, König theorem.

7. **Modular arithmetic (October 17, 2018)**
* Modular addition and multiplication: associativity, commutativity, distribitivity.
* Euclid's algorithm: certificate of the greatest common divisor, extended Euclid's algorithm.
* Diophantine equations: necessary and sufficient condition, finding all solutions.
* Modular division: multiplicative inverse.
* Chinese remainder theorem.
* Fermat's little theorem.

8. **RSA cryptosystem (October 24, 2018)**
* One-time pad.
* RSA: modular exponentiation, factoring, discrete logarithm.
* RSA attacks: too few messages, small prime, small difference, insufficient randomness, broadcast attack (the e=3 case).
* Digital signature.

9. **Sets and logic (November 1, 2018)**
* Basic set operations: union, intersection, set difference, symmetric difference, complement.
* Set identities: Venn diagrams, tables.
* Inclusion-exclusion formula: combinatorial proof, proof using characteristic functions.
* Propositional logic: Boolean variables, basic uniry and binary functions.

10. **Logic (November 8, 2018)**
* Completeness of {and, or, not}, {and, not}, {or, not}, {and, xor, 1}, {nand}; DNF, CNF, Zhegalkin polynomial.
* Post's theorem.

11. **Functions, Relations (November 14, 2018)**
* Functions: image, preimage, Cartesian product, plot, function as a special case of mapping.
* Injection, surjection, bijection.
* Bijection between NxN and N, bijection between subsets of [n], binary words of length n.
* Composition, associativity, inverse function.
* Number of different injections, surjections, bijections.
* Binary relations: graphs, matrices.
* Basic properties: symmetry, reflexivity, transitivity. Equivalence relations.


12. **Cardinalities (November 21, 2018)**
* Equinumerosity: symmetry, reflexivity, transitivity.
* Examples: natural and even numbers, natural numbers and squares, circle and triangle, closed and semi-open interval.
* Countable sets examples: integers, squares, rationals.
* Countable sets properties: union of countable sets is countable; a subset of a countable set is either finite or countable; rationals are countable; any infinite set contains a countable subset; cartesian product of two countable sets is countable.
* [0,1] ~ infinite binary sequences; [0,1] ~ [0,1] x [0,1].
* Cantor's diagonal argument: [0,1] is uncountable.
* Comparing cardinalities, Cantor–Bernstein theorem.
* Cantor's theorem: no A has the same cardinality as 2^A.

13. **Partially Ordered sets (November 28, 2018)**
* Partially ordered sets: rexlexivity, antisymmetry, transitivity.
* Examples: digits, segments, subsets, binary words, divisors.
* Hasse diagrams.
* Lexicographic ordering.
* Total orderings: every two (with the same number of elements) are isomorphic, each contains the minimum and maximum element.
* Every non-empty subset has a minimal element iff any decreasing chain is finite.
* Erdős--Szekeres theorem: a sequence of length sr+1 contains either an increasing subsequence of length s+1 or a decreasing subsequence of length r+1.
* Mirsky theorem: |longest chain|=|min antichain decomposition|.
* Dilworth theorem: |longest antichain|=|min chain decomposition|.

14. **Combinatorial Games (December 05, 2018)**
* Warm-up: a few simple games.
* Winning and losing positions, analyzing backwards.
* Symmetries: when it is possible to win by repeating the opponent's move.
* The nim game.
* The price of a game.