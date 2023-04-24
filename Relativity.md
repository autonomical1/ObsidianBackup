### Principle: 
- Classical physics
- The laws of physics have the same form in all ***inertial*** **reference frames**
	- Reference frame: observer and a coordinate system
		- every observer makes observations according to the reference frame they're in
- Convention: "Rest Frame" ($s$)
	- reference frame at rest with respect to observer
		- "Moving" reference frame: $s'$
			- has speed $v$ relative to $s$
		- Origins $O$ and $O'$ coincide at time $t = t' = 0$
		- The rest frame of the Earth is inertial.
- Inertial reference frame
	- Newton's First Law holds
		- No acceleration between reference frames
- Laws of physics are the same in **all** inertial reference frames.
### Galilean Transformation
- Translate coordinates between $s$ and $s'$ 
	- $x = x' = 0$
	- at a later time $t$, $s'$ has moved a distance $vt$
	- That means: $x' = x - vt$
### The Problem with Galilean Relativity
- Maxwell's equations:
	- 1. Gauss's Law for $\overrightarrow{E}$: $\iint \overrightarrow{E} \cdot d\overrightarrow{A} = \frac{Q_{enc}}{\epsilon_{0}}$ 
	- 2. Gauss's Law for $\overrightarrow{B}$: $\iint \overrightarrow{B} \cdot d\overrightarrow{A} = 0$
	- 3. Faraday's Law: $\int \overrightarrow{E} \cdot d\overrightarrow{l} = \frac{-\partial\phi_{B}}{\partial t}$ 
	- 4. Ampere's Law: $\int \overrightarrow{B} \cdot d \overrightarrow{l} = \mu_{0} I$ 
		- after Maxwell's correction: $\int \overrightarrow{B} \cdot d \overrightarrow{l} = \mu_{0} I + \epsilon_{0}\mu_{0}\frac{-\partial\phi_{B}}{\partial t}$ 
- First published in 1861
- Final form in 1884
- Maxwell's correction predicts a speed $c = \frac{1}{\sqrt{\epsilon_{0}\mu_{0}}}$ for electromagnetic radiation

### Einstein's Postulates of Special Relativity 
- 1. **The laws of physics are the same in all inertial reference frames**
- 2. **The speed of light in a vacuum has the definitive speed, c, regardless of the motion of the source and observer.**

## Events
- Something that happens and produces a light pulse
	- Person (observer) standing a distance d away from a lightning pulse; lightning pulse strikes, sending a light pulse towards the observer. 
		- The event doesn't occur unless the observer sees it.
		- $$s = ct  \rightarrow t = \frac{s}{c} > 0$$

### Simultaneity
- 2 events are said to be simultaneous when observed at the same time.
- EX: 2 lightning strikes a distance s on both sides away from the observer
	- O (observer) sees A and B at the same time, so the events are simultaneous in S

