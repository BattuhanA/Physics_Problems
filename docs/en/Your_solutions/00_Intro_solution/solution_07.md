# Task – Fly Between Bicycle and Wall

## Problem Statement

A bicycle is $10 \text{ m}$ from a wall and moves toward it at a constant speed of $1 \text{ m/s}$.  

A fly starts from the bicycle and flies toward the wall at $2 \text{ m/s}$.  

Each time it reaches the wall or the bicycle, it instantly turns back and continues flying.  

The task is to determine the **total distance traveled by the fly before it is crushed**.

---

## Theory

The key observation is that both the bicycle and the fly move over the **same time interval**.

The bicycle moves with constant velocity:

$$
v_b = 1 \text{ m/s}
$$

The fly moves with constant velocity:

$$
v_f = 2 \text{ m/s}
$$

Distance is given by:

$$
d = v \cdot t
$$

---

## Step-by-Step Solution

### 1. Time until collision

The bicycle travels $10 \text{ m}$ toward the wall:

$$
t = \frac{10}{1}
$$

$$
t = 10 \text{ s}
$$

This is the total time during which the fly is moving.

---

### 2. Distance traveled by the fly

The fly moves continuously for $10 \text{ s}$ at a constant speed of $2 \text{ m/s}$:

$$
d = v_f \cdot t
$$

$$
d = 2 \cdot 10
$$

$$
d = 20 \text{ m}
$$

---

## Final Result

$$
d = 20 \text{ m}
$$

---

## Interpretation

Although the fly changes direction infinitely many times, it always moves during the same total time interval of $10 \text{ s}$.

Instead of summing infinitely many back-and-forth distances, the problem reduces to a simple observation:

- the fly flies continuously
- the total flying time equals the time for the bicycle to reach the wall

Thus, the total distance depends only on the fly’s speed and total time of motion.
