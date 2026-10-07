# 2.8 Spring Forces

An ideal spring pushes or pulls with a force proportional to how far it is stretched or compressed from its relaxed length, given by Hooke's law $`\vec{F}_s = -k \Delta \vec{x}`$. The force always points back toward equilibrium, and you can combine multiple springs into one equivalent spring using series and parallel rules.

## Why This Matters for the AP Physics C: Mechanics Exam

Spring forces give you a clean example of a position-dependent restoring force, which you will use again in energy and oscillations later in the course. On the exam you may need to set up Newton's second law with a spring force, predict how acceleration or displacement changes when you change the spring constant, or justify a claim about stiffness in words and then back it with math. That kind of translation between a verbal description, a diagram, and an equation is exactly the thinking the free-response section rewards, especially when a question asks you to explain your reasoning before deriving an expression.

## Key Takeaways

- An ideal spring has negligible mass and exerts a force proportional to its stretch or compression from relaxed length. A nonideal spring has mass or a force that is not proportional to its length change.
- Hooke's law is $`\vec{F}_{s}=-k \Delta \vec{x}`$. The negative sign means the force is a restoring force that always points toward the equilibrium position of the object-spring system.
- The spring constant $`k`$ (units N/m) measures stiffness. A larger $`k`$ means a stiffer spring that needs more force for the same displacement.
- Springs in series: $`\frac{1}{k_{\text{eq, series}}}=\sum_{i}\frac{1}{k_{i}}`$. The result is smaller than the smallest individual spring constant.
- Springs in parallel: $`k_{\text{eq, parallel}}=\sum_{i} k_{i}`$. The result is larger than the largest individual spring constant.
- You only need to handle springs in pure series or pure parallel, not mixed arrangements.

## Force of an Ideal Spring

### Ideal vs Nonideal Springs

An ideal spring is a model that makes problems manageable. It has negligible mass and follows a perfectly linear relationship between force and stretch.

- The force is directly proportional to displacement from the relaxed (equilibrium) length.
- The mass of the spring is small enough to ignore compared to the objects it acts on.
- The force-displacement relationship stays linear across the range you analyze.

A nonideal spring breaks at least one of these conditions. By definition, it either has nonnegligible mass or exerts a force that is not proportional to its change in length. In real springs that can show up as nonlinear behavior at large stretches or compressions, or as effects from the spring's own mass.

### Hooke's Law

Hooke's law connects the spring force to displacement for an ideal spring:

```math
\vec{F}_{s}=-k \Delta \vec{x}
```

Where:

- $`\vec{F}_{s}`$ is the spring force vector
- $`k`$ is the spring constant in N/m, which measures stiffness
- $`\Delta \vec{x}`$ is the displacement vector from the relaxed length

The negative sign is the important part. It tells you the spring force always points opposite the displacement, so the spring pushes or pulls back toward equilibrium. That is why it is called a restoring force.

A larger $`k`$ means a stiffer spring. The same stretch produces a bigger force.

### Direction of the Spring Force

The spring force always points toward the equilibrium position of the object-spring system.

When a spring is compressed:

- It is shorter than its relaxed length.
- The force points outward, pushing back toward equilibrium.

When a spring is stretched:

- It is longer than its relaxed length.
- The force points inward, pulling back toward equilibrium.

Because the force depends only on position, the spring force is conservative. You will use this idea later when you work with spring potential energy $`\frac{1}{2}k\Delta x^2`$ in the energy unit.

## Equivalent Spring Constant

### Treating Multiple Springs as One

Several springs acting on the same object can often be replaced by a single equivalent spring with constant $`k_{\text{eq}}`$. This lets you analyze a complex setup as if it were one spring, which simplifies the math without losing accuracy. The value of $`k_{\text{eq}}`$ depends on how the springs are arranged.

### Springs in Series

Springs connected end to end are in series. In this arrangement each spring feels the same force, but the displacements add up.

