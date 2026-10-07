# 4.3 Conservation of Linear Momentum

Conservation of linear momentum means the total momentum of a system stays constant when the net external force on it is zero. By choosing your system wisely so that internal forces cancel, you can find velocities before and after collisions and explosions, even when kinetic energy is not conserved.

## Why This Matters for the AP Physics C: Mechanics Exam

Unit 4 carries 10 to 20 percent of the AP Physics C: Mechanics exam, and conservation of momentum is the engine that drives most collision and explosion problems. You will use it to set up equations for one and two dimensional interactions, justify why momentum is constant for a chosen system, and connect impulse to changes in momentum. The third free-response question is an Experimental Design and Analysis question, so being able to design a procedure, collect data, and linearize results for a momentum scenario is directly useful. Momentum reasoning also reinforces Newton's third law, which shows up across the exam.

## Key Takeaways

- A system's center-of-mass velocity is $`\vec{v}_{\mathrm{cm}}=\frac{\sum (m_i \vec{v}_i)}{\sum m_i}`$ and stays constant when no net external force acts.
- Total momentum is the vector sum of each part's momentum, so directions matter and you often work component by component.
- Inside an isolated system, any momentum gained by one object is balanced by an equal and opposite change elsewhere, a direct result of Newton's third law.
- If the net external force on your chosen system is zero, total momentum is conserved; if it is nonzero, momentum transfers between the system and its surroundings.
- Conservation of momentum gives velocities right before and right after collisions and explosions, even when kinetic energy changes.
- The exam expects quantitative analysis of one and two dimensional interactions; three dimensional cases are only qualitative.

## Center-of-Mass Velocity

The center-of-mass velocity describes how a collection of objects moves as if it were a single object. When several objects interact, you can treat the whole system as one object moving with this velocity.

- Calculate it with: $`\vec{v}_{\mathrm{cm}}=\frac{\sum \vec{p}_{i}}{\sum m_{i}}=\frac{\sum\left(m_{i} \vec{v}_{i}\right)}{\sum m_{i}}`$
- This velocity stays constant when no net external force acts on the system.
- Example: if a 2 kg object moving at 3 m/s collides with a 1 kg object at rest, the center-of-mass velocity is $`\vec{v}_{\mathrm{cm}}=\frac{(2\text{ kg})(3\text{ m/s})+(1\text{ kg})(0\text{ m/s})}{2\text{ kg}+1\text{ kg}}=2\text{ m/s}`$

## Total Momentum of a System

The total momentum tells you how a system moves and how it will behave in an interaction.

- Total momentum is the sum of all individual momenta: $`\vec{p}_{\text{total}} = \sum \vec{p}_i`$
- For objects moving in different directions, use vector addition.
- Total momentum connects to center-of-mass motion through $`\vec{p}_{\text{total}} = M\vec{v}_{\text{cm}}`$ where $`M`$ is the total mass.

## Changes in Momentum Within a System

When objects interact inside an isolated system, momentum transfers between them while the total stays constant. This lets you predict motion after collisions and other interactions.

- In isolated systems, momentum changes follow: $`\Delta\vec{p}_1 = -\Delta\vec{p}_2`$
- This comes from Newton's third law of equal and opposite forces.
- The impulse-momentum relationship governs these changes: $`\vec{J}=\Delta \vec{p}`$
- During an interaction, the impulse exerted by object 1 on object 2 is equal in magnitude and opposite in direction to the impulse exerted by object 2 on object 1: $`\vec{J}_{1\to2}=-\vec{J}_{2\to1}`$. This follows directly from Newton's third law and explains why momentum changes within an isolated system cancel.
- Example: when a baseball player hits a ball, the ball gains momentum in one direction while the bat and player experience an equal momentum change in the opposite direction.

## Velocity Before and After Collisions and Explosions

Conservation of momentum lets you find how objects move immediately before and immediately after collisions or explosions, even when kinetic energy is not conserved.

- For any collision in one dimension: $`m_1\vec{v}_{1i} + m_2\vec{v}_{2i} = m_1\vec{v}_{1f} + m_2\vec{v}_{2f}`$
- In an elastic collision, both momentum and kinetic energy are conserved.
- In an inelastic collision, momentum is conserved but kinetic energy is not.
- In a perfectly inelastic collision, objects stick together and move with a common final velocity.
- For an explosion in an isolated system, the total momentum afterward equals the total momentum before. If the system starts at rest, then $`\vec{p}_{\text{final}}=0`$, so the momenta of the pieces must add to zero.

**Example, Explosion:** A 4 kg object at rest explodes into a 1 kg piece moving right at 12 m/s and a 3 kg piece. Since the initial momentum is zero:

