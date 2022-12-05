

**Ohm's Law and Resistor Circuits**:
- $R = \frac{\Delta V_{wire}}{I}$
- Si Unit = 1 Ohm = 1 $\Omega$ = 1 $\frac{V}{A}$  
- Ohm's Law: $\Delta V = I \cdot R$ 
- Not a law of nature, not all conductors follow Ohm's Law
- Materials that follow Ohm's Law = **ohmic**
- If the graph of I vs V is linear, the material is non-ohmic, and if it is non-linear it would be non-ohmic

**Resistors**:
- Circuit elements that are designed to have certain resistance for practical reasons
- Uses:
	- Current Limiter
	- Voltage divider
- 
**Resistivity**:
- $\rho$ characterizes the electrical properties of materials
- Materials that are good conductors have low resistivity
- Materials that are poor conductors (good insulators) = high resistivity
- resistivity of a metal decreases with increasing temperature
- $R = \frac{\rho \cdot L}{A}$ 
	- property of a specific wire, since it depends on the conductors length, diameter and material

 **Energy and Power**:
 - The charge escalator transfers the chemical energy $E_{chem}$ to the electric potential energy U of the charges
 - That energy is then dissipated as the charges move through the lightbulb, keeping the filament warm and glowing
 - The battery provides potential energy to a charge "q" as it lifts the charge up the charge escalator from the negative to the positive terminal
 - The rate at which energy is transferred from the battery to the moving charges is:
	 - $P_{bat} =$ rate of energy transfer $= \frac{\Delta U}{\Delta t} = \frac{\Delta q}{\Delta t}\epsilon$
	 - $P_{emf} = I \epsilon$ 
	 - Units: $1 \frac{J}{s}$ or W

**Kirchhoff's Loop Rule**:
- Any closed loop in a circuit has $\Delta V = 0$

**Series and Parallel Circuits**:
- **Series circuit**: if circuit elements are connected directly to each other with no junction in between
- **Parallel circuit**: if circuit elements are not connected directly to each other and have a junction in between
	- Current will divide due to Kirchhoff's Junction Rule

**Series Resistors**:
- When there are two resistors in series, the current must be the same in both resistors because there are no junctions in the circuit
- Kirchhoff's Loop Rule shows potential differences:
	- $$\sum\limits \Delta V_{i} = \epsilon + \Delta V_{1} + \Delta V_{2} = 0$$
- An easy way to model multiple resistors in series is creating an equivalent resistor:
	- $$R_{eq} = R_{1} + R_{2} + . . . + R_{n}$$

**Parallel Resistors**:
- The potential differences across each resistor in parallel is equal to the  emf of the battery because both resistors are connected directly to the battery 
- The current $I_{bat}$ from the battery splits into currents $I_{1}$ and $I_{2}$ at the top of the junction
- Junction law states $$I_{bat}= I_{1} + I_{2}$$
- $$I_{bat} = \epsilon (\frac{1}{R_{1}} + \frac{1}{r_{2}})$$
- $$R_{eq} =  \frac{\Delta V}{I} = \frac{\epsilon}{I_{bat}} = (\frac{1}{R_{1}} + \frac{1}{R_{2}})^{-1}$$
- $$R_{eq} = (\frac{1}{R_{1}} + \frac{1}{R_{2}} + . . . + \frac{1}{R_{n}})^{-1} $$
	- DO NOT FORGET TO TAKE RECIPROCAL OF THE TOTAL RESISTANCES
- *The equivalent resistance of several resistors in parallel is always less than any single resistor in the group**
- 