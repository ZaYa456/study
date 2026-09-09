---
title: Exponents & Radicals
parent: Prerequisites
grand_parent: Math
nav_order: 2
---

# Exponents & Radicals

## Part 1: Exponent Laws & Negative Exponents

### Core Execution Rules

Mastering exponents requires applying operations to bases with identical variables:

- **Product Rule:** $$x^a \cdot x^b = x^{a+b}$$
- **Quotient Rule:** $$\frac{x^a}{x^b} = x^{a-b}$$
- **Power Rule:** $$(x^a)^b = x^{a \cdot b}$$
- **Power of a Product/Quotient:** $$(xy)^a = x^a y^a \quad \text{and} \quad \left(\frac{x}{y}\right)^a = \frac{x^a}{y^a}$$
- **Zero Exponent Rule:** $$x^0 = 1 \quad (x \neq 0)$$
- **Negative Exponent Rule:** $$x^{-a} = \frac{1}{x^a} \quad \text{and} \quad \left(\frac{x}{y}\right)^{-a} = \left(\frac{y}{x}\right)^a$$

### Worked Reference Example

Simplify completely and express the answer with positive exponents:

$$\left(\frac{2x^3 y^{-2}}{4x^{-1} y^4}\right)^{-2}$$

1. **Simplify the expression inside the parentheses first:**
   - Coefficient: $$\frac{2}{4} = \frac{1}{2}$$
   - $$x$$-terms: $$\frac{x^3}{x^{-1}} = x^{3 - (-1)} = x^4$$
   - $$y$$-terms: $$\frac{y^{-2}}{y^4} = y^{-2 - 4} = y^{-6}$$

$$\left(\frac{x^4 y^{-6}}{2}\right)^{-2}$$

2. **Invert the fraction to make the outer exponent positive:**

$$\left(\frac{2}{x^4 y^{-6}}\right)^2 = \left(\frac{2 y^6}{x^4}\right)^2$$

3. **Apply the power rule to every factor inside:**

$$\frac{2^2 \cdot (y^6)^2}{(x^4)^2} = \frac{4y^{12}}{x^8}$$

### Practice Problems

Simplify each expression completely and write all final answers with positive exponents:

1. $$(3x^2 y^{-3}) \cdot (2x^{-4} y^5)$$
2. $$\frac{12a^5 b^{-2}}{4a^{-3} b^3}$$
3. $$\left(\frac{2x^{-2} y^3}{z^{-1}}\right)^{-3}$$

### Solutions

**Problem 1**

$$(3x^2 y^{-3}) \cdot (2x^{-4} y^5)$$

1. Multiply coefficients:

$$3 \cdot 2 = 6$$

2. Apply the product rule ($$x^a \cdot x^b = x^{a+b}$$) to variable terms:
   - $$x$$-terms: $$x^{2 + (-4)} = x^{-2}$$
   - $$y$$-terms: $$y^{-3 + 5} = y^2$$

3. Combine and rewrite with positive exponents:

$$6x^{-2}y^2 = \frac{6y^2}{x^2}$$

**Problem 2**

$$\frac{12a^5 b^{-2}}{4a^{-3} b^3}$$

1. Divide coefficients:

$$\frac{12}{4} = 3$$

2. Apply the quotient rule ($$\frac{x^a}{x^b} = x^{a-b}$$) to variable terms:
   - $$a$$-terms: $$a^{5 - (-3)} = a^{5 + 3} = a^8$$
   - $$b$$-terms: $$b^{-2 - 3} = b^{-5}$$

3. Combine and rewrite with positive exponents:

$$3a^8 b^{-5} = \frac{3a^8}{b^5}$$

**Problem 3**

$$\left(\frac{2x^{-2} y^3}{z^{-1}}\right)^{-3}$$

1. Simplify the terms inside the parentheses first by moving negative exponents:

$$\frac{2y^3 z^1}{x^2}$$

2. Apply the negative outer exponent by inverting the entire fraction:

$$\left(\frac{x^2}{2y^3 z}\right)^3$$

3. Distribute the power of $$3$$ to every factor in the numerator and denominator:

$$\frac{(x^2)^3}{2^3 \cdot (y^3)^3 \cdot z^3} = \frac{x^6}{8y^9 z^3}$$

## Part 2: Radicals & Fractional Exponents

### Core Execution Rules

