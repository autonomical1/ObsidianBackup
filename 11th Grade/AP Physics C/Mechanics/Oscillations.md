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
- Frequency: $f = \frac{\omega}{2\pi} \rightarrow f \ \frac{1}{2\pi} \sqrt{\frac{k}{m}}$ 
- Period: $T = \frac{1}{f} \rightarrow T = 2\pi  /sqrt{\frac{m}{k}}$
- $[f] = \text{Hz} = \frac{\text{cycles}}{\text{second}}$

# Conservation of Energy
- Spring force is conservative, so: $E = K+U =$ constant, where $K = \frac{1}{2}mv^{2}$ and $U = \frac{1}{2} kx^{2}$
- $$F_{s} = \frac{-dU_{s}}{dx}$$$$dU_{s} = -F_{s}dx$$$$U_{s}(x) = \int_{0}^{x}dU_{s} = -\int_{0}^{x} F_{s} dx$$$$U_{s}(x) = -\int_{0}^{x} (-kx)dx$$$$U_{s}(x) = k\int_{0}^{x} xdx$$$$U_{s}(x) = k[\frac{x^{2}}{2}]_0}_$$