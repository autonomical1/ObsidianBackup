# Electromagnetic Induction
### Faraday's Discovery of 1831:
- When one coil is placed directly above another, there is no current in the lower circuit while the switch is in the closed position.
- A momentary current appears whenever the switch is opened or closed.
- When a bar magnet is pushed into a coil of wire, it causes a momentary deflection fo the current-meter needle.
- Holding the magnet inside the coil has no effect.
- Same effect when moving the coil.
### Motional emf
![[Pasted image 20240408110007.png]]
- Magnetic force on the charge carriers in a moving conductor creates an electric field of strength $E = vB$ inside the conductor.
- For a conductor of length l, the motional emf perpendicular to the magnetic field is: $$F_{B} = F_{E}$$$$qvB = qE$$$$E = vB$$$$\Delta V = E\cdot l$$$$\Delta V = vBl$$$$\downarrow$$$$\epsilon = vlB$$
- If we slide a conducting wire along a U-shaped conducting rail, we can complete a circuit and drive an electric current.
- If the total resistance of the circuit is $R$, the induced current given by Ohm's law is: $$I = \frac{\epsilon}{R} = \frac{vlB}{R} $$
- To keep wire moving at constant speed v, apply pulling force $F_{pull}= \frac{vl^{2}B^{2}}{R}$.
- This pulling force does work at a rate: $$P_{input} = F_{pull}v = \frac{v^{2}l^{2}B^{2}}{R}$$
- All of this power is dissipated by the resistance of the circuit.
- $$I = \frac{\epsilon}{R} = \frac{vlB}{R}$$$$F_{B} = IlB \text{, left (rhr)}$$$$\vec{v} = \text { constant, then }$$$$F_{ext}  = F_{B} = IlB$$Substitute for I: $$F_{ext} = (\frac{vlB}{R})lB$$$$F_{ext} = \frac{vl^{2}B^{2}}{R}$$
### Induced Current
- pushing force needed to keep wire moving at a constant speed. 
- Once again, this input power is dissipated in an electric circuit
- generator - converts mechanical energy to electric energy.

### Magnetic Flux
- Magnetic flux measures the amount of magnetic field passing throug a loop of area $A$ if the loop is tilted at an angle $\theta$ from the field.$$\phi_{m} = A_{\text{eff}}B = AB\cos\theta$$
- The SI Unit of magnetic flux is the *weber*: $$1 \text { weber} = 1 \text { WB} = 1 Tm^{2}$$
### Magnetic Flux in a Nonuniform Field
- Total magnetic flux through the loop found with area integral: $$\phi_{m} \int_\text{area of loop} B \cdot dA$$

# Lenz's Law
- There is an induced current in a closed, conducting loop if and only if the magnetic flux through the loop is changing. The direction of the induced current is such that the induced magnetic field opposed the *change* in flux.
	- ![[Pasted image 20240409105616.png]]
