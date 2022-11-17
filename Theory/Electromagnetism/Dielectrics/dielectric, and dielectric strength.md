#C24-4

This is a [[kind of material]], that is by nature [[electrical conductivity, and resistivity|insulatitve]], and is used to perform three tasks

- Separate the conductor [[metal]] in a [[ideal capacitor]].
- Increases the maximum [[voltage, or electric potential]], before [[capacitive breakdown]] occurs.
- Increases the [[ideal capacitor|capacitance]] achieved in the design, by lowering the voltage for the same amount of [[net charge]] accumulated.
	- An [[electrostatic induction]] occurs, resulting in [[material system charge polarization]], reducing the [[voltage, or electric potential]] at the plate.

#### ... using [[Gauss's law]]
We can perform an analysis such that by assuming that $$Q_\text{encl free} = A(\sigma-\sigma_i)$$....and it follows that,
$$\oint K\vec{E}\cdot d\vec{A}={Q_\text{free charges} \over \epsilon_0}$$

#### ... the [[dielectric constant]]
Based on the original capacitance, and the conclusion that the propensity of the material to polarize without conducting results in a new $V_0$ we write$$K = {C \over C_0} = {V_0 \over V}$$
holding $Q$ and thus, for example $\sigma / \epsilon_0$ constant

When the [[material system]] becomes [[material system charge polarization|polarized]], it does so with a constant proportionality akin to [[Hooke's law]], $$E = {E_0 \over K}$$ and so $\sigma_i$ is the induced surface [[charge density]], which has a [[range of validity]] limited to low voltages, and non-[[crystal]] materials with low [[intermolecular long-range order]] and high [[order and disorder|disorder]]. $$E={\sigma - \sigma_i \over \epsilon_0}$$
and this gives a relationship $$\sigma_i = \sigma\bigg( 1 - {1 \over K}\bigg)$$
and the dielectric [[permittivity]] is then $$\epsilon = K \epsilon_0$$
and the capacitance, for a [[parallel plate capacitor]] $$C = KC_0 = K\epsilon_0{A \over d}=\epsilon{A \over d}$$
and [[energy density]] $$ u = \frac{1}{2}K\epsilon_0E^2 = \frac{1}{2}\epsilon E^2$$
#Warning $K$ in an [[AC circuits]], and [[electromagnetic waves and light]] also depends on the [[frequency]], [[electromagnetic spectrum, frequency of light]] -- any frequency where the [[material system charge polarization]] may no longer can be understood as an [[electrostatic interactions]].

#### ... the [[dielectric leakage|leakage]] [[electrical current|current]]
Since no dielectric is a perfect [[electrical conductivity, and resistivity|resistor]], some [[electrical current]] will flow through any such [[complete electrical circuit]], and as a result for very long [[duration]], a capacitor isn't effective for long term [[energy storage and transmission]].

Following from #C25-E 25.65, for a dielectric in place, this can be computed from the [[electrical conductivity, and resistivity|resistivity]], $\rho$ of the material: $$I_\text{leakage} = {Q \over K \rho \epsilon_0}$$
#### ... before [[capacitive breakdown]]
The dielectric strength is given as $E_m \text{ (V / m)}$

#### ... [[table]] of common [[kind of material]]
|material type | $K \ \ @ \ \ 20^\circ \text{ C}$|Dielectric strength $E_\text{m} \text{(V / m)}$|
|-|-|-|
|[[vacuum]]|1|
|[[air]] @$\text{1 atm}$ [[pressure]]|1.00059|$3\times 10^6$|
|[[air]] @ $\text{100 atm}$|1.0548|
|[[teflon]]|2.1|
|[[polyethylene]]|2.25|
|[[polycarbonate]]|2.8|$3\times 10^7$|
|[[polyester]]|3.3|$6\times 10^7$|
|[[polypropylene]]|2.2|$7\times 10^7$|
|[[polystyrene]]|2.6|$2\times 10^7$|
|[[pyrex glass]]|4.7|$1\times 10^7$|
|[[benzene]]|2.28|
|[[mica]]|3-6|
|[[mylar]]|3.1|
|[[polyvinyl chloride]]|3.18|
|[[plexiglas]]|3.40|
|[[glass]]|5-10|
|[[neoprene]]|6.70|
|[[germanium]]|16|
|[[glycerin]]|42.5|
|[[water]]|80.4|
|[[strontium titanate]]|310|

[Changing the Dielectric in a Capacitor - YouTube](https://www.youtube.com/watch?v=PF0g4EcBVh0)