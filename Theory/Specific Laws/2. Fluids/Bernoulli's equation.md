#C14-5

Bernoulli's equation is derived from the [[continuity equation]].

#### [[derivation]]
For an 
- [[tensile-compressive stress|incompressible]] fluid ($dV_1/dt = dV_2/dt$)
- under [[steady flow]]
- zero [[viscosity]]

We can derive a [[work]] relationship by applying the [[work-energy theorem]] $dW = K_1 - K_2$, call each chunk of this a [[parcel]]

$$ds_1 = v_1dt \implies dV =A_1ds_1=A_2ds_2$$
We have [[pressure]] $p_1, p_2$ at either end, and based on the definition we have forces like $F_1 = p_1A_1$ so through the referenced interval, $$dW = p_1A_1ds_1 - p_2A_2ds_2 = (p_1-p_2)dV$$ and the [[kinetic energy]] can be found by writing it for each element $$dK = K_2-K_1 = \frac{1}{2}\rho dV(v_2^2) - \frac{1}{2}\rho dV(v_1^2) = \frac{1}{2}\rho(v_2^2-v_1^2)\  dV$$
and the [[gravitational potential energy]] $$dU = \rho g (y_2-y_1) \ dV$$
so combining these using the [[work-energy theorem]], $dW = dK+dU$. $$p_1+\rho gy_1 + \frac{1}{2}\rho v_1^2 = p_2+\rho gy_2+\frac{1}{2}\rho v_2^2$$
#### Applications
- [[venturi meter]]
- [[airfoil]]
- [[fan]]
- [[turbine]]
- [[centrifuge]]
- [[fluid siphon]]