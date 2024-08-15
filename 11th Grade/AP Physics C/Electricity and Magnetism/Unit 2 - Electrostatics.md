- Electric effects were first noticed by the ancient Greeks.
- Discovered that amber could pick up small pieces of cloth or straw.
- Benjamin Franklin (18th C)
	- Discovered two types of charge:
	- Named them "positive" and "negative"
- Most matter is electrically **neutral**
	- **Neutral**: equal numbers of + (protons) and - (electrons)
		- *no net charge*
- Charged Objects: **Always have +/- imbalance** **Always transfer electrons** 
- Properties of charge:
	- **conserved**
	- **quantized**
	-  Any charge, q, has specific values so that $q = Ne$ where $N$ is an integer and $e$ is the magnitude of electron charge.
- **Charged Particles**:
	- *Proton*: $q_{p} = +e$
	- *Electron:* $q_{e} = -e$
	- $e$: Fundamental unit of charge

## Charging by Friction
- Two objects can be charged by rubbing them together.
	- Ex: Rubber & Fur
	- Ex: Glass & Silk

## Charging by conduction:
- Consider a charged rubber rod and a neutral conducting sphere.

## Electrostatic Force:
- Recall that electric charges exert forces on one another (Newton's 3rd Law).
- Like charges repel ($+/+$ or $-/-$)
- Opposite charges attract ($+/-$ or $-/+$)

## Conductors and Insulators
- **Conductors**: Allow charges to move freely throughout the material; tend to be metallic
- **Insulators**: Do not allow charge to move freely; tend to be nonmetallic

## Polarization of an Insulator
![[Pasted image 20231206110639.png]]
## Polarization of a conductor: 
- Assume conductor is initially neutral
	- no net charge
- ![[Pasted image 20231206111050.png]]

## Charge by induction:
- Connect one side of conductor to an electrical ground
- Ground: enforces no net charge
	- ![[Pasted image 20231206111912.png]]


## Electrostatic force between two point-charges
- **point-charge**: size of the object is very small compared to the separation distance
- Empirical (Charles Coulomb):
	- found that: $$F_{E} \propto \frac{1}{r^{2}}$$$$F_{E}= |q_{1}||q_{2}|$$
		- combine with constant of proportionality ($k_{e}$: coulomb constant)
- Coulomb's Law: $$ |F_{E}| = k_{E} \frac{q_{1}q_{2}}{r^{2}}$$where $$k_{E} = 9.0 * 10^{9}\frac{N\cdot m^{2}}{C^{2}}$$but the real constant: $$k_{E} = \frac{1}{4\pi\epsilon_{0}}$$ where $\epsilon_{0} = 8.854 * 10^{-12} \frac{C^{2}}{N\cdot m^{2}}$ is the permittivity of free space

### Example: Electric Force due to Multiple Charges
- Consider three identical charges that form an equilateral triangle
- Find the electrical force on one of the charges due to the other two:
- ![[Pasted image 20231211111312.png]]


## Electric Field
- Consider very large source charge, Q, and a very small test charge, $q_0$
- ![[Pasted image 20231211112354.png]]
- We define the electric field at point P in terms of electric force experienced by charge $q_0$
	- $$\overrightarrow{E} = \frac{F_{E}}{q_{0}}$$

## Electric Field Due to a Point Charge
- $$E = \frac{F_{E}}{q_{0}} = \frac{1}{q_{0}} [k_{E} (\frac{Qq_{0}}{r^{2}} \hat{r})]$$therefore: $$E = k_{E} \frac{Q}{r^{2}}\hat{r}$$
- Electric field due to an extended (continuous) charge distribution:
	- Then: $\Delta E$, due to $\Delta q$ is: $$\Delta E = k_{E} \frac{\Delta q}{r^{2}}\hat{r}$$
	- And: $$E \approx \sum\limits_{i} \frac{\Delta q_{i}}{r_{i}^{2}} \hat{r_{i}}$$
	- Becomes exact when: $$E = \lim_{\Delta q \rightarrow 0} k_{E} \frac{\Delta q_{i}}{r_{i}^{2}}\hat{r_{i}} = k_{E} \int \frac{dq}{r^{2}}\hat{r}$$
- Example: Find $E$ at point $P$.![[Pasted image 20231212105401.png]]
	- Answer: $$E = k_{E} \int \frac{dq}{r^{2}}\hat{r}$$
		- $dq$: differential piece of charge
		- $r$: distance from $dq$ to $P$
		- $\hat{r}$: radial (outward $+$, inward $-$)

## Charge Densities:
- Linear: $$\lambda (x) = \frac{dq}{dx} \rightarrow dq = \lambda (x)dx$$
- Surface (area): $$\sigma (A) = \frac{dq}{dA} \rightarrow dq = \sigma (A)da$$
	- (Book uses $\eta$)

### Example: Uniform Ring of Charge
- ![[Pasted image 20231212112028.png]]
	- Symmetry: $y$ and $z$ components cancel, $x$-components add.
	- Then: $$E = \int \frac{dq}{r^{2}}\hat{r}$$$$E = E_{x} = k_{E} \int \frac{dq}{r^{2}}cos\theta \hat{i}$$where $$r^{2} = (x^{2} + R^{2})$$and$$cos \theta = \frac{x}{r} = \frac{x}{ (x^{2} + R^{2})^{\frac{1}{2}}}$$Substituting, we obtain: $$E = k_{E} \int \frac{dq}{x^{2} + R^{2}}\cdot \frac{x}{(x^{2}+ R^{2})^{\frac{1}{2}}} \hat{i}$$$$E = k_{E} \frac{x\hat{i}}{(x^{2} + R^{2})^{\frac{3}{2}}} \int dq$$$$E = k_{E} \frac{Qx}{(x^{2} + R^{2})^{\frac{3}{2}}\hat{i}}$$
	- Uniform ring of radius R.
		- Test: $x = 0 \rightarrow E = 0$

### Example: Find $E$ at the origin force for a very long wire with charge density $\lambda_{0}$ along the x-axis starting at $x_{0}$
![[Pasted image 20231213110611.png]]
- Symmetry:$$E = E_{x}\hat{i}$$$$E_{x} = k_{E} \int \frac{dq}{x^{2}}$$$$\lambda (x) = \lambda_{0}  = \frac{dq}{dx} \rightarrow dq = \lambda_{0}dx$$$$E_{x} = k_{E} \int_{x_{0}}^{\infty} \frac{\lambda_{0} dx}{x^{2}}$$$$E_{x}  = k_{E} \lambda_{0} \int_{x_{0}}^{\infty} \frac{dx}{x^{2}}$$$$E_{x} = k_{E}\lambda_{0} [\frac{-1}{x} |_{x_{0}}^\infty]$$$$E_{x} = k_{E}\lambda_{0} [0 - \frac{-1}{x_{0}}]$$$$E_{x} = \frac{k_{E}\lambda_{0}}{x_{0}}$$$$E = \frac{k_{E}\lambda_{0}}{x_{0}}(-\hat{i})$$$$E = -k_{E} \frac{\lambda_{0}}{x_{0}}\hat{i}$$


## Electric Field Lines
- Used as a visual representation of the E-Field
- The E-field is tangent to the field lines at every point in space.
- Rules for Drawing:
	- 1) E-field lines must begin on a positive charge and end on a negative charge.
	- 2) Number of lines is proportional to the magnitude of the charge.
	- 3) If charges are unbalanced, some lines begin or end at infinity.
	- 4) Line density is proportional to $||E||$.
	- 5) E-field lines cannot touch or cross one another.

