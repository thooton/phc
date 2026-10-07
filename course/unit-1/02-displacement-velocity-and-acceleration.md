# 1.2 Displacement, Velocity, and Acceleration

Displacement, velocity, and acceleration describe how an object's position changes over time. In AP Physics C: Mechanics, the key calculus connection is that velocity is the derivative of position, acceleration is the derivative of velocity, and displacement can be found by integrating velocity.

Start by treating the object as a point particle when its size and shape do not matter. Then distinguish average quantities over a time interval from instantaneous quantities at one moment.

## Change in Object Position

### Object Model Simplification

In physics, we often need to analyze complex objects with many moving parts. To make this analysis manageable, we use a simplified model.

The point particle model treats complex objects as single points with properties like mass and charge, but without physical dimensions.

- This simplification ignores the object's size, shape, and internal structure
- The model places all the object's mass concentrated at a single point in space
- For rotational motion, we may need to consider the object's dimensions, but for linear motion, the point model is usually sufficient
- This simplification works well when an object's size is much smaller than the distance it travels

### Displacement Definition

Displacement measures how far out of place an object is from its starting position. Unlike distance, which measures the total path length, displacement only considers the straight-line difference between start and end points.

- Represented mathematically as: $`\Delta x = x - x_0`$ where $`x`$ is the final position and $`x_0`$ is the initial position
- Displacement is a vector quantity with both magnitude and direction
- An object that returns to its starting point has zero displacement, regardless of how far it traveled
- In multiple dimensions, displacement can be calculated using vector components: $`\Delta \vec{r} = (x - x_0)\hat{i} + (y - y_0)\hat{j} + (z - z_0)\hat{k}`$

## Average Velocity and Acceleration

### Calculation of Averages

When analyzing motion over a time interval, we often need to calculate average values rather than tracking every instantaneous change. Average calculations provide a simplified overview of an object's behavior during a specific time period.

Average values consider only the net change between the beginning and end of the interval, effectively smoothing out any variations that occurred during that time. This approach is particularly useful when detailed moment-by-moment analysis isn't necessary or when we want to characterize overall motion trends.

### Average Velocity Formula

Average velocity represents how quickly an object's position changes over a given time interval. It provides the rate of displacement, not the rate of distance traveled.

```math
\vec{v}_{\text{avg}} = \frac{\Delta \vec{x}}{\Delta t}
```

- The direction of average velocity matches the direction of displacement
- Average velocity can be zero even when an object is moving (if it returns to its starting point)
- Units are typically meters per second (m/s)
- Average velocity differs from average speed, which is the total distance divided by time

### Average Acceleration Formula

Average acceleration describes how an object's velocity changes over time. It indicates both how quickly the speed changes and how the direction of motion changes.

```math
\vec{a}_{\text{avg}} = \frac{\Delta \vec{v}}{\Delta t}
```

- Calculated by dividing the change in velocity by the time interval
- Represents the rate of velocity change in a particular direction
- Units are typically meters per second squared (m/s²)
- Can be positive (speeding up) or negative (slowing down) relative to the direction of motion

### Acceleration Conditions

Acceleration occurs whenever there is a change in an object's velocity. This change can involve the speed, direction, or both.

- An object accelerates when it speeds up or slows down (change in speed)
- An object accelerates when it changes direction, even at constant speed
- In circular motion at constant speed, acceleration is always present because the direction constantly changes
- The acceleration vector points in the direction of the velocity change, not necessarily in the direction of motion

## Instantaneous Kinematics

### Limit of Average Values

Instantaneous values tell us exactly what's happening at a specific moment in time, rather than over an interval. These values are found by taking the limit of average values as the time interval approaches zero.

- Instantaneous velocity: $`\vec{v} = \lim_{\Delta t \to 0} \frac{\Delta \vec{x}}{\Delta t} = \frac{d\vec{r}}{dt}`$
- Instantaneous acceleration: $`\vec{a} = \lim_{\Delta t \to 0} \frac{\Delta \vec{v}}{\Delta t} = \frac{d\vec{v}}{dt}`$
- These limits lead to derivatives in calculus, connecting position, velocity, and acceleration
- For component-wise analysis: $`v_x = \frac{dx}{dt}`$ and $`a_x = \frac{dv_x}{dt}`$

### Time-Dependent Functions

In many physics problems, we can express position, velocity, and acceleration as functions of time. These functions allow us to determine the state of motion at any instant.

- Position functions $`x(t)`$ describe where an object is at time $`t`$
- Velocity functions $`v(t) = \frac{dx}{dt}`$ describe how fast and in what direction an object is moving at time $`t`$
- Acceleration functions $`a(t) = \frac{dv}{dt} = \frac{d^2x}{dt^2}`$ describe how the velocity is changing at time $`t`$
- We can find displacement by integrating velocity: $`\Delta x = \int_{t_1}^{t_2} v(t) dt`$
- We can find velocity change by integrating acceleration: $`\Delta v = \int_{t_1}^{t_2} a(t) dt`$

## Practice Problem 1: Displacement Calculation

A car travels 50 meters east, then 30 meters north, and finally 20 meters west. What is the car's total displacement from its starting point?

**Solution**

To solve this problem, we need to find the net displacement vector by adding all individual displacements.

Step 1: Break down the displacements into components.

