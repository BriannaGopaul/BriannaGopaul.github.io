---
title: "Lecture 2: Multivariable Calculus"
author: "Brianna Gopaul"
date: "2020-08-31"
url: "lecture-2"
...

# Lecture 2 

###  Topic: Vectors in 3D

**Distance Between Points**
<br> 
$P_1(x_1, y_1, z_1)$ and $P_2(x_2, y_2, z_2)$

$d(P_1, P_2) = \sqrt{(x_2-x_1)^2 + (y_2-y_1)^2+(z_2-z_1)^2}$

*EX:* 
Show that $A(3,4,1)$, $B(4,4,6)$, $C(3,1,2)$

$d(AB) = \sqrt{1^2 + 0^2 + 5^2} = \sqrt{26}$

**The 2D Circle Equation becomes a Sphere Equation**: 
$(x-h)^2 + (y-k)^2 + (z-L)^2 = r^2$

**Midpoint Formula**
$(\frac{x_1 + x_2}{2}, \frac{y_1 + y_2}{2}, \frac{z_1 + z_2}{2}$
Center: $(h, k, L)$
Radius: $r$

Just as you would complete the square to find the center and radius of a circle, you'd do the same for spheres. 

**Position Vectors**
<br> 
$/vec{v}$ $= <v_1, v_2, v_3>$ or $\vec{v} = v_1 \hat{i} + v_2 \hat{j} + v_3 \hat{k}$

$||\vec{v}|| = \sqrt{(v_1)^2 + (v_2)^2 + (v_3)^2}$

**Remember:** If two vectors have the same scalar, they're parallel. 

*EX:*
Find $\vec{v}$ such that $||vec|| = 2$ and $\vec{v}$ has the same direction as $\vec{w} = \hat{i} - 2\hat{j} + 3\hat{k}$

First, find the direction of $\vec{w}$: 
$||w|| = \sqrt{1^2 + 2^2 + 3^3} = \sqrt{14}$

Next, find the unit vector since the unit vector tells us the direction $\vec{v}$

$\hat{u}$ $=$ $\frac{\vec{v}}{||\vec{v}||}$
<br> 
$\hat{u} = \frac{\hat{i}-2\hat{j}+3\hat{k}}{\sqrt{14}}$

Since, $\vec{v} = \hat{u} \cdot ||\vec{v}||$ and $||v|| = 2$

$\vec{v} = \frac{\sqrt{14}}{7}(\hat{i}-2\hat{j}+3\hat{k})$

