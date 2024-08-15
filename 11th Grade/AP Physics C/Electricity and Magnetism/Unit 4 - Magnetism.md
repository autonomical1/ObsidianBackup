- Magnets - 2 types:
	- 1. Permanent Magnets
	- 2. Electromagnets
- Always have 2 poles (North and South)
- Like poles repel ($N-N$ or $S-S$)
- Opposites attract ($N - S$ or $S-N$)
- **Magnetic monopoles do not exist**
- $\vec{E}$ fields are associated with charges (moving/stationary) and $\vec{B}$ fields are associated with $moving$ charges only ($I$)
## Magnetic Force
- $\vec{E}$ and $\vec{F_{E}}$ are parallel or anti-parallel ($F_{e} = qE$)
- $\vec{B}$ and $\vec{F_{B}}$ are *always* perpendicular to each other.
- Equation: $$F_{B} = q\vec{v}\times\vec{B}$$$$|F_{B}| = qvB\sin\alpha$$
- SI Unit for $\vec{B}$: $$[\vec{B}] = T \text { (Tesla)  where } 1 T = \frac{N}{A*m}$$
- Non-SI Unit: Gauss ($G$)$$1T = 10^{4} \text { } G$$
- Comparison of $F_{E}$ and $F_{B}$
	- $F_{E}$ acts on any charge
	  $F_{B}$ acts on moving charges
	- $F_{E}$ parallel to $\vec{E}$
	  $F_{B}$ perpendicular to $\vec{B}$
	- $F_{E}$ does work on the charge
	  $F_B$ does not do work

- Motion of a charged particle in a uniform magnetic field:
	- ![[Pasted image 20240326110655.png]]
	- Uniform circular motion: 
		- $\vec{v} \perp \vec{B}$ (common): $$F_{B} = qvB = \frac{mv^{2}}{r}$$$$r = \frac{mv}{qB} = \frac{p}{qb}$$
		- Note: $r \propto p, r\propto \frac{1}{B}$
		- Angular Velocity: $$\omega = \frac{v}{r}$$$$\omega = \frac{qB}{m}$$
		- Period$$T = \frac{2\pi}{\omega}$$$$T = \frac{2\pi m}{qB}$$
		- Notes:
			- $\omega$ and $T$ don't depend on $v$ and $r$
			- $\omega$ is known as the cyclotron frequency

### Microscopic model of a conductor:
- Conductor of area A and length L.
	- ![[Pasted image 20240328112746.png]]
- Let n be the # of charge carriers per unit volume.
- Total charge $\Delta Q$ in length $L$ is $$\Delta Q = (nAL)q$$
	- where $(nAL)$ is the number of charge carriers, and $q$ is the charge.
- For an electron, $q = -e$
- Therefore, for an electron: $$\Delta Q = -nALe$$
- Assume the time taken to traverse distance $L$ is $\Delta t$
- Then, drift speed will be: $$v_{d} = \frac{L}{\Delta t} \rightarrow L = v_{d}*\Delta T$$
- Substituting, $$\Delta Q = -nA(v_{d} \Delta t)e$$
- Finally, $$\frac{\Delta Q}{\Delta t} = -nAv_{d} e$$$$I = -nAv_{d} e$$
- Now, the magnetic force on an individual charge carrier is: $$F_{B}=qv_{d}\times b$$
- For $n$ charge carriers per unit volume, there are $nV = nAL$ charge carriers in the conductor.
- So, $$F_{B} = (qv_{d}\times b)(nAL)$$$$F_{B} = nqALv_{d}\times b$$
- Define a vector $\vec{L}$ with magnitude $L$ and direction $v_{d}$
- Then, $Lv_{d} = v_{d} \vec{L}$
- Now, $F_{B}  =(nqAv_{d})(\vec{L} \times \vec{B})$
$$F_{B} =  I\vec{L}\times\vec{B}$$
![[Pasted image 20240329110306.png]]
- $I=0$ then $F_{B} = 0$
- $I \ne 0$: 
	- upward: $$F_{B} = ILB \text{, (left)}$$
	- downward: $$F_{B} = ILB, \text{ (right)}$$
- Above assumes $B$ uniform and $\perp$ to L.
- What if $B$ is not uniform?
	- ![[Pasted image 20240329110650.png]]
	- Then, $$dF_{B} = Idl\times B$$
	- And, $$F_{B} = \int_{A}^{B}dFB$$$$F_{B}= I \int_{A}^{B}dl\times B$$
		- General answer.
