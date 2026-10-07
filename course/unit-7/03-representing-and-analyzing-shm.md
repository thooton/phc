# 7.3 Representing and Analyzing SHM

Simple harmonic motion is oscillation where acceleration is always proportional to displacement and points back toward equilibrium, written as $`\frac{d^2x}{dt^2} = -\omega^2 x`$. Its position follows a sine or cosine curve, and once you know the amplitude $`A`$, angular frequency $`\omega`$, and phase constant $`\phi`$, you can find velocity, acceleration, and every zero and extreme value of the motion.

## Why This Matters for the AP Physics C: Mechanics Exam

This topic gives you the tools to move between equations, graphs, and physical descriptions of an oscillating system, which is exactly the kind of thinking the exam rewards. You will be expected to connect a position function to its velocity and acceleration through calculus, read or sketch displacement-velocity-acceleration graphs, and explain where the object is fastest, slowest, or momentarily stopped.

The free-response section includes a Translation Between Representations question that asks you to build and compare graphical, verbal, and mathematical models of a scenario, and oscillating block-spring systems are a natural fit. Content from any unit can show up there, so getting comfortable switching between representations here pays off across the whole exam.

## Key Takeaways

- Position in SHM follows $`x = A\cos(\omega t + \phi)`$, with velocity and acceleration found by differentiating that expression.
- The defining feature of SHM is $`a = -\omega^2 x`$, so acceleration is largest at the turning points and zero at equilibrium.
- Velocity is largest at equilibrium ($`v_{max} = A\omega`$) and zero at the turning points; acceleration is largest at the turning points ($`a_{max} = A\omega^2`$).
- Velocity is shifted 90 degrees from displacement, and acceleration is shifted 180 degrees from displacement.
- The period depends on the system's properties, not the amplitude, so changing $`A`$ does not change $`T`$.
- Resonance happens when an external force drives a system at its natural frequency, which increases the amplitude.

## Displacement, Velocity, and Acceleration in SHM

### Equations for SHM Displacement

The position of an object undergoing SHM can be described using sinusoidal functions that show how displacement varies with time.

$`x=A \cos (2 \pi f t)`$ or $`x=A \sin (2 \pi f t)`$

Where:

- $`x`$ is the displacement from equilibrium
- $`A`$ is the amplitude (maximum displacement)
- $`f`$ is the frequency of oscillation
- $`t`$ is time

These can also be written using angular frequency ($`\omega = 2\pi f`$):

$`x=A \cos (\omega t)`$ or $`x=A \sin (\omega t)`$

The choice between sine and cosine depends on the initial conditions. If the object starts at maximum displacement with zero velocity, cosine fits. If it starts at equilibrium with maximum velocity, sine fits. The values of $`x(0)`$ and $`v(0)`$ together set the amplitude $`A`$ and phase constant $`\phi`$.

### Differential Equation for SHM

Applying Newton's second law to an object with a restoring force proportional to displacement gives the equation that defines SHM:

```math
\frac{d^{2} x}{d t^{2}}=-\omega^{2} x
```

This says the acceleration is proportional to displacement but in the opposite direction. That relationship is the mathematical signature of SHM, and its solution is the sinusoidal position function above.

For a mass-spring system, this equation comes from:

- Restoring force: $`F = -kx`$ (Hooke's Law)
- Newton's Second Law: $`F = ma = m\frac{d^2x}{dt^2}`$
- Setting these equal: $`m\frac{d^2x}{dt^2} = -kx`$
- Rearranging: $`\frac{d^2x}{dt^2} = -\frac{k}{m}x = -\omega^2x`$ where $`\omega = \sqrt{\frac{k}{m}}`$

You are expected to know that the sinusoidal function solves this equation and to identify SHM from it, but you do not need to prove the solution is correct.

### Characteristics from the Position Equation

From the general position equation $`x=A \cos (\omega t+\phi)`$ (where $`\phi`$ is the phase constant), you can derive the other characteristics of SHM.

Velocity is the derivative of position with respect to time: $`v = \frac{dx}{dt} = -A\omega \sin(\omega t + \phi)`$

Acceleration is the derivative of velocity with respect to time: $`a = \frac{dv}{dt} = -A\omega^2 \cos(\omega t + \phi) = -\omega^2 x`$

The acceleration is always proportional to displacement and directed toward equilibrium. That is what defines SHM.

Maximum values for velocity and acceleration:

- Maximum velocity: $`v_{max} = A\omega`$ (occurs at $`x = 0`$)
- Maximum acceleration: $`a_{max} = A\omega^2`$ (occurs at $`x = \pm A`$)

### Zeros and Extrema of Displacement, Velocity, and Acceleration

Recognizing where displacement, velocity, and acceleration are zero or at their extreme values is one of the most useful skills for describing SHM qualitatively. Here is a summary of the key relationships:

| Condition | Displacement $`x`$ | Velocity $`v`$ | Acceleration $`a`$ |
|---|---|---|---|
| At turning points ($`x = \pm A`$) | Maximum magnitude ($`\pm A`$) | Zero | Maximum magnitude ($`a_{max} = A\omega^2`$), directed toward equilibrium |
| At equilibrium ($`x = 0`$) | Zero | Maximum magnitude ($`v_{max} = A\omega`$) | Zero |

Key things to notice:

1. **Displacement** is at its maximum or minimum ($`x = \pm A`$) at the turning points, where the object momentarily stops before reversing direction. Velocity is zero and the magnitude of acceleration is greatest here.
2. **Displacement** is zero at the equilibrium position, where the object moves fastest. Velocity has its greatest magnitude and acceleration is zero here.
3. **Velocity** is zero at the turning points ($`x = \pm A`$) and has its greatest magnitude as the object passes through equilibrium ($`x = 0`$).
4. **Acceleration** is zero at equilibrium ($`x = 0`$) and has its greatest magnitude at the turning points ($`x = \pm A`$). Acceleration always points back toward equilibrium.

Recognizing these zeros and extrema on graphs or at specific times helps you figure out where the object is in its cycle and predict what happens next.

### Resonance in Oscillating Systems

Resonance occurs when an external periodic force is applied to an oscillating system at its natural frequency.

The natural frequency is the frequency at which a system oscillates when displaced from equilibrium, set by the physical properties of the system. For a mass-spring system:

```math
f = \frac{1}{2\pi}\sqrt{\frac{k}{m}}
```

When a system is driven at its natural frequency:

- Energy transfer from the driving force to the system is maximized
- The amplitude of oscillation increases significantly
- Even a small periodic force can produce large-amplitude oscillations

A few applications of resonance: a child on a swing pushed at the right moment, musical instruments producing sound, and large structures like the Tacoma Narrows Bridge responding to wind. These are illustrations of the idea, not required AP content.

### Amplitude vs Period in SHM

One of the most important properties of SHM is that the period is independent of the amplitude.

The period depends only on:

- The mass of the object
- The stiffness of the spring (or equivalent restoring force)

For a mass-spring system: $`T = 2\pi\sqrt{\frac{m}{k}}`$

This means that whether you displace a mass-spring system a small amount or a large amount, it takes the same time to complete one full oscillation. The amplitude affects *how far* the object moves, not *how long* each cycle takes.

### Graphical Analysis of SHM

Graphs give you a visual way to analyze SHM.

Displacement-time graphs:

- Sinusoidal curve
- Amplitude equals maximum displacement
- Period is the time for one complete cycle

Velocity-time graphs:

- Also sinusoidal
- Phase shifted by 90 degrees ($`\frac{\pi}{2}`$ radians) compared to displacement
- When displacement is maximum, velocity is zero
- When displacement is zero, velocity is maximum

Acceleration-time graphs:

- Sinusoidal curve
- Phase shifted by 180 degrees ($`\pi`$ radians) compared to displacement
- Acceleration magnitude is maximum when displacement is maximum
- Acceleration is zero when displacement is zero

These phase relationships let you identify where in the cycle an object is at any given time.

🚫 **Boundary Statement**

On the exam, you are expected to know the solution to the second-order differential equation that describes SHM and to identify SHM. You are not expected to mathematically prove that the solution is correct.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

- Match a given position equation to the standard form $`x = A\cos(\omega t + \phi)`$ to read off $`A`$ and $`\omega`$, then use $`\omega = 2\pi f`$ to find frequency or $`T = 2\pi/\omega`$ to find period.
- Differentiate position to get velocity and acceleration rather than memorizing every variant. The calculus is fast and avoids sign mistakes.
- Use $`v_{max} = A\omega`$ and $`a_{max} = A\omega^2`$ as quick checks on your answers.
- To find velocity at a specific displacement, either solve for the time first or use the energy relationship from the next topic. Both work, so pick the cleaner path.

### Free Response

- The Translation Between Representations question may ask you to sketch graphs, draw free-body diagrams, or write equations for an oscillating block-spring system and then explain how those representations agree.
- When you sketch $`x(t)`$, $`v(t)`$, and $`a(t)`$, line up the zeros and extrema correctly: velocity peaks where displacement crosses zero, and acceleration peaks where displacement is at $`\pm A`$.
- When asked to justify a claim, point to the relationship $`a = -\omega^2 x`$ or to a specific feature of a graph rather than just stating the result.

### Common Trap

- Read initial conditions carefully before choosing sine or cosine. Starting at equilibrium with positive velocity means sine, not cosine.
- Keep track of signs when reporting velocity. A negative velocity means the object is moving toward decreasing $`x`$, which is useful information, not an error.

## Common Misconceptions

- **Misconception:** Changing the amplitude changes the period.  
  **Actually:** Changing the amplitude does not change the period. A larger swing means the object moves faster and covers more distance, so the cycle time stays the same.
- **Misconception:** Velocity and acceleration are maximum at the same place.  
  **Actually:** Velocity and acceleration are not maximum at the same place. Velocity peaks at equilibrium, while acceleration peaks at the turning points.
- **Misconception:** Acceleration is zero just because velocity is zero.  
  **Actually:** Acceleration is not zero just because velocity is zero. At the turning points velocity is zero but acceleration is at its maximum magnitude.
- **Misconception:** The acceleration in SHM is constant.  
  **Actually:** The acceleration in SHM is not constant. It changes continuously because it is proportional to a changing displacement, so the constant-acceleration kinematics equations do not apply.
- **Misconception:** Resonance creates energy.  
  **Actually:** Resonance does not create energy. The driving force at the natural frequency just transfers energy into the system efficiently, which builds up the amplitude.
- **Misconception:** The phase constant $`\phi`$ is the same as the angular frequency $`\omega`$.  
  **Actually:** The phase constant $`\phi`$ is not the same as the angular frequency $`\omega`$. The phase constant sets the starting point of the motion, while $`\omega`$ sets how fast the oscillation cycles.

## Practice Problem 1: SHM Displacement and Velocity

A mass attached to a spring oscillates with simple harmonic motion described by the equation x = 0.15 cos(4πt), where x is in meters and t is in seconds. Determine:

a) The amplitude of the motion b) The frequency of oscillation c) The maximum velocity of the mass d) The velocity when the displacement is 0.075 m

