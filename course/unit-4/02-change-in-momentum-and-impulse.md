# 4.2 Change in Momentum and Impulse

Impulse is the integral of net force over time, and the impulse momentum theorem says that impulse equals an object's change in momentum: $`\vec{J} = \int \vec{F} {\text{net}}\,dt = \Delta\vec{p}`$. This links force and time directly to changes in velocity, which helps with collisions, impacts, and rocket-propulsion problems.

## Why This Matters for the AP Physics C: Mechanics Exam

Impulse and momentum change show up across the exam in both calculation and reasoning forms. You may need to find an average force from a contact time, read impulse as the area under a force versus time graph, or interpret the slope of a momentum versus time graph as net force. Because this topic involves integrals and derivatives, it is a natural place for the exam to test your calculus skills alongside physics reasoning.

The experimental design and analysis free-response question can ask you to plan how you would collect force or momentum data and then analyze it, sometimes by linearizing a graph. Getting comfortable with force-time and momentum-time graphs here builds the data-analysis habits that question rewards.

## Key Takeaways

- Net force equals the time rate of change of momentum: $`\vec{F}_{\text{net}} = \frac{d\vec{p}}{dt}`$.
- Impulse is the integral of net force over time, $`\vec{J} = \int_{t_1}^{t_2}\vec{F}_{\text{net}}(t)\,dt`$, and it is a vector pointing in the direction of the net force.
- The impulse-momentum theorem: impulse delivered equals change in momentum, $`\vec{J} = \Delta\vec{p} = \vec{p} - \vec{p}_0`$.
- Area under a force versus time graph gives impulse; slope of a momentum versus time graph gives net force.
- Newton's second law, $`\vec{F}_{\text{net}} = m\vec{a}`$, comes straight from the impulse-momentum theorem when mass is constant.
- When velocity is constant but mass changes, $`\vec{F}_{\text{net}} = \frac{dm}{dt}\vec{v}`$, which is how variable-mass problems like sand falling onto a moving conveyor belt work. (Rocket thrust instead depends on the exhaust speed relative to the rocket.)
- Impulse units are $`\text{N}\cdot\text{s}`$, which equal $`\text{kg}\cdot\text{m/s}`$, the same units as momentum.

## Impulse Delivery

### Rate of Momentum Change

The net external force on a system sets how fast that system's momentum changes. This is the momentum form of Newton's second law.

```math
\vec{F}_{\text{net}}=\frac{d \vec{p}}{dt}
```

- $`\vec{F}_{\text{net}}`$ is the net external force vector.
- $`\frac{d \vec{p}}{dt}`$ is the rate of change of momentum with respect to time.

A larger force changes momentum faster; a smaller force changes it more slowly. A baseball feels a much greater force when hit by a bat than when caught by a glove, so its momentum changes much more rapidly during the hit.

### Impulse Definition

Impulse is the total effect of a net force acting over a time interval.

```math
\vec{J}=\int_{t_{1}}^{t_{2}} \vec{F}_{\text{net}}(t) dt
```

- $`\vec{J}`$ is the impulse vector.
- $`\vec{F}_{\text{net}}(t)`$ is the net external force as a function of time.
- $`t_1`$ and $`t_2`$ are the initial and final times of the interval.

When the force is constant, the integral simplifies to $`\vec{J} = \vec{F}_{\text{net}}\,\Delta t`$. The same impulse can come from a large force over a short time or a small force over a long time.

### Impulse Direction

Impulse takes its direction from the net force that produces it.

- Impulse is a vector with both magnitude and direction.
- It points in the same direction as the net force on the system.
- In two dimensions, each component of impulse matches the corresponding component of force, so you can work with $`J_x`$ and $`J_y`$ separately.

A tennis racket striking a ball horizontally delivers a horizontal impulse, changing the ball's horizontal momentum.

### Impulse and Force-Time Graphs

Force-time graphs show how force varies during an interaction, which makes them useful for finding impulse.

- The area under a force versus time curve equals the impulse delivered.
- This area is the integral of net force over time.

In a collision, the force often starts at zero, rises to a peak, and returns to zero. The total impulse is the entire area under that curve.

### Force and Momentum-Time Graphs

Momentum-time graphs show how momentum changes, and the slope tells you the net force.

- The slope of a momentum versus time graph at any instant is the net external force at that instant.
- Steeper slopes mean larger net forces.
- A constant slope means a constant net force.
- A changing slope reflects a changing net force.

## Impulse-Momentum Relationship

### Change in Momentum

Change in momentum is the difference between final and initial momentum.

```math
\Delta \vec{p}=\vec{p}-\vec{p}_{0}
```

- $`\Delta \vec{p}`$ is the change in momentum vector.
- $`\vec{p}`$ is the final momentum vector.
- $`\vec{p}_0`$ is the initial momentum vector.

