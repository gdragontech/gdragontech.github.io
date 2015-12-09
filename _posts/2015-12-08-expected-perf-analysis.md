---
layout: post
title: Analysis of Expected Performance of Randomized QuickSort
description: "Analysis of randomized algorithms"
tags: [math post]
image:
  background: triangular.png
---

**Theorem**: For _randomized quicksort_, the expected number of comparisons is \\(O(n\log n)\\).

_proof_: Denote the input array as \\(A=[a_1,a_2,...,a_n]\\), while the sorted version is \\(S=[s_1,s_2,...,s_n]\\). Let \\(X\\) be the \# of comparisons over the execution of _quicksort_, and \\(X_{i,j}\\) be the indicator random variable which is defined as 
$$
X_{i,j} = \begin{cases}1,\quad if s_i \& s_j \mbox{ is compared}\\0,\quad \mbox{otherwise}\end{cases}
$$