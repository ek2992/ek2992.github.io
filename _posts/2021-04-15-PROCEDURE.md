---
title: EP calculations
article_header:
  type: cover
  image:
    src: 
---

## Detector information



## Procedure
Here, all genotypes can transition due to one heat bath at the same temperature. I initialize the genotypes in a uniform distribution. Because the subsystems (base pairs) can transition due to fluctuations of a resivour T, the system will relax to an equilibrium steady state. If the subsystems were attached to resivours of different temeperatures, the temperature difference would result in a net current driving the system to a non equilibrium steady state. This is not the case here. 

When the system is in equilibrium, we will have zero entropy production and the probability distribution will stop changing. The probability distribuition of system in an NESS (Non equilibrium steady state) will also stop changing, but the entropy production will not. 

The entropy production rate is given by 

$\dot{\sigma}=\frac{k_{b}}{2}\sum_{\nu}(W^{\nu}_{J,J'}P_{_{J'}}-W^{\nu}_{J',J}P_{_J})\ln\left(\frac{W^{\nu}_{J,J'}P_{{_{J'}}}}{W^{\nu}_{J',J}P_{_J}}\right)$

We can easily determine the accumulated entropy production from the trajectories (for a single heat bath). Note that the intermediate probabilities cancel and the trajectory level EP can be written as 

$\sigma[X]=\frac{E_i-E_f}{T}+log\, p(i)-log\, p(f)$ 

<!--more-->
