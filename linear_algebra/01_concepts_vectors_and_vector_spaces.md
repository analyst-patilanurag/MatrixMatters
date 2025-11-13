# 📘 Vectors and Vector Spaces

This document provides the **theoretical foundation** for the notebooks in this repository.  
Each concept includes intuitive explanations, formulas, and clean mathematical notation.

---

## 🧩 1. Vectors as Ordered Lists / Feature Vectors

A **vector** is an ordered list of real numbers representing a point or direction in an $n$-dimensional space:

$\mathbf{v} = \begin{bmatrix} v_1 \\ v_2 \\ \vdots \\ v_n \end{bmatrix} \in \mathbb{R}^n$

\[\mathbf{v} =\begin{bmatrix}v_1 \\v_2 \\\vdots \\v_n\end{bmatrix}\in \mathbb{R}^n\]

Examples:
- 2D point: $\mathbf{v} = [3, 2]$
- Document feature vector (word counts): $\mathbf{x} = [5, 0, 3, 1]$

Vectors are the building blocks for all linear algebra in machine learning, NLP, and deep learning.

---

## ➕ 2. Vector Addition and Scalar Multiplication

### **Vector addition** (component-wise):

$\mathbf{u} + \mathbf{v} =\begin{bmatrix}u_1 + v_1 \\u_2 + v_2 \\\vdots \\u_n + v_n\end{bmatrix}$

### **Scalar multiplication**:

$\c\mathbf{v} =\begin{bmatrix}c v_1 \\c v_2 \\\vdots \\c v_n\end{bmatrix}$

These operations let us combine or scale vectors while staying inside the same space.

---

## 🧮 3. Vector Space (Informal Definition)

A **vector space** over $\mathbb{R}$ is a set of vectors that allows:

- vector addition  
- scalar multiplication  

and satisfies:

1. **Closure under addition:**  
   If $\mathbf{u}, \mathbf{v} \in V$, then $\mathbf{u} + \mathbf{v} \in V$.

2. **Closure under scalar multiplication:**  
   If $c \in \mathbb{R}$ and $\mathbf{v} \in V$, then $c\mathbf{v} \in V$.

3. **Zero vector:**  
   There exists $\mathbf{0}$ such that $\mathbf{v} + \mathbf{0} = \mathbf{v}$.

4. **Additive inverse:**  
   For each $\mathbf{v} \in V$, there exists $-\mathbf{v}$ such that  
   $\mathbf{v} + (-\mathbf{v}) = \mathbf{0}$.

This is the structure behind all linear modeling, dimensionality reduction, and embeddings.

---

## 🧠 4. Linear Combinations and Span

A **linear combination** of vectors $\mathbf{v}_1,\dots,\mathbf{v}_k$ is:

$\mathbf{x} = c_1\mathbf{v}_1 + c_2\mathbf{v}_2 + \dots + c_k\mathbf{v}_k,
\qquad c_i \in \mathbb{R}$

The **span** of these vectors is all possible linear combinations:

$
\text{span}\{\mathbf{v}_1,\dots,\mathbf{v}_k\}= \left\{c_1\mathbf{v}_1 + \dots + c_k\mathbf{v}_k \;\middle|\; c_i \in \mathbb{R}\right\}$

Interpretation:
- Span = everything we can construct by mixing given vectors  
- If the span covers all of $\mathbb{R}^n$, the set **spans** $\mathbb{R}^n$  
- If one vector can be written from others → **linear dependence**

