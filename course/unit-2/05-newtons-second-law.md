# 2.5 Newton's Second Law

Newton's second law says the acceleration of a system's center of mass equals the net external force divided by the system mass, and it points in the same direction as that net force. If the forces on a system do not cancel, the velocity changes.

## Why This Matters for the AP Physics C: Mechanics Exam

Newton's second law is the engine behind almost every dynamics problem in this course. Once you can build a free-body diagram and write the net force, you can predict how a system accelerates in any situation, from carts and pulleys to inclines and friction.

This topic supports several types of exam thinking:

- Setting up equations from a free-body diagram and solving for acceleration, force, or mass.
- Predicting how acceleration changes when force or mass changes, using the proportional relationship.
- Designing or analyzing experiments where you measure acceleration and net force, including plotting force versus acceleration where the slope gives mass.
- Justifying claims about motion with physics reasoning, which connects to the qualitative-quantitative translation style of free-response question that asks you to link words and math.

## Key Takeaways

- The core equation is $`\vec{a}_{\text{sys}} = \dfrac{\sum \vec{F}}{m_{\text{sys}}} = \dfrac{\vec{F}_{\text{net}}}{m_{\text{sys}}}`$, and acceleration always points in the direction of the net force.
- Unbalanced forces mean the vector sum of forces is not zero, so the center of mass accelerates.
- Acceleration is directly proportional to net force and inversely proportional to mass.
- Only net external force changes the motion of a system's center of mass. Internal forces cancel in pairs.
- Forces can balance in one direction while staying unbalanced in another, so work the x and y directions separately.
- A constant net force produces constant acceleration, which lets you pair this law with kinematics.

## Net Force and Newton's Second Law

Net force is the vector sum of the external forces on the system. In AP Physics C: Mechanics, the most useful form is:

```math
\vec{F}_{\text{net}} = m_{\text{sys}}\vec{a}_{\text{sys}}
```

That equation means the acceleration of the system's center of mass points in the same direction as the net external force. If $`\vec{F}_{\text{net}} = 0`$, the velocity stays constant. If $`\vec{F}_{\text{net}} \neq 0`$, the velocity changes in the direction of the nonzero net force.

## Conditions for Velocity Changes

### Unbalanced Forces

When the forces on a system do not cancel, you have unbalanced forces. These produce a net force that accelerates the system in the direction of that net force.

- Unbalanced forces occur whenever the vector sum of all forces is not zero.
- They can come from a single force acting alone or from several forces that do not cancel.
- Unbalanced forces change a system's velocity, meaning its speed, direction, or both.

For example, when you push a shopping cart, it accelerates because your push is unbalanced. If you and a friend push with equal force from opposite sides, the cart stays put because the forces are balanced.

### Newton's Second Law

Newton's second law gives the relationship between net force, mass, and acceleration. The acceleration of a system's center of mass is directly proportional to the net force and inversely proportional to the mass:

- Doubling the net force doubles the acceleration.
- Doubling the mass halves the acceleration.

```math
\vec{a}_{\text{sys}} = \frac{\sum \vec{F}}{m_{\text{sys}}} = \frac{\vec{F}_{\text{net}}}{m_{\text{sys}}}
```

Where:

- $`\vec{a}_{\text{sys}}`$ is the acceleration of the system's center of mass
- $`\sum \vec{F}`$ is the vector sum of all forces (the net force) on the system
- $`\vec{F}_{\text{net}}`$ is another notation for the net force
- $`m_{\text{sys}}`$ is the total mass of the system

This is why a bowling ball accelerates less than a tennis ball when you apply the same force to each. The bowling ball's larger mass means less acceleration for the same net force. Mass here acts as inertia, a scalar that resists changes in motion.

### Net External Force

The net external force decides whether a system's velocity changes. It is the vector sum of all forces exerted on the system from outside the system boundary.

- Only external forces change the motion of a system's center of mass.
- Internal forces (forces between parts of the system) occur in equal and opposite pairs that cancel.
- When the net external force is zero, the center of mass keeps constant velocity, which is Newton's first law.
- When the net external force is nonzero, the center of mass accelerates according to Newton's second law.

For instance, a book resting on a table has gravity pulling down and the normal force pushing up. These balance, so the net force is zero and there is no acceleration. Tilt the table and the net force along the incline becomes nonzero, so the book accelerates down the slope.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

A reliable approach for second law problems:

1. Draw a free-body diagram with each force as a separate arrow from a dot at the center of mass.
2. Choose axes that line up with the direction of acceleration. On an incline, set one axis parallel to the surface.
3. Write the net force in each direction: $`\sum F_x = m a_x`$ and $`\sum F_y = m a_y`$.
4. Solve for the unknown, then pair the acceleration with kinematics if the question asks for velocity or position.

### Free Response

When a question asks you to explain before calculating, state your claim about how the system accelerates and back it with physics reasoning about the net force, then derive the equation that matches your claim. Make sure your final answer connects back to the conceptual claim you started with. Keep units attached at every step.

### Experimental Reasoning

A common lab setup measures the acceleration of a cart pulled by a hanging mass through a pulley. If you plot net force on the vertical axis and acceleration on the horizontal axis, the slope equals the mass of the system, since $`F_{\text{net}} = m a`$. You can also measure acceleration directly as $`a = \Delta v / \Delta t`$ using a motion or force sensor.

