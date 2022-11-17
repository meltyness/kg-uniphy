#C34-2
Contained are [[derivation]]
#### ... for a spherical concave [[mirror]]
- Since we suspect this depends on [[curvature]], the best place to start is the spherical mirror.
- A [[point object]] at $P$ is on the reflecting side of a spherical mirror just behind its [[center of curvature]] (the center of the sphere)
- The [[point object]] sits a positive distance $s$ along the [[optical axis]] from the [[optical vertex]] of the mirror.
- An [[optical ray]] along the [[optical axis]] intersects a point, $P'$ just in front of the [[center of curvature]], and a positive distance, $s'$ from the [[optical vertex]].
- Additionally, all rays intersect at $P'$, producing a [[real image]].
	- When the observer is near the [[optical axis]], and the object $s$ is far away,
	- For small [[angle]] of [[optical ray]] from the [[point object]] off the [[optical axis]], $\alpha$
		- Outgoing [[optical ray]] passes through $P'$ making angle $\beta$ with [[optical axis]]
	- Following from the first and second [[sign rules of geometric optics|sign rule]], $s$ and $s'$ are both positive, and sign rule 3, interior to the curvature, $R>0$.
	- For a point on the mirror, at $(\phi, R)$ we can consider the ray in terms of $\alpha, \beta, \theta$ where $\theta$ is the angle of attack, and by [[law of specular reflection]] outgoing angle as well off the [[material surface normal]].
	- Trigonometric analysis gives $\phi=\alpha+\theta, \beta=\phi+\theta\implies \alpha+\beta = 2\phi$.
	- More trig gives the equations $$ \tan\alpha={h \over s - \delta} \ \ \ \ \ \ \ \ \ \tan\beta={h \over s' - \delta} \ \ \ \ \ \ \ \ \ \tan\phi={h \over R - \delta}$$
	- To arrive at the [[paraxial approximation for a spherical mirror]], we apply [[approximating specific complications]] taking the $\tan$ [[function]] near the [[origin]], and $\delta$ small (essentially, $s$ far from the mirror)	$$ \alpha = {h \over s} \ \ \ \ \ \ \ \ \ \beta = {h \over s'} \ \ \ \ \ \ \ \ \ \phi = {h \over R}$$
	- This process corresponds to a kind of [[dilation and contraction]] transforming the [[point object]] to the [[real image]].

This gives the [[object-image relationship]], and in terms of [[focal point, and focal length]] has [[formula]] $${1 \over s} + {1\over s'} = {2 \over R}={1\over f}$$
Additionally, we can show through geometry that the [[optical magnification]] is $$m={-s' \over s}$$

#### ... for a spherical convex [[mirror]]
- Following from [[sign rules of geometric optics|sign rule 3]], $R<0$ for the case where the outgoing light from the [[point object]], $P$ is on the opposite side of the [[center of curvature]]
- All the reflected rays from $P$ converge at $P'$ on the opposite side of the [[optical vertex]], which implies that $s'<0$.
- Since $s$ is on the reflecting side, $s>0$.
- Following from the [[paraxial approximation for a spherical mirror]], $${1 \over s} + {1 \over s'} = {2 \over R}$$
- In this case however, the [[optical magnification]] is inverted, $$m={-s' \over s}$$