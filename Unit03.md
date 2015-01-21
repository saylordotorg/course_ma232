**Unit 3: Vector Spaces** <span id="3"></span> 
***Vector spaces ****are among the most useful structures in
mathematics.  Used heavily in economics and finance as well as
engineering and the natural and physical sciences, vector spaces are
additional structures that have both algebraic and geometric
properties.*  
 *             
 Vectors are extended commutative groups with additional distributive
properties concerning field values called scalars.  Thus, all theorems
that apply to groups may apply to vectors.*  
 *             
 A **subspace** is a subset of a vector space that contains the **zero
vector** and is a vector space itself.  **Linear independence** is a
property of spaces and subspaces that states that no family of vectors
in the space may be written as linear combinations of the other vectors
in the family.  The number of unique, linearly independent vectors in a
space is called the space’s dimension.*  
 *             
 The **basis** of a space is a set of vectors that can represent all the
vectors in the space by linear combinations.  That is, the basis is a
**linearly independent spanning set** of the space.  Sometimes, it is
easier to work in some bases than others.  For that reason, we sometimes
prefer to change a basis from one coordinate set to another.  The
**group isomorphism** that maps one basis to another is called a
**change of basis**.  This type of isomorphism is a category of a set of
functions called **linear transformations**.  In general, linear
transformations are functions that preserve the operations of vector
addition and scalar multiplication.  We will discover that all
compositions of transformations result in transformations.  The **kernel
of a linear transformation** L is the set of all vectors **v** in a
space V for which L(**v**) = **0**.  That is, all of the vectors that
are mapped to the zero vector by L are in L’s kernel.  The kernel of L
is by nature a subspace of the vector space V.  If the only vector in V
contained in the kernel of L (also called Ker(L)) is **0**, then L is
1-1.  The range of a transformation L is all vectors **w** in space W
for which there is a **v** in space V such that L(**v**) = **w**.  If L
is onto W, then the range of L = W.  If Ker(L) = {**0**} and range L =
W, then L is a **vector space isomorphism**.  If L is an isomorphism,
then matrices made from vectors in V are invertible.*  
 *             
 At the end of the unit, we will consider the Fundamental Theorem of
Invertible Matrices, which is the core theorem of linear algebra.  The
beauty of this theorem is that there are twenty equivalent statements
about matrices.  If we determine that any of the twenty are true about a
matrix, they are all true.  Conversely, if any is not true, none are
true.*

**Unit 3 Time Advisory**  
This unit will take approximately 45 hours to complete.   
  
 ☐    Subunit 3.1: 4 hours  
  
 ☐    Subunit 3.2: 4 hours  
  
 ☐    Subunit 3.3: 5 hours  
  
 ☐    Subunit 3.4: 5 hours  
  
 ☐    Subunit 3.5: 6 hours  
  
☐    Reading materials: 4.5 hours  
  
 ☐    Video: 1 hour  
  
 ☐    Assignment: 0.5 hours

☐    Subunit 3.6: 5 hours  
  
 ☐    Subunit 3.7: 6 hours  
  
☐    Reading materials: 4.5 hours  
  
 ☐    Video: 0.5 hours  
  
 ☐    Assignment: 1 hour

☐    Subunit 3.8: 5 hours  
  
 ☐    Subunit 3.9: 5 hours

**Unit3 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
    
-   Determine whether a vector space is independent or not.
-   Find the basis of a vector space.
-   Use linear transformations to change bases.
-   Define the kernel of a linear transformation.
-   Determine if a matrix is invertible.

**3.1 Definitions and Examples of Vector Spaces** <span
id="3.1"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Vector Spaces”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”
    (PDF): “Vector Spaces”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Please read 20.1: Definitions and Examples, pages 319
    – 321.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

