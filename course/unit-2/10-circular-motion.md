# 2.10 Circular Motion

## What is circular motion in AP Physics C: Mechanics?

Circular motion happens when a net force points toward the center of a curved path, producing centripetal acceleration $`a_c = v^2/r`$ even when speed stays constant. To analyze it, you identify which real forces (gravity, normal force, friction, tension) point toward the center, set their net value equal to $`mv^2/r`$, and use period and frequency to track timing. The same logic explains satellite orbits through Kepler's third law, $`T^2 = \frac{4\pi^2}{GM}R^3`$.

## Why This Matters for the AP Physics C: Mechanics Exam

Circular motion ties together everything from Unit 2: free-body diagrams, Newton's second law, gravity, friction, and tension all show up here. The exam expects you to translate a physical scenario into math, which is exactly the skill tested in the Qualitative/Quantitative Translation free-response question. That means you may be asked to describe what keeps an object on a circular path in words first, then derive the equation that backs up your claim, then connect the two.

On multiple-choice and free-response questions, you will set up force equations where the net inward force equals $`mv^2/r`$, sketch free-body diagrams for loops, banked curves, and conical pendulums, and reason about how period or orbital radius changes when other variables change. Getting comfortable with these setups gives you a reliable method for a large share of dynamics problems.

## Key Takeaways

- Centripetal acceleration always points toward the center: $`a_c = \dfrac{v^2}{r}`$, and it exists even at constant speed.
- "Centripetal force" is not a new force. It is the net inward force from real forces like gravity, normal force, friction, or tension.
- Tangential acceleration changes speed; centripetal acceleration changes direction. Net acceleration is the vector sum of the two.
- For uniform circular motion, use $`T = \dfrac{2\pi r}{v}`$ and $`T = \dfrac{1}{f}`$ to connect speed, period, and frequency.
- At the top of a vertical loop with minimum speed, gravity alone supplies the centripetal force, giving $`v = \sqrt{gr}`$.
- For a satellite in a circular orbit, gravity is the only centripetal force, leading to $`T^2 = \dfrac{4\pi^2}{GM}R^3`$.

## Motion in Circular Paths

### Centripetal Acceleration

Centripetal acceleration keeps an object moving along a circular path by constantly changing the direction of its velocity. It always points toward the center of the circle, perpendicular to the velocity.

- The magnitude is given by: $`a_c = \frac{v^2}{r}`$ where $`v`$ is the tangential speed and $`r`$ is the radius of the path.
- Centripetal acceleration exists even when an object moves at constant speed in a circle, because direction is still changing.
- The direction constantly updates as the object moves, always pointing toward the center.
- The unit is meters per second squared (m/s²).

"Centripetal" means "center-seeking," which describes how this acceleration always points toward the center of the path.

### Forces That Cause Centripetal Acceleration

For an object to follow a circular path, the net force must point toward the center. This inward net force can come from one source or a combination of sources. There is no separate "centripetal force" to add to a free-body diagram. You draw the real forces, then find their inward component.

A single force can supply it (like gravity for a satellite). Multiple forces or components of forces can also combine to produce the inward net force.

In a vertical loop, such as on a roller coaster:

- At the top of the loop, gravity provides the centripetal acceleration if the object has at least the minimum required speed.
- That minimum speed is $`v = \sqrt{gr}`$
- Below this speed, the object cannot maintain contact and falls away from the track.

On a banked curve, like a racetrack turn:

- The normal force and static friction can both contribute to the inward net force.
- Banking the surface lets a component of the normal force point inward, reducing how much friction is needed.
- The ideal banking angle depends on the speed and radius of the turn.

In a conical pendulum:

- Tension has a vertical component that balances weight and a horizontal component that points inward.
- The horizontal component of tension provides the centripetal force.
- The string's angle depends on the speed of rotation.

### Tangential Acceleration

Tangential acceleration changes the speed of an object in circular motion, not its direction.

- It points tangent to the path: same direction as velocity when speeding up, opposite when slowing down.
- It causes the object's speed to increase or decrease.
- When tangential acceleration is zero, the object moves at constant speed (uniform circular motion).
- When it is nonzero, the object's speed changes as it travels along the path.

### Net Acceleration in Circles

The total acceleration combines centripetal and tangential components.

- Net acceleration is the vector sum of centripetal and tangential acceleration.
- These two components are perpendicular to each other.
- The magnitude follows the Pythagorean theorem: $`a_{net} = \sqrt{a_c^2 + a_t^2}`$
- The direction depends on the relative sizes of the two components.

### Period and Frequency

In uniform circular motion, period and frequency describe how quickly an object completes revolutions.

