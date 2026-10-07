# 7.2 Frequency and Period of SHM

In simple harmonic motion, period (T), frequency (f), and angular frequency (omega) are tied together by $`T = \frac{2\pi}{\omega} = \frac{1}{f}`$. For a mass on an ideal spring, the period is $`T_s = 2\pi\sqrt{m/k}`$, and for a simple pendulum at small angles it is $`T_p = 2\pi\sqrt{l/g}`$.

## Why This Matters for the AP Physics C: Mechanics Exam

Oscillations make up a solid chunk of the exam, so being fluent with these period and frequency relationships pays off across multiple-choice and free-response questions. You will be asked to predict how the period changes when you adjust mass, spring constant, length, or gravity, and to derive symbolic expressions instead of just plugging in numbers. This topic also connects to graphing and representation work, since the translation-style free-response question can ask you to link diagrams, graphs, and equations for an oscillating block-spring system. Knowing where these formulas come from and what each variable controls helps you reason quickly under time pressure.

## Key Takeaways

- $`T = \frac{2\pi}{\omega} = \frac{1}{f}`$ ties period, frequency, and angular frequency together; higher frequency means shorter period.
- Angular frequency omega is measured in rad/s, frequency f in hertz (Hz), and period T in seconds.
- For a mass-spring oscillator, $`T_s = 2\pi\sqrt{m/k}`$: more mass slows it down, a stiffer spring speeds it up.
- For a simple pendulum at small angles, $`T_p = 2\pi\sqrt{l/g}`$: longer length slows it down, stronger gravity speeds it up.
- Period is independent of amplitude for both the ideal spring and the small-angle pendulum.
- Use functional dependence (square-root scaling) to predict factors of change without recalculating from scratch.

## Angular Frequency Relationship

Simple harmonic motion (SHM) happens when the restoring force is directly proportional to displacement. The timing of these oscillations is described through three connected quantities: period, frequency, and angular frequency.

The period (T) is the time for one complete oscillation cycle. Frequency (f) is how many complete oscillations happen in one second. Angular frequency (omega) is the rate at which the oscillating object moves through its cycle, measured in radians per second.

These quantities are related by:

```math
T=\frac{2\pi}{\omega}=\frac{1}{f}
```

This relationship shows that:

- A higher frequency means a shorter period (faster oscillations)
- A lower frequency means a longer period (slower oscillations)
- Angular frequency is frequency multiplied by 2 pi

For example, if a mass on a spring completes 2 oscillations per second, its frequency is 2 Hz, its period is 0.5 seconds, and its angular frequency is about 12.57 rad/s.

## Spring-Mass Systems

For a mass attached to an ideal spring undergoing SHM, the period depends on the mass and the spring stiffness:

```math
T_s=2\pi\sqrt{\frac{m}{k}}
```

Where:

- m is the mass attached to the spring (in kg)
- k is the spring constant, which measures the spring's stiffness (in N/m)

This equation reveals important physical insights:

- Increasing the mass makes the oscillations slower (longer period)
- Increasing the spring stiffness makes the oscillations faster (shorter period)
- The period is proportional to the square root of the mass-to-spring-constant ratio

The period does not depend on the amplitude of oscillation, so a spring-mass system oscillates at the same frequency regardless of how far it is initially stretched or compressed. This comes from Hooke's law, $`F = -kx`$, which gives the equation of motion $`m\frac{d^2x}{dt^2} = -kx`$ and an angular frequency $`\omega_s = \sqrt{k/m}`$.

## Simple Pendulums

A simple pendulum is a point-mass bob suspended from a pivot by a string or rod. When displaced and released, it undergoes SHM for small angles. The period is:

```math
T_p=2\pi\sqrt{\frac{l}{g}}
```

Where:

- l is the length of the pendulum (distance from pivot to the center of mass of the bob)
- g is the acceleration due to gravity (9.8 m/s² on Earth)

This equation tells us:

- Longer pendulums swing more slowly (longer period)
- Stronger gravity makes pendulums swing faster (shorter period)
- Like the spring-mass system, the period is independent of amplitude for small angles

The small-angle approximation $`\sin\theta \approx \theta`$ (in radians) is what makes this a clean SHM problem, giving angular frequency $`\omega_p = \sqrt{g/l}`$. As an application, this is why a grandfather clock uses a long pendulum for its slower, steady tick, and why a pendulum clock runs slightly differently where gravity is weaker.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

- Identify the system first. Spring-mass uses $`T_s = 2\pi\sqrt{m/k}`$, simple pendulum uses $`T_p = 2\pi\sqrt{l/g}`$.
- Convert between T, f, and omega early so you have the quantity the question actually wants.
- Watch your units: omega in rad/s, f in Hz, T in seconds.

### Free Response

- For symbolic derivations, start from the equation of motion ($`m\frac{d^2x}{dt^2} = -kx`$ for a spring) and identify omega before writing the period.
- For translation-style questions, be ready to connect a diagram or graph of an oscillating block-spring system to its equation and back. Label maxima, minima, and zeros consistently across representations.

### Common Trap

- Because the period scales with a square root, doubling the mass does not double the period. It multiplies the period by $`\sqrt{2}`$.
- Quadrupling the length of a pendulum doubles its period, since $`\sqrt{4} = 2`$.

## Practice Problem 1: Spring-Mass Period

A 0.5 kg mass is attached to a spring with spring constant k = 20 N/m. What is the period of oscillation for this system?

**Solution**

Use the spring-mass period equation:

```math
T_s = 2\pi\sqrt{\frac{m}{k}}
```

Substitute the given values:

- m = 0.5 kg
- k = 20 N/m

```math
T_s = 2\pi\sqrt{\frac{0.5 \text{ kg}}{20 \text{ N/m}}}
```

```math
T_s = 2\pi\sqrt{0.025 \text{ s}^2}
```

```math
T_s = 2\pi \times 0.158 \text{ s}
```

```math
T_s = 0.99 \text{ s} \approx 1.0 \text{ s}
```

The period of oscillation is approximately 1.0 second.

## Practice Problem 2: Pendulum Frequency

A simple pendulum has a length of 2.0 meters. What is its frequency of oscillation on Earth (g = 9.8 m/s²)?

**Solution**

First find the period using the pendulum period equation:

```math
T_p = 2\pi\sqrt{\frac{l}{g}}
```

Substitute the given values:

- l = 2.0 m
- g = 9.8 m/s²

```math
T_p = 2\pi\sqrt{\frac{2.0 \text{ m}}{9.8 \text{ m/s}^2}}
```

```math
T_p = 2\pi\sqrt{0.204 \text{ s}^2}
```

```math
T_p = 2\pi \times 0.452 \text{ s}
```

```math
T_p = 2.84 \text{ s}
```

Now find the frequency using $`f = 1/T`$:

```math
f = \frac{1}{T_p} = \frac{1}{2.84 \text{ s}} = 0.352 \text{ Hz}
```

The pendulum oscillates at a frequency of approximately 0.35 Hz.

## Common Misconceptions

- **Misconception:** Amplitude changes the period.  
  **Actually:** Amplitude does not change the period. Pulling a spring farther or starting a small-angle pendulum from a larger angle still gives the same period.
- **Misconception:** Period and frequency are the same thing.  
  **Actually:** Period and frequency are inverses, not the same thing. A large period means a small frequency.
- **Misconception:** The pendulum period formula holds for large angles.  
  **Actually:** The pendulum period formula only holds for small angles, where $`\sin\theta \approx \theta`$. For large swings the motion is no longer clean SHM and the simple formula breaks down.
- **Misconception:** A heavier simple pendulum bob changes the period.  
  **Actually:** The mass of a simple pendulum bob does not appear in $`T_p = 2\pi\sqrt{l/g}`$, so a heavier bob does not change the period. Mass only matters for the spring system.
- **Misconception:** Angular frequency omega is the same as frequency f.  
  **Actually:** Angular frequency omega is not the same as frequency f. They differ by a factor of $`2\pi`$, so do not plug f into a formula that calls for omega.
- **Misconception:** Changes in mass, spring constant, length, or gravity scale the period proportionally.  
  **Actually:** The relationships are square-root based, so changes in mass, spring constant, length, or gravity do not scale the period proportionally.

## Related AP Physics C: Mechanics Guides

- [7.1 Defining Simple Harmonic Motion (SHM)](01-defining-simple-harmonic-motion-shm.md)
- [7.3 Representing and Analyzing SHM](03-representing-and-analyzing-shm.md)
- [7.5 Simple and Physical Pendulums](05-simple-and-physical-pendulums.md)
- [7.4 Energy of Simple Harmonic Oscillators](04-energy-of-simple-harmonic-oscillators.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| angular frequency | The rate of change of phase angle in simple harmonic motion, denoted by ω and related to frequency by ω = 2πf. |
| frequency | The number of complete oscillations or cycles of simple harmonic motion that occur per unit time, measured in hertz (Hz). |
| object-ideal-spring oscillator | A system consisting of a mass attached to an ideal spring that undergoes simple harmonic motion. |
| period | The time required for an object to complete one full circular path, rotation, or cycle. |
| simple harmonic motion | A special case of periodic motion in which a restoring force proportional to displacement causes an object to oscillate about an equilibrium position. |
| simple pendulum | A special case of a physical pendulum in which the hanging object is modeled as a point mass at a fixed distance from the pivot point. |

## Frequently Asked Questions

### What is the period of simple harmonic motion?

The period is the time for one complete oscillation. In SHM, period, frequency, and angular frequency are related by $`T=\frac{2\pi}{\omega}=\frac{1}{f}`$.

### What is frequency in SHM?

Frequency is the number of oscillations per second, measured in hertz. It is the reciprocal of period, so $`f=1/T`$. A shorter period means a higher frequency.

### What is angular frequency?

Angular frequency measures how quickly an oscillator moves through its cycle in radians per second. It relates to period and frequency by $`\omega=2\pi f`$ and $`T=2\pi/\omega`$.

### What is the period formula for a mass on a spring?

For an ideal mass-spring oscillator, $`T_s=2\pi\sqrt{m/k}`$. More mass increases the period, while a larger spring constant makes the period shorter.

### What is the period formula for a simple pendulum?

For a simple pendulum at small angles, $`T_p=2\pi\sqrt{l/g}`$. A longer pendulum has a longer period, while stronger gravity gives a shorter period.

### Does amplitude affect the period of SHM?

For an ideal spring-mass oscillator and a small-angle pendulum, period does not depend on amplitude. On the AP exam, focus on the system parameters: mass and spring constant for springs, length and gravity for pendulums.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-7/2-frequency-and-period-of-shm/study-guide/ZP4XBQORYFR7bHpw](https://fiveable.me/ap-physics-c-mechanics/unit-7/2-frequency-and-period-of-shm/study-guide/ZP4XBQORYFR7bHpw)</sub>