## Electric Flux
- Consider a uniform E-field in some region of space.
- Recall that |E| is proportional to the line density.
- Let the field lines penetrate some surface area A.
- ![[Pasted image 20231218105343.png]]
	- Define the electric flux $\Phi_{E}$ as: $$\Phi_{E} = E \cdot A$$
	- Geometrically: $$\Phi_{E} = E\cdot A = \frac{\text{number of lines}}{\text{area}} = \text{number of lines through } A$$
	- SI Unit: $$[\Phi_{E}] = \frac{N\cdot m^{2}}{C}$$
	- $\Phi_{E}$ depends on the orientation of both $\overrightarrow{E}$ and $\overrightarrow{A}$
		- Area vector $\overrightarrow{A}$ is defined to be $\perp$ to the surface with $||\overrightarrow{A}|| = \text{area}$ 
	- If $E$ is not $\perp$ to the plane of the sheet, then, effective area is $A_{eff} = A \cos\theta$

## What if E is not uniform?
- $$\Delta \Phi_{E} = E \cdot \Delta A$$$$\Phi_{E} \approx \sum\limits_{i} \Delta\Phi_{E, i} \approx\sum\limits_{i} E_{i} \cdot \Delta A_{i} $$
- Exact Solution as $\Delta A \rightarrow 0$$$\Phi_{E} = \lim_{\Delta A \rightarrow 0}\sum\limits_{i} E_{i}\cdot\Delta A_{i}$$$$\Phi_{E} = \int_{s} E\cdot \Delta A$$
	- integrate over surface area A, known as a surface integral.

