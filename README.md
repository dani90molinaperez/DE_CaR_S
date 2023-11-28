# DE-CaR+S

In this work, a differential evolution variant (DE-CaR+S)  was developed. DE-CaR+S has two  fundamental  strategies:  The  first  one   takes into account  a set of “good fitness-infeasible solutions” defined as surviving solutions, that contribute to the exploration of promising regions from infeasible  contours. Thus, it  reduces  the vulnerability  of  the   population  to  be  attracted  to  the  larger  discontinuous feasible parts with unpromising objective  function  values.  The second strategy is a composite  trial  vector  generation  aimed  at  improving the combinatorial exploration of the discrete variables. 

Paper: Molina-Pérez, D., Mezura-Montes, E., Portilla-Flores, E. A., Vega-Alvarado, E., & Calva-Yañez, B. (2023). A differential evolution algorithm for solving mixed-integer nonlinear programming problems. Swarm and Evolutionary Computation, 101427.



# Optimization Problem

min: $f(x_{1},x_{2}) = 2 \cdot (x_{1} - 1)^{2} + (x_{2} - 3)^{2}$

Subject to:

$g(x_{1},x_{2})=x_{1}^{2} + x_{2}^{2} - 4 \leq 0$

$x_1 \in [-3, 3]$

$x_2 \in \\{-3, -2, -1, 0, 1, 2, 3\\}$

## Correcting Population Bias Towards the Largest Feasible Parts using DE-CaR+S

![ezgif com-video-to-gif](https://github.com/dani90molinaperez/DE_CaR_S/assets/99913325/5241ac7b-63a9-4f4b-bef6-c4b735f7173c)



