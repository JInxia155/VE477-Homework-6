Download Link : https://programming.engineering/product/ve477-homework-6/

# VE477-Homework-6
VE477 Homework 6

Questions preceded by a * are optional. Although they can be skipped without any deduction, it is important to know and understand the results they contain.

Ex. 1 — Perfect matching in a bipartite graph

Let G = V , E be a bipartite graph where V = L ∪ R. A perfect matching in G is a subset of E where every vertex is contained in exactly one edge. Let A be the matrix whose rows correspond to vertices in L and columns to vertices in R. Each element ai ,j of A is defined as a variable Xi ,j , if vertices i and j are connected and 0 otherwise.

    Expressing the determinant of A as a polynomial prove that it is identically zero if and only if G has no perfect matching.

    Deduce an algorithm to decide if a bipartite graph has a perfect matching.

    What are the complexity and error probability of this algorithm?

    As deterministic polynomial time algorithms already exist, discuss the usefulness of this strategy.

Ex. 2 — Critical thinking

Given a singly linked list, write two algorithms to solve each of the following problems.

    Find the middle node in one pass.

    Without using any storage, that is without using any memory to saving information, determine if the list contains a loop. What is the complexity of this algorithm? Explain.

Ex. 3 — The coupon collector desillusion

As part of their marketing strategy a brand decides to sell each box of cereal they produce with a coupon.

A collector decides to gather all the n different coupons.

1. At least how many boxes should be bought to collect all the different coupons?

Let X be a random variable equal to the number of boxes bought in order to have at least a coupon of each type, and Xj be the number of steps necessary for getting coupon j, knowing that the collector already has j − 1 coupons.

        ]

* 2. What is E Xj , the expectation of Xj ?

3. Prove that the expected time before all types of coupon are collected is E [X ] = Θ(n log n).

4. In terms of “coupon collector”, explain the meaning of the previous mathematical formula.
