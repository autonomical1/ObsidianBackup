# Classical Relativity
- Relativity Principles = all inertial reference frames (IRFs) hold
- Reference frames ($S, S'$)
	- $S$ = rest frame
	- $S'$ = moving frame
- Reference frames use coordinates: ($x, x', y, y', z, z', t, t'$)
	- $$x = x't vt$$
		- difference in frame position after time $t$ assuming constant $v$
- $$u_{x}= \frac{dx'}{dt} = \frac{d}{dt}(x -vt)= \frac{dx}{dt} -v = u_{x} -v$$
	- $$u'_{x} = u_{x} - v$$
		- velocities of moving frames and object is subtracted
- $$a_{x} = a'_{x} \text{ because IRFs have the no acceleration}$$
## Galilean Invariance of Newton's Laws
- Solve problem using Newton's laws in frame $S$
- Add constant velocity (transformation to frame $S'$)
- Solve problem using Newton's Laws in frame $S'$
	- yields same result with constant $v$ added ($v$ addition)

#### Assumptions
- Common sense:
	- universal (invariant) time
	- invariant mass
	- invariant force ($ma$)
- (not always valid)

## Problem with Galilean Relativity
- Maxwell's equations
	- ![[Pasted image 20240813115641.png]]
		- Gauss's law for Magnetism indicates that magnetic monopoles do not exist.
- Maxwell's correction term in Ampere's Law ($\mu_{0}\epsilon_{0} \frac{\partial E}{\partial t}$) is essential for the existence of **electromagnetic radiation**.
- Correction term predicts speed, $c$, of EM waves in free space is $c = \frac{1}{\sqrt{\epsilon_{0}\mu_{0}}}$, confirmed by experiment
- Predict single value for $c$, but Galilean transformations yield diff values in diff reference frames.

## Ether
- In the 19th century, all known waves were mechanical waves, propagated through some physical medium.
- EM waves assumed to propagate through medium
	- This was called *ether* - assumed to permeate all space
	- Assumed speed $c$ predicted by Maxwell's equations is speed of waves w.r.t. ether
	- This means that Maxwell's equations do not satisfy Relativity Principle
	- Einstein's Second Postulate of Special Relativity would later resolve this.

## Experimentation
- Several experiments:
	- attempts to measure differences in $c$ with different orientations
	- should depend on Earth's orientation w.r.t ether
	- goal was to find speed of ether w.r.t. earth.
- Michelson-Morley Experiment
	- Designed to measure the speed of the ether w.r.t. the earth
	- Analogy: Boats crossing a stream with a current.
		- Both boats travel same distance, $L$, from point $A$ to point $B$ and bacl.
		- Objective: determine whether there is a time difference due to the difference in the path taken by each boat.
	- Boat 1: Travels straight across the stream, perpendicular to the current
		- Effective speed: $$v_{1} = \sqrt{c^{2}-v^{2}}$$
		- Time taken to cross: $$t_{1} = \frac{2L}{v_{1}}= \frac{2L}{\sqrt{c^{2}-v^{2}}} = \frac{2L}{c} (\frac{1}{\sqrt{1-(\frac{v^{2}}{c^{2}})}}$$

# Postulates of Special Relativity
## First Postulate: (Relativity Principle)
- The laws of Physics have the same form in all inertial reference frames.

## Second Postulate: (Constancy of Light Speed)
- EMR propagates through space with definite speed, $c$, independent of relative speed between source and observer.

### Notes
- First postulate dismisses concept of ether and any preferred frame of reference. consistent with null result of Michelson-Morley experiment
- Second postulate appears to violate common sense. Velocities should always be additive.
	- Resolves issue with Maxwell's theory, EMR has single, definite speed $c$, in **any IRF**

### Events
- One consequence of the second postulate - time can't be an absolute quantity
- Define *event* s something that occurs at a particular place (spatial position) and time.
	- Time difference between two events and whether they are simultaneous depends on reference frame of the observer.
	- Why? - light travel time 

### Simultaneity
- Let two events occur at points $A$ and $B$ with observer $O$ in the middle. Since distance $OA = OB$, light flashes reach $O$ at same time - observer sees both events as simultaneous.
- Definition: light signals reach observer in that reference at the same time.
- Question: If 2 events are simultaneous i one frame, will they be simultaneous in another frame?

### Einstein's Train
- Consider train platform in frame $S$ and train in frame $S'$ moving with speed $v$ relative to $S$.
- Let points $A'$ and $B'$ represent ends of a train car with observer $O'$ in the middle of the train car.
- At time $t = 0$ , points $A$, $B$, and $O$ in frame $S$ coincide with points $A'$, $B'$, and $O'$ in the frame $S'$.
- Conclusions:
	- simultaneity is relative, not absolute
	- since all IRFs equivalent by 1st postulate (no preferred IRF), both observers at $O$ and $O'$ are correct, observations equally valid.
	- Lack of agreement noticeable as $v$ approaches $c$

## Time Dilation
- Lack of simultaneity in different reference frames suggests time is not absolute and may pass at different rates in different reference frames.
- Gedanken experiment:
	- Consider spaceship travelling past Earth at high speed.
	- On ship, light ray reflected off a mirror, round-trip transit time recorded.
	- By the second postulate: 
		- $$\Delta t = \frac{2D'}{c} - \frac{2\sqrt{D^{2}+L^{2}}}{c} \text { where } L = \frac{v\Delta t}{2}$$
		- Substituting for $L$ and simplifying, we obtain: $$\Delta t = 1/\sqrt{1- \frac{v^{2}}{c^{2}}}(\frac{2D}{c})$$
			- Transit time: $$\Delta t_{0} = \frac{2D}{c}$$
		- Therefore, $$\Delta t = \frac{1}{\sqrt{1- \frac{v^{2}}{c^{2}}}} \Delta t_{0}$$
		- The quantity occurs very often in Special Relativity, so we define the *relativistic gamma-factor* as: $$\gamma\equiv \frac{1}{\sqrt{1- \frac{v^{2}}{c^{2}}}}$$
			- Note that $\gamma = 1$ if $v = 0$ and $\gamma \gt 1$ if $v \gt 0$, so $\gamma \geq 1$ always. 
	- Our final result for light transit time in rest frame of earth is: $$\Delta t= \gamma\Delta t_{0} \text { where } \gamma \geq 1$$
		- this is time dilation
	- Notes:
		- Observers always note time running at a normal rate in their own frame of reference.
		- In frames moving relative to an observer, time will appear to run slower.
		- For non-relativistic speeds, $v \lt\lt 1$ and $\Delta t \approx \Delta t_{0}$. Therefore, time dilation is only noticeable when relativistic speeds are involved. 

### Proper Time
- The quantity $\Delta t_{0}$ is known as the **proper time** and is the time interval between two events in the reference frame where those events occur at the **same location in space.**
- The proper time is the shortest possible time interval between two events and the time interval will be larger when measured in any other frame of reference.

## The Twin Paradox
- Consider two young twins of the same age
- One lives on earth, one travels far away from Earth at a relativistic speed and returns. 
- Because of time dilation, Earth-bound twin will observe time running more slowly in the space-bound twin's reference frame. 
- **_Conclusion_**: Upon returning to Earth, space-bound twin will age less than Earth-bound twin because less time elapsed in their rest frame. 
- **Paradox**: 
	- Can't the space-bound twin make the same argument about the earth bound twin?
	- if observations in all reference frames are equally valid, then each twin should observe the other as being younger, but that can't possibly be the case
- **Resolution**:
	- There are two problems with this scenario:
		- Space bound twin must accelerate in order to turn around for the return voyage to the earth which means that their reference frame is not always inertial. 
		- *Length contraction* will also occur.

## The Relativistic Doppler Effect
- Recall that for sound, if there is relative motion between the source of the sound and the observer, the frequency detected by the observer is different from that measured at the source.
- The situation for light (EMR) is similar with two primary differences.
	- EMR does not require a physical medium, hence, no effects due to motion of the medium w.r.t. source and observer as was the case with sound. 
	- Relativistic speeds are involved, so we must take relativistic effects (time dilation) into account in calculations.
- General: $$v = \lambda\cdot f \text{ (any wave)}$$$$\text{E-M : } c =\lambda f$$

### The Train/Tunnel Paradox:
- Consider a tunnel that is 800 feet long in its rest frame and a train that is 1000 feet long in its rest frame as shown below. 
- Tunnel has doors at either end that can be closed, goal is to contain entire train in the tunnel with both doors closed.
- Train has speed $0.8 \cdot c (\gamma = 1.67)$ w.r.t. tunnel rest frame.
- In rest frame of tunnel,
	- 
- 