- 3 Types of motion:
	- translation
	- rotation
	- oscillation

# Angular Kinematics (Translational Analogs)
|   |   |
|---|---|
|Translation:|Rotation:|
|1. **Displacement** ($\Delta$X)|1. Angular Displacement ($\Delta\theta$)|
|2. Velocity ($v = \frac{dx}{dt}$)|2. Angular Velocity ($\omega = \frac{d\theta}{dt}$)![[Pasted image 20231016105801.png]]|
|3. Acceleration $(a = \frac{dv}{dt})$|3. Angular Acceleration ($\alpha = \frac{d\omega}{dt}$)

# Kinematic Equations:
|   |   |
|---|---|
|$x = x_{0} + v_{0}t + \frac{1}{2}at^{2}$|$\theta = \theta + \omega_{0}t + \frac{1}{2}\alpha t^{2}$|
|$v = v_{0} + at$|$\omega = \omega_{0} + \alpha t$
|$v^{2} = v_{0}^{2}+ 2a\Delta x$|${\omega}^{2} = \omega_{0}^{2} + 2\alpha \Delta\theta$

# Center of Mass
- If an object is unconstrained and no net force is exerted, it will rotate freely about a point known as the center of mass (COM)..
- **COM**: Average location of the mass
- Discrete Objects:
	- ![[Pasted image 20231016110423.png]]
- **COM for extended objects**:
	- ![[Pasted image 20231016110952.png]]
	- COM: $$X_{cm} \approx \frac{1}{m} \sum\limits_{i} x_{i}m_{i}$$$$X_{cm} = \lim_{\Delta m \rightarrow 0} \frac{1}{m}\sum\limits_{i} x_{i}m_{i}$$ therefore: (for uniform objects)
$$X_{cm} = \frac{1}{m} \int_{object} x \cdot dm$$$$y_{cm}= \frac{1}{m} \int_{object} y \cdot dm$$
		however for non-uniform objects: $$x_{cm} = \frac{\int x dm}{\int dm}$$$$y_{cm} = \frac{\int y dm}{\int dm }$$
- Note:
	- Need geometry of object to evaluate $dm$ and the limits of integration
	- If object is non-uniform, $M = \int dm$

# Mass Density (linear)
- $\lambda(x) = \frac{dm}{dx} \rightarrow dm = \lambda(x)dx$
- Uniform: $\frac{dm}{dx} = \frac{M}{L} \rightarrow dm = \frac{M}{L}dx = M$
	- $\int_{object} dm = \int_{0}^{L} \frac{M}{L} dx= M$
- Ex: $$\lambda(x) = \alpha x^{2}$$$$dm = \lambda (x) dx$$$$dm = \alpha x^{2} dx$$$$M = \int_{obj} dm = \int_{0}^{L} \alpha x^{2} dx = \frac{\alpha L^{3}}{3}$$


### Example: Ex 12.2 p. 298
Thin uniform rod of mass M and length L:
![[Pasted image 20231016112837.png]]
### Example: Non-uniform rod of length L and linear mass density $\lambda(x) = \frac{kx^{2}}{L}$ where k is a constant
Then: $$x_{cm} = \frac{\int xdm}{\int dm}$$where $$dm = \lambda(x) dx$$ $$dm = \frac{K}{L}x^{2}dm$$$$\int_{obj}dm = \int_{0}^{L} \frac{K}{L} x^{2}dx$$$$\int dm = \frac{K}{L} \int_{0}^{L} x^{2} dx = \frac{KL^{2}}{3}$$
$$\int_{obj} xdm = \int_{0}^{L} x \cdot \left[\frac{Kx^{2}}{L} dx\right]= \frac{KL^{3}}{4}$$
$$X_{cm}= \frac{\int xdm}{\int dm} = \frac{3}{4}L$$
### Example: P50, p.332
![[Pasted image 20231017110927.png]]

# Rotational Energy
- A rotating object has kinetic energy because all particles in the object are in motion.
- The kinetic energy due to rotation is called the **rotational kinetic energy**.
- Adding up KE and using $v_{i} = r_{i}\omega$
	- $$K_{rot} = \frac{1}{2} m_{1}v_{1}^{2} + \frac{1}{2}m_{2}v_{2}^{2}+ ...$$$$= \frac{1}{2} m_{1}r_{1}^{2}\omega^{2} + \frac{1}{2}m_{2}r_{2}^{2}\omega^{2} + ... = \frac{1}{2}(\sum\limits_{i}m_{i}r_{i}^{2})\omega^{2}$$
	- ![[Pasted image 20231018105643.png|300]]
- Define object's **moment of inertia**: $$ I = m_{1}r_{1}^{2} + m_{2}r_{2}^{2}+m_{3} r_{3}^{2} + ... = \sum\limits_{i} m_{i}r_{i}^{2}$$
- Then rotational kinetic energy is: $$K_{rot} = \frac{1}{2} I\omega^{2}$$
- Units for Moment of inertia: $kg \cdot m^{2}$
- Moment of inertia depends on the axis of rotation
- Moment of inertia sum: $$I = \sum\limits_{i}r_{i}^{2} \Delta m \rightarrow_{\Delta m \rightarrow0} I = \int_{object} r^{2}dm$$
	- much like calculating center of mass


### Example 12.5 p. 302: Find I for a thin rod of length L pivoted from one end at the origin
![[Pasted image 20231018111425.png]]

### I for a hoop: Assume mass M and radius R.
![[Pasted image 20231018111853.png]]


### Example: I for a uniform ring: "onion ring" method
![[Pasted image 20231019105756.png]]

### Example: Problem 55.a., p.332
![[Pasted image 20231019110620.png]]
# Parallel Axis Theorem
- Suppose we know $I_{cm}$ about the center of mass of an object.
- We want to know $I$ through another parallel axis a distance $d$ away.
- General:
	- ![[Pasted image 20231023105706.png]]
	- Statement: $$I = I_{cm} + Md^{2}$$
		- Parallel Axis Theorem
- Proof (1-D):
	- ![[Pasted image 20231023110554.png]]
	- ![[Pasted image 20231023110526.png]]

### Example: Find the moment of inertia for a thin rod pivoted at the end.
![[Pasted image 20231023111243.png]]
### Example: Uniform disk pivoted about its edge
![[Pasted image 20231023111413.png]]

# Torque
- Mathematically: $$\tau = rF \sin \phi$$
	- Units: $N \cdot m$
- Ability of a force to cause rotation: 
	- the magnitude F of the force
	- the distance r is large
	- $\sin \phi > 0$
- In AP1: $\tau = rFsin\phi$
	- dir: CCW +, CW -
- In APC: $\overrightarrow{\tau} = \overrightarrow{r} \text { x}$
### Cross product of two vectors:
- a.k.a Vector Product
- Given two vectors $\overrightarrow{A}$ and $\overrightarrow{B}$
- Define $\overrightarrow{C} = \overrightarrow{A} \text{ x } \overrightarrow{B}$
- ![[Pasted image 20231023112046.png]]
- Notes:
- $\overrightarrow{A} \text { x } \overrightarrow{B} \ne \overrightarrow{B} \text{ x } \overrightarrow{a}$
- Cross product vanishes if: $\phi = 0 \degree \text{ or } 180\degree$ 
- Cross product is mutually 1 to both vectors
- ![[Pasted image 20231023113154.png]]
