# Week 01 (19/2/25 - 19/3/1)

* Lecture
  * Introduction to vectors and linear equations
  * Elimination method
* Recitation
  * Introduction to Python programming.
  * Installing Python IDEs.

## Lecture 01 (19/2/25)

### To Do
* Overview syllabus
  * Emphasize homework policy
  * Explain the purpose of the project
* Checking roster
* Split recitation classes
  * Check available time

### Contents (1.1 - 1.4)

* Notations
  * Define vector notations: tuple, column, or row representations.
  * Define matrix addition, multiplication, scalar multiplications. 
  * Upshots for using row / column reprensetations of vectors. 

* System of linear equations
  * Example: 
    $$\begin{array}{rl} 2u + v + w &= 5 \\
    4u -6v &= -2\\
    -2u +7v + 2w &= 9\end{array}$$
  * Finding solution(s)
    * Elimination method converts to:
      $$\begin{array}{rl} 2u + v + w &= 5 \\
      -8v -2w &= -12\\
      w &= 2\end{array}$$
    * Define **pivots**.
    * Matrix representation $Ax = b$ where
      $$A = \begin{bmatrix} 2 & 1 & 1 \\ 4 & -6 & 0 \\ -2 & 7 & 2 \end{bmatrix},\quad x = \begin{bmatrix} u \\ v \\ w \end{bmatrix},\quad b =\begin{bmatrix}5 \\ -2 \\ 9 \end{bmatrix}$$
  * Geometric meaning of system of linear equations with 3 variables.
    * Definition: **Singular, nonsingular** systems.
    * **Q** Classify the geometric position of planes in three cases: (1) there is a unique solution, (2) there are infinitely many solutions, (3) no solution
  * Vector representation
    * Let $A = \begin{bmatrix}a_1&a_2&a_3\end{bmatrix}$, and write $Ax = b$ as
      $$a_1u + a_2v + a_3w = b$$
    * **Q** In what condition(s) of $a_1,a_2,a_3$, and $b$ is there a unique solution to the system? (Similarly for infinitely many solutions and no solution)

### Timeline

* (0 ~ 10 min) Syllabus
* (10 ~ 15 min) Roster and recitation availability check
* (15 ~ 55 min) Lecture on main contents (English)
* (55 ~ 75 min) Discussion on questions (Korean)

## Lecture 02 (19/2/28)

### To Do

* Review previous lecture
* Check roster
* Announce homework assignment #01

### Contents (1.5 - 1.6)

* $LU$ (and $LDU$) decomposition.
  * Definition: **Upper / lower triangular matrices, echelon form.** 
    * **Q** Show that the multiple of two lower (or upper) triangular matrices is also lower (or upper) triangular.
    * Example: 
      $$A = \begin{bmatrix} 2 & 1 & 1 \\ 4 & -6 & 0 \\ -2 & 7 & 2 \end{bmatrix}$$
  * Elementary row operations: $E_{ij}(c)$, $P_{ij}$
   * Example:
      $$A = \begin{bmatrix} 1 & 1 & 1 \\ 1 & 1 & 3 \\ 2 & 5 & 8 \end{bmatrix}$$
    * **Q** Show that if $A$ is nonsingular, then there exists a permutation matrix $P$ such that $PA=LU$.
  * Uniqueness: if $A = L_1DU_1 = L_2DU_2$, then $L_1 = L_2$ and $U_1 = U_2$.
* Inverse matrix
  * Definition and meaning
    * $A^{-1}A = I$, $AA^{-1} = I$
    * Nonsingular system and inverse matrix.
  * Gauss-Jordon elimination.
* Transpose and symmetric matrices
  * Property : $(AB)^T = B^TA^T$, $(A^{-1})^T = (A^T)^{-1}$
  * $LDU$ factorization of symmetric matrix: $LDL^T$

### Timeline

* (0 ~ 5 min) Review
* (5 ~ 10 min) Questions, roster
* (10 ~ 55 min) Lecture on contents (English)
* (55 ~ 75 min) Discussion (Korean)

