# 6.2 Torque and Work

Torque does work on a rotating object when it acts through an angular displacement, and you find that work with $`W = \int {\theta 1}^{\theta 2} \tau \, d\theta`$. For constant torque this becomes $`W = \tau \Delta\theta`$, and on a torque versus angular position graph the work is just the area under the curve. These relationships connect rotational motion to energy transfer and work-energy reasoning.

## Why This Matters for the AP Physics C: Mechanics Exam

This topic is the rotational version of the work integral you learned for linear forces. On both the multiple-choice and free-response sections, you may need to set up and evaluate $`W = \int \tau \, d\theta`$, read work off a torque versus angle graph, or connect that work to a change in rotational kinetic energy. The exam often asks you to compare scenarios or justify whether a quantity goes up, down, or stays the same, so being able to explain the reasoning behind the math matters as much as getting a number. Watch your units too, since torque is in N·m but work comes out in joules.

## Key Takeaways

- Torque transfers energy into or out of a rigid system only when it acts over an angular displacement.
- Work done by a torque is $`W = \int_{\theta_1}^{\theta_2} \tau \, d\theta`$; use this whenever the torque changes with angle.
- For constant torque, the integral simplifies to $`W = \tau \Delta\theta`$.
- On a torque versus angular position graph, work equals the area under the curve. Area above the axis is positive work; area below is negative work.
- Torque in the direction of rotation does positive work (adds energy); torque opposing rotation does negative work (removes energy).
- Keep units straight: torque is measured in N·m, but the work it does is energy in joules.

## Energy Transfer by Torque

Torque is the rotational version of force, and it can move energy into or out of a rigid system when it acts through an angular displacement. If there is no rotation, the torque does no work, just like a force does no work without displacement.

- When torque points the same way as the rotation, it does positive work and adds energy to the system.
- When torque opposes the rotation, it does negative work and removes energy.
- The amount of energy transferred depends on both how strong the torque is and how far the object rotates.

As an application, pushing on a bike pedal applies torque that adds energy to the drivetrain and speeds it up. Brakes apply a torque that opposes the wheel's spin, doing negative work and slowing the wheel down.

## Work-Torque Relationship

To find the work done by a torque, integrate the torque over the angular displacement. This mirrors the $`W = \int F \, dx`$ relationship from linear motion.

```math
W=\int_{\theta_{1}}^{\theta_{2}} \tau \, d \theta
```

Where:

- $`W`$ is the work done by the torque (in joules)
- $`\tau`$ is the torque as a function of angular position (in N·m)
- $`\theta_{1}`$ and $`\theta_{2}`$ are the initial and final angular positions (in radians)

When the torque is constant, it pulls straight out of the integral and you get:

```math
W = \tau \Delta \theta
```

So the work is just the torque times the angular displacement it acts through. Use the full integral form whenever the torque changes as the object turns.

## Graphical Work Analysis

Graphing torque against angular position is a fast way to handle problems, especially when the torque is not constant.

When you plot torque versus angular position:

- The area under the curve is the work done by the torque.
- Area above the horizontal axis is positive work (energy added).
- Area below the axis is negative work (energy removed).

This is handy when the torque changes during the rotation. Instead of always grinding through an integral, you can find the area of triangles, rectangles, or other shapes under the curve to get the total work.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

- Read the problem to decide if the torque is constant or variable. Constant torque means $`W = \tau \Delta\theta`$; variable torque means set up $`W = \int \tau \, d\theta`$ with the right limits.
- Make sure your angular displacement is in radians before plugging in.
- If you find a change in rotational kinetic energy, you can connect it back to the work done by the net torque.

### Free Response

- Show the integral setup explicitly, including the limits $`\theta_1`$ and $`\theta_2`$, before evaluating.
- When you justify a claim, do not just name an equation. Explain the reasoning step that takes you from $`W = \int \tau \, d\theta`$ to your conclusion.
- When a graph is given, state that work equals the area under the torque versus angle curve, then compute that area.

### Common Trap

- Mixing up units: torque is N·m, but the work it does is reported in joules. They have the same base units, so label them carefully and do not call your work answer N·m.

## Practice Problem 1: Work Done by Constant Torque

A student applies a constant torque of 15 N·m to a wheel, causing it to rotate through an angle of 2.5 radians. How much work does the student do on the wheel?

