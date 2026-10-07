# 3.3 Potential Energy

Potential energy is stored energy that depends on the positions of objects in a system that interact through conservative forces like gravity and springs. It is a scalar tied to configuration, and only changes in potential energy matter, so you get to pick where zero is.

## Why This Matters for the AP Physics C: Mechanics Exam

Potential energy is one of the core ideas you reuse across the whole course, from springs and gravitation to oscillations and orbits. On the exam you will need to derive symbolic expressions, calculate values with correct units, and read potential energy graphs to make and justify claims about motion and equilibrium. The first free-response question rewards clean mathematical reasoning, and potential energy is ideal practice for it because it connects calculus (integrals and derivatives) directly to physical meaning. You will also use these ideas constantly in the next topic, conservation of energy.

## Key Takeaways

- Potential energy belongs to a system of two or more objects that interact only through conservative forces; a single object alone cannot store potential energy.
- It is a scalar tied to position/configuration, and only differences in potential energy are physically meaningful, so the zero point is your choice.
- Force and potential energy are connected by $`\Delta U=-\int_{a}^{b} \vec{F}_{cf}(r) \cdot d \vec{r}`$ and, in one dimension, $`F_x = -\dfrac{dU}{dx}`$.
- On a $`U(x)`$ graph, forces point toward decreasing potential energy; local minima are stable equilibrium and local maxima are unstable equilibrium.
- Know the standard formulas: $`U_s = \frac{1}{2}k(\Delta x)^2`$, $`U_g = -G\dfrac{m_1 m_2}{r}`$, and the near-surface approximation $`\Delta U_g = mg\Delta y`$.
- For systems of more than two objects, total potential energy is the sum of every pair's contribution.

## Potential Energy of a System

A system has potential energy only when the objects in it interact through conservative forces. Potential energy is a property of the system, not of a single object by itself.

### Conservative Forces

Conservative forces let a system store energy that can be fully recovered later. The work they do depends only on the start and end configurations, not the path.

- Gravity and ideal spring forces are the conservative forces you use most in AP Physics C: Mechanics.
- When objects interact only through conservative forces, the system has potential energy.
- The work done by a conservative force is path-independent, so the work around any closed loop is zero.
- Friction and air resistance are nonconservative, and their work is path-dependent.

### Scalar Nature of Potential Energy

Potential energy is a scalar, so it has magnitude but no direction.

- It is associated with the positions (configuration) of objects in a system.
- The change in potential energy between two configurations is the same no matter how the system moves between them.
- You combine potential energies using ordinary addition and subtraction.

### Choosing Zero Potential Energy

You pick where potential energy equals zero to make the analysis simpler, because only changes in potential energy have physical meaning.

- There is no absolute zero of potential energy; only differences matter.
- Common reference choices include:
  
  - Ground level for near-surface gravity, so heights above ground give positive values.
  - The spring's equilibrium length, so any stretch or compression stores positive energy.
  - Infinite separation for two point masses, which makes all finite separations negative.
- Shifting the reference point shifts every potential energy value by the same constant, leaving differences unchanged.

### Relationship to Conservative Forces

Potential energy and conservative forces are linked through calculus, so you can find one from the other. The change in potential energy equals the negative of the work done by the conservative force:

```math
\Delta U=-\int_{a}^{b} \vec{F}_{c f}(r) \cdot d \vec{r}
```

This means:

- When a conservative force does positive work, potential energy decreases.
- When a conservative force does negative work, potential energy increases.
- The total change in potential energy around any closed path is zero.

### Force from the Slope of Potential Energy

In one dimension, force is the negative slope of the potential energy curve:

```math
F_{x}=-\frac{d U(x)}{d x}
```

Key insights from this relationship:

- Forces point in the direction of decreasing potential energy ("downhill" on the curve).
- A steeper curve means a stronger force.
- Flat regions correspond to zero force.
- The negative sign tells you the force acts to lower potential energy.

### Reading Potential Energy Graphs

A graph of $`U(x)`$ shows the energy landscape an object moves through.

