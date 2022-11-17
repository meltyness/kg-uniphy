#C3-4
#KeyConcept 

The direction component of [[velocity]] changes.

[[the radial component of acceleration is the square of the speed divided by the radius of the circular path, and perpendicular to the velocity]]

#### Nonuniform Circular Motion
We no longer assume that the speed is constant.

In this case we [[formula|have that]] 
- $a_{rad} = {v^2/r}$ as derived in the [[kinematics of circular motion#Geometric Model|geometric model, below]] 
- and that $a_{rad} \perp \vec{v}$
- There is $a_{tan}$ which is $$a_{tan}={{d |\vec{v}|} \over dt}$$ recalling from earlier discussions that a change in speed would result in a vertical component.

This results in a [[fictitious force]] of [[eulerian acceleration]]

#### Uniform Circular Motion
Speed is a constant, $v = c = \sqrt{v_x^2 + v_y^2}$

direction of speed varies continuously

So, $v_y = \sin\omega t$, $v_x = \cos\omega t$ therefore $\alpha = \omega t$

And we can show using calculus that $\vec{a}\cdot\vec{v} = 0$ and that $\vec{a} \perp \vec{v}$ in this case.

#### Geometric Model
Along a circle with $R$, through an angle $\Delta \phi$ 

Construct a pair of similar triangles where:

1.) The triangle consisiting of the path at two instants, the velocities, and the [[displacement]].
2.) The triangle consisting of the velocities at two instances, and their difference.

It can be shown that these two triangles are similar, so we can associate the lengths of the sides, like this:
$$|\Delta\vec{v}| = {v_1 \over R}\Delta s$$
And then construct the average [[acceleration]] as: $$a_{av} = {|\Delta \vec{v}| \over \Delta t}={v_1 \over R}{\Delta s \over \Delta t}$$
and constructing the continuous case, $$a = \lim_{\Delta t \rightarrow 0}{v_1 \over R}{\Delta s \over \Delta t}={v_1 \over R}\lim_{\Delta t \rightarrow 0}{\Delta s \over \Delta t}$$
and so the *centripetal acceleration* is given$$a_{rad} = {v^2 \over R}$$
and if we reassociate this to the [[oscillatory period]] it takes to travel around the circle, $$ {2 \pi R \over v} = T$$ we find that $$a_{rad} = {4 \pi^2 R \over T^2}$$
#### Extension to a [[Centripetal Force]]
For this type of motion to persist:
$$F_{\text{net}} = ma_{\text{rad}} = m{v^2 \over R}$$

#### Relation to [[path]] [[curvature]]
[[kinematics in space#acceleration in space|acceleration and curvature]]

#### Related [[physical quantities]]
- [[frequency]]
