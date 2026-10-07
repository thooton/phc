# 6.4 Conservation of Angular Momentum

Conservation of angular momentum says a system's total angular momentum about a chosen axis stays constant when the net external torque about that axis is zero. If angular momentum changes, the change equals the angular impulse applied to the system.

The AP Physics C move is choosing the right system. If all relevant torques are internal, total angular momentum is conserved; if a net external torque acts, angular momentum is transferred between the system and the environment.

## Sum of Angular Momenta

The total angular momentum of a system is found by combining the individual angular momenta of each part about a specific rotational axis.

- Angular momentum follows the principle of superposition - the total effect equals the sum of individual contributions
- For a system of particles, the total angular momentum is $`L_{total} = \sum L_i = \sum r_i \times p_i`$
- For extended objects, we can integrate over all mass elements: $`L = \int r \times v \, dm`$
- The direction of angular momentum follows the right-hand rule, perpendicular to both position and momentum vectors

When analyzing complex systems like planetary motion or rotating machinery, this summation approach allows us to track how angular momentum is distributed throughout the system.

## Changes in Angular Momentum

Angular momentum can only change when an external torque acts on the system.

- According to Newton's second law for rotation: $`\tau_{net} = \frac{d\vec{L}}{dt}`$
- When object A interacts with object B, the angular impulse exerted by A on B is equal in magnitude and opposite in direction to the angular impulse exerted by B on A. This follows from Newton's third law and means angular momentum is transferred between interacting parts of a system without changing the total angular momentum of the full isolated system.
- By carefully defining our system boundaries, we can create a closed system with no external torques
- In a closed system, the total angular momentum remains constant even as it redistributes among components
- Any change in a system's total angular momentum equals the net angular impulse applied: $`\Delta \vec{L} = \int \vec{\tau} \, dt`$

Angular momentum is conserved in all interactions when the full interacting system is considered. If one object gains angular momentum, another object or the surroundings must gain equal and opposite angular momentum so that the total angular momentum of the larger isolated system remains constant.

This principle explains why a spinning top eventually slows down (due to friction with the surface creating an external torque) while planets can orbit for billions of years with minimal change (negligible external torques).

## System Selection and Angular Momentum

Whether angular momentum changes depends on how the system is chosen. If the selected system includes all objects exerting torques on one another, then those torques are internal and cancel in the total angular momentum accounting. If the net external torque on the chosen system is zero, the system's total angular momentum remains constant. If the net external torque on the chosen system is nonzero, angular momentum is transferred between the system and the environment, so the system's angular momentum changes by the external angular impulse.

For example, consider a person standing on a freely rotating turntable who pushes off a heavy disk. If we choose the person alone as our system, the torque from the disk is external and the person's angular momentum changes. If we choose the person plus the disk plus the turntable as our system, all torques are internal and the total angular momentum of that combined system is conserved. The choice of system boundaries determines whether we see angular momentum as constant or as being transferred in or out.

Angular momentum is conserved in every interaction when the entire interacting system is included. A subsystem may gain or lose angular momentum, but the full system made of the subsystem plus its interaction partner(s) has constant total angular momentum if there is no net external torque on that full system.

## Angular Impulse

Angular impulse represents the cumulative effect of torque applied over time, changing an object's angular momentum.

- Mathematically defined as: $`\vec{J} = \int \vec{\tau} \, dt`$
- For constant torque: $`\vec{J} = \vec{\tau} \Delta t`$
- Units are $`\text{kg} \cdot \text{m}^2/\text{s}`$ (same as angular momentum)
- According to the impulse-momentum theorem for rotation: $`\vec{J} = \Delta \vec{L}`$
- Angular impulse is a vector quantity with the same direction as the torque that produced it

When a baseball bat strikes a ball, the angular impulse delivered depends on both the magnitude of the torque and how long the bat remains in contact with the ball.

**Qualitative graph skill:** On a graph of external torque vs. time, the area under the curve gives the angular impulse, which equals the change in angular momentum. If the net external torque is zero for an interval, the angular momentum vs. time graph is horizontal (constant) during that interval. If a constant nonzero torque is applied, the angular momentum vs. time graph is a straight line with a slope equal to that torque.

## Constant Angular Momentum

In a closed system with no external torques, the total angular momentum remains constant.

- Expressed mathematically as: $`\vec{L}_i = \vec{L}_f`$ or $`I_i\omega_i = I_f\omega_f`$
- Angular momentum can redistribute among components, but the total sum stays the same
- This principle applies to all scales, from atomic particles to galaxies
- Angular momentum must be defined about a specified rotational axis (or origin). For a chosen system, angular momentum about that axis is constant when the net external torque about that axis is zero.

A classic demonstration involves a person sitting on a rotating stool holding weights. When they extend their arms, their rotation slows; when they pull their arms in, they spin faster—all while maintaining constant angular momentum.

## Angular Speed in Nonrigid Systems

When a system's mass distribution changes relative to its rotation axis, its angular speed adjusts to conserve angular momentum.

- The relationship is governed by: $`I_i\omega_i = I_f\omega_f`$
- When moment of inertia decreases (mass moves closer to axis), angular speed increases
- When moment of inertia increases (mass moves away from axis), angular speed decreases
- The product $`I\omega`$ always remains constant in the absence of external torques

