# 6.1 Rotational Kinetic Energy

Rotational kinetic energy is the energy an object has because it spins, and it equals $`K {\mathrm{rot}}=\frac{1}{2} I \omega^{2}`$. It depends on how the mass is spread out (rotational inertia $`I`$) and how fast the object turns (angular velocity $`\omega`$), and like all energy it is a scalar.

## Why This Matters for the AP Physics C: Mechanics Exam

Unit 6 carries 10 to 15 percent of the exam weighting, and rotational kinetic energy is the foundation for the rest of the unit. You will use it on both multiple-choice and free-response questions when you set up energy conservation for rolling objects, compare spinning systems, and predict how changing mass distribution or angular speed changes energy.

This topic also supports the kind of reasoning the exam rewards. When you justify a claim on free response, naming an equation or principle is not enough. You need to explain the steps that connect $`K_{\mathrm{rot}}=\frac{1}{2} I \omega^{2}`$ to your conclusion, such as why one disk has more energy than another.

## Key Takeaways

- Rotational kinetic energy is $`K_{\mathrm{rot}}=\frac{1}{2} I \omega^{2}`$, where $`I`$ is in kg·m² and $`\omega`$ is in rad/s.
- This equation parallels translational kinetic energy $`\frac{1}{2}mv^2`$, with $`I`$ playing the role of mass and $`\omega`$ the role of speed.
- For a point mass at radius $`r`$, rotational kinetic energy reduces exactly to $`\frac{1}{2}mv^2`$ because $`v = r\omega`$.
- An object can rotate about its center of mass and also move through space, so total kinetic energy is $`K_{\mathrm{trans}} + K_{\mathrm{rot}}`$.
- A system with a stationary center of mass can still have rotational kinetic energy because its individual points are moving.
- Rotational kinetic energy is a scalar, so it adds directly without direction or components.

## The Rotational Kinetic Energy Equation

Rotational kinetic energy is the energy an object has because of its rotation. Just as translational kinetic energy depends on mass and speed, rotational kinetic energy depends on rotational inertia and angular velocity.

```math
K_{\mathrm{rot}}=\frac{1}{2} I \omega^{2}
```

Each symbol has a specific meaning:

- $`K_{\mathrm{rot}}`$ is the rotational kinetic energy, in joules (J)
- $`I`$ is the rotational inertia, also called moment of inertia, in kg·m²
- $`\omega`$ is the angular velocity, in radians per second (rad/s)

Notice how closely this mirrors the translational form $`K = \frac{1}{2}mv^2`$. Rotational inertia $`I`$ takes the place of mass, and angular velocity $`\omega`$ takes the place of linear speed. That parallel is worth keeping in mind, because most rotational equations have a translational twin.

## Why It Equals Translational Kinetic Energy

Rotational kinetic energy is not a separate kind of energy. It is the regular kinetic energy of all the little pieces of a spinning object, added up.

For a single point mass moving in a circle of radius $`r`$, the linear speed relates to angular velocity by $`v = r\omega`$. Substitute that into the rotational energy equation:

```math
K_{\mathrm{rot}} = \frac{1}{2}I\omega^2 = \frac{1}{2}(mr^2)\omega^2 = \frac{1}{2}m(r\omega)^2 = \frac{1}{2}mv^2
```

So for a point mass, rotational kinetic energy is exactly its translational kinetic energy. For an extended object, you can think of it as integrating over every mass element, which is why the rotational inertia $`I`$ captures how the mass is distributed.

## Total Kinetic Energy of a System

Many real objects spin and move at the same time. The total kinetic energy is the sum of the rotational part (about the center of mass) and the translational part (motion of the center of mass):

```math
K_{\mathrm{total}} = K_{\mathrm{rot}} + K_{\mathrm{trans}} = \frac{1}{2}I\omega^2 + \frac{1}{2}Mv_{cm}^2
```

This applies to systems like:

- A ball rolling down a ramp (moving forward and spinning)
- A frisbee flying through the air while spinning
- A car wheel during normal driving

Splitting the kinetic energy into these two pieces makes energy conservation problems much easier to set up, which is exactly what you will do later in this unit with rolling.

## Rotation With a Stationary Center of Mass

A system can have rotational kinetic energy even when its center of mass is not going anywhere. When $`v_{cm} = 0`$, the total kinetic energy is just the rotational part:

```math
K_{\mathrm{total}} = K_{\mathrm{rot}} = \frac{1}{2}I\omega^2
```

