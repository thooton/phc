# 6.6 Motion of Orbiting Satellites

## TLDR

In AP Physics C: Mechanics, satellite motion focuses on circular orbits around a massive central object, where gravity provides the centripetal force. The key results you need are the energy relationships ($`U_g = -GMm/r`$, $`K = -\frac{1}{2}U`$, $`E_{total} = -GMm/2r`$), the circular orbital speed $`v_{circ} = \sqrt{GM/r}`$, and escape velocity $`v_{esc} = \sqrt{2GM/r}`$. Elliptical orbits show up conceptually, but your calculations center on circular orbits.

## Why This Matters for the AP Physics C: Mechanics Exam

This topic ties together gravitation, energy conservation, angular momentum, and circular motion, so it tests whether you can connect ideas from several units at once. On both multiple-choice and free-response questions, you may need to derive orbital quantities from conservation of energy, compare energies at different orbital radii, or justify whether a satellite is bound or can escape. Strong answers do more than name a law or write an equation. You have to show the reasoning steps that lead from the principle to your conclusion, which is exactly the skill graders reward on free response.

## Key Takeaways

- When the satellite's mass is tiny compared to the central object, treat the central object as fixed and only track the satellite's motion.
- Gravitational potential energy is $`U_g = -\frac{GMm}{r}`$, defined as zero at infinite separation, so it gets more negative as the objects get closer.
- For circular orbits, gravity supplies the centripetal force, which gives $`v_{circ} = \sqrt{GM/r}`$ and the relation $`K = -\frac{1}{2}U`$.
- Total mechanical energy of a circular orbit is $`E_{total} = \frac{1}{2}U = -\frac{GMm}{2r}`$, and the negative sign means the satellite is bound.
- Escape velocity sets total mechanical energy to zero, giving $`v_{esc} = \sqrt{\frac{2GM}{r}}`$, which is independent of the satellite's mass.
- In circular orbits, total mechanical energy, gravitational potential energy, kinetic energy, and angular momentum all stay constant.

## How a Central Object Stays Effectively Fixed

For a two-object system interacting only through gravity, both objects technically orbit their common center of mass. When the satellite's mass is negligible compared with the central object's mass, the center of mass sits so close to the central object that you can treat the central object as stationary and model only the satellite's motion. 🪐

- The center of mass of the system lies extremely close to the center of the massive object.
- For example, Earth's mass is roughly 6 × 10^24 kg while a typical satellite might be only 1000 kg.
- That mass ratio (around 10^21 to 1) makes the central object's motion negligible for most calculations.
- In these problems, place the central object at the origin and analyze the satellite around it.

This simplification lets you focus on the satellite without tracking the tiny movement of the central body.

## Conservation Laws That Constrain Orbits

Conservation laws set the rules for satellite motion and produce predictable orbital patterns no matter the satellite's mass.

- **Conservation of angular momentum**: the satellite sweeps out equal areas in equal times.
- **Conservation of energy**: the total mechanical energy stays constant throughout the orbit.

In a circular orbit, each of these stays constant:

- Total mechanical energy
- Gravitational potential energy
- Satellite's kinetic energy
- Angular momentum

For a satellite-central-object system, gravitational potential energy is defined to be zero when the satellite is infinitely far from the central object. At separation $`r`$:

```math
U_g = -\frac{GMm}{r}
```

Because the potential energy is zero at infinite separation, it becomes more negative as the objects move closer. This convention lets you quantify the energy needed to fully separate the two objects.

**Note on elliptical orbits:** In an elliptical orbit, total mechanical energy and angular momentum stay constant, while kinetic energy and gravitational potential energy each change as the satellite speeds up and slows down. For AP Physics C: Mechanics, your calculations focus on circular orbits, so treat elliptical orbits as a conceptual extension.

## Energy and Speed in Circular Orbits

In a circular orbit, the satellite keeps a constant distance from the central object, so its energy components stay fixed. 🛰️

The gravitational potential energy of the system is:

```math
U = -\frac{GMm}{r}
```

The kinetic energy of the satellite is:

```math
K = \frac{1}{2}mv^2
```

In a circular orbit, gravity provides the entire centripetal force:

```math
\frac{mv^2}{r} = \frac{GMm}{r^2}
```

Solving this for the orbital speed gives the circular orbital speed:

```math
v_{circ} = \sqrt{\frac{GM}{r}}
```

Notice that $`v_{circ}`$ depends only on the central object's mass and the orbital radius, not on the satellite's mass. Substituting this speed back into the kinetic energy leads to a special relationship between kinetic and potential energy:

```math
K = -\frac{1}{2}U
```

So the total energy is:

```math
E_{total} = K + U = -\frac{1}{2}U + U = \frac{1}{2}U = -\frac{GMm}{2r}
```

The negative total energy means the satellite is bound to the central object. A total energy of zero or higher would mean the satellite has enough energy to escape.

## Escape Velocity

Escape velocity is the minimum launch speed a satellite needs to break free from a gravitational field completely. 🚀

A satellite at exactly escape velocity has a total mechanical energy of zero:

```math
E_{total} = K + U = 0
```

That means:

```math
\frac{1}{2}mv_{esc}^2 - \frac{GMm}{r} = 0
```

Solving for escape velocity:

```math
v_{esc} = \sqrt{\frac{2GM}{r}}
```

Useful facts about escape velocity:

- It is independent of the satellite's mass.
- It depends only on the central object's mass and the starting distance.
- It decreases as the starting distance from the central object increases.
- From Earth's surface it is about 11.2 km/s.

A satellite launched at exactly escape velocity will:

- Keep moving away from the central object indefinitely.
- Gradually slow down as it travels outward.
- Approach zero speed as the distance approaches infinity.
- Never return to the central object.

When gravity from the central object is the only force, a satellite that reaches escape velocity moves away until its speed reaches zero at an infinite distance from the central body.

## Practice Problem 1: Circular Orbit Energy

A satellite with mass 1500 kg orbits Earth in a circular orbit with radius 8000 km. Calculate: a) the gravitational potential energy of the system, b) the kinetic energy of the satellite, and c) the total energy of the system. Use G = 6.67 × 10^-11 N·m²/kg² and Earth's mass = 5.97 × 10^24 kg.

**Solution**

First convert the radius to meters: 8000 km = 8 × 10^6 m

a) The gravitational potential energy is: $`U = -\frac{GMm}{r}`$ $`U = -\frac{(6.67 \times 10^{-11})(5.97 \times 10^{24})(1500)}{8 \times 10^6}`$ $`U = -7.48 \times 10^{10} \text{ J}`$

b) For a circular orbit, the kinetic energy is half the magnitude of the potential energy: $`K = -\frac{1}{2}U = -\frac{1}{2}(-7.48 \times 10^{10})`$ $`K = 3.74 \times 10^{10} \text{ J}`$

c) The total energy is: $`E_{total} = K + U = 3.74 \times 10^{10} + (-7.48 \times 10^{10})`$ $`E_{total} = -3.74 \times 10^{10} \text{ J}`$

You could also use $`E_{total} = \frac{1}{2}U = -\frac{GMm}{2r}`$ directly and get the same result.

## Practice Problem 2: Escape Velocity

Calculate the escape velocity from the surface of Mars. Mars has a mass of 6.42 × 10^23 kg and a radius of 3.39 × 10^6 m. G = 6.67 × 10^-11 N·m²/kg².

**Solution**

The escape velocity is given by: $`v_{esc} = \sqrt{\frac{2GM}{r}}`$

Substituting the values: $`v_{esc} = \sqrt{\frac{2(6.67 \times 10^{-11})(6.42 \times 10^{23})}{3.39 \times 10^6}}`$ $`v_{esc} = \sqrt{\frac{8.56 \times 10^{13}}{3.39 \times 10^6}}`$ $`v_{esc} = \sqrt{2.53 \times 10^7}`$ $`v_{esc} = 5.03 \times 10^3 \text{ m/s}`$

So the escape velocity from Mars' surface is about 5.03 km/s, which is less than Earth's escape velocity (11.2 km/s) because Mars has less mass and a smaller radius.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

- Start from a physical principle, not a memorized result. For orbital speed, set gravity equal to the centripetal force; for escape velocity, set total mechanical energy to zero. Showing this setup earns more credit than dropping in a final formula.
- Keep track of signs. Gravitational potential energy is negative, and total energy in a bound circular orbit is negative. A positive total energy signals an unbound path.
- When asked to compare two orbits, use the functional dependence in the equations. For example, $`E_{total} = -GMm/2r`$ tells you a larger radius means a less negative (higher) total energy.

### Free Response

- Explain your reasoning in words, not just symbols. Saying a satellite is bound "because of conservation of energy" is not enough. State that the total mechanical energy is negative, then connect that to the satellite being unable to reach infinite distance.
- When you derive escape velocity, write the energy conservation statement, set $`E_{total} = 0`$, and solve. Show each algebra step so a grader can follow the logic.
- If a question gives a graph of energy versus radius or torque versus time, describe what the slope or area represents before plugging in numbers.

### Common Trap

- Do not confuse $`v_{circ} = \sqrt{GM/r}`$ with $`v_{esc} = \sqrt{2GM/r}`$. Escape velocity is larger by a factor of $`\sqrt{2}`$ at the same radius.

