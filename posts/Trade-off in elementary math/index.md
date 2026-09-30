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
a \times (b+c) = a \times b + a \times c.
$$

<details>
<summary>More...</summary>
$$
0=-1\times \bigl(1+(-1)\bigr)= -1 + (-1 \times -1).
$$
</details>

## $\frac{3}{0}$ and $\frac{0}{0}$

We leave both $\frac{3}{0}$ and $\frac{0}{0}$ undefined to preserve division as the operation that uniquely undoes multiplication: $a/b$ must be the unique number $q$ satisfying

$$
bq = a.
$$

<details>
<summary>More...</summary>
For $\frac{3}{0}$, no number satisfies $0q = 3$.

For $\frac{0}{0}$, every number satisfies $0q = 0$, so there is no unique answer.
</details>


<!-- ---
title: "Tradeoffs in elementary math"
author: "Mohammad Tanviruzzaman"
date: "2026-09-30"
categories: [math]
---
**tl;dr**

> If we need to define a boundary case, among the options, we choose the definition that preserves a useful general structure.

## $x^0$
We choose $x^0 = 1$ because, if we chose $x^0 = 0$ instead, we had to give away the useful general structure: $x^{a+b} = x^ax^b$.

<details>
<summary>More...</summary>
$$
\begin{align}
x &= x^1 \\
  &= x^{1+0} \\
  &= x \cdot x^0
\end{align}
$$
</details>

## $-1 \times -1$
We choose $-1 \times -1 = +1$ because, if we chose $-1 \times -1 = -1$, we had to give away the useful general structure (distributive law): $a \times (b+c) = a \times b + a \times c$.

## $\frac{3}{0}$, $\frac{0}{0}$
We choose both $\frac{3}{0}$ and $\frac{0}{0}$ as undefined because if allowed them, we had to give away the useful general structure: division always has a unique quotient. -->