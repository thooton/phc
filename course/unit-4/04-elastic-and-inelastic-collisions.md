# 4.4 Elastic and Inelastic Collisions

A collision is elastic when the system's total kinetic energy stays the same before and after, and inelastic when total kinetic energy decreases. Momentum is conserved in both types, so you always use conservation of momentum first, then check kinetic energy to decide which kind of collision you have.

## What Is the Difference Between Elastic and Inelastic Collisions?

The difference between elastic and inelastic collisions is what happens to kinetic energy. In an elastic collision, total kinetic energy is conserved. In an inelastic collision, total kinetic energy decreases because some kinetic energy changes into other forms, like thermal energy, sound, or deformation.

Momentum can still be conserved in both types. If the system has negligible net external force during the collision, start with conservation of momentum, then use the kinetic energy information to classify the collision or solve for final velocities.

## Why This Matters for the AP Physics C: Mechanics Exam

Collisions show up across the linear momentum unit, which carries a noticeable share of the AP Physics C: Mechanics exam. This topic builds directly on conservation of momentum and the impulse-momentum theorem, and it asks you to combine momentum reasoning with energy reasoning in the same problem.

On multiple-choice questions, you often have to decide quickly whether kinetic energy is conserved and whether momentum is conserved. On free-response questions, you may need to set up momentum equations, compute kinetic energy before and after, and explain in words why energy was lost. The experimental design and analysis free-response question can also use a collision setup, such as dynamics carts, where you collect velocity data, linearize it, and justify claims with evidence.

## Key Takeaways

- Momentum is conserved in every collision when the net external force on the system is zero. Use $`m_1v_{1i} + m_2v_{2i} = m_1v_{1f} + m_2v_{2f}`$ as your starting point.
- A collision is elastic only when total kinetic energy is the same before and after. The objects do not stick together.
- A collision is inelastic when total kinetic energy decreases. The lost energy turns into heat, sound, or deformation through nonconservative forces.
- A perfectly inelastic collision is the case where objects stick together and move with one common final velocity, and it loses the most kinetic energy possible while still conserving momentum.
- Total energy is always conserved. "Lost" kinetic energy is just energy that changed form, not energy that disappeared.
- For a 1D elastic collision, you solve momentum and kinetic energy equations together, or use the standard final-velocity formulas.

## Elastic vs Inelastic Interactions

### Elastic Collision Kinetic Energy

In an elastic collision, the total kinetic energy of the system is the same before and after the collision. This is the defining feature that separates elastic collisions from inelastic ones.

- Kinetic energy gets redistributed among the colliding objects, but the total stays constant.
- Real situations only approach perfectly elastic behavior. Billiard balls, marbles, and atomic particles come close.
- A perfectly elastic collision is an idealization with no kinetic energy lost.

The kinetic energy condition for an elastic collision:

```math
KE_{initial} = KE_{final}
```

```math
\frac{1}{2}m_1v_{1i}^2 + \frac{1}{2}m_2v_{2i}^2 = \frac{1}{2}m_1v_{1f}^2 + \frac{1}{2}m_2v_{2f}^2
```

### Individual Object Kinetic Energy

Even though the system's total kinetic energy stays constant in an elastic collision, each individual object's kinetic energy usually changes during the interaction.

- One object can gain kinetic energy while the other loses an equal amount.
- The energy exchange depends on the mass ratio of the colliding objects.
- In a head-on collision between objects of equal mass, they can completely exchange velocities.

To find the final velocities in a 1D elastic collision, solve these two equations together:

$`m_1v_{1i} + m_2v_{2i} = m_1v_{1f} + m_2v_{2f}`$ (conservation of momentum) $`\frac{1}{2}m_1v_{1i}^2 + \frac{1}{2}m_2v_{2i}^2 = \frac{1}{2}m_1v_{1f}^2 + \frac{1}{2}m_2v_{2f}^2`$ (conservation of kinetic energy)

### Inelastic Collision Energy Decrease

An inelastic collision is one in which the system's total kinetic energy decreases after the collision.

- Some initial kinetic energy converts to thermal energy, sound, or deformation.
- How much energy is lost depends on the materials and the collision speed.
- Even though kinetic energy decreases, the total energy of the system in all its forms stays conserved.

The decrease in kinetic energy:

```math
KE_{lost} = KE_{initial} - KE_{final}
```

### Energy Transformation in Collisions

During a collision, kinetic energy can change into other forms depending on the collision type and the objects involved.

- Elastic collisions: kinetic energy is conserved, with no net transformation into other forms.
- Inelastic collisions: kinetic energy transforms into forms such as:
  
  - Thermal energy from friction and deformation
  - Sound energy from vibrations and pressure waves
  - Energy stored in deformed materials

Energy conservation still holds for every collision. The total energy across all forms stays constant:

```math
E_{total,initial} = E_{total,final}
```

### Perfectly Inelastic Collisions

