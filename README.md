# spinal-fusion-beam-fea

A 2D beam-chain finite element model of a fused spine, built in Python. 
Planned extensions: a neural network surrogate and maybe an uncertainty and sensitivity analysis of the stiffness.








# phase uno
beam-chain FEA in progress, 
>>>> function that returns the stiffness matrix for one beam then test with a simple case,  then compare to deflection equals P times L cubed, divided by 3 times E times I.

Compare a flexible (before fusion) spine chain with a fused one,  fused levels are modeled as parallel bone and rod elements. then check how load splits between the two >>>
DONE

>function that rotates a beam element's local stiffness matrix into global coordinates then  global stiffness matrix from a list of beam elements then boundary cond.

2nd phase