For a baseball being hit, the change in momentum is its momentum after the hit minus its momentum before contact. Because momentum is a vector, watch your signs carefully when direction reverses.

### Impulse-Momentum Theorem

The impulse-momentum theorem connects impulse directly to change in momentum.

```math
\vec{J}=\int_{t_{1}}^{t_{2}} \vec{F}_{\text{net}}(t) dt=\Delta \vec{p}
```

- $`\vec{J}`$ is the impulse vector.
- $`\vec{F}_{\text{net}}(t)`$ is the net external force as a function of time.
- $`\Delta \vec{p}`$ is the change in momentum vector.

This theorem explains why airbags help in crashes: they extend the contact time, which lowers the force while keeping the same impulse and the same change in momentum.

For systems with constant mass, Newton's second law follows directly:

```math
\vec{F}_{\text{net}}=\frac{d \vec{p}}{dt}=m \frac{d \vec{v}}{dt}=m \vec{a}
```

- $`m`$ is the constant mass of the system.
- $`\frac{d \vec{v}}{dt}`$ is the acceleration vector $`\vec{a}`$.

The theorem also covers systems where velocity stays constant but mass changes with time:

```math
\vec{F}_{\text{net}}=\frac{d \vec{p}}{dt}=\frac{d m}{dt} \vec{v}
```

- $`\frac{d m}{dt}`$ is the rate of change of mass with respect to time.
- $`\vec{v}`$ is the constant velocity vector.

This form is useful for rocket propulsion, where mass decreases as fuel is ejected.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

- To find an average force, compute $`\Delta\vec{p}`$ first, then divide by the contact time: $`\vec{F}_{\text{avg}} = \frac{\Delta\vec{p}}{\Delta t}`$.
- Pick a positive direction at the start and stick with it. If an object reverses direction, the initial and final velocities have opposite signs.
- For non-constant forces given as a function of time, integrate $`\vec{F}_{\text{net}}(t)`$ over the interval to get impulse.

### Free Response

- When a force versus time graph is given, break the area into triangles and rectangles, then add them to get total impulse.
- Treat the slope of a momentum versus time graph as net force, and use it to compare forces at different times.
- For variable-mass setups, use $`\vec{F}_{\text{net}} = \frac{dm}{dt}\vec{v}`$ rather than $`m\vec{a}`$.
- Justify claims with the impulse-momentum theorem and units. Showing that impulse units $`\text{N}\cdot\text{s}`$ equal momentum units $`\text{kg}\cdot\text{m/s}`$ supports your reasoning.

### Common Trap

- Do not assume force is constant when a graph shows it changing. Use the area, not a single force value times time.

## Practice Problem 1: Impulse Calculation

A 0.145 kg baseball traveling at 35.0 m/s is hit by a bat, and the ball leaves in the opposite direction at 45.0 m/s. If the bat and ball are in contact for 0.0020 seconds, what is the average force exerted on the ball by the bat?

Solution: First, find the change in momentum of the baseball. Define the initial direction as positive.

Initial momentum: $`p_i = m \times v_i = 0.145 \text{ kg} \times 35.0 \text{ m/s} = 5.075 \text{ kg}\cdot\text{m/s}`$

Final momentum: $`p_f = m \times v_f = 0.145 \text{ kg} \times (-45.0 \text{ m/s}) = -6.525 \text{ kg}\cdot\text{m/s}`$

Change in momentum: $`\Delta p = p_f - p_i = -6.525 \text{ kg}\cdot\text{m/s} - 5.075 \text{ kg}\cdot\text{m/s} = -11.6 \text{ kg}\cdot\text{m/s}`$

Using the impulse-momentum theorem, impulse equals change in momentum: $`J = \Delta p = F_{avg} \times \Delta t`$

Solving for the average force: $`F_{avg} = \frac{\Delta p}{\Delta t} = \frac{-11.6 \text{ kg}\cdot\text{m/s}}{0.0020 \text{ s}} = -5800 \text{ N}`$

The negative sign means the force points opposite to the ball's initial velocity. The average force exerted on the ball by the bat is 5800 N, directed opposite to the ball's initial motion.

## Practice Problem 2: Force-Time Graph Analysis

A 2.0 kg object is initially at rest. A time-varying force is applied to it as follows: the force starts at 0 N, increases linearly to 10 N over 2 seconds, remains constant at 10 N for another 2 seconds, and then decreases linearly to 0 N over the final 2 seconds. Calculate the final velocity of the object after the force has been applied.

Solution: To find the final velocity, determine the impulse delivered, then apply the impulse-momentum theorem.

The impulse equals the area under the force-time graph:

Area of the first triangle (0-2s): $`\frac{1}{2} \times 2 \text{ s} \times 10 \text{ N} = 10 \text{ N·s}`$

