---
title: "260920 – Pseudoscalars, Polar and Axial vectors"
date: 2026-09-20
slug: 260920-pseudoscalars-polar-and-axial-vectors
source: https://theoryofabsolutes.com/260920-pseudoscalars-polar-and-axial-vectors/
categories: [physics]
status: publish
---

# 260920 – Pseudoscalars, Polar and Axial vectors

# Pseudoscalars, Polar Vectors, and Axial Vectors


*Source: Copilot exchange*


---


## What is a pseudoscalar?


A **pseudoscalar** is a quantity that behaves like an ordinary scalar under rotations, but changes sign under a parity transformation (mirror reflection or spatial inversion).


More formally:


A scalar $s$ is unchanged by parity:


$$s(\mathbf{x}) \rightarrow s(-\mathbf{x}) = s$$


A pseudoscalar $p$ picks up a minus sign:


$$p(\mathbf{x}) \rightarrow p(-\mathbf{x}) = -p$$


### Why is it called “pseudo”?


Because it looks like a scalar with respect to rotations. Rotating the coordinate system does not affect its value. The difference only appears when you perform an orientation-reversing transformation such as a mirror reflection.


### Example


Take two polar vectors $\mathbf{a}$ and $\mathbf{b}$.


Their cross product


$$\mathbf{a}\times\mathbf{b}$$


is an axial vector (pseudovector).


Now dot that with another polar vector $\mathbf{c}$:


$$(\mathbf{a}\times\mathbf{b})\cdot\mathbf{c}.$$


This is a scalar number, but under parity:


- $\mathbf{a}$, $\mathbf{b}$, $\mathbf{c}$ each change sign.

- $\mathbf{a}\times\mathbf{b}$ does not change sign because it is axial.

- Therefore the whole quantity changes sign.


Hence


$$(\mathbf{a}\times\mathbf{b})\cdot\mathbf{c}$$


is a pseudoscalar.


Geometrically it represents an oriented volume (the scalar triple product).


### Connection to the Helmholtz decomposition of an axial field


An axial vector field $A_i$ can be Helmholtz-decomposed as


$$A_i = (\nabla\times V)_i + \partial_i\phi_A .$$


Here:


- $\nabla\times V$ is an axial vector if $V$ is polar.

- $\partial_i\phi_A$ must also be axial.


Since $\nabla$ is a polar vector operator, the quantity whose gradient produces an axial vector cannot be an ordinary scalar. It must be a pseudoscalar:


$$\phi_A \xrightarrow{P} -\phi_A.$$


Then


$$\nabla \phi_A$$


transforms as an axial vector.


So the longitudinal part of an axial vector field is indeed encoded in a pseudoscalar potential.


This is why, in theories where the fundamental sources provide no pseudoscalar degree of freedom, one often finds that only the curl-type (transverse) axial component can be sourced independently, while the longitudinal axial component is absent or constrained away.


### In short


|
Quantity |
Under parity |
 |


|
Scalar $s$ |
$s \to s$ |
 |

|
Polar vector $\mathbf{v}$ |
$\mathbf{v}\to-\mathbf{v}$ |
 |

|
Axial vector $\mathbf{A}$ |
$\mathbf{A}\to\mathbf{A}$ |
 |

|
Pseudoscalar $p$ |
$p\to-p$ |
 |


and


$$\boxed{\text{gradient of a pseudoscalar} = \text{axial vector}}$$


which is the key point in the quoted argument.


---


## What is a polar vector?


A **polar vector** is the ordinary kind of vector you first learn in physics.


Examples:


- Position: $\mathbf{r}$

- Velocity: $\mathbf{v}$

- Force: $\mathbf{F}$

- Electric field: $\mathbf{E}$

- Gradient: $\nabla\phi$


The defining property is how it behaves under parity (spatial inversion):


$$(x,y,z)\rightarrow(-x,-y,-z).$$


A polar vector changes sign:


$$\mathbf{v}\rightarrow-\mathbf{v}.$$


For example, position transforms as


$$\mathbf{r}\rightarrow-\mathbf{r}.$$


because every coordinate flips.


### Contrast with an axial vector


An **axial vector** (or pseudovector) does not change sign under parity:


$$\mathbf{A}\rightarrow\mathbf{A}.$$


Examples:


- Angular momentum $\mathbf{L}=\mathbf{r}\times\mathbf{p}$

- Torque $\boldsymbol{\tau}=\mathbf{r}\times\mathbf{F}$

- Magnetic field $\mathbf{B}$


Why?


Because they are built from a cross product of two polar vectors. Under parity:


$$\mathbf{r}\rightarrow-\mathbf{r},\qquad \mathbf{p}\rightarrow-\mathbf{p},$$


so


$$\mathbf{L} = \mathbf{r}\times\mathbf{p} \rightarrow (-\mathbf{r})\times(-\mathbf{p}) = \mathbf{r}\times\mathbf{p}.$$


The two minus signs cancel.


### The connection to pseudoscalars


Notice:


- $\nabla$ is a polar vector operator.

- If $\phi$ is an ordinary scalar, then $\nabla\phi$ is a polar vector.

- If $\phi_A$ is a pseudoscalar, then $\nabla\phi_A$ is an axial vector.


This is because under parity:


$$\nabla\rightarrow-\nabla, \qquad \phi_A\rightarrow-\phi_A,$$


and the two minus signs cancel:


$$\nabla\phi_A \rightarrow \nabla\phi_A.$$


So in the quoted argument, the longitudinal part of an axial field


$$A_i = (\nabla\times V)_i + \partial_i\phi_A$$


requires $\phi_A$ to be a pseudoscalar. That is exactly why the author says the independent longitudinal content of $A_i$ is encoded in a pseudoscalar potential.


### A useful memory aid


|
Object |
Parity transformation |
 |


|
Scalar $s$ |
$s\to s$ |
 |

|
Pseudoscalar $p$ |
$p\to -p$ |
 |

|
Polar vector $\mathbf{v}$ |
$\mathbf{v}\to-\mathbf{v}$ |
 |

|
Axial vector $\mathbf{A}$ |
$\mathbf{A}\to\mathbf{A}$ |
 |


So polar vectors flip under a mirror inversion; axial vectors do not.