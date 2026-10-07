# 2.1 Properties and Interactions of a System

A system's behavior comes from how its parts interact, and you can often model a whole system as a single point at its center of mass. In AP Physics C: Mechanics, this topic focuses on internal versus external interactions, center-of-mass models, and center-of-mass calculations for discrete masses and continuous objects.

## Why This Matters for the AP Physics C: Mechanics Exam

This topic sets up the way you analyze every force and motion problem for the rest of the course. Once you can locate a center of mass and decide how to model a system, you can apply Newton's laws to the system as a whole using only external forces, which is the foundation for free-body diagrams, momentum, and rotation later on.

Center of mass calculations show up in both multiple-choice and free-response work, including problems with discrete particles and integrals for nonuniform objects. The reasoning side, deciding when a system acts like a single object and explaining why internal forces do not move the center of mass, fits the kind of translation between words and math that the free-response section rewards. Building fluency with both the calculation and the explanation prepares you for questions that ask you to justify a claim, not just plug in numbers.

## Key Takeaways

- A system's properties come from the interactions between its parts; internal interactions control relative motion, and external interactions control how the whole system accelerates.
- A system can be modeled as a single point at its center of mass when the internal structure does not matter for the motion you are analyzing.
- For symmetric, uniform objects, the center of mass lies on the lines of symmetry and at their intersection.
- Use $`\vec{x}_{\mathrm{cm}}=\frac{\sum m_{i} \vec{x}_{i}}{\sum m_{i}}`$ for discrete masses and $`\vec{r}_{\mathrm{cm}}=\frac{\int \vec{r}\, dm}{\int dm}`$ for continuous mass distributions.
- For nonuniform objects, write $`dm`$ using a density: $`dm = \lambda\, d\ell`$, $`dm = \sigma\, dA`$, or $`dm = \rho\, dV`$, then integrate.
- Internal forces never change the motion of the center of mass; only a net external force does.

## How Systems Work in Mechanics

A system is just the set of objects you choose to study together. The properties you care about, like total mass and how it moves, come from the interactions among those objects and with the environment.

### Internal vs external interactions

Start every problem by deciding what is inside your system and what is outside.

- Internal interactions are forces between objects in the system. They control how the parts move relative to each other, but they do not move the system's center of mass.
- External interactions are forces from the environment. They are what change the motion of the system as a whole.
- Example: In two blocks connected by a rope, the rope tension is internal if both blocks are in your system. The friction from the ground is external.

### When you can treat a system as one object

If the internal details do not matter for the motion you want, you can model the whole system as a single point mass at its center of mass and apply Newton's second law using only external forces:

```math
\Sigma F_{\text{ext}} = M a_{\text{cm}}
```

- A car analyzed for its overall trajectory can be a point mass.
- The Earth-Moon system can be treated as one object when studying its orbit around the Sun.
- This works best when the internal structure stays roughly constant.

### Energy and mass transfer across boundaries

Systems can exchange energy or mass with their surroundings, and that affects which models apply.

- Open systems allow both energy and mass to cross the boundary.
- Closed systems allow energy transfer but not mass transfer.
- Isolated systems exchange neither.
- When energy or mass crosses the boundary, you have to account for that interaction before applying a momentum, energy, or center-of-mass model to the system you chose.

### Individual parts vs the whole

Different objects in the same system can have different accelerations, velocities, and forces, even while the center of mass follows simpler motion set by the net external force.

- In a two-block system connected by a rope, each block can have different forces acting on it.
- In an exploding object, the fragments fly apart in different directions, but the center of mass keeps moving according to the net external force.

### Internal structure and external changes

The internal structure decides what model is valid.

- A rigid body keeps fixed distances between its parts. A set of connected masses may need separate free-body diagrams. A deformable object can store elastic energy and may not move as one rigid unit.
- Two systems with the same total mass can behave very differently if their parts are free to move.

As you change external variables, the substructure can change, and that can break a model.

- Two blocks moving together act as one system only while they stay in contact. A large enough external force can separate them, and the single-object model fails.
- A spring-mass system might start as a compact object, but once the spring stretches a lot, you have to include the internal structure.

## Finding the Center of Mass

The center of mass is the mass-weighted average position of all the particles in a system. It gives you one point that follows predictable motion under the net external force.

