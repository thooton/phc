# 7.4 Energy of Simple Harmonic Oscillators

In simple harmonic motion, total mechanical energy stays constant while it shifts back and forth between kinetic and potential. For a spring-object system, that total equals $`E_{\text{total}} = \frac{1}{2}kA^2`$, so energy is set by the spring constant and the amplitude.

## Why This Matters for the AP Physics C: Mechanics Exam

Oscillations make up a solid chunk of the exam, and energy is one of the cleanest tools for analyzing them. Instead of tracking position and velocity at every instant, you can use conservation of energy to jump straight to the answer at any point in the cycle.

This topic also connects directly to the Translation Between Representations free-response question, where you may need to sketch energy bar charts for a block-spring system at maximum displacement and at equilibrium, then explain how those charts agree with other representations like free-body diagrams. Being able to move between energy graphs, equations, and verbal descriptions is exactly the kind of thinking that question rewards.

## Key Takeaways

- Total mechanical energy in SHM is constant: $`E_{\text{total}} = U + K`$, with no energy lost in an ideal (undamped) system.
- Kinetic energy is $`K = \frac{1}{2}mv^2`$ and spring potential energy is $`U = \frac{1}{2}kx^2`$.
- For a spring-object system, $`E_{\text{total}} = \frac{1}{2}kA^2`$, so total energy scales with the square of the amplitude.
- At equilibrium ($`x = 0`$): $`U = 0`$, $`K`$ is maximum, and speed is maximum at $`v_{\text{max}} = A\omega`$.
- At the turning points ($`x = \pm A`$): $`K = 0`$, $`U`$ is maximum, and the object is momentarily at rest.
- Changing amplitude changes total energy, but it does not change the period.

## Mechanical Energy in SHM

### Total Energy Components

The total mechanical energy in a simple harmonic oscillator is the sum of kinetic and potential energy at any point in the motion. This relationship is the foundation for understanding how energy transforms during oscillation.

```math
E_{\text{total}}=U+K
```

Kinetic energy ($`K`$) is the energy of motion and depends on the mass and velocity of the oscillating object:

```math
K = \frac{1}{2}mv^2
```

Potential energy ($`U`$) is stored energy that depends on the object's position relative to equilibrium:

```math
U = \frac{1}{2}kx^2
```

For a mass-spring system, the potential energy is elastic potential energy stored in the compressed or stretched spring, while the kinetic energy comes from the mass's motion. As the object oscillates, these two forms continuously convert into each other.

### Conservation of Total Energy

During simple harmonic motion, energy constantly transforms between kinetic and potential forms, but the total energy stays constant throughout the oscillation. This is conservation of energy in action.

The total energy can be calculated at any point during the motion:

```math
E_{\text{total}} = \frac{1}{2}mv^2 + \frac{1}{2}kx^2
```

Because total energy is constant, knowing the system's conditions at one point (either maximum displacement or maximum velocity) lets you find the energy split at any other point. That means you can skip the detailed instant-by-instant motion and focus on key positions where the calculations are simpler.

### Maximum Kinetic Energy

Kinetic energy varies through the cycle and reaches its maximum value when the object passes through equilibrium.

At equilibrium ($`x = 0`$):

- The object moves at maximum speed ($`v_{\text{max}}`$)
- Potential energy is zero (since $`x = 0`$)
- All the energy is kinetic

The maximum kinetic energy is:

```math
K_{\text{max}} = \frac{1}{2}mv_{\text{max}}^2
```

Since total energy is conserved, this maximum kinetic energy equals the total energy of the system. You can relate maximum speed to amplitude using $`v_{\text{max}} = A\omega`$, where $`\omega`$ is the angular frequency of oscillation.

### Maximum Potential Energy

Potential energy reaches its maximum when the object is at its maximum displacement from equilibrium (the amplitude).

At maximum displacement ($`x = \pm A`$):

- The object momentarily stops ($`v = 0`$)
- Kinetic energy is zero
- All the energy is potential

The maximum potential energy is:

```math
U_{\text{max}} = \frac{1}{2}kA^2
```

Since total energy is conserved, this maximum potential energy equals the total energy of the system:

```math
E_{\text{total}} = \frac{1}{2}kA^2
```

This equation shows that the total energy in a spring-object oscillator depends on the spring constant and the amplitude. A stiffer spring (larger $`k`$) or a greater amplitude (larger $`A`$) stores more energy. Notice that amplitude appears squared, so doubling the amplitude makes the total energy four times larger.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

