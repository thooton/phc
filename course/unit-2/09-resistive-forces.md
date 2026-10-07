# 2.9 Resistive Forces

## What are resistive forces in AP Physics C: Mechanics?

A resistive force is a velocity-dependent force that points opposite an object's velocity, often modeled as $`\vec{F}_{r}=-k\vec{v}`$. When you apply Newton's second law to an object under this kind of force, you get a first-order differential equation that you solve by separation of variables, and the resulting velocity, acceleration, and position are exponential functions that approach a terminal value over time.

## Why This Matters for the AP Physics C: Mechanics Exam

This topic combines forces with calculus, which is exactly the kind of thinking AP Physics C: Mechanics rewards. You take a physical setup, write Newton's second law as a differential equation, and solve it with separation of variables and proper limits of integration. That same chain of reasoning shows up when you derive symbolic expressions, predict how velocity changes over time, and explain why an object levels off at terminal speed.

You may also be asked to translate between representations: a verbal description of an object slowing in a fluid, the differential equation, the exponential solution, and a graph with an asymptote. Building fluency moving among words, math, and graphs is useful across the free-response section, including questions that ask you to make a claim and then back it with a derivation.

## Key Takeaways

- A resistive force is velocity-dependent and points opposite the velocity, modeled here as $`\vec{F}_{r}=-k\vec{v}`$. This is not the same as ordinary kinetic friction.
- Newton's second law turns the situation into a first-order separable differential equation: $`m\frac{dv}{dt}=F_{constant}-kv`$.
- Solving by separation of variables with limits gives an exponential velocity, $`v(t)=v_{term}+(v_0-v_{term})e^{-kt/m}`$.
- The time constant $`\tau=\frac{m}{k}`$ sets how fast the object approaches terminal velocity; after one $`\tau`$, velocity reaches about 63% of its final value.
- Terminal velocity happens when the net force is zero: $`v_{terminal}=\frac{F_{constant}}{k}`$, which becomes $`\frac{mg}{k}`$ for a falling object.
- Velocity and acceleration are exponential in time and decay toward asymptotes, while position grows nearly linearly at the terminal rate for large $`t`$.

## Motion with Resistive Force

### Resistive Force Definition

Resistive forces act opposite an object's motion and slow it down over time. Because the force depends on speed, faster objects feel stronger resistance, which naturally limits how fast the object can go.

- Acts in the opposite direction of an object's velocity vector
- Magnitude increases with speed (faster objects experience stronger resistance)
- Examples include air resistance and fluid drag. In this topic, a resistive force means a velocity-dependent force opposite the object's velocity, such as $`\vec{F}_{r}=-k \vec{v}`$. Do not confuse this with ordinary kinetic friction, which is modeled separately.

Air resistance is the most common everyday example. In this model it is written as:

```math
\vec{F}_{r}=-k \vec{v}
```

Here $`k`$ is a positive constant that depends on the object's shape, size, and the medium it moves through, and $`\vec{v}`$ is the velocity vector. The negative sign shows the force opposes motion.

This model treats the resistive force as proportional to velocity, which fits objects moving at relatively low speeds through fluids.

### Differential Equation for Velocity

When an object experiences a resistive force, its motion follows a differential equation that comes straight from Newton's second law. This is where calculus does the heavy lifting.

Applying Newton's second law ($`\vec{F}_{net} = m\vec{a}`$) to an object with both a constant force and a resistive force:

```math
m\frac{dv}{dt} = F_{constant} - kv
```

This first-order differential equation is solved using **separation of variables** with proper limits of integration. Here is the explicit derivation:

Starting from $`m\frac{dv}{dt} = F_{constant} - kv`$, separate variables by moving all $`v`$-terms to one side and $`t`$-terms to the other:

```math
\frac{dv}{F_{constant} - kv} = \frac{dt}{m}
```

Now integrate both sides using limits. If the object has initial velocity $`v_0`$ at $`t = 0`$ and velocity $`v`$ at time $`t`$:

```math
\int_{v_0}^{v} \frac{dv'}{F_{constant} - kv'} = \int_{0}^{t} \frac{dt'}{m}
```

