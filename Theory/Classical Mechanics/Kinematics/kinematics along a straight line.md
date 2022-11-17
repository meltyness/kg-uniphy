#C2-1 
#KeyConcept 

Choose a [[coordinate system]] for a [[particle]] $B$ and it's [[position]], $x_i$ to travel along a straight-line path.

We choose the $x\text{-axis}$ with origin $O$ positive, along the direction of motion.

### [[formula]]
#### Average velocity
We describe $B$'s motion in terms of the change in $x$ after some passage of [[time#Interval|time interval]].
- We define an [[velocity#Average|average velocity]] $\bar{v}_x = {\Delta x / \Delta t} = (x_2 - x_1 )/(t_2 - t_1)$
- Notice that this implies we must select a specific starting time $t_1$, since not all $\Delta t$ are created equal against the [[phenomena of nature|phenomena]]
- $\bar{v}_x$ is signed with the coordinate system.
- We can construct an $x\text{-}t$ graph, and velocity corresponds to the slope.

#### Instantaneous velocity
Tells us in an [[time#instant|instant]] how much motion was taking place as a [[vector quantity]] -- [[velocity#Instantaneous]] like $v_x = \lim_{\Delta t \rightarrow 0}{\Delta x \over \Delta t} = {dx \over dt}$

#### Average acceleration
We describe $B$'s motion, if we find that $B$ has instantaneous velocity $v_{1x}$ at $t_1$ and $v_{2x}$ at $t_2$ then we can write $\bar{a}_x = {v_{2x}-v_{1x} \over {t_2 - t_1}} = {\Delta v_x \over \Delta t}$

#### Instantaneous acceleration
To [[describe outcomes]] of motion along a [[path]], where we can make [[experiment or measurement|measurement]] of [[velocity]] at near [[time#Instant|instant]] intervals, $a_x = \lim_{\Delta t \rightarrow 0}{\Delta v_x \over \Delta t} = {dv_x \over dt}$

#### ... with Constant Acceleration
An analysis results in the kinematic equations:
- Velocity with time $v_x = v_{0x} + a_xt$
- Position with time $x = x_0 + v_{0x}t + (1/2)a_xt^2$
- Velocity with position $v_x^2 = v_{0x}^2 + 2a_x(x-x_0)$
	- ### [[derivation]]
	- Take velocity with time, $(v=v_0+at)$
	- Write $v^2 = (v_0+at)^2$
	- $=v_0^2+2v_0at+a^2t^2$
	- $=v_0^2+2a(v_0t+{\frac{1}{2}}at^2)$
	- and from position with time, $(x-x_0=v_0t+\frac{1}{2}at^2)$
	- $v_0^2+2a(x-x_0)$.
- Change in position given known velocity: $x-x_0 = ({v_{0x} + v_x \over 2})t$ #WaitWhat

#### [[free fall]]
[[surface gravity]] causes [[kinematics#with Constant Acceleration|motion with constant acceleration]] at around $g=9.8 \ \text{m}/\text{s}^2$

#### ... with Variable Acceleration
Using the [[integral]] and $a_x$ not a constant, things are no longer valid.

We can use $v_x={dx/dt}$ to find $v_x(t)$ and $a_x = dv_x/dt$ are still valid definitions, and we can go from $v_x(t)$ to $a_x(t)$ using this calculus.

Write $\Delta v_x = \bar{a}_x\Delta t$, we can add up using [[integral]] and $$v_{2x}-v_{1x}=\int_{v_{1x}}^{v_{2x}}dv_x = \int_{t_1}^{t_2}a_xdt$$
And more usefully, we have the following terribly helpful [[integral]] relationships:
$$v_x = v_{0x} + \int_0^t{a_xdt}$$$$x=x_0+\int_0^tv_xdt$$

### Related [[physical quantities]]
- [[position]]
- [[displacement]]
- [[velocity]]
- [[acceleration]]