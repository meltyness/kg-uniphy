#C10-7

A gyroscope uses [[angular momentum]] to [[build, or part|create]] a stable equilibrium, measure flywheel by [[precession]].

The [[earth, atmosphere, water, and wildlife]] has a [[precession]], that its axis completes every 26,000 years.

#### Technical Discussion / [[models|Model]]
Recall that in our discussions of [[torque]] a key assumption was that the axis does not change direction, however in the case of a gyroscope, the [[axis]] *must* change direction.

![[Pasted image 20220725103918.png]]

At rest, the gyroscope with $O$ at the origin, the [[flywheel]] has a large mass relative to the pivot assembly, $M$ and $I$ about its axis, initially aligned on $x$. The forces on the gyroscope are such that $\hat{n}$ [[normal force]] acts at the Pivot, and $\vec{w}$ [[weight]] acts at the flywheel.

In this [[states|state]] there will be a [[torque]] $\tau$ at the pivot with the weight of the flywheel. 

Initially $L_i=\vec{0}$. And we also have the relationship $d\vec{L} = \vec{\tau} \ dt$.

We drop the flywheel axis, and applying [[right-hand rule]] to the torque relationship with axis away from pivot, towards the weight force, gives an angular momentum for this fall towards the $+\theta$ direction, $d\vec{L}$ will have the same direction from the discussion of [[angular momentum]].

Now if the flywheel starts with some momentum, $\vec{L}_i$ and we assume very large $\omega$ for the flywheel, we find the following situation:

- $L_i$ is along the flywheel axis
- $d\vec{L}$ is perpendicular, because $d\vec{L} = \vec{\tau}dt = \vec{r} \times \vec{w}$ is perpendicular to the flywheel axis.

Therefore $\vec{L}$ changes, but the net external forces are such that it only changes direction in the plane traced out by the flywheel axis.

We can compute the precession angular speed by finding that applying [[the arc length of a circle with given radius through a given angle is their product|arc length formula,]] $|\vec{L}| \ d\phi = |d\vec{L}|$ so that $$d\phi = {|d\vec{L}| \over |\vec{L}|}$$
and to [[derivation|find]] the [[formula]] for $\Omega = \text{precession angular speed}$ $d\phi / dt$ we write: $$\Omega = {d\phi\over dt}={{|d\vec{L}|/\vec{L}} \over dt} = {\tau_z \over L_z}={wr \over I\omega}$$ So it can be related to the weight, the distance of the flywheel axis and the momentum of the flywheel axis.

#### Violating [[abstract negligible facets|simplifying assumptions]]
- There's an assumption that the flywheel is the [[center of mass]] of the whole device which implies that gravity acts there only.
- There's an assumption that $\omega >> \Omega$ the flywheel is spinning much faster, but in the presence of typical things like [[friction force]], this will be violated and result in [[nutation]]
