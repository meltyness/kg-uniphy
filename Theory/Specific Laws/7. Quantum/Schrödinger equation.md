#C39-1

A [[empirical laws]] regarding [[quantum kinematics]], which is a statement of [[law of conservation of energy]].

#### ... [[formula]]
$$-{\hbar^2 \over 2m}{d^2\psi(x) \over dx^2}+U(x)\psi(x)=E\psi(x)$$

#### ... for describing [[state change]]
- For a general [[subatomic particle]]'s motion, $\Psi(x,y,z,t)$ is a function of [[time]], and at every [[spacetime]] [[event]], there is a time-dependent Schrödinger equation relating the intrinsic and extrinsic [[physical quantities]].

##### ... for a [[stationary state]], infinite [[potential well]]
- For a particle in a box, with $L$, this implies exclusive [[potential well]] with an infinite [[potential barrier]] $$U(x) = 
\begin{array}{cc}
  \Bigg \lbrace & 
    \begin{array}{cc}
	  \infty & x\le 0 \\
	  0 & 0 \leq x \leq L \\
      \infty & x\ge L
    \end{array}
\end{array}
$$ 
- And we can then solve for [[standing wave particle, bound state, stationary state]] modes in [[analogy]] to [[standing mechanical waves]], describing the [[boundary condition]] needed.
- Following the intuition that the [[kinetic energy]] is with $d^2 \psi$, and the [[potential energy]] with $U(x)\psi$, then the total energy is $E\psi$.
- With the fact that under [[principle of superposition of waves]], nodes remain nodes.
- We then write that there are [[mechanical wave node]] that must terminate on $0,L$ so choose that $kL=n\pi$, then $\lambda = {2L / n}$ which then implies a set of $n$ [[normal modes of a mechanical wave]], and [[momentum]] from [[de Broglie wavelength]], $$p_n={h \over \lambda_n} = {nh \over 2L}$$
- And with each of these (for, say, an [[electrons]] with mass $m_e$, then an associated [[electron energy level]],  [[kinetic energy]] $$E_n={p_n^2 \over 2m_e}={n^2h^2 \over 8m_eL^2}={n^2\pi^2\hbar^2 \over2m_eL^2}$$

#### ... for a finite [[potential barrier|barriers]] forming a [[potential well]]
#C40-2
- Serves as a useful simplified model of [[electrical conductivity, and resistivity]], where [[elementary entities]] cannot move without appearing with sufficient energy to overcome a barrier.
- This define [[electric charge freedom]] for $E>U_0$ 
- Where $U=0$ (inside the well) the equation becomes, $${d^2\psi \over dx}=-{2m \over \hbar}E\psi(x)$$
- and hence $$\psi(x)=A\cos{{\sqrt{2 m E}} \over \hbar}+B\sin{{\sqrt{2 m E}} \over \hbar}$$
- and where $U=U_0$, $${d^2\psi \over dx}=-{2m \over \hbar}(U_0-E)\psi(x)$$
- And taking $E>U_0$ in this case, write $\kappa = \sqrt{2m(U_0-E)} /\hbar$, has solutions $$\psi(x)=Ce^{\kappa x}+De^{-\kappa x}$$
- Each term of which converges for [[normalization]] on differing sides $x>L, x<0$ 
- Has a finite number of [[standing wave particle, bound state, stationary state|bound states]] where the [[elementary entities]] can be expected to remain inside of the [[potential barrier]].
- $E_\infty$ is the state where $n=1$ in the infinite well. One method of finding a finite well is to write $U = nE_\infty$ as the $\sqrt{n}$-1 of bound states present in the finite well.

#### ... [[quantum tunneling]]
- For a finite [[potential well]], $U(x)$ then quantum tunneling may be observed with a [[probability]] of observing the [[wavefunction]] on the other side.

#### ... [[normalization]]
- A process by which we enforce that $$\int_S|\Psi|^2\ dV=\int_L|\Psi|^2\ dx=1.0$$
#### ... [[quantum harmonic oscillator]]
- An [[analogy]] to the [[simple harmonic motion]] for $$U(x)=\frac{1}{2}k'x^2$$
- Which then presents an equation with $$-{\hbar^2 \over 2m}{d^2\psi \over dx^2}+\frac{1}{2}k'x^2\psi = E\psi$$
- which has solution in the form of a [Hermite function](obsidian://open?vault=Calculus%20Review&file=Hermite%20polynomials), $$\psi(x)=Ce^{-\sqrt{mk'}x^2/2\hbar}={\frac{1}{2}\hbar\sqrt{k' \over m}}e^{-\sqrt{mk'}x^2/2\hbar}$$
- And $$E_n=\bigg(n+\frac{1}{2}\bigg)\hbar\sqrt{k' \over m} = \bigg(n+ \frac{1}{2}\bigg)\hbar\omega$$

#### ... in [[space]]
$$-{\hbar^2 \over 2m}({\nabla\cdot\psi})+U(\vec{r})\psi(\vec{r})=E\psi(\vec{r})$$

#### ... for a [[wave packet]]
- Typically following from [[Heisenberg uncertainty principle]] we have *some* [[information]] regarding the particle's [[position]] and *some* regarding its [[momentum]].
- In light of this, recalling discussions regarding [[beats]] we arrive at the idea of a [[wave packet]] where for some set of [[amplitude]] as a [[function]] of [[wave number]], $A(k)$ $$\psi(x)=A(k)e^{ikx}\ dx$$

#### ... for a [[standing wave particle, bound state, stationary state]] in one dimension
- For an [[electron energy level]] in an [[atom]], for example, we'd have:
- In determining $\psi$ wavefunctions from a given situation this applies, along a single spatial dimension, $$-{\hbar^2 \over 2m}{d^2\psi(x) \over dx^2}+U(x)\psi(x)=E\psi(x)$$

#### ... for a [[electric charge freedom|free particle]] [[traveling wave]] in one dimension
- For an [[electrons]], with $U(x)=0$ (i.e., no observed forces), and $E=p^2/2m$
- From [[de Broglie wavelength]] we can compute $k={p/\hbar}, \omega={E / \hbar}$
- Then, $$\Psi(x,t)=A\cos(kx-\omega t)+B\sin(kx-\omega t)$$
- Recalling that in [[quantum kinematics#... the wavefunction of a stationary state / standing wave particle]] that the $t$ dimension must fall out, we can inflict this form on our general equation via the relationship $B=iA$,
- $$\Psi(x,t)=Ae^{i(kx-\omega t)}$$
- #WaitWhat doesn't this violate the [[Heisenberg uncertainty principle]]? #GotIt no, this allows unlimited uncertainty with $t$, and therefore exact precision with $E$.

[Rev. Mod. Phys. 20, 367 (1948) - Space-Time Approach to Non-Relativistic Quantum Mechanics (aps.org)](https://journals.aps.org/rmp/abstract/10.1103/RevModPhys.20.367)

#### ... [[distinction, and indistinguishability]]
If two [[electrons]] may be discovered at a single [[event]], then they are not distinguishable, and certain results in [[statistical mechanics]] depend on that fact, such as [[Maxwell-Boltzmann Distribution]]. #WaitWhat 

#### Applications
- [[neutron scattering]]
- [[hydrogen]]