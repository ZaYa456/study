---
title: Functions & Graphing
parent: Prerequisites
grand_parent: Math
nav_order: 3
---

# Functions & Graphing

## Part 1: Function Notation, Evaluating Functions, and Domain & Range

### Core Concepts & Rules

A function $$f(x)$$ assigns exactly one output value $$y$$ to each input value $$x$$:

- **Function Notation:** $$f(a)$$ represents the output when $$x = a$$. To evaluate $$f(\text{expression})$$, substitute the entire expression into every instance of $$x$$.
- **Domain:** the set of all allowable real inputs ($$x$$-values). When determining domain algebraically, apply two key restrictions:
  1. **Denominators cannot equal zero:** exclude any $$x$$-values where a denominator equals $$0$$.
  2. **Radicands of even roots must be non-negative:** for $$\sqrt{g(x)}$$, set $$g(x) \ge 0$$.
- **Range:** the set of all possible output values ($$y$$-values) generated across the domain.

### Worked Reference Example

Given $$f(x) = \frac{\sqrt{x + 3}}{x - 2}$$:

1. Evaluate $$f(6)$$.
2. Find the domain of $$f(x)$$ in interval notation.

**Step 1: Evaluate $$f(6)$$**

$$\text{Substitute } x = 6: \quad f(6) = \frac{\sqrt{6 + 3}}{6 - 2} = \frac{\sqrt{9}}{4} = \frac{3}{4}$$

**Step 2: Find the Domain**

1. Even root restriction — set the radicand greater than or equal to zero:

$$x + 3 \ge 0 \implies x \ge -3$$

2. Denominator restriction — set the denominator non-zero:

$$x - 2 \neq 0 \implies x \neq 2$$

3. Combine restrictions and write in interval notation:

$$[-3, 2) \cup (2, \infty)$$

### Practice Problems

1. Given $$f(x) = 2x^2 - 3x + 1$$: evaluate $$f(-2)$$, and expand and simplify $$f(x + 1)$$.
2. Find the domain of $$g(x) = \frac{5}{x^2 - 16}$$ in interval notation.
3. Find the domain of $$h(x) = \sqrt{2x - 8}$$ in interval notation.

### Solutions

**Problem 1**

Given $$f(x) = 2x^2 - 3x + 1$$:

- **Evaluate $$f(-2)$$:**

$$f(-2) = 2(-2)^2 - 3(-2) + 1$$

$$f(-2) = 2(4) + 6 + 1 = 8 + 6 + 1 = 15$$

- **Expand and simplify $$f(x + 1)$$:** substitute $$(x + 1)$$ for every instance of $$x$$:

$$f(x + 1) = 2(x + 1)^2 - 3(x + 1) + 1$$

Expand $$(x + 1)^2 = x^2 + 2x + 1$$ and distribute terms:

$$f(x + 1) = 2(x^2 + 2x + 1) - 3x - 3 + 1$$

$$f(x + 1) = 2x^2 + 4x + 2 - 3x - 2$$

Combine like terms:

$$f(x + 1) = 2x^2 + x$$

**Problem 2**

$$g(x) = \frac{5}{x^2 - 16}$$

1. Set the denominator equal to zero to find restricted values:

$$x^2 - 16 = 0 \implies (x - 4)(x + 4) = 0 \implies x = 4, \; x = -4$$

2. Exclude $$x = 4$$ and $$x = -4$$ from all real numbers:

$$\text{Domain: } (-\infty, -4) \cup (-4, 4) \cup (4, \infty)$$

**Problem 3**

$$h(x) = \sqrt{2x - 8}$$

1. Set the radicand of the even root greater than or equal to zero:

$$2x - 8 \ge 0$$

2. Isolate $$x$$:

$$2x \ge 8 \implies x \ge 4$$

3. Write in interval notation:

$$\text{Domain: } [4, \infty)$$

## Part 2: Linear & Quadratic Transformations

### Core Concepts & Transformation Rules

