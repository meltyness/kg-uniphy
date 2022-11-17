#C16-1 

#### ... [[wave speed]] based on [[material phase]]
$$ v=\sqrt{B \over \rho} \ \ \ \ \ \text{(fluid)}$$
$$v = \sqrt{Y \over \rho} \ \ \ \ \ \ \ \text{(solid)}$$
Gas is a special case, where this depends on [[temperature]] to a great extent on [[ratio of heat capacities]], the [[gas constant]] which implies $B=\gamma p_0$
$$v = \sqrt{\gamma RT \over M} \ \ \ \ \ \ \text{(gas)}$$
And as an additional note $\gamma, R, M$ depend on the [[kind of material]]
- $\gamma$ the ratio of heat capacities
- $M$ is the [[molar mass]]
- $R$ the gas constant
- $T$ is the [[temperature]]

#### ...[[derivation]] of [[wave speed]]
#C16-2 
A [[fluid]] (possibly [[air]]) in a [[test volume]] [[container|capped]] with a [[piston]] or [[diaphragm]] at one end with a plate, has

At [[equilibrium]]:
- An area $A$
- An incident pressure, $p$
- (which together imply some sort of [[force]])
- The [[fluid]] inside (which is no longer an [[ideal fluid]]) a [[bulk modulus]]
	- With a resulting $V$ [[volume]]
	- and a [[mass density]], $\rho$

With [[kinematics along a straight line]] (the [[piston]] moving with [[Newton's first law of motion]], constant [[velocity]])
- The piston has moved $v_yt$
- The fluid [[incident]] is moving with $v_y$,
	- The [[wavefront]] is at $vt$ (with the [[wave speed]], still unknown)

Computing the [[momentum]] of the fluid gives:
$$\text{fluid momentum} = (\rho vtA)v_y$$
Computing the [[bulk modulus]], $$B = {-\Delta p \over -Av_yt/Av_t} $$and solving for the change in pressure (corresponding to the [[forced oscillation]]) $$\Delta p =B{v_y \over v}$$ applying [[impulse-momentum theorem]] gives $$\Delta p A t = B{v_y \over v}At$$
and we can solve these equations for the
$$ v=\sqrt{B \over \rho}$$
#### ...[[derivation]] of [[formula]] [[analogy|from]] [[relative pressure]]
At any point we take $p_a+p(x,t)$, and treat $p$ like the disturbance $y$ in the analysis of [[transverse wave]] given in [[kinematics of mechanical wave motion]].

For example at a [[test volume]] [[cylinder]] with $A$ and its [[axis]] along the $x$ and we can associate two [[states]]:

- With [[equilibrium|no wave present]], $V=A\Delta x$ with geometry $y_1,y_2$ as distances along the cylinder
- A time $t$ forward, we have $y_1=y(x,t)$ and $y_2=y(x+\Delta x, t)$

So $\Delta V = A(y_2-y_1) = A[y(x+\Delta x, t) - y(x,t)$, and $${dV \over V}=\lim_{\Delta x\rightarrow 0}{{S[y(x+\Delta x, t)-y(x,t)]} \over {S\Delta x}}={\partial y(x,t) \over \partial x}$$
Using the [[bulk modulus]] $B$ to find the [[bulk stress]] ${-p \over (dV / V)}$ we have 
$$p(x,t) = -B{\partial y(x,t) \over \partial x}$$
next, following from [[kinematics of sound waves]] $$p(x,t)=BkA\sin(kx-\omega t)$$
Where $p_\text{max} = BkA$ is the [[amplitude]]. $k$ is the [[wave number]]. The form suggests it is related to [[law of conservation of momentum]], [[elastic collision]], and [[particle]].