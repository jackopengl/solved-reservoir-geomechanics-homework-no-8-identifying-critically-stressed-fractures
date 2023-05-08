Download Link: https://assignmentchef.com/product/solved-reservoir-geomechanics-homework-no-8-identifying-critically-stressed-fractures
<br>
In this homework assignment, you will determine which fractures are critically stressed in a site of the Barnett shale using values of parameters and data in the first, fifth, and seventh homework assignments.




While this a 3D problem, in this assignment, we will assume the maximum horizontal stress at a depth of 5725 feet in the seventh homework assignment is the lower bound of the maximum horizontal stress at the depth of 5725 feet. Under this assumption, S<sub>hmin</sub> = S<sub>Hmax</sub> = S<sub>3</sub>, S<sub>V</sub> = S<sub>1</sub>, we are in a radial extension stress state, the Mohr circle simplifies into 2D, and an angle between a fracture normal and S<sub>1</sub> is equal to a fracture dip. The fracture dip data can be downloaded from the Plots of Homework 5.




Utilize a scientific computing program such as Matlab, Excel, R, or Python to follow the steps below.




<ol>

 <li><strong> Shear on Fractures </strong></li>

</ol>




Calculate a shear stress and an effective normal stress acting on a fracture using equations modified from (Zoback, 2007),




τ= 0.5(<em>S</em><sub>1 </sub>−<em>S</em><sub>3</sub>)sin2<sup>β</sup>

σ<em><sub>n </sub></em>= 0.5(<em>S</em><sub>1 </sub>+<em>S</em><sub>3</sub>)+0.5(<em>S</em><sub>1 </sub>−<em>S</em><sub>3</sub>)cos2β−<em>P</em><em><sub>p</sub></em>




in which t is a shear stress, S<sub>1</sub> is a maximum principal stress, S<sub>3</sub> is a minimum principal stress, b is an angle between the normal vector of a fracture and direction of the maximum principal stress, s<sub>n</sub> is an effective normal stress, and P<sub>p</sub> is a pore pressure. If t &gt; µs<sub>n</sub> on a fracture, and µ is a coefficient of sliding friction, the fracture is considered to be critically stressed.




For each fracture in a Barnett_fractures.xls file in the fifth homework assignment, determine the shear stress and the effective normal stress on each plane, assuming a gradient of an overburden stress at a depth of 5725 feet calculated in the first homework assignment, a gradient of a pore pressure at a depth of 5725 feet given in the seventh homework assignment, a coefficient of sliding friction at a depth of 5725 feet given in the seventh homework assignment, a gradient of a minimum horizontal stress at a depth of 5725 feet given in the seventh homework assignment, a gradient of a maximum horizontal stress as a lower bound of the maximum horizontal stress at a depth of 5725 feet constrained in the seventh homework assignment, and assuming that the stress gradients, the pore pressure gradient, and the coefficient of sliding friction do not vary in the depth range of the Barnett_fractures.xls file.




For the same coefficient of sliding friction given in the seventh homework assignment, change the gradient of the pore pressure as 0.52 psi/ft (Montgomery et al., 2005). For the same gradient of the pore pressure given in the seventh homework assignment, change the coefficient of sliding friction as 0.45 (Kohli and Zoback, 2013).




<ol>

 <li><strong> Answer the questions on the page below </strong></li>

</ol>




Use the calculations in Part 1 to answer the questions on the page below. The answers will be posted after the due time. Numerical entry type responses have a range of acceptable values.







Zoback, M. (2007). Reservoir Geomechaincs. Cambridge: Cambridge University Press.

doi:10.1017/CBO9780511586477




Montgomery, S. L., Jarvie, D. M., Bowker, K. A. and Pollastro, R. M. (2005). Mississippian Barnett Shale, Fort Worth basin, north-central Texas: Gas-shale play with multi–trillion cubic foot potential. AAPG Bulletin (2005) 89 (2): 155– 175. https://doi.org/10.1306/09170404042




Kohli, A. H. and Zoback, M. D. (2013). Frictional properties of shale reservoir rocks. JOURNAL OF GEOPHYSICAL

RESEARCH: SOLID EARTH, VOL. 118, 5109–5125, doi:10.1002/jgrb.50346, 2013


