#C20-6

In an effort to explore the limits of the [[the laws of thermodynamics]] the Carnot cycle is an example of [[crossing two composite physical quantities]]. It does so by considering the [[reversibility]] of a [[combustion engine]]. It exhibits zero [[entropy]].

Introducing the following [[heat flow through a finite temperature gradient is not reversible|principle]]:

> [[energy transformation and heat flow|heat flow through]] a finite [[temperature gradient]] is not [[reversibility|reversible]]. 

A cycle with no [[temperature gradient]] is described, providing a [[speed limit]] on such a [[machine]] of a given design.

So the [[hot resevoir]], the [[working substance]] are at $T_H$ and waste heat and the [[cold resevoir]] must both be at $T_C$, [[isothermal]] transfer processes. Any process involving [[working substance]] with $T$ must be [[adiabatic]].

#### Steps
For an [[ideal gas]] two [[reversibility]] [[isothermal]] processes, and two [[reversibility]] [[adiabatic]] process comprise the [[thermodynamic process, path#Cyclicality|cycle]].

1. The gas expands isothermally at $T_H$ absorbing $Q_H$.
2. It expands adiabatically and drops to $T_C$
3. It is [[tensile-compressive stress|compressed]] isothermally at $T_C$ rejecting $dQ_C = |Q_C|$
4. It is compressed adiabatically back to $T_H$.

Considering the process at step 1, we have $\Delta U = 0 = Q_H - W_\text{ab}$
$$Q_H = W_\text{ab}=nRT_H\ln{V_b \over V_a}$$

and from step 3, $$Q_C = W_\text{cd}=nRT_C\ln{V_d \over V_c}$$
following from [[derivation]] using the [[equation of thermodynamic state#for an adiabatic thermodynamic process path|adiabatic state equtions,]] for states $b\rightarrow c, d \rightarrow a$ we have the [[formula]] $$e_\text{Carnot} = 1-{T_C \over T_H} = {T_H - T_C \over T_H}$$
which goes to $1$ as $T_C \rightarrow 0$.