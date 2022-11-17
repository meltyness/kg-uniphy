NI#C30-3

In a single [[solenoid, and current loops]], with an [[electrical current]] changing in time $i(t)$, causes a [[magnetic flux]] through itself. Similar to [[mutual inductance]], $$L = {N\Phi_B \over i}$$ and the [[electromotive force, and ideal voltage source|voltage]] then is $$\mathcal{E} = - L{di \over dt}$$
and in this sense they form a [[electrical circuit element]].

Note that every *real* inductor has some [[resistor|resistance]] in its [[solenoid, and current loops|windings]].

#### ... [[human control]] and [[energy]]
Depends on size, shape, [[solenoid, and current loops#with a permanent magnet ferromagnetic material ferromagnetic core|presence of a]] [[permanent magnet, ferromagnetic material]].

With a very large [[relative permeability]], $L$ could increase linearly with $K_\text{m}$, as well as with $M$, though $M$ [[magnetization density]] is not always linear with $B$, and therefore $L$ can be a complicated function of $i$.

Starting from ${dW \over dt}=P=VI = Li{di \over dt}$ we can derive the following expression for energy
$$U=L\int_0^Iidi = \frac{1}{2}LI^2$$
and as an [[energy density]], which we can [[derivation]] the [[formula]] using a toroidal [[solenoid, and current loops]], which is useful because the $B$ is completely confined to the inside of the device. Noting that $\mu$ is the [[permittivity]] of the core material. 

- For a toroidal solenoid, following from [[Biot-Savart law#table of common assume common reasonable system geometry geometries|Biot-Savart table]] $$\Phi_B = \oint \vec{B}\cdot d\vec{A}=BA=\bigg({\mu N i \over 2\pi r}\bigg)A={\mu NiA \over 2\pi r}$$
- and then following from $L$, $$L={\mu N^2A \over 2\pi r}$$
- and algebraic manipulation, and factoring in the [[volume]] of a torus gives: $$u = {U \over 2\pi rA}=\frac{1}{2}{\mu N^2A \over 2\pi r}I^2{1 \over 2\pi rA}= \frac{1}{2}{\mu^2 \over \mu} {N^2I^2 \over(2\pi r)^2}={B^2 \over 2\mu}$$
- and so energy density is $$u={B^2 \over 2\mu}$$
#### ... as the [[voltage, or electric potential]] drop in a circuit
[[are formal and support the argument based solely on the key principles|To be formal and support the argument based solely on the key principles]] $$\oint\vec{E}_n\cdot d\vec{l} = {-d\Phi_B \over dt} = -L{di \over dt}$$ and because the inductor doesn't concentrate a [[net charge]], $$E_n + E_c = 0$$ and this implies that $$\oint \vec{E}_c \cdot d\vec{l} = L{di \over dt}$$ and that $$V_{ab} = L{di \over dt}$$
#### ... Applications
- [[fluorescent lighting]]
- [[locomotion]] and [[road]]
- [[combustion engine]]