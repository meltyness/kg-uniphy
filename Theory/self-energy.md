#C23-E 23.71

[[describe any facet of the assembly process|Assembling]] a uniformly-charged object with [[charge density]] $\rho$ leads to a [[duality|dichotomy]] that, [[the self energy to create a uniformly charged point charge is infinite]].

As found by drawing in shells of uniform density, the self energy on a uniformly-charged sphere is 

$$\bigg({3\over 5}\bigg){1 \over 4\pi\epsilon_0}{Q^2 \over R}$$

#### ... with charging by [[electrostatic induction]]
#WaitWhat #ProofDeferred Note, for the misread interpretation it may be that the [[method of images]] is needed to analyze this correctly, otherwise the problem is underdetermined.

>I was confounded a bit by the same problem, but I've come to the following confusion. In order to *integrate* and compute $W_{a \rightarrow b}$ you would need to write down $Q(r)$ (how much charge has accumulated on the sphere, based on how far you've brought some test charge in) which requires some clairvoyance regarding the dynamics of the situation.

>Following the setup for polarization from earlier chapters, with the changes:

> - It's already connected to ground
> - Ground is $\infty$ far away, and the charge accumulated there has no contribution.

>However, with the surface [[assume the maximum possible|at]] $\infty$ $V=0$, and drawing a test charge in towards the surface to a point $P$, which we can treat as a net charge-centered point charge, per Gauss's Law. 

>At $P$, we have $$V={1\over 4\pi\epsilon_0}{Q \over r_f}$$
where $r_f$ is some arbitrary distance at which the sphere would have taken on the targeted quantity of charge $Q$.

>And then to find the work, $$W=U_f=Vq_0={1\over 4\pi\epsilon_0}{Qq_0 \over r_f}$$which does not encode any assumptions about $q_0$ or how $Q$ varies with distance. I would say *no*, that the work required depends on $Q$, not $Q^2$.