Evaluate the left side with a $`u`$-substitution ($`u = F_{constant} - kv'`$, $`du = -k\,dv'`$):

```math
-\frac{1}{k}\ln\left(\frac{F_{constant} - kv}{F_{constant} - kv_0}\right) = \frac{t}{m}
```

Solve for $`v(t)`$ by exponentiating both sides and rearranging:

```math
F_{constant} - kv = (F_{constant} - kv_0)\,e^{-kt/m}
```

```math
v(t) = \frac{F_{constant}}{k} + \left(v_0 - \frac{F_{constant}}{k}\right)e^{-kt/m}
```

The initial condition $`v_0`$ enters directly through the limits of integration, which is why setting up those limits carefully matters.

The time constant $`\tau = \frac{m}{k}`$ tells you how quickly the object approaches its terminal velocity. After one time constant, the velocity reaches about 63% of its final value.

- Objects with larger mass take longer to reach terminal velocity
- Stronger resistive forces (larger $`k`$ values) cause objects to reach terminal velocity more quickly
- The approach to terminal velocity follows an exponential pattern

### Time-Dependent Functions: Velocity, Acceleration, and Position

For a constant applied force $`F_{constant}`$ in the positive direction and resistive force $`\vec{F}_{r} = -k\vec{v}`$, you can write the full set of time-dependent functions. Defining the terminal velocity as $`v_{term} = \frac{F_{constant}}{k}`$:

**Velocity:**

```math
v(t) = v_{term} + (v_0 - v_{term})\,e^{-kt/m}
```

**Acceleration** (found by differentiating velocity):

```math
a(t) = \frac{dv}{dt} = -\frac{k}{m}(v_0 - v_{term})\,e^{-kt/m}
```

**Position** (found by integrating velocity):

```math
x(t) = x_0 + v_{term}\,t + \frac{m}{k}(v_0 - v_{term})(1 - e^{-kt/m})
```

Each function depends on the initial conditions $`x_0`$ and $`v_0`$. Velocity and acceleration are exponential functions of time, while position is a linear term plus an exponential term. Their long-term behavior is set by asymptotes:

- As $`t \to \infty`$, $`v(t) \to v_{term}`$ (velocity approaches terminal velocity asymptotically)
- As $`t \to \infty`$, $`a(t) \to 0`$ (acceleration decays exponentially to zero)
- As $`t \to \infty`$, $`x(t)`$ grows approximately linearly at the rate $`v_{term}`$, since the exponential correction term vanishes

### Terminal Velocity

Terminal velocity is the maximum speed reached when a constant force and a resistive force act in opposite directions. It happens when the net force is zero, so acceleration is zero. If the constant force has magnitude $`F_{constant}`$ and the resistive force is $`kv`$ opposite the motion, then at terminal speed $`F_{constant} - kv_{terminal} = 0`$, so:

```math
v_{terminal} = \frac{F_{constant}}{k}
```

For a falling object, $`F_{constant} = mg`$, giving:

```math
v_{terminal} = \frac{mg}{k}
```

This balance explains many everyday situations:

- Skydivers control their descent rate by changing body position, effectively altering their $`k`$ value
- Raindrops fall at different terminal velocities depending on their size
- Heavier objects generally reach higher terminal velocities in the same medium

The time required to get close to terminal velocity depends on how far the initial velocity is from terminal velocity and on the time constant $`\tau`$. An object reaches roughly 95% of terminal velocity after about 3 time constants.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

- Start every resistive-force problem by drawing a free-body diagram and writing Newton's second law along the direction of motion. Get the signs right: the resistive term opposes velocity.
- Recognize the setup $`m\frac{dv}{dt} = F_{constant} - kv`$ as a first-order separable equation. Separate variables, then integrate with limits that match your initial condition.
- Once you have $`v(t)`$, get acceleration by differentiating and position by integrating. Carry your initial conditions through every step.

### Free Response

