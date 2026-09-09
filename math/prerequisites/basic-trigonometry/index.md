---

title: Basic Trigonometry
parent: Prerequisites
grand_parent: Math
nav_order: 5
------------

**# Basic Trigonometry**

## Module 5, Part 1: Trigonometric Ratios & Right Triangle Trigonometry

### Core Definitions & Ratios

In a right triangle, the six primary trigonometric ratios are defined relative to a chosen angle $\theta$.

* **Opposite:** The side directly across from angle $\theta$.
* **Adjacent:** The side next to angle $\theta$, excluding the hypotenuse.
* **Hypotenuse:** The side opposite the right angle and the longest side of the triangle.

**Primary Ratios**

$$
\sin(\theta) = \frac{\text{Opposite}}{\text{Hypotenuse}}
$$

$$
\cos(\theta) = \frac{\text{Adjacent}}{\text{Hypotenuse}}
$$

$$
\tan(\theta) = \frac{\text{Opposite}}{\text{Adjacent}}
$$

**Reciprocal Ratios**

$$
\csc(\theta) = \frac{1}{\sin(\theta)} = \frac{\text{Hypotenuse}}{\text{Opposite}}
$$

$$
\sec(\theta) = \frac{1}{\cos(\theta)} = \frac{\text{Hypotenuse}}{\text{Adjacent}}
$$

$$
\cot(\theta) = \frac{1}{\tan(\theta)} = \frac{\text{Adjacent}}{\text{Opposite}}
$$

### Worked Reference Example

A right triangle has an adjacent side of $5$ and an opposite side of $12$ relative to angle $\theta$.

First, find the hypotenuse using the Pythagorean theorem:

$$
5^2 + 12^2 = h^2
$$

$$
25 + 144 = h^2
$$

$$
169 = h^2
$$

$$
h = 13
$$

Therefore:

$$
\sin(\theta) = \frac{12}{13}
$$

$$
\cos(\theta) = \frac{5}{13}
$$

$$
\tan(\theta) = \frac{12}{5}
$$

**Final Answer:**

$$
\boxed{\sin(\theta)=\frac{12}{13},\quad
\cos(\theta)=\frac{5}{13},\quad
\tan(\theta)=\frac{12}{5}}
$$

### Practice Problems

**Problem 1**

A right triangle has a hypotenuse of $10$ and $\sin(\theta)=\frac{3}{5}$.

Find the opposite and adjacent sides.

**Problem 2**

Given:

$$
\cos(\theta)=\frac{8}{17}
$$

Find the exact values of $\sin(\theta)$ and $\tan(\theta)$.

**Problem 3**

In right triangle $ABC$, $\angle C=90^\circ$. The side opposite angle $A$ is $7$, and the side opposite angle $B$ is $24$.

Find:

$$
\sec(A),\quad \cot(A)
$$

### Solutions

**Problem 1**

Given:

$$
\sin(\theta)=\frac{\text{Opposite}}{\text{Hypotenuse}}=\frac{3}{5}
$$

The hypotenuse is $10$, so:

$$
\frac{\text{Opposite}}{10}=\frac{3}{5}
$$

$$
\text{Opposite}=6
$$

Now use the Pythagorean theorem:

$$
6^2+\text{Adjacent}^2=10^2
$$

$$
36+\text{Adjacent}^2=100
$$

$$
\text{Adjacent}^2=64
$$

$$
\text{Adjacent}=8
$$

**Final Answer:**

$$
\boxed{\text{Opposite}=6,\quad \text{Adjacent}=8}
$$

**Problem 2**

Given:

$$
\cos(\theta)=\frac{8}{17}
$$

Therefore:

$$
\frac{\text{Adjacent}}{\text{Hypotenuse}}=\frac{8}{17}
$$

Take the adjacent side as $8$ and the hypotenuse as $17$.

Using the Pythagorean theorem:

$$
8^2+\text{Opposite}^2=17^2
$$

