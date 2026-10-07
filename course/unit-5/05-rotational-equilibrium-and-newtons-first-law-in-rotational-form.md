# 5.5 Rotational Equilibrium and Newton's First Law in Rotational Form

Rotational equilibrium means the net torque on a system is zero, so its angular velocity stays constant. This is Newton's first law written for rotation, and an object can be in rotational equilibrium even while it is not in translational equilibrium.

## Why This Matters for the AP Physics C: Mechanics Exam

This topic is part of Unit 5 (Torque and Rotational Dynamics), which carries 10 to 15 percent of the exam weight. Rotational equilibrium gives you the tools to analyze beams, meter sticks, hinges, and balanced systems by writing torque equations and solving for unknowns.

These skills show up in both multiple-choice questions and free response. You will draw force diagrams, calculate torques, compare scenarios, and justify claims about whether angular velocity stays constant or changes. The Qualitative/Quantitative Translation (QQT) free-response question often tests how a quantity changes when one variable shifts, so being fluent with $`\sum \tau = 0`$ and how torque depends on force and lever arm pays off directly.

## Key Takeaways

- Rotational equilibrium happens when $`\sum \tau = 0`$, which means angular velocity stays constant (it can be zero or nonzero).
- A system can be in rotational equilibrium without being in translational equilibrium, and the reverse is also true.
- Newton's first law in rotational form: a system keeps a constant angular velocity unless an external net torque acts on it.
- If the torques do not balance, angular velocity must change, following $`\alpha = \frac{\sum \tau}{I}`$.
- Choosing a smart pivot point (often where an unknown force acts) makes torque equations simpler because that force contributes zero torque.
- Use force diagrams to track where each force acts relative to the axis, then turn each force into a torque using its lever arm.

## Core Concepts

### Rotational vs Translational Equilibrium

Rotational equilibrium occurs when an object keeps a constant angular velocity because the net torque is zero. Translational equilibrium is the linear version: constant linear velocity because the net force is zero. These two conditions are independent.

- A system can be in rotational equilibrium (constant angular velocity) without being in translational equilibrium 🌀
- Free-body diagrams show the forces on an object; force diagrams for rotation also show where each force acts relative to the axis, so you can find the torques
- When the net torque equals zero, $`\sum \tau = 0`$, the system is in rotational equilibrium
- An object can experience a net force, so it is not in translational equilibrium, yet still keep a constant angular velocity if its torques balance

Newton's first law for rotation states that an object holds its current angular velocity unless an external net torque acts on it. This mirrors the linear version but applies to rotation.

A system can have zero net force but a nonzero net torque. If two equal and opposite forces act at different points on a rigid object (a couple), the net force is zero, but the object still gains angular acceleration because the torques do not cancel.

### Torque Balance and Angular Velocity

The angular velocity of a system stays constant when all torques sum to zero. That is the core of rotational equilibrium.

- When $`\sum \tau = 0`$, angular velocity remains constant
- If torques do not balance, the object has angular acceleration given by $`\sum \tau = I\alpha`$
- The rotational inertia $`I`$ represents an object's resistance to changes in rotational motion
- Angular acceleration $`\alpha`$ is directly proportional to net torque and inversely proportional to rotational inertia

🚫 **Boundary Note**

The AP Physics C: Mechanics exam does not expect you to analyze rotation in multiple planes at the same time.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

A reliable order for rotational equilibrium problems:

1. Draw a force diagram and identify every force acting on the object.
2. Choose a pivot point. Picking the location of an unknown force removes that force from the torque equation.
3. Find the lever arm for each force (the perpendicular distance from the axis to the line of action).
4. Calculate each torque with $`\tau = rF\sin\theta`$ or $`\tau = r_\perp F`$, and assign a consistent sign for clockwise vs counterclockwise.
5. Set $`\sum \tau = 0`$ for equilibrium, or $`\sum \tau = I\alpha`$ if the angular velocity is changing. Solve for the unknown.

### Common Trap

Watch your sign convention. Pick one rotation direction as positive and stick with it for every torque. Mixing signs is the fastest way to get a balanced system to look unbalanced.

## Practice Problem 1: Rotational Equilibrium

A uniform meter stick with mass 0.150 kg is balanced at the 30.0 cm mark. A 0.200 kg mass is hung from the 10.0 cm mark. Where should a 0.300 kg mass be hung to maintain rotational equilibrium?

**Solution**

Set the pivot at the 30.0 cm mark and calculate torques around this point:

1. Identify all torques acting on the system:
   
   - The meter stick's weight acts at its center of mass (50.0 cm mark), creating a clockwise torque
   - The 0.200 kg mass at 10.0 cm creates a counterclockwise torque
   - The 0.300 kg mass at position x creates a clockwise torque
2. For rotational equilibrium, the sum of torques must equal zero: $`\sum \tau = 0`$
3. Calculate each torque (using g = 9.8 m/s²):
   
   - Meter stick torque: $`\tau_{stick} = (0.150 \text{ kg})(9.8 \text{ m/s}^2)(0.20 \text{ m}) = 0.294 \text{ N} \cdot \text{m}`$ (clockwise, positive)
   - 0.200 kg mass torque: $`\tau_{0.2} = (0.200 \text{ kg})(9.8 \text{ m/s}^2)(0.20 \text{ m}) = 0.392 \text{ N} \cdot \text{m}`$ (counterclockwise, negative)
   - 0.300 kg mass torque: $`\tau_{0.3} = (0.300 \text{ kg})(9.8 \text{ m/s}^2)(x - 0.30 \text{ m})`$ (clockwise if x \> 30 cm, positive)
