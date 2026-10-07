# 5.1 Rotation

## AP Physics C 5.1 Rotational Motion Summary

Rotational kinematics describes how a spinning rigid system changes position over time using angular displacement, angular velocity, and angular acceleration. In AP Physics C rotational motion problems about one fixed axis, these quantities behave like their linear cousins (displacement, velocity, acceleration), so the same kinematics equations and graph rules carry over.

## Why This Matters for the AP Physics C: Mechanics Exam

This topic gives you the language and equations for every rotating system you will see in Unit 5 and Unit 6, from spinning wheels to flywheels to rolling objects. On the exam, you will use these ideas in both multiple-choice and free-response questions, often by predicting how one angular quantity changes when another changes (functional dependence). That kind of reasoning shows up directly in the Qualitative/Quantitative Translation free-response question, where you connect symbolic relationships, words, and calculations. Getting fluent with angular displacement, velocity, and acceleration now makes torque, rotational inertia, and angular momentum much easier later.

## Key Takeaways

- Angular displacement $`\Delta\theta = \theta - \theta_0`$ is measured in radians, and one full circle is $`2\pi`$ radians.
- Angular velocity is $`\omega = \frac{d\theta}{dt}`$ (rad/s); angular acceleration is $`\alpha = \frac{d\omega}{dt}`$ (rad/s²).
- For motion about one fixed axis, angular quantities follow the same math as one-dimensional linear motion.
- When angular acceleration is constant, use $`\omega = \omega_0 + \alpha t`$, $`\theta = \theta_0 + \omega_0 t + \frac{1}{2}\alpha t^2`$, and $`\omega^2 = \omega_0^2 + 2\alpha(\theta - \theta_0)`$.
- On graphs: slope of $`\theta`$-$`t`$ gives $`\omega`$, slope of $`\omega`$-$`t`$ gives $`\alpha`$, and area under $`\omega`$-$`t`$ gives $`\Delta\theta`$.
- You only need clockwise/counterclockwise sign conventions; full vector directions of these quantities are not assessed.

## Angular Displacement in Radians

Angular displacement measures how far an object has rotated about an axis. Unlike linear displacement which uses meters, angular displacement is measured in radians, where a complete circle equals $`2\pi`$ radians (or 360 degrees). It is the change in angular position about a specified axis and is defined as $`\Delta\theta = \theta - \theta_0`$, where $`\theta_0`$ is the initial angular position and $`\theta`$ is the final angular position.

In this topic, rotational kinematics is treated for motion about a single fixed axis, so angular displacement, angular velocity, and angular acceleration are handled the same way as one-dimensional linear motion.

- A rigid system keeps its shape during rotation, but different points on it move in different directions, so it cannot be modeled as a single point object.
- Rotation direction is shown by sign: typically counterclockwise is positive and clockwise is negative.
- When a system's rotation about an axis can be described by its center of mass motion, it can be treated as a single object. For example, Earth's spin about its own axis can be treated as negligible when modeling Earth's revolution around the center of mass of the Earth-Sun system.
- Example: a wheel making a quarter turn rotates through $`\pi/2`$ radians (90 degrees).

A radian is the angle at the center of a circle that is subtended by an arc equal in length to the radius of the circle.

## Angular Velocity Definition

Angular velocity tells you how quickly an object rotates, measured as the rate of change of angular position with respect to time.

- Defined by: $`\omega=\frac{d\theta}{dt}`$
- Units are radians per second (rad/s).
- A constant angular velocity means the object rotates at a steady rate.
- Example: a record spinning at 33⅓ rpm has an angular velocity of $`33\tfrac{1}{3} \times (2\pi/60) \approx 3.49`$ rad/s.

## Angular Acceleration Definition

Angular acceleration describes how angular velocity changes over time. When an object speeds up or slows its rotation, it has angular acceleration.