**Solution**

From the given equation x = 0.15 cos(4πt), we can identify:

a) The amplitude is the coefficient of the cosine function: A = 0.15 m

b) The frequency comes from comparing with the standard form x = A cos(2πft): 2πf = 4π f = 2 Hz

c) The maximum velocity is given by vmax = Aω = A(2πf): vmax = 0.15 × 4π = 0.15 × 12.57 = 1.88 m/s

d) When x = 0.075 m (half the amplitude), find the corresponding time first: 0.075 = 0.15 cos(4πt) cos(4πt) = 0.5 4πt = π/3 or 4πt = 5π/3 (for the first cycle)

Using the velocity equation v = -Aω sin(ωt): v = -0.15 × 4π × sin(π/3) v = -0.15 × 4π × 0.866 v = -1.63 m/s

The negative sign indicates the mass is moving toward the equilibrium position.

## Practice Problem 2: Resonance and Natural Frequency

A 0.5 kg mass is attached to a spring with spring constant k = 20 N/m. The system is driven by an external periodic force. At what frequency should the external force be applied to achieve resonance?

**Solution**

For resonance to occur, the driving frequency must match the natural frequency of the system.

For a mass-spring system, the natural frequency is:

f = (1/2π)√(k/m)

Substituting the given values: f = (1/2π)√(20/0.5) f = (1/2π)√40 f = (1/2π) × 6.32 f = 1.01 Hz

Therefore, the external force should be applied at a frequency of 1.01 Hz to achieve resonance.

## Practice Problem 3: Graphical Analysis of SHM

A particle undergoes SHM with amplitude 10 cm and period 4 seconds. If the particle starts from the equilibrium position with positive velocity, determine:

a) The equation for the displacement as a function of time b) At what times during the first cycle is the acceleration maximum? c) Sketch the displacement, velocity, and acceleration graphs for the first cycle

**Solution**

a) Since the particle starts at the equilibrium position (x = 0) with positive velocity, we use the sine function:

A = 10 cm = 0.1 m T = 4 s ω = 2π/T = 2π/4 = π/2 rad/s

Therefore, x(t) = 0.1 sin(πt/2) meters

b) Acceleration is maximum in magnitude when displacement is maximum (either positive or negative).

