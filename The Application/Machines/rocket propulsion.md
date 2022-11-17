#C8-5 
#EmergingTechnology 
A form of [[locomotion]] generated from [[combustion]] of a [[propellant]].

#### Other considerations
- [[slosh]]
- [[pogo]]
- [[water hammer]]

#### Discussion
Momentum [[models|modeling]] can be used when [[mass]] is variable. 

[[Newton's second law of motion]], $\sum \vec{F} = m\vec{a}$ is not applicable because $m$ is changing.

#### [[derivation]] of the [[formula]]
A rocket is propelled forward by rearward ejection of burned fuel initially contained in the rocket, termed **[[propellant]].** [[action-reaction pair|The forward force on the rocket is the reaction to the backward force on the ejected material.]] The total [[mass]] is constant, but the mass of the rocket decreases as material is ejected.

In a [[vacuum]] with no [[fluid resistance]] or [[gravitational interaction]], we capture our assumptions
- The variable, $m$ represents the mass of the rocket.
- The rocket moves along the $x$-axis. 
- Through any small time window, $dt$ it will have expelled $-dm$ propellant and $m+dm$ mass at that [[time]]. (from which the modeling technique, [[it won't always be immediately obviously which rate a phenomena effects]])
- The rocket also has [[speed]] $v_\text{RKT}$.
- Initially we have $P_1 = mv_\text{RKT}$.

To find $P_2$ we make the following observations:
- $v_{\text{ex}}$ is the speed of the exhaust [[relative velocity|relative]] to the rocket.
	- The [[velocity]] relative to the rocket is then $-v_{\text{ex}}$
- To a stationary observer then $v_{\text{fuel}}=v_\text{RKT}-v_{\text{ex}}$
- It follows that the momentum of the fuel is $(-dm)v_{\text{fuel}}=(-dm)(v_\text{RKT}-v_{\text{ex}})$.

We write that
- So the rocket's momentum is $(m+dm)(v_\text{RKT}+dv_\text{RKT})$.
- And the total momentum is $P_2 = (m+dm)(v_\text{RKT}+dv_\text{RKT}) + (-dm)(v_\text{RKT}-v_{\text{ex}})$
- Therefore we have due to [[law of conservation of momentum]] and an [[isolated system]] with no [[externality|external forces]], $$P_1 = P_2$$$$mv_\text{RKT}=(m+dm)(v_\text{RKT}+dv_\text{RKT}) + (-dm)(v_\text{RKT}-v_{\text{ex}})$$
- This spans out to $$mdv_\text{RKT}=-dmv_\text{ex}-dmdv$$
- Since $dmdv << dv, dm$ we can disregard that term and rearrange to find $$m{dv \over dt}=-v_\text{ex}{dm \over dt} \ \ \ \ \ \text{(thrust)}$$
- To find $v$ rewrite: $$dv = {-v_\text{ex} {dm \over m}}$$
- Take integral [[priming the variable to use the upper limit]] $$\int_{v_0}^v dv'=-\int_{m_0}^mv_\text{ex}{dm' \over m'}\implies$$ $$v - v_0 = -v_\text{ex}\ln{m \over m_0}=v_\text{ex}\ln{m_0 \over m}$$
 