# 6.5 Kinetic Energy of a System with Translational and Rotational Motion

When an object both moves and spins, its total kinetic energy is the sum of translational energy ($`\frac{1}{2}mv {cm}^2`$) and rotational energy ($`\frac{1}{2}I\omega^2`$). For rolling without slipping, the no-slip condition $`v {cm} = r\omega`$ links the two motions, and static friction does no work, so mechanical energy is conserved.

## Why This Matters for the AP Physics C: Mechanics Exam

Rolling problems pull together ideas from energy, rotation, and friction, so they are common in both multiple-choice and free-response questions. You will often need to combine conservation of energy with the no-slip condition to find a speed, acceleration, or energy partition. Free-response answers usually ask you to explain your reasoning, not just write an equation, so being able to say *why* static friction does no work or *why* energy is conserved is just as important as the math. Unit 6 carries a 10 to 15 percent weighting on the exam, and rolling sits right in the middle of it.

## Key Takeaways

- Total kinetic energy of a rolling object: $`K_{tot} = K_{trans} + K_{rot} = \frac{1}{2}mv_{cm}^2 + \frac{1}{2}I\omega^2`$.
- Rolling without slipping gives three constraints: $`\Delta x_{cm} = r\Delta\theta`$, $`v_{cm} = r\omega`$, and $`a_{cm} = r\alpha`$.
- In ideal rolling without slipping, static friction is a constraint force that does no work, so mechanical energy is conserved.
- When slipping, $`v_{cm} = r\omega`$ no longer holds, and kinetic friction dissipates mechanical energy as thermal energy.
- The energy split between translational and rotational depends on the moment of inertia, so objects with more mass farther from the axis roll slower down a ramp.
- Rolling friction is outside the scope of this course.

## Total Kinetic Energy

When an object both moves linearly and rotates, you have to account for both forms of energy. The total kinetic energy is the complete energy of motion for the system, found by adding the two pieces:

```math
K_{\text{tot}} = K_{\text{trans}} + K_{\text{rot}}
```

Where:

- $`K_{\text{tot}}`$ is the total kinetic energy of the system
- $`K_{\text{trans}}`$ is the translational kinetic energy, $`\frac{1}{2}mv_{cm}^2`$ (with $`m`$ the mass and $`v_{cm}`$ the center-of-mass speed)
- $`K_{\text{rot}}`$ is the rotational kinetic energy about the center of mass, $`\frac{1}{2}I\omega^2`$ (with $`I`$ the moment of inertia and $`\omega`$ the angular velocity)

This combined approach lets you analyze motions like a rolling ball, where both the moving center of mass and the spinning contribute to the overall energy. Both terms are scalars, so you simply add them.

## Rolling Without Slipping

### Key Relationships

Rolling without slipping is the ideal case where an object rolls along a surface with no relative motion at the point of contact. The contact point is instantaneously at rest, which ties the linear motion of the center of mass directly to the rotation.

These equations connect translational and rotational motion:

- $`\Delta x_{\mathrm{cm}} = r \Delta \theta`$ : linear displacement equals radius times angular displacement
- $`v_{\mathrm{cm}} = r \omega`$ : linear velocity equals radius times angular velocity
- $`a_{\mathrm{cm}} = r \alpha`$ : linear acceleration equals radius times angular acceleration

These relationships show up in everyday scenarios such as:

- A car wheel rolling on a road
- A ball rolling down a ramp
- A cylinder rolling on a flat surface

### Friction in Ideal Rolling

In perfect rolling without slipping, static friction matters but works in a special way.

Static friction in rolling motion:

- Acts as a constraint force rather than a dissipative force
- Keeps the contact point momentarily at rest, preventing slipping
- Does no work on the system, because there is no displacement at the point where the force is applied
- Lets mechanical energy be conserved, unlike kinetic friction

Because no energy is lost, you can use conservation of mechanical energy to solve rolling-without-slipping problems.

## Rolling with Slipping

### Center of Mass vs Rotational Motion

When slipping occurs, the clean link between linear and angular motion breaks down.

In rolling with slipping:

- The equations $`\Delta x_{\mathrm{cm}} = r \Delta \theta`$, $`v_{\mathrm{cm}} = r \omega`$, and $`a_{\mathrm{cm}} = r \alpha`$ no longer apply
- The center-of-mass motion and the rotational motion become decoupled
- You must track translational and rotational components separately
- The contact point has real motion relative to the surface

This happens when a vehicle's wheels spin on ice or when a ball is thrown with backspin onto a surface.

### Kinetic Friction in Slipping

When slipping occurs, kinetic friction takes over and changes the energy picture.

Kinetic friction during slipping:

- Converts mechanical energy into thermal energy
- Does negative work on the system, lowering its total mechanical energy
- Often drives the system toward eventual rolling without slipping
- Acts at a contact point that moves relative to the surface, which is why it dissipates energy

Track this energy loss when you predict the final state of an object that starts out slipping.

**Boundary note:** Rolling friction is not covered on the AP Physics C: Mechanics exam.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

For a rolling-without-slipping object, the fastest path is usually conservation of energy. Set the change in gravitational potential energy equal to the gain in total kinetic energy, then substitute $`\omega = v_{cm}/r`$ so everything is in terms of $`v_{cm}`$:

```math
mg\Delta h = \frac{1}{2}mv_{cm}^2 + \frac{1}{2}I\omega^2
```

The moment of inertia controls how the energy splits. A larger $`I`$ (more mass farther from the axis) sends more energy into rotation, leaving less for translation, so that object reaches a lower speed at the bottom of a ramp.

### Free Response

Stating "by conservation of energy" or "because of friction" is not enough to support a stronger score. Walk through the steps: name the principle, state why it applies (for example, static friction does no work in pure rolling so mechanical energy is conserved), then connect that to your claim. If two objects roll down the same ramp, explain the role of $`I`$ in the energy partition before declaring which is faster.

### Common Trap

Watch the friction type. Static friction in pure rolling does no work, so energy is conserved. Kinetic friction during slipping does negative work and removes mechanical energy. Mixing these up will break your energy bookkeeping.

## Common Misconceptions

- **Misconception:** Friction always removes energy.  
  **Actually:** In rolling without slipping, static friction does no work because the contact point is instantaneously at rest. Only kinetic friction during slipping dissipates energy.
- **Misconception:** $`v_{cm} = r\omega`$ always works.  
  **Actually:** This holds only while rolling without slipping. Once an object slips, the center-of-mass and rotational motions are decoupled and you cannot use it.
- **Misconception:** All round objects roll down a ramp at the same speed.  
  **Actually:** The energy split depends on $`I`$. A hoop ($`I = mr^2`$) ends up slower than a solid sphere ($`I = \frac{2}{5}mr^2`$) of the same mass and radius, because the hoop puts more energy into rotation.
- **Misconception:** A rolling object's energy is purely translational.  
  **Actually:** You must add the rotational term. Using only $`\frac{1}{2}mv^2`$ undercounts the total kinetic energy.
- **Misconception:** Heavier objects always roll faster.  
  **Actually:** When you solve down an incline, the mass cancels out. The final speed depends on the shape (through $`I/mr^2`$) and the height, not the mass.

## Practice Problem 1: Total Kinetic Energy

A solid sphere with mass 2.0 kg and radius 0.10 m rolls without slipping at a speed of 5.0 m/s. Calculate the total kinetic energy of the sphere. The moment of inertia of a solid sphere is $`I = \frac{2}{5}mr^2`$.

**Solution**

Find both the translational and rotational pieces, then add them:

1. Translational kinetic energy: $`K_{trans} = \frac{1}{2}mv^2 = \frac{1}{2} \times 2.0 \text{ kg} \times (5.0 \text{ m/s})^2 = 25.0 \text{ J}`$
2. Since the sphere rolls without slipping, use $`v_{cm} = r\omega`$ to get the angular velocity: $`\omega = \frac{v_{cm}}{r} = \frac{5.0 \text{ m/s}}{0.10 \text{ m}} = 50.0 \text{ rad/s}`$
3. Rotational kinetic energy: $`K_{rot} = \frac{1}{2}I\omega^2 = \frac{1}{2} \times \frac{2}{5}mr^2 \times \omega^2`$ $`K_{rot} = \frac{1}{2} \times \frac{2}{5} \times 2.0 \text{ kg} \times (0.10 \text{ m})^2 \times (50.0 \text{ rad/s})^2`$ $`K_{rot} = \frac{1}{2} \times \frac{2}{5} \times 2.0 \text{ kg} \times 0.01 \text{ m}^2 \times 2500 \text{ rad}^2/\text{s}^2`$ $`K_{rot} = 10.0 \text{ J}`$
4. Total kinetic energy: $`K_{tot} = K_{trans} + K_{rot} = 25.0 \text{ J} + 10.0 \text{ J} = 35.0 \text{ J}`$

## Practice Problem 2: Rolling Without Slipping

A solid cylinder with mass 5.0 kg and radius 0.20 m starts from rest and rolls without slipping down a 30° incline. If it travels 3.0 m along the incline, what is its final speed? The moment of inertia of a solid cylinder is $`I = \frac{1}{2}mr^2`$.

**Solution**

Because the cylinder rolls without slipping, mechanical energy is conserved, so use conservation of energy:

1. The initial energy is gravitational potential energy: $`E_i = mgh_i`$
2. The final energy is translational plus rotational kinetic energy (taking the final height as the reference): $`E_f = \frac{1}{2}mv^2 + \frac{1}{2}I\omega^2`$
3. Height change from the distance along the incline: $`\Delta h = 3.0 \text{ m} \times \sin(30°) = 3.0 \text{ m} \times 0.5 = 1.5 \text{ m}`$
4. By conservation of energy: $`mg\Delta h = \frac{1}{2}mv^2 + \frac{1}{2}I\omega^2`$
5. For rolling without slipping, $`\omega = \frac{v}{r}`$, so: $`mg\Delta h = \frac{1}{2}mv^2 + \frac{1}{2}\left(\frac{1}{2}mr^2\right)\left(\frac{v}{r}\right)^2`$ $`mg\Delta h = \frac{1}{2}mv^2 + \frac{1}{4}mv^2`$ $`mg\Delta h = \frac{3}{4}mv^2`$
6. Solving for $`v`$: $`v^2 = \frac{4g\Delta h}{3} = \frac{4 \times 9.8 \text{ m/s}^2 \times 1.5 \text{ m}}{3} = 19.6 \text{ m}^2/\text{s}^2`$ $`v = 4.43 \text{ m/s}`$

Notice the mass cancels out, so the final speed depends only on the shape of the object and the height dropped.

## Related AP Physics C: Mechanics Guides

- [6.4 Conservation of Angular Momentum](04-conservation-of-angular-momentum.md)
- [6.6 Motion of Orbiting Satellites](06-motion-of-orbiting-satellites.md)
- [6.1 Rotational Kinetic Energy](01-rotational-kinetic-energy.md)
- [6.2 Torque and Work](02-torque-and-work.md)
- [6.3 Angular Momentum and Angular Impulse](03-angular-momentum-and-angular-impulse.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| angular acceleration | The rate of change of angular velocity with respect to time, represented by the symbol α. |
| angular displacement | The change in angular position of a rotating object, measured in radians. |
| angular velocity | The rate of change of angular position with respect to time, represented by the symbol ω. |
| center of mass | The point in a system where the entire mass can be considered to be concentrated for the purposes of analyzing motion and forces. |
| energy dissipation | The process by which mechanical energy is lost from a system, in this case due to the work done by kinetic friction during slipping. |
| frictional force | The force that acts at the contact point between a rolling object and a surface; in ideal rolling without slipping, it does not dissipate energy from the system. |
| kinetic energy | The energy possessed by an object due to its motion, equal to one-half the product of its mass and the square of its velocity. |
| kinetic friction | The friction force exerted on a system moving relative to a surface, which acts at the point of contact and dissipates energy. |
| rolling while slipping | Motion of a system where the center of mass translation and rotational motion are not directly related due to slipping relative to a surface. |
| rolling without slipping | A motion condition where a rolling object's translational and rotational motions are related such that the contact point with the surface has zero velocity, with no relative sliding between the object and surface. |
| rotational kinetic energy | The kinetic energy of a rigid system due to its rotation about an axis, calculated as half the product of rotational inertia and the square of angular velocity. |
| rotational motion | The motion of a rigid body or point rotating about a fixed axis, characterized by angular displacement, velocity, and acceleration. |
| slipping | A situation in which two surfaces in contact are moving relative to each other. |
| translational motion | The motion of an object's center of mass moving from one location to another through space. |

## Frequently Asked Questions

### What is the total kinetic energy of a rolling object?

The total kinetic energy is the sum of translational and rotational kinetic energy: K\_tot = 1/2 mv\_cm^2 + 1/2 I omega^2.

### What is the rolling without slipping condition?

Rolling without slipping means the center-of-mass motion and rotation are linked by v\_cm = r omega, a\_cm = r alpha, and delta x\_cm = r delta theta.

### Does static friction do work during rolling without slipping?

In ideal rolling without slipping, static friction does no work on the system because the contact point is instantaneously at rest.

### What happens to energy when an object rolls while slipping?

When slipping occurs, v\_cm = r omega no longer applies and kinetic friction dissipates mechanical energy as thermal energy.

### How does moment of inertia affect rolling speed?

A larger moment of inertia puts more energy into rotation and leaves less for translation, so objects with more mass far from the axis roll slower down the same height.

### Is rolling friction tested on AP Physics C: Mechanics?

No. The CED boundary states that rolling friction is beyond the scope of AP Physics C: Mechanics.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-6/5-kinetic-energy-of-a-system-with-translational-and-rotational-motion/study-guide/tpS8vdLgJ6AQpm2V](https://fiveable.me/ap-physics-c-mechanics/unit-6/5-kinetic-energy-of-a-system-with-translational-and-rotational-motion/study-guide/tpS8vdLgJ6AQpm2V)</sub>
