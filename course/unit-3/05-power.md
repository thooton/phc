# 3.5 Power

Power is how fast energy moves into, out of, or within a system. You can find average power with $`P_{avg} = \frac{\Delta E}{\Delta t}`$ or $`P_{avg} = \frac{W}{\Delta t}`$, and instantaneous power with $`P_{inst} = \frac{dW}{dt}`$ or $`P_{inst} = Fv\cos\theta`$.

## Why This Matters for the AP Physics C: Mechanics Exam

Power connects work, energy, force, and velocity, so it shows up wherever you already use energy ideas. On the exam, you might calculate how fast a motor or person delivers energy, read power off a graph, or derive a power expression using calculus. Because the first free-response question asks you to create and use mathematical models, power problems are good practice for setting up an equation, plugging in correct units, and explaining your reasoning clearly. Power also appears later when you study rotation, where the same logic gives $`P = \tau\omega`$.

## Key Takeaways

- Power is the rate of energy transfer or conversion, not the total energy itself.
- Use $`P_{avg} = \frac{\Delta E}{\Delta t}`$ or $`P_{avg} = \frac{W}{\Delta t}`$ for average power over a time interval.
- Use $`P_{inst} = \frac{dW}{dt}`$ when power changes continuously and you want the value at one instant.
- For a constant force, $`P_{inst} = F_{\parallel} v = Fv\cos\theta`$, so only the force component along the velocity counts.
- The SI unit is the watt (W), equal to one joule per second (J/s).
- Negative power means energy is being removed from the system.

## Energy Transfer and Power

### Power as Energy Rate

Power measures how quickly energy is transferred into or out of a system, or converted from one form to another within a system.

- Power tells you the rate of energy change, not the total amount of energy.
- The SI unit of power is the watt (W), which equals one joule per second (J/s).
- A system with high power can transfer or convert large amounts of energy in a short time.
- Engines, electric motors, and even muscles are common examples of systems described by power.

### Average Power Calculation

Average power looks at the total energy transferred over a specific time period.

- Divide the total energy transferred or converted by the time it took: $`P_{\text{avg}}=\frac{\Delta E}{\Delta t}`$
- The change in energy ($`\Delta E`$) is measured in joules.
- The time interval ($`\Delta t`$) is measured in seconds.
- This works for any form of energy transfer or conversion.

For example, if a 60 W light bulb uses 180 joules over 3 seconds, its average power is $`P_{\text{avg}}=\frac{180 \text{ J}}{3 \text{ s}}=60 \text{ W}`$.

### Power and Work Relationship

Because work is energy transferred by a force, you can also write power in terms of work.

- Divide the total work done by the time interval: $`P_{\text{avg}}=\frac{W}{\Delta t}`$
- Power increases when either:
  
  - More work is done in the same amount of time, or
  - The same work is done in less time.
- This is why engines are rated by power (like horsepower) instead of just total energy output.

### Instantaneous Power

Average power gives the overall rate, but instantaneous power gives the exact rate at one moment.

- Instantaneous power is the derivative of work with respect to time: $`P_{\text{inst}}=\frac{dW}{dt}`$
- This calculus definition lets you analyze systems where power changes continuously.
- It is useful for dynamic situations like an accelerating car or a changing load.
- It is the limit of average power as the time interval shrinks toward zero.

### Power from Force and Velocity

For mechanical systems, you can connect power directly to force and velocity.

- When a constant force moves an object, the instantaneous power delivered is: $`P_{\text{inst}}=F_{\parallel} v=F v \cos \theta`$
- $`F_{\parallel}`$ is the component of force parallel to the motion.
- $`\theta`$ is the angle between the force and velocity vectors.
- This equation shows that:
  
  - When force and velocity are parallel ($`\theta = 0°`$), power transfer is largest.
  - When force and velocity are perpendicular ($`\theta = 90°`$), no power is transferred.
  - Negative power means energy is being removed from the system.

For example, when pushing a cart, you deliver the most power when pushing straight along the direction of motion. Pushing at an angle reduces the effective force component and lowers the power.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

- Identify whether the question wants average power or instantaneous power. Average power uses a time interval; instantaneous power uses a single moment.
- For lifting or vertical-climb problems, the work done against gravity is $`mg\Delta y`$, so $`P_{avg} = \frac{mg\Delta y}{\Delta t}`$.
- When force and velocity are both given and the force is constant, go straight to $`P = Fv\cos\theta`$ instead of finding work first.
- Watch the angle. Only the force component along the velocity contributes, so check $`\theta`$ before multiplying.
- Track units carefully. Answers in watts come from joules per second, and you can convert to kilowatts (1 kW = 1000 W) when numbers get large.

### Derivation

