#C14-1 

A type of material, typically [[solid]] at room temperature. Capable of [[metallic bonding]], and [[plating]].


#### ... [[free-electron model of conduction]]
#C42-5 
- Assume a box with length $L$ contains [[electric charge freedom|free electrons]], that cannot [[escape]] the box. Then similar to [[Schrödinger equation#... for a stationary state , infinite potential well]], [[wavefunction]], $$\psi(x,y,z)=A\sin{n_x\pi x\over L}\sin{n_y\pi y\over L}\sin{n_z\pi z\over L}$$
- Where $(n_x,n_y,n_z)$ are the [[quantum number]] defining the [[quantum states]].
- It also follows from [[Schrödinger equation#... in space]], with $U=0$ that, $$-{\hbar^2 \over 2m}({\nabla\cdot\psi})+U(\vec{r})\psi(\vec{r})=E\psi(\vec{r}) \ \ \ \ \ \ \ \ \ \ \text{and} \ \ \ \ \ \ \ \ \ \ E={(n_x^2+n_y^2+n_z^2)\pi^2 \hbar^2\over2mL^2}$$
- To [[compute a density from a presumed set of boundaries|find]] the [[electronic state density]], $g(E)$ consider a space with $$n_\text{rs}=n_x^2+n_y^2+n_z^2$$
- Each integer point is a [[quantum states]], with $m_s=\pm\frac{1}{2}$ and so we have a volume $\frac{1}{8}(\frac{4}{3}\pi n_\text{rs}^3)$ which totals up to $$n={\pi n_\text{rs}^3 \over 3} \ \ \ \ \ \ \ \ \ \ \ \ \ \text{and energy} \ \ \ \ \ \ \ \ \ E={n_\text{rs}^2\pi^2 \hbar^2\over2mL^2}$$
- Which can be solved taking $V=L^3$ $$n={(2m)^{3/2}VE^{3/2} \over 3\pi^2\hbar^3}$$
- and therefore $$g(E)={dn \over dE} = {(2m)^{3/2}VE^{1/2} \over 2\pi^2\hbar^3}$$
- We also stated that this varies with $T$ as with [[Maxwell-Boltzmann Distribution]], but
	- [[Pauli exclusion principle]] prevents complete collapse at $T=0$ 
	- [[Maxwell-Boltzmann Distribution]] depends on [[distinction, and indistinguishability]]
- Instead the [[Fermi-Dirac distribution]] is used $$f(E) = {1 \over e^{(E-E_F)/kT} + 1}$$
- $E_F$ is the [[Enrico Fermi]] [[electron energy level]] a kind of [[expectation value]] where at $E_F$ half the states are filled, and half are empty, when this is independent of the temperature ([[the Fermi level of semiconductors is dependent on temperature, but the Fermi level of metals is not]])
- We can find, using this [[complementary cumulative distribution function]] that the electrons in range $dE$ are given $$dN=g(E)f(E)dE$$
- Choosing a max at $E_{F0}$ corresponding to [[absolute zero]], and integrating, $$N={(2m)^{3/2}VE_{F0}^{3/2} \over 3\pi^2\hbar^3}$$
- Solving for $E_{F0}$ and replacing $N/V$ with $n$ representing [[concentration]] of [[electrons]], $$E_{F0} = {3^{2/3}\pi^{4/3}\hbar^2n^{2/3} \over 2m}$$
- We can also use the statistics to compute [[how much on average]] [[energy]] per [[electrons]] $E[E]$  $$E[E] = {3 \over 2E_{F0}^{3/2}}\int_0^{E_{F0}}E^{3/2}dE={3 \over 5}E_{F0}$$