A perfectly inelastic collision is the extreme case where the objects stick together and move as a single unit after impact.

- The maximum possible kinetic energy is lost for that set of initial conditions.
- The objects share one common final velocity.
- Examples include a dart sticking in a board or two cars that crumple and lock together.

Find the common final velocity using conservation of momentum:

```math
m_1v_{1i} + m_2v_{2i} = (m_1 + m_2)v_f
```

The kinetic energy lost:

```math
KE_{lost} = \frac{1}{2}m_1v_{1i}^2 + \frac{1}{2}m_2v_{2i}^2 - \frac{1}{2}(m_1 + m_2)v_f^2
```

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

Use a consistent order so you do not mix up the two big conservation laws.

1. Pick your system and confirm the net external force is about zero during the brief collision, so momentum is conserved.
2. Write conservation of momentum first. It works for elastic, inelastic, and perfectly inelastic collisions.
3. Decide the collision type. If kinetic energy is conserved, add the kinetic energy equation. If the objects stick together, use the single common final velocity.
4. Solve for unknowns, then check that your answer keeps momentum constant and that kinetic energy did not increase.

### Free Response

When a question asks you to explain or justify, connect the equations to physical meaning. State that momentum is conserved because external forces are negligible during impact, and state whether kinetic energy is conserved based on the collision type. If energy decreased, name where it went, such as heat, sound, or permanent deformation by nonconservative forces.

### Common Trap

Watch your signs and directions. Velocities in 1D collisions are signed quantities, so a rebound is negative if the original motion is positive. Plugging in a wrong sign breaks both your momentum and kinetic energy checks.

## Practice Problem 1: Elastic Collision

A 2.0 kg ball moving at 5.0 m/s collides elastically with a 3.0 kg ball initially at rest. What are the final velocities of both balls after the collision?

**Solution**

For an elastic collision, apply both conservation of momentum and conservation of kinetic energy:

Conservation of momentum: $`m_1v_{1i} + m_2v_{2i} = m_1v_{1f} + m_2v_{2f}`$

```math
(2.0 \text{ kg})(5.0 \text{ m/s}) + (3.0 \text{ kg})(0 \text{ m/s}) = (2.0 \text{ kg})v_{1f} + (3.0 \text{ kg})v_{2f}
```

```math
10.0 \text{ kg}\cdot\text{m/s} = 2.0v_{1f} + 3.0v_{2f}
```

Conservation of kinetic energy: $`\frac{1}{2}m_1v_{1i}^2 + \frac{1}{2}m_2v_{2i}^2 = \frac{1}{2}m_1v_{1f}^2 + \frac{1}{2}m_2v_{2f}^2`$

```math
\frac{1}{2}(2.0)(5.0)^2 + \frac{1}{2}(3.0)(0)^2 = \frac{1}{2}(2.0)v_{1f}^2 + \frac{1}{2}(3.0)v_{2f}^2
```

```math
25.0 \text{ J} = 1.0v_{1f}^2 + 1.5v_{2f}^2
```

Solving these equations together: From the momentum equation: $`v_{2f} = \frac{10.0 - 2.0v_{1f}}{3.0}`$

Substituting into the kinetic energy equation: $`25.0 = 1.0v_{1f}^2 + 1.5\left(\frac{10.0 - 2.0v_{1f}}{3.0}\right)^2`$

You can solve this directly, or use the standard 1D elastic-collision results:

```math
v_{1f} = \frac{m_1-m_2}{m_1+m_2}v_{1i} + \frac{2m_2}{m_1+m_2}v_{2i} = \frac{2.0-3.0}{2.0+3.0}(5.0) + \frac{2(3.0)}{5.0}(0) = -1.0\text{ m/s}
```

```math
v_{2f} = \frac{2m_1}{m_1+m_2}v_{1i} + \frac{m_2-m_1}{m_1+m_2}v_{2i} = \frac{2(2.0)}{2.0+3.0}(5.0) + \frac{3.0-2.0}{5.0}(0) = 4.0\text{ m/s}
```

Check momentum: $`(2.0)(-1.0) + (3.0)(4.0) = -2.0 + 12.0 = 10.0\text{ kg·m/s}`$

Check kinetic energy: $`\frac{1}{2}(2.0)(-1.0)^2 + \frac{1}{2}(3.0)(4.0)^2 = 1.0 + 24.0 = 25.0\text{ J}`$

The first ball rebounds at 1.0 m/s in the negative direction, and the second ball moves forward at 4.0 m/s.

## Practice Problem 2: Perfectly Inelastic Collision

A 1500 kg car moving at 20 m/s collides with a 2500 kg truck at rest. If they stick together after the collision, find (a) their common final velocity and (b) the kinetic energy lost in the collision.

**Solution**

(a) For a perfectly inelastic collision, use conservation of momentum to find the common final velocity:

```math
m_1v_{1i} + m_2v_{2i} = (m_1 + m_2)v_f
```

