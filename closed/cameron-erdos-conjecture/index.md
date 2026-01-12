# Cameron–Erdős Conjecture

**Status:** Solved (2003)
**Solved by:** Alexander Sapozhenko (independently also by Ben Green)

## Problem Statement

The number of sum-free subsets of {1, 2, ..., n} is O(2^(n/2)).

## Description

A set S of integers is sum-free if there are no elements x, y, z in S (not necessarily distinct) such that x + y = z. The Cameron–Erdős conjecture, posed by Peter Cameron and Paul Erdős in 1990, concerns counting such sets.

Trivially, any subset of odd numbers is sum-free, which gives 2^(⌈n/2⌉) sum-free subsets. The conjecture states that the total count is not much larger than this trivial bound.

## Solution

The conjecture was proved independently by Alexander Sapozhenko and Ben Green in 2003. Both proofs show that the number of sum-free subsets of {1, 2, ..., n} is indeed Θ(2^(n/2)).

Sapozhenko's proof used container methods, while Green's proof employed Fourier analysis and density increment arguments.

## Significance

This result established important counting techniques for combinatorial structures defined by arithmetic properties.
