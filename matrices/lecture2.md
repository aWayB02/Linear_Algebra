# Основные операции над матрицами

### Умножение матрицы на число.

Чтобы умножить матрицу на число, нужно все ее элементы умножить на это число. Например:  
  
$$
3 \cdot
\begin{pmatrix}
  1 & 2 \\
  4 & 5 \\
\end{pmatrix} = 
\begin{pmatrix}
  3 \cdot 1 & 3 \cdot 2 \\
  3 \cdot 4 & 3 \cdot 5 \\
\end{pmatrix} =
\begin{pmatrix}
  3 & 6 \\
  12 & 15 \\
\end{pmatrix}
$$


### Сложение матриц

Если $A = [a_{ij}]$, и $B = [b_{ij}]$, — матрицы одинаково размера $m \times n$, то их суммой $C = A + B$ называется матрица $C = [c_{ij}]$ того же размера, такая что:  
$c_{ij} = a_{ij} + b_{ij} \quad \forall i \in \{1,\dots,m\}, \\ \forall j \in \{1,\dots,n\}$

Например:  


$$
\begin{pmatrix}
  1 & 2 \\
  4 & 5 \\
\end{pmatrix} + 
\begin{pmatrix}
  3 & 6 \\
  12 & 15 \\
\end{pmatrix} =
\begin{pmatrix}
  1 + 3 & 2 + 6 \\
  4 + 12 & 5 + 15 \\
\end{pmatrix} = 
\begin{pmatrix}
  4 & 8 \\
  16 & 20 \\
\end{pmatrix}
$$


### Умножение матриц

Пусть $A = [a_{ij}]$, $m \times n$ и $B = [b_{ij}]$, $n \times k$