- APC: Assume $\vec{B}$ is uniform.
	- Then, $F_{B}  = I(\int_{A}^{B} d\vec{l})\times\vec{B}$

### Torque on a current-carrying loop:
- ![[Pasted image 20240329113327.png|400]]
- $$F_{B} = F_{B,top} + F_{B,lhs} + F_{B,rhs} + F_{B, bott}$$$$F_{B,top} = IL_{top}\times B=0$$$$F_{B, bott}=  IL_{bot}\times B=0$$$$F_{B,lhs} = IL_{L}\times B = I(b)B, \text {out of board}$$$$F_{B,rhs} = I(b)B, \text {into board}$$$$\sum\limits F_{B} =0$$

### Torque on a Current-Carrying Loop
![[Pasted image 20240401105344.png]]
$$\sum\limits \vec{\tau}= \tau_{left} + \tau_{right}$$$$F_{left} = I\vec{l}\times\vec{B} = I(b)B, \text{ out of board}$$$$F_{right} = I\vec{l}\times\vec{B} = I(b)B, \text { out of board}$$
Top view:
![[Pasted image 20240401105850.png|400]]
$$\tau_{left} = F(\frac{a}{2}), CCW$$$$\tau_{left}= IbB(\frac{a}{2}), CCW$$$$\tau_{right} =IbB(\frac{a}{2}), CCW$$$$\sum\limits \tau = \tau_{left} + \tau_{right}$$$$\sum\limits\tau = I(ab)B, CCW$$$$\sum\limits\tau = IAB, CCW$$
What if $\vec{B}$ not parallel to the plane of the loop?
![[Pasted image 20240401110519.png]]
Now, $\tau = IAB \sin\theta$
Define a vector $\vec{A}$ where $|\vec{A}|$ is the area of the loop, and direction is $\perp$ to the plane of the loop.
Then, $\tau = I \vec{a}\times\vec{B}$
Define the magnetic dipole moment ($\mu$) $$\mu = I\vec{A}$$Finally: $$\tau  = \mu \times\vec{B}$$
![[Pasted image 20240401110858.png]]
### Magnetic Field due to a long, straight wire
![[Pasted image 20240402105457.png]]
$$B = \frac{\mu_{0}I}{2\pi r}; rhr$$
$$\mu_{0} = 4\pi * 10^{-7} \frac{T\cdot m}{A}$$
- permeability of free space

### Magnetic force between two parallel wires
![[Pasted image 20240402105911.png]]
$$F_{2 on1} = I_{1}L\times B_{2}$$$$F_{2on1} = I(L\hat{i})\times(\frac{\mu_{0}I_{2}}{2\pi d}\hat{k})$$$$F_{2on1} = L \frac{\mu_{0}I_{1}I_{2}}{2\pi d} (-\hat{j})$$$$\frac{F_{2on1}}{L} = \frac{\mu_{0}I_{1}I_{2}}{2\pi d} (-\hat{j})$$$$F_{1on2} = I_{2}L\times B_{1}$$$$F_{1on2} = I_{2} (L\hat{i}) \times (\frac{\mu_0I_{1}}{2\pi d} (\hat{k}))$$$$F_{1on2} = L\left(\frac{\mu_{0}I_{1}I_{2}}{2\pi d}\right)(+\hat{j})$$$$\frac{F_{1on2}}{L} = \frac{\mu_{0}I_{1}I_{2}}{2\pi d}\hat{j}$$
- Forces
	- $I_{1}$ and $I_{2}$ same direction $\rightarrow$ attractive
	- $I_{1}$ and $I_{2}$ opposite direction $\rightarrow$ repellent


## Ampere's Law:
Consider a current-carrying wire perpendicular to the plane of the board:
![[Pasted image 20240402111442.png]]
$$B = \frac{\mu_{0}I}{2\pi r}$$
- Consider a length $d\vec{l}$ of the loop; then, evaluate $B\cdot dl$ for the loop.
- Now, $B$ is parallel to $d\vec{l}$, so $B\cdot dl = Bdl$
- For the entire loop, $$\oint B\cdot dl = \oint Bdl = \oint \left(\frac{\mu_{0}I}{2\pi r}\right)dl$$$$\oint B\cdot dl = \left[\frac{\mu_{0}I}{2\pi r}\right]\oint dl$$$$\oint dl  = 2\pi r$$$$\oint B\cdot dl = \mu_{0}I_{enc}$$
	- This is Ampere's Law.
	- Notes:
		- Works for *any* closed loop, regardless of shape.
		- Known as as Amperian loop.
		- Magnetic analog to Gauss's Law.