- Pushing the bar magnet into the loop causes the magnetic flux to *increase* in the downward direction.
- To oppose change in flux (Lenz's Law), the loop itself needs to generate an upward pointing magnetic field. 
- The induced current ceases as soon as the magnet stops moving.
- Pushing the bar magnet away causes the magnetic flux to *decrease* in the downward direction.
- To oppose this decrease, a clockwise current is induced. 
- Tactics: Using Lenz's Law:
	- Determine direction of applied magnetic field.
		- Field must pass through loop.
	- Determine how flux is changing.
		- $\uparrow, \downarrow$ or staying the same
	- Determine the direction of an induced magnetic field that will oppose the change in flux.
		- Increasing flux - induced field opposite applied field
		- Decreasing flux - induced field in the same direction as applied field
		- Steady flux - no induced field.
	- Determine the direction of the induced current.
		- right-hand rule

# Faraday's Law
- emf induced through conducting loop if magnetic flux through loop changes.
- Magnitude of the emf is: $$\epsilon = \left|\frac{d\Phi_{m}}{dt}\right|$$
- Direction of the emf is such as to drive an induced current in the direction given by Lenz's Law.

| Faraday's Law: $$\epsilon = \left\|\frac{d\Phi_{m}}{dt}\right\|$$ | Induced EMF: $$\epsilon = - \frac{d\Phi_{m}}{dt}$$ |
| ----------------------------------------------------------------- | -------------------------------------------------- |

### Induced Fields


| ![[Pasted image 20240409112318.png\|400]] |
| ----------------------------------------- |

- The figure shows a conducting loop in an increasing magnetic field.
- According to Lenz's Law, there is an induced current in the counterclockwise direction.
- Something has to act on the charge carriers to make them move, so we infer that there must be an induced electric field tangent to the loop at all points.

- Recall, $W_{ext} = \Delta U_{E} = q\Delta V$
- Associate: $\Delta V \rightarrow \epsilon$
- Then, $\epsilon  = \frac{W_{ext}}{q}$ where $W_{ext} = \int_{\text{loop}}dW$ and $dW = \vec{F_{E}}\cdot d\vec{s} = q\vec{E}\cdot d\vec{s}$$$W_{ext} = \int_\text{loop} q\vec{E}\cdot d\vec{s} =  q \int_\text{loop} \vec{E}\cdot d\vec{s}$$
- Then, $\epsilon = \frac{W_{ext}}{q} = \frac{q}{q} \int_\text{loop} \vec{E} \cdot d\vec{s}$$$\epsilon =  \oint \vec{E}\cdot d\vec{s} = - \frac{d\Phi_{m}}{dt}$$
	- This is Faraday's Law.

### Transformers
- A transformer sends an alternating emf $V_{1}$ through the primary coil.
- This causes an oscillating magnetic flux through the secondary coil and an induced emf $V_{2}$
- This induced emf of the secondary coil is delivered to the load: $$V_{2} = \frac{N_{2}}{N_{1}}V_{1}$$
- Step-up transformers with $N_{2} \gt\gt N_{1}$ can boost the voltage of a generator up to several hundred thousand volts.
- Delivering power with smaller currents and higher voltages reduces losses to resistance in the wires.
- High-voltage transmission lines carry electric power to urban areas, where step-down transformers ($N_{2} \lt\lt N_{1}$) lower the voltage to 120$V$.

# Inductors and Inductance
- **Inductor**: solenoid inside a circuit
	- store energy in magnetic fields
	- ![[Pasted image 20240416105228.png]]
	- Ideal: $R = 0$ if $I = \text{ constant}$
	- Inductance ($L$): $$L = \frac{\Phi_{B}}{I}$$
	- With $N$ coils, area $A$, field $B$, then $$\Phi_{B} = NBA$$where $B = \frac{\mu_{0}NI}{l}$ 
	- Substituting, we obtain: $$\Phi_{B}= N(\frac{\mu_{0}NI}{l})A = \frac{\mu_{0}N^{2}IA}{l}$$$$L = \frac{\Phi_{B}}{I}$$$$L = \frac{\mu_{0}N^{2}A}{l}$$
	- SI Unit for inductance: **Henry** ($H$)
		- $1 H = 1 \frac{Wb}{A} = 1 \frac{T\cdot m^{2}}{A}$
	- Schematic symbol: ![[Pasted image 20240416105745.png|100]]
	- When current changes, $$\epsilon_{\text{coil}} = \frac{-d\Phi_{B}}{dt} \text { where } \Phi_{B} = LI$$
	- Substituting, $\epsilon_{\text{coil}} = \frac{-d}{dt}(LI) \text { where } L = \text { constant}$$$E_{coil} = -L \frac{dI}{dt}$$
	- Associate $\epsilon_\text{coil}$ with $\Delta V_{L}$: $$\Delta V_{L}= -L \frac{dl}{dt}$$
## Potential Difference across an inductor
- When current increases, flux increases going to the right. 
- ![[Pasted image 20240416111044.png]]
- Induced emf $\Delta V_{L}$ must be opposite to the current in the solenoid: $$\Delta V_{L} =  -L \frac{dl}{dt}$$
- When current decreases, flux decreases going to the left.
- ![[Pasted image 20240416110706.png]]

## Energy in an inductor:
$$P_\text{elec} = I\Delta V \text { where } \Delta V = \Delta V_{L} = -L \frac{dI}{dt}$$$$P_\text{elec} = I\Delta V_{L} = I\left(-L \frac{dI}{dt}\right)$$$$P_\text{elec} = -LI \frac{dI}{dt}$$
- Note: 
	- $P_\text{elec} \lt 0$ since $I$ is losing energy
	- Energy lost by $I$ is stored in the inductor.
	- Inductor: $$$P_{L} = \frac{dU_{L}}{dt} = -P_\text{elec}$$$$P_{L} = - \left(-LI \frac{dI}{dt} \right)$$$$P_{L}= +LI \frac{dI}{dt} = \frac{dU_{L}}{dt}$$$$\frac{dU_{L}}{dt} = +LI \frac{dI}{dt}$$$$\frac{d}{dt} (dU_{L}) = \frac{d}{dt} (LIdI)$$Then, $dU_L = LIdI$, so: $$U_{L}= \frac{1}{2} LI^{2}$$which is the energy in the $B$-field of a conductor. 
	- Analogous to: $U_{C} = \frac{1}{2}CV^{2} = \frac{Q^{2}}{2C}$
		- $\vec{E}$-field in a capacitor
### LC Circuits
- Capacitor with initial charge $Q_{0}$, and inductor, and a switch.
- ![[Pasted image 20240417105511.png]]
- The switch has been open for a long time, so there is no current in the circuit.
- The charge and current oscillate in a way that is analogous to a mass on a spring. 
- Calculations: 
	- Loop rule: $$\Delta V_{C} + \Delta V_{L} = 0$$$$\frac{Q}{C} -L \frac{dI}{dt} = 0$$where $I = \frac{-dQ}{dt}$ since Q comes from capacitor.
		- $Q$: charge on $C$
		- $I$: current i n $L$
	- Then, $$\frac{dI}{dt} = \frac{d}{dt}I = \frac{d}{dt} (\frac{-dQ}{dt})$$$$\frac{dI}{dt}= \frac{-d^{2}Q}{dt^{2}}$$
	- Substituting,$$\frac{Q}{C} - L \left(\frac{d^{2}Q}{dt^{2}}\right)= 0$$$$\frac{d^{2}Q}{dt^{2}}= \left(\frac{-1}{LC}\right)Q$$
- An LC circuit is an *electric oscillator*
- Charge on upper plate is $Q = Q_{0}\cos\omega t$ and the current through the inductor is $I = I_\text{max}\sin\omega t$, where $$\omega = \sqrt{\frac{1}{LC}}$$

### LR Circuit
- Inductor and resistor in series
- Initially, steady current $I_{0}$ driven through LR circuit by external battery
- Current through circuit decays exponentially, with time constant $\tau  = \frac{L}{R}$
- ![[Pasted image 20240417111425.png]]
- Calculations:
	- Current $I_{0}$ at $t = 0$. $I(t)$ after.
	- Loop rule: $$\Delta V_{R} + \Delta V_{L} = 0$$$$-RI - L \frac{dI}{dt} = 0$$
	- Separate variables: $\frac{dI}{I} = \frac{-R}{L}dt$ $$\int_{I_{0}}^{I} \frac{dI}{I} = \frac{-R}{L} \int_{0}^{t} dt$$$$\frac{I}{I_{0}}= e^\frac{-Rt}{L}$$
	- Time constant: $\tau = \frac{L}{R}$$$I(t) = I_{0}\left(e^\frac{-t}{\tau}\right)$$
