#C31-1

This is commonly used for [[electrical power transmission]] because of the lower [[electrical power dissipation]] associated with $i^2 R$ for high-[[voltage, or electric potential|voltage]] step-up that can be provided by [[electrical transformers]] on a time-varying [[electrical current]].

Key result regarding [[resonance]] ([[fingerprint]]). We use the [[phasor]] to circuits. #WaitWhat 

#### ... in terms of [[phasor]]
An [[alternating source of emf]] is implicit in these types of discussions. We write the [[formula]], $$v = V\cos\omega t \ \ \ \ \ \ \ \ \ \ i=I\cos\omega t$$ for these situations.

 In order to make measurements, [[electrical rectification]] is required.

This also results, [[using statistical techniques to describe oscillatory phenomena|unfortunately]] an [[abuse statistical techniques]], on using [[how much on average]], and [[root-mean square]] to describe the current, $$I_\text{rectified av} = {2 \over \pi}I \ \ \ \ \ \ \ \ \ \ \ I_\text{rms} = {I \over \sqrt{2}} \ \ \ \ \ \ \ \ \ \ \ \ \ \  V_\text{rms}={V \over \sqrt{2}}$$
#### ... over a [[resistor]],
This is a simple linear relationship and does not effect the [[phasor]] of the current and voltage$$V_R = IR\implies v_R = V_R\cos\omega t$$
#### ... over a [[reactance]], and [[occlude or filter|filtering]] [[formula]]
Sources like a [[ideal capacitor]] or [[self inductance, and inductors]] produce a reactance to a voltage following from a [[derivation]] writing down $i_C={dq / dt}$ and integrating or, $v_L = L{di/dt}$ and differentiating with:$$v_L=-I\omega L\sin\omega t \ \ \ \ \ \ \ \ \ \ v_C={I \over \omega C}\sin\omega t$$
and the terms $\omega L, (\omega  C)^{-1}$ are given labels $X_L, X_C$ respectively. The induction forms a [[low-pass filter]], the capacitance forms a [[high-pass filter]].

#### ... in terms of [[impedance]]
The impedance defines the combined effect of [[resistor|resistance]] and [[reactance]] $$Z=R+jX$$
and are useful for determining the [[steady-state]] condition of the circuits.

[[transients]] are #OutOfScope 

#### ... in terms of [[electrical power dissipation]], [[energy]]
#C31-4
Starting from the [[instantaneous]] power dissipation and find the [[derivation]] of [[formula]] such that, $$p=vi$$
Consider that we then may proceed by computing the [[weighted sum]] over instantaneous values of power through a repeating segment of [[signal]].

Note that this may lead to a natural need for the [[Fourier series]].

#### ... [[harmonic analysis]] of [[resonance]]
This is key in constructing a [[electrical signal filtering]]

#### Applications
- [[electronic devices]].
