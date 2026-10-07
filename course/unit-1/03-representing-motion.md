# 1.3 Representing Motion

Representing motion means describing an object's position, velocity, and acceleration using motion diagrams, graphs, equations, and word descriptions. The constant acceleration kinematic equations and motion graphs are your main tools, and graph slopes give you derivatives while areas under curves give you integrals.

## Why This Matters for the AP Physics C: Mechanics Exam

Translating between representations is a core skill in AP Physics C: Mechanics, and this topic builds the foundation for it. The free-response section includes a Translation Between Representations question, where you move between graphs, equations, diagrams, and verbal descriptions of the same motion. Reading slopes and areas off motion graphs, and connecting them to derivatives and integrals, also shows up throughout the multiple-choice section.

Getting comfortable with these representations now pays off in every later unit, since forces, energy, momentum, and rotation all build on how you describe motion.

## Key Takeaways

- Motion can be shown as motion diagrams, figures, graphs, equations, or narrative descriptions, and each gives a different view of the same motion.
- The three constant-acceleration kinematic equations connect position, velocity, acceleration, and time for one-dimensional motion.
- On a position vs time graph, the slope of the tangent line is instantaneous velocity. On a velocity vs time graph, the slope of the tangent line is instantaneous acceleration.
- The area under a velocity vs time graph is displacement, and the area under an acceleration vs time graph is the change in velocity.
- Near Earth's surface, gravity gives a constant downward acceleration of about $`g \approx 10 \mathrm{~m}/\mathrm{s}^2`$.
- Slopes connect to derivatives ($`v_x = dx/dt`$, $`a_x = dv_x/dt`$) and areas connect to integrals.

## Object Motion Representations

### Representation Methods

Motion can be represented in multiple complementary ways, each offering a different view of how objects move:

- **Visual representations** include motion diagrams (showing object positions at equal time intervals), figures (illustrating trajectories), and graphs (plotting motion variables against time)
- **Mathematical representations** use equations to precisely describe relationships between position, velocity, acceleration, and time
- **Verbal descriptions** provide narrative explanations of motion, often highlighting key events or transitions during movement

These methods work together to give you a complete picture of an object's motion. Being able to switch between them is exactly what the Translation Between Representations question asks you to do.

### Kinematic Equations

When an object moves with constant acceleration, its motion follows predictable patterns described by three equations. These connect all the key variables of motion.

The three kinematic equations for constant acceleration in one dimension are:

- $`v_{x}=v_{x0}+a_{x}t`$ This gives the velocity at any time from the initial velocity and acceleration. Velocity changes linearly with time when acceleration is constant.
- $`x=x_{0}+v_{x0}t+\frac{1}{2}a_{x}t^{2}`$ This gives the position at any time. The squared time term shows position changing non-linearly when acceleration is present.
- $`v_{x}^{2}=v_{x0}^{2}+2a_{x}(x-x_{0})`$ This relates velocity directly to position, so you can find velocity without using time. It is useful when time is not given.

These equations are written for motion along the x-axis, but they work along any single dimension by swapping in the appropriate variables (for example, y for vertical motion). They only apply when acceleration is constant.

### Gravitational Acceleration

Objects falling near Earth's surface experience a consistent acceleration:

- The acceleration due to gravity points downward toward Earth's center
- This acceleration stays nearly constant for objects near Earth's surface
- For AP Physics C calculations, use $`a_{g}=g \approx 10\mathrm{~m}/\mathrm{s}^{2}`$

This constant acceleration lets you apply the kinematic equations directly to falling objects and projectiles, using $`a_y = -g`$ when up is positive.

**Boundary Statement**

For all situations requiring a numerical value for $`g`$ on the exam, use $`g \approx 10 \mathrm{~m} / \mathrm{s}^{2}`$. You will not be penalized for correctly using the more precise commonly accepted values of $`g=9.81 \mathrm{~m} / \mathrm{s}^{2}`$ or $`g=9.8 \mathrm{~m} / \mathrm{s}^{2}`$.

### Motion Graphs

Motion graphs show how position, velocity, and acceleration change over time, and they reveal the relationships between these quantities.

Position vs time graphs show where an object is at each moment:

- The slope of a tangent line at any point equals the instantaneous velocity
- Expressed as $`v_{x}=\frac{dx}{dt}`$
- A horizontal line means the object is stationary
- A straight sloped line means constant velocity

