## 3. Analytic Geometry
* (Page 70)
  * Inner products and their corresponding norms and metrics capture the intuitive notions of *similarity* and *distances*
  * Concept of Analytic Geometry (Page 70)
 ![Concept of Analytic Geometry](https://github.com/kicom95/Math-For-Machine-Learning/blob/master/MML/Images/Concept%20of%20Analytic%20Geometry.PNG) 

### 3.1 Norms
* (Page 71)
  * a norm is a function from a real or complex vector space to the nonnegative real numbers that behaves in certain ways like the distance from the origin.
    * *assigns each vector x its length*
  * ![Norm Property](https://github.com/kicom95/Math-For-Machine-Learning/blob/master/MML/Images/norm_property.PNG)
  * Manhattan Norm (L1 Norm)
    * ![Manhatan Norm](https://wikimedia.org/api/rest_v1/media/math/render/svg/6909908a18e848414a32a6310c5c7fed3f18e7b6)
  * Euclidean Norm (L2 Norm)
    * ![Euclidean Norm](https://wikimedia.org/api/rest_v1/media/math/render/svg/4d2562bd8e6df0c2625fd9c0e0c09ee9b932785d)
    
### 3.2 Inner Product
#### 3.2.1 Dot Product
 * (Page 72)
   * Dot/Scalar prodct is a kind of inner prodcut but inner products are more general concept
     * ![Inner Product](https://wikimedia.org/api/rest_v1/media/math/render/svg/5bd0b488ad92250b4e7c2f8ac92f700f8aefddd5)
#### 3.2.2 General Inner Product
 * (Page 73)
   * *Inner Product* - A positive definite, symmetric bilinear mapping that takes two vectors and maps them onto a real number
   * *Inner Product Space* (or vectors space with innner product )
     * dot prodcut is *Euclidean vector space*
#### 3.2.3 Symmetric, Positive Definite Matrices
 * Readings
   * [What is a Positive Definite Matrix? and why does it matter?](https://towardsdatascience.com/what-is-a-positive-definite-matrix-181e24085abd)
 * (Page 73)
   * An n x n **symmetric** real matrix M is said to be positive-definite
     * ![positive-definite](https://wikimedia.org/api/rest_v1/media/math/render/svg/4c7c64b7e5da9e0b4ae20e1890804507dc58f573)
   * Inner Product
     * ![inner product](https://github.com/kicom95/Math-For-Machine-Learning/blob/master/MML/Images/inner_product_positive-definite.PNG)  
     * The null space of A consists only of 0
     * The diagnoal elements of A are positive