```math
0 = (1\text{ kg})(12\text{ m/s}) + (3\text{ kg})v_2
```

```math
v_2 = -4\text{ m/s}
```

The 3 kg piece moves left at 4 m/s.

## System Selection for Momentum

Choosing your system boundaries is critical for applying conservation correctly. Momentum is conserved in all interactions, but whether the momentum of a chosen system stays constant depends on what you include. If you include all the interacting objects so the net external force on the system is zero, the system's total momentum is constant. If part of the interaction is outside the system, momentum transfers between the system and the environment, so the selected system's momentum changes.

### Conservation in All Interactions

Momentum conservation applies to every interaction between objects, which is what makes it so powerful.

- Whether you are dealing with collisions, explosions, or other interactions, total momentum stays constant in isolated systems.
- This works for both microscopic (atomic) and macroscopic (everyday) objects.
- It holds whether the interaction is elastic, inelastic, or somewhere in between.

### Zero Net External Force

When no net external force acts on a system, its total momentum stays constant over time.

- Examples include collisions on frictionless surfaces or explosions in empty space.
- The mathematical statement is: $`\vec{p}_{\text{initial}} = \vec{p}_{\text{final}}`$
- This lets you analyze complex interactions by focusing only on the objects involved.

### Nonzero Net External Force

When a net external force acts on a system, momentum is exchanged between the system and its environment.

- The change in momentum equals the impulse from external forces: $`\Delta\vec{p}_{\text{system}} = \vec{J}_{\text{external}}`$
- Common external forces include friction, gravity, and contact forces from objects outside the system.
- By expanding your system boundaries to include all interacting objects, you can often remove external forces and apply conservation.

**Boundary Statement**

On the exam, expect to quantitatively analyze 1D and 2D collisions and interactions. 3D collisions may appear for qualitative analysis only.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

- Define your system first, then check whether the net external force is zero. Only then can you write total momentum before equals total momentum after.
- Set a coordinate system and break momentum into components. In two dimensions, conserve $`p_x`$ and $`p_y`$ separately.
- For perfectly inelastic collisions, combine the masses for the final velocity since the objects move together.
- For explosions starting from rest, set the total final momentum to zero and solve for the unknown piece.

### Free Response

- Justify why momentum is conserved by naming the system and stating that the net external force on it is zero.
- When kinetic energy is not conserved, do not try to use energy conservation for the collision step. Use momentum for the collision, then energy for any before or after motion if needed.
- Show your impulse reasoning clearly when a force acts over a time interval, using $`\vec{J}=\Delta \vec{p}`$.

### Experimental Design and Analysis

- The third free-response question asks you to design a procedure and analyze data. For a momentum lab, identify what you would measure (masses and velocities before and after) and how.
- Be ready to linearize data and use a best-fit line to support a claim, such as showing total momentum is constant within experimental error.
- Discuss sources of error, like friction acting as an external force that removes momentum from your chosen system.

## Common Misconceptions

- **Misconception:** Momentum is always constant for any object you pick.  
  **Actually:** Momentum is conserved only for the right system. It is not "always constant" for any object you pick. If the net external force on your system is nonzero, that system's momentum changes.
- **Misconception:** Momentum and kinetic energy are the same.  
  **Actually:** Momentum and kinetic energy are not the same. In inelastic collisions momentum is conserved but kinetic energy decreases, so do not assume kinetic energy is conserved in every collision.
- **Misconception:** Each object keeps its own momentum when momentum is conserved.  
  **Actually:** "Conserved" does not mean each object keeps its own momentum. Individual momenta change; the total of the system stays constant.
- **Misconception:** Momentum is a scalar.  
  **Actually:** Momentum is a vector. A common error is adding magnitudes without considering direction. Always use signs or components.
- **Misconception:** The two objects have equal velocity changes when their masses differ.  
  **Actually:** Newton's third law forces are equal and opposite, so the impulses on the two objects are equal and opposite, but their velocity changes differ when their masses differ.
- **Misconception:** An explosion creates momentum.  
  **Actually:** An explosion does not create momentum. If the system starts at rest, the pieces must have momenta that add to zero.

## Practice Problem 1: Inelastic Collision

A 2000 kg car traveling east at 15 m/s collides with a 1500 kg car traveling north at 20 m/s. The cars stick together after the collision. Find the velocity (magnitude and direction) of the combined cars immediately after the collision.

**Solution**

Apply conservation of momentum. Since no net external force acts on the system of two cars, the total momentum before equals the total momentum after.

Step 1: Find the initial momentum components.

