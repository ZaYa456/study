---

title: Rational Expressions
parent: Prerequisites
grand_parent: Math
nav_order: 4
------------

**# Rational Expressions**

## Part 1: Simplifying, Multiplying, and Dividing Rational Expressions

### Core Concepts & Rules

A rational expression is an algebraic fraction containing polynomials in the numerator and denominator:

* **Simplifying:** Factor both the numerator and denominator completely, then cancel common factors.

* **Multiplying Rational Expressions:** Factor all terms, multiply numerators and denominators, and cancel common factors:

$$
\frac{A}{B} \cdot \frac{C}{D} = \frac{A \cdot C}{B \cdot D}
$$

* **Dividing Rational Expressions:** Multiply by the reciprocal of the second fraction:

$$
\frac{A}{B} \div \frac{C}{D} = \frac{A}{B} \cdot \frac{D}{C}
$$

* **Domain Restrictions:** Variable values that make any denominator equal to $0$ are undefined and must be excluded.

### Worked Reference Example

Simplify completely and state restrictions:

$$
\frac{x^2 - 9}{x^2 + 5x + 6} \div \frac{2x - 6}{x + 2}
$$

**1. Convert division into multiplication by multiplying by the reciprocal:**

$$
\frac{x^2 - 9}{x^2 + 5x + 6} \cdot \frac{x + 2}{2x - 6}
$$

**2. Factor all numerators and denominators completely:**

* $x^2 - 9 = (x - 3)(x + 3)$

* $x^2 + 5x + 6 = (x + 2)(x + 3)$

* $2x - 6 = 2(x - 3)$

$$
\frac{(x - 3)(x + 3)}{(x + 2)(x + 3)} \cdot \frac{x + 2}{2(x - 3)}
$$

**3. Cancel common binomial factors in numerator and denominator:**

$$
\frac{\mathbf{(x - 3)}\mathbf{(x + 3)}}{\mathbf{(x + 2)}\mathbf{(x + 3)}} \cdot \frac{\mathbf{x + 2}}{2\mathbf{(x - 3)}} = \frac{1}{2}
$$

**4. Identify restrictions:**

Setting denominators from the original expression to zero gives:

$$
x \neq -2,\,-3,\,3
$$

**Final Answer:**

$$
\frac{1}{2}, \qquad x \neq -2,\,-3,\,3
$$

### Practice Problems

Simplify each expression completely, then reply with your final answers or step-by-step working.

1. \(\frac{x^2 - 4x - 12}{x^2 - 36}\)

2. \(\frac{2x + 10}{x^2 - 25} \cdot \frac{x - 5}{4x}\)

3. \(\frac{x^2 + 3x}{x^2 - 1} \div \frac{x + 3}{x - 1}\)

### Solutions

**Problem 1**

$$
\frac{x^2 - 4x - 12}{x^2 - 36}
$$

**1. Factor the numerator and denominator completely:**

* Numerator ($x^2 - 4x - 12$): Find factors of $-12$ that sum to $-4$:

$$
x^2 - 4x - 12 = (x - 6)(x + 2)
$$

* Denominator ($x^2 - 36$): Difference of squares:

$$
x^2 - 36 = (x - 6)(x + 6)
$$

$$
\frac{(x - 6)(x + 2)}{(x - 6)(x + 6)}
$$

**2. Cancel common binomial factors:**

$$
\frac{\mathbf{(x - 6)}(x + 2)}{\mathbf{(x - 6)}(x + 6)}
= \frac{x + 2}{x + 6}
$$

**3. Identify the restriction:**

$$
x \neq 6,\,-6
$$

**Final Answer:**

$$
\frac{x + 2}{x + 6}, \qquad x \neq 6,\,-6
$$

**Problem 2**

$$
\frac{2x + 10}{x^2 - 25} \cdot \frac{x - 5}{4x}
$$

**1. Factor all numerators and denominators:**

* $2x + 10 = 2(x + 5)$

* $x^2 - 25 = (x - 5)(x + 5)$

$$
\frac{2(x + 5)}{(x - 5)(x + 5)} \cdot \frac{x - 5}{4x}
$$

