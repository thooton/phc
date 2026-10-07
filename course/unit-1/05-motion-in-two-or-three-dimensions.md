# 1.5 Motion in Two or Three Dimensions

Motion in two or three dimensions becomes manageable when you split it into perpendicular components and apply one-dimensional kinematics to each one separately. The components are independent, but they share the same clock, so time links the x and y motions together.

## Why This Matters for the AP Physics C: Mechanics Exam

This topic builds the habit of breaking vectors into components, which you use across the entire course, from forces to momentum to orbits. On the exam, you analyze two-dimensional motion quantitatively, often by setting up position, velocity, and acceleration as separate component equations and connecting them through time. Translating between representations, like turning a verbal projectile scenario into component equations or a parabolic trajectory sketch, matches the kind of thinking tested in both the multiple-choice and free-response sections.

Note the scope boundary: AP Physics C: Mechanics expects you to analyze motion in two dimensions quantitatively. Three-dimensional motion shows up only as qualitative description in the Electricity and Magnetism course, not here.

## Key Takeaways

- Break any 2D or 3D motion into perpendicular components and treat each as its own 1D kinematics problem.
- Velocity and acceleration can differ by component and can change with time, so each component follows its own functional form.
- Perpendicular dimensions are independent: changing motion along one axis does not change motion along a perpendicular axis.
- Time is the shared variable that links the components together.
- Projectile motion is the special case with $`a_x = 0`$ and $`a_y = -g`$, producing a parabolic path.
- For a launch from ground level with no air resistance, the launch angle giving maximum range is 45 degrees.

## Component Analysis

When you analyze motion in multiple dimensions, you break vectors into components along coordinate axes. This turns a complicated path into separate, simpler problems.

- Each component is its own one-dimensional problem.
- Position, velocity, and acceleration are all vector quantities written by component.
- For AP Physics C: Mechanics, focus on two-dimensional vectors such as $`\vec{v} = v_x\hat{i} + v_y\hat{j}`$ and $`\vec{a} = a_x\hat{i} + a_y\hat{j}`$.

You can find a vector's magnitude with the Pythagorean theorem. For a two-dimensional velocity: $`|\vec{v}| = \sqrt{v_x^2 + v_y^2}`$

## Velocity and Acceleration by Component

In multi-dimensional motion, velocity and acceleration can change independently in each direction, which is what creates curved paths.

- Velocity components can change at different rates in different directions.
- An object can accelerate along one axis while keeping constant velocity along another.
- The direction of motion shifts as the velocity components change relative to each other.
- Adding the component vectors gives you the resultant velocity or acceleration.

The components do not have to be constant. An object might have $`a_x(t)`$ or $`a_y(t)`$ that changes with time, so you analyze each component using its own function of time. Projectile motion is the special case where $`a_x = 0`$ and $`a_y = -g`$ stays constant, but not all two-dimensional motion has constant component acceleration.

In uniform circular motion, for example, the speed stays constant while the direction of velocity keeps changing, which means there is a centripetal acceleration pointing toward the center of the circle.

## Independent Dimensions

One of the most useful ideas here is that perpendicular dimensions act independently.

- Changes in motion along the x-axis do not affect motion along a perpendicular y or z axis.
- Each dimension follows its own kinematic equations, for example $`v = v_0 + at`$ and $`x = x_0 + v_0t + \frac{1}{2}at^2`$.
- This independence lets you solve a complex problem by handling one direction at a time.
- Time is the common variable that links the dimensions together.

This is why a horizontally launched projectile hits the ground at the same time as an object simply dropped from the same height: their vertical motions are identical and independent of any horizontal motion.

## Projectile Motion

Projectile motion is the cleanest application of component analysis, because gravity acts in only one direction.

- Horizontal motion: constant velocity with $`a_x = 0`$ when air resistance is neglected.
- Vertical motion: constant acceleration from gravity, $`a_y = -g`$.
- Initial velocity components: $`v_{0x} = v_0\cos\theta`$ and $`v_{0y} = v_0\sin\theta`$, where $`\theta`$ is the launch angle.
- The trajectory is a parabola because horizontal velocity is constant while vertical velocity changes steadily.

