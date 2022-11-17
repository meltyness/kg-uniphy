#Custom-1 

See [[Lagrangian Kinematics]]

#### [[formula]]
- $\mathbb{S}$ the "action" which is also called the [[action functional]]
- $[t_1,t_2]$ the "duration"
- $\vec{q}$ the "configuration" #WaitWhat does this include energy, force, position? and $\vec{\dot{q}}$ its time [[derivative]].
- $L$ the "[[Lagrangian]]"

We have the following relations,
$$\mathbb{S}[\vec{q}, t_1,t_2] = \int_{t_1}^{t_2}L(\vec{q}(t),\vec{\dot{q}}(t),t)dt$$ and that $$\partial S = 0$$
... or differentially, with $Q_j$ the [[externality|external]] [[generalized force]] where we must identify the forces relative to the [[generalized coordinates]] chosen -- a #Caution complicated process.

$${d\over dt}[{\partial L \over \partial \dot{q}_j}] - {\partial L \over {\partial q_j}} = Q_j$$

and subbing in [[Lagrangian]]
$${d\over dt}{[{\partial(K - U) \over \partial \dot{q}_j}]}-{{\partial(K - U) \over \partial q_j}}$$
simple distribution,	$$={d\over dt}{[{\partial(K) \over \partial \dot{q}_j}]}-{d\over dt}{[{\partial(U) \over \partial \dot{q}_j}]}-{{\partial(K) \over \partial q_j}}+{{\partial(U) \over \partial q_j}}=Q_j$$
With ${d\over dt}({\partial (U) \over \partial \dot{q}_j})=0$ when effects like [[fluid resistance]] are not present, or excluded. #Caution [[electromagnetic interaction]] shouldn't exclude this term, additionally, ${-\partial(K) \over \partial q_j}$ is often zero (since, for example [[generalized force|we'll have omitted potential forces in this formulation]]), therefore.
$$\partial K + \partial U = \partial W_\text{ext}$$
	