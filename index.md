---
layout: splash
---

![an image alt text]({{ site.baseurl }}/assets/images/teaser.png "Contact and Friction Simulation for Computer Graphics")

[**Sheldon Andrews**](https://profs.etsmtl.ca/sandrews/) 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[**Kenny Erleben**](https://iphys.wordpress.com/) <br/>
École de technologie supérieure
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
University of Copenhagen 

### Description
Efficient simulation of contact is of interest for numerous physics-based animation applications. For instance, virtual reality training, video games, rapid digital prototyping, and robotics simulation are all examples of applications that involve contact modeling and simulation. However, despite its extensive use in modern computer graphics, contact simulation remains one of the most challenging problems in physics-based animation.

This course covers fundamental topics on the nature of contact modeling and simulation for computer graphics. Specifically, we provide mathematical details about formulating contact as a complementarity problem in rigid body and soft body animations. We briefly cover several approaches for contact generation using discrete collision detection. Then, we present a range of numerical techniques for solving the associated LCPs and NCPs. The advantages and disadvantages of each technique are further discussed in a practical manner, and best practices for implementation are discussed. Finally, we conclude the course with several advanced topics, such as anisotropic friction modeling and proximal operators. Programming examples are provided on the course website to accompany the course notes.

### Course Notes 
<i class="fa fa-file-pdf-o"></i> 
[Course notes](/assets/files/SIGGRAPH21_friction_contact_notes.pdf)

### Slides 
<i class="fa fa-file-powerpoint-o"></i>
[Section 1.1-1.4: Introduction to Contact Simulation](/assets/files/SIGGRAPH21_Sheldon_S1_Intro.pptx) (Sheldon)<br/>
<i class="fa fa-file-powerpoint-o"></i>
[Section 1.5-1.7: Coulomb Friction](/assets/files/SIGGRAPH21_Sheldon_S1_Coulomb.pptx) (Sheldon) <br/>
<i class="fa fa-file-powerpoint-o"></i>
[Section 1.10: Soft-bodies and Contact](/assets/files/SIGGRAPH21_Sheldon_S1_SoftBodies.pptx) (Sheldon) <br/>
<i class="fa fa-file-powerpoint-o"></i>
[Section 2: Contact Generation](/assets/files/SIGGRAPH21_Sheldon_S2_ContactGen.pptx) (Sheldon)<br/>
<i class="fa fa-file-powerpoint-o"></i>
[Section 3.1: Pivoting Methods](/assets/files/SIGGRAPH21_Sheldon_S3_Pivoting.pptx) (Sheldon)<br/>
<i class="fa fa-file-powerpoint-o"></i>
[Section 3.2a: Splitting Methods (LCP)](/assets/files/SIGGRAPH21_Kenny_S3_SplittingMethods_LCP.pptx) (Kenny)<br/>
<i class="fa fa-file-powerpoint-o"></i>
[Section 3.2b: Splitting Methods (BLCP)](/assets/files/SIGGRAPH21_Kenny_S3_SplittingMethods_BLCP.pptx) (Kenny)<br/>
<i class="fa fa-file-powerpoint-o"></i>
[Section 3.2: Non-smooth Newton Methods](/assets/files/SIGGRAPH21_Kenny_S3_NonsmoothNewton.pptx) (Kenny)<br/>
<i class="fa fa-file-powerpoint-o"></i>
[Section 4.1: Pivoting Methods](/assets/files/SIGGRAPH21_Kenny_S4_Prox.pptx) (Kenny)<br/>
<i class="fa fa-file-powerpoint-o"></i>
[Section 4.2: Anisotropic Friction](/assets/files/SIGGRAPH21_Kenny_S4_Anisotropic.pptx) (Kenny)<br/>

### Links
<i class="fab fa-youtube"></i>
Video (available after 29 October) 

<i class="fa fa-code-fork" aria-hidden="true"></i>
Code (coming soon!)

### BibTex 
```
@inproceedings{SiggraphContact21,
  author = {Andrews, Sheldon and Erleben, Kenny},
  title = {Contact and Friction Simulation for Computer Graphics},
  year = {2021},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/3450508.3464571},
  doi = {10.1145/3450508.3464571},
  booktitle = {ACM SIGGRAPH 2021 Courses},
  articleno = {2},
  numpages = {124},
  location = {Virtual Event, USA},
  series = {SIGGRAPH '21}
}
```