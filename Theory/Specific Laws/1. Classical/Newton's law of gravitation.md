#C12-1
## Basic Description
Two [[particle|particles]] of [[material]] in [[space]] a [[displacement|distance from one another]] with [[mass]] undergo [[attraction]] and [[acceleration]] towards one another. It is an [[inverse square law]].

This is why large bodies tend to be spherical, because the particles tend to minimize the distance between them.

[[synthesizes a very generic, correct statement regarding a number of disparate observations]]

#### Definition
[[Every particle of material in the universe attracts every other particle with a force that is directly proportional to the product of the masses of the particles and inversely proportional to the square of the distance between them]]

#### [[formula]]
A [[conservative force, field]], the [[potential energy|potential]] is given: $$U(r)=-G{m_1m_2 \over r}$$and it follows that for $i=x,y,z$ $$F_i = {-Gm_1m_2i \over {(x^2+y^2+z^2)^{\frac{3}{2}}}}$$
$G$ is called the [[gravitational constant]].

As a [[force]], gravitation is also subject to [[superposition of forces]].

#### [[derivation]] for a spherical shell, demonstrating [[point-equivalence]]
#C12-6
For a mass distributed with $M=\sum m_i$ on a hollow spherical shell with $R$ and taking $U_i= -Gmm_i/s$ where $s$ is the separation on a specific part, and $r$ is the distance of the [[particle]] from the [[mass]], we find that $$dU=\sum U_i = -{Gm \ dM \over s}$$
next we iterate over the surface areas along $\phi$ with the following strips: $$dA=2\pi R^2\sin\phi \ d \phi$$
So that this can be interpreted as the circumference, $2\pi R\sin \phi$ times the width, $R \ d\phi$ of rectangular strips, since this is evenly distributed and we know the surface area of a sphere is $4\pi R^2$ we can write $${dM \over M} = {dA \over A} = {2\pi R^2\sin\phi \ d\phi \over 4\pi R^2} = \frac{1}{2}\sin\phi \ d\phi$$
And backfilling, $$dU = {-Gm\sin\phi \ d \phi \over 2s}$$
varying $\phi \in [0, \pi]$, $s \in [r-R, r+R]$ since this situation can always be made [[axis symmetric]].

We also must write $s$ in terms of $\phi$ we do so as follows: $$s^2=(r-R\cos\phi)^2+(R\sin\phi^2)$ = r^2-2rR\cos\phi+R^2$$
and taking the derivative, $$2s \ ds = 2rR\sin\phi \ d\phi$$
into $dU$, $$dU={-GMm \over 2rR} \ ds$$
and finally, 
$$U=-{GMm \over 2rR}\int_{r-R}^{r+R}ds=-{GMm \over 2rR}[(r+R)-(r-R)]$$
which reduces to $$\therefore U={-GMm \over r}$$
#### Inside the shell
Inside the shell we have $U={-GMm \over R}$ which doesn't vary with position -- [[apparent weight]] zero.

#### Varying [[mass density]]
It obviously follows from the above that for *arbitrary* shells, that each one only contributes based on its distance from the center.