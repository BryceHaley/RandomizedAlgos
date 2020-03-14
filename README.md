# Introduction

A randomized algorithm is an algorithm that takes random bits *r* as one of its inputs. Even if *r* is never used. True randomness (ie. a random oracle) is a mostly theoretical concern, and won't be discussed here. We will use deterministic methods (PRNGs, rand(), etc) to 'approximate' randomness.

> Insert elevator pitch here on how cool and neat random algos are and how they can solve untractable (read: NP-Hard) problems in a sane amount of time, with known and BOUNDED error. Cool eh?

# Why?

Practice. I (Rulai) also did terribly in this class so I want to prove I actually understand the material. So I will do what a programmer does best: code.

Understanding. I (Bryce) have no idea what I actually learned in CMPT
409 and what I fooled myself into thinking I learned but was just
mimicking. 

# CMPT 409

CMPT 409 was offered in winter 2019, and was cross-listed as both CMPT 815 and some 500 level MATH course. The syllybus described it as follows:
>Most interesting optimization problems are NP-hard. For an NP-hard problem, it is impossible to have an algorithm which gives an optimal solution efficiently (in polynomial time) for any input instance of the problem unless P=NP. Approximation are powerful and widely used approaches for tackling hard optimization problems. An approximation algorithm finds a near-optimal solution with guaranteed accuracy efficiently for any input instance. Randomized algorithms are another powerful and widely used approach to tackle problems for which efficient deterministic algorithms are not known. The course will cover the fundamentals on the design and analysis of approximation and randomized algorithms for discrete optimization problems. By completing this course, students are expected to be able to design approximation and randomized algorithms for their own problems, prove and analyze the correctness and efficiency of their algorithms, and apply theoretical analysis to the study of heuristics. 
it covered:
1. Basic probability: linearity of expectation, concentration inequalities
2. Approximation algorithms for discrete optimization problems
3. Randomized algorithms
4. Linear programming
5. Semidefinite programming
6. Sublinear time algorithms
7. PCP theorem and hardness of approximation

Both Authors of this repo (Rulai and Bryce) had an auful time completing
the course work but actually really loved the content. The work in this
repo is to interact with the subject matter in a more gentle way and
ensure that we understand what our proofs proved.
