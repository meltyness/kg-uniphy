#C20-1 
This [[electrical properties of materials]] leads to [[resistor]]

#### ... [[lattice electronic energy]]
With an analysis using [[Schrödinger equation]] and [[quantum mechanics]] more detail can be gleaned.

#### ... from [[subatomic particle collisions]], [[intermolecular long-range order]] inside of a [[metal]]
We want to come to a [[derivation]] that supports our claim of ohmic behavior in metals.

- With $\vec{J}=nq\vec{v}_d$ as discussed in [[current density]]
- Knowing that $q$ is the [[elementary charge]] and assuming [[electrons]] are the primary charge carriers,
- So we attempt to relate $E$ to $v_d$ that [[how much on average|on average]] speed gains are speed losses.
- At $t=0$ we have $E[\vec{v}_0] = \vec{0}$, and introduce field $\vec{E}$
- $\vec{F}=q\vec{E}$ is seen at all charges in the concentration, and by [[Newton's second law of motion]],
	- $$\vec{a} = {\vec{F} \over m} = {q\vec{E}\over m}$$
- Following from [[kinematics along a straight line]], at $t=\tau$ (the [[mean free time]] for each [[electrons]]) $$\vec{v}=\vec{v}_0+\vec{a}\tau$$
- And striking $\vec{v}_0$ and replacing $\vec{a}$, $$\vec{v_d}={q\tau \over m}\vec{E}$$
- And substituting into our expression $\vec{J}$ $$\vec{J} = nq\vec{v}_d={nq^2\tau \over m}\vec{E} $$
- So we find that in a metal, $$\rho={m \over ne^2\tau}$$ 
Additionally the [[Tolman-Stewart experiment]] demonstrates that [[electrons]] are indeed the carriers.

#### ... conductivity in [[electrical current]]
Resistivity is an [[electrical properties of materials]] is the reciprocal of conductivity, applying [[Ohm's law]] $$\rho = {E \over J} \ \ \ \ \ \ \ \text{(resistivity)}$$

#### ... [[table]] of common [[kind of material]]
(At $20^\circ \text{ C}$)
|Conductive material|$10^{-8} \ \rho \ (\Omega \text{ m})$|Resistive material|$\rho \ (\Omega \text{ m})$|
|-|-|-|-|
|[[metal]]||[[semiconductors]]||
|[[silver]]|1.47|[[carbon]]|$3.5\times 10^{-5}$|
|[[Copper]]|1.72|[[germanium]]|$0.60$|
|[[gold]]|2.44|[[silicon]]|$2300$|
|[[Aluminum]]|2.75|[[dielectric, and dielectric strength]]||
|[[tungsten]]|5.25|[[amber]]|$5\times 10^{14}$|
|[[steel]]|20|[[glass]]|$10^{10} - 10^{14}$|
|[[lead]]|22|[[lucite]]|$>10^{13}$|
|[[mercury]]|95|[[mica]]|$10^{11}-10^{15}$|
|[[alloy]]||[[fused quartz]]|$75\times 10^{16}$|
|[[Manganian]]|44|[[sulfur]]|$10^{15}$|
|[[Constantan]]|49|[[teflon]]|$>10^{13}$|
|[[Nichrome]]|100|[[wood]]|$10^8-10^{11}$|

The extremely large difference leads to the obvious [[approximating specific complications|usefulness]] of the [[complete electrical circuit]]. Compare this also to [[thermal conduction#Common k values]] there's a trend that good heat conductors generally form good electrical conductors.

[[in typical materials the electrical conductivity is much greater than the thermal conductivity]]

#### ... resistivity and [[temperature]]
We introduce a factor to [[simply fit a relationship]] to this behavior $$\rho(T) = \rho_0[1+\alpha(T-T_0)]$$ where $\alpha$ is called the [[temperature coefficient of resistivity]], a kind of [[tropographic]] [[states]] for the [[electrical properties of materials]] in this case.

$\alpha \approx 0.0025$ would be a good guess though [[carbon]] in the form of [[graphite]] has a negative relationship. This property can be used to form a [[thermometer]].

Thermal dependence of temperature leads to the concept of the [[superconductor]].

#### Conductivity in [[electrostatic interactions]]
A [[material system]] can maintain a [[net charge]]. [[metal]] and [[kind of material]] that have good [[thermal conduction]] are often good conductors of [[motion involving electrical charges]].

If this system is brought into contact with another [[material system]] through a conductive material, it can become charged. Most [[metal]] [[kind of material]] are good conductors. During [[metallic bonding]] and [[solidfying]] the outer [[electrons]] can be free in the material and can undergo [[intermolecular motion of charges]].

If there is an [[electric field]] inside of the conductor, this implies forces onto those free charges, and thus [[intermolecular motion of charges|motion]]. Then we can [[employ deductive reasoning]] to find that
- everywhere in the [[material]] of a conductor (possibly excluding voids), 
- undergoing only [[electrostatic interactions]], has
$$\vec{E} = 0$$
[[in electrostatics the electric field at every point within the material of a conductor must be zero]]

This principles leads to the [[Faraday cage]]

###### ...in the presence of [[cavitation]]
#C22-5 
[[in an electrostatic situation a conductor cavity surface has no net charge|Since any excess charge will be repulsive, it won't accumulate on the surface of the cavity, only on the outer surface of the conductor]]. #WaitWhat proof deferred

If we place a charge in the cavity, then it polarizes the inner surface, which then polarizes the outer surface.

It polarizes to match $\vec{E} = 0$ inside the conductor, for [[in electrostatics the electric field at every point within the material of a conductor must be zero|the previous discussion]].

This effect is confirmed with [[Faraday's ice-pail experiment]], or [[Van de Graaff generator]]

###### ...near the [[surface]] of a conductor
We have that (for some [[test volume]]) we find *near* the surface $$E_\perp A={\sigma A \over \epsilon_0} \ \ \ \ \ \ \ \ E_\perp = {\sigma \over \epsilon_0}$$
This type of analysis leads to an understanding of [[lightning, and lightning rods]], [[electrical voltage corona]], and dielectric strength
