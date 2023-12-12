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
		- 