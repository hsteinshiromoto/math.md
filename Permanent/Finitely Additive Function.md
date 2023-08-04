---
alias: finitely additive, finitely additive functions
tags: 
title: Finitely Additive Function
date created: 2023-07-27 21:59:01
date modified: 2023-08-04 21:24:04
---

tags: #definition

# Finitely Additive Function

## Statements

**Definition**. ([[Dudley, R. M. - Real Analysis and Probability|@Dud04, pp. 85]]) Let $X$ be a set and $\mathfrak{S}$ be a collection of subsets of $X$ with $\emptyset\in\mathfrak{S}$. A function $\mu:\mathfrak{S}\to[-\infty,\infty]$ is said to be _finitely additive_ if $\mu(\emptyset)=0$ and, for any $n\in\mathbb{N}_{>0}$, on disjoint sets $\{A_i\}_{i\in[1,n]}$ of $\mathfrak{S}$ satisfying
$$A:=\bigcup_{i=1}^nA_i\in\mathfrak{S}$$
the equality
$$\mu(A)=\sum_{i=1}^n\mu(A_i)$$
holds.