# 1.1 Scalars and Vectors

Scalars have magnitude only, like distance, speed, mass, and energy. Vectors have both magnitude and direction, like position, displacement, velocity, acceleration, and force. In AP Physics C: Mechanics, keeping those categories straight helps you set up kinematics, force, momentum, and rotation problems without losing direction information.

## Why This Matters for the AP Physics C: Mechanics Exam

Scalars and vectors are the language for everything else in AP Physics C: Mechanics. Once you can split a vector into components and recombine them, you can handle motion in two dimensions, forces in free-body diagrams, momentum, and rotation without getting lost in directions.

This topic shows up in the multiple-choice section, where you analyze and compare representations like arrows and component expressions. It also supports the free-response section, including the question that asks you to translate between representations, since you constantly move between an arrow drawing, a magnitude and angle, and unit vector notation. Getting comfortable with vectors now saves you from sign and direction errors all year.

## Key Takeaways

- A scalar needs only magnitude; a vector needs magnitude and direction.
- Distance and speed are scalars. Position, displacement, velocity, and acceleration are vectors.
- A vector can be drawn as an arrow, written as a magnitude and direction, or written in unit vector notation: $`\vec{r} = A\hat{i} + B\hat{j} + C\hat{k}`$.
- To add vectors, add components separately: $`\vec{C} = (A_x + B_x)\hat{i} + (A_y + B_y)\hat{j}`$.
- In one dimension, opposite directions get opposite signs, so $`+5\,\text{m/s}`$ and $`-5\,\text{m/s}`$ have the same magnitude but point opposite ways.
- The magnitude of a vector comes from its components: $`|\vec{a}| = \sqrt{a_x^2 + a_y^2 + a_z^2}`$.

## Scalar and Vector Quantities

### Scalars vs Vectors

Scalars are physical quantities fully described by their magnitude alone. They are numerical values with appropriate units.

- Examples include distance, speed, mass, time, energy, and temperature.
- Scalars follow ordinary algebra for addition, subtraction, multiplication, and division.
- When you add two scalars (like 5 kg + 3 kg = 8 kg), you just combine their numerical values.

Vectors require both magnitude and direction to be fully described.

- Examples include position, displacement, velocity, acceleration, and force.
- Vectors are modeled as arrows, where the length is proportional to the magnitude and the orientation shows direction.
- Adding vectors requires techniques that account for direction, not just numbers.

### Vector Representation

The difference between scalars and vectors becomes clear when you compare related quantities.

Distance is a scalar measuring total path length. Displacement is a vector representing the straight-line change in position and its direction from start to finish.

- A car driving 5 km east, then 3 km north travels a distance of 8 km (scalar).
- The car's displacement is about 5.8 km directed northeast (vector).

Similarly, speed is a scalar measuring how fast something moves, while velocity is a vector giving both speed and direction.

In equations, vectors are written with an arrow above the symbol:

- $`\vec{v}`$ represents velocity
- $`\vec{a}`$ represents acceleration
- A vector equation like $`\vec{v} = \vec{v}_0 + \vec{a}t`$ shows relationships between vector quantities

In a one-dimensional coordinate system, opposite directions get opposite signs. If motion to the right is positive, then motion to the left is negative. A velocity of $`+5\,\text{m/s}`$ and a velocity of $`-5\,\text{m/s}`$ have the same magnitude but opposite directions.

### Examples of Scalars and Vectors

Scalar quantities include:

- Mass (5 kg)
- Time (10 seconds)
- Temperature (25°C)
- Energy (100 joules)
- Distance (400 meters)
- Speed (12 m/s)

Vector quantities include:

- Position (3 m east)
- Displacement (30 meters east)
- Velocity (20 m/s downward)
- Acceleration (9.8 m/s² toward Earth's center)
- Force (50 newtons upward)

A runner finishing a 5 km race has traveled a distance of 5 km (scalar), but their displacement (vector) depends on the path and could be much smaller if they did not run in a straight line.

### Vector Notation

Vectors can be expressed in two common ways: unit vector notation and magnitude-direction format.

Unit vector notation expresses a vector as the sum of its components along the coordinate axes:

- $`\vec{r} = (A\hat{i} + B\hat{j} + C\hat{k})`$, where $`A`$, $`B`$, and $`C`$ are scalar components
- The position vector $`\vec{r}`$ points from the origin to a specific point in space
- $`\hat{r}`$ is the unit vector in the same direction as $`\vec{r}`$

A resultant vector is the vector sum of two or more vectors. If $`\vec{C} = \vec{A} + \vec{B}`$, then the components add independently:

```math
\vec{C} = (A_x + B_x)\hat{i} + (A_y + B_y)\hat{j}
```

in two dimensions, and similarly with a $`\hat{k}`$ component in three dimensions. The x-components combine with x-components and the y-components combine with y-components to give the resultant.

You can also describe a vector by stating its magnitude and direction:

- "A force of 50 N at an angle of 30° above the horizontal"
- "A velocity of 15 m/s directed 45° south of west"

### Unit Vector Notation

The standard unit vectors in a Cartesian coordinate system are:

- $`\hat{i}`$ points along the positive x-axis
- $`\hat{j}`$ points along the positive y-axis
- $`\hat{k}`$ points along the positive z-axis

These unit vectors have important properties:

- Each has a magnitude of exactly 1 (no units)
- They are mutually perpendicular to each other
- They let you describe any vector in three-dimensional space

For example, if $`\vec{a} = 2\hat{i} - 3\hat{j} + 4\hat{k}`$, then:

- The x-component is $`a_x = 2`$
- The y-component is $`a_y = -3`$
- The z-component is $`a_z = 4`$
- The magnitude is $`|\vec{a}| = \sqrt{a_x^2 + a_y^2 + a_z^2} = \sqrt{4 + 9 + 16} = \sqrt{29}`$

Unit vectors keep vector calculations organized and give you a standard way to express any vector, no matter which physical quantity it represents.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

- To find components from a magnitude and angle, use $`r_x = r\cos\theta`$ and $`r_y = r\sin\theta`$ when the angle is measured from the positive x-axis. Check which axis your angle is referenced to before plugging in.
- To go from components back to magnitude and direction, use $`|\vec{r}| = \sqrt{r_x^2 + r_y^2}`$ and $`\theta = \tan^{-1}(r_y/r_x)`$. Watch the quadrant so your angle points the right way.
- Add or subtract vectors by components, never by adding raw magnitudes unless the vectors point the same direction.

### Free Response

- When a question asks you to translate between representations, be ready to switch between an arrow sketch, a magnitude with an angle, and unit vector notation for the same vector.
- Draw vectors as arrows with length proportional to magnitude and a clear direction. A sloppy arrow can cost you on diagram-based reasoning.

### Common Trap

- Distance and displacement are not the same, and speed and velocity are not the same. The scalar version ignores direction; the vector version does not.

## Practice Problem 1: Vector Components

A displacement vector $`\vec{r}`$ has a magnitude of 10 meters and points at an angle of 30° above the positive x-axis in the xy-plane. Express this vector in unit vector notation and calculate its components.

**Solution**

Find the x and y components.

For a vector with magnitude r = 10 m at angle θ = 30° above the x-axis:

- x-component: $`r_x = r\cos(\theta) = 10 \times \cos(30°) = 10 \times 0.866 = 8.66`$ m
- y-component: $`r_y = r\sin(\theta) = 10 \times \sin(30°) = 10 \times 0.5 = 5`$ m

In unit vector notation:

```math
\vec{r} = 8.66\hat{i} + 5\hat{j} \text{ meters}
```

## Practice Problem 2: Scalar vs Vector Quantities

A car travels 3 km east, then 4 km north, and finally 2 km east. Calculate: (a) the total distance traveled (scalar), and (b) the displacement vector (magnitude and direction) from the starting point.

**Solution**

(a) The total distance is the sum of the individual segments:

Distance = 3 km + 4 km + 2 km = 9 km

(b) For the displacement, find the resultant of all segments:

- Total eastward displacement: 3 km + 2 km = 5 km (x-component)
- Total northward displacement: 4 km (y-component)

The magnitude of the displacement vector is:

```math
|\vec{d}| = \sqrt{x^2 + y^2} = \sqrt{5^2 + 4^2} = \sqrt{25 + 16} = \sqrt{41} = 6.40 \text{ km}
```

The direction is the angle θ measured from the positive x-axis:

```math
\theta = \tan^{-1}(y/x) = \tan^{-1}(4/5) = \tan^{-1}(0.8) = 38.7°
```

So the displacement is 6.40 km at 38.7° north of east.

## Common Misconceptions

- **Misconception:** Distance and displacement are the same thing.  
  **Actually:** Distance is a scalar that adds up the whole path. Displacement is a vector from start to finish, and it can be smaller than the distance or even zero if you return to the start.
- **Misconception:** Speed and velocity mean the same thing.  
  **Actually:** Speed is a scalar; velocity includes direction. Two objects can have the same speed and different velocities if they move in different directions.
- **Misconception:** A negative sign always means slowing down.  
  **Actually:** In one dimension a negative sign just shows direction, not whether something is speeding up or slowing down.
- **Misconception:** You can add vectors by adding their magnitudes.  
  **Actually:** You add vectors by components. Adding magnitudes only works when the vectors point the same way.
- **Misconception:** Unit vectors carry units.  
  **Actually:** The unit vectors $`\hat{i}`$, $`\hat{j}`$, and $`\hat{k}`$ have a magnitude of 1 and no units; the components carry the units and the sign.
- **Misconception:** Bigger magnitude means a longer arrow regardless of scale.  
  **Actually:** Arrow length is proportional to magnitude only within a consistent scale, so compare arrows using the same scale.

## Related AP Physics C: Mechanics Guides

- [1.3 Representing Motion](03-representing-motion.md)
- [1.4 Reference Frames and Relative Motion](04-reference-frames-and-relative-motion.md)
- [1.5 Motion in Two or Three Dimensions](05-motion-in-two-or-three-dimensions.md)
- [1.2 Displacement, Velocity, and Acceleration](02-displacement-velocity-and-acceleration.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| acceleration | A vector quantity that describes the rate of change of an object's velocity with respect to time. |
| component | The projection of a vector along a specific direction, such as the x-, y-, or z-direction. |
| direction | The orientation or path along which a vector quantity acts. |
| displacement | A vector quantity representing the change in position from an initial to a final location. |
| distance | A scalar quantity representing the total length of the path traveled. |
| magnitude | The size or amount of a quantity, often represented as the length of a vector arrow. |
| position | A vector quantity that specifies the location of an object relative to a reference point. |
| position vector | A vector denoted by r⃗ that specifies the location of a point relative to the origin. |
| resultant vector | The vector sum obtained by adding the components of two or more vectors. |
| scalar | A physical quantity that has only magnitude and no direction. |
| speed | A scalar quantity representing the rate of change of distance with respect to time. |
| unit vector notation | A method of expressing vectors as the sum of their components in the x-, y-, and z-directions using unit vectors î, ĵ, and k̂. |
| vector | A quantity that has both magnitude and direction, used to represent forces on a free-body diagram. |
| vector sum | The result of adding two or more vectors by combining their components. |
| velocity | A vector quantity that describes the rate of change of an object's position with respect to time. |

## Frequently Asked Questions

### What is the difference between a scalar and a vector?

A scalar has magnitude only, while a vector has magnitude and direction. Distance, speed, mass, time, and energy are scalars. Position, displacement, velocity, acceleration, and force are vectors.

### Is velocity a scalar or vector quantity?

Velocity is a vector because it includes both speed and direction. Speed is the scalar version because it tells how fast something moves without describing direction.

### How do you find the magnitude of a vector?

Use the Pythagorean relationship for perpendicular components. In two dimensions, the magnitude is $`|\vec{a}| = \sqrt{a_x^2 + a_y^2}`$. In three dimensions, include the z-component: $`|\vec{a}| = \sqrt{a_x^2 + a_y^2 + a_z^2}`$.

### What is unit vector notation?

Unit vector notation writes a vector as components along the coordinate axes using $`\hat{i}`$, $`\hat{j}`$, and $`\hat{k}`$. For example, $`\vec{r}=A\hat{i}+B\hat{j}+C\hat{k}`$ describes x-, y-, and z-components.

### How do you add vectors by components?

Add matching components separately. If $`\vec{C}=\vec{A}+\vec{B}`$, then $`C_x=A_x+B_x`$ and $`C_y=A_y+B_y`$. This is safer than adding magnitudes unless the vectors point in the same direction.

### How do scalars and vectors show up on the AP Physics C exam?

They appear in diagrams, kinematics, force problems, momentum, and rotation. Be ready to translate between arrows, magnitude-direction descriptions, and unit vector notation while keeping signs and directions consistent.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-1/1-scalars-and-vectors/study-guide/rVQeOgdT8itcgCoV](https://fiveable.me/ap-physics-c-mechanics/unit-1/1-scalars-and-vectors/study-guide/rVQeOgdT8itcgCoV)</sub>
