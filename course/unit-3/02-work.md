# 3.2 Work

Work is the energy transferred into or out of a system by a force acting over a displacement of the force's point of application. You calculate it with $`W = \int a^b \vec{F}(r) \cdot d\vec{r}`$, which simplifies to $`W = Fd\cos\theta`$ when the parallel component of the force is constant. This connects force, displacement, energy transfer, and the work-energy theorem.

## Why This Matters for the AP Physics C: Mechanics Exam

Work is the bridge between forces and energy, so it shows up across the whole course, not just in Unit 3. Once you can quantify how a force transfers energy, you can analyze motion without tracking every detail of the path, which makes hard problems much faster.

This topic supports several kinds of exam thinking. You will set up and evaluate line integrals for variable forces, read work off force versus displacement graphs, and apply the dot product to handle angles between force and displacement. The first free-response question, the Mathematical Routines question, asks you to derive expressions, use representations, and write a clear, organized analysis. Work problems are ideal practice for that because they reward careful sign tracking and tying each formula back to its physical meaning. Energy methods built on work also feed directly into potential energy, conservation of energy, and power.

## Key Takeaways

- Work transfers energy: $`W = \int_a^b \vec{F}(r) \cdot d\vec{r}`$, and $`W = F_\parallel d = Fd\cos\theta`$ when the parallel component is constant.
- Only the force component parallel to the displacement of the point of application changes the system's total energy. A perpendicular component does no work.
- Work is a scalar that can be positive, negative, or zero, so you add contributions from multiple forces algebraically with signs.
- Conservative forces (gravity, ideal springs) do path-independent work, and their closed-path work is zero. Nonconservative forces (friction, air resistance) are path-dependent.
- The work-energy theorem, $`\Delta K = \sum W_i`$, links net work to the change in kinetic energy and applies to all forces.
- Work equals the area under an $`F_\parallel`$ versus displacement graph, with signed areas adding algebraically.

## Energy Transfer through Work

Work is the amount of energy transferred into or out of an object or system by a force exerted over a displacement of the force's point of application. You need to describe work done by a single force or by multiple forces, both for an object modeled as a particle and for a system whose configuration may change.

The focus in this course is analyzing transfers of mechanical energy, while recognizing that some mechanical energy can be dissipated into nonmechanical forms such as thermal energy or sound.

- Work transfers energy when a force moves an object through a distance
- The amount of work depends on both the force magnitude and how far the object moves
- Work can add energy to a system (positive work) or remove energy (negative work)

Conservative forces like gravity do work that depends only on the starting and ending positions, not the path taken between them. When an object under a conservative force returns to its starting point, the net work done is zero.

Nonconservative forces like friction behave differently:

- Their work depends on the specific path taken
- They typically convert mechanical energy into thermal energy
- The most common nonconservative forces are friction and air resistance

For friction, the mechanical energy dissipated is typically modeled as the work done by friction: $`\Delta E_{\mathrm{mech}} = F_f d \cos\theta`$, which for kinetic friction opposing motion becomes $`\Delta E_{\mathrm{mech}} = -F_f d`$.

## Path Independence of Conservative Forces

Conservative forces have a special property: the work they do depends only on the initial and final positions of an object, not the path taken between those positions.

- Gravitational force is conservative, so lifting an object requires the same work regardless of path
- Elastic spring forces are conservative, so stretching a spring stores the same energy regardless of how quickly you stretch it
- When an object moves in a closed path under only conservative forces, the total work is zero

For a conservative force, the work done on the system is related to potential energy by $`W_c = -\Delta U`$. So if the system returns to its initial configuration, $`\Delta U = 0`$ and the net work done by the conservative force is also zero.

This path independence is what lets us define potential energy functions for conservative forces, which makes energy calculations much simpler. Potential energy is associated only with conservative forces. Nonconservative forces such as friction and air resistance do not have corresponding potential energy functions in this course.