4. Apply the equilibrium condition: $`0.294 - 0.392 + (0.300)(9.8)(x - 0.30) = 0`$ $`-0.098 + 2.94(x - 0.30) = 0`$ $`2.94x - 0.882 - 0.098 = 0`$ $`2.94x = 0.98`$ $`x = 0.333 \text{ m}`$

The 0.300 kg mass should be hung at the 33.3 cm mark to maintain rotational equilibrium.

## Practice Problem 2: Newton's First Law in Rotational Form

A turntable is spinning at 0.5 rad/s. After the driving motor is disconnected, the net external torque on the turntable is zero because friction is negligible. What happens to its angular velocity?

**Solution**

By Newton's first law in rotational form, a system keeps a constant angular velocity when the net external torque is zero.

1. Identify the condition: $`\sum \tau = 0`$
2. Apply the rotational form of Newton's first law: If $`\sum \tau = 0`$, then angular acceleration $`\alpha = 0`$.
3. Since angular acceleration is zero, the angular velocity does not change: $`\omega_f = \omega_i = 0.5\ \text{rad/s}`$

The turntable continues rotating at **0.5 rad/s**.

## Common Misconceptions

- **Misconception:** Equilibrium means not moving.  
  **Actually:** Rotational equilibrium only means angular velocity is constant. A wheel spinning at a steady rate with zero net torque is in rotational equilibrium even though it is rotating.
- **Misconception:** Zero net force means zero net torque.  
  **Actually:** Not true. A couple (two equal, opposite forces at different points) gives zero net force but a nonzero net torque, so the object angularly accelerates.
- **Misconception:** Torque depends only on how hard you push.  
  **Actually:** Torque depends on both the force and the lever arm. A small force far from the axis can produce more torque than a large force near the axis.
- **Misconception:** Only the full force matters for torque.  
  **Actually:** Only the component of force perpendicular to the position vector creates torque. Use $`\tau = rF\sin\theta`$ or the perpendicular lever arm.
- **Misconception:** The pivot point is fixed by the problem.  
  **Actually:** For a system in equilibrium, you can choose any point as the pivot. Picking the point where an unknown force acts makes that force drop out of the equation.

## Related AP Physics C: Mechanics Guides

- [5.1 Rotation](01-rotation.md)
- [5.3 Torque](03-torque.md)
- [5.4 Rotational Inertia](04-rotational-inertia.md)
- [5.6 Newton's Second Law in Rotational Form](06-newtons-second-law-in-rotational-form.md)
- [5.2 Connecting Linear and Rotational Motion](02-connecting-linear-and-rotational-motion.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| angular velocity | The rate of change of angular position with respect to time, represented by the symbol ω. |
| force diagram | A diagram that represents the forces exerted on an object or system. |
| free-body diagram | A visual representation showing all forces exerted on an object or system, with each force drawn as a vector originating from the center of mass. |
| net torque | The vector sum of all torques acting on an object or system, which causes changes in angular motion. |
| rigid system | A collection of objects or particles that maintain fixed distances from each other and rotate as a single unit. |
| rotational equilibrium | A state in which a system maintains constant angular velocity because the net torque exerted on it is zero. |
| torque | A measure of the rotational effect of a force on a rigid body, calculated as the product of the force component perpendicular to the position vector and the distance from the axis of rotation. |
| translational equilibrium | The configuration of forces such that the net force exerted on a system is zero, resulting in constant velocity. |

## Frequently Asked Questions

### What is rotational equilibrium?

Rotational equilibrium means the net torque on a system is zero, so angular velocity remains constant. The angular velocity can be zero or nonzero.

### What is Newton’s first law in rotational form?

Newton’s first law in rotational form says a system keeps a constant angular velocity unless an external net torque acts on it. If net torque is zero, angular velocity does not change.

### What is the condition for rotational equilibrium?

The condition is sum of torques equals zero. In symbols, Στ = 0. You choose a sign convention, calculate clockwise and counterclockwise torques, and set the net torque to zero.

### Can an object be in rotational equilibrium but not translational equilibrium?

Yes. Rotational equilibrium depends on net torque, while translational equilibrium depends on net force. A system can have zero net torque but nonzero net force, or zero net force but nonzero net torque.

### Why does pivot choice matter in torque problems?

Choosing a pivot at the location of an unknown force can make that force contribute zero torque, which simplifies the equation. The physics is the same, but the algebra becomes cleaner.

### What is a common rotational equilibrium mistake?

A common mistake is mixing sign conventions for clockwise and counterclockwise torque. Pick one direction as positive and keep it consistent for every torque in the equation.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-5/5-rotational-equilibrium-and-newtons-first-law-in-rotational-form/study-guide/hkkIAh5Csy8T6d0p](https://fiveable.me/ap-physics-c-mechanics/unit-5/5-rotational-equilibrium-and-newtons-first-law-in-rotational-form/study-guide/hkkIAh5Csy8T6d0p)</sub>
