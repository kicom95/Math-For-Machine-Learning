## 2 Linear Algebra
 * (Page 17)
   * **Linear Algebra** - Study of vectors and certain algebra rules to manipulate vectors.
     * Focuses on the *similarities* between these vector concepts. (Page 18)
 * (Page 17-18)
   * **Vector**
     1. Geometric vectors - intuitions about direction and magnitude
     1. Polynomials
     1. Audio signals
     1. **R^n** (Tuples of n real numbers)
        * Our(This Book's) Focus
        * Closure 
        * Vector Space
 * Concept of Linear Algebra (Page 19)
 ![Concept of Linear Algebra](https://github.com/kicom95/Math-For-Machine-Learning/blob/master/MML/Images/concept%20of%20linear%20algebra.JPG) 
### 2.1 Systems of Linear Equations (연립 일차 방정식)
 * **Readings**
   * [System of linear equations from Wikipedia](https://en.wikipedia.org/wiki/System_of_linear_equations) 
     * General Form
     ![General Form](https://wikimedia.org/api/rest_v1/media/math/render/svg/f50252ba5f1e440c6323e52462ebcd22d1aa7716)
     * Vector Equation
     ![Vector Equation](https://wikimedia.org/api/rest_v1/media/math/render/svg/27012bec5c523ae61a7a760cbf383e2962ede481)
     * Matrix Equation
     ![Matrix Equation](https://wikimedia.org/api/rest_v1/media/math/render/svg/85b8cb94702eb575b664969060eb077ab8ac37a6)
 * (Page 20)
   * for a real-valued system of linear equations we obtain either *no*, *exactly one*, or *infinitely many* **solutions**.
### 2.2 Matrices
 * (Page 22)
   * Compactly represent systems of linear equations.
   * Represent linear functions (linear mappings)
#### 2.2.1 Matrix Addition and Multiplication
 * (Page 23)
   * [Matrix multiplication](https://en.wikipedia.org/wiki/Matrix_multiplication)
     * dot product of the corresponding row and column
     * Fundamental applications
       * Linear Map
       * System of linear equations
   * Hadamard product : element-wise multiplication
   * Indentity Matrix
#### 2.2.2 Inverse and Transpose
 * (Page 24)
   * Inverse
     * Square Matrix Only
     * regular/invertible/nonsingular
       * Inverse Exist
       * When the matrix inverse exists, it is **unique**
     * singular/noninvertible
       * No Inverse Exist
     * determinant - checks whether a matrix is invertible.  
 * (Page 25)
   * Symmetric Matrix
     * Transpose(A) == A
     * Square Matrix Only    
![Inverse Transpose Matrix](https://github.com/kicom95/Math-For-Machine-Learning/blob/master/MML/Images/inverse%20transpose%20matrix.JPG) 
#### 2.2.3 Multiplication by a Scalar
#### 2.2.4 Compact Representations of Systems of Linear Equations
 * (Page 26)
 
 ![Linear Equation in Matrix](https://github.com/kicom95/Math-For-Machine-Learning/blob/master/MML/Images/compact_representation_of_linear_equation.JPG) 
### 2.3 Solving Systems of Linear Equations
 * (Page 27)
   * Matrices can be used as a compact way of formulating systems of linear equations
### 2.3.1 Solving Systems of Linear Equations
 * (Page 27)
   * Particular (Special) Solution
   * General Solution
   * Combination of Particular Solution and General Solution
### 2.3.2 Elementary Transformations  
* (Page 29)   
  * [Elementary Transformations](https://en.wikipedia.org/wiki/Elementary_matrix#Operations)
    * Exchange of two equations (rows in the matrix representing the system of equations
    * Multiplication of an equation (row) with a constant 
    * Addition of two equations (rows)
  * [Augmented matrix](https://en.wikipedia.org/wiki/Augmented_matrix)  
    * A matrix obtained by appending the columns of two given matrices, usually for the purpose of performing the same elementary row operations 
    * The augmented matrix compactly represents the system of linear equations
* (Page 30)
  * [Row-Echelon Form](https://en.wikipedia.org/wiki/Row_echelon_form)
    * A matrix is in echelon form if it has the shape resulting from a Gaussian elimination
    * All rows consisting of only zeroes are at the bottom.
    * The leading coefficient (also called the *pivot*) of a nonzero row is always strictly to the right of the leading coefficient of the row above it.
    * ![Row-Echelon Form](https://wikimedia.org/api/rest_v1/media/math/render/svg/3743aca294b2e5346c167819fd9ee0bcb79ef22c)
      * Basic Variables - variables corresponding to the pivots in the row-echelon
        * x1, x3, x4
      * Free Variables  - other than basic variable
        * x2, x5
* (Page 31)
  * Reduced Row Echelon Form
    * It is in row-echelon form.
    * Every pivot is 1.
    * The pivot is the only nonzero entry in its column.
* (Page 32)
  * Gaussian elimination
  * Gauss–Jordan elimination
    *  finding the inverse of a matrix (Square Matrix Only)
### 2.3.4 Algorithms for Solving a System of Linear Equations
* (Page 34)
  * Solution does Not Exist
    * approximate solutions : Linear Regression
  * Solution Exist
    * Inverse : Square Matrix Only
    * Moore-Penrose pseudo-inverse
   
![Moore-Penrose pseudo-inverse](https://github.com/kicom95/Math-For-Machine-Learning/blob/master/MML/Images/Moore-Penrose%20pseudo-inverse.JPG)

## 2.4 Vector Spaces
* (Page 35)
 * structured space in which vectors live.
### 2.4.1 Group

 
