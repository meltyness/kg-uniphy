#C16-3

Just like with [[mechanical waves and work, power, energy]], as well as [[wave intensity]] we have the following results for [[sound waves]].

[[intensity is the power delivered by a wave, per unit area|Wave intensity is equal to the time-average rate which energy is transported per unit area across a surface perpendicular to the direction of propagation]]

#### ... measuring the [[sound intensity level]]
This is written in a way to better corroborate scales in [[loudness]].

#### [[derivation]] of [[formula]]
We have the [[amplitude]] $A$ equivalent to the [[pressure|pressure amplitude]] of the [[longitudinal wave]] $p_\text{max}$

Recall from [[power]] that we have $P = \vec{F} \cdot \vec{v}$, so with equations from [[dynamics of a sound wave]]
$$v_y(x,t)={\partial y \over \partial x}=\omega A \sin(kx-\omega t)$$
$$p(x,t)v_y(x,t)=[BkA\sin(kx-\omega t)][\omega A\sin(kx-\omega t)$$$$=B\omega kA^2\sin^2(kx-\omega t)$$
#### ... for [[wave intensity]]
For a [[sinusoidal waves]] with $\omega = 2\pi f$ and  $T=1 / f = 2\pi / \omega$
$$I = {1\over T}\int P(t)dt = {B\omega^2kA^2 \over 2\pi}\int_0^{2\pi/\omega}\sin^2(kx-\omega t)dt={B\omega^2kA^2 \over 2\pi}[{\pi \over \omega}]$$$$={B\omega kA^2 \over 2}$$
And with $\omega=vk$ and $v^2=B/\rho$ we can write $$I=\frac{1}{2}\sqrt{\rho B}\omega^2 A^2={p_\text{max}^2 \over 2\sqrt{\rho B}}$$