```math
(1500 \text{ kg})(20 \text{ m/s}) + (2500 \text{ kg})(0 \text{ m/s}) = (1500 \text{ kg} + 2500 \text{ kg})v_f
```

```math
30,000 \text{ kg}\cdot\text{m/s} = 4000 \text{ kg} \times v_f
```

```math
v_f = \frac{30,000 \text{ kg}\cdot\text{m/s}}{4000 \text{ kg}} = 7.5 \text{ m/s}
```

(b) To find the kinetic energy lost:

```math
KE_{lost} = KE_{initial} - KE_{final}
```

```math
KE_{initial} = \frac{1}{2}m_1v_{1i}^2 + \frac{1}{2}m_2v_{2i}^2 = \frac{1}{2}(1500)(20)^2 + \frac{1}{2}(2500)(0)^2 = 300,000 \text{ J}
```

```math
KE_{final} = \frac{1}{2}(m_1 + m_2)v_f^2 = \frac{1}{2}(4000)(7.5)^2 = 112,500 \text{ J}
```

```math
KE_{lost} = 300,000 \text{ J} - 112,500 \text{ J} = 187,500 \text{ J}
```

The common final velocity is 7.5 m/s, and 187,500 J of kinetic energy is lost during the collision.

## Common Misconceptions

- **Misconception:** Inelastic means momentum is lost.  
  **Actually:** Momentum is conserved in both elastic and inelastic collisions when external forces are negligible. Only kinetic energy decreases in an inelastic collision.
- **Misconception:** Energy disappears in an inelastic collision.  
  **Actually:** Total energy is always conserved. The kinetic energy that goes missing becomes heat, sound, or deformation.
- **Misconception:** Perfectly inelastic means all kinetic energy is lost.  
  **Actually:** The objects stick together and lose the maximum possible kinetic energy, but they still keep moving if the system had net momentum, so kinetic energy is not zero.
- **Misconception:** If the objects stick together, momentum is not conserved.  
  **Actually:** Sticking together is exactly when you use one common final velocity in the momentum equation. Momentum still holds.
- **Misconception:** Elastic collisions never change each object's energy.  
  **Actually:** The total kinetic energy stays constant, but individual objects usually gain or lose kinetic energy as they exchange it.
- **Misconception:** You can use the kinetic energy equation for any collision.  
  **Actually:** Only use kinetic energy conservation when you already know the collision is elastic. For inelastic collisions, kinetic energy is not conserved.

## Related AP Physics C: Mechanics Guides

- [4.1 Linear Momentum](01-linear-momentum.md)
- [4.3 Conservation of Linear Momentum](03-conservation-of-linear-momentum.md)
- [4.2 Change in Momentum and Impulse](02-change-in-momentum-and-impulse.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| elastic collision | A collision between objects in which the total kinetic energy of the system is conserved, with initial kinetic energy equal to final kinetic energy. |
| inelastic collision | A collision between objects in which the total kinetic energy of the system decreases, with some kinetic energy transformed into other forms of energy. |
| kinetic energy | The energy possessed by an object due to its motion, equal to one-half the product of its mass and the square of its velocity. |
| nonconservative force | A force for which the work done is path-dependent, such as friction or air resistance. |
| perfectly inelastic collision | A collision in which the objects stick together after impact and move with the same velocity. |

## Frequently Asked Questions

### What's the difference between elastic and inelastic collisions?

Elastic collisions conserve total kinetic energy, while inelastic collisions lose some kinetic energy to other forms such as heat, sound, or deformation. Momentum can be conserved in both if net external force is negligible.

### Is momentum conserved in inelastic collisions?

Yes. Momentum is conserved in an inelastic collision when the system has negligible net external force during the collision. Kinetic energy decreases, but momentum does not disappear.

### What is a perfectly inelastic collision?

A perfectly inelastic collision is one where the objects stick together and move with one common final velocity. It loses the maximum possible kinetic energy for the given starting conditions while still conserving momentum.

### What formula do you use for elastic collisions?

For a 1D elastic collision, use conservation of momentum and conservation of kinetic energy together. The core equations are momentum before equals momentum after, and kinetic energy before equals kinetic energy after.

### How do you solve inelastic collision problems?

Start with conservation of momentum. If the objects stick together, use one common final velocity. Then compare initial and final kinetic energy if the question asks how much kinetic energy changed form.

### How are collisions tested on AP Physics C: Mechanics?

AP Physics C can test collisions through multiple-choice, calculation, justification, and experimental-analysis questions. You may need to set up momentum equations, compare kinetic energy before and after, and justify whether a collision is elastic or inelastic.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-4/4-elastic-and-inelastic-collisions/study-guide/JvjEzhTLprTtp64U](https://fiveable.me/ap-physics-c-mechanics/unit-4/4-elastic-and-inelastic-collisions/study-guide/JvjEzhTLprTtp64U)</sub>
