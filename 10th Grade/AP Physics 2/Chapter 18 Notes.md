# 18.1 - The Ray Model Of Light
- ignores diffraction, valid as long as apertures through which light passes are larger than 1 mm
- **light ray**: line in direction along which energy of light flows
	- laser is a good approximation
	- travel in straight lines and can cross (don't interact with each other)
		- can be reflected or refracted and interfere between new materials 
		- within material, light can be scattered or absorbed.
	- An object is a source of light rays
		- rays originate from every point; each point sends rays in all directions
	- The eye sees by focusing a bundle of rays
# 18.2 - Reflection
- Specular Reflection: smooth and shiny (e.g. piece of polished metal)
- incident and reflected rays in the plane of the page
	- ![[Pasted image 20230327145854.png]]
- Law of Reflection: angle of incidence is equal to angle of reflected ray
### The Plane Mirror
- **Plane Mirror**: flat mirror
- Rays from a point reflect according to law of reflection\
 ![[Pasted image 20230327145641.png]]
- The dashed lines indicate that the rays appear to come from point P'. All reflected rays appear to come from point P'.
- Point P', from which the reflected rays diverge, is called the **virtual image** of P.
![[Pasted image 20230327145957.png]]
- The image is virtual because no rays actually leave point P', but the light waves act exactly as if they were.
- **image distance** s' is equal to the **object distance** s:
	- $$s' = s \text{ (Plane mirror)}$$
![[Pasted image 20230327150551.png]]
	1. Rays from each point on the object spread out in all directions and strike every point on the mirror. Only a very few of these rays enter your eye, but the other rays are very real and might be seen by other observers.
	2. Rays from points P and Q enter your eye after reflecting from different areas of the mirror. This is why you can 't always see the full image of an object in a very small mirror
# 18.3 - Refraction
- Two things happen when a light ray crosses the boundary between air and glass
	- 1) part of the light reflects from boundary, obeying law of reflection.
	- 2) part of the light continues into the second medium. *transmitted instead of reflected*, as it crosses the boundary.
- **Refraction:** Transmission of light from one medium to another, but with a change in direction
- The angle between the incident ray and the normal is the *angle of incidence*
- The angle on the transmitted side compared to the normal is the *angle of refraction*.
- **Snell's Law**: $$n_{1} \sin \theta_{1} = n_{2} \sin \theta_{2}$$
	- n = index of refraction

### Examples of refraction
- When a ray is transmitted into a material with a higher n, it bends to make a smaller angle.
- into a lower index medium, larger angle with normal

### Total Internal Reflection
- **Total internal reflection** (TIR): when a light ray is unable to refract through a boundary. Instead, 100% of the lights reflected from the boundary
- Crossing a boundary into a lower n material, the ray bends away from the normal.
- As angle $\theta_{1}$ increases, the refraction angle $\theta_{2}$ approaches $90\degree$
- The fraction of light energy transmitted decreases while the reflection increases.
- **Critical angle** $\theta_{c}$ is reached when $\theta_{2} = 90\degree$
- $$\theta_{c} = \sin^{-1} \left(\frac{n_{2}}{n_{1}}\right)$$
	- critical angle of incidence for TIR
- **There is no critical angle and no total internal reflection if $n_{2} > n_{1}$
### Fiber Optics
- use TIR for transmission of light through optical fibers
- Light rays into the narrow diameter glass fiber, but then strike the inside wall of the fiber at an angle of incidence approaching 90$\degree$ 
# 18.4 - Image Formation by Refraction
- Take a ruler in an aquarium:
	- To your eye, the rays appear to diverge not from the object at point P instead of point P'
	- **The ruler appears closer than it really is because of the refraction of light at the boundary**
- **optical axis**: line through the object perpendicular to the boundary
- The distance is common to both the incident and refracted rays.
	- $$l = s \tan \theta_{1} = s' \tan \theta_{2}$$
			- $$s' = \frac{\tan\theta_{1}}{\tan\theta_{2}} = \frac{\sin\theta_{1}}{\sin\theta_{2}} = \frac{n_{2}}{n_{1}}$$$$s' = \frac{n_{2}}{n_{1}}s$$
