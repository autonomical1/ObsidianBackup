# Electrodynamics
- Charges carriers move!
- Moving charges are an *electric current*
- Consider some surface area $A$.
	- ![[Pasted image 20240301105652.png|400]]
		- Definition: Let some charge $\Delta Q$ flow through $A$ in time $\Delta t$.
- Then, the current ($I$) is defined by: $$I = \frac{\Delta Q}{\Delta t} \text { (AP 2 Version) }$$
- SI Units: Ampere (Amp) $$1A = \frac{1C}{1S}$$
- **AP C Version**: $$I = \frac{dQ}{dt}$$
### Microscopic Model
- Consider a conductor of length L and cross-sectional area A.
	- ![[Pasted image 20240301110928.png]]

### Conventional Current
- Flows in the same direction as $\vec{E}$ in the conductor.
- Represents the sense of positive charge flow.
- Positive charge carriers are known as *holes*
- Electron current (rare): flow of electrons ($e^{-}$)
- Conductivity:
	- material dependent property that describes how readily charge can move through a conductor.
	- symbol: $\sigma$ 
- Resistivity:
	- Reciprocal of conductivity
	- symbol: $\rho$ 
	- SI Unit: $[\rho] = \ohm \cdot m$
	- $\rho = \frac{1}{\sigma}$

## Ohm's Law
- Empirical result (not a law of nature)
- *Ohmic* materials obey Ohm's law
- *Nonohmic* materials do not obey Ohm's law
- Relates the *current density* in a conductor to the magnitude of $\vec{E}$
- $$\vec{J} = \sigma \vec{E}$$
	- where $\vec{J} = \frac{I}{A}$ is the current density in the conductor and $\sigma$ is the conductivity of the conductor.

### "Practical" form of Ohm's Law
- Assume that $\vec{E}$ is uniform
- Then, $\Delta V = E\cdot L$, so $E = \frac{\Delta V}{L}$$$J = \sigma E$$$$J = \sigma (\frac{\Delta V}{L})$$$$\Delta V = \frac{JL}{\sigma} = \frac{L}{\sigma} *J$$Substituting $J = \frac{I}{A}$$$\Delta V = \frac{L}{\sigma} \cdot \frac{I}{A} = \left(\frac{L}{\sigma A}\right)* I$$Using $\rho = \frac{1}{\sigma}$$$\Delta V = (\rho \frac{L}{A})*I$$
- Define the resistance ($R$) of the conductor as: $$R = \rho \frac{L}{A}$$
	- SI Unit: $[R] = \ohm \text { (Ohm)}$
- Substituting, we obtain: $$\Delta V = I*R \text { (Ohm's Law)}$$
- Ohmic material: 
	- ![[Pasted image 20240304110603.png|400]]
	- Units: $\frac{1}{R} = \frac{1}{\ohm} = \mho \text { (mho)}$

# Electric Circuits:
### Requirements
- 1. Source of potential difference ($\Delta V$)
- 2. Closed, conducting path.
- 3. Some form of load resistance

### Kirchhoff's Rules: 
- Two rules:
	- 1) Junction rule: Conservation of charge
	- 2) Loop rule: Conservation of energy
- Junction: Location in a circuit where two or more wires meet.
	- Ex: ![[Pasted image 20240304112251.png|400]]
- Junction: $$\sum\limits I_{in} = \sum\limits I_{out}$$
- Loop: Any path through the circuit where we begin and end at the same location
- Through any closed loop in a circuit, $\sum\limits V_{loop} = 0$
	- Ex:![[Pasted image 20240304112933.png]]
- Example:
	- ![[Pasted image 20240305105728.png|500]]
	- Junction: $\sum\limits I_{in} = \sum\limits I_{out}$$$I_{1} = I_{2} + I_{3}$$Left loop CW: $$\sum\limits V_{loop} = 0 = +12V - (5\ohm)(I_{1}) - (3\ohm)(I_{3}) -(7\ohm)(I_{1})$$$$12I_{1} + 3I_{3} = 12$$$$4I_{1} + I_{3} = 4$$

- Power Dissipation in a resistor:
	- ![[Pasted image 20240306105911.png]]
	- Loop rule: $$\sum\limits \Delta V_{loop} = \Delta V_{abcda} = 0$$
	- Potential drop $\Delta V$ across $R$.
	- As charge $q$ moves through the resistor, $U = q\Delta V$ is deposited.
	- Power dissipated is: $$P = \frac{dU}{dt} = \frac{d}{dt} (q\Delta V)$$$$P = (\frac{dq}{dt})\Delta V$$$$P = I\Delta V$$
		- Ohm's Law derivations: $$P = IV$$$$P = I^{2} R$$$$P = \frac{V^{2}}{R}$$
	- SI Unit: Watt ($W$)
		- $1W = 1 \frac{J}{s}$
	- Energy: $1J = 1 W*s$

## Series and Parallel Connections: 
### Series Connection: 
- Circuit elements connected in a line without junctions
- Current is the same through all elements.
- Voltages will vary.
- Example:
	- ![[Pasted image 20240306111302.png|400]]
	- Equivalent Circuit: 
	  ![[Pasted image 20240306111509.png|400]]
