#C13-1 

A body undergoing this type of motion is called a [[harmonic oscillator]].

[[simple harmonic motion is the projection of uniform circular motion onto a diameter]] this is a clever application of [[shadow puppetry]]

Simple harmonic motion occurs when the [[dynamics]] of the system are such that the [[frequency]] and [[amplitude]] are [[coordinate independence|independent]]. #WaitWhat is this more general than the book's definition 👀

#### Discussion
With $F=-kx$ we have the following [[differential equations]]: $$a_x = {d^2x \over dt^2} = {-k \over m}x$$
Gives $\omega = \sqrt{k \over m}$  as its [[angular frequency]].

A vector with [[kinematics of circular motion#Uniform Circular Motion|constant]] [[angular velocity|rotating speed]] is called a [[phasor]]. 
We'll also have an interesting relationship with [[angular velocity]] 

( #Caution not to be confused with [[frequency]]) 

that $a = \omega^2 A$ where $A$ is the [[amplitude]] (from $v=\omega A$ based on [[kinematics of rotational motion of rigid bodies#formula|definition of rolling]] and $a = v^2 / A$, see also, [[rolling]])

This boils down to the following [[kinematics|kinematic]] equation: $$x=A\cos(\omega t + \phi)$$
Where $\phi$ is called the [[phase angle]], we can solve for it by knowing $x_0$, setting $t=0$ so that $\phi = \cos^{-1}{x_0 \over A}$.

We can also find $v_x, a_x$ by taking derivatives, etc. 

We'll also have that, given $v_0, x_0$ we can find $\phi, A$ $$\phi = \tan^{-1}({-v_{0x} \over \omega x_0})$$ $$A = \sqrt{x_0^2 + {v_{0x}^2 \over \omega^2}}$$
#### [[energy]]
Simply the maximum [[spring potential energy|potential]], $$E = \frac{1}{2}kA^2$$
#### Vertical
Choose $x=0$ to be $\Delta l$ the displacement of the spring at [[equilibrium]], so that we can then write, around that point simply, $$\sum F_\text{net} = -kx$$
#### Angularly
A [[mechanical watch]] has a balance wheel with [[moment of inertia]] $I$ about its [[axis]], and a [[spring]] exerts $\tau_z$ proportional to $\theta$ ...  $$\tau_z = -\kappa\theta$$ $\kappa$ is called the [[torsion constant]].

And applying [[Newton's law for rotational forces]], we find a [[differential equations]] for $\theta(t)$: $$I{d^2 \theta \over dt^2}=-\kappa \theta$$
Similarly we arrive at $$\theta = \Theta\cos (\omega t + \phi)$$
#### [[atom]] vibrations, in [[material]]
A pair of [[atom]] form a [[molecule]], and they can be at [[equilibrium]] a certain number of [[angstroms]] for eachother, due to the [[van der Waals interaction]]. We have the following [[derivation]] from the [[The Lennard-Jones Potential]].

With equilibrium $r=R_0$ we describe $$U=U_0[({R_0 \over r})^{12}-2({R_0 \over r})^6]$$
and so $$F_r = {-dU \over dr} = U_0[{12R_0^{12} \over r^13}-2{6R_0^6\over r^7}]={12U_0\over R_0}[({R_0\over r})^{13}-({R_0\over r})^7]$$
which we can approximate to be 
$$F_r \approx -({72U_0 \over R_0^2})x$$
when $r$ near $R_0$.

#### Applications
The fact that [[angular frequency]] varies with incident [[mass]] with $\omega = \sqrt{k / m}$ leads to the following [[machine]] operating principles:
- A [[tuning fork]] 
- [[Body Mass Measurement Device]]