Velocity vs time graphs show how fast an object is moving at each moment:

- The slope of a tangent line at any point equals the instantaneous acceleration, since acceleration is the rate of change of velocity
- Expressed as $`a_{x}=\frac{dv_x}{dt}`$
- A horizontal line means constant velocity (zero acceleration)
- The area under the curve between two times equals the displacement during that interval
- This area relationship is $`\Delta x=\int_{t_{1}}^{t_{2}}v_{x}(t)dt`$

Acceleration vs time graphs show how the velocity changes at each moment:

- The area under the curve between two times equals the change in velocity during that interval
- Expressed as $`\Delta v_{x}=\int_{t_{1}}^{t_{2}}a_{x}(t)dt`$
- A horizontal line means constant acceleration

These graphs link together: instantaneous velocity is the slope of the position vs time graph, $`v_x=\frac{dx}{dt}`$; instantaneous acceleration is the slope of the velocity vs time graph, $`a_x=\frac{dv_x}{dt}`$; displacement over an interval is the area under the velocity vs time graph, $`\Delta x=\int_{t_1}^{t_2} v_x(t)\,dt`$; and the change in velocity over an interval is the area under the acceleration vs time graph, $`\Delta v_x=\int_{t_1}^{t_2} a_x(t)\,dt`$.

## How to Use This on the AP Physics C: Mechanics Exam

### Free Response

The Translation Between Representations question asks you to move between graphs, equations, diagrams, and word descriptions of the same motion. Practice taking a velocity vs time graph and sketching the matching position vs time and acceleration vs time graphs, then writing the motion in words. Justify your sketches using slope and area reasoning, not just memorized shapes.

### Problem Solving

Before choosing a kinematic equation, list what you know and what you want. If time is not given and is not needed, $`v_{x}^{2}=v_{x0}^{2}+2a_{x}(x-x_{0})`$ often saves a step. Always confirm acceleration is constant before using these three equations.

### Common Trap

When a problem gives you a graph instead of an equation, decide whether you need a slope (a rate of change) or an area (an accumulated quantity). Slope gives velocity from a position graph or acceleration from a velocity graph. Area gives displacement from a velocity graph or change in velocity from an acceleration graph.

## Practice Problem 1: Kinematic Equations

A car accelerates uniformly from rest at 3.0 m/s² for 8.0 seconds. How far does the car travel during this time?

**Solution**: Since the car starts from rest, the initial velocity is $`v_{x0} = 0`$ m/s. To find displacement, use the position equation:

```math
x = x_0 + v_{x0}t + \frac{1}{2}a_x t^2
```

Set the initial position $`x_0 = 0`$ for simplicity:

```math
x = 0 + 0 \times 8.0 + \frac{1}{2} \times 3.0 \times (8.0)^2
```

```math
x = \frac{1}{2} \times 3.0 \times 64
```

$`x = 96`$ meters

The car travels 96 meters during the 8.0 seconds of acceleration.

## Practice Problem 2: Motion Graphs

A velocity-time graph shows a line with a slope of -2.0 m/s² starting from 15 m/s at t = 0 s. At what time will the object come to a stop?

**Solution**: The slope of the velocity vs time graph is the acceleration, which is constant at -2.0 m/s². The initial velocity is 15 m/s.

The object stops when velocity equals zero. Use the velocity equation:

```math
v_x = v_{x0} + a_x t
```

Substitute the given values: $`0 = 15 + (-2.0)t`$

Solve for t: $`2.0t = 15`$ $`t = 7.5`$ seconds

The object comes to a stop 7.5 seconds after it begins slowing down.

## Practice Problem 3: Gravitational Acceleration

A stone is thrown vertically upward with an initial velocity of 20 m/s. How high will it go before it begins to fall back down?

**Solution**: At the maximum height, the vertical velocity is zero. Use the third kinematic equation to find the height without needing the time:

```math
v_y^2 = v_{y0}^2 + 2a_y(y - y_0)
```

At the highest point, $`v_y = 0`$ m/s. The initial velocity $`v_{y0} = 20`$ m/s, and the acceleration is $`a_y = -g = -10`$ m/s². Set $`y_0 = 0`$ as the starting position:

```math
0^2 = 20^2 + 2(-10)(y - 0)
```

