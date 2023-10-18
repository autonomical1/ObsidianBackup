## Uniform Motion
- zero acceleration, velocity is constant
- Motion diagram is constant
- Position vs. time graph is constant

## Non-uniform motion
- not constant acceleration, velocity is not constant
- motion diagram shows changing distance between points


- to find instantaneous velocity at a certain time, find the result of a derivative of the function of distance/time
	- $$v(t) = \lim_{\Delta t \to 0} = \frac{dx}{dt}$$
	- $$v(t) = \frac{dx}{dt}$$


## Non-Uniform Forces: (velocity-dependent)
- $\overrightarrow{a} \neq constant$ 
- "Jerk" = $\frac{da}{dt} = \frac{d^{3}x}{dt^{3}}$
- Newton's second law in AP1 - $\sum\limits F = ma$
	- becomes: $\sum\limits F = m \frac{dv_{x}}{dt}$


### Newton's Law Example (Drag Forces)
- Falling object: 
	- ![[Pasted image 20230827150734.png|300]]
	- $mg$ down, $F_{d}$ up, where $F_{d} = kv$
		- $$\sum\limits F_{y} = m \frac{dv}{dt} = mg - kv$$
		- to solve: $$\frac{mdv}{mg-kv} = dt$$then: $$\frac{dv}{mg-kv} = \frac{dt}{m}$$then, integrate:$$\int_{v_{0}}^{v} \frac{dv}{mg -kv} = \int_{t_{0}=0}^{t} \frac{dt}{m}$$then to solve: $$\frac{-ln(mg-kv)}{k} |_{v_{0}}^{v} = \frac{1}{m}(t)|_{0}^{t}$$$$ln(mg-kv) |_{v_{0}}^{v} = \frac{-k}{m}t |_{0}^{t}$$

## Projectile Motion (2-D Motion)
- Modeled as two 1-D motions:
	- Horizontal (constant $V_{x} = V_{0x}$)
	- Vertical (constant $a_{y} = -g$)
- Setup:

## Symmetrical Motion only (start/stop at same height)
- Range: $$R = \frac{v_{0}^{2}\sin{(2\theta)}}{g}$$
- Max Height: $$h = \frac{v_{0}^{2}\sin^{2}(\theta)}{2g}$$
## Non-symmetric motion
- 2 approaches:
	- divide into symmetric and non-symmetric motion
	- divide into up and down motion


## Uniform Circular Motion
- Uniform: $|\overrightarrow{v}| =$ constant
	- direction of $\overrightarrow{v}$ changes
	- Centripetal $\overrightarrow{a_{c}}$: $$a_{c} = \frac{v^{2}}{r}$$
		- $\overrightarrow{a_{c}}$ radial inwards
	- angular position is $\theta$
- One revolution: $t = \frac{d}{s}$
	- so $$T = \frac{2\pi r}{v}$$
	- where $v = r \cdot w$ $$T = \frac{2\pi}{\omega}$$
		- $T = \frac{2\pi}{\omega}$ and $\omega = \frac{2\pi}{T}$
	- and $\omega = \frac{d\theta}{dt}$ is angular speed --> $[\omega] = \frac{rad}{s}$

## Non-uniform circular motion: speeding up/slowing down
- $v$ changes, $a_{c} = \frac{v^{2}}{r}$ changes
- acceleration: $$a = \sqrt{a_{t}^{2} + a_{c}^{2}}$$
- Angular acceleration: $$\alpha = \frac{a_{t}}{r}$$
	- where $[\alpha] = \frac{rad}{s^{2}}$



## Drag Force Example
$$\sum\limits F = ma_{x}= \frac{md_{v}}{dt}$$
$$m \frac{dv_{x}}{dt} = -kv$$ $$m(dv_{x}) = -kv \cdot dt$$$$dv_{x} = \frac{-k}{m} v \cdot dt$$$$\int_{v_{0}}^{v} \frac{dv_{x}}{v} = \frac{-k}{m}\int_{0}^{t}dt$$$$ln (v)|_{v_{0}}^{v}= - \frac{k}{m} (t|_{0}^{t})$$
$$e^{ln(\frac{v}{v_{0}})}=e^{\frac{-kt}{m}}$$
$$\frac{v}{v_{0}} = e^{\frac{-kt}{m}}$$
$$v(t) = e^{\frac{-kt}{m}} \cdot v_{0}$$