## Work as a Scalar Quantity

Work is a scalar quantity, with magnitude but no direction. This sets it apart from vector quantities like force and displacement.

- Work is positive when energy is added to a system
- Work is negative when energy is removed from a system
- Work is zero when no energy is transferred, such as when the displacement is zero or when the force is perpendicular to the displacement

Because work is a scalar, you can add work contributions from different forces algebraically, without breaking them into directional components.

### Work by a Collection of Forces

When several forces act on an object or system, handle each force separately: identify the displacement of the point of application, find the component of each force parallel to that displacement, assign the correct sign, then add the scalar contributions algebraically:

```math
W_{\text{net}} = \sum W_i
```

For example, if an object moves horizontally while an applied force acts forward, friction acts backward, and the normal force and weight act vertically, then $`W_{net} = W_{applied} + W_{friction} + W_{normal} + W_{gravity}`$. Here $`W_{normal} = 0`$ and $`W_{gravity} = 0`$ because those forces are perpendicular to the displacement.

If the system can be modeled as an object, net work changes the object's kinetic energy. If the force changes the configuration of a system, the energy transferred may change the system's configuration or potential energy rather than going entirely into kinetic energy.

## Work by Variable Forces

When forces vary in magnitude or direction along a path, you need calculus to find the work done:

```math
W=\int_{a}^{b} \vec{F}(r) \cdot d \vec{r}
```

This integral sums the infinitesimal work contributions along the path from point $`a`$ to point $`b`$. For common variable forces like springs, this integral can be evaluated to find expressions for work and potential energy.

For a spring following Hooke's Law ($`F = -kx`$), the work done by the spring as it moves from position $`x_1`$ to $`x_2`$ is:

```math
W = \frac{1}{2}k(x_1^2 - x_2^2)
```

## Dot Product in Work Calculations

The dot product is what extracts the force component parallel to displacement, so it is central to calculating work.

```math
\vec{A} \cdot \vec{B} = AB\cos\theta
```

Where $`\theta`$ is the angle between the vectors. For work:

```math
W = \vec{F} \cdot \vec{d} = Fd\cos\theta
```

More precisely, this displacement is the displacement of the point where the force is applied. For a rigid object modeled as a particle, this may match the object's displacement. For a system whose configuration changes, the point of application can move a different distance than the system's center of mass, so the work done by the external force is based on the point-of-application displacement.

This means:

- When force and displacement are parallel ($`\theta = 0°`$), work is maximum ($`W = Fd`$)
- When force and displacement are perpendicular ($`\theta = 90°`$), no work is done ($`W = 0`$)
- When force opposes displacement ($`\theta = 180°`$), work is negative ($`W = -Fd`$)

Only the component of the force parallel to the displacement of the point of application transfers energy to or from the system, so only that component changes the system's total energy. If the parallel component is constant, the work done is $`W = F_{\parallel} d = Fd\cos\theta`$. A component of force perpendicular to the displacement of the system's center of mass can change the direction of the system's motion without changing its kinetic energy.

## Work from a Force-Displacement Graph

Work is equal to the area under a graph of $`F_{\parallel}`$ versus displacement. A positive area represents positive work, a negative area represents negative work, and the total work is the algebraic sum of all signed areas between the curve and the displacement axis.

## Work-Energy Theorem

The work-energy theorem connects work and kinetic energy directly:

```math
\Delta K = \sum W_i = \sum F_{\parallel,i} d_i
```

for constant parallel components, or more generally

```math
\Delta K = \sum \int \vec{F}_i \cdot d\vec{r}
```

This says the change in an object's kinetic energy equals the net work done by all forces acting on it. This theorem:

- Applies to all forces, both conservative and nonconservative
- Lets you analyze complex motion without tracking the entire path
- Connects work and energy in a direct mathematical relationship