**2. Cancel common factors across numerators and denominators:**

$$
\frac{2\mathbf{(x + 5)}}{\mathbf{(x - 5)}\mathbf{(x + 5)}} \cdot \frac{\mathbf{x - 5}}{4x}
= \frac{2}{4x}
$$

**3. Reduce the numerical fraction:**

$$
\frac{1}{2x}
$$

**4. Identify the restrictions:**

The original denominators cannot equal zero:

$$
x^2 - 25 \neq 0
$$

$$
x \neq -5,\,5
$$

and

$$
4x \neq 0 \implies x \neq 0
$$

**Final Answer:**

$$
\frac{1}{2x}, \qquad x \neq -5,\,0,\,5
$$

**Problem 3**

$$
\frac{x^2 + 3x}{x^2 - 1} \div \frac{x + 3}{x - 1}
$$

**1. Convert division to multiplication by the reciprocal:**

$$
\frac{x^2 + 3x}{x^2 - 1} \cdot \frac{x - 1}{x + 3}
$$

**2. Factor numerators and denominators completely:**

* $x^2 + 3x = x(x + 3)$

* $x^2 - 1 = (x - 1)(x + 1)$

$$
\frac{x(x + 3)}{(x - 1)(x + 1)} \cdot \frac{x - 1}{x + 3}
$$

**3. Cancel common factors:**

$$
\frac{x\mathbf{(x + 3)}}{\mathbf{(x - 1)}(x + 1)}
\cdot
\frac{\mathbf{x - 1}}{\mathbf{x + 3}}
=
\frac{x}{x + 1}
$$

**4. Identify the restrictions:**

The original denominators cannot equal zero:

$$
x^2 - 1 = 0 \implies x \neq -1,\,1
$$

Additionally, because the divisor cannot equal zero:

$$
\frac{x + 3}{x - 1} \neq 0 \implies x \neq -3
$$

Therefore:

$$
x \neq -3,\,-1,\,1
$$

**Final Answer:**

$$
\frac{x}{x + 1}, \qquad x \neq -3,\,-1,\,1
$$

---

## Part 2: Adding, Subtracting, and Solving Rational Equations

### Core Concepts & Rules

Operating on and solving rational expressions requires finding and using the Least Common Denominator (LCD):

* **Finding the LCD:** Factor all denominators completely. The LCD is the product of the highest power of each unique factor present across all denominators.

* **Adding and Subtracting:**

  1. Rewrite each rational expression with the LCD as its denominator:

  $$
  \frac{A}{B} \pm \frac{C}{D}
  =
  \frac{A \cdot D}{B \cdot D}
  \pm
  \frac{C \cdot B}{B \cdot D}
  =
  \frac{AD \pm CB}{BD}
  $$

  2. Expand numerators, combine like terms, and simplify the fraction if possible. Keep the denominator in factored form.

* **Solving Rational Equations:**

  1. Identify variable restrictions ($x$-values that make any denominator equal to zero).

  2. Multiply every term on both sides of the equation by the overall LCD to clear all fractions.

  3. Solve the resulting polynomial equation.

  4. **Extraneous Solutions:** Compare solutions against the original restrictions. Discard any solution that results in division by zero.

### Worked Reference Example

Solve for $x$:

$$
\frac{2}{x - 3} + \frac{1}{x} = \frac{6}{x^2 - 3x}
$$

**1. Factor denominators and identify restrictions:**

$$
x^2 - 3x = x(x - 3)
$$

$$
\text{Restrictions: } x \neq 0,\,3
$$

$$
\text{LCD: } x(x - 3)
$$

**2. Multiply both sides by the LCD $x(x - 3)$ to clear denominators:**

$$
x(x - 3) \cdot \left(\frac{2}{x - 3}\right)
+
x(x - 3) \cdot \left(\frac{1}{x}\right)
=
x(x - 3) \cdot \left(\frac{6}{x(x - 3)}\right)
$$

$$
2x + (x - 3) = 6
$$

**3. Solve the resulting linear equation:**

$$
2x + x - 3 = 6
$$

