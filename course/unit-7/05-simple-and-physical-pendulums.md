# 7.5 Simple and Physical Pendulums

## AP Physics C 7.5 Simple vs Physical Pendulum Summary

A physical pendulum is any rigid body that swings about a pivot and undergoes simple harmonic motion for small angles, with period $`T_{\text{phys}}=2\pi\sqrt{\frac{I}{mgd}}`$. A simple pendulum is the special case where all the mass can be modeled as a point a distance $`\ell`$ from the pivot, giving $`T_p=2\pi\sqrt{\frac{\ell}{g}}`$. A torsion pendulum oscillates because a twisted wire supplies a restoring torque proportional to angular displacement.

## Why This Matters for the AP Physics C: Mechanics Exam

This topic pulls together rotational dynamics, torque, moment of inertia, and SHM into one model, so it tests whether you can connect ideas across units. You will use Newton's second law in rotational form to set up the differential equation that describes the motion, then read off the angular frequency and period.

Because pendulums are easy to set up and time, they show up in experimental reasoning. You might design a procedure to measure $`g`$ from a pendulum's period, or determine an unknown moment of inertia from a measured period. Free-response work often asks you to derive an expression, sketch a graph of angular displacement versus time, or justify a claim using the period equation and its functional dependence.

## Key Takeaways

- A physical pendulum is a rigid body oscillating about a pivot; the restoring torque comes from gravity acting at the center of mass: $`\tau=-mgd\sin\theta`$.
- The small-angle approximation $`\sin\theta\approx\theta`$ turns the torque equation into the SHM differential equation $`\frac{d^2\theta}{dt^2}=-\omega^2\theta`$ with $`\omega=\sqrt{\frac{mgd}{I}}`$.
- The physical pendulum period is $`T_{\text{phys}}=2\pi\sqrt{\frac{I}{mgd}}`$, where $`I`$ is the moment of inertia about the pivot and $`d`$ is the pivot-to-center-of-mass distance.
- A simple pendulum is the special case with $`I=m\ell^2`$ and $`d=\ell`$, giving $`T_p=2\pi\sqrt{\frac{\ell}{g}}`$ with the mass canceling out.
- A torsion pendulum follows $`I\alpha=-\kappa\Delta\theta`$, so $`T=2\pi\sqrt{\frac{I}{\kappa}}`$, with the torsion constant playing the role of a spring constant.
- The small-angle approximation only holds for small displacements (roughly under about 10 degrees); larger angles break the SHM model.

## Properties of Physical Pendulums

### Rigid Body Oscillation

A physical pendulum is a rigid body that swings about a fixed pivot point. When you displace it from equilibrium and release it, it undergoes simple harmonic motion for small angular displacements. The restoring torque comes from gravity acting at the center of mass. The motion is oscillatory, and under the small-angle approximation that oscillation is SHM.

- The body can have any shape (rod, disk, irregular object)
- The mass is distributed throughout the body rather than concentrated at a point
- The pivot point can be located anywhere relative to the center of mass
- The restoring torque is provided by gravity acting on the center of mass

Unlike a simple pendulum, which models the mass as a point at the end of a massless string, a physical pendulum accounts for the actual distribution of mass throughout the object.

### Period Derivation for Small Amplitudes

When a physical pendulum is displaced by a small angle from equilibrium, it experiences a restoring torque that drives the oscillation. You analyze this with rotational dynamics.

The relevant equation for the period is:

```math
T_{\text{phys}}=2 \pi \sqrt{\frac{I}{m g d}}
```

where $`I`$ is the moment of inertia about the pivot point, $`m`$ is the mass, $`g`$ is the acceleration due to gravity, and $`d`$ is the distance between the pivot and the center of mass.

The derivation follows from analyzing the torque on the pendulum:

1. The restoring torque is:
   
   ```math
   \tau=-m g d \sin \theta
   ```
   
   where $`\theta`$ is the angular displacement from equilibrium.
