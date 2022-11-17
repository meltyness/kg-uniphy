#C5-3 

Given $v$ is [[speed]] $f$ is the magnitude of the resistance, and $D, k$ coefficients.

Fluid resistance [[action-reaction pair|acts]] on a specific [[rigid body|object]] in a medium.

#### Fluid Resistance
$f = kv$ or at high speeds,

#### Air Drag
$f = Dv^2$.

#### [[derivation]] for finding [[terminal speed]]
Given a naive [[models|model]] of a falling object we apply [[Newton's second law of motion]], to find the [[dynamics]] of the situation $$F_y = mg + (-kv_y) = ma_y$$
So that the force and the [[acceleration]] depends on the [[velocity]], with the given relationship.

It's trivial to find the terminal speed utilizing the relationship with $a_y=0$ and rewriting $$mg = kv_t$$ then we have that $v_t = mg/k$.

#### [[formula]] for [[derivation|Finding]] [[kinematics]]
It is more complicated though to find $v(t)$ in general though...

We can rewrite $a_y = {dv_y / dt}$ by definitions given in [[kinematics along a straight line]].
$$m {dv_y \over dt} = mg-kv_y$$
$$m{dv_y \over dt} - mg = -kv_y$$ $${m \over k}{dv_y \over dt}-v_t = -v_y$$
$${m\over k}{dv_y \over dt} = v_t - v_y$$
$$ \int_0^v{dv_y \over ({v_y-v_t})} = {-k \over m}\int_0^tdt$$
$$[\ln(v_y-v_t)-\ln(-v_t)]={-kt \over m}$$
$$\ln{(v_t-v_y) \over v_t} = {-kt\over m}$$
Therefore, $$v_y = v_t[1 - e^{-(k/m)t}]$$