- **lens**: transparent material that uses refraction of light rays at curved surfaces to form an image.
	- **converging lens**: rays refract *towards* the optical axis
		- thicker at the center than the edges
		- incoming rays refract toward optical axis at both the first (air-glass) and second (glass-air) boundaries.
			- as the ray enters the lens, it bends toward normal and optical axis
			- as it leaves, it bends away from the normal, but still toward optical axis.
		- **focal point**: The incoming rays initially parallel to the optical axis converge at the same point
		- **focal length**: distance from the focal point from the lens ($f$)
	- **diverging lens**: rays refract *away* from the optical axis
		- thinner at the center, thicker at the edges
		- **the focal length is the distance from the lens to the point at which rays parallel to the optical axis converge or from which they appear to diverge**
# 18.5 - Thin Lenses: Ray Tracing
- pictorial method used to understand image formation
### Converging Lenses
- **thin lens**: idealized lens whose thickness is zero and lies entirely in a plane (**lens plane**)
- **all refraction occurs as the rays cross the lens plane, and all distances are measured from the lens plane.**
### Real Images
- If rays diverge from an object at point P and interact with a lens such that they converge at point P', the rays generate a **real image**.
- **object plane**: all points on the object in the same plane
	- converge to image points in the image plane
- inverted image
### Magnification
- image can be larger or smaller than the object depending on the location and focal length of the lens
- the **magnification** describes the *orientation* of the image relative to the object and its size. $$m = \frac{-s'}{s}$$
	- 1. The absolute value of m gives the ratio of image height to object height: $\frac{h'}{h} = |m|$
	- 2. A positive value of m indicates that the image is upright relative to the object. A negative value of m indicates that the image is inverted.
- #### Sign Convention
	- Real image: $s' > 0$
	- Virtual image: $s' < 0$
	- $$m = \frac{-s'}{s}$$
	- $$|m| = \frac{h'}{h}$$
### Virtual Images
- When the object is inside the focal point, a ray passing through the focal point (to the left) would never reach the lens.
- The rays emerging parallel to the axis entered the lens along a line passing through a near focal point.

### Diverging Lenses
- thinner at its center than at the edges.
- always make virtual images.

# 18.6 - Image Formation with Spherical Mirrors
- **Spherical Mirrors**: curved mirrors, can be used to form images
- **concave mirror**: parallel waves reflect off the mirror and pass through the focal point.
	- the law of reflection says any incoming ray will reflect at the same angle but on the other side of the optical axis
	- incoming rays reflect off the **mirror plane**, not off the curved surface of the mirror for the ray trace.
- **convex mirror**: parallel rays reflect off the mirror and appear to have come from a point behind the mirror.

### Convex Mirrors
- Any ray initially parallel to the optical axis will reflect as though it came from the focal point
- Any ray directed toward the focal point will reflect parallel to the optical axis
- Any ray directed at the center of the mirror will reflect at an equal angle on the opposite side of the optical axis.
- No rays converge at image point 
- **creates an image that is upright and much smaller than the actual object**
# 18.7 - Thin Lens Equation

![[Pasted image 20230331144141.png]]
- The ratios of any two similar sides are the same: $$\frac{h'}{h} = \frac{s'-f}{f}$$
- Also: $$\frac{h'}{h} = \frac{s'}{s}$$
- Therefore: $$\frac{s'}{s} = \frac{s'-f}{f}$$
- **$$\frac{1}{s} + \frac{1}{s'} = \frac{1}{f}$$
	- Thin-lens equation (also works for mirrors) relating object and image distances to focal length
![[Pasted image 20230331145155.png]]
- Converging: Convex lens or concave mirror
	- outside focal point: *real image*, m is *negative,* s' is *positive*
	- inside focal point: *virtual images*, *upright*, m is *positive*, s' is *negative*
- Diverging: Concave lens or convex mirror
	- No difference between object inside or outside focal point
	- **always gives *virtual* images that are *upright*, m is *positive* and s' is *negative***