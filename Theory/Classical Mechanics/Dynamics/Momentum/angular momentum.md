#C10-5
#KeyConcept 

#### Definition
Analogous to [[momentum]], [[the rate of change of angular momentum of a particle equals the torque of the net force acting on it]]. It is a [[vector quantity]]

$$\vec{L}=\vec{r}\times\vec{p}=\vec{r}\times m\vec{v}$$
$${d\vec{L} \over dt} = \vec{r} \times \vec{F} = \vec{\tau}$$

#### [[formula]] for a [[rigid body]]
We want to find the [[formula]] for [[superposition of forces|total]] angular momentum of a rigid body rotating about $z$ with $\omega$.

Since we are in [[kinematics of circular motion|rotational motion]], each particle in the $xy$-plane has $v_i$ perpendicular to $\vec{r_i}$, hence,
$$L_i = r_i(m_i)v_i = r_i(m_i)(r_i\omega) = m_ir_i^2\omega$$
with the same direction as the [[axis]]. in total then, and including the [[moment of inertia]] definition, we can [[derivation|derive]] for that slice, $$L=\sum{L_i}=(\sum m_ir_i^2)\omega = I\omega$$ and given our choice of axis is [[axis symmetric]] across the body, the definition using $\vec{r}\times m\vec{v}$ is not a problem, because the $z$ component of $\vec{r}$ along the body will cancel out as we move along the slices, therefore:

In vector form, $$\vec{L} = I \vec{\omega} \ \ \ \ \ \ \text{(rigid body rotating about a symmetry axis)}$$ 
We can further extend the reach of this conclusion by pointing out that for arbitrary internal forces ([[rigid body]] or [[soft body]]) this holds, since the internal forces cancel when we apply [[torque#Newton's second law of motion Newton's law for rotational forces for rotational forces applied|Newton's second law for torque]] $$\sum{\tau} = {d \vec{L} \over dt} \ \ \ \ \ \ \ \text{(for any system of particles)}$$
#### ... [[law of conservation of momentum]] for angular momentum
For a [[mechanical system]] without [[externality|external forces]], we have the following:

[[when the net external torque acting on a system is zero, the total angular momentum of the system is constant (conserved)]]

Such relationships are typically going to be written $$I_1\omega_{1z}=I_2\omega_{2z}$$
This is a result of [[Newton's third law of motion]].

Certain behaviors can be conceptualized as [[angular collision]]