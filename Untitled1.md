

```python
from IPython.display import Math, Latex
```

Chapter I. Introduction (소개)
============


As the authors pointed out, the book is intended for **anyone** who wants to learn modern statistical learning. However, you would probably need to know very basic math such as functions and simple linear algebra(matrix operations).
For example, you should know something like this:
Suppose $ y = f(x) = x^2.$  
If $ x = 3 $, then $ y = f(3) = 3^2 = 9 $.

Or something like these:
$
\begin{bmatrix}
    1       & 2  \\
    3       & 4 
\end{bmatrix}^{-1}
= \frac{1}{1 \cdot 4-3 \cdot 2}\begin{bmatrix}
    4       & -2  \\
    -3       & 1 
\end{bmatrix}
$

For $
\begin{bmatrix}
    a       & b  \\
    c       & d 
\end{bmatrix}
$, 
$
\begin{bmatrix}
    a       & b  \\
    c       & d 
\end{bmatrix}^{-1}
$
does not exist if $ D(X) = ad-bc = 0$


Throughout this lecture, we will use the notation used in the textbook.

Let
\begin{equation}
\textbf{X} =
\begin{bmatrix}
    x_{11}       & x_{12} & x_{31} & \dots & x_{1p} \\
    x_{21}       & x_{22} & x_{23} & \dots & x_{2p} \\
    \vdots       & \vdots & \vdots & \vdots & \vdots \\
    x_{n1}       & x_{n2} & x_{n3} & \dots & x_{np}
\end{bmatrix}_{n \times p}\end{equation}
Then,
\begin{equation}
\mathbf{X^{T}} =
\begin{bmatrix}
    x_{11}       & x_{21} & x_{31} & \dots & x_{n1} \\
    x_{12}       & x_{22} & x_{32} & \dots & x_{n2} \\
    \vdots       & \vdots & \vdots & \vdots & \vdots \\
    x_{1p}       & x_{2p} & x_{3p} & \dots & x_{np}
\end{bmatrix}_{p \times n}\end{equation}

We define j-th column of $X$ as
\begin{equation} \mathbf{x_j} = 
\begin{bmatrix}
    x_{1j}  \\
    x_{2j}  \\
    \vdots  \\
    x_{nj}  
\end{bmatrix}_{n \times 1}\end{equation}

Then, 
\begin{equation}
\mathbf{X} =
\begin{bmatrix}
    \mathbf{x_{1}} & \mathbf{x_{2}} & \mathbf{x_{3}} & \dots & \mathbf{x_{p}}
\end{bmatrix}_{n \times 1}\end{equation}


Further,
\begin{equation}
\mathbf{y} =
\begin{bmatrix}
    y_{1}  \\
    y_{2}  \\
    \vdots  \\
    y_{n}  
\end{bmatrix}_{n \times 1}\end{equation}

\begin{equation}
\mathbf{a} =
\begin{bmatrix}
    a_{1}  \\
    a_{2}  \\
    \vdots  \\
    a_{n}  
\end{bmatrix}_{n \times 1}\end{equation}



```python

```