- For derivations, show the separation of variables and the limits of integration clearly. Skipping these steps can cost points even if the final answer is right.
- When a question asks for terminal velocity, set the net force to zero rather than taking a limit, unless the limit is what is requested. Both should give the same value.
- If you are asked to sketch a graph, draw the asymptote. Velocity should level off at $`v_{term}`$, and acceleration should decay toward zero.

### Common Trap

- Plugging numbers in too early. Keep things symbolic until the final step so you can check units and functional dependence.

## Practice Problem 1: Terminal Velocity

A skydiver with mass 75 kg jumps from an airplane. If the air resistance is proportional to velocity with a constant $`k = 15`$ kg/s, what is the skydiver's terminal velocity? How long will it take to reach 90% of terminal velocity?

**Solution**

First, find the terminal velocity: $`v_{terminal} = \frac{mg}{k}`$

Given:

- Mass (m) = 75 kg
- Gravitational acceleration (g) = 9.8 m/s²
- Resistance constant (k) = 15 kg/s

```math
v_{terminal} = \frac{75 \times 9.8}{15} = \frac{735}{15} = 49 \text{ m/s}
```

To find the time to reach 90% of terminal velocity, use the exponential approach equation: $`v(t) = v_{terminal}(1 - e^{-t/\tau})`$

Where $`\tau = \frac{m}{k} = \frac{75}{15} = 5`$ seconds.

Find $`t`$ when $`v(t) = 0.9 \times v_{terminal}`$: $`0.9 = 1 - e^{-t/5}`$

```math
e^{-t/5} = 0.1
```

```math
-t/5 = \ln(0.1)
```

```math
t = -5 \times \ln(0.1) = -5 \times (-2.3) = 11.5 \text{ seconds}
```

So the skydiver reaches 90% of terminal velocity (44.1 m/s) after about 11.5 seconds.

## Practice Problem 2: Motion with Resistive Force

A 2 kg object is thrown upward with an initial velocity of 20 m/s. If it experiences a resistive force proportional to velocity with constant $`k = 0.4`$ kg/s, find the maximum height it reaches.

**Solution**

This requires solving the differential equation of motion with both gravity and the resistive force.

Given:

- Mass (m) = 2 kg
- Initial velocity (v₀) = 20 m/s
- Resistance constant (k) = 0.4 kg/s
- Gravitational acceleration (g) = 9.8 m/s²

The differential equation is: $`m\frac{dv}{dt} = -mg - kv`$

The velocity as a function of time is: $`v(t) = (v_0 + \frac{mg}{k})e^{-kt/m} - \frac{mg}{k}`$

To find the maximum height, find when $`v = 0`$, then calculate the displacement.

Setting $`v(t) = 0`$: $`(20 + \frac{2 \times 9.8}{0.4})e^{-0.4t/2} - \frac{2 \times 9.8}{0.4} = 0`$

```math
(20 + 49)e^{-0.2t} = 49
```

```math
69e^{-0.2t} = 49
```

```math
e^{-0.2t} = \frac{49}{69}
```

```math
-0.2t = \ln(\frac{49}{69})
```

```math
t = -\frac{1}{0.2}\ln(\frac{49}{69}) = -5\ln(\frac{49}{69}) \approx 1.713 \text{ seconds}
```

The height comes from integrating the velocity function from $`t = 0`$ to $`t = 1.713`$: $`h = \int_0^{1.713} v(t) \, dt`$

Using the position formula for this type of motion: $`x(t) = x_0 + \frac{m}{k}(v_0 + \frac{mg}{k})(1-e^{-kt/m}) - \frac{mg}{k}t`$

Substituting with $`x_0 = 0`$: $`h = \frac{2}{0.4}(20 + \frac{2 \times 9.8}{0.4})(1-e^{-0.4 \times 1.713/2}) - \frac{2 \times 9.8}{0.4} \times 1.713`$

```math
h = 5(20 + 49)(1-e^{-0.3426}) - 49 \times 1.713
```

Using $`e^{-0.3426} \approx 0.7101`$, so $`1 - e^{-0.3426} \approx 0.2899`$.

```math
h = 5 \times 69 \times 0.2899 - 49 \times 1.713
```

```math
h \approx 99.97 - 83.94 = 16.03 \text{ meters}
```

