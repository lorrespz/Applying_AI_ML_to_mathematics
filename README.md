This repo contains a collection of Jupyter notebooks that sometimes apply AI/ML techniques to construct various objects from mathematics. 

## 1. Constructing classical Lie algebra generators

A Jupyter notebook to create generators for the classical Lie algebras SO(n), SU(n) and SL(n)

In this notebook, our goal is to construct the generators of the classical Lie algebras $SO(n)$, $SU(n)$ and $SL(n)$. 

$SO(n)$ is the orthogonal group generating rotations in $n$-dimensional space:
https://en.wikipedia.org/wiki/Orthogonal_group

$SU(n)$ is the special unitary group:

https://en.wikipedia.org/wiki/Special_unitary_group

https://en.wikipedia.org/wiki/Structure_constants

$SL(n)$ is the special linear group:
https://en.wikipedia.org/wiki/Special_linear_group

$SU(n)$ and $SO(n)$, also to smaller extent $SL(n)$, have numerous applications in physics. 

 1. $SO(3)$, being the generators of rotations in 3D space is perhaps the most familiar and most readily understood example. $SO(3)$ is a subgroup of $SO(3,1)$, which plays an central part in the theory of special relativity, since it is the symmetry of flat Minkowski spacetime. Relativistic transformations (time dilation and space contraction when moving near the speed of light) - more commonly known as Lorentz transformations (https://en.wikipedia.org/wiki/Lorentz_transformation) - are generated by $SO(3,1)$. Furthermore, all known particles in the universe such as scalars, fermionic particles and gauge bosons must form representations of $SO(3,1)$. 
    
    
 2. In high-energy physics, $SU(2)$ and $SU(3)$, respectively, are the gauge groups of the weak interaction (more commonly known in its unified version with $U(1)$ as electroweak theory https://en.wikipedia.org/wiki/Electroweak_interaction) and quantum chromodynamics (https://en.wikipedia.org/wiki/Quantum_chromodynamics). The standard model of particle physics (https://en.wikipedia.org/wiki/Standard_Model) is based on the product gauge group $U(1)\times SU(2)\times SU(3)$, which describes the 3 known forces: electromagnetism, strong and weak nuclear forces. 

 In the Jupyter notebook, generators for $SU(n)$ groups are constructed recursively starting with the $n=2$ case, in which the $SU(2)$ generators are the Pauli matrices. $SO(n)$ generators are defined very straightforwardly as real, antisymmetric matrices. $SL(n)$ generators are obtained from those of $SU(n)$ groups by a simple conversion. The procedure to check for the closure of the algebras and the extraction of the associated structure constants are implemented. 