## Worked Example 1: Applying Newton's Second Law

A 2.0 kg object is initially at rest. If a constant force of 8.0 N is applied to it, what will be its velocity after 3.0 seconds?

**Solution**

First, find the acceleration using Newton's second law:

```math
a = \frac{F_{net}}{m} = \frac{8.0 \text{ N}}{2.0 \text{ kg}} = 4.0 \text{ m/s}^2
```

The object starts from rest, so its initial velocity is zero. Because the net force is constant, the acceleration is constant, so use the kinematic equation:

```math
v_f = v_i + at
```

```math
v_f = 0 + (4.0 \text{ m/s}^2)(3.0 \text{ s})
```

```math
v_f = 12.0 \text{ m/s}
```

The object reaches a velocity of 12.0 m/s after 3.0 seconds.

## Worked Example 2: Unbalanced Forces

A 5.0 kg box is being pushed across a horizontal surface by a force of 20.0 N. If the force of friction opposing the motion is 12.0 N, what is the acceleration of the box?

**Solution**

Identify all forces and find the net force.

The horizontal forces acting on the box are:

- Push force: 20.0 N (to the right)
- Friction force: 12.0 N (to the left)

The net force is:

```math
F_{net} = 20.0 \text{ N} - 12.0 \text{ N} = 8.0 \text{ N} \text{ (to the right)}
```

Using Newton's second law:

```math
a = \frac{F_{net}}{m} = \frac{8.0 \text{ N}}{5.0 \text{ kg}} = 1.6 \text{ m/s}^2
```

The box accelerates at 1.6 m/s² in the direction of the net force, to the right.

## Common Misconceptions

- **Misconception:** Force causes velocity.  
  **Actually:** Force does not cause velocity, it causes acceleration. A net force changes velocity over time, so an object can be moving fast with zero net force on it.
- **Misconception:** Zero net force means zero motion.  
  **Actually:** Zero net force does not mean zero motion. It means constant velocity, which includes moving at a steady speed in a straight line.
- **Misconception:** The net force and acceleration point in the same direction as the object's motion.  
  **Actually:** The net force and acceleration point the same way, but neither has to point the same way the object is currently moving. A car slowing down has a net force opposite its motion.
- **Misconception:** Internal forces between parts of a system change the motion of the center of mass.  
  **Actually:** Internal forces between parts of a system do not change the motion of the center of mass. Only external forces do.
- **Misconception:** If forces cancel in one direction, the whole system is in equilibrium.  
  **Actually:** Forces can cancel in one direction while staying unbalanced in another, so always handle x and y separately rather than assuming the whole system is in equilibrium.
- **Misconception:** Mass is a force.  
  **Actually:** Mass is not a force. Weight is the gravitational force $`mg`$, while mass is the scalar that measures inertia.

## Related AP Physics C: Mechanics Guides

- [2.1 Properties and Interactions of a System](01-properties-and-interactions-of-a-system.md)
- [2.2 Forces and Free-Body Diagrams](02-forces-and-free-body-diagrams.md)
- [2.3 Newton's Third Law](03-newtons-third-law.md)
- [2.4 Newton's First Law](04-newtons-first-law.md)
- [2.6 Gravitational Force](06-gravitational-force.md)
- [2.7 Kinetic and Static Friction](07-kinetic-and-static-friction.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| acceleration | A vector quantity that describes the rate of change of an object's velocity with respect to time. |
| center of mass | The point in a system where the entire mass can be considered to be concentrated for the purposes of analyzing motion and forces. |
| net external force | The vector sum of all external forces acting on an object or system, which determines the rate of change of the system's momentum. |
| net force | The vector sum of all forces acting on an object or system. |
| Newton's second law of motion | The principle that the net force on an object equals the rate of change of its momentum, expressed as Fnet = dp/dt = ma. |
| system | A defined collection of objects whose energy and interactions are being analyzed. |
| unbalanced forces | Forces acting on a system such that their vector sum is not zero, resulting in acceleration in that direction. |
| velocity | A vector quantity that describes the rate of change of an object's position with respect to time. |

## Frequently Asked Questions

### What is net force?

Net force is the vector sum of all external forces on a system. It determines the acceleration of the system's center of mass.

### What is Newton's second law formula?

Newton's second law is Fnet = ma in component form, or acceleration equals net force divided by system mass in vector form. Acceleration points in the direction of the net external force.

### How is Newton's second law used in AP Physics C: Mechanics?

Draw a free-body diagram, choose axes, write net-force equations for each direction, and solve for acceleration, force, or mass. Then use kinematics if the problem asks for velocity or position.

### What happens when net force is zero?

If the net external force is zero, the system's center of mass keeps constant velocity. That is Newton's first law as the zero-net-force case of dynamics.

### Do internal forces affect the center of mass motion?

Internal forces between parts of the chosen system cancel in pairs, so they do not change the motion of the system's center of mass. Only net external force does.

### How can an experiment verify Newton's second law?

A typical experiment varies net force on a cart-system and measures acceleration. If force is plotted against acceleration, the slope gives the system mass because Fnet = ma.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-2/5-newtons-second-law/study-guide/c4OMxeY505zPKE78](https://fiveable.me/ap-physics-c-mechanics/unit-2/5-newtons-second-law/study-guide/c4OMxeY505zPKE78)</sub>