### Special Relativity
- Time is no longer an absolute quantity
- 4-D space-time is ***invariant*** (doesn't change) in special relativity)
- Gamma factor: $\gamma == \frac{1}{\sqrt{\frac{1-v^{2}}{c^{2}}}}$
	- $\gamma \geq 1$ 
		- $\gamma = 1 \text{ only if } v = 0$
### Time Dilation: 
- Proper time: $\Delta t_{0}$
	- shortest time interval between two events
	- occurs in frame where the events occur at the same point in space
	- in a moving frame of reference - dilated time
		- $\Delta t = \gamma \Delta t_{0}$

### Length Contraction (Lorentz Contraction):
- Proper length $L_{0}$
- Largest measured distance between two events
- occurs in frame at rest with respect to the two events
- Other frames (moving with respect to the measurements) observe a contracted length: $$L = \frac{L_{0}}{\gamma}$$
- Ex: Spaceship travelling from Earth to Venus
	- Two events: 
		- 1. Leave Earth
		- 2. Arrive at Venus
	- Observers: 
		- S: Earth 
			- measures proper length $L_{0}$ 
			- measures dilated time
	- Earth: $v = \frac{L_{0}}{\Delta t'}$
	- Ship: 
		- proper time: $\Delta t_{0}$
		- contracted length: $L$
			- $v = \frac{L}{\Delta t_{0}}$

### Lorentz Transformations:
- Position:
	- $x = \gamma(x' + vt')$
	- $y = y'$
	- $z = z'$
	- $t = \gamma(t' + \frac{vx'}{c^{2}})$
- Note "folding" of spatial and temporal dimensions

### The Photoelectric Effect
- Heinrich Hertz
	- physicist
	- 1886-89: experimented with electromagnetic waves (EMR)
	- 1888: discovered UV radiation could discharge a charged electroscope
		- Metal sphere with metal leaves that move apart when charged
- **Photoelectric effect**: ability of electromagnetic waves to eject charges from a charged metallic object
- Philip Lenard: continued experimentation
- Classical Expectations:
	- Kinetic energy of the photoelectrons proportional to the intensity of the light striking the surface ($U_{e} \propto E^{2} \text{ or } B^{2}$)
	- Delay to get metal to "heat up"
	- Any frequency should eject electrons
- Experimental Observations:
	- Threshold frequency below which there are no photoelectrons emitted from the surface
	- Above the threshold frequency ($f_{0}$) the effect is *immediate*
	- Intensity increases number of electrons ejected, but not the kinetic energy
	- Kinetic energy increases with increasing frequency (shorter $\lambda$)
- 1899-1900: Max Planck
	- Investigated black body radiation
	- Ultraviolet Catastrophe
	- Solved with Planck radiation law
		- had to do something radical to solve it 
	- Proposed energy from electromagnetic waves was quantized
		- could only occur in discrete values/packets
	- Electromagnetic wave: $E = hf = \frac{hc}{\lambda}$
		- $h = 6.626 * 10^{-34} J \cdot s^{-1}$
		- Energies: $hf, 2hf, 3hf, ..., nhf$ 
- Einstein's explanation:
	- Electromagnetic radiation occurs in discrete bundles or packets of energy known as photons.
	- wave-icle
	- Intensity = more photons.
	- One-to-one coupling between photons and electrons
- Photon model: 
	- EMR in "packets of energy" - photons
	- $E_{\gamma} = hf = \frac{hc}{\lambda}$
	- One-to-one coupling between photons and electrons
	- Threshold frequency
		- every metal has a **work function**
			- $\phi$
			- minimum energy to liberate an electron from an atom
			- $\phi = hf_{0}$
			- depends on the metal used as the cathode
- Maximum kinetic energy: $K_{max} = hf - hf_{0}$
- Stopping potential: 
	- $eV_{stop} = K_{max}$ (in eV)
	- $V_{stop} = \frac{K_{max}}{e}$
### Matter Waves:
- Recall electromagnetic radiation has particle and wave characteristics
- Depends on dimensions of apparatus compared to $\lambda$ (ex. diffraction)
- Can objects that are classically a particle (electron) also have wave-like properties?
- ~1920, Prince Louis de Broglie proposed existence of matter waves
	- **all** objects have a characteristic wavelength
		- $\lambda = \frac{h}{p}$
			- where $p = mv$ is the *classical* momentum
			- De Broglie wavelength of the particle
	- Particle in a box: 
		- Consider a particle of mass $m$ confined to a region of space with some dimension $L$. 
		- Classically, particle bounces back and forth between x = 0 and x = L
		- Non-classically ($l \leq \lambda$)
			- Boundary condition: Matter wave must vanish at x = 0 and x = L.
		- First harmonic: $\lambda_{1} = 2L$
		- Second harmonic: $\lambda_{2} = L$
		- Third harmonic: $\lambda_{3} = \frac{2L}{3}$
		- **General**: $\lambda_{n} = \frac{2L}{n}$
			- n = 1, 2, 3, . . .
		- De Broglie wavelength: $\lambda_{n} = \frac{h}{p_{n}}$
			- $p_{n}= \frac{h}{\lambda_{n}} = \frac{nh}{2L}$
			- $p_{n} = \frac{nh}{2L}$
		- Energy: $K = \frac{1}{2} mv^{2} = \frac{p^{2}}{2m}$
			- Substituting for momentum: 
				- $K_{n} = \frac{p_{n}^{2}}{2m} = \frac{1}{2m}[\frac{nh}{2L}]^{2}$
				- $$K_{n} = \frac{n^{2}h^{2}}{8mL^{2}} \text{ where } K_{n} \propto n^{2} \text{ ; } n = 1, 2, 3, ...$$
					- L is the length of the particle in a box
				- Energies are **quantized**
				- Assumes $L \approx \lambda$ (on a small scale)
				- $E_{n} = n^{2}E_{1}$
				- $E_{1}$ : ground state energy
				- $E_{1} \gt 0$ 
				- $n$: quantum number (n = principle quantum number - describes energy level)


### Energy Level Diagrams
- useful visual representation of the quantized energies
- vertical axis represents energy (in eV)
- lowest rung is ground states, the highest rungs are the excited states
- If system drops energy levels, excess energy emitted in photons
- A quantum system in energy level $E_{i}$ that jumps down to energy level $E_{f}$ loses an energy: $\Delta E_{system} = |E_{f} - E_{i}|$ 
- The jump corresponds to the emission of a photon with frequency: $$f_{photon} = \frac{\Delta E_{system}}{h}$$
- If the system absorbs a photon, it can "jump up" to a higher energy level
- Energy jumps are called **transitions or quantum jumps**

### Atoms and Atomic Theory
- c. 1887, J.J. Thomson discovers the electron 
	- Found that $m_{e} \lt \lt m_{atom}$ 
- Atomic structure: some positive sphere about $10^{-10} m$ across with charge
	- "raisin cake model"
- Ernest Rutherford 
	- Found that $U$ could emit alpha and beta rays ($\alpha \text{ and } \beta$)
		- $\alpha$-ray (particle) $\rightarrow_2^4He$ 
		- $\beta$-ray (particle) $\rightarrow$ high energy $e^{-}$ 
	- Further suggest nuclear structure and nuclear stability/instability
	- Gold Foil experiment showed a very small very dense nucleus
### Rutherford Model: 
- Small dense nucleus surrounded by a "cloud" of electrons
- c. 1932: Neutron discovered ($n^{0}$)
- Atoms composed of : $p^{+}, e^{-}, n^{0}$
	- $m_{p} \approx m_{n} \approx 1800m_{e}$
- Nomenclature:
	- Atomic number: $Z$ (number of protons)
	- $N$ (number of neutrons)
	- $A$ (atomic mass) - ($p^{+} + n^{0}$)
		- Z + N
- Atomic mass unit (amu or u)
	- Mass of $_{6}^{12}C$ defined to be exactly 12 u
	- $1u = 1.66 \cdot 10^{-27} kg$ 
- Isotopes:
	- same element
	- different number of $n^{0}$
### Bohr Model of the Atom: 
- Problem with Rutherford Atom: accelerating charges emit electromagnetic radiation
	- The energy carried off by the waves cause the electrons to spiral into the nucleus
	- Rutherford atom is inherently unstable
- Adds quantization to the Rutherford model.
- According to Bohr's model, the electrons in an atom can exist in only certain *allowed orbits*. A particular arrangement of the electrons in these orbits are called **stationary states**.
- Stationary states: Stable electron orbits have specific, discrete energies
- 