2. For small angles, use the approximation $`\sin \theta \approx \theta`$, which simplifies the torque to:
   
   ```math
   \tau=-m g d \theta
   ```
3. Apply Newton's second law in rotational form:
   
   ```math
   \tau=I \alpha
   ```
   
   where $`\alpha`$ is the angular acceleration.
4. Substitute and rearrange:
   
   ```math
   -m g d \theta=I \alpha
   ```
   
   ```math
   \alpha = -\frac{mgd}{I}\theta
   ```
5. Since angular acceleration is the second derivative of angular displacement:
   
   ```math
   \frac{d^{2} \theta}{d t^{2}}=-\frac{m g d}{I} \theta=-\omega^{2} \theta
   ```
   
   where $`\omega`$ is the angular frequency.
6. This differential equation describes simple harmonic motion with angular frequency:
   
   ```math
   \omega = \sqrt{\frac{mgd}{I}}
   ```
7. The period is related to the angular frequency by:
   
   ```math
   T=\frac{2\pi}{\omega}
   ```
8. Therefore:
   
   ```math
   T_{\text{phys}}=2 \pi \sqrt{\frac{I}{m g d}}
   ```

This shows that the period depends on the moment of inertia, which captures the mass distribution of the object, rather than treating it as a point mass.

## Simple Pendulum vs Physical Pendulum

A simple pendulum is a special case of a physical pendulum in which the bob is modeled as a point mass $`m`$ located a distance $`\ell`$ from the pivot on a massless string or rod. Because all the mass is concentrated at a single point, the analysis simplifies.

For small angular displacements, the restoring torque is:

```math
\tau = -mg\ell \sin\theta \approx -mg\ell\theta
```

Using $`I = m\ell^2`$ for a point mass at distance $`\ell`$ from the pivot, Newton's second law for rotation gives:

```math
m\ell^2 \frac{d^2\theta}{dt^2} = -mg\ell\theta
```

Dividing both sides by $`m\ell^2`$:

```math
\frac{d^2\theta}{dt^2} = -\frac{g}{\ell}\theta
```

This is the SHM differential equation with $`\omega = \sqrt{\frac{g}{\ell}}`$. The period is therefore:

```math
T_{p}=2 \pi \sqrt{\frac{\ell}{g}}
```

Notice that the mass cancels out entirely. The period of a simple pendulum depends only on its length and the acceleration due to gravity. You can also recover this result directly from the physical pendulum formula by substituting $`I = m\ell^2`$ and $`d = \ell`$:

```math
T = 2\pi\sqrt{\frac{m\ell^2}{mg\ell}} = 2\pi\sqrt{\frac{\ell}{g}}
```

This confirms that the simple pendulum is just a specific instance of the more general physical pendulum model.

## Torsion Pendulum

A torsion pendulum is another rotational SHM system. Instead of gravity providing the restoring torque, a twisted wire or rod provides a restoring torque proportional to the angular displacement. A common example is a horizontal disk suspended from a wire attached to its center of mass. When you rotate the disk and release it, it oscillates back and forth about the wire's axis in the horizontal plane.

The equation of motion for a torsion pendulum is:

```math
I\alpha = -\kappa \Delta\theta
```

where $`I`$ is the rotational inertia about the axis of rotation, $`\kappa`$ is the torsion constant of the wire (analogous to a spring constant), and $`\Delta\theta`$ is the angular displacement from equilibrium.

This can be rewritten as:

```math
\frac{d^2\theta}{dt^2} = -\frac{\kappa}{I}\theta
```

This has the standard SHM form, so the angular frequency and period are:

```math
\omega = \sqrt{\frac{\kappa}{I}} \qquad T = 2\pi\sqrt{\frac{I}{\kappa}}
```

Notice the structural similarity to a mass-spring system: the torsion constant $`\kappa`$ plays the role of the spring constant $`k`$, and the rotational inertia $`I`$ plays the role of mass $`m`$.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