$$
64+\text{Opposite}^2=289
$$

$$
\text{Opposite}^2=225
$$

$$
\text{Opposite}=15
$$

Therefore:

$$
\sin(\theta)=\frac{15}{17}
$$

and

$$
\tan(\theta)=\frac{15}{8}
$$

**Final Answer:**

$$
\boxed{\sin(\theta)=\frac{15}{17},\quad
\tan(\theta)=\frac{15}{8}}
$$

**Problem 3**

The legs are $7$ and $24$. Find the hypotenuse:

$$
7^2+24^2=h^2
$$

$$
49+576=h^2
$$

$$
625=h^2
$$

$$
h=25
$$

Relative to angle $A$:

* Opposite side = $7$
* Adjacent side = $24$
* Hypotenuse = $25$

Therefore:

$$
\sec(A)=\frac{\text{Hypotenuse}}{\text{Adjacent}}
=\frac{25}{24}
$$

and

$$
\cot(A)=\frac{\text{Adjacent}}{\text{Opposite}}
=\frac{24}{7}
$$

**Final Answer:**

$$
\boxed{\sec(A)=\frac{25}{24},\quad
\cot(A)=\frac{24}{7}}
$$

---

## Module 5, Part 2: Special Right Triangles & The Unit Circle

### Core Concepts & Rules

**1. Special Right Triangles**

**$45^\circ-45^\circ-90^\circ$ Triangle**

The side ratio is:

$$
1:1:\sqrt{2}
$$

Therefore:

$$
\sin(45^\circ)=\cos(45^\circ)=\frac{\sqrt{2}}{2}
$$

$$
\tan(45^\circ)=1
$$

**$30^\circ-60^\circ-90^\circ$ Triangle**

The side ratio is:

$$
1:\sqrt{3}:2
$$

Therefore:

$$
\sin(30^\circ)=\frac{1}{2}
$$

$$
\cos(30^\circ)=\frac{\sqrt{3}}{2}
$$

$$
\tan(30^\circ)=\frac{\sqrt{3}}{3}
$$

And:

$$
\sin(60^\circ)=\frac{\sqrt{3}}{2}
$$

$$
\cos(60^\circ)=\frac{1}{2}
$$

$$
\tan(60^\circ)=\sqrt{3}
$$

**2. Degree-Radian Conversion**

To convert degrees to radians:

$$
\text{Radians}=\text{Degrees}\cdot\frac{\pi}{180}
$$

To convert radians to degrees:

$$
\text{Degrees}=\text{Radians}\cdot\frac{180}{\pi}
$$

**3. Unit Circle Definitions**

On the unit circle:

$$
x=\cos(\theta)
$$

$$
y=\sin(\theta)
$$

Therefore:

$$
(\cos(\theta),\sin(\theta))
$$

represents the coordinates of the point corresponding to angle $\theta$.

Since:

$$
\tan(\theta)=\frac{\sin(\theta)}{\cos(\theta)}
$$

we also have:

$$
\tan(\theta)=\frac{y}{x},\quad x\neq0
$$

**4. ASTC Quadrant Signs**

The signs of trigonometric functions depend on the quadrant:

* **Quadrant I:** All functions are positive.
* **Quadrant II:** Sine is positive.
* **Quadrant III:** Tangent is positive.
* **Quadrant IV:** Cosine is positive.

A useful mnemonic is:

**A-S-T-C**

* **A:** All
* **S:** Sine
* **T:** Tangent
* **C:** Cosine

**5. Reference Angles**

The reference angle $\theta_r$ is the acute angle between the terminal side of $\theta$ and the nearest $x$-axis.

For Quadrant II:

$$
\theta_r=180^\circ-\theta
$$

For Quadrant III:

$$
\theta_r=\theta-180^\circ
$$

For Quadrant IV:

$$
\theta_r=360^\circ-\theta
$$

### Worked Reference Example

Find the exact values of:

$$
\sin\left(\frac{5\pi}{6}\right),\quad
\cos\left(\frac{5\pi}{6}\right),\quad
\tan\left(\frac{5\pi}{6}\right)
$$

First identify the quadrant.

$$
\frac{5\pi}{6}=150^\circ
$$

Therefore, the angle lies in **Quadrant II**.

The reference angle is:

$$
180^\circ-150^\circ=30^\circ
$$

From the special-angle values:

$$
\sin(30^\circ)=\frac{1}{2}
$$

$$
\cos(30^\circ)=\frac{\sqrt{3}}{2}
$$

$$
\tan(30^\circ)=\frac{\sqrt{3}}{3}
$$

In Quadrant II, sine is positive while cosine and tangent are negative.

Therefore:

$$
\sin\left(\frac{5\pi}{6}\right)=\frac{1}{2}
$$

$$
\cos\left(\frac{5\pi}{6}\right)=-\frac{\sqrt{3}}{2}
$$

$$
\tan\left(\frac{5\pi}{6}\right)=-\frac{\sqrt{3}}{3}
$$

**Final Answer:**

$$
\boxed{
\sin\left(\frac{5\pi}{6}\right)=\frac{1}{2},\quad
\cos\left(\frac{5\pi}{6}\right)=-\frac{\sqrt{3}}{2},\quad
\tan\left(\frac{5\pi}{6}\right)=-\frac{\sqrt{3}}{3}
}
$$

### Practice Problems

**Problem 1**

Find the exact values of:

$$
\sin(135^\circ),\quad \cos(135^\circ)
$$

**Problem 2**

Find:

$$
\tan\left(\frac{4\pi}{3}\right)
$$

**Problem 3**

Convert $240^\circ$ to radians and find the corresponding unit-circle coordinates.

### Solutions

**Problem 1**

$135^\circ$ lies in Quadrant II.

The reference angle is:

$$
180^\circ-135^\circ=45^\circ
$$

Since:

$$
\sin(45^\circ)=\frac{\sqrt{2}}{2}
$$

and sine is positive in Quadrant II:

$$
\sin(135^\circ)=\frac{\sqrt{2}}{2}
$$

Since:

$$
\cos(45^\circ)=\frac{\sqrt{2}}{2}
$$

and cosine is negative in Quadrant II:

$$
\cos(135^\circ)=-\frac{\sqrt{2}}{2}
$$

**Final Answer:**

$$
\boxed{
\sin(135^\circ)=\frac{\sqrt{2}}{2},\quad
\cos(135^\circ)=-\frac{\sqrt{2}}{2}
}
$$

**Problem 2**

First identify the quadrant:

$$
\frac{4\pi}{3}=240^\circ
$$

Therefore, the angle lies in Quadrant III.

The reference angle is:

$$
240^\circ-180^\circ=60^\circ
$$

Since tangent is positive in Quadrant III:

$$
\tan\left(\frac{4\pi}{3}\right)=\tan(60^\circ)
$$

Therefore:

$$
\boxed{\tan\left(\frac{4\pi}{3}\right)=\sqrt{3}}
$$

**Problem 3**

Convert $240^\circ$ to radians:

$$
240^\circ\cdot\frac{\pi}{180}
$$

$$
=\frac{4\pi}{3}
$$

Therefore:

$$
240^\circ=\frac{4\pi}{3}
$$

The angle lies in Quadrant III.

The corresponding unit-circle coordinates are:

$$
\left(\cos\left(\frac{4\pi}{3}\right),
\sin\left(\frac{4\pi}{3}\right)\right)
$$

Using the $60^\circ$ reference angle:

$$
\cos\left(\frac{4\pi}{3}\right)=-\frac{1}{2}
$$

$$
\sin\left(\frac{4\pi}{3}\right)=-\frac{\sqrt{3}}{2}
$$

Therefore:

$$
\boxed{
\frac{4\pi}{3},\quad
\left(-\frac{1}{2},-\frac{\sqrt{3}}{2}\right)
}
$$