### Using symmetry

For an object with a symmetric, uniform mass distribution, the center of mass lies on any line or plane of symmetry. If there are several symmetry lines, it sits at their intersection.

- A uniform sphere's center of mass is at its center.
- A uniform rod's center of mass is at its midpoint.
- For uniform density, the center of mass matches the geometric center.

### Discrete masses

For a set of separate masses, use the weighted average:

```math
\vec{x}_{\mathrm{cm}}=\frac{\sum m_{i} \vec{x}_{i}}{\sum m_{i}}
```

- The denominator is the total mass of the system.
- Apply it separately to each coordinate (x, y, z).
- For a two-particle system, the center of mass is closer to the more massive object.

### Continuous and nonuniform objects

When mass is spread out continuously, switch to an integral:

```math
\vec{r}_{\mathrm{cm}}=\frac{\int \vec{r} \, dm}{\int dm}
```

- Write $`dm`$ using a density that matches the geometry:
  
  - Line: $`dm = \lambda\, d\ell`$, where linear mass density is $`\lambda=\frac{d}{d \ell} m(\ell)`$
  - Surface: $`dm = \sigma\, dA`$
  - Volume: $`dm = \rho\, dV`$
- Total mass comes from integrating that density over the object: $`M = \int \lambda\, d\ell`$, $`M = \int \sigma\, dA`$, or $`M = \int \rho\, dV`$.
- For a nonuniform object, the center of mass usually does not sit at the geometric center.

### Modeling the system at its center of mass

For translational motion, you can treat the system as a single particle at its center of mass and apply Newton's second law to the whole thing:

```math
\Sigma F_{\text{ext}} = M a_{\text{cm}}
```

- External forces effectively act at the center of mass.
- Internal forces do not move the center of mass.
- This is what makes projectile motion, collisions, and orbital problems manageable.
- With no net external force, the center of mass moves at constant velocity.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

- For discrete masses, total the mass first, then compute each coordinate of the center of mass separately. Keep units attached the whole way through.
- For nonuniform objects, set up $`dm`$ from the right density before integrating. The numerator is $`\int \vec{r}\, dm`$ and the denominator is the total mass $`\int dm`$.
- Check that your answer leans toward the heavier or denser side. If a rod is denser near $`x = L`$, the center of mass should be past the midpoint.

### Free Response

- Be ready to explain, in words, when a system can be treated as a single object and why internal forces do not change the center of mass motion.
- When asked to justify a claim, connect your reasoning to the net external force and the center-of-mass model rather than only showing a calculation.
- Practice translating between a verbal description, a diagram, and the equation so you can move smoothly between them.

### Common Trap

- Do not assume the center of mass is at the geometric center for a nonuniform object. Set up the integral instead.
- Do not include internal forces when finding the acceleration of the center of mass.

## Common Misconceptions

- **Misconception:** The center of mass is always the geometric center.  
  **Actually:** The center of mass is not always the geometric center. For uniform, symmetric objects it is, but for varying density you have to calculate it.
- **Misconception:** Internal forces move the center of mass.  
  **Actually:** Internal forces do not move the center of mass. No matter how parts push or pull on each other inside the system, only a net external force changes the center of mass motion.
- **Misconception:** A system has to be one solid object.  
  **Actually:** A system does not have to be one solid object. It is any group of objects you choose to analyze together, and the center of mass formula still applies.
- **Misconception:** Treating a system as a single point mass means the parts all move the same way.  
  **Actually:** Treating a system as a single point mass does not mean the parts all move the same way. Individual objects can have different velocities and accelerations even while the center of mass follows simple motion.
- **Misconception:** Mass crossing the boundary does not matter.  
  **Actually:** Mass crossing the boundary matters. If mass or energy enters or leaves, you cannot blindly apply a closed-system model to your chosen system.

## Practice Problem 1: Center of Mass Calculation

A system consists of three objects with masses and positions as follows:

- Object 1: mass = 2 kg, position = (0, 0, 0) m

- Object 2: mass = 3 kg, position = (4, 0, 0) m

- Object 3: mass = 5 kg, position = (2, 3, 0) m

Calculate the position of the center of mass of this system.

**Solution**