When you set up a physical pendulum problem, get these three pieces right before plugging in:

- $`I`$ is the moment of inertia about the pivot, not about the center of mass. If you only know the center-of-mass value, use the parallel-axis theorem to shift to the pivot.
- $`d`$ is the straight-line distance from the pivot to the center of mass.
- The small-angle approximation must apply, or the period equation does not hold.

### Free Response

Common tasks include deriving $`T_{\text{phys}}=2\pi\sqrt{\frac{I}{mgd}}`$ from $`\tau=-mgd\sin\theta`$ and Newton's second law in rotational form, sketching angular displacement versus time, and predicting how the period changes when you move the pivot, change the length, or change the mass distribution. When asked how period responds to a change, reason from the functional dependence in the equation rather than recomputing from scratch.

### Experimental Reasoning

Pendulums are good for lab questions. You might plan a procedure to measure $`g`$ from the period of a simple pendulum, or determine an unknown moment of inertia from the measured period of a physical pendulum. Plotting period-related data with appropriate axes can let you extract a slope tied to $`g`$, $`I`$, or the torsion constant.

## Practice Problem 1: Physical Pendulum Period

A uniform rod of length L = 1.0 m and mass M = 2.0 kg is pivoted at one end and allowed to swing as a physical pendulum. Calculate the period of small oscillations. (Recall that the moment of inertia of a rod about its end is $`I = \frac{1}{3}ML^2`$.)

**Solution**

Use the period formula for a physical pendulum:

```math
T_{\text{phys}}=2 \pi \sqrt{\frac{I}{m g d}}
```

For a uniform rod pivoted at one end:

- The moment of inertia about the pivot is $`I = \frac{1}{3}ML^2 = \frac{1}{3} \times 2.0 \text{ kg} \times (1.0 \text{ m})^2 = \frac{2.0}{3} \text{ kg·m}^2`$
- The center of mass is at the middle of the rod, so $`d = \frac{L}{2} = 0.5 \text{ m}`$
- The mass is $`m = 2.0 \text{ kg}`$
- Acceleration due to gravity is $`g = 9.8 \text{ m/s}^2`$

Substituting:

```math
T_{\text{phys}}=2 \pi \sqrt{\frac{\frac{2.0}{3} \text{ kg·m}^2}{2.0 \text{ kg} \times 9.8 \text{ m/s}^2 \times 0.5 \text{ m}}}
```

```math
T_{\text{phys}}=2 \pi \sqrt{\frac{\frac{2.0}{3}}{2.0 \times 9.8 \times 0.5}} = 2 \pi \sqrt{\frac{1}{3 \times 9.8 \times 0.5}}
```

```math
T_{\text{phys}}=2 \pi \sqrt{\frac{1}{14.7}} = 2 \pi \times 0.261
```

```math
T_{\text{phys}} = 1.64 \text{ seconds}
```

The period of small oscillations for this physical pendulum is about 1.64 seconds.

## Common Misconceptions

- **Misconception:** A heavier pendulum swings with a different period just because it is heavier.  
  **Actually:** A heavier pendulum does not swing with a different period just because it is heavier. For a simple pendulum the mass cancels, and for a physical pendulum the period depends on how the mass is distributed (through $`I`$ and $`d`$), not on the total mass alone.
- **Misconception:** The $`d`$ is the full length of the object.  
  **Actually:** The $`d`$ in $`T_{\text{phys}}=2\pi\sqrt{\frac{I}{mgd}}`$ is the distance from the pivot to the center of mass, not the full length of the object.
- **Misconception:** The moment of inertia in the period formula can be taken about the center of mass without applying the parallel-axis theorem.  
  **Actually:** The moment of inertia in the period formula must be taken about the pivot. Using the center-of-mass value without applying the parallel-axis theorem gives the wrong period.
- **Misconception:** The simple pendulum period formula is exact for all angles.  
  **Actually:** The simple pendulum period $`T_p=2\pi\sqrt{\frac{\ell}{g}}`$ is not exact for all angles. It only works under the small-angle approximation, so large swings change the period.