Function transformations alter the graph of a parent function $$f(x)$$ through shifts, reflections, and scaling. For a transformed function $$g(x) = a \cdot f(x - h) + k$$:

- **Vertical Shift ($$k$$):** $$+k$$ shifts the graph up $$k$$ units; $$-k$$ shifts it down $$k$$ units.
- **Horizontal Shift ($$h$$):** $$f(x - h)$$ shifts the graph right $$h$$ units; $$f(x + h)$$ shifts it left $$h$$ units.
- **Vertical Stretch / Compression ($$a$$):**
  - $$\lvert a \rvert > 1$$: vertically stretches the graph by a factor of $$\lvert a \rvert$$ (steeper/narrower).
  - $$0 < \lvert a \rvert < 1$$: vertically compresses the graph by a factor of $$\lvert a \rvert$$ (flatter/wider).
- **Reflection:** if $$a < 0$$, the graph is reflected across the x-axis.
- **Vertex Form of a Parabola:** for $$f(x) = a(x - h)^2 + k$$, the vertex is located at the point $$(h, k)$$.

### Worked Reference Example

Describe the transformations applied to the parent function $$f(x) = x^2$$ to obtain $$g(x) = -\frac{1}{2}(x + 4)^2 - 3$$, and state the vertex of $$g(x)$$.

1. **Identify horizontal shift:** $$(x + 4)$$ indicates $$h = -4$$, so the graph shifts **left 4 units**.
2. **Identify vertical scaling and reflection:** $$a = -\frac{1}{2}$$:
   - The negative sign indicates a **reflection across the x-axis** (opens downward).
   - $$\\lvert a \rvert = \frac{1}{2}$$ indicates a **vertical compression by a factor of $$\frac{1}{2}$$**.
3. **Identify vertical shift:** $$k = -3$$, so the graph shifts **down 3 units**.
4. **Determine vertex:** $$(h, k) = (-4, -3)$$.

### Practice Problems

1. Identify all transformations applied to $$f(x) = x^2$$ to produce $$g(x) = 3(x - 2)^2 + 7$$, and state the vertex of $$g(x)$$.
2. Write the equation in vertex form for $$g(x)$$ if the parent function $$f(x) = x^2$$ is shifted right 5 units, vertically stretched by a factor of 4, reflected across the x-axis, and shifted up 1 unit.
3. Given the linear function $$f(x) = 2x - 4$$, find the simplified algebraic expression for $$g(x) = f(x + 3) + 5$$.

### Solutions

**Problem 1**

$$g(x) = 3(x - 2)^2 + 7$$

1. Identify transformations relative to $$f(x) = x^2$$:
   - **Horizontal shift:** $$(x - 2)$$ indicates $$h = 2$$, shifting the graph **right 2 units**.
   - **Vertical stretch:** $$a = 3$$ ($$\lvert a \rvert > 1$$), stretching the graph **vertically by a factor of 3**.
   - **Vertical shift:** $$k = 7$$, shifting the graph **up 7 units**.
2. State the vertex $$(h, k)$$:

$$(2, 7)$$

**Problem 2**

1. Apply each transformation to vertex form $$g(x) = a(x - h)^2 + k$$:
   - **Shifted right 5 units:** $$h = 5 \implies (x - 5)^2$$
   - **Vertically stretched by 4 and reflected across the x-axis:** $$a = -4$$
   - **Shifted up 1 unit:** $$k = 1$$
2. Write the complete equation:

$$g(x) = -4(x - 5)^2 + 1$$

**Problem 3**

Given $$f(x) = 2x - 4$$, find $$g(x) = f(x + 3) + 5$$:

1. Substitute $$(x + 3)$$ into $$f(x)$$:

$$f(x + 3) = 2(x + 3) - 4$$

$$f(x + 3) = 2x + 6 - 4 = 2x + 2$$

2. Add $$5$$ to complete $$g(x)$$:

$$g(x) = (2x + 2) + 5$$

3. Simplify:

$$g(x) = 2x + 7$$
