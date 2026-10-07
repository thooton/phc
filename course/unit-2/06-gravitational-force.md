# 2.6 Gravitational Force

## Gravitation AP Physics C Summary

Gravitational force is the attractive pull between any two objects with mass, given by $`F_g = G\frac{m_1 m_2}{r^2}`$. It always points along the line connecting their centers of mass, weakens with the square of the distance, and shows up as weight near a planet's surface. You also need to handle gravitational fields, apparent weight, and how a uniform sphere pulls on objects inside and outside it.

## Why This Matters for the AP Physics C: Mechanics Exam

This topic gives you the tools to explain and calculate how objects attract each other, which connects to orbits, energy, and circular motion later in the course. On the exam you may need to translate between words, equations, diagrams, and graphs, so being able to describe gravity in plain language and then back it with the right equation is exactly the kind of thinking the free-response section rewards. The Qualitative/Quantitative Translation question can pull content from any unit, so practice stating a claim about gravitational force, then deriving the equation that supports it.

You will also use functional dependence here: predicting how force changes when mass or distance changes is a common multiple-choice and free-response skill. Knowing the difference between true weight and apparent weight helps you reason through elevator and free-fall problems with confidence.

## Key Takeaways

- Use $`F_g = G\frac{m_1 m_2}{r^2}`$ for the attractive force between two masses, measured center to center.
- The gravitational field is $`|\vec{g}| = G\frac{M}{r^2}`$, with units of N/kg, and it equals the acceleration of an object in free fall at that point.
- Weight is $`F_g = mg`$; near Earth's surface, $`g \approx 10`$ N/kg.
- Apparent weight equals the normal force, so it changes when an object accelerates and drops to zero in free fall.
- Inertial mass and gravitational mass have been shown by experiment to be equivalent.
- For a uniform sphere, use Newton's shell theorem: outside, treat it as a point mass at the center; inside, only the mass closer to the center counts, and the force grows in proportion to distance from the center.

## Gravitational Interaction Between Objects

### Newton's Law of Universal Gravitation

Every object with mass attracts every other object with mass. The force is directly proportional to the product of the two masses and inversely proportional to the square of the distance between their centers of mass:

```math
F_g = G\frac{m_1 m_2}{r^2}
```

Where:

- $`F_g`$ is the gravitational force between the objects
- $`G`$ is the universal gravitational constant ($`6.67 \times 10^{-11} \text{ N} \cdot \text{m}^2/\text{kg}^2`$)
- $`m_1`$ and $`m_2`$ are the masses of the two objects
- $`r`$ is the distance between their centers of mass

Key features of this force:

- It is always attractive between objects with mass 🪐
- It acts along the line connecting the two centers of mass
- For an extended object, you can treat its mass as if it sits at the center of mass

Because of the inverse-square relationship, doubling the distance cuts the force to one-fourth. This functional dependence is worth memorizing because it shows up constantly in multiple-choice questions.

### Gravitational Field Model

A field describes the effect of a noncontact force at different points in space. The gravitational field at a point equals the gravitational force per unit mass on a small test object placed there:

```math
\vec{g} = \frac{\vec{F}_g}{m}
```

For a source mass $`M`$ at distance $`r`$, the magnitude is:

```math
|\vec{g}| = \frac{|\vec{F}_g|}{m} = G\frac{M}{r^2}
```

The field points toward the source mass because gravity is attractive.

Where:

- $`\vec{g}`$ is the gravitational field vector at a point in space
- $`\vec{F}_g`$ is the gravitational force on a test mass
- $`m`$ is the test mass placed at that point

What this model tells you:

- The field at a point equals the acceleration a falling object would have there if gravity were the only force acting
- Field strength can be written in N/kg or m/s², and these are numerically equal
- The field gets weaker with distance but never reaches exactly zero

### Weight as Gravitational Force

Weight is the gravitational force a large astronomical body exerts on a relatively small nearby object:

```math
W = F_g = mg
```

This relationship shows that:

- Weight is proportional to mass
- Weight changes with location because $`g`$ changes
- Weight is a force in newtons, while mass is an intrinsic property in kilograms

## Constant Gravitational Force

### When Gravity Can Be Treated as Constant

You can treat the gravitational force as constant when the distance between the two centers of mass barely changes over the motion you are analyzing. If $`r`$ changes only a tiny bit, then $`G\frac{m_1 m_2}{r^2}`$ changes by only a tiny bit too.

For example, when analyzing motion near Earth's surface, you usually assume gravity does not change with height for small vertical displacements. This works because a few meters of change is negligible compared to Earth's radius.

### Earth's Gravitational Field Strength

Near Earth's surface, the gravitational field strength is approximately:

$`g \approx 10 \text{ N/kg}`$ 🌍

This value varies slightly with:

- Latitude (Earth's rotation and non-spherical shape)
- Altitude (it decreases with height)
- Local density variations

## Apparent Weight vs Gravitational Force

### Normal Force as Apparent Weight

Apparent weight is the magnitude of the normal force exerted on a system. When you stand on a scale, the reading equals the normal force the scale pushes up on you, which is your apparent weight. This may or may not equal your true gravitational weight, depending on whether you are accelerating.

### How Acceleration Changes Apparent Weight

When a system accelerates, its apparent weight differs from its true gravitational weight. Taking upward as positive, Newton's second law in the vertical direction gives:

```math
F_N - mg = ma
```

So $`F_N = m(g + a)`$ for upward acceleration and $`F_N = m(g - a)`$ for downward acceleration of magnitude $`a`$.

This explains why:

- You feel heavier in an elevator accelerating upward
- You feel lighter in an elevator accelerating downward
- You feel weightless in free fall, even though gravity still acts on you

### Weightlessness Conditions

A system appears weightless when:

- No forces are exerted on it
- Gravity is the only force acting on it, as in free fall 🪶

In orbit, an object is in continuous free fall around a planet, so there is no normal force to create the sensation of weight, even though gravity is still pulling on it.

### Equivalence Principle

The equivalence principle says an observer in a noninertial reference frame cannot tell the difference between an object's apparent weight and the gravitational force exerted by a gravitational field. In practice:

- In an accelerating elevator, the normal-force sensation feels just like gravity
- Inside a closed elevator with no outside information, you cannot tell whether the apparent weight you feel comes from sitting in a gravitational field or from the elevator accelerating

## Inertial vs Gravitational Mass

### Inertial Mass

Inertial mass measures how much an object resists changes in its motion, as in Newton's second law:

```math
F = m_i a
```

Where $`m_i`$ is the inertial mass. The larger the inertial mass, the more force is needed to produce a given acceleration.

### Gravitational Mass

Gravitational mass measures how strongly an object takes part in the gravitational interaction:

```math
F_g = G\frac{m_{g1} m_{g2}}{r^2}
```

Where $`m_{g1}`$ and $`m_{g2}`$ are the gravitational masses of the two objects.

### Equivalence of the Two

Experiments have confirmed that inertial mass and gravitational mass are equivalent to very high precision. That is why a single number for "mass" works in both Newton's second law and the law of gravitation.

## Gravitational Force of a Spherical Mass

### Net Force from a Mass Distribution

The net gravitational force on an object from a distributed mass is the vector sum of the gravitational forces from all the individual mass elements:

```math
\vec{F}_{net} = \sum \vec{F}_i
```

For continuous shapes, this sum becomes an integral over the differential masses that make up the object.

### Newton's Shell Theorem

Newton's shell theorem gives you shortcuts for spherical objects:

- Outside a uniform spherical shell: the force is the same as if all the shell's mass were a point at the center
- Inside a uniform spherical shell: the net gravitational force is zero, because the pulls from opposite sides cancel
- Inside a solid sphere of uniform density: only the mass closer to the center than the object contributes to the force

These results let you simplify many gravitational problems involving spheres.

### Force Inside a Uniform Sphere

For a sphere of uniform density, the mass enclosed within radius $`r`$ is:

```math
m_{\text{partial}} = \rho \frac{4}{3}\pi r^3
```

Only this enclosed mass pulls on an object located a distance $`r`$ from the center.

For an object at distance $`r`$ from the center of a uniform sphere of radius $`R`$ and total mass $`M`$, with $`r < R`$:

```math
F_g = G\frac{M_r m}{r^2} = G\frac{m}{r^2}\left(\frac{r^3}{R^3}M\right) = G\frac{Mm}{R^3}r
```

In restoring-force form, this is $`F_{g,\partial} = -kr`$, where the negative sign shows the force points toward the center, opposite the displacement.

So inside a uniform sphere:

- The force is directly proportional to distance from the center
- The force decreases linearly to zero at the center
- The motion acts like a harmonic oscillator for an object moving through the sphere

🚫 **Boundary Statement**

AP Physics C: Mechanics does not require you to mathematically prove or derive Newton's shell theorem.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

- Always measure $`r`$ from center to center, not from surface to surface.
- For force comparisons, lean on functional dependence: if $`r`$ triples, the force drops by a factor of 9; if one mass doubles, the force doubles.
- Switch between force and field views when it helps. The field $`g = G\frac{M}{r^2}`$ is just the force per unit mass and gives you acceleration directly.
- For apparent-weight problems, write $`F_N - mg = ma`$ and solve for $`F_N`$. The sign of $`a`$ tells you whether the scale reads more or less than true weight.

### Free Response

- The Qualitative/Quantitative Translation question can use gravitation. Be ready to state a claim in words first, then derive the supporting equation, then connect the two.
- When you derive the field or force, define your variables and keep units attached so your reasoning is easy to follow.
- For inside-a-sphere problems, justify using the enclosed-mass idea before plugging in numbers.

### Common Trap

- Do not confuse weight (a force in newtons) with mass (in kilograms). They are not the same quantity.
- Do not assume gravity is constant when the distance changes a lot, such as far above Earth's surface. The constant-$`g`$ approximation only holds for small changes in $`r`$.

## Practice Problem 1: Gravitational Force Calculation

A 70 kg astronaut is standing on the surface of Mars. The mass of Mars is 6.42 × 10²³ kg and its radius is 3.39 × 10⁶ m. Calculate the gravitational force (weight) experienced by the astronaut on Mars. The universal gravitational constant G = 6.67 × 10⁻¹¹ N·m²/kg².

**Solution**

Use Newton's law of universal gravitation:

```math
F_g = G\frac{m_1 m_2}{r^2}
```

Where:

- $`m_1`$ = mass of Mars = 6.42 × 10²³ kg
- $`m_2`$ = mass of astronaut = 70 kg
- $`r`$ = radius of Mars = 3.39 × 10⁶ m
- $`G`$ = 6.67 × 10⁻¹¹ N·m²/kg²

Substituting:

```math
F_g = (6.67 \times 10^{-11})\frac{(6.42 \times 10^{23})(70)}{(3.39 \times 10^6)^2}
```

```math
F_g = (6.67 \times 10^{-11})\frac{4.494 \times 10^{25}}{1.149 \times 10^{13}}
```

```math
F_g = (6.67 \times 10^{-11})(3.91 \times 10^{12})
```

```math
F_g = 261 \text{ N}
```

The astronaut would weigh about 261 N on Mars, roughly 38% of their weight on Earth.

## Practice Problem 2: Apparent Weight in an Elevator

A 60 kg person stands on a scale in an elevator. What is the reading on the scale when the elevator is accelerating upward at 2.0 m/s²? The gravitational field strength is 9.8 N/kg.

**Solution**

The scale reading equals the normal force. Find it with Newton's second law.

Forces on the person:

- Weight (downward): $`F_g = mg = (60 \text{ kg})(9.8 \text{ m/s}^2) = 588 \text{ N}`$
- Normal force from the scale (upward): $`F_N`$ (the unknown)

Since the person accelerates upward at 2.0 m/s²: $`F_{net} = ma`$ $`F_N - F_g = ma`$

```math
F_N - 588 \text{ N} = (60 \text{ kg})(2.0 \text{ m/s}^2)
```

```math
F_N - 588 \text{ N} = 120 \text{ N}
```

```math
F_N = 708 \text{ N}
```

The scale reads 708 N, more than the true weight of 588 N. This shows how acceleration raises apparent weight.

## Practice Problem 3: Gravitational Force Inside Earth

A mining operation drills a hole to a depth of 2000 km below Earth's surface. If Earth has a radius of 6370 km, a mass of 5.97 × 10²⁴ kg, and approximately uniform density, what fraction of the surface gravitational force would a 1 kg object experience at this depth?

**Solution**

Inside a uniform sphere, the gravitational force is proportional to the distance from the center:

```math
F_g = G\frac{Mm}{R^3}r \quad (\text{for } r < R)
```

Where:

- $`M`$ = mass of Earth = 5.97 × 10²⁴ kg
- $`m`$ = mass of object = 1 kg
- $`R`$ = radius of Earth = 6370 km
- $`r`$ = distance from center = 6370 km − 2000 km = 4370 km

The fraction of surface gravity is:

```math
\frac{F_g \text{ at depth}}{F_g \text{ at surface}} = \frac{G\frac{Mm}{R^3}r}{G\frac{Mm}{R^2}} = \frac{r}{R}
```

```math
\frac{F_g \text{ at depth}}{F_g \text{ at surface}} = \frac{4370 \text{ km}}{6370 \text{ km}} = 0.686
```

At a depth of 2000 km, the object experiences about 68.6% of the gravitational force it would feel at Earth's surface.

## Common Misconceptions

- **Misconception:** Weight and mass are the same thing.  
  **Actually:** Mass is an intrinsic property in kilograms, while weight is the gravitational force in newtons and changes with location.
- **Misconception:** Astronauts in orbit feel no gravity.  
  **Actually:** Gravity is still pulling on them; they feel weightless because they are in continuous free fall with no normal force.
- **Misconception:** The distance in $`F_g = G\frac{m_1 m_2}{r^2}`$ is measured from the surfaces.  
  **Actually:** It is measured center to center, between the two centers of mass.
- **Misconception:** Gravity is zero inside a planet.  
  **Actually:** Inside a uniform sphere, gravity is not zero in general. It actually grows in proportion to your distance from the center and reaches zero only at the exact center.
- **Misconception:** Doubling the distance cuts the force in half.  
  **Actually:** Because of the inverse-square law, doubling the distance cuts the force to one-fourth.
- **Misconception:** Apparent weight always equals true weight.  
  **Actually:** Apparent weight equals the normal force, so it changes whenever the object accelerates and reaches zero in free fall.
- **Misconception:** Inertial mass and gravitational mass might be different.  
  **Actually:** Experiments have shown them to be equivalent to very high precision, which is why a single mass value works in both Newton's second law and the law of gravitation.

## Related AP Physics C: Mechanics Guides

- [2.1 Properties and Interactions of a System](01-properties-and-interactions-of-a-system.md)
- [2.2 Forces and Free-Body Diagrams](02-forces-and-free-body-diagrams.md)
- [2.3 Newton's Third Law](03-newtons-third-law.md)
- [2.4 Newton's First Law](04-newtons-first-law.md)
- [2.7 Kinetic and Static Friction](07-kinetic-and-static-friction.md)
- [2.9 Resistive Forces](09-resistive-forces.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| accelerating | Changing velocity; experiencing a net force that causes a change in speed or direction of motion. |
| apparent weight | The magnitude of the normal force exerted on a system; the weight that a system appears to have based on the support force acting on it. |
| center of mass | The point in a system where the entire mass can be considered to be concentrated for the purposes of analyzing motion and forces. |
| differential mass | An infinitesimally small element of mass, denoted as dm, used in integration to calculate properties of nonuniform solids. |
| equivalence of inertial and gravitational mass | The experimentally verified principle that an object's inertial mass and gravitational mass are equal. |
| equivalence principle | The principle stating that an observer in a noninertial reference frame cannot distinguish between the effects of acceleration and the effects of a gravitational field. |
| gravitational field | The region of space around a mass where gravitational force is exerted on other masses; its strength is measured in N/kg. |
| gravitational field strength | The magnitude of the gravitational field at a point in space, equal to the gravitational force per unit mass, measured in N/kg or m/s². |
| gravitational force | The attractive force between two objects due to their masses, described by Newton's law of universal gravitation. |
| gravitational interaction | The attractive force exerted between two objects or systems due to their masses. |
| gravitational mass | A property of an object that relates to the force of attraction between two systems with mass. |
| inertia | The property of an object that resists changes in its motion. |
| inertial mass | A property of an object that determines how much its motion resists changes when interacting with another object; a measure of an object's inertia. |
| Newton's law of universal gravitation | The law stating that the gravitational force between two objects is directly proportional to the product of their masses and inversely proportional to the square of the distance between their centers of mass. |
| Newton's shell theorem | A principle stating that the gravitational force exerted by a uniform spherical shell depends on whether an object is inside or outside the shell. |
| noninertial reference frame | A reference frame that is accelerating or rotating, in which Newton's laws do not hold without introducing fictitious forces. |
| normal force | The contact force exerted by a surface on an object perpendicular to that surface. |
| partial mass | The portion of a sphere's mass located within a distance from the center equal to or less than an object's distance from the center. |
| spherical shell | A thin, hollow sphere with mass distributed uniformly over its surface. |
| test object | A small object of known mass used to measure the gravitational field strength created by another mass. |
| uniform density | A property of an object where mass is distributed evenly throughout its volume, resulting in constant mass per unit volume. |
| uniform spherical distribution of mass | A sphere with mass distributed evenly throughout its volume, with constant density. |
| weight | The gravitational force exerted by an astronomical body on a relatively small nearby object. |
| weightless | The condition in which a system experiences no apparent weight, occurring when no forces act on the system or when gravity is the only force acting on it. |

## Frequently Asked Questions

### What is gravitational force in AP Physics C Mechanics?

Gravitational force is the attractive force between two objects or systems with mass. Newton's law says its magnitude is directly proportional to both masses and inversely proportional to the square of the center-to-center distance.

### What equation do you use for universal gravitation?

Use |Fg| = Gm1m2/r^2, where r is the distance between centers of mass. The force is attractive and points along the line connecting the two centers of mass.

### What is a gravitational field in AP Physics C?

A gravitational field models the effect of gravity at points in space. Its magnitude is |g| = |Fg|/m = GM/r^2, and if gravity is the only force, the object's acceleration equals the field strength.

### What is apparent weight?

Apparent weight is the magnitude of the normal force on an object. It can differ from true gravitational weight when the object accelerates, and it becomes zero in free fall.

### What does Newton's shell theorem say?

For a uniform spherical shell, the outside force acts as if all mass were at the center, while the net force inside a thin shell is zero. Inside a uniform solid sphere, only enclosed mass contributes.

### What is a common mistake with AP Physics C gravitation?

A common mistake is using surface-to-surface distance instead of center-to-center distance in |Fg| = Gm1m2/r^2, or treating g as constant when distance changes significantly.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-2/6-gravitational-force/study-guide/CzrVgTyZ4BKEJNfh](https://fiveable.me/ap-physics-c-mechanics/unit-2/6-gravitational-force/study-guide/CzrVgTyZ4BKEJNfh)</sub>