When a problem gives you amplitude and spring constant, start with $`E_{\text{total}} = \frac{1}{2}kA^2`$. That single number is your anchor for the rest of the problem, because it equals the energy at every point in the cycle.

To find speed at a specific position, set the total energy equal to the sum of kinetic and potential energy at that position and solve:

```math
\frac{1}{2}kA^2 = \frac{1}{2}kx^2 + \frac{1}{2}mv^2
```

### Free Response

| Position | Motion | Kinetic energy, K | Spring potential energy, U | Total energy, E\_total |
|---|---|---|---|---|
| Turning point: x = ±A | v = 0 | Empty | Full | Same (conserved) |
| Equilibrium: x = 0 | v = vmax | Full | Empty | Same (conserved) |

For the Translation Between Representations question, practice sketching energy bar charts at both the turning points and equilibrium. At a turning point, the potential bar is full and the kinetic bar is empty; at equilibrium, the kinetic bar is full and the potential bar is empty. The total bar height stays the same in both cases, which is how you show conservation of energy visually. Be ready to connect those bar charts to free-body diagrams and to written explanations of why the representations agree.

### Common Trap

A graph of $`U(x) = \frac{1}{2}kx^2`$ is a parabola in position, but a graph of energy versus time looks different. $`K(t)`$ and $`U(t)`$ are both sinusoidal and oscillate at twice the frequency of the position, while the total energy line stays flat. Read the axis labels carefully before deciding what the curve should look like.

## Practice Problem 1: Energy Conservation in SHM

A 0.5 kg mass attached to a spring with spring constant 200 N/m oscillates with an amplitude of 0.1 m. Calculate: (a) the total energy of the system, (b) the maximum speed of the mass, and (c) the speed of the mass when it is 0.06 m from equilibrium.

**Solution**

(a) The total energy of the system can be calculated using the maximum potential energy: $`E_{\text{total}} = \frac{1}{2}kA^2 = \frac{1}{2}(200 \text{ N/m})(0.1 \text{ m})^2 = 1 \text{ J}`$

(b) To find the maximum speed, use the fact that at the equilibrium position all energy is kinetic: $`E_{\text{total}} = \frac{1}{2}mv_{\text{max}}^2`$ $`v_{\text{max}} = \sqrt{\frac{2E_{\text{total}}}{m}} = \sqrt{\frac{2(1 \text{ J})}{0.5 \text{ kg}}} = 2 \text{ m/s}`$

(c) When the mass is at position x = 0.06 m, use conservation of energy: $`E_{\text{total}} = \frac{1}{2}kx^2 + \frac{1}{2}mv^2`$ $`1 \text{ J} = \frac{1}{2}(200 \text{ N/m})(0.06 \text{ m})^2 + \frac{1}{2}(0.5 \text{ kg})v^2`$ $`1 \text{ J} = 0.36 \text{ J} + \frac{1}{2}(0.5 \text{ kg})v^2`$ $`0.64 \text{ J} = \frac{1}{2}(0.5 \text{ kg})v^2`$ $`v = \sqrt{\frac{2(0.64 \text{ J})}{0.5 \text{ kg}}} = 1.6 \text{ m/s}`$

## Practice Problem 2: Energy Transformations in SHM

A 0.2 kg object on a horizontal frictionless surface is attached to a spring with spring constant k = 50 N/m. If the object is pulled 0.15 m from equilibrium and released from rest, determine: (a) the total energy of the system, (b) the kinetic and potential energies when the object is 0.10 m from equilibrium, and (c) the position where the kinetic energy equals the potential energy.

**Solution**

(a) The total energy is the initial potential energy since the object starts from rest: $`E_{\text{total}} = \frac{1}{2}kA^2 = \frac{1}{2}(50 \text{ N/m})(0.15 \text{ m})^2 = 0.5625 \text{ J}`$

(b) When x = 0.10 m:

- Potential energy: $`U = \frac{1}{2}kx^2 = \frac{1}{2}(50 \text{ N/m})(0.10 \text{ m})^2 = 0.25 \text{ J}`$
- Kinetic energy (from conservation of energy): $`K = E_{\text{total}} - U = 0.5625 \text{ J} - 0.25 \text{ J} = 0.3125 \text{ J}`$

(c) For kinetic energy to equal potential energy: $`\frac{1}{2}kx^2 = \frac{1}{2}mv^2`$

Since total energy is conserved: $`E_{\text{total}} = \frac{1}{2}kx^2 + \frac{1}{2}mv^2 = 0.5625 \text{ J}`$