- To get a sense of whether E-field lines are entering or exiting, we restrict our analysis to **closed surfaces**.
	- completely encloses a finite volume
	- Convention: $\Delta A$ always points outward.
	- Notation: $$\int_{s} \rightarrow \oint_{s}$$
	- Then, the electric flux is; $$\Phi_{E} = \oint_{s} E\cdot \Delta A$$
- Gauss's Law: $$\Phi_{E} = \oint_{s} E\cdot dA$$
	- The second half: $$\Phi_{E} = \frac{Q_{enc}}{\epsilon_{0}}$$


| **1**![[Pasted image 20240104110259.png]]  | **2**![[Pasted image 20240104110840.png]] |
| ---- | ---- |
| **3**![[Pasted image 20240104111154.png]] | ![[Pasted image 20240104111947.png]] |

## Applications of Gauss's Law
- Choose a closed Gaussian surface that satisfies one or more of the following conditions:
	- 1. By symmetry, $|E|$ is constant over the surface.
	- 2. $E$ and $dA$ are parallel so that $E \cdot dA = EdA$
	- 3. $E$ and $dA$ are perpendicular so $E\cdot dA = 0$
	- 4. $E$ is zero over the surface.

## Conductors in Electrostatic Equilibrium
- 1. $\overrightarrow{E} = 0$ inside the conductor. 
- 2. All charge resides on the surface.
- 3. $\overrightarrow{E}$ is perpendicular to the surface.
- 4. $|\overrightarrow{E}| = \frac{\sigma}{\epsilon_{0}} (TB: |\overrightarrow{E}| = \frac{\eta}{\epsilon_{0}})$ 
- 5. $|\overrightarrow{E}|$ inversely proportional to the radius of the curvature.