#### Equivalent Resistance
$$I = I_{1} + I_{2} \text { } (\text{Junction rule})$$$$V = V_{1} + V_{2} \text{ (Loop rule)}$$$$IR_{eq} = IR_{1} + IR_{2}$$$$R_{eq} = R_{1} + R_{2}$$For $N$ resistors: $$R_{eq} = R_{1} + R_{2} + \text{ } . . . \text{ } + R_{N}$$Note: $R_{eq}$ is greater than any individual resistance.

### Parallel Connections:
- Circuit elements encounter a junction.
- Current varies
- Voltages are the same.
- Example:
	- ![[Pasted image 20240306112227.png]]
		- Junction Rule: $$I = I_{1} + I_{2}$$
	- Equivalent Circuit:
	  ![[Pasted image 20240306111509.png|400]]
	  Now: $$I = \frac{V}{R_{eq}}$$$$I = I_{1} + I_{2}$$$$\frac{V}{R_{eq}} =\frac{V_{1}}{R_{1}} + \frac{V_{2}}{R_{2}}$$However, $V = V_{1} + V_{2}$$$\frac{V}{R_{eq}}  =\frac{V_{1}}{R_{1}}+ \frac{V_{2}}{R_{2}}$$$$\frac{1}{R_{eq}}= \frac{1}{R_{1}}+ \frac{1}{R_{2}}$$$$R_{eq} = \left[\frac{1}{R_{1}}+ \frac{1}{R_{2}}\right]^{-1}$$General: $$R_{eq} = \left[\frac{1}{R_{1}} = \frac{1}{R_{2}} + \text{ } . . . \text{ } \frac{1}{R_{n}}\right]^{-1}$$Note: For a parallel combo, $R_{eq}$ is _less than_ any individual resistance.
	  ![[Pasted image 20240306112843.png]]

## RC Circuits
- Consists of a resistor and capacitor in series. 
- **Case I**: Charging an uncharged capacitor
	- ![[Pasted image 20240318105939.png|400]]
	- Close switch at time $t = 0$
	- Loop rule: $$\sum\limits V_{loop} = 0 = \epsilon - V_{R} - V_{C}$$
	- $$\epsilon = IR + \frac{Q}{C}$$
	- Substitute: $I = \frac{dQ}{dt}$
	- $$\epsilon = R \frac{dQ}{dt} + \frac{Q}{C}$$
	- Separate the variables: $$\epsilon dt = RdQ + \frac{Q}{C} dt$$$$C\epsilon dt = RCdQ + Qdt$$$$\frac{((\epsilon-Q))dt}{C\epsilon-Q} = \frac{RCdQ}{C\epsilon-Q}$$$$dt = \frac{RCdQ}{C\epsilon-Q}$$$$\frac{dt}{RC} = \frac{dQ}{C\epsilon-Q}$$
	- Integrate both sides: 
		- Limits: $t = 0$, $Q = 0$, $t \gt 0$, $Q \gt 0$
	$$\int_{0}^{Q} \frac{dQ}{C\epsilon-Q} = \int_{0}^{t} \frac{dt}{RC}$$$$-\ln(C\epsilon-Q) |_{0}^{Q} = \frac{t}{RC} |_{0}^{t}$$$$-\ln(C\epsilon-Q) + \ln(C\epsilon) = \frac{t}{RC}$$$$\ln(C\epsilon-Q) - \ln(C\epsilon) = \frac{-t}{RC}$$$$ln(1- \frac{Q}{C\epsilon})= \frac{-t}{RC}$$
	- Exponentiate both sides: $$1 - \frac{Q}{C\epsilon} = e^{-t/RC}$$$$C\epsilon-Q = C\epsilon e^{-t/RC}$$$$-Q = C\epsilon e^{-t/RC} -C\epsilon$$Therefore: $$Q(t)  = C\epsilon(1-e^{-t/RC})$$$$V_{C} (t) = Q\frac{t}{C}$$Therefore: $$V_{C} (t) = \epsilon(1-e^{-t/RC})$$**RC Time Constant**: $\tau = RC$
		- Looks like this: ![[Pasted image 20240318112110.png|400]]
	- Current: $$I(t) = \frac{dQ(t)}{dt} $$$$I(t) = \frac{d}{dt} \left[C\epsilon(1-e^{-t/RC}\right]$$$$I(t) = \frac{\epsilon}{R}e^{-t/\tau}$$
		- Looks like: ![[Pasted image 20240318112805.png|400]]
- **Case II**: Discharging a charged capacitor
	- ![[Pasted image 20240318112956.png|400]]
	- Switch is closed at $t = 0$
	- At any instant,  $$V_{C} = V_{R}$$$$\frac{Q}{C} = IR$$where $I = - \frac{dQ}{dt}$ (discharging)$$\frac{Q}{C} = -R \frac{dQ}{dt}$$$$\frac{dQ}{Q} = \frac{-dt}{RC}$$Limits: $t = 0$, $Q = Q_{0}$, $t \gt 0$, $Q \lt Q_{0}$$$\int_{Q_{0}}^{Q} \frac{dQ}{Q} = \int_{0^{t}} \frac{-t}{RC}$$$$\ln(Q)|_{Q_{0}}^{Q}= \frac{-t}{RC}$$$$\frac{Q}{Q_{0}} = e^{-t/RC}$$$$Q(t) = Q_{0} e^{-t/RC}$$$$V(t) =V_{0} e^{-t/RC}$$ $V_{0} = \frac{Q_{0}}{C}$
- 