- East: 50 m in the positive x-direction: (50 m, 0 m)
- North: 30 m in the positive y-direction: (0 m, 30 m)
- West: 20 m in the negative x-direction: (-20 m, 0 m)

Step 2: Add the x-components and y-components separately.

- Net x-displacement: 50 m + 0 m + (-20 m) = 30 m
- Net y-displacement: 0 m + 30 m + 0 m = 30 m

Step 3: Find the magnitude and direction of the resultant displacement.

- Magnitude: $`|\vec{d}| = \sqrt{(30 \text{ m})^2 + (30 \text{ m})^2} = \sqrt{1800 \text{ m}^2} = 42.4 \text{ m}`$
- Direction: $`\theta = \tan^{-1}\left(\frac{30 \text{ m}}{30 \text{ m}}\right) = 45°`$ (northeast)

The car's total displacement is 42.4 meters at 45° northeast from its starting point.

## Practice Problem 2: Average and Instantaneous Velocity

A particle moves along the x-axis according to the position function $`x(t) = 3t^2 - 2t + 5`$, where $`x`$ is in meters and $`t`$ is in seconds. Find (a) the average velocity between $`t = 2`$ s and $`t = 3`$ s, and (b) the instantaneous velocity at $`t = 2`$ s.

**Solution**

(a) To find the average velocity between $`t = 2`$ s and $`t = 3`$ s:

Step 1: Calculate the positions at the given times.

- At $`t = 2`$ s: $`x(2) = 3(2)^2 - 2(2) + 5 = 3(4) - 4 + 5 = 12 - 4 + 5 = 13`$ m
- At $`t = 3`$ s: $`x(3) = 3(3)^2 - 2(3) + 5 = 3(9) - 6 + 5 = 27 - 6 + 5 = 26`$ m

Step 2: Calculate the displacement.

- $`\Delta x = x(3) - x(2) = 26 \text{ m} - 13 \text{ m} = 13 \text{ m}`$

Step 3: Calculate the time interval.

- $`\Delta t = 3 \text{ s} - 2 \text{ s} = 1 \text{ s}`$

Step 4: Calculate the average velocity.

- $`v_{avg} = \frac{\Delta x}{\Delta t} = \frac{13 \text{ m}}{1 \text{ s}} = 13 \text{ m/s}`$

(b) To find the instantaneous velocity at $`t = 2`$ s:

Step 1: Find the velocity function by differentiating the position function.

- $`v(t) = \frac{dx}{dt} = \frac{d}{dt}(3t^2 - 2t + 5) = 6t - 2`$

Step 2: Substitute $`t = 2`$ s into the velocity function.

- $`v(2) = 6(2) - 2 = 12 - 2 = 10 \text{ m/s}`$

Therefore, the average velocity between $`t = 2`$ s and $`t = 3`$ s is 13 m/s, and the instantaneous velocity at $`t = 2`$ s is 10 m/s.

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| average acceleration | The change in velocity of an object divided by the time interval over which that change occurs. |
| average value | The mean value of a quantity calculated over a time interval. |
| average velocity | The displacement of an object divided by the time interval over which that displacement occurs. |
| derivative | A mathematical operation that represents the rate of change of a function with respect to a variable. |
| differentiation | The mathematical process of finding the derivative of a function. |
| displacement | A vector quantity representing the change in position from an initial to a final location. |
| instantaneous acceleration | The acceleration of an object at a specific instant in time, calculated as the limit of average acceleration over an infinitesimally small time interval. |
| instantaneous position | The exact location of an object at a specific moment in time. |
| instantaneous velocity | The velocity of an object at a specific instant in time, calculated as the limit of average velocity over an infinitesimally small time interval. |
| integration | The mathematical process of finding the antiderivative or accumulated sum of a function. |
| object model | A simplified representation of an object where size, shape, and internal configuration are ignored, treating the object as a single point with properties such as mass and charge. |
| position | A vector quantity that specifies the location of an object relative to a reference point. |
| time-dependent functions | Mathematical functions in which the output depends on time as the independent variable. |

## Frequently Asked Questions

### What is displacement in physics?

Displacement is the change in an object's position. In one dimension, it is Delta x = x - x0, and it includes direction because it is a vector quantity.

### What is the difference between displacement and distance?

Distance is the total path length traveled, while displacement is the straight-line change from initial position to final position with direction.

### How do you find average velocity?

Average velocity is displacement divided by the time interval: v\_avg = Delta x / Delta t. It depends on net displacement, not total distance.

### What is acceleration in AP Physics C Mechanics?

Acceleration is the rate of change of velocity. An object accelerates when its speed changes, its direction changes, or both.

### How are position, velocity, and acceleration related by calculus?

Velocity is the derivative of position with respect to time, and acceleration is the derivative of velocity. Displacement can be found by integrating velocity over time.

### What is instantaneous velocity?

Instantaneous velocity is the velocity at a specific moment. It is the limit of average velocity as the time interval approaches zero, or dx/dt in one dimension.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-1/2-displacement-velocity-and-acceleration/study-guide/robnlCwaanT6NImP](https://fiveable.me/ap-physics-c-mechanics/unit-1/2-displacement-velocity-and-acceleration/study-guide/robnlCwaanT6NImP)</sub>