**Solution**

Since the torque is constant, use the simplified equation:

```math
W = \tau \Delta \theta
```

Substitute the given values: $`W = 15 \text{ N·m} \times 2.5 \text{ rad}`$ $`W = 37.5 \text{ J}`$

The student does 37.5 joules of work on the wheel.

## Practice Problem 2: Work from a Variable Torque

A variable torque is applied to a rotating shaft according to the function $`\tau = 20 - 5\theta`$ N·m, where $`\theta`$ is in radians. Calculate the work done by this torque as the shaft rotates from $`\theta = 0`$ to $`\theta = 3`$ radians.

**Solution**

Because the torque changes with angle, integrate the torque function over the angular displacement:

```math
W = \int_{0}^{3} (20 - 5\theta) \, d\theta
```

```math
W = \left[20\theta - \frac{5\theta^2}{2}\right]_{0}^{3}
```

```math
W = \left(20 \times 3 - \frac{5 \times 3^2}{2}\right) - \left(20 \times 0 - \frac{5 \times 0^2}{2}\right)
```

```math
W = 60 - 22.5 - 0
```

```math
W = 37.5 \text{ J}
```

The work done by the variable torque is 37.5 joules.

## Common Misconceptions

- **Misconception:** Torque always does work.  
  **Actually:** It only does work when the object actually rotates through an angle. A torque applied with no angular displacement does zero work.
- **Misconception:** $`W = \tau \Delta\theta`$ works every time.  
  **Actually:** That shortcut only applies when the torque is constant. If torque depends on angle, you must integrate.
- **Misconception:** Angular displacement can be in degrees.  
  **Actually:** Use radians in these work and energy equations, or your answer will be wrong.
- **Misconception:** Torque and work are the same thing because both use N·m.  
  **Actually:** Torque is a rotational push measured in N·m; work is energy and is reported in joules. Keep the labels separate.
- **Misconception:** Area below the axis on a torque versus angle graph doesn't count.  
  **Actually:** That area represents negative work, meaning the torque is removing energy from the system, and you must subtract it.

## Related AP Physics C: Mechanics Guides

- [6.4 Conservation of Angular Momentum](04-conservation-of-angular-momentum.md)
- [6.6 Motion of Orbiting Satellites](06-motion-of-orbiting-satellites.md)
- [6.1 Rotational Kinetic Energy](01-rotational-kinetic-energy.md)
- [6.3 Angular Momentum and Angular Impulse](03-angular-momentum-and-angular-impulse.md)
- [6.5 Kinetic Energy of a System with Translational and Rotational Motion](05-kinetic-energy-of-a-system-with-translational-and-rotational-motion.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| angular displacement | The change in angular position of a rotating object, measured in radians. |
| energy transfer | The process by which energy moves into or out of a system through the action of forces or torques. |
| rigid system | A collection of objects or particles that maintain fixed distances from each other and rotate as a single unit. |
| torque | A measure of the rotational effect of a force on a rigid body, calculated as the product of the force component perpendicular to the position vector and the distance from the axis of rotation. |
| work | Energy transferred to or from a system by forces or torques acting on it. |

## Frequently Asked Questions

### How does torque do work?

A torque does work on a rigid system when it acts through an angular displacement. If there is torque but no angular displacement, no rotational work is done.

### What is the work done by torque formula?

For variable torque, W = integral from theta1 to theta2 of tau d theta. For constant torque, this simplifies to W = tau Delta theta.

### Why must angular displacement be in radians?

Radians make the rotational work equation consistent with energy units. When using W = tau Delta theta, Delta theta should be measured in radians.

### How do you find work from a torque versus angular position graph?

Work is the signed area under a torque versus angular position graph. Area above the axis is positive work, and area below the axis is negative work.

### When is work by torque positive or negative?

Torque does positive work when it acts in the direction of rotation and adds energy. It does negative work when it opposes rotation and removes energy.

### How does torque work connect to rotational kinetic energy?

The net work done by torque changes the rotational kinetic energy of the rigid system. This is the rotational version of the work-energy relationship.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-6/2-torque-and-work/study-guide/IDr6scmUlLJQ3Uub](https://fiveable.me/ap-physics-c-mechanics/unit-6/2-torque-and-work/study-guide/IDr6scmUlLJQ3Uub)</sub>
