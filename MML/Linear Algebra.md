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
* **Readings**
  * [Group](https://en.wikipedia.org/wiki/Group_(mathematics))
    *  a set equipped with a binary operation that combines any two elements to form a third element in such a way that four conditions called group axioms are satisfied, namely closure, associativity, identity and invertibility. 
* (Page 36)
  * closure
  * associativity
  * neutral element
  * inverse element 
  * commutative - **Abelian group**
* (Page 37)
  * Example
    * the set of m x n-matrices is Abelian (with componentwise addition )
    * the set of **regular** (*invertible*) n x n-matrices with matrix multiplication - **General Linear Group**
      * Indenity matrix
    
### 2.4.2 Vector Space
* (Page 38)
  * A vector space (also called a linear space) is a collection of objects called vectors, which may be added together and multiplied ("scaled") by numbers, called scalars defined in [Wikipedia](https://en.wikipedia.org/wiki/Vector_space).
    * vector addition
    * scalar multiplication or multiplication by scalars.
    * Elemens of V are commonly called **vectors**
    * Neutral element is *zero vector*
    * Examples
      * R^N
        * R^(Nx1) : column vector = *x*
        * R^(1xN) : row vector = *x^T* , transpose of x
      * R^(NxN)

### 2.4.3 Vector Subspaces
* [Linear Subspace](https://en.wikipedia.org/wiki/Linear_subspace)
* (Page 39)
   * [Homogeneous systems](https://en.wikipedia.org/wiki/System_of_linear_equations#Homogeneous_systems)
     * Ax = 0
     * at least one solution, known as the zero
     * singular matrix --> an infinite number of solutions.
     * subspace of R^n
   * Inhomogeneous systems  
     * Ax = b & b is not zero
     * **Not** subspace of R^n
## 2.5 Linear Independence
* (Page 40)
  *  **Basis** - a set of vectors with which we can represent every vector  in the vector space by adding them together and scaling them. 
  * Linear Combination
    * ![Linear Combination](https://wikimedia.org/api/rest_v1/media/math/render/svg/0a701e9b8de6ac82da0fe68b425b44688d1d0b97)
  * Linearly Dependent
    * if at least one of the vectors in the set can be defined as a linear combination of the others
  * Linearly Independent
    * if no vector in the set can be written in this way, then the vectors are said to be linearly independent.
    * a set of linearly independent vectors consists of vectors that have no redundancy,
    * ![Definition](https://github.com/kicom95/Math-For-Machine-Learning/blob/master/MML/Images/Linear%20Independce.JPG)
* (Page 41)
  * A practical way of checking whether vectors are linearly independent is to use Gaussian elimination
    * All column vectors are linearly independent if and only if all columns are pivot columns.
    
## 2.6 Basis and Rank
### 2.6.1 Generating Set and Basis
* (Page 44)
  * **Generating sets** are sets of vectors that **span** vector (sub)spaces, i.e., every vector can be represented as a linear combination of the vectors in the generating set
  * **Basis** - A generating set A of V is called *minimal* if there exists no smaller set that spans V
* (Page 45)  
  * A basis is a minimal generating set and a maximal linearly independent set of vectors.
  * A vector space can have several bases; however all the bases have the same number of elements, called the **dimension** of the vector space
  * *Canonical (Standard)* Basis
* (Page 46)
  * The dimension of a vector space corresponds to the number of its basis vectors.)
### 2.6.2 Rank
 * (Page 47)
   * The number of linearly independent columns of a matrix equals the number of linearly independent rows
   * Dimension of the vector space generated (or spanned) by its columns.
   * **Kernel / null space**
     * [Youtube Video](https://www.youtube.com/watch?v=C8zOd07U3l8&feature=emb_title)
   * Full rank
## 2.7 Linear Mapping
* (Page 48)
  * Linear Transformation
  ![Linear Mapping](https://github.com/kicom95/Math-For-Machine-Learning/blob/master/MML/Images/Linear%20Mapping.PNG)
  * Injective means we won't have two or more "A"s pointing to the same "B".
    * every element in W can be “reached” from V using linear mapping
    * can be undone
  * Surjective means that every "B" has at least one matching "A" (maybe more than one).
  * Bijective if it is injective and surjective.
* (Page 49)
  * Isomorphism:  : V ! W linear and bijective
  * Endomorphism:  : V ! V linear 
  * Automorphism:  : V ! V linear and bijective
   * idV : V => V , x -> x as the identity mapping or identity identity mapping identity automorphism in V .