```math
\frac{1}{k_{\text{eq, series}}}=\sum_{i} \frac{1}{k_{i}}=\frac{1}{k_{1}}+\frac{1}{k_{2}}+\ldots
```

Where:

- $`k_{\text{eq, series}}`$ is the equivalent spring constant for the series combination
- $`k_{i}`$ is the constant of the $`i`$-th spring

Key features of springs in series:

- The combination is less stiff than any single spring in it.
- $`k_{\text{eq, series}}`$ is always smaller than the smallest individual spring constant.
- Each spring feels the same magnitude of force.
- The total displacement is the sum of the individual displacements.

### Springs in Parallel

Springs arranged side by side, connected to the same points, are in parallel. Here each spring has the same displacement, but the forces add up.

```math
k_{\text{eq, parallel}}=\sum_{i} k_{i}=k_{1}+k_{2}+\ldots
```

Where:

- $`k_{\text{eq, parallel}}`$ is the equivalent spring constant for the parallel combination
- $`k_{i}`$ is the constant of the $`i`$-th spring

Key features of springs in parallel:

- The combination is stiffer than any single spring in it.
- $`k_{\text{eq, parallel}}`$ is always greater than the largest individual spring constant.
- Each spring has the same displacement.
- The total force is the sum of the individual forces.

🚫 **Boundary Statement**

You are only expected to find the equivalent spring constant for springs arranged in pure series or pure parallel. You will not be asked to handle systems that mix series and parallel arrangements.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

For a single spring, write Hooke's law, plug in the displacement from the relaxed length, then use Newton's second law if the question asks for acceleration. Keep track of signs so your final direction makes sense.

### Free Response

If a question asks you to explain before you calculate, state in words that the spring force is a restoring force pointing toward equilibrium, then derive the relationship using $`\vec{F}_{s}=-k \Delta \vec{x}`$. Connect the words and the math at the end so your claim and your equation agree.

### Common Trap

Decide whether springs are in series or parallel before picking a formula. Series uses the reciprocal sum and gives a smaller $`k_{\text{eq}}`$, while parallel adds directly and gives a larger one. Mixing these up is the most common mistake on these problems.

## Practice Problem 1: Hooke's Law Application

A 2.0 kg block is attached to a horizontal spring with spring constant k = 100 N/m. The block is pulled 0.15 m from its equilibrium position and released from rest. What is the magnitude of the initial acceleration of the block?

Solution: Apply Hooke's law to find the force, then use Newton's second law to find the acceleration.

Step 1: Find the spring force using Hooke's law. $`F_s = -k \Delta x = -(100 \text{ N/m})(0.15 \text{ m}) = -15 \text{ N}`$

Step 2: Apply Newton's second law to find the acceleration. $`F = ma`$ $`a = \frac{F}{m} = \frac{-15 \text{ N}}{2.0 \text{ kg}} = -7.5 \text{ m/s}^2`$

The negative sign shows the acceleration points opposite the displacement. The magnitude of the initial acceleration is 7.5 m/s².

## Practice Problem 2: Equivalent Spring Constant

Three springs with spring constants $`k_1 = 200 \text{ N/m}`$, $`k_2 = 300 \text{ N/m}`$, and $`k_3 = 600 \text{ N/m}`$ are connected in series. What is the equivalent spring constant of this system?

Solution: For springs in series, use the reciprocal sum:

```math
\frac{1}{k_{\text{eq, series}}} = \frac{1}{k_1} + \frac{1}{k_2} + \frac{1}{k_3}
```

Substituting the given values: $`\frac{1}{k_{\text{eq, series}}} = \frac{1}{200 \text{ N/m}} + \frac{1}{300 \text{ N/m}} + \frac{1}{600 \text{ N/m}}`$

```math
\frac{1}{k_{\text{eq, series}}} = \frac{3}{600 \text{ N/m}} + \frac{2}{600 \text{ N/m}} + \frac{1}{600 \text{ N/m}} = \frac{6}{600 \text{ N/m}} = \frac{1}{100 \text{ N/m}}
```

