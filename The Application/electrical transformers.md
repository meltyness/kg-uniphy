#C31-6

A type of [[electrical circuit element]] that uses [[mutual inductance]] to produce a high [[voltage, or electric potential]], usually for the purpose of [[electrical power transmission]].

This process reduces $i^2R$ losses in power lines by using a very high voltge and very low [[electrical current]] when the [[resistor]] comprising of the power lines can't be changed because of its [[displacement|distance]] from the destination.


#### ...[[derivation]] of [[formula]]
A primary and secondary [[solenoid, and current loops]] form two [[complete electrical circuit]]. 

The primary is connected to an [[alternating source of emf]], and the secondary is coupled by [[Faraday's law of induction]], typically through a [[permanent magnet, ferromagnetic material|ferromagnetic core]] which [[solenoid, and current loops|implies an increase in the]] [[magnetic flux]] with [[Ampere's law]], and therefore an increase in the [[mutual inductance]] with 

With typical assumptions ([[approximating specific complications|negligible]] winding resistance, identical $\Phi_B$ in both coils), we have that the [[electrical terminals]] [[voltage, or electric potential|voltage]] across the primary and secondary in a transformer typically have $${V_2 \over V_1} = {N_2 \over N_1}$$
And so the windings ratio determines whether the transformer is step-up, or step-down.

Following from [[law of conservation of energy]], $$I_1V_1=I_2V_2$$ and we can find that if there's a load $R$, on the secondary $${V_1 \over I_1} = {R \over (N_2/N_1)^2}$$
There are losses due to
- [[magnetic hysteresis]]
- coil [[electrical conductivity, and resistivity|resistivity]]
- core [[eddy current]]
	- mitigated by breaking the core into a [[cascade]] of [[membrane|laminated]] segments made of a [[dielectric, and dielectric strength|dielectric]].
	- #WaitWhat  is there a *most small* where we can make this effect dissapear, similar to how [Knudsen effect in aerogels](https://en.wikipedia.org/wiki/Knudsen_number)
	- This is the cause of the hum and [[sound waves and work, power, energy]] loss.

However [[efficiency]] is often $>90\%$.  