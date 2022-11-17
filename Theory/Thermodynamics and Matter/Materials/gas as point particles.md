#C18-3 

A [[derivation]] of the [[formula]] for [[molecular speeds]]

#### Assumptions
- A [[container]] with [[volume]] $V$ 
	- [[contain|contains]] a [[statistical mechanics|very large number]] $N$ of identical [[molecule]], 
		- each with [[mass]] $m$
		- Behave like [[particle]] such that
			- Their [[molecular geometry]] is small [[relative]] to $V$
			- They don't [[elastic collision|interact meaningfully]] with one another
		- Are in constant [[molecular motion]]
		- Obey [[Newton's laws of motion]]
		- Undergo [[elastic collision|perfectly elastic collision]] with the container.
			- [[molecular collision]] in reality deviates from this
		- [[assume the maximum possible|As]] $t\rightarrow\infty$ then $N/V$ [[concentration]] is a constant everywhere
	- The [[container]] has $M_\text{container} >> m$, and remains [[at rest]].

#### The [[models|model]]
The [[collision]] of each [[molecule]] exerts a [[action-reaction pair]], and a resulting [[pressure]] due to the presence of the [[material system]].

- All molecules have [[molecular speeds]] $|v_x|$ 
- With a collision [[momentum]] changes, $\Delta p = 2m|v_x|$
- A molecule will collide with the wall if it is [[length]] $L^*=|v_x|dt$ from the wall.
- Taking a cylindrical [[test volume]] with $A, L^*$
- Since we have $N/V \propto {\text{molecules} / \text{m}^3}$ and a $V^* = A|v_x|dt$ with half the molecules headed towards, and the other half headed away, $$E[n_\text{collisions}] = \frac{1}{2}\frac{N}{V} A|v_x|dt$$- And so by [[Newton's second law of motion]], (and dropping the abs, since it is assumed that these particles made a positive contribution) $$\sum F_x=ma_x={dP_x \over dt} = {E[n_\text{collisions}]\over dt}(\Delta p) = {NAmv_x^2\over V}$$
- and therefore $$p={F \over A}={Nmv_x^2 \over V}$$
#### Refining $v_x$
- We take the previous argument for all [[molecule]] with identical $v_x$, and use [[superposition of forces]] we can rewrite $E[v_x^2]$ 
- With $v^2=v_x^2+v_y^2+v_z^2$ $$E[v^2] = E[v_x^2]+E[v_y^2]+E[v_z^2]$$
-  Again [[abstract negligible facets]] for [[gravitational interaction]] we'll have each component equal, $$E[v^2] = 3E[v_x^2]$$
- Following through $$p = {F \over A} = {NmE[v^2] \over 3V} \implies pV=\frac{2}{3}N\bigg[\frac{1}{2}mE[v^2]\bigg]=\frac{2}{3}K_\text{tr}$$
- Which gives the [[kinetic energy]] of a single [[molecule]]
- Back-substituting into the [[ideal gas law]] gives $$K_\text{tr} = \frac{3}{2}nRT$$
- Taking $${K_\text{tr} \over N} = \frac{1}{2}mE[v^2]={3nRT \over 2N}$$
- Relating to [[Avogadro's constant]], $$N = nN_A \implies {n \over N} = {1 \over N_A}$$
- Gives that the average [[kinetic energy]] $$E[K]=\frac{1}{2}mE[v^2] = \frac{3}{2}\bigg({R \over N_A}\bigg)T=\frac{3}{2}kT$$
- And so [[Boltzmann constant]]
- Therefore [[the translational kinetic energy per molecule in an ideal gas depends only on temperature]]