To find the center of mass of this discrete system, we need to apply the formula: $`\vec{x}_{\mathrm{cm}}=\frac{\sum m_{i} \vec{x}_{i}}{\sum m_{i}}`$

First, let's calculate the total mass of the system: $`M_{total} = m_1 + m_2 + m_3 = 2 \text{ kg} + 3 \text{ kg} + 5 \text{ kg} = 10 \text{ kg}`$

Now, we'll calculate the center of mass coordinates:

For the x-coordinate: $`x_{cm} = \frac{m_1x_1 + m_2x_2 + m_3x_3}{M_{total}} = \frac{(2 \text{ kg})(0 \text{ m}) + (3 \text{ kg})(4 \text{ m}) + (5 \text{ kg})(2 \text{ m})}{10 \text{ kg}} = \frac{0 + 12 + 10}{10} = \frac{22}{10} = 2.2 \text{ m}`$

For the y-coordinate: $`y_{cm} = \frac{m_1y_1 + m_2y_2 + m_3y_3}{M_{total}} = \frac{(2 \text{ kg})(0 \text{ m}) + (3 \text{ kg})(0 \text{ m}) + (5 \text{ kg})(3 \text{ m})}{10 \text{ kg}} = \frac{0 + 0 + 15}{10} = \frac{15}{10} = 1.5 \text{ m}`$

For the z-coordinate: $`z_{cm} = \frac{m_1z_1 + m_2z_2 + m_3z_3}{M_{total}} = \frac{(2 \text{ kg})(0 \text{ m}) + (3 \text{ kg})(0 \text{ m}) + (5 \text{ kg})(0 \text{ m})}{10 \text{ kg}} = 0 \text{ m}`$

Therefore, the center of mass of the system is located at position (2.2 m, 1.5 m, 0 m).

## Practice Problem 2: System as a Single Object

A 1500 kg car and a 500 kg trailer move together at the same velocity. Explain when the car-trailer combination can be treated as a single system, and determine the x-coordinate of the center of mass if the car's center is at x = 2.0 m and the trailer's center is at x = 8.0 m.

**Solution**

The car-trailer combination can be treated as a single system when internal forces between the car and trailer (such as the tension in the hitch) are not needed for the motion being analyzed. For example, if we only care about the overall acceleration of the combination due to an external force like friction or a hill, we can lump the two objects together and apply Newton's second law to the whole system.

To find the center of mass: $`x_{cm} = \frac{m_{\text{car}} \cdot x_{\text{car}} + m_{\text{trailer}} \cdot x_{\text{trailer}}}{m_{\text{car}} + m_{\text{trailer}}}`$

```math
x_{cm} = \frac{(1500 \text{ kg})(2.0 \text{ m}) + (500 \text{ kg})(8.0 \text{ m})}{1500 \text{ kg} + 500 \text{ kg}} = \frac{3000 + 4000}{2000} = \frac{7000}{2000} = 3.5 \text{ m}
```

Therefore, the center of mass of the car-trailer system is at $`x = 3.5 \text{ m}`$. Notice that the center of mass is closer to the car, which makes sense because the car is three times more massive than the trailer.

## Practice Problem 3: Nonuniform Mass Distribution

A thin rod of length L has a linear mass density that varies according to the function λ(x) = λ₀(1 + x/L), where x is measured from one end of the rod and λ₀ is a constant. Find the position of the center of mass of the rod relative to the end where x = 0.

**Solution**

For a continuous mass distribution like this rod with varying linear density, we need to use calculus to find the center of mass.

The center of mass along the x-axis is given by: $`x_{cm} = \frac{\int x \, dm}{\int dm}`$

For a rod with linear mass density λ(x), we have dm = λ(x)dx, so: $`x_{cm} = \frac{\int_0^L x \, λ(x) \, dx}{\int_0^L λ(x) \, dx}`$

First, let's calculate the total mass by integrating the linear density function: $`M = \int_0^L λ(x) \, dx = \int_0^L λ_0(1 + \frac{x}{L}) \, dx = λ_0 \int_0^L (1 + \frac{x}{L}) \, dx`$

```math
M = λ_0 \left[x + \frac{x^2}{2L}\right]_0^L = λ_0 \left[L + \frac{L^2}{2L}\right] = λ_0 \left[L + \frac{L}{2}\right] = \frac{3}{2}λ_0 L
```