Useful equations for a projectile launched and landing at the same height:

- Time of flight: $`t_{flight} = \frac{2v_0\sin\theta}{g}`$
- Range: $`R = \frac{v_0^2\sin(2\theta)}{g}`$
- Maximum height: $`h_{max} = \frac{v_0^2\sin^2\theta}{2g}`$

🚫 **Scope Note**

In AP Physics C: Mechanics, you only need to analyze motion in two dimensions quantitatively. Qualitative three-dimensional motion belongs to the Electricity and Magnetism course, not this topic.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

- Set up a clear coordinate system first, then write separate equations for x and y.
- Solve the direction you know the most about (often vertical, where $`a_y = -g`$) to find the time, then use that time in the other direction.
- Keep your sign convention consistent. If up is positive, then $`a_y = -g`$ and a downward displacement is negative.

### Free Response

- Show the component split explicitly. Graders look for $`v_{0x} = v_0\cos\theta`$ and $`v_{0y} = v_0\sin\theta`$, not just a final number.
- When acceleration depends on time, integrate each component separately to go from $`a(t)`$ to $`v(t)`$ to $`r(t)`$, and carry units the whole way.
- If asked to justify a claim like "both objects land at the same time," point to the independence of perpendicular motion rather than just plugging numbers.

### Common Trap

- Do not apply the range and time-of-flight shortcut equations when the launch and landing heights differ. Those formulas assume the projectile returns to its starting height. For uneven heights, solve the vertical equation for time directly.

## Practice Problem 1: Projectile Motion

A soccer ball is kicked with an initial velocity of 20 m/s at an angle of 30° above the horizontal from ground level. Neglecting air resistance, determine: (a) the maximum height reached by the ball, (b) the total time the ball is in the air, and (c) the horizontal distance traveled before the ball hits the ground.

**Solution**

First, break this into components:

- Initial velocity: $`v_0 = 20`$ m/s
- Launch angle: $`\theta = 30°`$
- Initial horizontal velocity: $`v_{0x} = v_0\cos\theta = 20\cos(30°) = 20 \times 0.866 = 17.32`$ m/s
- Initial vertical velocity: $`v_{0y} = v_0\sin\theta = 20\sin(30°) = 20 \times 0.5 = 10`$ m/s

(a) Maximum height: $`h_{max} = \frac{v_{0y}^2}{2g} = \frac{(10)^2}{2(9.8)} = \frac{100}{19.6} = 5.1 \text{ m}`$

(b) Time of flight: The ball returns to the ground when $`y = 0`$. Using $`y = v_{0y}t - \frac{1}{2}gt^2`$:

```math
0 = 10t - 4.9t^2
```

```math
4.9t^2 = 10t
```

```math
t(4.9t - 10) = 0
```

```math
t = 0 \quad \text{or} \quad t = \frac{10}{4.9} = 2.04 \text{ s}
```

Since $`t = 0`$ is the starting point, the total time in the air is 2.04 seconds.

(c) Horizontal distance: $`x = v_{0x} \times t = 17.32 \times 2.04 = 35.3 \text{ m}`$

## Practice Problem 2: Independent Motion in Two Dimensions

A ball rolls off a table with a horizontal speed of 3.0 m/s from a height of 1.2 m. Neglect air resistance. Find (a) the time to hit the floor and (b) the horizontal distance traveled.

**Solution**

Vertical motion sets the time: $`\Delta y = v_{0y}t + \frac{1}{2}a_yt^2`$ with $`\Delta y = -1.2\text{ m}`$, $`v_{0y}=0`$, and $`a_y=-9.8\text{ m/s}^2`$. $`-1.2 = 0 + \frac{1}{2}(-9.8)t^2`$ $`-1.2 = -4.9t^2`$ $`t^2 = \frac{1.2}{4.9} = 0.245`$ $`t = 0.495\text{ s}`$

Now use horizontal motion: $`x = v_{0x}t = (3.0)(0.495) = 1.49\text{ m}`$.

