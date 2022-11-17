#C15-6
Here are the relevant [[formula]]

#### ... [[standing mechanical waves]]
In the case where [[forced oscillation]] is occuring, the same motion is [[principle of superposition of waves|superimposed]] 

#### ... [[principle of superposition of waves]]
For two different [[wave pulse]], their [[amplitude]] add.

#### ... [[interference of mechanical waves]]
The [[thermodynamic state]] where a [[wave pulse]] overlaps a portion of a [[wave medium]].

#### ... [[reflection of mechanical waves]]
The property of a [[wave medium]] that results in changing [[wave speed|wave velocity]] and possibly [[phase]], depending on whether the [[wave medium boundary]]

#### ...for a [[ideal string]], using [[differential equations]]
Apply [[Newton's second law of motion]], $\sum \vec{F} = m\vec{a}$ to a small segment of string with length $\Delta x$ in [[equilibrium]], then the mass is $\Delta m = \mu \Delta x$, and the forces at the end of the segment have $x, y$ components -- but the [[transverse wave]] [[tension force]] cancels out. 

Without making any assumptions about the [[shape]] of the string,

So similar to [[kinematics of mechanical wave motion#triangle congruency step|triangle congruency step]] #WaitWhat I hate this [[wave steady-state constraint]]. #GotIt it is because this string is "[[ideal string|perfectly flexible]]"
$${F_{1y} \over F} =-({\partial y \over \partial x})_x \ \ \ \ \ \ \ \ \ \ {F_{2y} \over F} =({\partial y \over \partial x})_{x+\Delta x} $$
$$F_y = F_{1y} + F_{2y}=F[({\partial y \over \partial x})_{x+\Delta x} - ({\partial y \over \partial x})_{x}]$$
and so $$F[({\partial y \over \partial x})_{x+\Delta x} - ({\partial y \over \partial x})_{x}]=\mu \Delta x {\partial^2 y \over \partial t^2} \ \ \ \ \ \implies \ \ \ \ \ \ \lim_{\Delta x \rightarrow 0}{[({\partial y \over \partial x})_{x+\Delta x} - ({\partial y \over \partial x})_{x}] \over \Delta x}={\mu \over F}{\partial^2 y \over \partial t^2}$$
and therefore, 
$${\partial^2 x\over \partial t^2} = {\mu \over F}{\partial^2 y \over \partial t^2}$$
#### ...for a [[ideal string]]
In [[equilibrium]] we have [[tension force]], $F$, and $\mu = \text{mass / length}$. 

When portions of the string leave equilibrium, $F$ increases, and $\mu$ decreases.

At $t=0$ apply constant force $F_y$, successive particles begin moving at $v_y$, and the disturbance propagates at $v$. Applying [[impulse-momentum theorem]], $$F_y t = mv_y$$
Since it is our claim that $v_y$ is a constant, this means that [[momentum]] is increasing because $m$ is decreasing, across each element.

At $t$ the string moved $v_yt$ and the [[wavefront]] $P=vt$., and the final force has $\sqrt{F^2+F_y^2}$ .

##### triangle congruency step
We apply [[impulse-momentum theorem]] again to the left-hand side up to $P$$${F_y \over F} = {v_yt \over vt} \ \ \ \ \ \ \implies \ \ \ \ \ \ F_y=F{v_y \over v}$$ ... and so the moving part of the string has momentum, $$mv_y=(\mu v t)v_y$$ and it follows that all momentum is due to $F_y$ so that
$$F{v_y \over v}t=\mu vtv_y$$
Which finally gives, that the [[wave speed]] depends only on the [[tension force]] and [[mass density]]: $$v=\sqrt{F \over \mu}$$