- Defined by: $`\alpha=\frac{d\omega}{dt}`$
- Units are radians per second squared (rad/s²).
- A positive angular acceleration increases the rate of rotation.
- A negative angular acceleration decreases the rate of rotation.
- Example: a spinning top slowing down due to friction has a negative angular acceleration.

## Rotational vs Linear Motion

Rotation about a single fixed axis closely parallels linear motion along a straight line. Because we restrict ourselves to one axis, the math relating angular quantities mirrors that of their linear counterparts in one dimension.

- Angular displacement ($`\theta`$) corresponds to linear displacement ($`x`$).
- Angular velocity ($`\omega`$) corresponds to linear velocity ($`v`$).
- Angular acceleration ($`\alpha`$) corresponds to linear acceleration ($`a`$).
- The relationships between these quantities follow the same patterns as linear motion.
- Graphical analysis of angular quantities versus time works just like linear motion graphs:
  
  - Slope of $`\theta`$-$`t`$ graph gives $`\omega`$.
  - Slope of $`\omega`$-$`t`$ graph gives $`\alpha`$.
  - Area under $`\omega`$-$`t`$ graph gives change in angular displacement, $`\Delta\theta`$.
  - Area under $`\alpha`$-$`t`$ graph gives change in $`\omega`$.

### Sketching θ-t, ω-t, and α-t Graphs

Sketching qualitative graphs of angular quantities is an important skill. Here is what the graphs look like for some common cases:

**Constant positive angular acceleration ($`\alpha > 0`$):**

- The $`\alpha`$-$`t`$ graph is a horizontal line above zero.
- The $`\omega`$-$`t`$ graph is a straight line with a positive slope (angular velocity increases steadily).
- The $`\theta`$-$`t`$ graph is a concave-up curve (angular position increases faster and faster).

**Constant negative angular acceleration ($`\alpha < 0`$):**

- The $`\alpha`$-$`t`$ graph is a horizontal line below zero.
- The $`\omega`$-$`t`$ graph is a straight line with a negative slope (angular velocity decreases steadily).
- The $`\theta`$-$`t`$ graph curves downward (concave down), since the rate of angular position change slows over time.

**Zero angular acceleration ($`\alpha = 0`$):**

- The $`\alpha`$-$`t`$ graph is a horizontal line along zero.
- The $`\omega`$-$`t`$ graph is a horizontal line (constant angular velocity).
- The $`\theta`$-$`t`$ graph is a straight line (angular position changes at a constant rate).

## AP Physics C Rotation Equations for Constant Angular Acceleration

When angular acceleration stays constant throughout the motion, you can use a set of equations that parallel the constant linear acceleration equations.

- $`\omega=\omega_{0}+\alpha t`$ (final angular velocity equals initial plus acceleration times time)
- $`\theta=\theta_{0}+\omega_{0}t+\frac{1}{2}\alpha t^{2}`$ (angular displacement equation)
- $`\omega^{2}=\omega_{0}^{2}+2\alpha(\theta-\theta_{0})`$ (relates angular velocity to displacement)

These equations let you solve for unknown quantities when angular acceleration is constant, just as their linear counterparts do for constant linear acceleration.

🚫 **Boundary Statement**

AP Physics C: Mechanics expects you to mathematically manipulate the magnitudes of angular displacement, velocity, and acceleration using vector conventions. However, the directions of these vectors will not be assessed on the exam. Descriptions of rotational kinematics quantities for a point or rigid body are limited to clockwise and counterclockwise with respect to a given axis of rotation.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

- List your knowns and unknowns in angular variables first, then pick the constant-$`\alpha`$ equation that contains exactly what you have plus the one thing you want.
- Watch your starting state: "at rest" means $`\omega_0 = 0`$, and "comes to rest" means final $`\omega = 0`$.
- Convert rpm to rad/s before using the kinematics equations. Multiply rpm by $`2\pi/60`$.
- When you need revolutions, solve for $`\theta`$ in radians, then divide by $`2\pi`$.