- East component (x-direction): $`p_{x,i} = m_1v_{1x} = (2000 \text{ kg})(15 \text{ m/s}) = 30,000 \text{ kg}\cdot\text{m/s}`$
- North component (y-direction): $`p_{y,i} = m_2v_{2y} = (1500 \text{ kg})(20 \text{ m/s}) = 30,000 \text{ kg}\cdot\text{m/s}`$

Step 2: After the collision, the total mass is $`m_T = 2000 \text{ kg} + 1500 \text{ kg} = 3500 \text{ kg}`$

Step 3: Apply conservation of momentum to find final velocity components.

- $`v_{x,f} = \frac{p_{x,i}}{m_T} = \frac{30,000 \text{ kg}\cdot\text{m/s}}{3500 \text{ kg}} = 8.57 \text{ m/s}`$ (east)
- $`v_{y,f} = \frac{p_{y,i}}{m_T} = \frac{30,000 \text{ kg}\cdot\text{m/s}}{3500 \text{ kg}} = 8.57 \text{ m/s}`$ (north)

Step 4: Calculate the magnitude and direction of the final velocity.

- Magnitude: $`v_f = \sqrt{v_{x,f}^2 + v_{y,f}^2} = \sqrt{(8.57)^2 + (8.57)^2} = 12.1 \text{ m/s}`$
- Direction: $`\theta = \tan^{-1}\left(\frac{v_{y,f}}{v_{x,f}}\right) = \tan^{-1}\left(\frac{8.57}{8.57}\right) = 45°`$ north of east

The combined cars move at 12.1 m/s at 45° north of east immediately after the collision.

## Practice Problem 2: Center-of-Mass Velocity

Three objects are moving along the x-axis: a 2 kg object at 3 m/s, a 5 kg object at -2 m/s, and a 3 kg object at 4 m/s. Calculate the center-of-mass velocity of the system.

**Solution**

To find the center-of-mass velocity, use the formula: $`\vec{v}_{\mathrm{cm}}=\frac{\sum\left(m_{i} \vec{v}_{i}\right)}{\sum m_{i}}`$

Step 1: Calculate the total mass of the system. $`m_{total} = 2 \text{ kg} + 5 \text{ kg} + 3 \text{ kg} = 10 \text{ kg}`$

Step 2: Calculate the sum of the products of mass and velocity. $`\sum(m_i v_i) = (2 \text{ kg})(3 \text{ m/s}) + (5 \text{ kg})(-2 \text{ m/s}) + (3 \text{ kg})(4 \text{ m/s})`$ $`\sum(m_i v_i) = 6 \text{ kg}\cdot\text{m/s} + (-10) \text{ kg}\cdot\text{m/s} + 12 \text{ kg}\cdot\text{m/s} = 8 \text{ kg}\cdot\text{m/s}`$

Step 3: Calculate the center-of-mass velocity. $`v_{cm} = \frac{8 \text{ kg}\cdot\text{m/s}}{10 \text{ kg}} = 0.8 \text{ m/s}`$

The center-of-mass velocity of the system is 0.8 m/s in the positive x-direction.

## Related AP Physics C: Mechanics Guides

- [4.1 Linear Momentum](01-linear-momentum.md)
- [4.4 Elastic and Inelastic Collisions](04-elastic-and-inelastic-collisions.md)
- [4.2 Change in Momentum and Impulse](02-change-in-momentum-and-impulse.md)

## Frequently Asked Questions

### What is conservation of linear momentum?

Conservation of linear momentum means the total momentum of a selected system stays constant when the net external force on that system is zero.

### How is Newton's third law related to momentum conservation?

Newton's third law means interacting objects exert equal and opposite forces for the same time, so their impulses and momentum changes are equal and opposite.

### When is momentum conserved in AP Physics C Mechanics?

Momentum is conserved for a selected system when the net external force on that system is zero. System selection is what determines whether external impulse changes the system momentum.

### What is the formula for center-of-mass velocity?

The center-of-mass velocity is v\_cm = sum(m\_i v\_i) divided by sum(m\_i), or total momentum divided by total mass.

### Is momentum conserved in inelastic collisions?

Yes, momentum is conserved in isolated inelastic collisions, but kinetic energy is not conserved. In perfectly inelastic collisions, objects stick together.

### How do you solve two-dimensional momentum problems?

Choose x and y axes, then conserve momentum separately in each direction: total p\_x before equals total p\_x after, and total p\_y before equals total p\_y after.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-4/3-conservation-of-linear-momentum/study-guide/qWLd3tCmiQRSZKv0](https://fiveable.me/ap-physics-c-mechanics/unit-4/3-conservation-of-linear-momentum/study-guide/qWLd3tCmiQRSZKv0)</sub>
