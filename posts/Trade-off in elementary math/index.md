---
title: "Tradeoffs in elementary math"
author: "Mohammad Tanviruzzaman"
date: "2026-09-30"
categories: [math]
---

**tl;dr**

> When extending a definition or operation, we favor choices that preserve useful general rules.

## $x^0$

For $x \ne 0$, we choose $x^0 = 1$ because choosing $x^0 = 0$ instead would require us to give up the general exponent rule:

$$
x^{a+b} = x^a x^b.
$$

<details>
<summary>More...</summary>
$$
x = x^{1+0} = x^1 \cdot x^0
$$
</details>

## $-1 \times -1$

When extending multiplication to negative numbers, we choose $(-1) \times (-1) = +1$ because choosing $-1$ instead would require us to give up the distributive law:

$$
a \times (b+c) = a \times b + a \times c
$$

<details>
<summary>More...</summary>
$$
0=-1\times \bigl(1+(-1)\bigr)= -1 + (-1 \times -1)
$$
</details>

## $\frac{3}{0}$ and $\frac{0}{0}$

We leave both $\frac{3}{0}$ and $\frac{0}{0}$ undefined to preserve division as the operation that uniquely undoes multiplication: $a/b$ must be the unique number $q$ satisfying

$$
bq = a
$$

<details>
<summary>More...</summary>
For $\frac{3}{0}$, no number satisfies $0q = 3$.

For $\frac{0}{0}$, every number satisfies $0q = 0$, so there is no unique answer.
</details>