#C17-E 

A cooler is a [[machine]] for the purpose of [[human limitations|keeping food]] [[health and safety|free of disease]].

#### ... as a [[thermodynamic process, path]]
The [[efficiency]] is taken $$K={|Q_C| \over |W|}$$
A [[fluid flow]] is generated from a hot [[condenser]], passed through an [[expansion valve]], and then placed into [[thermal contact, material system junction, optical junction or adventure|thermal contact]] with the space to be refrigerated. [[heat flows so that thermal energy goes only from hot to cold]], and then the cycle is repeated until the [[human control|desired]] [[temperature]] is reached.

$K$ is given [[archaic|customarily]] in $\text{(Btu/h)/W}$ ... for refrigerators and air conditioners, right around $10$ is a common efficiency.

#### ... an ice cooler
We [[models|model]] an ice cooler: 

- For [[solid]] [[water]] $m_\text{ice}=24.0 \text{ Kg}$ at $0^\circ \text{ C}$, with [[latent heat|latent head of fusion]] $L_f = 334\times 10^3 \text{ J/Kg}$
	- Once melted, the ice accumulates in the bottom of the cooler
- A cooler with $V = (0.5 \text{ m})(0.5 \text{ m})(0.8 \text{ m})=0.2\text{ m}^3$ and interior [[air]] [[temperature]] $5^\circ \text{ C}$
- The external environment presents $21.0^\circ \text{ C}$ to the outside of the cooler
- The cooler must maintain $5^\circ \text{ C}$ for $1 \text{ wk} = 6.048\times 10^5 \text{ s}$

- Constructed of [[styrofoam]] with width $L_s$ 

#### The smart way
First we [[abstract negligible facets]]. 

Because $k_\text{water}$ for [[water]] $\approx 1.6 \text{ W/m K}$, and for ice $\approx 2.2\text{ W/m K}$ we have that it is 70-100x better thermal conductor than [[air]] or [[styrofoam]], so we [[form an equitropic joint-union]] of the ice, fluid water system, [[assume common, reasonable system geometry|since on most time scales]], this will form a good approximation of the overall behavior.

Then we can write that $$Q_{L_f} = (24.0)(334\times 10^3) \text{ J} = 8.016\times10^6 \text{ J}$$ with the assumption that the water that forms maintains $0^\circ \text{ C}$ with the ice, due to the conduction, and that the water "doesn't quite touch" the styrofoam, so that a thin layer of $5^\circ \text{ C}$ air forms there we can write down the [[thermal conduction]] for the styrofoam. $$ {dQ \over dt} = {8.016 \times 10^6 \text{ J} \over {6.048 \times 10^5 \text{ s}}} = (0.01 \text{ W/m K})[4(0.5)(0.8)+2(0.5)^2\text{ m}^2]{16^\circ \text{ C} \over L}$$
and solving for $L$ gives simply, $$L\approx 2.54 cm$$
#### The less-smart way
Assume the ice is suspended by a negligble string, and that as the heat due to melting $Q_{L_f}$ is released into the environment, $0^\circ$ water accumulates at the bottom of the container, and mixes so that the top-most layer is exactly $0^\circ$, and the layer abutting the styrofoam is $T_\text{fish}$, and the length is $\ell(t)$.

So with $m$ the mass of the melted water, $\bar{Q}$ the remaining energy in the ice, $$\bar{Q}(t)=(24-m(t))L_f=(24-\rho_{H_2O}(0.5)(0.8)\ell(t))L_f$$
we can try to apply [[Fourier's law of thermal conduction]], which is where this breaks down to successive layers of the sphere and find an inappropriate application of linear heat transfer:$${d\bar{Q} \over dt} = (2.2 \text{ W/m K})(4\pi r(t)^2 \text{ m}^2)\int_0^{r(t)}{dL\over L} $$
because attempting to model an abrupt [[temperature gradient]] gives $dT/dx \rightarrow \infty$, and we must change strategy.

Instead we write Fourier's law in general, $${\partial Q \over \partial t} = -k\oint_S\nabla T \cdot d\vec{S}$$
Taking our situation in **spherical coordinates** simplifies to a case where 
- Surface normals, $dS$ are always in the same direction as $\partial T / \partial r$ 
- $\partial T / \partial r$ itself has a jump discontinuity, but doesn't depend on the integral, so can be moved out as a constant, and resolved as follows:

Chain rule gives,
$${\partial T \over \partial r} = {\partial t \over \partial r}{\partial T \over \partial t} $$
and an application of [[Joule-Thomson Effect]], differentiated wrt time so that ( #Caution 
 this is clearly not applicable, if we want to take the remaining ice always $0$ and the air always $5$ $\Delta T$ doesn't vary with time $${\partial Q \over \partial t}{1 \over mc}={\partial T \over \partial t}$$ gives $${\partial Q \over \partial t}=-k{\partial t \over \partial r}{\partial Q \over \partial t}{1 \over mc}\oint_S dS $$
and with $m=\rho (\frac{4}{3}\pi r^3)$, and some re-arrangement we have $${\partial r \over \partial t} = {-k \over mc}(4 \pi r^2)={-3k \over rc}$$
A first-order non-linear ordinary differential equation with relevant solution family, $$r(t)=\sqrt{2 \over c}\sqrt{\alpha c - 3kt}$$ where $\alpha$ comes from the initial-value, and [[mass density]] relationship

With that we also can find an $\ell(t)$ from $\rho_\text{ice} / \rho_\text{water}$ 

#WaitWhat ... now i've gotten myself pretty confused.