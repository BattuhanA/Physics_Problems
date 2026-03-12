# Task 07 – Elimination of Time and Interpretation of Acceleration

## Problem Statement

The motion of a point is given in parametric form

$$
x(t)=2t^2
$$

$$
y(t)=3t^3
$$

Tasks:

- eliminate the parameter $t$
- determine the trajectory
- compute the velocity vector $\vec v(t)$
- compute the speed $|\vec v(t)|$
- compute the acceleration vector $\vec a(t)$
- compute the magnitude $|\vec a(t)|$
- determine whether the acceleration is constant

---

# Theory

For parametric motion

$$
\vec r(t) = (x(t),y(t))
$$

Velocity:

$$
\vec v(t)=\frac{d\vec r}{dt}
$$

Acceleration:

$$
\vec a(t)=\frac{d\vec v}{dt}
$$

Speed:

$$
|\vec v|=\sqrt{v_x^2+v_y^2}
$$

Acceleration magnitude:

$$
|\vec a|=\sqrt{a_x^2+a_y^2}
$$

---

# Step-by-Step Solution

## 1. Elimination of parameter

From

$$
x(t)=2t^2
$$

we obtain

$$
t^2=\frac{x}{2}
$$

$$
t=\sqrt{\frac{x}{2}}
$$

Substitute into the equation for $y$:

$$
y(t)=3t^3
$$

$$
y=3\left(\sqrt{\frac{x}{2}}\right)^3
$$

$$
y=3\left(\frac{x}{2}\right)^{3/2}
$$

Therefore the trajectory is

$$
y = 3\left(\frac{x}{2}\right)^{3/2}
$$

---

## 2. Velocity vector

Velocity components

$$
v_x=\frac{dx}{dt}
$$

$$
v_x=4t
$$

$$
v_y=\frac{dy}{dt}
$$

$$
v_y=9t^2
$$

Velocity vector

$$
\vec v(t)=(4t,9t^2)
$$

---

## 3. Speed

$$
|\vec v|=\sqrt{v_x^2+v_y^2}
$$

$$
|\vec v|=\sqrt{(4t)^2+(9t^2)^2}
$$

$$
|\vec v|=\sqrt{16t^2+81t^4}
$$

$$
|\vec v|=t\sqrt{16+81t^2}
$$

---

## 4. Acceleration vector

$$
a_x=\frac{dv_x}{dt}
$$

$$
a_x=4
$$

$$
a_y=\frac{dv_y}{dt}
$$

$$
a_y=18t
$$

Acceleration vector

$$
\vec a(t)=(4,18t)
$$

---

## 5. Magnitude of acceleration

$$
|\vec a|=\sqrt{a_x^2+a_y^2}
$$

$$
|\vec a|=\sqrt{4^2+(18t)^2}
$$

$$
|\vec a|=\sqrt{16+324t^2}
$$

---

# Final Result

Trajectory

$$
y = 3\left(\frac{x}{2}\right)^{3/2}
$$

Velocity

$$
\vec v(t)=(4t,9t^2)
$$

Acceleration

$$
\vec a(t)=(4,18t)
$$

---

# Interpretation

The acceleration is **not constant** because

$$
a_y = 18t
$$

depends on time.

Therefore the magnitude of acceleration

$$
|\vec a|=\sqrt{16+324t^2}
$$

also changes with time.
