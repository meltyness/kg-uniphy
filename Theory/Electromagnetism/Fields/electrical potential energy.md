#C23-1 

Since [[electromagnetic interaction]] can be said to perform [[work]] on a [[subatomic particle]] we can use this [[potential energy]] as an important interpretation, while [[separating the situation from the specific motion]].

Recall to that from the earliest discussions of [[energy]] the definition that it is a property of a  [[mechanical system]]. [[energy is a property of systems not objects]].

The potential energy can also be interpreted as [[the potential energy is the work that must be done by an external force to move the particle slowly from b to a against the electrical force]] #WaitWhat why "slowly" ? ...

There is also an equivalent of the [[electric field]] for [[electromagnetic interaction]] called [[voltage, or electric potential]].

#### ... extended across [[superposition of fields]]
[[for every electric field due to a static charge distribution, the force exerted by that field is conservative]]
$$U = {q_0 \over 4\pi\epsilon_0}\bigg({q_1 \over r_1}+{q_2\over r_2}+\dots\bigg) ={q_0\over 4\pi\epsilon_0}\sum_i{q_i\over r_i}$$
And [[total electrical energy]] $$U={1\over 4\pi\epsilon_0}\sum_{i < j}{q_iq_j \over r_{ij}}$$
#### ... [[work]] done by $\vec{F}$ onto a [[particle]] moving $a \rightarrow b$
The definition of the work doesn't change.
$$ W_{a \rightarrow b} = \int_a^b\vec{F}\cdot d\vec{l}=\int_a^bF\cos\phi \ dl$$
Given that $\vec{F}$ is a [[conservative force, field]], that implies the following, where $U$ is the potential energy, $$W_{a \rightarrow b} = -\Delta U$$ we also have the [[work-energy theorem]], $$K_a + U_a = K_b+U_b$$
in words, the [[total mechanical energy]] is [[conservation|conserved]].

#### ... in a [[Coulomb's law]] field
We can represent any charge distribution as a collection of point charges ([[Earnshaw's theorem|even some impossible charge distributions]]). For the pair of charges, $q, q_0$ in a [[vacuum]],

For any path, $dr = d \vec{l}_\text{radial} = \cos\phi dl$

we can write that the work only depends on the [[radial]] [[displacement]]: $$W_{a \rightarrow b} = \int_{r_a}^{r_b}{1 \over 4\pi\epsilon_0}{qq_0 \over r^2}\cos\phi \ dl$$
which implies that the $W$ done by $F$ depends only on the initial and final [[states]], so establishing that it's a [[conservative force, field]] we can compute the [[potential energy]], 

with $${1 \over 4\pi\epsilon_0}{qq_0 \over r^2} = -{dU \over dr}$$
$$\int dU =U= {-qq_0 \over 4\pi\epsilon_0}{\int {r'^{-2}dr'}}={-qq_0 \over 4\pi\epsilon_0}{r^{-1}\over-1}\implies$$

$$U = {1 \over 4\pi\epsilon_0}{qq_0 \over r}$$

#### ... in a flat [[electric field]]
Similar ([[analogy]]) to [[surface gravity]] and [[gravitational potential energy]], we can find that inside of a [[parallel plate capacitor]] we'll have a field $E$ with $$E = {\sigma \over \epsilon_0}$$
we'll have work $$W_{a \rightarrow b} = q_0E\Delta y$$
which is [[path]] independent, it only depends on the initial and final coordinate, $y$.

We can also form a potential function, $$U=q_0Ey$$
recalling of course that this implies that potential increases when work is done against a force, and decreases when a force does work. $$\vec{F} = -\nabla \vec{U}$$
