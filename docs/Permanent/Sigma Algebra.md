---
alias: [sigma algebra, sigma algebras, measurable space, measurable spaces, measurable set, measurable sets]
tags: 
title: Sigma Algebra
date created: 2023-08-02 22:29:11
date modified: 2023-08-02 22:41:19
---

tags: #definition | #analysis

# Sigma Algebra

## Statements

**Definition**. ([[Salsa S. - Partial Differential Equations in Action|@Sal08, Definition B.1]]) A collection $\mathfrak{S}$ of subsets of a set $\Omega$ is said to be a $\sigma-$_algebra_ if
1. $\emptyset$, $\Omega\in\mathfrak{S}$.
2. If $A\in\mathfrak{S}$, then $\Omega\setminus A\in\mathfrak{S}$.
3. If $\{A_k\}_{k\in\mathbb{N}}\subset\mathfrak{S}$, then
	$$\bigcup_{k\in\mathbb{N}}A_k\in\mathfrak{S}\ \text{and}\ \bigcap_{k\in\mathbb{N}}A_k\in\mathfrak{S}\;.$$
The pair $(\Omega,\mathfrak{S})$ is said to be a _measurable space_, and the sets $A_k$ are said to be _measurable sets_.