- Magnetic field inside a solenoid
	- Solenoid:
		- ![[Pasted image 20240403112855.png]]

## The Biot-Savart Law
- Consider an arbitrary current flowing along some path and measure the differential field $d\vec{B}$ due to an element $d\vec{l}$ of the path.
- ![[Pasted image 20240405105811.png]]
- From experiment, find: $$dB \propto I, dB\propto dl, dB\propto \sin\theta, dB \propto \frac{1}{r^{2}}$$
- Combining these dependencies: $$dB \propto \frac{Idl\sin\theta}{r^{2}}$$
- Proportionality constant is: $$\frac{\mu_{0}}{4\pi} \text { where }\mu_{0} = 4\pi * 10^{-7} \frac{T\cdot m}{A}$$
- In vector form: $$d\vec{B} = \frac{\mu_{0}I}{4\pi} \frac{d\vec{l}\times\hat{r}}{r^{2}}$$
- Total field: $$\vec{B} = \oint_{path} d\vec{B}$$$$\vec{B} = \frac{\mu_{0}I}{4\pi} \int \frac{d\vec{l}\times\hat{r}}{r^{2}}$$
- Notes: 
	- vector summation (cross product)
	- Magnetic equivalent of Coulomb's Law
	- Inverse-square law like Coulomb's law

### Example: Find the magnetic field at point P for the following current loop:
- ![[Pasted image 20240405110336.png]]
- B-S Law: $$\vec{B} = \frac{\mu_{0}I}{4\pi} \int_{path} \frac{d\vec{l}\times\hat{r}}{r^{2}}$$
- Symmetry:
	- Paths 1 and 3: $d\vec{l} \parallel \hat{r}$, so $d\vec{l} \times \hat{r} = 0$
	- Path 2: $d\vec{l} \perp \hat{r}$, so $d\vec{l} \times\hat{r}$ = $d\vec{l} (+\hat{k})$
	- Path 4: $d\vec{l} \perp \hat{r}$, so $d\vec{l}\times\hat{r} = d\vec{l}(-\hat{k})$
	- Paths 2 and 4 are by right-hand rule

$$B = \frac{\mu_{0}I}{4\pi} \left[\int_{2} \frac{dl\hat{k}}{r^{2}} + \int_{4} dl(\frac{-\hat{k})}{r^{2}}\right]$$
- Path 2: $r = R_{1} =$ constant
- Path 4: $r = R_{2} =$ constant
$$\vec{B} = \frac{\mu_{0}I}{4\pi} \left[\frac{\hat{k}}{R_{1}^{2}\int_{2}dl}+ \frac{-\hat{k}}{r^{2}_{2}} \int_{4} dl\right]$$$$\vec{B} = \frac{\mu_{0}I}{4\pi} \theta\hat{k} \left[\frac{1}{r_{1}} - \frac{1}{r_{2}}\right]$$$$\vec{B} = \frac{\mu_{0}I\theta}{4\pi} \left[\frac{R_{2} - R_{1}}{R_{2}R_{1}}\right]\hat{k}$$

### Magnetic force due to a current loop
- ![[Pasted image 20240405112415.png]]
- Find the force on the current loop due to the wire (long).
- Symmetry: 
	- $\vec{F}_{B}$ on sections 1 and 3 cancel.
		- ($F_{B, 1} \rightarrow, F_{B,2}\leftarrow$)
	- $F_{B,2} \downarrow$, $F_{B, 4} \uparrow$
- $$\vec{F}_{b,loop} = \vec{F}_{B,2} + \vec{F}_{B,4}$$$$\vec{F}_{B,loop} = \left[\frac{\mu_{0}I_{1}I_{2}l}{2\pi d_{2}}(-\hat{j}) + \frac{\mu_{0}I_{1}I_{2}l}{2\pi d_{1}}(+\hat{j}\right]$$$$\vec{F}_{B,loop} \frac{\mu_{0}I_{1}I_{2}l}{2\pi} \left[\frac{d_{2}-d_{1}}{d_{1}d_{2}}\right]\hat{j}$$