Now, let's calculate the numerator: $`\int_0^L x \, λ(x) \, dx = \int_0^L x \, λ_0(1 + \frac{x}{L}) \, dx = λ_0 \int_0^L (x + \frac{x^2}{L}) \, dx`$

```math
= λ_0 \left[\frac{x^2}{2} + \frac{x^3}{3L}\right]_0^L = λ_0 \left[\frac{L^2}{2} + \frac{L^3}{3L}\right] = λ_0 \left[\frac{L^2}{2} + \frac{L^2}{3}\right] = λ_0 L^2 \left(\frac{1}{2} + \frac{1}{3}\right) = \frac{5}{6}λ_0 L^2
```

Finally, we can calculate the center of mass: $`x_{cm} = \frac{\frac{5}{6}λ_0 L^2}{\frac{3}{2}λ_0 L} = \frac{5}{6} \cdot \frac{2}{3} \cdot L = \frac{10}{18}L = \frac{5L}{9}`$

Therefore, the center of mass is located at $`x = \frac{5L}{9}`$ from the end where x = 0. This is slightly beyond the midpoint of the rod, which makes sense because the rod is denser toward the x = L end.

## Related AP Physics C: Mechanics Guides

- [2.2 Forces and Free-Body Diagrams](02-forces-and-free-body-diagrams.md)
- [2.3 Newton's Third Law](03-newtons-third-law.md)
- [2.4 Newton's First Law](04-newtons-first-law.md)
- [2.6 Gravitational Force](06-gravitational-force.md)
- [2.7 Kinetic and Static Friction](07-kinetic-and-static-friction.md)
- [2.9 Resistive Forces](09-resistive-forces.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| center of mass | The point in a system where the entire mass can be considered to be concentrated for the purposes of analyzing motion and forces. |
| constituent objects | The individual objects that make up a system. |
| differential mass | An infinitesimally small element of mass, denoted as dm, used in integration to calculate properties of nonuniform solids. |
| internal structure | The arrangement and organization of constituent parts within a system that affects how the system behaves and is analyzed. |
| lines of symmetry | Imaginary lines about which a system's mass distribution is balanced, and where the center of mass is located for symmetrical objects. |
| macroscopic system | A system large enough to be observed and analyzed at the scale of everyday objects, which can sometimes be treated as a single object. |
| mass density | The mass per unit length, area, or volume of a material or object, used to determine total mass through integration. |
| nonuniform solid | An object with varying mass density throughout its volume, requiring integration to determine its center of mass. |
| substructure | The internal organization and arrangement of components within a system that may change as external variables change. |
| symmetrical mass distribution | A distribution of mass in an object or system that is balanced about one or more lines or planes of symmetry. |
| system | A defined collection of objects whose energy and interactions are being analyzed. |
| system properties | The characteristics and behaviors of a system that are determined by the interactions between objects within it. |

## Frequently Asked Questions

### What is a system in AP Physics C Mechanics?

A system is the set of objects you choose to analyze together. Its properties depend on interactions among the parts and with the environment.

### What is the difference between internal and external interactions?

Internal interactions occur between objects inside the chosen system, while external interactions come from the environment. External interactions can change the motion of the system as a whole.

### What is center of mass?

The center of mass is the mass-weighted average position of a system. A system can often be modeled as one object located at its center of mass.

### What is the center of mass formula for discrete masses?

Along one axis, x\_cm = sum(m\_i x\_i) / sum(m\_i). In vector form, use the mass-weighted average of each position vector.

### How do you find center of mass for a continuous object?

For a continuous object, use r\_cm = integral(r dm) / integral(dm). Rewrite dm using the appropriate density, such as lambda d ell for a rod, sigma dA for an area, or rho dV for a volume.

### Where is the center of mass for a symmetric object?

For a uniform object with symmetry, the center of mass lies on the lines of symmetry. If multiple symmetry lines intersect, the center of mass is at their intersection.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-2/1-properties-and-interactions-of-a-system/study-guide/Hw10Krhy0qtfeWAb](https://fiveable.me/ap-physics-c-mechanics/unit-2/1-properties-and-interactions-of-a-system/study-guide/Hw10Krhy0qtfeWAb)</sub>