```math
0 = 400 - 20y
```

$`20y = 400`$ $`y = 20`$ meters

The stone reaches a maximum height of 20 meters before falling back down.

## Common Misconceptions

- **Misconception:** A negative acceleration always means an object is slowing down.  
  **Actually:** A negative acceleration does not always mean an object is slowing down. If velocity and acceleration point the same direction, the object speeds up. An object slows down only when velocity and acceleration point in opposite directions.
- **Misconception:** The slope of a position vs time graph is acceleration.  
  **Actually:** The slope of a position vs time graph is velocity, not acceleration. Acceleration comes from the slope of the velocity vs time graph.
- **Misconception:** The area under a velocity vs time graph is velocity.  
  **Actually:** The area under a velocity vs time graph is displacement, not velocity. The value on the curve is velocity; the area is an accumulated quantity.
- **Misconception:** The three kinematic equations work when acceleration is changing.  
  **Actually:** The three kinematic equations only work when acceleration is constant. For changing acceleration, go back to derivatives and integrals.
- **Misconception:** A steep position vs time graph means high acceleration.  
  **Actually:** A steep position vs time graph means high speed, not high acceleration. Steepness is slope, which is velocity.
- **Misconception:** An object with zero velocity has zero acceleration.  
  **Actually:** An object can have zero velocity and nonzero acceleration at the same moment, like the stone at the top of its path, where velocity is zero but gravity still acts.

## Related AP Physics C: Mechanics Guides

- [1.1 Scalars and Vectors](01-scalars-and-vectors.md)
- [1.4 Reference Frames and Relative Motion](04-reference-frames-and-relative-motion.md)
- [1.5 Motion in Two or Three Dimensions](05-motion-in-two-or-three-dimensions.md)
- [1.2 Displacement, Velocity, and Acceleration](02-displacement-velocity-and-acceleration.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| acceleration | A vector quantity that describes the rate of change of an object's velocity with respect to time. |
| constant acceleration | Motion in which an object's acceleration remains unchanged over time. |
| displacement | A vector quantity representing the change in position from an initial to a final location. |
| gravitational acceleration | The constant downward acceleration experienced by objects near Earth's surface due to gravity, approximately 10 m/s². |
| instantaneous acceleration | The acceleration of an object at a specific instant in time, calculated as the limit of average acceleration over an infinitesimally small time interval. |
| instantaneous velocity | The velocity of an object at a specific instant in time, calculated as the limit of average velocity over an infinitesimally small time interval. |
| kinematic equations | Mathematical equations that describe the motion of an object under constant acceleration in one dimension. |
| motion diagrams | Visual representations showing an object's position at successive time intervals to illustrate its motion. |
| position | A vector quantity that specifies the location of an object relative to a reference point. |
| velocity | A vector quantity that describes the rate of change of an object's position with respect to time. |

## Frequently Asked Questions

### What does representing motion mean in AP Physics C Mechanics?

Representing motion means describing position, velocity, and acceleration using graphs, equations, diagrams, figures, and words. The exam often asks you to translate between these representations.

### Which kinematic equations are used for constant acceleration?

For one-dimensional constant acceleration, use vx = vx0 + axt, x = x0 + vx0t + (1/2)axt², and vx² = vx0² + 2ax(x - x0). These equations only apply when acceleration is constant.

### What does the slope of a position-time graph represent?

The slope of a position-time graph gives instantaneous velocity. A steeper slope means a larger speed, and a horizontal slope means the object is momentarily at rest.

### What does the area under a velocity-time graph represent?

The area under a velocity-time graph over an interval gives displacement. In calculus terms, Δx = ∫v(t)dt over that time interval.

### What value of g should I use on AP Physics C?

Use g ≈ 10 m/s² when a numerical value is needed, unless the problem gives a different value. Correct use of 9.8 or 9.81 m/s² is also accepted, but the CED convention is 10 m/s².

### How is representing motion tested on AP Physics C?

You may need to sketch matching position, velocity, and acceleration graphs, use derivatives and integrals, or choose a constant-acceleration equation that fits the known variables.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-1/3-representing-motion/study-guide/ZIECLULiWCrBlX16](https://fiveable.me/ap-physics-c-mechanics/unit-1/3-representing-motion/study-guide/ZIECLULiWCrBlX16)</sub>
