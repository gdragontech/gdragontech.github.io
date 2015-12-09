---
layout: post
title: Probability
description: "useful probability"
tags: [AM post]
image:
  background: triangular.png
---

## Stirling's Formula

$$
n!=\sqrt{2\pi n}\left(\frac{n}{e}\right)^n\left(1 + \frac{1}{12n} + O\left(\frac{1}{n^2}\right)\right)
$$

## Useful Inequalities

1. \\(\binom{n}{k}\le \frac{n^k}{k!}\\)
2. \\(\binom{n}{k}\le \left(\frac{ne}{k}\right)^k\\)
3. \\(\binom{n}{k} \ge \left(\frac{n}{k}\right)^k\\)

## Moment Generating Function

Given random variable \\(X\\), its moment generating function is defined as,

$$
g(t) = E(e^{tX}),
$$

**Property**: 

$$
\frac{d^n}{d t^n}g(t)|_{t=0} = \mu_n,
$$

where \\(\mu_n\\) is the order n moment.
  


