#C36-1

By [[analogy]], consider an L-shaped [[container]] of [[water]] with a [[mechanical waves]] -- the ripples travel around the corner via diffraction. Following from [[Huygen's principle]], when reaching a finite [[occlude or filter|aperture]], these types of [[thermal contact, material system junction, optical junction or adventure|adventure]] produces behaviors similar to a [[thin film]]

##### ... [[formula]] [[derivation]]
- Consider two strips coming from a slit with width $a$, emitting [[monochromatic]] light with [[wavelength]] $\lambda$.
	- One [[optical ray]] from the top of the slit
	- One [[optical ray]] from the middle of the slit
- Similar to the [[double-slit experiment]], $\text{path difference}=r_2-r_1 = (a/2)\sin\theta$
- Supposing that $\Delta \text{path} = \lambda / 2$, these two strips then cancel.
- So we have a dark fringe whenever $$(a/2)\sin\theta=\pm{\lambda \over 2}$$
- We can [[induct previous results]] for the case where there are four, six, strips and find that there is complete destruction interference at $$\sin\theta = {m\lambda \over a} \ \ \ \ \ \ \ \ \ (m=\pm1, \pm2,\dots \text{ and } m\ne0)$$
- And to predict [[light intensity]],
	- Again break the incident and emitted rays into strips along $a$,
	- Apply [[Huygen's principle]] [[wavelet]] emitted from each of those strips, and consider their contribution at $P$ on the [[screen]] at $\theta$ and a distance $L$ from the [[material surface normal]].
	- Similar to [[double-slit experiment#in terms of light intensity|double slit intensity]], we consider the [[phasor]] of $\vec{E}$ from each [[optical ray]].
	- Then the magnitude of the [[superposition of fields]] is $E_P$.
	- Near $\theta=0$ the phase difference vanishes for $L>>a$ [[approximating specific complications]]
		- This implies $E_P=E_0$
	- Considering contributions [[assume the maximum possible|from a large number]] of strips
		- An angle $\beta$ is formed between the first and the last strip phase
		- The path of phasors forms an arc, also of length $E_0$
		- $E_P$ is then the length of the chord through [[sector]] $\beta$. $$E_P=E_0{\sin(\beta/2) \over \beta /2}$$
		- Taking $\beta = (2\pi / \lambda)a\sin\theta$ 
		- And backsubstituting into the intensity calculation, recalling the result regarding the [[Poynting vector]], $I_0=\frac{1}2{}\epsilon_0cE_0^2$ $$I=I_0\bigg[{\sin(\pi a\sin\theta/\lambda)\over\pi a\sin \theta/\lambda}\bigg]^2$$
	- For two such slits we can extend our analysis as follows:
		- Using the [[interference of light waves|interference pattern]] computed in [[double-slit experiment]] which does not have any [[dampened oscillation|damping factor]] $$I=2\epsilon_0cE^2\cos^2\bigg({d\pi y \over \lambda R}\bigg)$$
		- with $d=4a$, $$\phi = {2\pi d \over \lambda}\sin\theta \ \ \ \ \ \ \ \ \ \ \ \beta = {2 \pi a \over \lambda}\sin\theta$$
		- The total intensity is like $$I=I_0\cos^2{\phi\over2}\bigg({\sin(\beta / 2) \over\beta/2}\bigg)$$
	- And for $N$ slits, #ProofDeferred 
		- The pattern has $N^2I_0$ maxima, called "principal maxima"
		- Each maximum has $N-1$ minima between them, and a width of $1/N$
		- minima occur at $2\pi / N$ which follows from a phasor diagram of the incident waves
		- 

#### ... [[phenomenology]] of a single [[occlude or filter|slit]]
- Wheras [[geometric optics]] would predict a [[sharp]] distinction in a [[shadow puppetry]] type [[experiment or measurement]], this does not actually occur.
- A central bright band is surrounded by alternating bands with decreasing intensity.
	- The width of this band is inversely-proportional to the slit width.
- In Fresnel diffraction, the screen is close to the source
	- we consider a set of [[optical ray]] emerging from the slit,
	- each contacting a single point on the [[screen]], $P$.
- In Fraunhofer diffraction, the screen is far from the source
	- The rays become parallel towards the screen
	- Can be focused via an [[optical lens]] to a point.
		- #ProofDeferred it follows that all beams are given the same [[phase]] [[difference]] by this [[thermal contact, material system junction, optical junction or adventure|adventure]].

#### ... [[phenomenology]] of [[Fresnel and Fraunhofer diffraction]]
- Wheras [[geometric optics]] would predict a [[sharp]] distinction in a [[shadow puppetry]] type [[experiment or measurement]], this does not actually occur.
- What really occurs can be understood 
	- by [[Huygen's principle]] at the small interface of the [[occlude or filter]] barrier, multiple coherent light sources emit light
	- We add up wavelets to find the wave displacement, or phase at a future time and position $$f(\vec{x}, t+1)=\iiiint_{i\in E, j\in R} f_i(\vec{x_j},t)$$
- These undergo [[interference of light waves]] at their final [[optical image]], and realistically this is simply a continuous form of [[interference of light waves]].

An integral formulation gives the following must more sensible results, for $k=2\pi/\lambda$, $\omega=2\pi f = 2\pi{c \over \lambda}$:
$$dE=E_0{dy' \over a}\sin[k(D-y'\sin\theta)-\omega t]$$

#### Applications
- [[CD Player]]
- [[x-ray crystallography]]
- [[holograms]]
- [[emission spectra, absorption spectra and diffraction grating, spectroscopy]]
- [[pinhole camera, and Airy disk]]
- [[geometric optics]] [[resolution]]