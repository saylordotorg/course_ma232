**Unit 2: Advanced Discussion of Rings** <span id="2"></span> 
*We begin Unit 2 by returning to the idea of polynomial rings, which we
first encountered in Abstract Algebra I.  These are rings that have a
set of polynomials with coefficients in another ring.  We will revisit
the materials we have seen on these rings first.  Then, we will look at
the division algorithm.  For polynomial rings, this is analogous to the
algorithm for dividing integers.  Put simply, if there exist polynomials
g, q and f in **R[X]** such that f = gq, then if g|f, one of the
following must be true: either f = 0 or deg f* *³deg g.  Also, if fg =
0, then either f = 0 or g = 0 (or both).  What we will find is a
procedure for dividing f.*  
 *             
 **Irreducible polynomials** are similar to prime integers, for they
cannot be split into the product of two or more non-trivial
polynomials.  Irreducible polynomials play an important role in Galois
theory, because there exists a relationship between a field, the field’s
Galois group, and the field’s irreducible polynomials.  Since all fields
are commutative rings, we will be able to incorporate what we learn in
this unit in Unit 4.*  
 *             
 **Integral domains** advance our conversation further, because these
bring us closer to the study of fields.  Integral domains are
commutative rings with the property that the multiplicative and additive
identities cannot be equal; they also have no zero divisors.  That is,
if ab is in the ring and ab = 0, then either a = 0 or b = 0.  Both
cannot be nonzero.  Thus, integral domains are either prime or
factorable.  If these factors are unique, then the integral domain is a
**unique factorization domain**.*  
 **             
 *Lattices ****are algebraic structures with group-like properties. 
With the operations **join*** ***Ú ****(which produces the least upper
bound of two elements in the lattice) and **meet*** ***Ù ****(which
produces the greatest lower bound between two elements on the lattice),
lattices are close to being commutative rings.  **Boolean algebras**,
then, are complemented distributed lattices**. ** That is, for every a
in lattice B, there is an element b for which a* *Úb = 1 and a* *Ùb = 0
and the properties* *Úand* *Ùdistribute over each other.  The complement
b of a listed above need not be unique.  The importance of Boolean
algebras is that they form ring-like structures that use essential
properties of both set and logic operations.*

**Unit 2 Time Advisory**  
This unit will take approximately 36 hours to complete.   
  
 ☐    Subunit 2.1: 5 hours  
  
 ☐    Subunit 2.2: 5 hours  
  
 ☐    Subunit 2.3: 4 hours  
  
 ☐    Subunit 2.4: 5 hours  
  
 ☐    Subunit 2.5: 6 hours  
  
☐    Reading materials: 4.5 hours  
  
 ☐    Video: 1 hour  
  
 ☐    Assignments: 0.5 hours

☐    Subunit 2.6: 6 hours  
  
 ☐    Reading materials: 4.5 hours  
  
 ☐    Video: 1 hour  
  
 ☐    Assignments: 0.5 hours

☐    Subunit 2.7: 5 hours

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
    
-   Use the division algorithm to factor a polynomial.
-   Find a given polynomial’s irreducible polynomials.
-   Distinguish between polynomial rings, integral domains, and unique
    factorization rings.
-   Use lattices to determine solutions to various problems requiring
    partial ordering.

**2.1 Polynomial Rings** <span id="2.1"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Polynomials”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”:
    “Polynomials” (PDF)  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Please read 17.1: Polynomial Rings, pages 264 –
    267.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Polynomials”: “Exercise
    Problem 2”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”
    (PDF): “Polynomials”: “Exercise Problem 2”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Do problem 2 on page 278.  The solution can be found
    on page 405.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

**2.2 The Division Algorithm** <span id="2.2"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Polynomials”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”
    (PDF): “Polynomials”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Please read 17.2: The Division Algorithm, pages 268 –
    271.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Polynomials”: “Exercise
    Problems 3 and 5”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”
    (PDF): “Polynomials”: “Exercise Problems 3 and 5”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Do problems 3 and 5 on page 278 – 279.  The solutions
    can be found on page 405.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

**2.3 Irreducible Polynomials** <span id="2.3"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Polynomials”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”
    (PDF): “Polynomials”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Please read 17.3: Irreducible Polynomials, pages 272
    – 277.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”
    (PDF)  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Do problems 3 and 5 on page 278 – 279.  The solutions
    can be found on page 405.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

**2.4 Integral Domains** <span id="2.4"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Integral Domains”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”
    (PDF): “Integral Domains”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Please read 18.1: Field of Fractions, pages 283 –
    287.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Integral Domains”:
    “Exercise Problem 1”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”
    (PDF): “Integral Domains”: “Exercise Problem 1”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Do problem 1 on page 297.  The solution can be found
    on page 406.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

**2.5 Factorization of Integral Domains** <span id="2.5"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Integral Domains”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”
    (PDF): “Integral Domains”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Please read 18.2: Factorization of Integral Domains,
    pages 287 – 296.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Integral Domains”:
    “Exercise Problem 2”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”
    (PDF): “Integral Domains”: “Exercise Problem 2”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Do problem 2 on page 297.  The solution can be found
    on page 406.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

**2.6 Lattices** <span id="2.6"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Lattices and Boolean
    Algebras”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”
    (PDF): “Lattices and Boolean Algebras”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Please read 19.1: Lattices, pages 301 – 306.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

-   **Lecture: YouTube: “Lecture 40 – Lattices”**
    Link: YouTube: “[Lecture 40 -
    Lattices](http://www.youtube.com/watch?v=qPtGlrb_sXg)” (YouTube)  
        
     Instructions: Please click on the link and view the video in its
    entirety.  
        
     Note on the Media: The video discusses linear independence. 
    Professor Kamala Krithvisian, from the Department of Computer
    Science and Engineering of IIT Madris, in India, created this
    video.  She does an excellent job of discussing lattices in terms of
    posets and makes the material understandable.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.  

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Lattices and Boolean
    Algebras”: “Exercise Problem 2”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”
    (PDF): “Lattices and Boolean Algebras”: “Exercise Problem 2”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Do problem 2 on page 315.  The solution can be found
    on page 406.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

**2.7 Boolean Algebras** <span id="2.7"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Lattices and Boolean
    Algebras”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”
    (PDF): “Lattices and Boolean Algebras”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Please read 19.2: Boolean Algebras, pages 306 –
    312.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Lattices and Boolean
    Algebras”: “Exercise Problem 6”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”
    (PDF): “Lattices and Boolean Algebras”: “Exercise Problem 6”  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Do problem 6 on page 316.  The solution can be found
    on page 406.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)


