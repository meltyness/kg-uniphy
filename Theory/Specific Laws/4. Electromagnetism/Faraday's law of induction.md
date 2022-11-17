#C29-1 

It is observed that while the [[magnetic flux]] through a [[electrical conductivity, and resistivity|conductor]] / [[solenoid, and current loops|solenoid]] varies, that an [[electromotive force, and ideal voltage source|electromotive force]] appears in the conductor, and that it is proportional to the rate of change, and the direction depends on whether it is increasing or decreasing. This [[phenomena of nature]] are always [[electrodynamic interactions]]

There [[enumerate all apparently permissible configurations|are several different ways]] that this can be integrated into [[models]]

#### ... discussion and [[formula]] / time-varying field
Recalling that the flux is given $$\Phi_B = \oint \vec{B}\cdot d\vec{A}$$
[[the induced emf in a closed loop equals the negative of the time rate of change of the magnetic flux through the loop]] [[hold on is this green's theorem whats going on here]]

$$\mathcal{E}={-d\Phi_B \over dt}$$
The direction can be determined with the [[right-hand rule]], notice as well that since $\Phi_B$ is susceptible to linear increase via [[superposition of fields]] by its definition, this increases emf linearly, in a [[solenoid, and current loops]]
$$\mathcal{E}=-N{d\Phi_B \over dt}$$

#### ... moving conductors / [[electromagnetic induction#as motional electromotive force and ideal voltage source emf|motional emf]]
This can also be stated in terms of motional emf, $$\mathcal{E}=\oint(\vec{v}\times\vec{B})\cdot d\vec{l}$$ which provides a good tool for predicting the direction of an [[eddy current]]

#### ... and the production of an [[electric field]]
While motional emf follows from [[Ørsted-Laplace-Thomson law]], but we also need to explain this the case where the [[magnetic field]] isn't present *at* the actual conductor.

Taking a conductor around a [[solenoid, and current loops|solenoid]] and finding the flux through it ($B=0$ outside, $B=\mu_0NIA$ inside.) gives (following from [[Biot-Savart law]] or [[Ampere's law]]) $$\Phi_B= \oint \vec{B}\cdot d\vec{A}=BA=\mu_0NIA$$and then applying Faraday's law by differentiating, $$\mathcal{E}={-d\Phi_B \over dt}=-\mu_0N{dI\over dt}A$$ so because $B=0$ where our [[ammeter]] is, the $B$ [[considering the alternative situation, and deducing a contradiction (pulling it out of thin air)|field cannot be causing]] $\mathcal{E}$ to appear, so we conclude that an electric field is being induced inside, further more this $E$ field is **not conservative**, it is an [[electrodynamic interactions]] and requires special treatment, in the simple case discussed here $E$ curls around the conductor, and a field with curl can not be conservative. $$\oint \vec{E}\cdot d\vec{l} = {-d \Phi_B \over dt}$$ and in the simple case $$E={1 \over 2\pi r} \bigg|{d\Phi_B \over dt}\bigg|$$
