#C28-6

Provides a [[formula|relationship]] between enclosed [[electrical current]] and the [[magnetic field]]. Similar to [[Gauss's law for Magnetism]], we [[establish a test volume or area]], however instead of a [[test volume]], rather we consider a [[path]] enclosing a [[surface]] / [[membrane]]. This enables us to [[exploit the symmetry of a problem]]

#### ... [[derivation]] / [[creativity|motivation]]
From [[Biot-Savart law]] we found that $$B={\mu_0I \over 2\pi r}$$ so that the field lines for concentric circles centered on the [[electrical conductivity, and resistivity|conductor]], and since they are everywhere parallel, $\vec{B}\cdot d\vec{l} = B \ dl$

So computing a closed-path [[integral]], $$\oint \vec{B}\cdot d\vec{l}=\int B_\text{||} \ dl= B\int \ dl = {\mu_0I \over 2\pi r}(2\pi r) = \mu_0I$$ and is independent of the radius of the path, still adhering to the [[right-hand rule]].

Another [[potato extension technique]] can be used to show that this holds for any general path, and applying [[superposition of fields]], $$\oint \vec{B}\cdot d\vec{l}=\mu_0I_\text{enclosed} \ \ \ \ \ \ \ \ \text{(for constant current, electric flux)}$$in simple geometric terms, the sum on the path of the tangent components of the magnetic field is proportional to the current enclosed.

#Caution the [[range of validity]] is limited to where $I \ne I(t)$, so that it only applies to [[DC circuits]].

#### ... for [[displacement current]], and [[electromagnetic induction]]
Consider the process of charging [[R-C circuits]], a current $i_c(t)$ flows around the circuit and puts $Q$ on the plates of the capacitor. With [[magnetic flux]]/[[electrical current]] relationship: $$\oint \vec{B}\cdot d \vec{l} = \mu_0 I_\text{encl}$$ through two distinct surfaces:
- The flat surface wire carrying the current,
- A "bulged" surface through the plate, where there is apparently zero current,

[[considering the alternative situation, and deducing a contradiction (pulling it out of thin air)|implies that there is a contradiction]] in *this* form of the law.

As $Q$ accumulates, $\vec{E}$ and therefore $\Phi_E$ are increasing. We argue, from the invariants developed for [[parallel plate capacitor#derivation and formula|parallel plate capacitance defined]] 
- $q(t)=Cv(t)$
- $C=\epsilon A/d$ where we can account for [[dielectric, and dielectric strength|the presence of a dielectric]] via the [[permittivity]]
- $v(t)=Ed$ neglecting [[electric field line fringing]]
- $\Phi_E = EA$ 

we can simply derive that $$q(t) = \epsilon \Phi_E(t)$$ and with $i_C = dq / dt$, $$i_C(t) = {dq \over dt} = \epsilon {d\Phi_E \over dt}$$
which is called the [[displacement current]], a sort of [[fictitious current]] between the plates, $$i_D(t) = \epsilon{d \Phi_E \over dt} \ \ \implies \ \ j_D = \epsilon{d E \over dt}$$ and so to account for this effect, we generalize $$\oint \vec{B}\cdot d\vec{l} = \mu_0(i_C(t) + i_D(t))_\text{enclosed}$$ this effect also modifies [[Kirchoff's rules#Kirchoff's Junction rule|KCL]], since a capacitor, in a naive way, does not allow there to exist a [[complete electrical circuit]].
