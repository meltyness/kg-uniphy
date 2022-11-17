#C26-4

By modeling a [[resistor]] and a [[ideal capacitor]] in series with an [[electromotive force, and ideal voltage source|voltage source]], we arrive at the following equations and facets: 

#### ... charging the capacitor
[[formula]] follows from [[complete electrical circuit#Modeling]] as a [[DC circuits]], solving the [[differential equations]]
$$q = C\mathcal{E}(1-e^{-t/RC})=Q_f(1-e^{-t/RC}) $$
$$i = {dq \over dt} = {\mathcal{E} \over R}e^{-t/RC}= I_0e^{-t/RC}$$
#### ... [[time constant]], relaxation time
$$\tau = RC$$
is the time it takes for the circuit to reach $1/e$ of its final value

#### ... discharging the capacitor
$$q = Q_0 e^{-t / RC}$$
$$i = {dq \over dt}= -{Q_0 \over RC}e^{-t/RC}=I_0e^{-t/RC}$$
