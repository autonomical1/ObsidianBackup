# Capacitors:
- Any configuration of two conductors having equal charge with opposite sign is known as a **capacitor**.
	- ![[Pasted image 20240209105926.png]]
- Often (almost always), the conductors are parallel plates.
	- Known as a **parallel plate capacitor**
	- ![[Pasted image 20240209110257.png]]
		- *Strong* and uniform $\vec{E}$ between the plates.
	- Types:
		- Ceramic disk capacitor
		- Electrolytic capacitor
- Empirical Result: $$Q \propto \Delta V$$
	- Constant of proportionality is known as the *capacitance* of the capacitor.$$Q= C\Delta V$$
		- $C$ (capacitance) - measure of the ability to store charge.
		- SI Unit: Farad ($F$), where $1F = \frac{1C}{1V}$
		- Most capacitors are in the $pF, nF, \mu F, mF$
## Parallel Plate Capacitor
$$C = \frac{Q}{\Delta V}$$Also, $E = \frac{\sigma}{\epsilon_{0}}$ where $\sigma = \frac{Q}{A}$ $$E = \frac{Q}{\epsilon_{0}A}$$$$Q = \epsilon_{0} EA$$Also, $\Delta V = E \cdot d$ where $\vec{E}$ is uniform
Substituting: $$C = \frac{Q}{\Delta V} = \frac{\epsilon_{0} EA}{E\cdot d}$$$$C = \epsilon_{0} \frac{A}{d}$$
- $\epsilon_{0} = 8.854 * 10^{-12} \frac{C^{2}}{Nm^{2}}$
- $A$ = plate area
- $d$ = plate separation

## Capacitance of a Capacitor
- Other arrangements of conductors also have capacitance. 
- <ins>Ex:</ins> Cylindrical Capacitor
	- ![[Pasted image 20240220110813.png]]$$\Delta V = V_{B} - V_{A} = -\int_{a}^{b} \vec{E} \cdot d\vec{l}$$For a long cylinder, $$\vec{E} = \frac{1}{2\pi\epsilon_{0}} \frac{\lambda}{R} \hat{r}$$where $$\lambda = \frac{Q}{L} \text{ , so } \vec{E} = \frac{1}{2\pi\epsilon_{0}} \frac{Q}{LR} \hat{r} \text { and } d\vec{l} = \hat{r}d\vec{r}$$Substituting:$$\Delta V = -\int_{R_{a}}^{R_{b}} \left(\frac{1}{2\pi\epsilon_{0}} \frac{Q}{LR} \hat{r}\right)\cdot (-\hat{r} d\vec{r})$$$$\Delta V = \frac{+1}{2\pi\epsilon_{0}} \frac{Q}{L}  \int_{R_{a}}^{R_{b}} \frac{dr}{r}$$$$\Delta V = \frac{Q}{2\pi\epsilon_{0}L} [\ln(R_{b})-\ln(R_{a})]$$$$\Delta V = \frac{Q}{2\pi\epsilon_{0}}\ln[\frac{R_{b}}{R_{a}}]$$Finally, $Q = C\Delta V$$$C = \frac{Q}{\Delta V} = \frac{2\pi\epsilon_{0}L}{\ln(\frac{R_{a}}{R_{b}})}$$

## Capacitors in Series and Parallel
- Schematic diagram symbols

| Wire | ![[Pasted image 20240221105523.png]] | ![[Pasted image 20240221105532.png\|50]] | ![[Pasted image 20240221105539.png]] |
| ---- | ---- | ---- | ---- |
| Resistor | ![[Pasted image 20240221105633.png\|200]] | ![[Pasted image 20240221105651.png\|200]] |  |
| Variable Resistor | ![[Pasted image 20240221105956.png\|200]] |  |  |
| Capacitor | ![[Pasted image 20240221105743.png]](unpolarized) | ![[Pasted image 20240221105850.png]](polarized) |  |
| Battery (EMF) | ![[Pasted image 20240221110409.png]](cell) | ![[Pasted image 20240221110616.png]](multi-cell or DC power supply) |  |
### Two main ways to connect circuit elements
1. Series connection: 
	- ![[Pasted image 20240221110838.png|300]]
	- Connected in Series: 
		- same current (resistor)
		- same charge (capacitor)
		- different voltages
2. Parallel connection:
	- ![[Pasted image 20240221111522.png|300]]
	- Connected in Parallel: 
		- Different current (resistor)
		- Different charges (capacitor)
		- Same voltage across each

## Energy Storage in a Capacitor
- Energy stored is equal to work done in charging.
- Consider an initially uncharged capacitor:
	- ![[Pasted image 20240222111703.png|500]]
	- $$Q = CV$$$$W_{ext} = U_{E} = q\Delta V$$
- At some point, assume total charge q on the capacitor.
- Then, there would be a potential difference $\Delta V = \frac{Q}{C}$ across the plates.
- To move an additional charge $dq$ requires work $dW_{ext} = d\Delta U_{E} = \Delta V dq  = (\frac{q}{c})dq$
- Then, the total amount of work: $$W_{ext} = \int dW_{ext} = \int_{0}^{Q} \frac{1}{C} qdq$$$$W_{ext} = U_{E} = \frac{Q^{2}}{2C} $$
- Use $Q = CV$ to obtain: $$U_{E} = \frac{Q^{2}}{2C} = \frac{C^{2}V^{2}}{2C} = \frac{1}{2}CV^{2}$$$$U_{E} \frac{Q^{2}}{2(\frac{Q}{V})} = \frac{VQ^{2}}{2Q} = \frac{1}{2}QV$$$$U_{E} = \frac{Q^{2}}{2C} = \frac{1}{2} CV^{2} = \frac{1}{2} QV$$

# Dielectrics
- An insulator placed between the places of a capacitor is known as a dielectric.
- Dielectrics
	- allow for increased voltage.
	- increase capacitance
	- provide mechanical support for plates.
- Dielectric strength: Maximum $E$-field before the dielectric breaks down.

