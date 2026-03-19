# Task – Ant Motion (Infinite Alternating Movement)

## Problem Statement

An ant starts at the origin and moves according to the pattern:

- $1$ m east  
- $\frac{1}{2}$ m north  
- $\frac{1}{3}$ m west  
- $\frac{1}{4}$ m south  
- $\frac{1}{5}$ m east  
- and so on  

The task is to determine the final position of the ant.

---

## Theory

The motion can be separated into horizontal and vertical components.

Horizontal motion alternates between east and west:

$$
x = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \cdots
$$

Vertical motion alternates between north and south:

$$
y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \cdots
$$

These are known infinite series.

---

## Step-by-Step Solution

### 1. Horizontal position

The series:

$$
x = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \cdots
$$

is a known alternating series:

$$
x = \frac{\pi}{4}
$$

---

### 2. Vertical position

The series:

$$
y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \cdots
$$

can be written as:

$$
y = \frac{1}{2} \left( 1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \cdots \right)
$$

The series inside parentheses is:

$$
\ln(2)
$$

Thus:

$$
y = \frac{1}{2} \ln(2)
$$

---

## Final Result

The final position of the ant is:

$$
\left( \frac{\pi}{4}, \frac{1}{2} \ln(2) \right)
$$

---

## Interpretation

The ant never stops moving, but the total displacement converges to a finite point.

This occurs because the step lengths decrease over time, forming convergent alternating series.

Thus, despite infinitely many steps, the ant approaches a fixed position in the plane.
