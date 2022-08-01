---
layout: splash
---

![an image alt text]({{ site.baseurl }}/assets/images/teaser.png "Contact and Friction Simulation for Computer Graphics")

[**Sheldon Andrews**](https://profs.etsmtl.ca/sandrews/)<sup>1</sup>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[**Kenny Erleben**](https://iphys.wordpress.com/)<sup>2</sup>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[**Zachary Ferguson**](https://zferg.us/)<sup>3</sup><br/>
<sup>1</sup>École de technologie supérieure
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<sup>2</sup>University of Copenhagen 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<sup>3</sup>New York University

### Description

Efficient simulation of contact is of interest for numerous physics-based animation applications. For
instance, virtual reality training, video games, rapid digital prototyping, and robotics simulation are all
examples of applications that involve contact modeling and simulation. However, despite its extensive
use in modern computer graphics, contact simulation remains one of the most challenging problems in
physics-based animation.

This course covers fundamental topics on the nature of contact modeling and simulation for computer
graphics. Specifically, we provide mathematical details about formulating contact as a complementarity
problem in rigid body and soft body animations. We briefly cover several approaches for contact
generation using discrete collision detection. Then, we present a range of numerical techniques for
solving the associated LCPs and NCPs. The advantages and disadvantages of each technique are
further discussed in a practical manner, and best practices for implementation are discussed. Finally, we
conclude the course with several advanced topics such as methods for soft body contact problems, barrier
functions, and anisotropic friction modeling. Programming examples are provided in our appendix as
well as on the course website to accompany the course notes.

**Updated for SIGGRAPH '22:** This version of the course adds coverage of multivariate continuous
collision detection, an extended treatment of penalty-based methods to include barrier methods,
a new chapter on implicit time integration schemes and methods for solving soft body
contact problems has been added. Additionally, we now include a more in-depth coverage of
anisotropic friction simulation, as well as a tutorial that guides the reader through the steps of
creating a rigid body simulator with frictional contact


### Course Notes 
<i class="fa fa-file-pdf-o"></i> 
[Course notes](/assets/files/SIGGRAPH22_friction_contact_notes.pdf)

<!--
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
-->

### Links
<i class="fab fa-youtube"></i>
[Video ](https://youtu.be/5JZ-tYHsJKg)
<iframe width="480" height="270" src="https://www.youtube.com/embed/vGfwbIShvog" frameborder="0" allowfullscreen></iframe>
<br/>

<i class="fa fa-code-fork" aria-hidden="true"></i>
Code: [**Tutorial: Programming a rigid body simulator with frictional contact**](https://github.com/siggraphcontact/rigidBodyTutorial)

### BibTex 
```
@inproceedings{SiggraphContact22,
  author = {Andrews, Sheldon and Erleben, Kenny and Ferguson, Zachary},
  title = {Contact and Friction Simulation for Computer Graphics},
  year = {2022},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {},
  doi = {},
  booktitle = {ACM SIGGRAPH 2022 Courses},
  articleno = {2},
  numpages = {124},
  location = {Hybrid Event, Vancouver, Canada},
  series = {SIGGRAPH '22}
}
```