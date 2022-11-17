#C28-1

A [[net charge]] in motion with [[velocity]], $v$ produces a [[magnetic field]] with $$\vec{B}={\mu_0 \over 4\pi}{q\vec{v}\times\hat{r}\over r^2}$$
#Caution $\hat{r}$ points from the source to the field point.

$\mu_0$ is the [[permeability of free space]]. Additionally [[superposition of fields]] applies, which leads to the following relationship, following from 

#### ... [[differential equation, or principle]]
- definition of [[electrical drift velocity]], [[current density]], [[electrical current]]
- $dQ = nqA \ dl$ (the charge in a segment with a given concentration, carrier, and cross-area)
$$dB ={\mu_0 \over 4\pi}{|dQ|v_d\sin\phi \over r^2}={\mu_0\over 4\pi}{{n|q|v_dA\sin\phi \ dl} \over r^2}$$
- With $J=n|q|vd=I/A$,
$$d\vec{B} = {\mu_0 \over 4\pi}{Id\vec{l}\times \hat{r}\over r^2}$$

#### ... [[table]] of common [[assume common, reasonable system geometry|geometries]]
|Scenario|Point in Electric field|Magnetic Field magnitude ([[scalar quantity]])|
|-|-|-|
|Long, straight conductor|Distance $r$ from conductor|$$B={\mu_0I\over2\pi r}$$|
|Circular loop of radius $a$|On axis of loop|$$B={\mu_0Ia^2 \over 2(x^2+a^2)^{3/2}}$$
||At center of loop|$$B={\mu_0I \over 2a}$$|
|Long cylindrical conductor of radius $R$|Inside conductor $r<R$|$$B={\mu_0I \over 2\pi}{r \over R^2}$$|
||Outside conductor $r>R$|$$B={\mu_0I \over 2\pi r}$$|
|Long closely wound [[solenoid, and current loops]], with $n$ turns per unit length, near its midpoint|Inside solenoid, near center|$$B=\mu_0 nI$$|
||Outside solenoid|$$B\approx 0$$|
|Tightly wound toroidal solenoid with $N$ turns|Within the space enclosed by the windings $r$ from the [[axis]]|$$B={\mu_0NI\over2\pi r}$$|
||Outside the space enclosed by the windings|$$B\approx 0$$|