| 1 | ![[Pasted image 20240105113224.png]] |  |
| ---- | ---- | ---- |
| 2 | ![[Pasted image 20240105111909.png]] | ![[Pasted image 20240105112259.png]]<br>		If $E$ is not $\perp$ to the surface, then $F_{E} = qE$ has tangential component, so the charges will move. |
| 3 | ![[Pasted image 20240105112820.png]] |  |
| 4 | ![[Pasted image 20240108105609.png]] | $\oint_{s} E \cdot dA = \int_{\text{inner end cap}} E \cdot dA = \int_{\text{barrel}} E \cdot dA + \int_{\text{outer end cap}} E \cdot dA$<br>$\oint_s E\cdot dA = \int_{\text{outer end cap}} E \cdot dA$<br><br>Using symmetry:<br>1. $E = 0$ inside conductor (property #1)<br>2. For the barrel, $E \perp dA$, so $E \cdot dA =0$<br>3. For the outer endcap , $E \parallel dA$, so $E\cdot dA = EdA$<br><br>Substituting,<br>$\oint_s E\cdot dA = \int_{\text{outer end cap}} E dA = \frac{Q_{enc}}{\epsilon_{0}}$<br><br>Finally, $\|E\|$ is uniform over the end cap.<br>$E \int_{\text{outer end cap}} dA = \frac{Q_{enc}}{\epsilon_{0}}$<br>$E \cdot A = \frac{Q_{enc}}{\epsilon_{0}}$<br>$E = \frac{1}{\epsilon_0} \frac{Q_{enc}}{A}$<br><br>Therefore: <br>$E = \frac{\sigma}{\epsilon_0}$<br>where: $\sigma:$ charge density ($\sigma = \frac{Q}{A})$ |


### $\overrightarrow{E}$ due to a conducting spherical shell:
![[Pasted image 20240105110728.png]]
Two cases:
- 1. Outside the shell ($r \gt R$)
- 2. Inside the shell ($r \lt R$)
- Then apply boundary conditions (Two solutions agree at $r = R$)

Gaussian Surface: 
- Spherical shell with a radius $r \gt R$

Symmetry: 
- 1. $E$ is radial, so $\overrightarrow{E} \cdot d\overrightarrow{A} = EdA$
- 2. $|\overrightarrow{E}|$ is uniform for constant $r$.
  
Then: $$\oint_{s} E \cdot dA = E\int dA = \frac{Q_{enc}}{\epsilon_{0}}$$$$E \cdot A = \frac{+Q}{\epsilon_{0}}$$$$E = \frac{1}{\epsilon_{0}} \frac{Q}{A} = \frac{1}{\epsilon_{0}} \frac{Q}{4\pi r^{2}}$$Therefore: $$E = \frac{1}{4\pi\epsilon_{0}} \frac{Q}{r^{2}}$$
- Same as for point charge Q at enter

## Electric Potential and Potential Energy
- Use gravitation as an analogy:
	- ![[Pasted image 20240129105827.png]]
	- For no change in K: ![[Pasted image 20240129105958.png]]
	- W-E Theorem$$\Delta E = \Delta U_{g} = W_{ext} = -W_{g}$$
		- Same relationship for all conservative forces
- Charge in an electric field:
	- ![[Pasted image 20240129110235.png]]
	- $$$\Delta E = \Delta U_{E} = W_{ext} = -W_{E}$$$$\Delta U_{E} = F_{E} \cdot d$$$$\Delta U_{E} = q_{0} E d$$
	- Note: $\Delta U_{g} = mgh$
- What if $E$ was not uniform?
	- ![[Pasted image 20240129110851.png]]
	- Then, $$dW_{E} = F_{E} dl = 0dU_{E}$$$$dU_{E} = -F_{E} \cdot dl$$$$dU_{E} = -q_{0} E \cdot dl$$So, $$U_{E} = \int_{path} dU_{E}$$Therefore: $$U_{E} = q_{0} \int_{A}^{B} E\cdot dl$$
	- Want a quantity that only depends on E and path taken.
	- Define electric potential($V$) as: $$\Delta V = \frac{\Delta U_{E}}{q_{0}}$$
		- SI Unit: Volt ($V$)
	- Then: $$\Delta V = -\int_{A}^{B} E\cdot dl$$
- SI Units: 
	- Since $\Delta V = \frac{\Delta U_{E}}{q_{0}}$$$[V] = \frac{J}{C}$$
	- New Unit for Electric field: $$[E] = \frac{N}{C} \cdot \frac{m}{m}$$$$[E] = \frac{J}{C \cdot m}$$$$[E] = \frac{V}{m}$$
	- New unit for energy: $$\Delta U = q_{0} \Delta V$$Let $q_{0} = e$ (Fundamental charge) ($q_{0} = 1.6 \cdot 10^{-19} C$)$$\Delta U = e\Delta V$$for $\Delta V = 1V$, $\Delta U = 1eV$
		- $eV$ is the electron-volt.
	- $1 eV = 1.6 * 10^{-19} J$

### Potential due to a Point Charge
![[Pasted image 20240131110454.png]]
$$\Delta V = V_{B} - V_{A} = -\int_{A}^{B}E\cdot dl$$where$$E = k_{E} \frac{q}{r^{2}} \hat{r}$$![[Pasted image 20240131110805.png|200]]$$\Delta V = -\int_{A}^{B} (k_{E} \frac{q}{r^{2}}\hat{r})\cdot dl $$where $$\hat{r} \cdot dl = |\hat{r}||dl|\cos\theta$$$$\hat{r}\cdot dl  = (1)(dl)(\frac{dr}{dl})$$$$\hat{r} \cdot dl = dr$$
Substituting: $$\Delta V = -\int_{r_{A}}^{r_{B}} k_{E} \frac{q}{r^{2}} dr$$$$\Delta V = -k_{E} q \int_{r_{A}}^{r_{B}}$$$$\Delta V = -k_{E} q [\frac{-1}{r}]_{r_{A}}^{r_{B}}$$$$\Delta V = k_{E} q [\frac{1}{r_{B}} - \frac{1}{r_{A}}]$$
Convention: $V_{A} = 0$ at $r = \infty$ 
Let $r_{A} = \infty$ and $r_{B} = r$
Therefore:$$V(r) = k_{E} \frac{q}{r}$$Note: 
	$V \propto q$
	$V \propto \frac{1}{r}$
	$V$ is a scalar

- What if there's more than one charge?

### Apply Superposition:

![[Pasted image 20240202105219.png]]
$$V_{P} = V_{1} + V_{2} + V_{3}$$$$V_{P} = k_{E} \frac{q_{1}}{r_{1}} + k_{E} \frac{q_{2}}{r_{2}}+ k_{E}  \frac{q_{3}}{r_{3}}$$$$V_{P}  = k_{E} \sum\limits_{i} \frac{q_{i}}{r_{i}}$$(Scalar)

### Potential Energy of Two Point Charges
![[Pasted image 20240131111841.png]]
## V due to a continuous charge distribution:
![[Pasted image 20240202110303.png]]
$$dV = k_{E} \frac{dq}{r}$$$$V = \int dv = \int k_{E} \frac{dq}{r} = k_{E} \int \frac{dq}{r}$$

## V due to a uniform ring
![[Pasted image 20240202110845.png]]
$$V = k_{E} \int_{ring} \frac{dq}{r} \text { where r = } \sqrt{x^{2} + R^{2}}$$By Symmetry: $r =$ constant
$$V = (\frac{k_{E}}{\sqrt{x^{2} + R^{2}}}) \int_{ring} dq = \frac{(k_{E} Q)}{(x^{2} + R^{2})^{1/2}} \text { for a ring of charge } Q$$Find $E$
Symmetry: $E = E_{x} \hat{i}$ 
$$E_{x} = - \frac{dV}{dx} = \frac{d}{dx}(\frac{(k_{E} Q)}{(x^{2} + R^{2})^{1/2}})$$$$E_{x} = -k_{E}Q \frac{d}{dx} [(x^{2} + R^{2})^\frac{-1}{2}]$$$$E_{x} = -k_{E} Q \left(- \frac{1}{2}\right) (x^{2} + R^{2})^{3 / 2}  (2x)  = k_{E} Qx(x^{2} + R^{2})^{3 / 2}  $$ $$\overrightarrow{E} = \frac{k_{E}Qx}{{(x^{2} + R^{2} )^{3 / 2}}} \hat{i}  $$$E_x (x = 0) = 0$, $V_x  (x = 0) = \frac{k_{E}Q}{R} =$ const 
$E_{x} (x \gt \gt R): (x^{2} +R^{2})^{3 / 2}  \rightarrow (x^{2})^{3/2}\rightarrow x^{3}$ 
$E_{x} = \frac{k_{E}Qx}{x^{3}} = \frac{k_{E}Q}{x^{2}}$ for a point charge

### Problem 69, p. 713
![[Pasted image 20240202113146.png]]
where Length: L, Charge: Q, and $\lambda = \frac{Q}{L}$

$$V_{P} = k_{E} \int_{rod} \frac{dq}{r}$$$$\lambda(x) = \frac{dq}{dx} \rightarrow dq = \lambda(x) dx \rightarrow dq = \frac{Q}{L}dx$$Substituting: $$V = k_{E} \int_{rod} \left(\frac{Q}{L}\right) \frac{dx}{r} = \frac{k_{E}Q}{L} \int_{x- \frac{L}{2}}^{x+ \frac{L}{2}} \frac{dx}{x} $$$$V = \frac{k_{E}Q}{L} \ln(\frac{x+ \frac{L}{2}}{x - \frac{L}{2}})$$