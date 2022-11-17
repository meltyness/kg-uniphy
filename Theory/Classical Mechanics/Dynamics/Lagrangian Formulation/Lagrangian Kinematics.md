#Custom-1 

In the [[Lagrangian]], $q$ are called [[generalized coordinates]], [[the generalized coordinates of a mechanical system are the minimum group of parameters which can completely and unambiguously define the configuration of the system]]. 

They are called generalized because, in contrast to [[Newtonian mechanics]] they 
- do not need to be in the cartesian [[coordinate system]]
- nor do they need to be within an [[inertial frame of reference]].

They express:
- [[kinetic energy]]
- [[potential energy]]

of the system, which themselves must be measured in an [[inertial frame of reference|inertial frame]], and therefore the generalized coordinates must be able to express [[velocity]] and [[displacement]] of [[rigid body]] [[relative]] to an [[inertial frame of reference]]. #WaitWhat 

This leads to different [[enumerate all apparently permissible configurations|classes]] of systems
- [[Holonomic systems]] the number of independent generalized coordinates required equals the number of [[degrees of freedom]].
- [[Nonholonomic systems]] exist and are studied in [[Fundamentals of Applied Dynamics (Williams)]], for example a [[trackball]]

[[degrees of freedom]] refers to the number of coordinates which can be **independently** varied. $N$ rigid bodies in [[space]], for example have $3N$ such degrees, two translational and one rotational. And if we add $k$ [[constraints]], then $d=3N-k$.

And so the coordinates must satisfy:
- [[coordinate completness]] Capable of locating all parts of the system at all times
- [[coordinate independence]] If all but one coordinates are fixed, then the remaining coordinate still may take on a continuous range of values #WaitWhat 

So procedurally
- Identify the [[degrees of freedom]] $d$
- Choose $d$ generalized coordinates which are complete, and independent.

So for $j$-dof system, with coordinates, $q_j$.

$$L=K-U=L(q_1,\dots,q_j,\dots,q_d,\dots,\dot{q_1},\dots,\dot{q_j},\dots,\dot{q_d})$$