Figure skaters utilize this principle during spins. By pulling their arms and leg close to their body (reducing $`I`$), they dramatically increase their rotation speed ($`\omega`$) while maintaining the same angular momentum. No external torque is required for this change in angular speed; the skater's angular momentum stays constant because the shape change is entirely internal to the system.

## Angular Impulse Effects

Angular impulse determines how a system's rotation changes during interactions.

- For constant torque: $`\Delta \vec{L} = \vec{\tau} \Delta t`$
- For variable torque: $`\Delta \vec{L} = \int \vec{\tau} \, dt`$
- The final angular momentum equals initial angular momentum plus angular impulse: $`\vec{L}_f = \vec{L}_i + \vec{J}`$
- Angular speed after impulse can be calculated as: $`\omega_f = \frac{L_i + J}{I_f}`$

This concept explains phenomena like how a falling cat can reorient itself to land on its feet without violating conservation of angular momentum, by changing its body configuration in a specific sequence.

## Practice Problem 1: Figure Skater Spin

A figure skater spinning with her arms extended has a moment of inertia of 4.0 kg·m² and an angular velocity of 2.0 rad/s. She pulls her arms in, reducing her moment of inertia to 1.6 kg·m². What is her new angular velocity?

**Solution**

We can apply conservation of angular momentum since there are no external torques acting on the skater:

```math
L_i = L_f
```

```math
I_i \omega_i = I_f \omega_f
```

Rearranging to solve for the final angular velocity: $`\omega_f = \frac{I_i \omega_i}{I_f}`$

Substituting the given values: $`\omega_f = \frac{4.0 \text{ kg·m²} \times 2.0 \text{ rad/s}}{1.6 \text{ kg·m²}}`$ $`\omega_f = \frac{8.0 \text{ kg·m²·rad/s}}{1.6 \text{ kg·m²}}`$ $`\omega_f = 5.0 \text{ rad/s}`$

The skater's angular velocity increases from 2.0 rad/s to 5.0 rad/s when she pulls her arms in, demonstrating how decreasing moment of inertia increases angular velocity when angular momentum is conserved.

## Practice Problem 2: Angular Impulse

A wheel with moment of inertia 2.5 kg·m² is initially rotating at 10 rad/s. A constant torque of 5.0 N·m is applied to the wheel for 3.0 seconds. What is the wheel's final angular velocity?

**Solution**

To solve this problem, we need to find the change in angular momentum due to the angular impulse, then calculate the final angular velocity.

Step 1: Calculate the initial angular momentum. $`L_i = I\omega_i = 2.5 \text{ kg·m²} \times 10 \text{ rad/s} = 25 \text{ kg·m²/s}`$

Step 2: Calculate the angular impulse. $`J = \tau \Delta t = 5.0 \text{ N·m} \times 3.0 \text{ s} = 15 \text{ kg·m²/s}`$

Step 3: Find the final angular momentum. $`L_f = L_i + J = 25 \text{ kg·m²/s} + 15 \text{ kg·m²/s} = 40 \text{ kg·m²/s}`$

Step 4: Calculate the final angular velocity. $`\omega_f = \frac{L_f}{I} = \frac{40 \text{ kg·m²/s}}{2.5 \text{ kg·m²}} = 16 \text{ rad/s}`$

The wheel's angular velocity increases from 10 rad/s to 16 rad/s due to the applied torque.

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| angular impulse | The product of net torque and the time interval over which it acts, equal to the change in angular momentum of an object or system. |
| angular momentum | A measure of the rotational motion of an object or system, calculated as the product of moment of inertia and angular velocity, or as the cross product of position vector and linear momentum. |
| angular speed | The rate at which an object rotates about a rotational axis, measured in radians per unit time. |
| conservation of angular momentum | The principle that the total angular momentum of a system remains constant when the net external torque on the system is zero. |
| net external torque | The total rotational force applied to a system from outside its boundaries. |
| nonrigid system | A system whose shape or configuration can change, allowing mass to move closer to or farther from the rotational axis. |
| rotational axis | The fixed line or point about which a system rotates or is analyzed for angular motion. |
| system | A defined collection of objects whose energy and interactions are being analyzed. |

## Frequently Asked Questions

### What is conservation of angular momentum?

Conservation of angular momentum means a system's total angular momentum about a chosen axis stays constant when the net external torque about that axis is zero.

### When is angular momentum conserved in AP Physics C?

Angular momentum is conserved for a selected system when the net external torque on that system is zero. Internal torques can transfer angular momentum between parts without changing the total.

### What is the angular impulse formula?

Angular impulse is the integral of torque over time: J = integral tau dt. It equals the change in angular momentum, Delta L.

### How does moment of inertia affect angular speed?

If angular momentum is conserved, decreasing moment of inertia increases angular speed, and increasing moment of inertia decreases angular speed because I omega stays constant.

### Why does system selection matter for angular momentum?

System selection determines whether torques are internal or external. If you include all interacting objects and the net external torque is zero, total angular momentum is conserved.

### Is perpetual motion possible with conservation of angular momentum?

No. Conservation of angular momentum does not remove energy losses or external torques in real systems, so it does not make perpetual motion possible.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-6/4-conservation-of-angular-momentum/study-guide/9JJXeFccr7Xo7FHS](https://fiveable.me/ap-physics-c-mechanics/unit-6/4-conservation-of-angular-momentum/study-guide/9JJXeFccr7Xo7FHS)</sub>
