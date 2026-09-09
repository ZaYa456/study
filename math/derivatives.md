---
title: Derivatives — Chain Rule
parent: Math
nav_order: 1
---

# Derivatives — Chain Rule

The chain rule states that if $$ y = f(g(x)) $$, then:

$$
\frac{dy}{dx} = f'(g(x)) \cdot g'(x)
$$

## Example

Let $$ y = \sin(3x^2) $$. Set $$ u = 3x^2 $$, so $$ y = \sin(u) $$.

$$
\frac{dy}{dx} = \cos(u) \cdot \frac{du}{dx} = \cos(3x^2) \cdot 6x
$$
