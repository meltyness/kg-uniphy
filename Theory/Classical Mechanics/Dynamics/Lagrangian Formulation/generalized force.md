#Custom-1 

Finding generalized [[force]] presents its own complications.

Consider a [[pendulums|pendulum]] length $L$ with 1 [[degrees of freedom]], which we'll choose our [[generalized coordinates]] as $\theta$.

- $q_j = q_1 = \theta$
- $\partial q_1 = \partial \theta$
- $Q_1\partial\theta = F\cdot \partial r = F\cdot {\partial r \over \partial \theta}\partial \theta$
- So through $\partial \theta$ the pendulum deflects $L\partial\theta$ 
- and the [[force|real force]] in the direction of this motion is $L\sin\theta \ \partial\theta$
- So $\partial W_\text{ext} = Q_1\partial\theta = FL\sin\theta\partial\theta$
- ... and so [[formula|we've found]] our [[virtual force]] is $FL\sin\theta$.

$$\partial W_\text{ext}=\sum F_i\cdot\partial r_i(\partial q_1, \partial q_2, \dots) = \sum Q_j\partial q_j$$

Follow these #Guidelines
- constraint forces, like [[tension force]] that perform zero work can be ignored.
- forces with [[potential energy]] are accounted for in $U$, and can be ignored.
- [[dissipative force]] or [[impulse]] should be the focus.