- **Misconception:** Increasing the amplitude within the small-angle range changes the period.  
  **Actually:** Increasing the amplitude (within the small-angle range) does not change the period. Amplitude and period are independent in SHM.
- **Misconception:** A torsion pendulum's restoring torque comes from gravity, so its period uses $`g`$ and $`d`$.  
  **Actually:** A torsion pendulum's restoring torque comes from the twisted wire, not from gravity, so its period uses the torsion constant rather than $`g`$ and $`d`$.

## Related AP Physics C: Mechanics Guides

- [7.1 Defining Simple Harmonic Motion (SHM)](01-defining-simple-harmonic-motion-shm.md)
- [7.3 Representing and Analyzing SHM](03-representing-and-analyzing-shm.md)
- [7.2 Frequency and Period of SHM](02-frequency-and-period-of-shm.md)
- [7.4 Energy of Simple Harmonic Oscillators](04-energy-of-simple-harmonic-oscillators.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| angular acceleration | The rate of change of angular velocity with respect to time, represented by the symbol α. |
| angular displacement | The change in angular position of a rotating object, measured in radians. |
| center of mass | The point in a system where the entire mass can be considered to be concentrated for the purposes of analyzing motion and forces. |
| equilibrium position | The position where the spring force on an object is zero and the object-spring system is at rest. |
| moment of inertia | A measure of a rigid body's resistance to rotational acceleration about a given axis, represented by the symbol I. |
| physical pendulum | A rigid body that exhibits simple harmonic motion when displaced from its equilibrium position and allowed to oscillate. |
| restoring torque | The torque that acts to return a displaced physical pendulum back toward its equilibrium position. |
| simple harmonic motion | A special case of periodic motion in which a restoring force proportional to displacement causes an object to oscillate about an equilibrium position. |
| simple pendulum | A special case of a physical pendulum in which the hanging object is modeled as a point mass at a fixed distance from the pivot point. |
| small-angle approximation | The approximation that sin(θ) ≈ θ for small angular displacements, used to simplify the analysis of pendulum motion. |
| torsion pendulum | A system undergoing simple harmonic motion where the restoring torque is proportional to the angular displacement of a rotating system. |

## Frequently Asked Questions

### What is the difference between a simple and physical pendulum?

A simple pendulum models the mass as a point at the end of a massless string or rod, while a physical pendulum is a rigid body with mass distributed throughout it. A simple pendulum is a special case of a physical pendulum.

### What is the physical pendulum formula?

For small oscillations, the physical pendulum period is T = 2π√(I/mgd), where I is the moment of inertia about the pivot, m is mass, g is gravitational field strength, and d is the distance from the pivot to the center of mass.

### What is the simple pendulum period formula?

For small angles, a simple pendulum has period T = 2π√(l/g), where l is the length from the pivot to the point mass. The mass cancels, so the period depends on length and gravity, not the bob’s mass.

### Why does a physical pendulum use moment of inertia?

A physical pendulum has mass spread through a rigid body, so its rotational inertia affects how it oscillates. The period formula uses I about the pivot to account for that mass distribution.

### When can you use the small-angle approximation for pendulums?

Use the small-angle approximation when the angular displacement is small enough that sin θ ≈ θ. That approximation turns the restoring torque equation into the SHM differential equation used to derive the period formulas.

### What is a torsion pendulum in AP Physics C?

A torsion pendulum is a rotational SHM system where a twisted wire provides a restoring torque proportional to angular displacement. Its equation can be written Iα = -κΔθ, with period T = 2π√(I/κ).

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-7/5-simple-and-physical-pendulums/study-guide/m0lcXe33VLYhg8EA](https://fiveable.me/ap-physics-c-mechanics/unit-7/5-simple-and-physical-pendulums/study-guide/m0lcXe33VLYhg8EA)</sub>