So the ball is in the air for $`0.495\text{ s}`$ and travels $`1.49\text{ m}`$ horizontally.

## Common Misconceptions

- **Misconception:** Horizontal motion affects vertical motion.  
  **Actually:** Perpendicular components are independent. A faster horizontal speed does not change how long a projectile stays in the air.
- **Misconception:** A projectile slows down because of horizontal acceleration.  
  **Actually:** With air resistance neglected, horizontal acceleration is zero, so horizontal velocity stays constant. The only acceleration is the downward $`g`$.
- **Misconception:** Acceleration is zero at the top of a projectile's path.  
  **Actually:** At the highest point the vertical velocity is zero, but the acceleration is still $`g`$ downward the entire time.
- **Misconception:** The range and time-of-flight formulas always work.  
  **Actually:** Those equations assume launch and landing at the same height. For different heights, solve the vertical kinematics equation for time instead.
- **Misconception:** Negative acceleration always means slowing down.  
  **Actually:** A negative $`a_y`$ just points downward in your chosen sign convention. A falling object can speed up while having negative acceleration.
- **Misconception:** You can add x and y components directly to get speed.  
  **Actually:** Combine perpendicular components with the Pythagorean theorem, not simple addition.

## Related AP Physics C: Mechanics Guides

- [1.1 Scalars and Vectors](01-scalars-and-vectors.md)
- [1.3 Representing Motion](03-representing-motion.md)
- [1.4 Reference Frames and Relative Motion](04-reference-frames-and-relative-motion.md)
- [1.2 Displacement, Velocity, and Acceleration](02-displacement-velocity-and-acceleration.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| acceleration | A vector quantity that describes the rate of change of an object's velocity with respect to time. |
| component | The projection of a vector along a specific direction, such as the x-, y-, or z-direction. |
| kinematic relationships | Mathematical equations that describe the relationships between position, velocity, acceleration, and time for moving objects. |
| motion in three dimensions | The movement of an object that changes position in three perpendicular directions simultaneously. |
| motion in two dimensions | The movement of an object that changes position in two perpendicular directions simultaneously. |
| projectile motion | A special case of two-dimensional motion where an object experiences zero acceleration in one dimension and constant, nonzero acceleration in the perpendicular dimension. |
| velocity | A vector quantity that describes the rate of change of an object's position with respect to time. |

## Frequently Asked Questions

### What is AP Physics C Mechanics 1.5 about?

AP Physics C: Mechanics 1.5 is about describing motion in two or three dimensions by separating vectors into perpendicular components. For Mechanics, you quantitatively analyze two-dimensional motion, especially projectile motion.

### How do you solve projectile motion problems?

Split the initial velocity into components, write separate x- and y-direction kinematics equations, and use time to connect the two directions. With no air resistance, horizontal acceleration is zero and vertical acceleration is -g if up is positive.

### What is the max height equation for projectile motion?

For a projectile launched and landing at the same height, maximum height is hmax = v0^2 sin^2(theta)/(2g). More generally, you can use vertical kinematics and set vertical velocity equal to zero at the top of the path.

### Why are horizontal and vertical motion independent?

Perpendicular components are independent because acceleration in one direction does not cause a change in a perpendicular direction. A projectile can keep constant horizontal velocity while its vertical velocity changes due to gravity. Time is the shared variable that connects both directions.

### When can I use the range equation?

The shortcut range equation R = v0^2 sin(2theta)/g assumes the projectile launches and lands at the same height with no air resistance. If the starting and ending heights differ, solve the vertical equation for time first, then use horizontal motion to find range.

### What is the AP Physics C scope for three-dimensional motion?

The CED boundary says AP Physics C: Mechanics expects quantitative analysis in two dimensions. Qualitative three-dimensional motion is part of AP Physics C: Electricity and Magnetism, so Mechanics questions focus on component methods and two-dimensional applications.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-1/5-motion-in-two-or-three-dimensions/study-guide/FnxHaY283LuHyd54](https://fiveable.me/ap-physics-c-mechanics/unit-1/5-motion-in-two-or-three-dimensions/study-guide/FnxHaY283LuHyd54)</sub>
