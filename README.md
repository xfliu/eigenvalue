## Summary
    
For the eigenvalue problem of the Laplacian, the conforming and non-conforming finite element methods are utilized to provide explicit lower and upper bounds for the eigenvalues.

Particularly, by applying Liu's method, the lower eigenvalue bounds can be easily obtained through the Crouzeix-Rarviart finite element method; such a method even works for non-convex domains.

The lower and upper eigenvalue bounds for both the unit square domain and an L-shaped domain are given in the notebook file.


<img src=https://github.com/xfliu/eigenvalue/blob/master/eigfunction_1.png> <img src=https://github.com/xfliu/eigenvalue/blob/master/eigfunction_2.png>

<img src=https://github.com/xfliu/eigenvalue/blob/master/eigfunction_3.png> <img src=https://github.com/xfliu/eigenvalue/blob/master/eigfunction_4.png>

## Reference
-  [A framework of verified eigenvalue bounds for self-adjoint differential operators, Xuefeng LIU, AMC-2015](https://www.sciencedirect.com/science/article/pii/S0096300315003628)

## Online liver demo provided by binder.

Click the button to start the live demo! [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/xfliu/eigenvalue/master?filepath=Eigenvalue_bounds_of_Laplacian.ipynb)