- The shape of the curve tells you where forces exist and which way they point.
- For a given total mechanical energy $`E`$, motion is allowed only where $`K = E - U(x) \ge 0`$. Positions where $`E = U(x)`$ are turning points, where the object reverses direction.
- Equilibrium positions occur where the slope is zero, so $`dU/dx = 0`$ and $`F_x = 0`$.
- Stable equilibrium positions are local minima of $`U(x)`$.
- Unstable equilibrium positions are local maxima of $`U(x)`$.

### Stable vs Unstable Equilibrium

At equilibrium the net force is zero, which matches a horizontal point on the potential energy curve. To classify it, imagine a small displacement. Because $`F_x = -dU/dx`$, a restoring force points back toward equilibrium at a minimum, and a force pushing farther away appears at a maximum.

Stable equilibrium:

- Located at local minima (valleys) of $`U(x)`$.
- A small displacement produces a force opposite the displacement, so the object accelerates back toward equilibrium.
- The second derivative of potential energy is positive (concave up).
- Example: a ball resting in a bowl.

Unstable equilibrium:

- Located at local maxima (hills) of $`U(x)`$.
- A small displacement produces a force in the same direction as the displacement, so the object accelerates farther away.
- The second derivative of potential energy is negative (concave down).
- Example: a ball balanced on top of a dome.

### Common Physical Systems

Each standard system has its own potential energy formula.

Elastic spring potential energy: $`U_{s}=\frac{1}{2} k(\Delta x)^{2}`$

- $`k`$ is the spring constant (stiffness).
- $`\Delta x`$ is the distance stretched or compressed from the equilibrium length.
- Energy increases with the square of displacement.
- It is positive for any displacement from equilibrium.

Gravitational potential energy between two point-like masses: $`U_{g}=-G \frac{m_{1} m_{2}}{r}`$

- $`G`$ is the universal gravitational constant.
- $`m_1`$ and $`m_2`$ are the two approximately spherical masses (e.g., moons, planets, or stars).
- $`r`$ is the distance between their centers.
- It is negative because gravity is attractive, with the zero reference at infinite separation.

Gravitational potential energy near a planet's surface: $`\Delta U_{g}=m g \Delta y`$

- $`m`$ is the object's mass.
- $`g`$ is the gravitational field magnitude near the surface (about 9.8 m/s² on Earth).
- $`\Delta y`$ is the change in height.
- This approximation works when the field is nearly constant, meaning height changes are small compared to the planet's radius.

### Multiple-Object Systems

When more than two objects interact through conservative forces, add up the pairs.

- Total potential energy equals the sum of all pairwise potential energies.
- For $`n`$ objects there are $`\dfrac{n(n-1)}{2}`$ pairs to include.
- Each pair contributes through its appropriate formula.
- The resulting landscape may have several equilibrium points.

## How to Use This on the AP Physics C: Mechanics Exam

### Free Response

- When asked to derive an expression for a conservative force, start from $`U(x)`$ and apply $`F_x = -dU/dx`$. Show the derivative step clearly.
- When asked for $`\Delta U`$ from a force, set up $`\Delta U=-\int \vec{F}_{cf}\cdot d\vec{r}`$ with correct limits, and watch the sign.
- State your zero reference explicitly when you write a potential energy expression, since the choice affects your numbers but not your physics.
- When you explain motion in a reasoned analysis, cite the specific principle (for example, force points toward decreasing $`U`$, or a local minimum means stable equilibrium) and tie it back to the graph or equation.

### Problem Solving

- For springs, plug straight into $`U_s = \frac{1}{2}k(\Delta x)^2`$ and remember $`\Delta x`$ is measured from equilibrium, not from the wall or floor.
- For wide height changes or orbital problems, use $`U_g = -G\dfrac{m_1 m_2}{r}`$. For small heights near the surface, $`\Delta U_g = mg\Delta y`$ is the faster tool.
- To find and classify equilibrium points, solve $`dU/dx = 0`$, then check the sign of $`d^2U/dx^2`$: positive means stable, negative means unstable.

