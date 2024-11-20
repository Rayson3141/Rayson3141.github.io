---
title: MathJax and LaTeX
author: Tao He
date: 2023-10-14
category: Jekyll
layout: post
mermaid: true
---

This jekyll-theme supports [MathJax](https://www.mathjax.org/) to render $\LaTeX$
and mathematics expressions.

> ##### TIP
>
> Currently, Kramdown uses double dollar sign delimiters for inline and display math:
> [https://kramdown.gettalong.org/syntax.html#math-blocks](https://kramdown.gettalong.org/syntax.html#math-blocks).
{: .block-tip }

2.1. Determine the centralizer and the order of the conjugacy class of
(a) the matrix 
$$\left[\begin{array}{ll}1 & 1 \\ & 1\end{array}\right]\) in $G L_{2}\left(\mathbb{F}_{3}\right]$$, 
(b) the matrix \(\left[\begin{matrix}1 & \\ & 2\end{matrix}\right]\) in 

$G L_{2}\left(\mathbb{F}_{5}\right)$.

```markdown
The well known Pythagorean theorem $x^2 + y^2 = z^2$ was
proved to be invalid for other exponents.
Meaning the next equation has no integer solutions:

$$ x^n + y^n = z^n $$
```
$$e^x$$
The well known Pythagorean theorem $x^2 + y^2 = z^2$ was
proved to be invalid for other exponents.
Meaning the next equation has no integer solutions:

$$ x^n + y^n = z^n $$



Another example with more complex markups:

```markdown
When $a \ne 0$, there are two solutions to $ax^2 + bx + c = 0$ and they are

$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$
```

When $a \ne 0$, there are two solutions to $ax^2 + bx + c = 0$ and they are

$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

Refer to the [MathJax website](https://docs.mathjax.org/en/latest/index.html) for more examples.
