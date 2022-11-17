#C6-2
#KeyConcept 

We also have the following: [[the work done by the net force on a particle equals the change in the particle's kinetic energy]] which gives the [[formula]] $$W_{\text{tot}}=K_f-K_0=\Delta K$$
#Caution Notice too that with$$F = ma = \frac{1}{2}{{mv_f^2-mv_0^2} \over s}$$In [[derivation|computing]] a force related to the given [[kinematics along a straight line#with Constant Acceleration|situation]], we applied [[Newton's second law of motion]], so this only can apply to an [[inertial frame of reference]]. As well, the *work* observed may differ from one frame to another.

#### [[derivation]] of a more general case
The work-energy theorem holds even in the case where the [[externality|external forces applied]] varies.
$$a = {dv\over dt}={dv \over dx}{dx \over dt}=v{dv \over dx}$$
From [[work#Formula]] we have that $$W=\int_{x_1}^{x_2}Fdx=\int_{x_1}^{x_2}mv{dv \over dx}dx=\int_{v_1}^{v_2}mvdv$$
and so $$W_{\text{tot}}=\frac{m}{2}(v_2^2-v_1^2)$$
#### [[derivation]] of the most general case in space
We'll take the linear case presented above, and expand it as follows $$W =\int_{P_1}^{P_2}\vec{F}\cdot\vec{dl}=\int_{P_1}^{P_2}F_xdx + F_ydy+F_zdz$$ $$=m\int_{P_1}^{P_2}a_xdx + a_ydy+a_zdz=m\int_{P_1}^{P_2}v_x{dv_x \over dx}dx + v_y{dv_y \over dy}dy+v_z{dv_z \over dz}dz$$ $$ =m\int_{P_1}^{P_2}v_xdx +v_ydy+v_zdz ={m \over 2}(v^2 -v_1^2)$$
So again, the work-energy theorem holds in general space.

#### final note
As a final note, when applying the [[work-energy theorem]] to systems it is best to consider [[kinetic energy of a rigid body#formula|the kinetic energy of a rigid body in total]] -- the sum of translational and rotational energy. Easy!

#### See also
- [[stationary-action principle]]