If $`\frac{1}{2}kx^2 = \frac{1}{2}mv^2`$, then each equals half the total energy: $`\frac{1}{2}kx^2 = \frac{E_{\text{total}}}{2} = 0.28125 \text{ J}`$ $`x = \sqrt{\frac{2(0.28125 \text{ J})}{50 \text{ N/m}}} = 0.106 \text{ m}`$

So the kinetic and potential energies are equal when the object is about 0.106 m from equilibrium.

## Common Misconceptions

- **Misconception:** Total energy depends on where the object is in its cycle.  
  **Actually:** Total energy does not depend on where the object is in its cycle. It is constant, so $`E_{\text{total}}`$ at the turning point equals $`E_{\text{total}}`$ at equilibrium. Only the split between $`K`$ and $`U`$ changes.
- **Misconception:** The period of a spring-object oscillator depends on amplitude.  
  **Actually:** Changing amplitude changes total energy but not the period. The period of a spring-object oscillator depends on $`m`$ and $`k`$, not on $`A`$.
- **Misconception:** Energy scales linearly with amplitude.  
  **Actually:** Energy does not scale linearly with amplitude. Because $`E_{\text{total}} = \frac{1}{2}kA^2`$, doubling the amplitude makes the total energy four times larger, not twice as large.
- **Misconception:** Maximum kinetic energy happens at the endpoints.  
  **Actually:** Maximum kinetic energy happens at equilibrium, not at the endpoints. Students sometimes flip this because the displacement is largest at the endpoints, but that is where speed is zero.
- **Misconception:** $`U = \frac{1}{2}kx^2`$ uses amplitude $`A`$, not position $`x`$.  
  **Actually:** $`U = \frac{1}{2}kx^2`$ uses position $`x`$, not amplitude $`A`$. Plug in the actual displacement at that instant, and only use $`A`$ when you want the maximum potential energy or the total energy.
- **Misconception:** Mechanical energy remains constant when friction or another nonconservative force is present.  
  **Actually:** These energy formulas assume an ideal, undamped system. If friction or another nonconservative force is present, mechanical energy is no longer constant and the amplitude shrinks over time.

## Related AP Physics C: Mechanics Guides

- [7.1 Defining Simple Harmonic Motion (SHM)](01-defining-simple-harmonic-motion-shm.md)
- [7.3 Representing and Analyzing SHM](03-representing-and-analyzing-shm.md)
- [7.5 Simple and Physical Pendulums](05-simple-and-physical-pendulums.md)
- [7.2 Frequency and Period of SHM](02-frequency-and-period-of-shm.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| amplitude | The maximum displacement of an object from its equilibrium position in simple harmonic motion. |
| conservation of energy | The principle that total mechanical energy remains constant in an isolated gravitational system. |
| kinetic energy | The energy possessed by an object due to its motion, equal to one-half the product of its mass and the square of its velocity. |
| mechanical energy | The total energy of a system due to its motion and position, equal to the sum of kinetic and potential energies. |
| potential energy | The energy stored in a system due to the relative positions or configurations of objects that interact via conservative forces. |
| simple harmonic motion | A special case of periodic motion in which a restoring force proportional to displacement causes an object to oscillate about an equilibrium position. |
| total energy | The sum of kinetic and potential energies in a system exhibiting SHM, which remains constant over time. |

## Frequently Asked Questions

### What is the total energy of a simple harmonic oscillator?

For an ideal simple harmonic oscillator, total mechanical energy is constant and equals the sum of kinetic and potential energy: E\_total = U + K.

### What is E\_total = 1/2 kA^2 used for?

Use E\_total = 1/2 kA^2 for a spring-object oscillator when you know the spring constant k and amplitude A. It gives the system's total mechanical energy.

### Where is kinetic energy maximum in SHM?

Kinetic energy is maximum at equilibrium, where displacement is zero, spring potential energy is minimum, and speed is maximum.

### Where is potential energy maximum in SHM?

Potential energy is maximum at the turning points, where displacement equals plus or minus the amplitude and the object is momentarily at rest.

### Does changing amplitude change the period of a spring oscillator?

Changing amplitude changes the total energy of an ideal spring-object oscillator, but the period depends on mass and spring constant, not amplitude.

### How do you find speed at a position in SHM using energy?

Set 1/2 kA^2 equal to 1/2 kx^2 + 1/2 mv^2, then solve for v using the given position x.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-7/4-energy-of-simple-harmonic-oscillators/study-guide/3UvewOScTLW9RUqd](https://fiveable.me/ap-physics-c-mechanics/unit-7/4-energy-of-simple-harmonic-oscillators/study-guide/3UvewOScTLW9RUqd)</sub>
