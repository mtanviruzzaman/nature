---
title: "Tradeoffs in elementary algebra"
author: "Mohammad Tanviruzzaman"
date: "2026-09-30"
categories: [math]
---

**tl;dr**

> When extending a definition or operation, we favor choices that preserve useful general rules.

## $x^0$

We choose $x^0 = 1$ because choosing $x^0 = 0$ instead would require us to give up the general exponent rule:

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

We can preserve the distributive law even if we define the product of $-1$ and $-1$ as $-1$, only if we are willing to pay the cost of redefining multiplication as: $a \star b = -(ab)$ with $ab = \underbrace{b + b + \cdots + b}_{a\text{ times}}$.

$$
0 = -1 \star \bigl(1+(-1)\bigr) = 1 + (-1 \star -1)
$$

This redefined multiplication now behaves very differently, like $-1$ becomes our multiplicative identity: $-1 \star a = a$. 
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