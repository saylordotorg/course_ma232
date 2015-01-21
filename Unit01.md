**Unit 1: Advanced Discussion on Groups** <span id="1"></span> 
*We will begin this unit with a series of counting methods involving
groups.  We will start with **Lagrange’s Theorem**.  Joseph Lagrange
discovered the interesting fact that the order, or number of elements,
of any true subgroup of a finite group will divide the order of the main
group.  This is important to know: if a group’s order is prime, then the
group is a cyclic, simple group, containing no nontrivial subgroups.*  
 *             
 Remembering that a symmetric group is the collection of all
permutations of a set X, we can think of a **group action** as a group
homomorphism from some group G to the symmetric group of X if the
mapping from G’s identity element to the permutation group of X is the
identity transformation and the mapping from gh in G is the composition
of permutations assigned to g and h.  That is, if we think of X as a set
of points on some regular geometric figure, then the group action is a
way of describing rotations and reflections of the figure.  Group
actions are powerful; they allow geometric ideas to be applied to
abstract structures.*  
              
 *The **Class Equation** tells us how many elements are in the center of
a finite group G (the center being the set of all elements in G that are
commutative under the operation on G) and in the distinct cosets
consisting of elements of G not in the center.  Remember that by
Lagrange’s Theorem, the order of the center must divide the order of G,
and if the order of G is prime, then the center is trivial.  If the
center contains only the identity element, or the center contains all of
G, then G is commutative.  On the other hand, if G contains
non-commutative elements and has a nontrivial center, its order
**cannot** be prime.*  
 *             
 Suppose G is a group that acts on a set X.  That is, for every g in G
and x in X, gx = y in X.  The set of all permutations of x caused by
left products with g is called the **group orbit** of x.  (Think of x as
some coordinate of an object in space and the transformation group G as
the group that moves or transforms x around a path.)  **Burnside’s
counting theorem**, also called the Cauchy-Frobenius lemma, tells us
exactly how many orbits exist for G and X.  Burnside did not discover
this theorem, but credited Ferdinand Frobenius.*  
 *             
 The **Sylow theorems** involve another counting principle.  Peter Sylow
said that every finite group has only so many subgroups of a fixed
order.  His theorem tells us how many subgroups of a given order exist. 
Further, he said that any subgroup that has a power of a prime order
must be the maximal subgroup of that order—that is, such a subgroup
cannot be contained in another subgroup of the same order.*  
 *             
 Abelian groups are commutative groups.  They were first studied by
Norwegian mathematician Niels Henrik Abel.  Abel discovered that if a
group of an equation was commutative, then its roots were solvable by
radicals.  After studying abelian groups, we will look at solvable
groups, which are constructed from abelian groups using extensions. 
From the use of extensions, a group G is called **solvable** if its
**derived series** eventually reaches the trivial subgroup of identity. 
The derived series is a series of commutator subgroups for which
commutators are elements of a group G that have the form
g<sup>-1</sup>h<sup>-1</sup>gh for g, h in G.  It makes sense that the
only way g<sup>-1</sup>h<sup>-1</sup>gh could reduce to the identity
element of G, e, is if g and h are commutative and are hence in the
center of G.  The commutator subgroups are not typically commutative,
and the larger that the largest commutator subgroup of G is, the “less
abelian” G is.*  
 *             
 Nilpotent groups are “almost” abelian through repeated use of
commutators.  What we discover is that if a group G is a direct product
of its Sylow subgroups, it is also nilpotent.  If G is nilpotent, then
every maximal proper subgroup of G is normal.  Nilpotency is an
important concept because constructs that are not abelian or solvable
may have solvable subconstructs, and there are applications for
nilpotent groups in Galois theory.*

**Unit 1 Time Advisory**  
This unit will take approximately 37 hours to complete.   
  
 ☐    Subunit 1.1: 4 hours  
  
 ☐    Subunit 1.2: 5 hours  
  
 ☐    Subunit 1.3: 5 hours  
  
 ☐    Subunit 1.4: 4 hours  
  
 ☐    Subunit 1.5: 6 hours  
<span id="cke_bm_576S" style="display: none; "> </span><span
id="cke_bm_577S" style="display: none; "> </span>  
 ☐    Reading materials: 4.5 hours  
  
 ☐    Video: 1 hour  
  
 ☐    Assignment: 0.5 hours

☐    Subunit 1.6: 5 hours  
  
 ☐    Subunit 1.7: 4 hours  
  
 ☐    Subunit 1.8: 4 hours