- Period (T) is the time for one full revolution.
  
  - Measured in seconds (s).
  - Can be calculated using: $`T = \frac{2\pi r}{v}`$
- Frequency (f) is the number of revolutions per unit time.
  
  - Measured in hertz (Hz).
  - Can be calculated using: $`f = \frac{v}{2\pi r}`$
- Period and frequency are inversely related: $`T = \frac{1}{f}`$

These are useful when analyzing systems like rotating wheels and orbiting bodies.

### Circular Orbits and Kepler's Third Law

For a satellite in circular orbit around a central body of mass $`M`$, the only force causing centripetal acceleration is gravitational attraction. Setting the gravitational force equal to the required centripetal force gives:

```math
\frac{GMm}{R^2} = \frac{mv^2}{R}
```

where $`G`$ is the gravitational constant, $`m`$ is the satellite's mass, and $`R`$ is the orbital radius.

Since the orbital speed can be written in terms of the period as $`v = \frac{2\pi R}{T}`$, substitute and solve to relate orbital period to orbital radius:

```math
T^2 = \frac{4\pi^2}{GM}R^3
```

This is Kepler's third law for circular orbits. The satellite's mass cancels, so the period depends only on the orbital radius and the mass of the central body. For objects orbiting the same central body, $`T^2 \propto R^3`$, which means satellites farther out take longer to complete an orbit.

AP Physics C: Mechanics does not require Kepler's first or second laws.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

Use a consistent method for circular motion problems:

1. Draw a free-body diagram with only real forces (gravity, normal, friction, tension). Do not add a separate centripetal force.
2. Pick a coordinate direction pointing toward the center of the circle as your positive inward axis.
3. Write Newton's second law so the net inward force equals $`\dfrac{mv^2}{r}`$.
4. Solve for the unknown, then check units and direction.

### Free Response

The Qualitative/Quantitative Translation question may ask you to describe a circular-motion scenario in words, then derive equations, then connect the two. Practice explaining which force or component points inward before you write any equation, then derive the result and tie it back to your verbal claim. Setups for loops, banked curves, conical pendulums, and orbits are all fair game from any unit.

### Common Trap

When a problem mentions an object "feeling pushed outward," remember the real physics is inertia, not an outward force. Keep your free-body diagram limited to actual interactions, and let the inward net force equal $`mv^2/r`$.

## Common Misconceptions

- **Misconception:** Centripetal force is an extra force.  
  **Actually:** Centripetal force is not an extra force. It is the name for the net inward force produced by real forces. Never draw it as a separate arrow on a free-body diagram.
- **Misconception:** An object in uniform circular motion is not accelerating.  
  **Actually:** An object in uniform circular motion is still accelerating. Constant speed does not mean zero acceleration, because the direction of velocity keeps changing.
- **Misconception:** Centrifugal force is a real force in an inertial frame.  
  **Actually:** Centrifugal force is not a real force in an inertial frame. The outward feeling comes from inertia, not from a force acting on the object toward the outside.
- **Misconception:** The minimum speed at the top of a loop, $`v = \sqrt{gr}`$, applies elsewhere on the loop.  
  **Actually:** The minimum speed at the top of a loop, $`v = \sqrt{gr}`$, applies only at that specific point where gravity alone supplies the centripetal force. Do not apply it elsewhere on the loop.
- **Misconception:** The orbiting object's mass affects the period.  
  **Actually:** In Kepler's third law for circular orbits, the orbiting object's mass does not affect the period. Only the central body's mass and the orbital radius matter.
- **Misconception:** Tangential and centripetal acceleration are interchangeable.  
  **Actually:** Tangential and centripetal acceleration are not interchangeable. One changes speed, the other changes direction, and they are always perpendicular.

## Practice Problem 1: Centripetal Acceleration

A car travels around a circular track with a radius of 50 meters at a constant speed of 20 m/s. Calculate the centripetal acceleration of the car.

**Solution:** Use the centripetal acceleration formula: $`a_c = \frac{v^2}{r}`$

Substitute the given values: $`a_c = \frac{(20 \text{ m/s})^2}{50 \text{ m}}`$ $`a_c = \frac{400 \text{ m}^2/\text{s}^2}{50 \text{ m}}`$ $`a_c = 8 \text{ m/s}^2`$

The car experiences a centripetal acceleration of 8 m/s² directed toward the center of the track.

## Practice Problem 2: Minimum Speed for Vertical Loop

A roller coaster car enters a vertical loop with a radius of 12 meters. What is the minimum speed the car must have at the top of the loop to stay on the track?