In some situations, an external force acts on a system rather than on a single object. The work done by that external force comes from the component of the force parallel to the displacement of the point of application: $`W_{\text{ext}} = \int \vec F_{\text{ext}} \cdot d\vec r_{\text{point}}`$. That transferred energy may appear as a change in the system's kinetic energy, a change in its potential energy, or both. If the system's center of mass and the point of application move the same distance, the system may be modeled as an object, and the external work changes only the system's kinetic energy: $`\Delta K = W_{\text{net}}`$. If they move different distances, the external work can change the system's configuration too, so the transferred energy is not necessarily all kinetic.

This theorem lets you solve problems by focusing on initial and final states instead of the details of motion in between, which simplifies many problems.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

- Decide whether the force is constant or variable first. Constant parallel component means $`W = Fd\cos\theta`$. Variable force means set up $`W = \int_a^b \vec{F}(r) \cdot d\vec{r}`$.
- Always identify the angle between the force and the displacement, then track the sign of $`\cos\theta`$. A force opposing motion gives negative work.
- For a spring or other position-dependent force, evaluate the integral. For a spring, the work done by the spring is $`W = \frac{1}{2}k(x_1^2 - x_2^2)`$.
- Use the work-energy theorem to skip the messy middle of the motion. If you know initial and final speeds, you know net work, and vice versa.

### Free Response

- On the Mathematical Routines question, derive symbolic expressions before plugging in numbers, and state the physical principle you are using.
- When you read work off a graph, label positive and negative areas clearly and add them with signs.
- Write a short, organized explanation that ties each step to a definition or law. Cite the work-energy theorem or the definition of work when you justify a claim.

### Common Trap

- For a system that changes shape, use the displacement of the point of application, not the center of mass, when finding the work done by an external force.

## Common Misconceptions

- **Misconception:** If a force is applied, it must do work.  
  **Actually:** A force does zero work if there is no displacement of its point of application, or if the force is perpendicular to the displacement. Holding a heavy box still does no work on it.
- **Misconception:** Work is a vector.  
  **Actually:** Work is a scalar. It can be positive, negative, or zero, but it has no direction. Add work contributions algebraically, not as vectors.
- **Misconception:** Negative work means the force is negative.  
  **Actually:** Negative work means the force has a component opposite the displacement, removing energy from the object. The force magnitude is still positive.
- **Misconception:** The normal force always does work because it is large.  
  **Actually:** A normal force perpendicular to the displacement does no work, no matter how large it is.
- **Misconception:** Friction's effect depends only on start and end points.  
  **Actually:** Friction is nonconservative and path-dependent. A longer path means more mechanical energy dissipated.
- **Misconception:** A single object can store potential energy.  
  **Actually:** Potential energy belongs to a system of interacting objects through conservative forces, not to one isolated object.
- **Misconception:** You always use the center-of-mass displacement for work.  
  **Actually:** For external work on a system that changes configuration, use the displacement of the point where the force is applied, which can differ from the center-of-mass displacement.

## Practice Problem 1: Work Done by a Constant Force

A 2.0 kg box is pushed 5.0 meters across a horizontal surface by a force of 15 N applied at an angle of 30° below the horizontal. Calculate the work done by this applied force.

**Solution**

To find the work done by the force, use the formula for work with a constant force:

```math
W = F \cdot d \cdot \cos\theta
```

Where:

- $`F = 15`$ N (magnitude of the force)
- $`d = 5.0`$ m (displacement)
- $`\theta = 30°`$ (angle between force and displacement)

The force is applied 30° below the horizontal, but the displacement is horizontal, so the angle between them is 30°.

```math
W = (15 \text{ N})(5.0 \text{ m})(\cos 30°)
```

```math
W = (15 \text{ N})(5.0 \text{ m})(0.866)
```

```math
W = 65.0 \text{ J}
```

The work done by the applied force is 65.0 joules.

## Practice Problem 2: Work-Energy Theorem Application