### Free Response

- For functional-dependence questions, write the symbolic equation first, then reason about how the target quantity scales when another variable doubles or halves. For example, in $`\theta = \frac{1}{2}\alpha t^2`$ with $`\omega_0 = 0`$, doubling $`t`$ makes $`\theta`$ four times larger.
- When asked to sketch, label axes and match slope and curvature to the scenario (constant slope for constant rate, concave up for speeding up).
- Justify claims by tying them to a definition or relationship, such as "since $`\omega = d\theta/dt`$, the slope of the $`\theta`$-$`t`$ graph is the angular velocity."

### Common Trap

- The constant-acceleration equations only work when $`\alpha`$ is constant. If $`\alpha`$ changes with time, go back to $`\omega = \frac{d\theta}{dt}`$ and $`\alpha = \frac{d\omega}{dt}`$ and use calculus.

## Practice Problem 1: Angular Displacement

A wheel initially at rest begins rotating with a constant angular acceleration of 3.0 rad/s². How many revolutions does the wheel make in 4.0 seconds?

**Solution**

Find the angular displacement, then convert it to revolutions.

Given:

- Initial angular velocity: $`\omega_0 = 0`$ (wheel starts from rest)
- Angular acceleration: $`\alpha = 3.0 \text{ rad/s}^2`$
- Time: $`t = 4.0 \text{ s}`$
- Initial angular position: $`\theta_0 = 0`$ (set to zero)

Using the angular displacement equation: $`\theta = \theta_0 + \omega_0t + \frac{1}{2}\alpha t^2`$ $`\theta = 0 + 0 + \frac{1}{2}(3.0)(4.0)^2`$ $`\theta = \frac{1}{2}(3.0)(16.0)`$ $`\theta = 24.0 \text{ radians}`$

To convert to revolutions, divide by $`2\pi`$ radians/revolution: $`\text{Revolutions} = \frac{24.0 \text{ rad}}{2\pi \text{ rad/rev}} = \frac{24.0}{2\pi} \approx 3.82 \text{ revolutions}`$

The wheel makes approximately 3.82 revolutions in 4.0 seconds.

## Practice Problem 2: Angular Velocity

A flywheel rotating at 120 rpm is brought to rest in 15 seconds with constant angular deceleration. What is the angular acceleration in rad/s²?

**Solution**

First, convert the initial angular velocity from rpm to rad/s.

Given:

- Initial angular velocity: $`\omega_0 = 120 \text{ rpm} = 120 \times \frac{2\pi}{60} \text{ rad/s} = 4\pi \text{ rad/s}`$
- Final angular velocity: $`\omega = 0 \text{ rad/s}`$ (wheel comes to rest)
- Time: $`t = 15 \text{ s}`$

Using the angular velocity equation: $`\omega = \omega_0 + \alpha t`$

Rearranging to solve for $`\alpha`$: $`\alpha = \frac{\omega - \omega_0}{t} = \frac{0 - 4\pi}{15} = -\frac{4\pi}{15} \text{ rad/s}^2`$

The negative sign means the angular acceleration is in the opposite direction of the initial angular velocity (a deceleration).

```math
\alpha = -\frac{4\pi}{15} \approx -0.84 \text{ rad/s}^2
```

The angular acceleration is approximately -0.84 rad/s².

## Common Misconceptions

- **Misconception:** Angular displacement is in degrees for these equations.  
  **Actually:** Angular displacement is not in degrees for these equations. Use radians, since the kinematics relationships and calculus definitions assume radians.
- **Misconception:** Angular velocity is the same as linear (tangential) speed.  
  **Actually:** Angular velocity is not the same as linear (tangential) speed. They are related by $`v = r\omega`$, but $`\omega`$ is the same for every point on a rigid system while $`v`$ depends on distance from the axis.
