#C39-3
Characterizes a sort of [[speed limit]] on [[experiment or measurement]].

The assertion that any [[measurement device]] fundamentally must [[fundamental forces|interact]] with the [[material]] to be [[observable]], and in doing so produces this limit on any [[precision, accuracy, uncertainty, and significant figures]].



#### [[formula]]
In the most common formulation we -- rather than using $\Delta p, \Delta x$ as parties to a [[differential equation, or principle]], they represent the [[Normal distribution|standard deviation]], as a simplifying kind of [[what is the shape of the probability density|hypothesis about probability density]]. $$\Delta x\Delta p_x \ge \hbar$$ Where $\hbar = h/2\pi$ in terms of the [[Planck constant]].

Following from #WaitWhat [[we can replace any force with the vector sum of its components]] $$\begin{array}{cc}
  \Bigg \lbrace & 
    \begin{array}{cc}
      \Delta x\Delta p_x \ge \hbar \\
      \Delta y\Delta p_y \ge \hbar \\
      \Delta z\Delta p_z \ge \hbar \\
    \end{array}
\end{array}$$
#Caution this has that $\Delta x, \Delta p_y$ aren't related directly.

The [[Bohr model of the atom]] is a limiting, violating case with $r$ being the principal direction of motion, $\Delta r=0, \Delta p_r = 0$ which implies a [[considering the alternative situation, and deducing a contradiction (pulling it out of thin air)|contradiction]].

And for [[energy]], ( #ProofDeferred, but presumably an instance of [[it won't always be immediately obviously which rate a phenomena effects]] ) $$\Delta E \Delta t \ge \hbar$$ 
#### [[derivation]], [[synthesis]]
- Consider a [[diffraction of light waves]] with $\lambda << a$ for [[electromagnetic waves and light]].
	- Most of the light is simply [[transmitted]] as in [[diffraction of light waves#... phenomenology of a single occlude or filter slit|single slit occlusion]]
- There is an interference minimum that appears at $\theta_1$ off the [[optical axis]], and following from [[diffraction of light waves]] and [[approximating specific complications]], $$\theta_1 = {\lambda \over a}$$
- Now repeat the experiment for [[electrons]] in a [[vacuum]] $< 10^{-7} \text{ atm}$ to prevent [[subatomic particle collisions]]
- There is experimental parity, and we [[describe outcomes|observe]] a [[diffraction of material entities]]
- If we try to [[adjust the interpretation of an experiment]] the following [[disaster]] present:
	- If the electrons are a [[particle]] in the [[Classical Mechanics]] sense, their [[path]] does not depend on their initial [[states]], and we can only describe the final state as a [[probability density]].
	- If we try to describe the interaction in terms of [[momentum]], $\vec{p}=<p_x,p_y>$ and relate it to the minimum, $\theta_1$, with $\tan \theta \approx \theta$, $p_y=p_x\theta_1$ then, $$p_y=p_x{\lambda \over a}$$
	- The [[fringes]] beyond the $m=0$ maximum in the interval $(-\lambda/a,+\lambda/a)$ imply an [[describe outcomes]] where $\Delta p_y \ge p_x{\lambda/a}$
	- And with momentum $p_x=mv_x$ and $\lambda=h/p_x$ from the [[de Broglie wavelength]] and the [[Planck constant]] #WaitWhat does this correspond to choosing the [[Fresnel and Fraunhofer diffraction|Fresnel diffraction]] only?$$\therefore \Delta p_y a \ge h$$
	- We, at this point [[allow violation of common sense]].
	- #ProofDeferred for the general case