Radicals and fractional exponents represent the exact same mathematical operations expressed in different notations. Converting radicals to rational exponents allows you to use standard exponent laws:

- **Equivalence Definition:** $$x^{a/b} = \sqrt[b]{x^a} = (\sqrt[b]{x})^a$$
- **Product Property of Radicals:** $$\sqrt[n]{a \cdot b} = \sqrt[n]{a} \cdot \sqrt[n]{b}$$
- **Quotient Property of Radicals:** $$\sqrt[n]{\frac{a}{b}} = \frac{\sqrt[n]{a}}{\sqrt[n]{b}}$$
- **Simplifying Radicals:** factor the radicand into perfect $$n$$-th powers and extract them.
- **Rationalizing Denominators:** eliminate radicals from denominators by multiplying the numerator and denominator by the conjugate ($$a - b$$ becomes $$a + b$$).

### Worked Reference Example

Simplify completely:

$$\sqrt{50x^5y^6} \cdot (8x^3y^9)^{1/3}$$

1. **Simplify the square root term** $$\sqrt{50x^5y^6}$$:
   - Split into perfect squares: $$\sqrt{25 \cdot 2 \cdot x^4 \cdot x \cdot y^6}$$
   - Extract root terms: $$5x^2y^3\sqrt{2x}$$

2. **Evaluate the fractional exponent term** $$(8x^3y^9)^{1/3}$$:
   - Apply power rule to coefficients and variables:

$$8^{1/3} \cdot (x^3)^{1/3} \cdot (y^9)^{1/3} = 2x^{3/3}y^{9/3} = 2xy^3$$

3. **Multiply the resulting terms together:**

$$(5x^2y^3\sqrt{2x}) \cdot (2xy^3) = (5 \cdot 2) \cdot (x^2 \cdot x) \cdot (y^3 \cdot y^3) \cdot \sqrt{2x} = 10x^3y^6\sqrt{2x}$$

### Practice Problems

Simplify each expression completely, writing all radicals in simplest form and converting negative/fractional exponents where appropriate:

1. $$\sqrt{72x^7 y^4}$$
2. $$(27x^6 y^{-3})^{2/3}$$
3. $$\frac{6}{\sqrt{5} - 1}$$

### Solutions

**Problem 1**

$$\sqrt{72x^7 y^4}$$

1. Break down the radicand into perfect square factors:

$$\sqrt{(36 \cdot 2) \cdot (x^6 \cdot x) \cdot y^4}$$

2. Extract square roots of perfect square terms ($$\sqrt{36} = 6$$, $$\sqrt{x^6} = x^3$$, $$\sqrt{y^4} = y^2$$):

$$6x^3y^2 \sqrt{2x}$$

**Problem 2**

$$(27x^6 y^{-3})^{2/3}$$

1. Distribute the fractional power $$2/3$$ to each factor using the power rule $$(a \cdot b)^n = a^n b^n$$:

$$27^{2/3} \cdot (x^6)^{2/3} \cdot (y^{-3})^{2/3}$$

2. Evaluate each component:
   - Coefficient: $$27^{2/3} = (\sqrt[3]{27})^2 = 3^2 = 9$$
   - $$x$$-term: $$(x^6)^{2/3} = x^{6 \cdot \frac{2}{3}} = x^4$$
   - $$y$$-term: $$(y^{-3})^{2/3} = y^{-3 \cdot \frac{2}{3}} = y^{-2}$$

3. Combine and express with a positive exponent:

$$9x^4y^{-2} = \frac{9x^4}{y^2}$$

**Problem 3**

$$\frac{6}{\sqrt{5} - 1}$$

1. Rationalize the denominator by multiplying numerator and denominator by the conjugate $$(\sqrt{5} + 1)$$:

$$\frac{6(\sqrt{5} + 1)}{(\sqrt{5} - 1)(\sqrt{5} + 1)}$$

2. Expand the denominator using the difference of squares $$(a-b)(a+b) = a^2 - b^2$$:

$$\frac{6(\sqrt{5} + 1)}{(\sqrt{5})^2 - 1^2} = \frac{6(\sqrt{5} + 1)}{5 - 1} = \frac{6(\sqrt{5} + 1)}{4}$$

3. Simplify the fraction by dividing numerator and denominator by $$2$$:

$$\frac{3(\sqrt{5} + 1)}{2} \quad \text{or} \quad \frac{3\sqrt{5} + 3}{2}$$