- **Misconception:** A negative angular acceleration always means slowing down.  
  **Actually:** A negative angular acceleration does not always mean "slowing down." It means $`\alpha`$ points opposite the chosen positive direction. The object slows only when $`\omega`$ and $`\alpha`$ have opposite signs.
- **Misconception:** Constant angular velocity means zero acceleration in every sense.  
  **Actually:** Constant angular velocity does not mean zero acceleration in every sense. A point on the rim still has centripetal (radial) acceleration even when $`\alpha = 0`$; the angular acceleration $`\alpha`$ being zero only means $`\omega`$ is not changing.
- **Misconception:** The constant-$`\alpha`$ equations are universal.  
  **Actually:** The constant-$`\alpha`$ equations are not universal. They fail the moment angular acceleration changes, so check that $`\alpha`$ is truly constant before using them.
- **Misconception:** Every point on a rigid body shares the same $`\theta`$, $`\omega`$, $`\alpha`$, arc length, and linear speed.  
  **Actually:** Every point on a rigid body shares the same $`\theta`$, $`\omega`$, and $`\alpha`$, but not the same arc length or linear speed. Do not mix up the angular quantities with the linear ones.

## Related AP Physics C: Mechanics Guides

- [5.3 Torque](03-torque.md)
- [5.4 Rotational Inertia](04-rotational-inertia.md)
- [5.5 Rotational Equilibrium and Newton's First Law in Rotational Form](05-rotational-equilibrium-and-newtons-first-law-in-rotational-form.md)
- [5.6 Newton's Second Law in Rotational Form](06-newtons-second-law-in-rotational-form.md)
- [5.2 Connecting Linear and Rotational Motion](02-connecting-linear-and-rotational-motion.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| angular acceleration | The rate of change of angular velocity with respect to time, represented by the symbol α. |
| angular displacement | The change in angular position of a rotating object, measured in radians. |
| angular velocity | The rate of change of angular position with respect to time, represented by the symbol ω. |
| axis of rotation | The fixed line about which a rigid body or system rotates. |
| constant angular acceleration | A condition in which angular velocity changes at a uniform rate over time, allowing the use of kinematic equations to relate angular displacement, angular velocity, and angular acceleration. |
| rigid system | A collection of objects or particles that maintain fixed distances from each other and rotate as a single unit. |

## Frequently Asked Questions

### What is rotational motion in AP Physics C: Mechanics?

Rotational motion describes how a rigid system changes angular position over time about an axis. In Topic 5.1, you use angular displacement, angular velocity, and angular acceleration to model that motion.

### What are the main rotational kinematics equations?

For constant angular acceleration, use ω = ω0 + αt, θ = θ0 + ω0t + 1/2αt^2, and ω^2 = ω0^2 + 2α(θ - θ0). They match the structure of the constant-acceleration equations from linear kinematics.

### What is angular displacement measured in?

Angular displacement is measured in radians. One full revolution is 2π radians, so convert revolutions or degrees to radians before using AP Physics C rotational kinematics equations.

### How are angular velocity and angular acceleration defined?

Angular velocity is the rate of change of angular position, written ω = dθ/dt. Angular acceleration is the rate of change of angular velocity, written α = dω/dt.

### How do rotation graphs work in AP Physics C?

The slope of a θ-t graph gives angular velocity, the slope of an ω-t graph gives angular acceleration, and the area under an ω-t graph gives angular displacement. These graph rules parallel linear motion graphs.

### What is the common mistake in AP Physics C rotation problems?

The common mistake is using constant-angular-acceleration equations when α is not constant. If angular acceleration changes with time, use the calculus definitions ω = dθ/dt and α = dω/dt instead.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-5/1-rotation/study-guide/0tVqvv29lj9DIxVt](https://fiveable.me/ap-physics-c-mechanics/unit-5/1-rotation/study-guide/0tVqvv29lj9DIxVt)</sub>
