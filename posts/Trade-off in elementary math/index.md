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

We can make the product of $-1$ and $-1$ equal to $-1$ while keeping distributivity, but other rules must change. For example, we could define a new multiplication: $a \star b = -(ab)$ with $ab = \underbrace{b + b + \cdots + b}_{a\text{ times}}$. Now, the distributive law works:

$$
0 = -1 \star \bigl(1+(-1)\bigr) = 1 + (-1 \star -1)
$$

The tradeoff is that multiplying by $1$ now reverses the sign:

$$
a \star 1 = -a.
$$

Instead, $-1$ becomes the multiplicative identity:

$$
a \star (-1) = a.
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