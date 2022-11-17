3#C37-5

Due to [[Einstein's special theory of relativity]] we must revisit [[kinematics in space]], and [[relative velocity]] to extend their [[range of validity]] for [[inertial frame of reference]] near the [[speed of light]].

[[arise by contrasting the predicted result from the actual result|Contrasting]] with [[relative velocity]] as discussed previously which provides a mapping $$\text{Galilean transformation}=\begin{array}{cc}
  \Bigg \lbrace & 
    \begin{array}{cc}
      \vec{f}(x,y,z)\mapsto(x',y',z')\\
      t=t'
    \end{array}
\end{array}
$$
#### ... [[formula]], and [[derivation]] for [[velocity]]
 - With the Lorentz coordinate transformation identified below, as well as basic rules of differentiation, [which follows from laws of differentiation](obsidian://open?vault=Calculus%20Review&file=Function%20Calculus%2FObjects%2Fdifferentials) write down $$dx' = \gamma(dx-udt) \ \ \ \ \ \ \ \text{and} \ \ \ \ \ \ \ dt'=\gamma(dt-u{dx \over c^2})$$
 - Computing $v_x'$, $$v_x' = {dx' \over dt'}\bigg({{1 \over dt} \over {1 \over dt}}\bigg) = {{dx \over dt}-u \over 1-{u \over c^2}{dx \over dt}}={v_x-u \over 1-{uv_x/c^2}}$$
 - Which also holds for $v_x'=c$ in light of [[Einstein's second postulate of special relativity]],
	 - as well as for the case in $S\implies u \mapsto -u$ and [[Einstein's first postulate of special relativity]].

#### ... [[formula]], and [[derivation]] for [[spacetime]] [[coordinate system|coordinates]]
Following from [[whether or not two events at different locations are simultaneous depends on the state of motion of the observer]] it is reasonable to ask the following:

An [[observable]] [[state change]] occurs at $(x,y,z,t)$ in $S$, where does it occur in $S'$?

- Start with $S$, $S'$, and $S'$ moving away from $S$ at $u$
- Taking that [[origin]] $O, O'$ are [[coincident]] at [[time]] $t=t'=0$
- In $S$ the [[displacement]] between $O, O'$ at $t$ is $ut$
- $x'$ is a [[proper]] [[length]] in $S'$ and so subject to [[length contraction]], $\gamma$ measured in $S$, which implies the following [[coordinate system]] transformation: $$x=ut+{x' \over \gamma} \implies{x' = \gamma{(x-ut)}}$$
- #Caution this must be [[reversibility|reversible]] with $x' \text{ like } (-uv)$  following from [[Einstein's first postulate of special relativity]].
- Writing this expression for $u'$ in $S'$, $$x'=-ut'+{x \over \gamma}$$
- we can now solve for $t'$, and in total we have $$\begin{array}{cc}
  \text{Lorentz coordinate transformation} \implies\Bigg \lbrace & 
    \begin{array}{cc}
      x' = \gamma(x-ut) \\
      y' = y \\
      z' = z \\
      t' = \gamma(t-ux/c^2)
    \end{array}
\end{array}
$$
From this we argue that [[space and time have become intertwined, we can no longer say that length and time have absolute meanings independent of the frame of reference]]... and introduce a [[spacetime]]