A 0.5 kg ball is thrown upward with an initial speed of 12 m/s. Using the work-energy theorem, calculate the work done by gravity when the ball reaches its maximum height.

**Solution**

By the work-energy theorem, the work done equals the change in kinetic energy:

```math
W = \Delta KE = KE_f - KE_i
```

At the maximum height, the ball's velocity is zero, so $`KE_f = 0`$. The initial kinetic energy is $`KE_i = \frac{1}{2}mv_i^2`$.

```math
KE_i = \frac{1}{2}(0.5 \text{ kg})(12 \text{ m/s})^2 = \frac{1}{2}(0.5 \text{ kg})(144 \text{ m}^2/\text{s}^2) = 36 \text{ J}
```

So the work done by gravity is:

```math
W = 0 \text{ J} - 36 \text{ J} = -36 \text{ J}
```

The negative sign shows that gravity removes kinetic energy from the ball as it rises, converting it to gravitational potential energy.

## Related AP Physics C: Mechanics Guides

- [3.3 Potential Energy](03-potential-energy.md)
- [3.4 Conservation of Energy](04-conservation-of-energy.md)
- [3.1 Translational Kinetic Energy](01-translational-kinetic-energy.md)
- [3.5 Power](05-power.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| air resistance | A nonconservative force exerted by air on a moving object that opposes its motion. |
| center of mass | The point in a system where the entire mass can be considered to be concentrated for the purposes of analyzing motion and forces. |
| conservative force | A force for which the work done is path-independent and depends only on the initial and final configurations of the system. |
| displacement | A vector quantity representing the change in position from an initial to a final location. |
| dot product | A mathematical operation between two vectors that results in a scalar quantity equal to the product of their magnitudes and the cosine of the angle between them. |
| friction | A nonconservative force that opposes motion and dissipates mechanical energy. |
| kinetic energy | The energy possessed by an object due to its motion, equal to one-half the product of its mass and the square of its velocity. |
| mechanical energy | The total energy of a system due to its motion and position, equal to the sum of kinetic and potential energies. |
| net work | The sum of all work done by all forces exerted on an object. |
| nonconservative force | A force for which the work done is path-dependent, such as friction or air resistance. |
| potential energy | The energy stored in a system due to the relative positions or configurations of objects that interact via conservative forces. |
| scalar | A physical quantity that has only magnitude and no direction. |
| work | Energy transferred to or from a system by forces or torques acting on it. |
| work-energy theorem | The principle stating that the change in an object's kinetic energy equals the net work done by all forces exerted on the object. |

## Frequently Asked Questions

### What is work in AP Physics C: Mechanics?

Work is the energy transferred into or out of a system by a force acting over a displacement. In AP Physics C, the general definition is W = integral from a to b of F(r) dot dr.

### What is the work equation for a constant force?

When the component of force parallel to displacement is constant, work is W = F\_parallel d = Fd cos theta. Only the component of the force parallel to the displacement changes the system's total energy.

### How do I find work from a force-displacement graph?

Work is the signed area under a graph of F\_parallel versus displacement. Areas above the axis are positive work, areas below the axis are negative work, and the total work is the algebraic sum.

### What is the work-energy theorem?

The work-energy theorem says the change in kinetic energy equals the net work done by all forces: Delta K = sum Wi. It lets you connect forces and motion through energy transfer.

### What is the difference between conservative and nonconservative work?

Conservative-force work is path-independent and has an associated potential energy. Nonconservative-force work, such as friction or air resistance, depends on the path and often dissipates mechanical energy.

### What mistake should I avoid with work on systems?

For a system that changes configuration, use the displacement of the point where the force is applied, not automatically the center-of-mass displacement. That distinction matters for external work and energy transfer.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-3/2-work/study-guide/Y8X1HNf1OSe29MGP](https://fiveable.me/ap-physics-c-mechanics/unit-3/2-work/study-guide/Y8X1HNf1OSe29MGP)</sub>
