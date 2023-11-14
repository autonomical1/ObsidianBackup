# Oscillatory Motion
- Period and frequency are determined by the restoring force and inertia
- If the restoring force is linear as a function of position, we get **simple harmonic motion** (SHM)
- Ex: Mass on a spring (Hooke's Law): 
	- ![[Pasted image 20231114105417.png]]
	- Spring force is $F_{s} = -k x$, where $k$ is the spring constant
- Newton's Second Law: 
	- $$\sum\limits F_{x} = ma_{x} = F_{s}$$where $F_{s} = -kx$ is the spring force and $a_{x} = \frac{d^{2}x}{dt^{2}}$
	  substituting, $$$m \frac{d^{2}x}{dt^{2}} = -kx$$ $$\frac{d^{2}x}{dt^{2}} = \frac{-k}{m}x$$
	  Solutions: $$x(t) = A\cos(\omega t) + B\sin(\omega t)$$where $\omega = \sqrt{\frac{k}{m}}$ is the angular frequency.
	- Physics solution:
		- Assume $\cos(x)$ with an initial condition (phase angle $\phi_{0}$)
		- $x(t) = A\cos(\omega t + \phi_{0})$
		- 