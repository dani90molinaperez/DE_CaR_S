# DE-CaR+S

In this work, we introduce a novel differential evolution algorithm variant, DE-CaR+S [1]. DE-CaR+S leverages the Cutting and Repulsion strategies initially proposed in [2] and integrates two essential strategies: Firstly, it  considers  a set of “good fitness-infeasible solutions” defined as surviving solutions that contribute to exploring promising regions from infeasible  contours. Thus, it  reduces  the population's vulnerability  to  be  attracted  to  the  larger  discontinuous feasible parts with unpromising objective  function  values.  Secondly, a composite  trial  vector  generation  to improve the combinatorial exploration of the discrete variables. 

[1] Molina-Pérez, D., Mezura-Montes, E., Portilla-Flores, E. A., Vega-Alvarado, E., & Calva-Yañez, B. (2023). A differential evolution algorithm for solving mixed-integer nonlinear programming problems. Swarm and Evolutionary Computation, 101427.

[2] Liu, J., Wang, Y., Huang, P. Q., & Jiang, S. (2021). Car: A cutting and repulsion-based evolutionary framework for mixed-integer programming problems. IEEE Transactions on Cybernetics, 52(12), 13129-13141.

# Optimization Problem

min: $f(x_{1},x_{2}) = 2 \cdot (x_{1} - 1)^{2} + (x_{2} - 3)^{2}$

Subject to:

$g(x_{1},x_{2})=x_{1}^{2} + x_{2}^{2} - 4 \leq 0$

$x_1 \in [-3, 3]$

$x_2 \in \\{-3, -2, -1, 0, 1, 2, 3\\}$

## Correcting Population Bias Towards the Largest Feasible Parts using DE-CaR+S

![ezgif com-video-to-gif](https://github.com/dani90molinaperez/DE_CaR_S/assets/99913325/5241ac7b-63a9-4f4b-bef6-c4b735f7173c)