**Solution:** At the minimum speed, gravity alone provides the centripetal acceleration at the top of the loop: $`v_{min} = \sqrt{gr}`$

Substitute the given values: $`v_{min} = \sqrt{9.8 \text{ m/s}^2 \times 12 \text{ m}}`$ $`v_{min} = \sqrt{117.6 \text{ m}^2/\text{s}^2}`$ $`v_{min} = 10.84 \text{ m/s}`$

The car must have a minimum speed of about 10.84 m/s at the top of the loop to stay on the track.

## Practice Problem 3: Period and Frequency

An object moves in uniform circular motion with a speed of 6 m/s around a circle of radius 3 meters. Calculate (a) the period and (b) the frequency of the motion.

**Solution:** (a) Use the period formula: $`T = \frac{2\pi r}{v}`$

Substitute the given values: $`T = \frac{2\pi \times 3 \text{ m}}{6 \text{ m/s}}`$ $`T = \frac{6\pi \text{ m}}{6 \text{ m/s}}`$ $`T = \pi \text{ s} \approx 3.14 \text{ s}`$

(b) Use $`f = \frac{1}{T}`$: $`f = \frac{1}{\pi \text{ s}} \approx 0.318 \text{ Hz}`$

The period is about 3.14 seconds, and the frequency is about 0.318 Hz.

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
| banked surface | A tilted surface on which an object travels in a circular path, where components of normal force and friction contribute to centripetal acceleration. |
| centripetal acceleration | The acceleration directed toward the center of a circular path, required to keep an object moving in a circle. |
| circular orbit | The path of a satellite moving around a central body at a constant distance, where gravitational force provides the centripetal force needed to maintain the circular path. |
| conical pendulum | A pendulum that moves in a horizontal circular path, with tension providing a component of the centripetal force. |
| frequency | The number of complete oscillations or cycles of simple harmonic motion that occur per unit time, measured in hertz (Hz). |
| gravitational attraction | The force of attraction between two masses, which in orbital mechanics provides the centripetal force for circular orbits. |
| Kepler's third law | The relationship stating that the square of a satellite's orbital period is proportional to the cube of its orbital radius, expressed as T² = (4π²/GM)R³. |
| net acceleration | The vector sum of an object's centripetal acceleration and tangential acceleration. |
| normal force | The contact force exerted by a surface on an object perpendicular to that surface. |
| orbital period | The time required for a satellite to complete one full orbit around a central body. |
| orbital radius | The distance from the center of the central body to the satellite in a circular orbit. |
| period | The time required for an object to complete one full circular path, rotation, or cycle. |
| radius | The distance from the center of a circular path to the object moving along that path. |
| static friction | A friction force that acts between two surfaces in contact that are not moving relative to each other, preventing an object from slipping or sliding. |
| tangential acceleration | The rate at which an object's speed changes, directed tangent to the object's circular path. |
| tangential speed | The instantaneous speed of an object moving along a circular path, directed tangent to the circle. |
| tension | The macroscopic net force that segments of a string, cable, chain, or similar system exert on each other in response to an external force. |
| uniform circular motion | Motion of an object traveling in a circular path at constant speed. |
| vertical circular loop | A circular path oriented vertically, where an object must maintain a minimum speed at the top to continue circular motion. |

## Frequently Asked Questions

### What is circular motion in AP Physics C: Mechanics?

Circular motion is motion along a circular path where acceleration has an inward centripetal component. Even at constant speed, the velocity direction changes, so the object accelerates toward the center.

### What is the centripetal acceleration formula?

The magnitude of centripetal acceleration is a\_c = v^2/r, where v is tangential speed and r is the radius of the circular path. It points toward the center.

### Is centripetal force a separate force?

No. Centripetal force is not an extra force to draw. It is the net inward force produced by real forces such as gravity, normal force, friction, or tension.

### What is the minimum speed at the top of a vertical loop?

At the top of a vertical loop, the minimum speed occurs when gravity alone supplies the centripetal acceleration. That gives v = sqrt(gr) for that specific point.

### How do period and frequency relate in circular motion?

Period T is the time for one revolution, frequency f is revolutions per unit time, and T = 1/f. For uniform circular motion, T = 2 pi r/v.

### How does Kepler’s third law connect to circular orbits?

For a circular orbit, gravity supplies the centripetal force. This leads to T^2 = (4 pi^2/GM)R^3, so orbital period depends on orbital radius and the central body mass.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-2/10-circular-motion/study-guide/mSTvL7QY6udY9crx](https://fiveable.me/ap-physics-c-mechanics/unit-2/10-circular-motion/study-guide/mSTvL7QY6udY9crx)</sub>