- If power varies with time, start from $`P_{inst} = \frac{dW}{dt}`$ and connect work to force and displacement.
- To get $`P = Fv\cos\theta`$, recognize that $`\frac{dW}{dt}`$ for a constant force becomes $`\vec{F}\cdot\vec{v}`$, which is $`Fv\cos\theta`$.
- Keep your steps in symbols first, then plug in numbers at the end so your logic stays clear.

### Graphs

- On a power versus time graph, the area under the curve equals the energy transferred.
- On an energy versus time graph, the slope at a point equals the instantaneous power.

## Practice Problem 1: Average Power Calculation

A 75 kg student runs up a flight of stairs with a vertical height of 4.0 m in 3.5 seconds. Calculate the average power output of the student during this climb. (Use g = 9.8 m/s²)

**Solution**

Find the work done against gravity, then divide by the time.

Step 1: Calculate the work done. Work = Force × distance = mass × gravity × height Work = 75 kg × 9.8 m/s² × 4.0 m = 2,940 J

Step 2: Calculate the average power. $`P_{\text{avg}} = \frac{W}{\Delta t} = \frac{2,940 \text{ J}}{3.5 \text{ s}} = 840 \text{ W}`$

The student's average power output is 840 watts, about the same as a small microwave oven.

## Practice Problem 2: Power from Force and Velocity

A 1200 kg car accelerates from rest under a constant force of 3000 N. After 8 seconds, the car reaches a speed of 20 m/s. Calculate the instantaneous power delivered to the car at that moment.

**Solution**

Use the equation $`P_{\text{inst}} = F v \cos \theta`$.

Given:

- Force F = 3000 N
- Velocity v = 20 m/s
- Angle θ = 0° (the force is in the same direction as the velocity)

Since the force is parallel to the velocity, cos θ = cos 0° = 1.

```math
P_{\text{inst}} = F v \cos \theta = 3000 \text{ N} \times 20 \text{ m/s} \times 1 = 60,000 \text{ W} = 60 \text{ kW}
```

The instantaneous power delivered to the car at that moment is 60 kilowatts, equivalent to about 80 horsepower, which gives a sense of the engine power needed for this acceleration.

## Common Misconceptions

- **Misconception:** Power and energy are the same thing.  
  **Actually:** Power and energy are not the same thing. Energy is measured in joules; power is the rate of energy change measured in watts.
- **Misconception:** More power always means more total work.  
  **Actually:** More power does not always mean more total work. A system can do the same work with more power if it finishes faster.
- **Misconception:** A large force guarantees high power.  
  **Actually:** A large force does not guarantee high power. If the velocity is zero or the force is perpendicular to the motion, the power can be zero.
- **Misconception:** The angle in $`P = Fv\cos\theta`$ is between force and the horizontal.  
  **Actually:** The angle in $`P = Fv\cos\theta`$ is between force and velocity, not force and the horizontal. Using the wrong angle gives the wrong component.
- **Misconception:** Average power and instantaneous power are always the same.  
  **Actually:** Average power and instantaneous power can differ. If power changes over time, dividing total work by total time only gives the average, not the value at a single moment.

## Related AP Physics C: Mechanics Guides

- [3.2 Work](02-work.md)
- [3.3 Potential Energy](03-potential-energy.md)
- [3.4 Conservation of Energy](04-conservation-of-energy.md)
- [3.1 Translational Kinetic Energy](01-translational-kinetic-energy.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| average power | The total amount of energy transferred or converted divided by the time interval over which the transfer or conversion occurs. |
| energy transfer | The process by which energy moves into or out of a system through the action of forces or torques. |
| instantaneous power | The rate at which energy is being transferred or converted at a specific instant in time. |
| power | The rate at which energy is transferred into or out of a system, or converted from one type to another within a system. |
| work | Energy transferred to or from a system by forces or torques acting on it. |

## Frequently Asked Questions

### What is power in AP Physics C Mechanics?

Power is the rate at which energy is transferred or converted. In AP Physics C Mechanics, power often connects work, time, force, velocity, and energy changes.

### What is the average power formula?

Average power is P\_avg = Delta E/Delta t or P\_avg = W/Delta t. Use it when you know total energy transferred or total work over a time interval.

### What is the instantaneous power formula?

Instantaneous power is P\_inst = dW/dt. For a constant or known force at an instant, it can also be written as P = F\_parallel v = Fv cos theta.

### How do you use P = Fv cos theta?

Use P = Fv cos theta when a force acts on an object moving with speed v and theta is the angle between the force and velocity. Only the component of force parallel to motion transfers power.

### What does negative power mean?

Negative power means energy is being removed from the object or system at that instant. For example, a force opposite the velocity does negative work and decreases mechanical energy.

### What units are used for power?

Power is measured in watts, where 1 watt equals 1 joule per second. In mechanics, that also matches the rate at which work is done.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-3/5-power/study-guide/aXNJ6Af1NIzpF1IM](https://fiveable.me/ap-physics-c-mechanics/unit-3/5-power/study-guide/aXNJ6Af1NIzpF1IM)</sub>