From x(t) = 0.1 sin(πt/2), displacement is maximum when sin(πt/2) = ±1 This occurs when πt/2 = π/2 and πt/2 = 3π/2 for the first cycle

Solving for t: t = 1 s (for maximum positive displacement) t = 3 s (for maximum negative displacement)

At these times, acceleration is at its maximum magnitude (in the negative and positive directions, respectively).

c) For the first cycle (0 ≤ t ≤ 4):

Displacement: x(t) = 0.1 sin(πt/2) m Velocity: v(t) = 0.1 × (π/2) × cos(πt/2) = 0.157 cos(πt/2) m/s Acceleration: a(t) = -0.1 × (π/2)² × sin(πt/2) = -0.247 sin(πt/2) m/s²

The displacement graph is a sine curve starting at zero, reaching maximum at t = 1 s, returning to zero at t = 2 s, reaching minimum at t = 3 s, and returning to zero at t = 4 s.

The velocity graph is a cosine curve, 90 degrees out of phase with displacement, starting at maximum, reaching zero at t = 1 s, reaching minimum at t = 2 s, returning to zero at t = 3 s, and reaching maximum again at t = 4 s.

The acceleration graph is a negative sine curve, 180 degrees out of phase with displacement, starting at zero, reaching minimum at t = 1 s, returning to zero at t = 2 s, reaching maximum at t = 3 s, and returning to zero at t = 4 s.

## Related AP Physics C: Mechanics Guides

- [7.1 Defining Simple Harmonic Motion (SHM)](01-defining-simple-harmonic-motion-shm.md)
- [7.5 Simple and Physical Pendulums](05-simple-and-physical-pendulums.md)
- [7.2 Frequency and Period of SHM](02-frequency-and-period-of-shm.md)
- [7.4 Energy of Simple Harmonic Oscillators](04-energy-of-simple-harmonic-oscillators.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| acceleration | A vector quantity that describes the rate of change of an object's velocity with respect to time. |
| amplitude | The maximum displacement of an object from its equilibrium position in simple harmonic motion. |
| angular frequency | The rate of change of phase angle in simple harmonic motion, denoted by ω and related to frequency by ω = 2πf. |
| displacement | A vector quantity representing the change in position from an initial to a final location. |
| equilibrium position | The position where the spring force on an object is zero and the object-spring system is at rest. |
| extrema | The maximum and minimum values of displacement, velocity, or acceleration in simple harmonic motion. |
| frequency | The number of complete oscillations or cycles of simple harmonic motion that occur per unit time, measured in hertz (Hz). |
| natural frequency | The frequency at which a system will oscillate when displaced from its equilibrium position in the absence of external driving forces. |
| period | The time required for an object to complete one full circular path, rotation, or cycle. |
| phase constant | A constant (φ) in the equation x = A cos(ωt + φ) that determines the initial position and velocity of an object in simple harmonic motion. |
| resonance | The phenomenon where an oscillating system experiences maximum amplitude when driven by an external force at its natural frequency. |
| velocity | A vector quantity that describes the rate of change of an object's position with respect to time. |

## Frequently Asked Questions

### What is the simple harmonic motion differential equation?

The SHM differential equation is d^2x/dt^2 = -omega^2 x. It means acceleration is proportional to displacement but points in the opposite direction, back toward equilibrium.

### How do you represent position in SHM?

Position in SHM can be represented with x = A cos(omega t + phi) or x = A sin(omega t + phi). The choice depends on initial position and velocity.

### Where is velocity maximum in SHM?

Velocity has maximum magnitude at equilibrium, where displacement is zero. At the turning points, velocity is zero because the object changes direction there.

### Where is acceleration maximum in SHM?

Acceleration has maximum magnitude at the turning points, where displacement is plus or minus the amplitude. Acceleration is zero at equilibrium.

### Does amplitude change the period in SHM?

For the ideal SHM models used in AP Physics C: Mechanics, changing amplitude does not change the period. The period depends on system properties such as mass and spring constant, not on amplitude.

### What is resonance in simple harmonic motion?

Resonance happens when an external force drives an oscillating system at its natural frequency. In AP Physics C: Mechanics, the key result is an increase in the amplitude of oscillation.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-7/3-representing-and-analyzing-shm/study-guide/nHLSGDEgw3L81KKh](https://fiveable.me/ap-physics-c-mechanics/unit-7/3-representing-and-analyzing-shm/study-guide/nHLSGDEgw3L81KKh)</sub>
