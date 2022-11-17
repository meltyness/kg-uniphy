#C34-3

The [[derivation]] proceeds as follows:
- A spherical surface with [[optical radius]] $R$ separates two [[material system|materials]] with [[index of refraction|refraction indices]] $n_a, n_b$.
- An [[image point]] $P'$ is formed from a [[point object]] at $P$
- Applying [[sign rules of geometric optics|sign rules]] gives
	- Rule 1 for $s$ 
		- since light from the [[point object]] $P$ is traveling towards the lens, $s$ is positive
	- Rule 2 for $s'$ 
		- since the light from the lens is traveling towards the [[image point]] $P'$, $s'$ is positive
	- Rule 3: $R$ 
		- since the light from the lens is traveling towards $C$, $R$ is positive.
- $PV$ along the [[optical axis]] passes through with $\theta_a = \theta_b = 0^\circ$
- $PB$ with an angle $\alpha$ off the axis passes through with $\theta_a$ to the [[material surface normal]] and undergoes [[law of light transmission, and refraction|refraction]] so that the outgoing angle make $\theta_b$ off the axis
- $n_a < n_b$ means that the lens is a denser refractive material, light slower inside, and observing that [[refraction always places the refracted ray on the opposite side of the normal as the incident ray]]
- Following from planar geometry, $\theta_a = \alpha+\phi$, and $\phi = \theta_b + \beta$
- Starting from 
	- [[law of light transmission, and refraction]] $n_a\sin\theta_a=n_b\sin\theta_b$, 
	- [[approximating specific complications]]  $n_a\theta_a=n_b\theta_b$,
	- backsubtituting $\theta_a$,we get $\theta_b={n_a \over n_b}(\alpha +\phi)$
	- and backsubstituting again $$\phi = \beta + {n_a \over n_b}(\alpha +\phi)\implies (n_b-n_a)\phi=n_a\alpha+n_b\beta$$
- Applying trig and [[paraxial approximation for a spherical mirror|paraxial approximation]],
$$\alpha = {h \over s} \ \ \ \ \ \ \ \ \beta={h \over s'} \ \ \ \ \ \ \ \  \phi = {h \over R}$$
- And finally in total, the [[object-image relationship]] for both convex and concave lens with the sign laws applied appropriately is then, $${(n_b-n_a) \over R} = {n_a \over s} + {n_b \over s'}$$
- And to obtain the [[optical magnification]], cast two rays from an [[extended object]] a length $y$ from the [[optical axis]]
	- One ray orthogonal to the lens non-refracted from $Q$ to $Q'$
	- Another from $Q$ refracted through $V$ to $Q'$ #ProofDeferred  gives [[formula]], $$m={-n_as' \over n_bs}$$
- We can also [[take a well-known general relationship, and extend it to a simpler case|derive from this the behavior of a planar surface by taking]] the [[object-image relationship]] [[assume the maximum possible|as]] $R\rightarrow \infty$ and also find the [[optical magnification]], $${n_a \over s}+{n_b \over s'} = 0 \ \ \ \ \ \ \ \ \ \ \ \ m=1$$
- #WaitWhat is the [[focal point, and focal length]] in this instance?? (see #C34-E 34.92)
- ![[Pasted image 20221004183529.png]]

#### Applications
- [[fiber optics]]