## Common Misconceptions

- **Misconception:** Escape velocity depends on the satellite's mass.  
  **Actually:** Escape velocity does not depend on the satellite's mass. It depends only on the central object's mass and the starting distance. The satellite mass cancels out of the energy equation.
- **Misconception:** Total energy of a bound orbit is zero.  
  **Actually:** Total energy of a bound orbit is negative, not zero. A circular orbit has $`E_{total} = -GMm/2r`$. Total energy reaches zero only at escape velocity, which marks the boundary between bound and unbound motion.
- **Misconception:** Orbital speed and escape velocity are the same.  
  **Actually:** Orbital speed and escape velocity are different. At a given radius, $`v_{esc} = \sqrt{2}\, v_{circ}`$. Mixing them up is a common calculation error.
- **Misconception:** Gravitational potential energy is zero in orbit.  
  **Actually:** Gravitational potential energy is negative, not zero, in orbit. It is defined as zero only at infinite separation, so any finite orbit has negative $`U_g`$.
- **Misconception:** A larger orbit means more kinetic energy.  
  **Actually:** A larger orbit does not mean more kinetic energy. As $`r`$ increases, the circular orbital speed decreases, so the satellite actually moves slower in a higher orbit.
- **Misconception:** Constant total energy means constant kinetic energy in every orbit.  
  **Actually:** Constant total energy does not mean constant kinetic energy in every orbit. In a circular orbit kinetic energy is constant, but in an elliptical orbit kinetic and potential energy trade off while the total stays fixed.

## Related AP Physics C: Mechanics Guides

- [6.4 Conservation of Angular Momentum](04-conservation-of-angular-momentum.md)
- [6.1 Rotational Kinetic Energy](01-rotational-kinetic-energy.md)
- [6.2 Torque and Work](02-torque-and-work.md)
- [6.3 Angular Momentum and Angular Impulse](03-angular-momentum-and-angular-impulse.md)
- [6.5 Kinetic Energy of a System with Translational and Rotational Motion](05-kinetic-energy-of-a-system-with-translational-and-rotational-motion.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| angular momentum | A measure of the rotational motion of an object or system, calculated as the product of moment of inertia and angular velocity, or as the cross product of position vector and linear momentum. |
| circular orbit | The path of a satellite moving around a central body at a constant distance, where gravitational force provides the centripetal force needed to maintain the circular path. |
| conservation of energy | The principle that total mechanical energy remains constant in an isolated gravitational system. |
| elliptical orbit | An orbital path where a satellite's distance from the central object varies, resulting in changing speed and kinetic energy while maintaining constant total energy. |
| escape velocity | The minimum velocity required for a satellite to escape the gravitational pull of a central object, at which the total mechanical energy equals zero. |
| gravitational force | The attractive force between two objects due to their masses, described by Newton's law of universal gravitation. |
| gravitational potential energy | The energy stored in a system due to the gravitational interaction between a satellite and a central object, defined as zero at infinite distance. |
| kinetic energy | The energy possessed by an object due to its motion, equal to one-half the product of its mass and the square of its velocity. |
| total mechanical energy | The sum of kinetic and potential energy in an orbiting system, which remains constant in both circular and elliptical orbits. |

## Frequently Asked Questions

### What provides centripetal force for an orbiting satellite?

Gravity provides the centripetal force for a satellite in circular orbit around a massive central object.

### What is the circular orbital speed formula?

For a circular orbit around a central mass M, the orbital speed is v = sqrt(GM/r). It depends on the central mass and orbital radius, not the satellite mass.

### What is the gravitational potential energy of a satellite system?

For a satellite and central mass, gravitational potential energy is U\_g = -GMm/r when zero potential energy is defined at infinite separation.

### What is the total energy of a circular orbit?

For a circular orbit, total mechanical energy is E\_total = -GMm/(2r). The negative value means the satellite is bound to the central object.

### What is escape velocity?

Escape velocity is the speed that makes total mechanical energy equal to zero, allowing the satellite to move infinitely far away. The formula is v\_esc = sqrt(2GM/r).

### How is AP Physics C Mechanics 6.6 tested?

Topic 6.6 is tested with circular orbit derivations, energy comparisons, angular momentum reasoning, gravitational potential energy, orbital speed, and escape velocity.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-6/6-motion-of-orbiting-satellites/study-guide/nmLPsSq9JDXcENSW](https://fiveable.me/ap-physics-c-mechanics/unit-6/6-motion-of-orbiting-satellites/study-guide/nmLPsSq9JDXcENSW)</sub>