### Graph Reading

- Find turning points where the horizontal total-energy line crosses $`U(x)`$, since that is where $`K = 0`$.
- Identify allowed regions as the places where the total-energy line sits above the curve.
- Read force direction by noting which way the curve slopes; the force pushes toward lower $`U`$.

## Common Misconceptions

- **Misconception:** A single object has potential energy.  
  **Actually:** Potential energy belongs to a system of at least two interacting objects, such as an object and Earth, or a block and a spring.
- **Misconception:** Potential energy has a true zero value.  
  **Actually:** Only differences in potential energy are physical. The zero point is a choice you make to simplify the problem.
- **Misconception:** Negative potential energy means something is wrong.  
  **Actually:** For two point masses, $`U_g = -Gm_1m_2/r`$ is negative by design because the zero reference is at infinite separation.
- **Misconception:** Force points uphill on a $`U(x)`$ graph.  
  **Actually:** Force points toward decreasing potential energy, so it points downhill on the curve.
- **Misconception:** $`\Delta U_g = mg\Delta y`$ always works.  
  **Actually:** That formula assumes a nearly constant field near the surface. For large distances or orbits, use $`U_g = -Gm_1m_2/r`$.
- **Misconception:** Any point where $`dU/dx = 0`$ is stable.  
  **Actually:** A zero slope only means equilibrium. You must check the second derivative (or the shape of the curve) to know whether it is stable or unstable.
- **Misconception:** Potential energy is a vector because forces have direction.  
  **Actually:** Potential energy is a scalar. You recover the force direction through the derivative, not from a direction stored in $`U`$ itself.

## Practice Problem 1: Spring Potential Energy

A 2.0 kg block is attached to a spring with spring constant k = 100 N/m. If the spring is compressed 0.15 m from equilibrium, what is the elastic potential energy stored in the spring?

**Solution**

We calculate the potential energy stored in the compressed spring using the formula: $`U_s = \frac{1}{2}k(\Delta x)^2`$

Given:

- Spring constant k = 100 N/m
- Displacement Δx = 0.15 m

```math
U_s = \frac{1}{2}(100)(0.15)^2 = 1.125\ \text{J}
```

Therefore, the elastic potential energy stored is 1.125 J.

## Practice Problem 2: Gravitational Potential Energy

A 0.5 kg ball is thrown upward from the ground with an initial velocity of 15 m/s. (a) What is the ball's gravitational potential energy at its maximum height? (b) What is this maximum height?

**Solution**

Using conservation of energy, the initial kinetic energy converts to gravitational potential energy at the maximum height.

Initial kinetic energy: $`KE_i = \frac{1}{2}mv_i^2 = \frac{1}{2} \times 0.5 \text{ kg} \times (15 \text{ m/s})^2 = \frac{1}{2} \times 0.5 \times 225 = 56.25 \text{ J}`$

(a) At the maximum height, the ball's velocity is zero, so all of its initial kinetic energy has become gravitational potential energy (measured from the ground): $`U_g = KE_i = 56.25 \text{ J}`$

(b) To find the maximum height, use the near-surface formula for gravitational potential energy: $`U_g = mgh`$

Rearranging for h: $`h = \frac{U_g}{mg} = \frac{56.25 \text{ J}}{0.5 \text{ kg} \times 9.8 \text{ m/s}^2} = \frac{56.25}{4.9} = 11.48 \text{ m}`$

Therefore, the ball's gravitational potential energy at maximum height is 56.25 J, and it reaches a maximum height of 11.48 m.

## Practice Problem 3: Equilibrium Points

A particle moves in a one-dimensional potential energy field described by U(x) = 2x³ - 15x² + 36x + 5 (in joules, with x in meters). Find all positions where the particle would be in equilibrium, and determine whether each equilibrium point is stable or unstable.

**Solution**

Equilibrium occurs where the force is zero. Since $`F_x = -dU/dx`$, we find where $`dU/dx = 0`$.