The center of mass sits still, but the individual points inside the object still move with speed $`v = r\omega`$, so they carry kinetic energy. Examples include:

- A spinning top holding its position
- A flywheel turning on a fixed axle
- Earth rotating on its axis

This is why a spinning object can store a lot of energy even when it looks like it is staying in one place.

## Rotational Kinetic Energy Is a Scalar

Like every form of energy, rotational kinetic energy is a scalar. It has a magnitude but no direction. That means you can:

- Add energy values directly, with no components
- Apply energy conservation without worrying about vector directions

This is different from other rotational quantities, which are vectors:

- Angular velocity $`\vec{\omega}`$
- Angular momentum $`\vec{L}`$
- Torque $`\vec{\tau}`$

The scalar nature is a big reason energy methods are often cleaner than force or torque methods for spinning systems.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

- Always convert angular velocity to rad/s before plugging into $`\frac{1}{2}I\omega^2`$. A common given is rpm, which you must convert.
- Pick the correct rotational inertia for the shape and axis. The energy is only as accurate as your $`I`$.
- For objects that both spin and translate, write $`K_{\mathrm{total}} = \frac{1}{2}I\omega^2 + \frac{1}{2}Mv_{cm}^2`$ and use $`v = r\omega`$ when it rolls without slipping.

### Free Response

- When you justify a claim, connect the equation to the conclusion. For example, "Since $`K_{\mathrm{rot}} = \frac{1}{2}I\omega^2`$ and the second disk has larger $`I`$ at the same $`\omega`$, it has more rotational kinetic energy."
- Compare quantities carefully. If $`\omega`$ is the same but mass moves farther from the axis, $`I`$ increases, so $`K_{\mathrm{rot}}`$ increases.

### Common Trap

- Forgetting to include rotational energy when an object rolls. A rolling object stores energy in both spinning and moving, so leaving out $`\frac{1}{2}I\omega^2`$ gives the wrong final speed.

## Practice Problem 1: Basic Rotational Kinetic Energy

A solid disk with mass 2.0 kg and radius 0.15 m rotates at 300 rpm (revolutions per minute). Calculate the rotational kinetic energy of the disk.

**Solution**

Identify the equation and the given values:

- $`K_{\mathrm{rot}} = \frac{1}{2}I\omega^2`$
- Mass: $`m = 2.0`$ kg
- Radius: $`r = 0.15`$ m
- Angular velocity: $`\omega = 300`$ rpm

Convert angular velocity to radians per second: $`\omega = 300 \text{ rpm} \times \frac{2\pi \text{ rad}}{1 \text{ rev}} \times \frac{1 \text{ min}}{60 \text{ s}} = 31.4 \text{ rad/s}`$

For a solid disk, the rotational inertia is: $`I = \frac{1}{2}mr^2 = \frac{1}{2} \times 2.0 \text{ kg} \times (0.15 \text{ m})^2 = 0.0225 \text{ kg·m}^2`$

Now calculate the rotational kinetic energy: $`K_{\mathrm{rot}} = \frac{1}{2}I\omega^2 = \frac{1}{2} \times 0.0225 \text{ kg·m}^2 \times (31.4 \text{ rad/s})^2 = 11.1 \text{ J}`$

The rotational kinetic energy of the disk is 11.1 joules.

## Practice Problem 2: Total Kinetic Energy

A 0.5 kg solid sphere with radius 0.1 m rolls without slipping down a ramp. If its center of mass has a speed of 2.0 m/s at the bottom, what is the total kinetic energy of the sphere?

**Solution**

Because the sphere rolls without slipping, calculate both the translational and rotational kinetic energy.

Given information:

- Mass: $`m = 0.5`$ kg
- Radius: $`r = 0.1`$ m
- Translational speed: $`v = 2.0`$ m/s

For a solid sphere, the rotational inertia is: $`I = \frac{2}{5}mr^2 = \frac{2}{5} \times 0.5 \text{ kg} \times (0.1 \text{ m})^2 = 0.002 \text{ kg·m}^2`$

For rolling without slipping, $`v = r\omega`$, so: $`\omega = \frac{v}{r} = \frac{2.0 \text{ m/s}}{0.1 \text{ m}} = 20 \text{ rad/s}`$

Now calculate each part:

1. Translational: $`K_{\mathrm{trans}} = \frac{1}{2}mv^2 = \frac{1}{2} \times 0.5 \text{ kg} \times (2.0 \text{ m/s})^2 = 1.0 \text{ J}`$
2. Rotational: $`K_{\mathrm{rot}} = \frac{1}{2}I\omega^2 = \frac{1}{2} \times 0.002 \text{ kg·m}^2 \times (20 \text{ rad/s})^2 = 0.4 \text{ J}`$

The total kinetic energy is: $`K_{\mathrm{total}} = K_{\mathrm{trans}} + K_{\mathrm{rot}} = 1.0 \text{ J} + 0.4 \text{ J} = 1.4 \text{ J}`$

The total kinetic energy of the rolling sphere is 1.4 joules.

## Common Misconceptions

- **Misconception:** Rotational kinetic energy is a vector.  
  **Actually:** It is a scalar. Angular velocity, angular momentum, and torque are vectors, but energy is not.
- **Misconception:** If the center of mass isn't moving, there's no kinetic energy.  
  **Actually:** A spinning object with a fixed center of mass still has rotational kinetic energy because its points are moving.
- **Misconception:** I can plug rpm straight into the formula.  
  **Actually:** You must convert to rad/s first, or your answer will be far off.
- **Misconception:** Rotational inertia is just the mass.  
  **Actually:** $`I`$ depends on how the mass is distributed relative to the axis, not only on how much mass there is. The same object can have different $`I`$ values about different axes.
- **Misconception:** A rolling object only has translational kinetic energy.  
  **Actually:** Rolling objects store energy in both translation and rotation, so you must include $`\frac{1}{2}I\omega^2`$.
- **Misconception:** Rotational kinetic energy is something separate from regular kinetic energy.  
  **Actually:** It is just the summed kinetic energy of all the moving pieces of a spinning object.

## Related AP Physics C: Mechanics Guides

- [6.4 Conservation of Angular Momentum](04-conservation-of-angular-momentum.md)
- [6.6 Motion of Orbiting Satellites](06-motion-of-orbiting-satellites.md)
- [6.2 Torque and Work](02-torque-and-work.md)
- [6.3 Angular Momentum and Angular Impulse](03-angular-momentum-and-angular-impulse.md)
- [6.5 Kinetic Energy of a System with Translational and Rotational Motion](05-kinetic-energy-of-a-system-with-translational-and-rotational-motion.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| angular velocity | The rate of change of angular position with respect to time, represented by the symbol ω. |
| center of mass | The point in a system where the entire mass can be considered to be concentrated for the purposes of analyzing motion and forces. |
| kinetic energy | The energy possessed by an object due to its motion, equal to one-half the product of its mass and the square of its velocity. |
| rigid system | A collection of objects or particles that maintain fixed distances from each other and rotate as a single unit. |
| rotational inertia | A measure of an object's resistance to changes in its rotational motion about a given axis; depends on both the mass of the object and how that mass is distributed relative to the axis of rotation. |
| rotational kinetic energy | The kinetic energy of a rigid system due to its rotation about an axis, calculated as half the product of rotational inertia and the square of angular velocity. |
| scalar | A physical quantity that has only magnitude and no direction. |

## Frequently Asked Questions

### How do you calculate rotational kinetic energy?

Use K\_rot = 1/2 I omega^2, where I is rotational inertia and omega is angular velocity. The result is energy in joules.

### What does moment of inertia do in rotational kinetic energy?

Moment of inertia, or rotational inertia, measures how mass is distributed around the rotation axis. A larger I means more rotational kinetic energy for the same angular velocity.

### How is rotational kinetic energy like translational kinetic energy?

K\_rot = 1/2 I omega^2 parallels K = 1/2 mv^2. Rotational inertia plays the role of mass, and angular velocity plays the role of speed.

### Can an object have rotational kinetic energy if its center of mass is at rest?

Yes. A rigid system can spin about its center of mass while the center of mass stays fixed. The individual points move, so the system has rotational kinetic energy.

### What is total kinetic energy for a rolling object?

For a rolling rigid object, total kinetic energy is the translational kinetic energy of the center of mass plus the rotational kinetic energy about the center of mass.

### Is rotational kinetic energy a scalar?

Yes. Rotational kinetic energy is a scalar, so it has no direction and adds directly with other energy terms.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-6/1-rotational-kinetic-energy/study-guide/Y5pLDWQTbxH05tCF](https://fiveable.me/ap-physics-c-mechanics/unit-6/1-rotational-kinetic-energy/study-guide/Y5pLDWQTbxH05tCF)</sub>