So the object reaches a maximum height of about **16.0 meters**.

## Common Misconceptions

- **Misconception:** Resistive force is the same as kinetic friction.  
  **Actually:** Resistive force is not the same as kinetic friction. Kinetic friction is modeled as roughly constant ($`\mu_k F_N`$), while a resistive force here depends on velocity. Mixing the two leads to the wrong equation.
- **Misconception:** The object stops at terminal velocity.  
  **Actually:** Terminal velocity does not mean the object stops. It means acceleration is zero and the object keeps moving at a constant speed.
- **Misconception:** The object reaches terminal velocity exactly in finite time.  
  **Actually:** The object never exactly reaches terminal velocity in finite time. The approach is exponential and asymptotic, so it gets arbitrarily close but never quite there.
- **Misconception:** The time constant $`\tau = \frac{m}{k}`$ is the time to reach terminal velocity.  
  **Actually:** The time constant $`\tau = \frac{m}{k}`$ is not the time to reach terminal velocity. After one $`\tau`$, the velocity is only about 63% of the way there.
- **Misconception:** Larger resistance always means slower behavior in every sense.  
  **Actually:** A larger $`k`$ means a lower terminal velocity but a faster approach to it. Students sometimes assume larger resistance always means slower behavior in every sense, but it speeds up the approach while lowering the final speed.
- **Misconception:** You can use the constant-acceleration kinematics equations here.  
  **Actually:** You cannot use the constant-acceleration kinematics equations here. Acceleration changes with time, so those formulas do not apply.

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
| asymptote | A line or value that a function approaches but never reaches, determined by initial conditions and forces in resistive force problems. |
| differential equation | An equation relating a function to its derivatives, used to describe how velocity changes with time under a resistive force. |
| exponential function | A mathematical function describing position, velocity, and acceleration of an object under a resistive force, characterized by constant percentage change over time. |
| initial conditions | The starting values of position, velocity, and acceleration used to determine the specific motion of an object under a resistive force. |
| net force | The vector sum of all forces acting on an object or system. |
| resistive force | A velocity-dependent force that acts in the opposite direction of an object's velocity, opposing its motion. |
| separation of variables | A mathematical method for solving differential equations by rearranging terms so that each variable appears on only one side of the equation. |
| terminal velocity | The maximum constant speed achieved by an object when the net force acting on it becomes zero, occurring when the resistive force balances other forces. |
| velocity-dependent force | A force whose magnitude depends on the velocity of an object, typically proportional to velocity or velocity squared. |

## Frequently Asked Questions

### What are resistive forces in AP Physics C: Mechanics?

A resistive force is a velocity-dependent force that acts opposite an object's velocity. In the AP Physics C model for this topic, it is often written as F\_r = -kv.

### What is the resistive force formula?

For the linear drag model in AP Physics C: Mechanics, the resistive force is F\_r = -kv, where k is a positive constant and v is velocity. The negative sign shows that the force points opposite the motion.

### How do resistive forces create a differential equation?

Applying Newton's second law with a constant force and a resistive force gives an equation such as m dv/dt = F\_constant - kv. Because velocity appears in the force term, you solve for v(t) with separation of variables.

### What is terminal velocity?

Terminal velocity is the maximum speed reached when the constant force and resistive force balance so the net force is zero. For a falling object with F\_r = -kv, terminal velocity has magnitude mg/k.

### How does the time constant m/k affect motion with resistive force?

The time constant tau = m/k controls how quickly velocity approaches terminal velocity. Larger mass makes the approach slower, while larger k makes the approach faster and lowers the terminal speed.

### How is resistive force tested on AP Physics C: Mechanics?

Questions can ask you to write Newton's second law as a differential equation, separate variables, apply initial conditions, derive v(t), identify terminal velocity, or interpret exponential velocity and acceleration graphs.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-2/9-resistive-forces/study-guide/pXbIz3a4RtJYP8Gq](https://fiveable.me/ap-physics-c-mechanics/unit-2/9-resistive-forces/study-guide/pXbIz3a4RtJYP8Gq)</sub>