Therefore, $`k_{\text{eq, series}} = 100 \text{ N/m}`$

This value is smaller than the smallest individual spring constant (200 N/m), which is exactly what you expect for springs in series.

## Common Misconceptions

- **Misconception:** The force in Hooke's law is always negative.  
  **Actually:** The negative sign in Hooke's law does not mean the force is always negative. It means the force always points back toward equilibrium, opposite the displacement. The actual direction depends on whether the spring is stretched or compressed.
- **Misconception:** A nonideal spring is just a stretched-out spring.  
  **Actually:** A "nonideal" spring is not just a stretched-out spring. It specifically means a spring with nonnegligible mass or a force that is not proportional to its change in length.
- **Misconception:** Series springs make the system stiffer.  
  **Actually:** Series springs make the system less stiff, not more. Adding springs in series gives a smaller equivalent constant than the weakest spring, because the displacements add while the force stays the same.
- **Misconception:** Parallel springs share force, not displacement.  
  **Actually:** Parallel springs share displacement, not force. Each parallel spring stretches the same amount, and their forces add, which is why the equivalent constant grows.
- **Misconception:** $`\Delta x`$ is measured from the floor or some other reference point.  
  **Actually:** $`\Delta x`$ is measured from the relaxed length of the spring, not from the floor or some other reference point. Using the wrong reference is a frequent source of sign and magnitude errors.

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
| equilibrium position | The position where the spring force on an object is zero and the object-spring system is at rest. |
| equivalent spring constant | A single spring constant that represents the combined effect of multiple springs exerting forces on an object. |
| Hooke's law | The principle that the force exerted by an ideal spring is proportional to its displacement from equilibrium, expressed as F\_s = -kΔx. |
| ideal spring | A theoretical spring that obeys Hooke's law and stores elastic potential energy proportional to the square of its displacement. |
| nonideal spring | A spring that either has nonnegligible mass or exerts a force that is not proportional to its change in length from its relaxed length. |
| relaxed length | The natural length of a spring when no external force is applied to it. |
| spring constant | A measure of a spring's stiffness, represented by k, that relates the force exerted by the spring to its displacement from equilibrium. |
| springs in parallel | An arrangement of springs connected side-by-side, where each spring experiences the same displacement and forces add together. |
| springs in series | An arrangement of springs connected end-to-end, where the same force is transmitted through each spring and displacements add together. |

## Frequently Asked Questions

### What is Hooke's law in AP Physics C: Mechanics?

Hooke's law says an ideal spring exerts a restoring force proportional to its displacement from relaxed length: F\_s = -k Delta x. The negative sign means the force points back toward equilibrium.

### What is an ideal spring?

An ideal spring has negligible mass and a linear force-displacement relationship. That means the spring force is proportional to the stretch or compression from the relaxed length.

### What does the spring constant k mean?

The spring constant k measures stiffness in newtons per meter. A larger k means a stiffer spring that requires more force for the same displacement.

### How do springs in series combine?

For springs in series, the reciprocal of the equivalent spring constant equals the sum of the reciprocals of the individual spring constants. The equivalent spring constant is smaller than the smallest spring in the set.

### How do springs in parallel combine?

For springs in parallel, the equivalent spring constant is the sum of the individual spring constants. The parallel combination is stiffer than any one spring by itself.

### How is AP Physics C Mechanics 2.8 tested?

Topic 2.8 is tested through Hooke's law, restoring force direction, free-body diagrams, Newton's second law with spring forces, and equivalent spring constants for pure series or pure parallel spring arrangements.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-2/8-spring-forces/study-guide/jtwF1NQEUJXZEYva](https://fiveable.me/ap-physics-c-mechanics/unit-2/8-spring-forces/study-guide/jtwF1NQEUJXZEYva)</sub>