-   **Lecture: Khan Academy’s “Linear Algebra: Vector Examples”**
    Link: Khan Academy’s “[Linear Algebra: Vector
    Examples](https://www.khanacademy.org/math/linear-algebra/vectors_and_spaces/vectors/v/linear-algebra--vector-examples)”
    (YouTube)  
        
     Instructions: Please watch the entire lecture, which provides
    specific examples of vectors on a coordinate plane.  
        
     Watching this lecture should take approximately 30 minutes.  
        
     Terms of Use: The article above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to Khan Academy.

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Vector Spaces”:
    “Exercise Problems 3 and 5”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”
    (PDF): “Vector Spaces”: “Exercise Problems 3 and 5”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Do problems 3 and 5 on page 325.  The solution can be
    found on page 407.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

**3.2 Subspaces** <span id="3.2"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Vector Spaces”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”
    (PDF): “Vector Spaces”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Please read 20.2: Subspaces, pages 321 – 322.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

-   **Lecture: Khan Academy’s “Linear Subspaces”**
    Link: Khan Academy’s “[Linear
    Subspaces](https://www.khanacademy.org/math/linear-algebra/vectors_and_spaces/subspace_basis/v/linear-subspaces?v=pMFv6liWK4M)”(YouTube)  
        
     Instructions: Please watch the entire lecture, which is about
    linear subspaces.  
      
     Watching this lecture should take approximately 30 minutes.  
        
     Terms of Use:  The article above is released under [Creative
    Commons Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to Khan Academy.

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Vector Spaces”:
    “Exercise Problem 7”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”
    (PDF): “Vector Spaces”: “Exercise Problem 7”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Do problem 7 on page 325.  The solution can be found
    on page 407.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

**3.3 Linear Independence** <span id="3.3"></span> 
-   **Reading: St. Michael's College: Jim Hefferon’s “Linear Algebra”:
    “Vector Spaces”: “Linear Independence”**
    Link: St. Michael's College: Jim Hefferon’s “[Linear
    Algebra](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-JimHeffersonText.pdf)”
    (PDF): “Vector Spaces”: “Linear Independence”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Linear-Algebra-Jim-Hefferon_-Saint-Michaels-College_-V.epub)  
        
     Instructions: Please read Chapter 2, II: Linear Independence, pages
    99 – 106.  
        
     Notes on the Textbook: This PDF file will be used for the rest of
    the unit.  It will be referenced for readings and assignments
    throughout.   
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages iv – vi.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Jim Hefferon and the original version can be
    found [here](http://joshua.smcvt.edu/linearalgebra/) (HTML).

-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Vector Spaces”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”
    (PDF): “Vector Spaces”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Please read 20.3: Linear Independence, pages 322 –
    325.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

-   **Lecture: Khan Academy’s “Introduction to Linear Independence”**
    Link: Khan Academy’s “[Introduction to Linear
    Independence](https://www.khanacademy.org/math/linear-algebra/vectors_and_spaces/linear_independence/v/linear-algebra--introduction-to-linear-independence?v=CrV1xCWdY-g)”
    (YouTube)  
        
     Instructions: Please watch the entire lecture, which is about
    linear independence.  
      
     Watching this lecture should take approximately 15 minutes.  
        
     Terms of Use: The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to Khan Academy.

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Vector Spaces”:
    “Exercise Problem 15”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”
    (PDF): “Vector Spaces”: “Exercise Problem 15”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Do problem 15 on pages 326 – 327.  The solution can
    be found on page 407.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

-   **Reading: St. Michael's College: Jim Hefferon’s “Linear Algebra”:
    “Vector Spaces”: “Linear Independence”: “Exercise Problems 1.18,
    1.19, and 1.24”**
    Link: St. Michael’s College: Jim Hefferon’s “[Linear
    Algebra](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-JimHeffersonText.pdf)”
    (PDF): “Vector Spaces”: “Linear Independence”: “Exercise Problems
    1.18, 1.19, and 1.24”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Linear-Algebra-Jim-Hefferon_-Saint-Michaels-College_-V.epub)  
        
     Instructions: Do problems 1.18, 1.19, and 1.24 on pages 106 – 107. 
    The answers can be found
    [here](http://www.saylor.org/site/wp-content/uploads/2011/11/jhanswer.pdf)
    on pages 49 – 50.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages iv – vi.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Jim Hefferon and the original version can be
    found [here](http://joshua.smcvt.edu/linearalgebra/) (HTML).

**3.4 Change of Basis** <span id="3.4"></span> 
-   **Reading: St. Michael's College: Jim Hefferon’s “Linear Algebra”:
    “Maps Between Spaces”: “Change of Basis”**
    Link: St. Michael's College: Jim Hefferon’s “[Linear
    Algebra](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-JimHeffersonText.pdf)”
    (PDF): “Maps Between Spaces”: “Change of Basis”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Linear-Algebra-Jim-Hefferon_-Saint-Michaels-College_-V.epub)  
        
     Instructions: Please read Chapter 3, V: Change of Basis, pages 236
    – 245.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages iv – vi.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Jim Hefferon and the original version can be
    found [here](http://joshua.smcvt.edu/linearalgebra/) (HTML).

-   **Lecture: Khan Academy’s “Linear Algebra: Change of Basis Matrix”**
    Link: Khan Academy’s “[Linear Algebra: Change of Basis
    Matrix](https://www.khanacademy.org/math/linear-algebra/alternate_bases/change_of_basis/v/linear-algebra--change-of-basis-matrix?v=1j5WnqwMdCk)”
    (YouTube)  
        
     Instructions: Please watch the entire lecture, which is about the
    change of basis matrix.  
      
     Watching this lecture should take approximately 20 minutes.  
        
     Terms of Use:  The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to Khan Academy.

-   **Assessment: St. Michael's College: Jim Hefferon’s “Linear
    Algebra”: “Vector Spaces”: “Exercise Problems 1.6, 1.7, 1.8, and
    1.9”**
    Link: St. Michael’s College: Jim Hefferon’s “[Linear
    Algebra](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-JimHeffersonText.pdf)”
    (PDF): “Vector Spaces”: “Exercise Problems 1.6, 1.7, 1.8, and 1.9”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Linear-Algebra-Jim-Hefferon_-Saint-Michaels-College_-V.epub)  
        
     Instructions: Please do problems 1.6, 1.7, 1.8, and 1.9 on page
    239.  The solutions to these exercises can be found
    [here](http://www.saylor.org/site/wp-content/uploads/2011/11/jhanswer.pdf)
    on pages 123 – 124.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages iv – vi.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Jim Hefferon and the original version can be
    found [here](http://joshua.smcvt.edu/linearalgebra/) (HTML).

**3.5 Linear Transformations** <span id="3.5"></span> 
-   **Reading: St. Michael's College: Jim Hefferon’s “Linear Algebra”:
    “Maps Between Spaces”: “Computing Linear Maps”**
    Link: St. Michael's College: Jim Hefferon’s “[Linear
    Algebra](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-JimHeffersonText.pdf)”
    (PDF): “Maps Between Spaces”: “Computing Linear Maps”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Linear-Algebra-Jim-Hefferon_-Saint-Michaels-College_-V.epub)  
        
     Instructions: Please read Chapter 3, III: Computing Linear Maps,
    pages 193 – 203.  This subchapter shows linear transformations as
    matrix operations and mappings.  It shows that the two are
    interchangeable.   
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages iv – vi.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Jim Hefferon and the original version can be
    found [here](http://joshua.smcvt.edu/linearalgebra/) (HTML).

-   **Lecture: Harvard University Extension: Dr. Benedict Gross’ “Math
    E-222 Abstract Algebra”: “Bases and Vectorspaces”**
    Link: Harvard University Extension: Dr. Benedict Gross’ “Math E-222
    Abstract Algebra”: “[Bases and
    Vectorspaces](http://www.extension.harvard.edu/openlearning/math222/)”
    (Flash, QuickTime, or Audio mp3)  
        
     Instructions: Please click on the link and then scroll down to Week
    4, Lecture 1.  Choose the format most appropriate for your internet
    connection.  Watch the entire video.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: St. Michael's College: Jim Hefferon’s “Linear
    Algebra”: “Vector Spaces”: “Exercise Problems 1.14, 1.15, and
    1.17”**
    Link: St. Michael’s College: Jim Hefferon’s “[Linear
    Algebra](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-JimHeffersonText.pdf)”
    (PDF): “Vector Spaces”: “Exercise Problems 1.14, 1.15, and 1.17”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Linear-Algebra-Jim-Hefferon_-Saint-Michaels-College_-V.epub)  
        
     Instructions: Do problems 1.14, 1.15, and 1.17 on page 201.  The
    solutions can be found
    [here](http://www.saylor.org/site/wp-content/uploads/2011/11/jhanswer.pdf)
    on pages 97 – 98.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages iv – vi.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Jim Hefferon and the original version can be
    found [here](http://joshua.smcvt.edu/linearalgebra/) (HTML).

**3.6 Composition of Transformations** <span id="3.6"></span> 
-   **Reading: St. Michael's College: Jim Hefferon’s “Linear Algebra”:
    “Maps Between Spaces”: “Matrix Multiplication”**
    Link: St. Michael's College: Jim Hefferon’s “[Linear
    Algebra](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-JimHeffersonText.pdf)”
    (PDF): “Maps Between Spaces”: “Matrix Multiplication”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Linear-Algebra-Jim-Hefferon_-Saint-Michaels-College_-V.epub)  
        
     Instructions: Please read Chapter 3, IV.2: Matrix Multiplication,
    pages 213 – 220.  This subchapter demonstrates composition of linear
    transformations as matrix multiplication.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages iv – vi.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Jim Hefferon and the original version can be
    found [here](http://joshua.smcvt.edu/linearalgebra/) (HTML).

-   **Lecture: Khan Academy’s “Compositions of Linear Transformation 1”
    and “Compositions of Linear Transformation 2”**
    Link: Khan Academy’s “[Compositions of Linear Transformations
    1](https://www.khanacademy.org/math/linear-algebra/matrix_transformations/composition_of_transformations/v/compositions-of-linear-transformations-1?v=f_DTiXZpb8M)”
    and “[Compositions of Linear Transformations
    2](https://www.khanacademy.org/math/linear-algebra/matrix_transformations/composition_of_transformations/v/compositions-of-linear-transformations-1?v=f_DTiXZpb8M)”
    (YouTube)  
        
     Instructions: Please watch both lectures, which cover compositions
    of linear transformations.  
      
     Watching these lectures should take approximately 30 minutes.  
        
     Terms of Use:  The videos above are released under [Creative
    Commons Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML). 
    They attributed to Khan Academy.

-   **Assessment: St. Michael's College: Jim Hefferon’s “Linear
    Algebra”: “Maps Between Spaces”: “Matrix Multiplication”: “Exercise
    Problems 2.24, 2.26, and 2.29”**
    Link: St. Michael’s College: Jim Hefferon’s “[Linear
    Algebra](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-JimHeffersonText.pdf)”
    (PDF): “Maps Between Spaces”: “Matrix Multiplication”: “Exercise
    Problems 2.24, 2.26, and 2.29”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Linear-Algebra-Jim-Hefferon_-Saint-Michaels-College_-V.epub)  
        
     Instructions: Do problems 2.24, 2.26, and 2.29 on page 218 – 219. 
    The solutions can be found
    [here](http://www.saylor.org/site/wp-content/uploads/2011/11/jhanswer.pdf)
    on pages 322 – 323.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages iv – vi.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Jim Hefferon and the original version can be
    found [here](http://joshua.smcvt.edu/linearalgebra/) (HTML).

**3.7 Kernel and Range of Transformations** <span id="3.7"></span> 
-   **Reading: St. Michael's College: Jim Hefferon’s “Linear Algebra”:
    “Maps Between Spaces”: “Rangespace and Nullspace”**
    Link: St. Michael's College: Jim Hefferon’s “[Linear
    Algebra](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-JimHeffersonText.pdf)”
    (PDF): “Maps Between Spaces”: “Rangespace and Nullspace”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Linear-Algebra-Jim-Hefferon_-Saint-Michaels-College_-V.epub)  
        
     Instructions: Please read Chapter 3, II.2: Rangespace and
    Nullspace, pages 181 – 192.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages iv – vi.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Jim Hefferon and the original version can be
    found [here](http://joshua.smcvt.edu/linearalgebra/) (HTML).

-   **Lecture: Khan Academy’s “Preimage and Kernel Example”**
    Link: Khan Academy’s “[Preimage and Kernel
    Example](https://www.khanacademy.org/math/linear-algebra/matrix_transformations/linear_transformations/v/preimage-and-kernel-example)”
    (YouTube)  
        
     Instructions: Please watch the lecture, which discusses kernel and
    preimages for vectors in the range of the transformation.  
      
     Watching this lecture should take approximately 15 minutes.  
        
     Terms of Use:  The article above is released under [Creative
    Commons Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to the Khan Academy.

-   **Lecture: Khan Academy’s “im(T): Image of a Transformation”**
    Link: Khan Academy’s “[im(T): Image of a
    Transformation](https://www.khanacademy.org/math/linear-algebra/matrix_transformations/linear_transformations/v/im-t----image-of-a-transformation)”(YouTube)  
        
     Instructions: Please watch the lecture, which discusses image (or
    range) of a transformation.  
      
     Watching this lecture should take approximately 15 minutes.  
        
     Terms of Use:  The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to Khan Academy.

-   **Assessment: St. Michael's College: Jim Hefferon’s “Linear
    Algebra”: “Homomorphisms”: “Rangespace and Nullspace”: “Exercise
    Problems 2.22, 2.23, 2.24, 2.27, and 2.29”**
    Link: St. Michael’s College: Jim Hefferon’s “[Linear
    Algebra](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-JimHeffersonText.pdf)”
    (PDF): “Homomorphisms”: “Rangespace and Nullspace”: “Exercise
    Problems 2.22, 2.23, 2.24, 2.27, and 2.29”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Linear-Algebra-Jim-Hefferon_-Saint-Michaels-College_-V.epub)  
        
     Instructions: Do problems 2.22, 2.23, 2.24, 2.27, and 2.29 on page
    190.  The solutions can be found
    [here](http://www.saylor.org/site/wp-content/uploads/2011/11/jhanswer.pdf)
    on pages 303-304.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages iv – vi.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Jim Hefferon and the original version can be
    found [here](http://joshua.smcvt.edu/linearalgebra/) (HTML).

**3.8 Vector Space Isomorphisms** <span id="3.8"></span> 
-   **Reading: St. Michael's College: Jim Hefferon’s “Linear Algebra”:
    “Maps Between Spaces”: “Isomorphisms”**
    Link: St. Michael's College: Jim Hefferon’s “[Linear
    Algebra](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-JimHeffersonText.pdf)”
    (PDF): “Maps Between Spaces”: “Isomorphisms”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Linear-Algebra-Jim-Hefferon_-Saint-Michaels-College_-V.epub)  
        
     Instructions: Please read Chapter 3, I : Isomorphisms, pages 157 –
    166.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages iv – vi.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Jim Hefferon and the original version can be
    found [here](http://joshua.smcvt.edu/linearalgebra/) (HTML).

-   **Assessment: St. Michael's College: Jim Hefferon’s “Linear
    Algebra”: “Maps Between Spaces”: “Isomorphisms”: “Exercise Problems
    1.10, 1.11, 1,13, and 1.14”**
    Link: St. Michael’s College: Jim Hefferon’s “[Linear
    Algebra](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-JimHeffersonText.pdf)”
    (PDF): “Maps Between Spaces”: “Isomorphisms”: “Exercise Problems
    1.10, 1.11, 1,13, and 1.14”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Linear-Algebra-Jim-Hefferon_-Saint-Michaels-College_-V.epub)  
        
     Instructions: Do problems 1.10, 1.11, 1.13, and 1.14 on page 164. 
    The answers can be found
    [here](http://www.saylor.org/site/wp-content/uploads/2011/11/jhanswer.pdf)
    on pages 287-290.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages iv – vi.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Jim Hefferon and the original version can be
    found [here](http://joshua.smcvt.edu/linearalgebra/) (HTML).

**3.9 The Fundamental Theorem of Invertible Matrices** <span
id="3.9"></span> 
-   **Reading: Wikipedia's “Invertible Matrix”**
    Link: Wikipedia’s “[Invertible
    Matrix](http://www.saylor.org/site/wp-content/uploads/2011/05/Invertible-Matrix.pdf)”
    (PDF)  
        
     Instructions: This article contains useful information about
    invertible matrices, including the twenty equivalent statements
    contained in the Fundamental Theorem of Invertible Matrices, listed
    as properties of invertible matrices.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Invertible_matrix) (HTML).

-   **Lecture: Khan Academy’s “Linear Algebra: Simplifying Conditions
    For Invertibility”**
    Link: Khan Academy’s [“Linear Algebra: Simplifying Conditions For
    Invertibility”](https://www.khanacademy.org/math/linear-algebra/matrix_transformations/inverse_transformations/v/linear-algebra--simplifying-conditions-for-invertibility) (YouTube)  
        
     Instructions: Please watch the entire video, which discusses
    conditions for invertibility.  
      
     Watching this video should take approximately 10 minutes.  
        
     Terms of Use: The video above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to Khan Academy.