Area of the rectangle (2-4s): $`2 \text{ s} \times 10 \text{ N} = 20 \text{ N·s}`$

Area of the second triangle (4-6s): $`\frac{1}{2} \times 2 \text{ s} \times 10 \text{ N} = 10 \text{ N·s}`$

Total impulse: $`J = 10 \text{ N·s} + 20 \text{ N·s} + 10 \text{ N·s} = 40 \text{ N·s}`$

Using the impulse-momentum theorem: $`J = \Delta p = m \times \Delta v`$

Since the object starts from rest, $`\Delta v = v_f - 0 = v_f`$

```math
40 \text{ N·s} = 2.0 \text{ kg} \times v_f
```

```math
v_f = \frac{40 \text{ N·s}}{2.0 \text{ kg}} = 20 \text{ m/s}
```

The final velocity of the object is 20 m/s in the direction of the applied force.

## Common Misconceptions

- **Misconception:** Impulse and momentum are different things only in name.  
  **Actually:** They share the same units, $`\text{N}\cdot\text{s} = \text{kg}\cdot\text{m/s}`$, and impulse equals the change in momentum, so they are tightly linked rather than unrelated.
- **Misconception:** A bigger force always means a bigger change in momentum.  
  **Actually:** What matters is the impulse, which is force times time (or the area under the force-time graph). A small force over a long time can deliver the same impulse as a large force over a short time.
- **Misconception:** The peak force on a force-time graph equals the impulse.  
  **Actually:** The impulse is the area under the whole curve, not the height of the peak.
- **Misconception:** You can ignore direction because impulse is "just a push."  
  **Actually:** Impulse is a vector. When an object bounces back, the change in momentum can be much larger than you expect because the velocity changes sign.
- **Misconception:** Newton's second law is always $`\vec{F} = m\vec{a}`$.  
  **Actually:** That form assumes constant mass. When mass changes with time, you need the full momentum form $`\vec{F}_{\text{net}} = \frac{d\vec{p}}{dt}`$, which can include a $`\frac{dm}{dt}\vec{v}`$ term.

## Related AP Physics C: Mechanics Guides

- [4.1 Linear Momentum](01-linear-momentum.md)
- [4.3 Conservation of Linear Momentum](03-conservation-of-linear-momentum.md)
- [4.4 Elastic and Inelastic Collisions](04-elastic-and-inelastic-collisions.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| change in momentum | The difference between an object's final momentum and its initial momentum, represented as Δp = p - p₀. |
| impulse | A vector quantity representing the change in momentum of an object or system, calculated as the integral of net force over a time interval or the area under a force-time graph. |
| impulse-momentum theorem | The relationship stating that the impulse exerted on an object equals its change in momentum. |
| momentum | A vector quantity defined as the product of an object's mass and velocity (p=mv), used to describe the motion of objects and systems. |
| net external force | The vector sum of all external forces acting on an object or system, which determines the rate of change of the system's momentum. |
| net force | The vector sum of all forces acting on an object or system. |
| Newton's second law of motion | The principle that the net force on an object equals the rate of change of its momentum, expressed as Fnet = dp/dt = ma. |
| rate of change of momentum | The time derivative of momentum, which equals the net external force exerted on a system. |
| vector quantity | A physical quantity that has both magnitude and direction, such as momentum or velocity. |

## Frequently Asked Questions

### What is impulse in AP Physics C Mechanics?

Impulse is the integral of net external force over a time interval. It is a vector and points in the direction of the net force that acts on the system.

### What is the impulse-momentum theorem?

The impulse-momentum theorem says the impulse delivered to a system equals the system's change in momentum: J = integral of F\_net dt = delta p. It connects force over time to a change in motion.

### How do I find impulse from a force-time graph?

Impulse is the area under the net force versus time graph over the interval. If the graph has simple shapes, add areas of rectangles, triangles, or trapezoids with signs based on direction.

### What does the slope of a momentum-time graph represent?

The slope of a momentum versus time graph is the net external force on the system. A steeper slope means a larger net force, and a changing slope means the force is changing.

### Why are vector signs important in impulse problems?

Impulse and momentum are vectors, so direction matters. Choose a positive direction, assign signs to initial and final momentum, and calculate delta p as final momentum minus initial momentum.

### How does AP Physics C use calculus in impulse problems?

Physics C can ask you to integrate a time-varying force to find impulse or interpret derivatives such as F\_net = dp/dt. The calculus connects graph features, symbolic functions, and physical reasoning.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-4/2-change-in-momentum-and-impulse/study-guide/dj7haZ7RqOOTuCat](https://fiveable.me/ap-physics-c-mechanics/unit-4/2-change-in-momentum-and-impulse/study-guide/dj7haZ7RqOOTuCat)</sub>