**Unit1 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
    
-   Use Lagrange’s theory to determine whether a group is cyclic or not.
-   Use the Class Equation to determine the size of the center of a
    nontrivial group.
-   Use Burnside’s counting theorem to determine the number of orbits of
    G on some set X.
-   Use the Sylow Theorems to determine how many subgroups of a finite
    order are contained in a given finite group.
-   Use a finite group G’s derived series to determine if G is solvable.

**1.1 Lagrange’s Theorem** <span id="1.1"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Cosets and Lagrange’s
    Theorem”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    ["Abstract Algebra Theory and
    Applications"](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf):
    “Cosets and Lagrange’s Theorem” (PDF)  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Please read Chapter 6: Cosets and Lagrange’s Theorem,
    pages 92 – 97.  
        
     Note: This PDF file will be used for the entire course.  It will be
    referenced for readings and assignments throughout.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be found
    [here](http://abstract.ups.edu/download.html) (HTML).

-   **Lecture: VideoLecture.net: Marconi Barbosa’s “Group Theory in
    Machine Learning”**
    Link: VideoLecture.net: Marconi Barbosa’s [Group Theory in Machine
    Learning](http://videolectures.net/ssll09_barbosa_gtiml/) (YouTube)  
        
     Instructions: Please click on the link above.  The video contains
    information on applications of group theory to the study of machine
    learning and this clip shows how Lagrange's Theorem may be
    applied.   
        
     Terms of Use: The video is freely available under the Creative
    Commons Attribution-Noncommercial-No Derivative Works 3.0 license. 
    Please respect the copyright and terms of use displayed on the
    webpage above.

**1.2 Group Actions** <span id="1.2"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Group Actions”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”:
    “Group Actions” (PDF)  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Please read Chapter 14: Group Actions, pages 209 –
    223.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML).

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Group Actions”:
    “Exercise Problems 1, 2, and 3”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”:
    “Group Actions”: “Exercise Problems 1, 2, and 3” (PDF)  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Do problems 1, 2, and 3 on page 224.  The solutions
    can be found on page 403.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

**1.3 The Class Equation** <span id="1.3"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Group Actions”: “The
    Class Equation”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”:
    “Group Actions”: “The Class Equation” (PDF)  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Please read Chapter 14.2: The Class Equation, pages
    213 – 215.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

-   **Reading: Wikipedia's “Order (group theory)”**
    Link: Wikipedia’s “[Order (group
    theory)](http://www.saylor.org/site/wp-content/uploads/2011/05/Order-group-theory.pdf)”
    (PDF)  
        
     Instructions: Please click on the link above to read the material. 
    The Class Equation is on the page along with other discussions of
    counting methods.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Order_(group_theory)) (HTML).

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Group Actions”:
    “Exercise Problems 6, 8, and 11”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”:
    “Group Actions”: “Exercise Problems 6, 8, and 11” (PDF)  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Do problems 6, 8, and 11 on page 224.  The solutions
    can be found on page 403.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

**1.4 Burnside’s Counting Theorem** <span id="1.4"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “Group Actions”:
    “Burnside's Counting Theorem”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”:
    “Group Actions”: “Burnside's Counting Theorem” (PDF)  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Please read Chapter 14.3: Burnside's Counting
    Theorem, pages 215 – 222.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

-   **Reading: Wikipedia's “Burnside's Lemma”**
    Link: Wikipedia’s “[Burnside's
    Lemma](http://www.saylor.org/site/wp-content/uploads/2011/05/Burnsides-Lemma.pdf)”
    (PDF)  
        
     Instructions: Please click on the link above to read the
    material.   
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Burnside's_counting_theorem) (HTML).

**1.5 The Sylow Theorems** <span id="1.5"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “The Sylow Theorems”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”:
    “The Sylow Theorems” (PDF)  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Please read Chapter 15: The Sylow Theorems, pages 227
    – 235.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

-   **Lecture: Harvard University Extension: Dr. Benedict Gross’ “Math
    E-222 Abstract Algebra”: “Alternating group structure”**
    Link: Harvard University Extension: Dr. Benedict Gross’ “Math E-222
    Abstract Algebra”: “[Alternating group
    structure](http://www.extension.harvard.edu/openlearning/math222/)”
    (Flash, QuickTime or Audio mp3)  
        
     Instructions: Please click on the link, then scroll down to Week 8,
    Lecture 1.  Choose the format most appropriate for your internet
    connection.  Watch the entire video.  This video clip discusses
    alternating group structures, but begins with a discussion on the
    Sylow theorems.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “The Sylow Theorems”:
    “Exercise Problems 1, 2, and 17”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”:
    “The Sylow Theorems”: “Exercise Problems 1, 2, and 17” (PDF)  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Do problems 1, 2, and 17 on page 235 – 236.  The
    solutions can be found on page 404.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

**1.6 Abelian Groups** <span id="1.6"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “The Structure of
    Groups”: “Finite Abelian Groups”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”:
    “The Structure of Groups”: “Finite Abelian Groups” (PDF)  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Please read 13.1: Finite Abelian Groups, pages 196 –
    201.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

-   **Reading: Wikipedia's “Abelian Group”**
    Link: Wikipedia’s “[Abelian
    Group](http://www.saylor.org/site/wp-content/uploads/2011/05/Abelian-group.pdf)”
    (PDF)  
        
     Instructions: Please click on the link above and read the material.
       
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Abelian_group) (HTML).

-   **Lecture: Harvard University Extension: Dr. Benedict Gross’ “Math
    E-222 Abstract Algebra”: “Review, Kernels, Normality”**
    Link: Harvard University Extension: Dr. Benedict Gross’ “Math E-222
    Abstract Algebra”: “[Review, Kernels,
    Normality](http://www.extension.harvard.edu/openlearning/math222/)”
    (Flash, QuickTime, or Audio mp3)  
        
     Instructions: Please click on the link, then scroll down to Week 2,
    Lecture 1.  Choose the format most appropriate for your internet
    connection.  Watch entire video.  
        
     Note on the Media: The video clip discusses kernels, normalities
    and centers.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “The Structure of
    Groups”: “Exercise Problems 1, 4, and 7”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”:
    “The Structure of Groups”: “Exercise Problems 1, 4, and 7” (PDF)  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Do problems 1, 4, and 7 on page 205 – 206.  The
    solutions can be found on page 403.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

**1.7 Solvable Groups** <span id="1.7"></span> 
-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “The Structure of
    Groups”: “Exercise Problems 12, 16, and 21”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”:
    “The Structure of Groups”: “Exercise Problems 12, 16, and 21”
    (PDF)  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Do problems 12, 16, and 21 on pages 206 – 207.  The
    solutions can be found on page 403.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    “Abstract Algebra Theory and Applications”: “The Structure of
    Groups”: “Solvable Groups”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    “[Abstract Algebra Theory and
    Applications](http://www.saylor.org/site/wp-content/uploads/2011/09/MA232-AbstractAlgebraText.pdf)”:
    “The Structure of Groups”: “Solvable Groups” (PDF)  
      
     Also available in:  

    [iBooks](http://www.saylor.org/site/wp-content/uploads/2011/09/Abstract-Algebra_-Theory-and-Applicatio-Thomas-W.-Judson.epub)  
        
     Instructions: Please read 13.2: Solvable Groups, pages 201 – 205.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 – 417.  The material linked above is
    licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download.html) (HTML)

-   **Reading: Wikipedia's “Solvable Group”**
    Link: Wikipedia “[Solvable
    Group](http://www.saylor.org/site/wp-content/uploads/2011/05/Solvable-group.pdf)”
    (PDF)  
        
     Instructions: Please click on the link above and read the
    material.   
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Solvable_group) (HTML).

**1.8 Nilpotent Groups** <span id="1.8"></span> 
-   **Reading: Wolfram MathWorld’s “Nilpotent Group”**
    Link: Wolfram MathWorld's: “[Nilpotent
    Group](http://mathworld.wolfram.com/NilpotentGroup.html)” (HTML)  
        
     Instructions: Please click on the link to read the information on
    the page.  This webpage contains a concise rendering of information
    on nilpotent groups.  It also contains links to related
    information.  
        
     Terms of Use: Please respect Wolfram MathWorld's [terms of
    use](http://mathworld.wolfram.com/about/terms.html).  MathWorld
    webpages are free for academic use and may be hyperlinked, according
    to their [FAQ
    site](http://mathworld.wolfram.com/about/faq.html#linking).

-   **Reading: Wikipedia's “Nilpotent Group”**
    Link: Wikipeda’s “[Nilpotent
    Group](http://www.saylor.org/site/wp-content/uploads/2011/05/Nilpotent-group.pdf)”
    (PDF)  
        
     Instructions: Please click on the link above to read the material. 
    This webpage contains useful information about nilpotent groups.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Nilpotent_group) (HTML).