Taking the derivative: $`\frac{dU}{dx} = 6x^2 - 30x + 36`$

Setting it equal to zero: $`6x^2 - 30x + 36 = 0`$

Dividing by 6: $`x^2 - 5x + 6 = 0`$

Using the quadratic formula: $`x = \frac{5 \pm \sqrt{25-24}}{2} = \frac{5 \pm 1}{2}`$

This gives x = 3 and x = 2.

To classify each point, find the second derivative: $`\frac{d^2U}{dx^2} = 12x - 30`$

At x = 2: $`\frac{d^2U}{dx^2} = 12(2) - 30 = -6`$

Since the second derivative is negative, x = 2 is an unstable equilibrium point (local maximum).

At x = 3: $`\frac{d^2U}{dx^2} = 12(3) - 30 = 6`$

Since the second derivative is positive, x = 3 is a stable equilibrium point (local minimum).

Therefore, the particle has equilibrium points at x = 2 m (unstable) and x = 3 m (stable).

## Related AP Physics C: Mechanics Guides

- [3.2 Work](02-work.md)
- [3.4 Conservation of Energy](04-conservation-of-energy.md)
- [3.1 Translational Kinetic Energy](01-translational-kinetic-energy.md)
- [3.5 Power](05-power.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| conservative force | A force for which the work done is path-independent and depends only on the initial and final configurations of the system. |
| elastic potential energy | The potential energy stored in a spring due to its displacement from equilibrium, given by Us = 1/2 k(Δx)². |
| gravitational potential energy | The energy stored in a system due to the gravitational interaction between a satellite and a central object, defined as zero at infinite distance. |
| ideal spring | A theoretical spring that obeys Hooke's law and stores elastic potential energy proportional to the square of its displacement. |
| local maximum | A point on a potential energy graph where the potential energy is higher than at nearby positions, corresponding to unstable equilibrium. |
| local minimum | A point on a potential energy graph where the potential energy is lower than at nearby positions, corresponding to stable equilibrium. |
| potential energy | The energy stored in a system due to the relative positions or configurations of objects that interact via conservative forces. |
| relaxed length | The natural length of a spring when no external force is applied to it. |
| scalar | A physical quantity that has only magnitude and no direction. |
| stable equilibrium | A position where a small displacement results in a restoring force that accelerates the object back toward the equilibrium position. |
| system | A defined collection of objects whose energy and interactions are being analyzed. |
| unstable equilibrium | A position where a small displacement results in a force that accelerates the object further away from the equilibrium position. |
| zero potential energy | A reference point chosen by an observer to simplify analysis of a system's potential energy. |

## Frequently Asked Questions

### What is potential energy in AP Physics C: Mechanics?

Potential energy is scalar energy associated with the positions of objects in a system that interact through conservative forces. It belongs to the system, not to a single object alone.

### Why can you choose zero potential energy?

Only changes in potential energy are physically meaningful, so the zero point is chosen for convenience. Shifting the reference point changes all U values by a constant but does not change energy differences.

### How are force and potential energy related?

For a conservative force, the change in potential energy is the negative of the work done by that force. In one dimension, force is the negative slope of the potential energy graph: F\_x = -dU/dx.

### How do you identify stable equilibrium on a U(x) graph?

Stable equilibrium occurs at a local minimum of the potential energy graph. A small displacement creates a force that points back toward the equilibrium position.

### What potential energy formulas should you know?

Know elastic potential energy U\_s = 1/2 k(Delta x)^2, gravitational potential energy U\_g = -Gm1m2/r for two masses, and near-surface gravitational change Delta U\_g = mg Delta y.

### How is AP Physics C Mechanics 3.3 tested?

Topic 3.3 is tested through symbolic derivations, calculations, U(x) graph interpretation, equilibrium reasoning, and connections between conservative forces and potential energy.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-3/3-potential-energy/study-guide/I4y3a9MbuG2OgtXM](https://fiveable.me/ap-physics-c-mechanics/unit-3/3-potential-energy/study-guide/I4y3a9MbuG2OgtXM)</sub>