$$
3x - 3 = 6
$$

$$
3x = 9
$$

$$
x = 3
$$

**4. Check for extraneous solutions:**

$x = 3$ violates the restriction $x \neq 3$ because it produces division by zero in the original expression.

Therefore, $x = 3$ is **extraneous**.

$$
\text{Final Answer: No Solution }(\emptyset)
$$

### Practice Problems

Solve or simplify each problem below, then reply with your answers or step-by-step working.

1. Perform the operation and simplify:

$$
\frac{3}{x + 2} + \frac{5}{x - 1}
$$

2. Perform the operation and simplify:

$$
\frac{x}{x - 4} - \frac{2}{x + 1}
$$

3. Solve for $x$ and check for extraneous solutions:

$$
\frac{x}{x - 2} - \frac{2}{x + 3}
=
\frac{10}{x^2 + x - 6}
$$

### Solutions

**Problem 1**

$$
\frac{3}{x + 2} + \frac{5}{x - 1}
$$

**1. Find the LCD:**

The least common denominator is:

$$
(x + 2)(x - 1)
$$

**2. Rewrite each fraction with the LCD:**

$$
\frac{3(x - 1)}{(x + 2)(x - 1)}
+
\frac{5(x + 2)}{(x + 2)(x - 1)}
$$

**3. Expand and combine numerators over the common denominator:**

$$
\frac{3x - 3 + 5x + 10}{(x + 2)(x - 1)}
$$

**4. Simplify like terms:**

$$
\frac{8x + 7}{(x + 2)(x - 1)}
$$

**5. Identify restrictions:**

$$
x \neq -2,\,1
$$

**Final Answer:**

$$
\frac{8x + 7}{(x + 2)(x - 1)}, \qquad x \neq -2,\,1
$$

**Problem 2**

$$
\frac{x}{x - 4} - \frac{2}{x + 1}
$$

**1. Find the LCD:**

The least common denominator is:

$$
(x - 4)(x + 1)
$$

**2. Rewrite each fraction with the LCD:**

$$
\frac{x(x + 1)}{(x - 4)(x + 1)}
-
\frac{2(x - 4)}{(x - 4)(x + 1)}
$$

**3. Expand and combine numerators, distributing the negative sign:**

$$
\frac{(x^2 + x) - (2x - 8)}{(x - 4)(x + 1)}
$$

$$
=
\frac{x^2 + x - 2x + 8}{(x - 4)(x + 1)}
$$

**4. Simplify like terms:**

$$
\frac{x^2 - x + 8}{(x - 4)(x + 1)}
$$

**5. Identify restrictions:**

$$
x \neq 4,\,-1
$$

**Final Answer:**

$$
\frac{x^2 - x + 8}{(x - 4)(x + 1)}, \qquad x \neq 4,\,-1
$$

**Problem 3**

$$
\frac{x}{x - 2}
-
\frac{2}{x + 3}
=
\frac{10}{x^2 + x - 6}
$$

**1. Factor denominators and identify restrictions:**

$$
x^2 + x - 6 = (x - 2)(x + 3)
$$

$$
\text{Restrictions: } x \neq 2,\,-3
$$

$$
\text{LCD: } (x - 2)(x + 3)
$$

**2. Multiply every term by the LCD $(x - 2)(x + 3)$ to clear fractions:**

$$
x(x + 3) - 2(x - 2) = 10
$$

**3. Expand terms and solve the resulting quadratic equation:**

$$
x^2 + 3x - 2x + 4 = 10
$$

$$
x^2 + x + 4 = 10
$$

$$
x^2 + x - 6 = 0
$$

**4. Factor the quadratic:**

$$
(x + 3)(x - 2) = 0
$$

$$
x = -3 \quad \text{or} \quad x = 2
$$

**5. Check candidate solutions against restrictions:**

* $x = -3$ causes division by zero $\implies$ **extraneous**

* $x = 2$ causes division by zero $\implies$ **extraneous**

Therefore, both candidate solutions are extraneous.

$$
\text{Final Answer: No Solution }(\emptyset)
$$
