# 6.3 Angular Momentum and Angular Impulse

Angular momentum is the rotational version of linear momentum. For a rigid body spinning about a fixed axis you use $`L = I\omega`$, and for any object about a point you use $`\vec{L} = \vec{r} \times \vec{p}`$. Angular impulse connects torque over time to the change in angular momentum.

## Why This Matters for the AP Physics C: Mechanics Exam

This topic builds the rotational analogs of the momentum tools from Unit 4, so you can carry your impulse and momentum thinking into spinning systems. On both the multiple-choice and free-response sections you may need to compare angular momentum between two moments in a scenario, read torque-time and angular momentum-time graphs, or set up an integral for a time-varying torque. Free-response answers ask you to justify claims with clear reasoning, so naming the impulse-momentum theorem is not enough on its own; you have to explain the steps that connect the principle to your conclusion. This topic also sets up conservation of angular momentum in 6.4, where the same ideas explain why a system's spin stays constant when external torque is zero.

## Key Takeaways

- For a rigid system about a fixed axis, angular momentum is $`L = I\omega`$, with units of kg·m²/s.
- For any object about a chosen point, $`\vec{L} = \vec{r} \times \vec{p}`$, so the reference point you pick changes the answer.
- An object moving in a straight line still has angular momentum about a point, equal to $`rmv\sin\theta`$.
- Angular impulse is $`\int \tau \, dt`$, points in the same direction as the torque, and equals the area under a torque vs. time graph.
- The rotational impulse-momentum theorem says $`\Delta L = \int \tau \, dt`$, and it comes from $`\tau_{\text{net}} = \frac{dL}{dt}`$.
- Net torque is the slope of an angular momentum vs. time graph; angular impulse is the area under a torque vs. time graph.

## Angular Momentum of Objects

### Magnitude of Angular Momentum

Angular momentum is the rotational counterpart of linear momentum. It describes an object's tendency to keep rotating at the same rate unless an external torque changes it.

For a rigid object rotating about a fixed axis, the magnitude of angular momentum is:

```math
L = I\omega
```

Where:

- $`L`$ is the angular momentum (in kg·m²/s)
- $`I`$ is the moment of inertia (in kg·m²)
- $`\omega`$ is the angular velocity (in rad/s)

Objects with larger moments of inertia or faster spin rates have greater angular momentum. A spinning figure skater with arms extended has a larger moment of inertia, so at the same angular velocity they carry more angular momentum than when their arms are pulled in.

### Angular Momentum About a Point

When an object is not rotating about a fixed axis, you find angular momentum from the cross product of the position and linear momentum vectors:

```math
\vec{L} = \vec{r} \times \vec{p}
```

Where:

- $`\vec{L}`$ is the angular momentum vector
- $`\vec{r}`$ is the position vector from the reference point to the object
- $`\vec{p}`$ is the linear momentum vector ($`m\vec{v}`$)

The reference point you choose changes the result, so always state the point you are measuring about. For an object moving in a straight line, its angular momentum about a point depends on:

- The distance from the reference point to the object
- The object's mass
- The object's speed
- The angle between the position vector and the velocity vector

The magnitude works out to:

```math
L = rmv\sin\theta
```

where $`\theta`$ is the angle between $`\vec{r}`$ and $`\vec{v}`$. Notice that an object moving in a perfectly straight line still has nonzero angular momentum about most points, which surprises a lot of students.

## Angular Impulse from Torque

### Definition of Angular Impulse

Angular impulse measures the total effect of a torque applied over a time interval, just like linear impulse measures the effect of force over time.

```math
\text{Angular impulse} = \int \tau \, dt
```

Where:

- $`\tau`$ is the torque
- $`dt`$ is the differential time element

For constant torque, this simplifies to:

```math
\text{Angular impulse} = \tau \Delta t
```

A longer push on a merry-go-round delivers more angular impulse than a quick push with the same force.

### Direction of Angular Impulse

Angular impulse points in the same direction as the torque that creates it. In three dimensions, use the right-hand rule: curl your right-hand fingers in the direction the torque tries to twist the object and your thumb points along the angular impulse (and torque) vector. This matches the direction of the change in angular momentum, which can be opposite the current spin if the torque is slowing it down.

### Graphical Representation of Impulse

Angular impulse equals the area under a torque vs. time graph. This is the go-to method when torque changes with time:

```math
\text{Angular impulse} = \int_{t_1}^{t_2} \tau \, dt = \text{area under } \tau \text{ vs. } t \text{ curve}
```

## Change in Angular Momentum

### Magnitude of Angular Momentum Change

The change in angular momentum compares the final and initial values:

```math
\Delta L = L - L_0
```

Where:

- $`\Delta L`$ is the change in angular momentum
- $`L`$ is the final angular momentum
- $`L_0`$ is the initial angular momentum

When a spinning top slows from friction, its angular momentum decreases over time, which is a negative $`\Delta L`$ in the direction of spin.

### Impulse-Momentum Theorem for Rotation

The rotational impulse-momentum theorem connects angular impulse to the change in angular momentum:

```math
\Delta L = \int_{t_1}^{t_2} \tau \, dt
```

The angular impulse delivered to an object equals the change in its angular momentum. This comes directly from Newton's second law in rotational form:

```math
\tau_{\text{net}} = \frac{dL}{dt} = I\frac{d\omega}{dt} = I\alpha
```

When the moment of inertia stays constant, integrating both sides with respect to time gives the rotational impulse-momentum theorem.

### Torque and Angular Momentum Graphs

Two graph relationships show up often:

- Net torque equals the slope of an angular momentum vs. time graph.
- Angular impulse equals the area under a torque vs. time graph.

A steeper slope on an angular momentum-time graph means a larger net torque. A larger area under a torque-time graph means a greater change in angular momentum.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

- Decide first whether you have a rigid body about a fixed axis ($`L = I\omega`$) or a single object about a point ($`\vec{L} = \vec{r} \times \vec{p}`$). Picking the wrong form wastes time.
- For straight-line motion about a point, use $`L = rmv\sin\theta`$ and check the angle carefully. Only the perpendicular component of $`\vec{r}`$ (or of $`\vec{v}`$) contributes.
- For a time-varying torque, set up $`\Delta L = \int \tau \, dt`$ rather than trying to use $`\tau \Delta t`$, which only works for constant torque.
- Track units. Angular momentum is kg·m²/s, and angular impulse comes out in N·m·s, which is the same unit.

### Free Response

- When asked to justify a change in angular momentum, connect the steps out loud: identify the net torque, link it to $`\tau_{\text{net}} = \frac{dL}{dt}`$, then state what happens to $`L`$. Just writing "impulse-momentum theorem" will not support a stronger score.
- If a graph is given, say explicitly whether you are reading a slope (net torque) or an area (angular impulse), and label what that value represents.
- State the reference point or axis you are using. Since angular momentum depends on that choice, your reasoning needs it.

### Common Trap

- Forgetting that the angular impulse integral uses $`dt`$, while the rotational work integral from 6.2 uses $`d\theta`$. They look similar but answer different questions.

## Worked Examples

### Example 1: Angular Momentum Calculation

A 2.0 kg disk with radius 0.30 m rotates at 5.0 rad/s about an axis through its center. Calculate the angular momentum of the disk. The moment of inertia of a disk about its center is $`I = \frac{1}{2}MR^2`$.

**Solution**

Use $`L = I\omega`$.

First find the moment of inertia:

```math
I = \frac{1}{2}MR^2 = \frac{1}{2} \times 2.0 \text{ kg} \times (0.30 \text{ m})^2 = 0.09 \text{ kg·m}^2
```

Then find the angular momentum:

```math
L = I\omega = 0.09 \text{ kg·m}^2 \times 5.0 \text{ rad/s} = 0.45 \text{ kg·m}^2/\text{s}
```

The angular momentum of the disk is 0.45 kg·m²/s.

### Example 2: Angular Impulse and Change in Angular Momentum

A torque of 15 N·m is applied to a stationary wheel for 3.0 seconds. If the wheel has a moment of inertia of 2.0 kg·m², what is its final angular velocity?

**Solution**

Use the rotational impulse-momentum theorem.

First find the angular impulse:

```math
\text{Angular impulse} = \tau \Delta t = 15 \text{ N·m} \times 3.0 \text{ s} = 45 \text{ N·m·s}
```

This equals the change in angular momentum:

```math
\Delta L = L - L_0 = 45 \text{ N·m·s}
```

The wheel starts from rest, so $`L_0 = 0`$ and $`L = 45 \text{ N·m·s}`$.

Since $`L = I\omega`$:

```math
\omega = \frac{L}{I} = \frac{45 \text{ N·m·s}}{2.0 \text{ kg·m}^2} = 22.5 \text{ rad/s}
```

The wheel's final angular velocity is 22.5 rad/s.

### Example 3: Angular Momentum About a Point

A 0.5 kg ball moves with a velocity of 4.0 m/s in a straight line. At one point, the ball is 3.0 m away from an observer, with the path of the ball perpendicular to the line connecting the observer and the ball. What is the angular momentum of the ball about the observer's position?

**Solution**

For straight-line motion about a point:

```math
L = rmv\sin\theta
```

Where:

- $`r`$ is the distance from the reference point to the object
- $`m`$ is the mass of the object
- $`v`$ is the speed of the object
- $`\theta`$ is the angle between $`\vec{r}`$ and $`\vec{v}`$

The path is perpendicular to the line connecting the observer and the ball, so $`\theta = 90°`$ and $`\sin\theta = 1`$:

```math
L = rmv\sin\theta = 3.0 \text{ m} \times 0.5 \text{ kg} \times 4.0 \text{ m/s} \times 1 = 6.0 \text{ kg·m}^2/\text{s}
```

The angular momentum of the ball about the observer is 6.0 kg·m²/s.

## Common Misconceptions

- **Misconception:** Angular momentum is a single fixed number for an object.  
  **Actually:** Angular momentum is not a single fixed number for an object. It depends on the axis or reference point you choose, so $`\vec{L} = \vec{r} \times \vec{p}`$ gives different values about different points.
- **Misconception:** An object moving in a straight line has zero angular momentum everywhere.  
  **Actually:** An object moving in a straight line is not "zero angular momentum" everywhere. About a point off the line of motion, $`L = rmv\sin\theta`$ is nonzero.
- **Misconception:** $`\tau \Delta t`$ works even when torque changes.  
  **Actually:** $`\tau \Delta t`$ only works when torque is constant. For a changing torque you must integrate, $`\int \tau \, dt`$, or take the area under the torque-time graph.
- **Misconception:** The relationship $`\tau_{\text{net}} = I\alpha`$ applies even when the moment of inertia changes.  
  **Actually:** The relationship $`\tau_{\text{net}} = I\alpha`$ assumes the moment of inertia stays constant. The more general statement is $`\tau_{\text{net}} = \frac{dL}{dt}`$.
- **Misconception:** The area on a torque vs. time graph is the torque at one instant, and the slope on an angular momentum vs. time graph is the angular momentum.  
  **Actually:** On a torque vs. time graph the area is the angular impulse, not the torque value at one instant. On an angular momentum vs. time graph, the slope is the net torque, not the angular momentum.
- **Misconception:** Angular impulse and angular momentum are plain positive numbers without direction.  
  **Actually:** Angular impulse and angular momentum are vectors with direction set by the right-hand rule. Do not treat them as plain positive numbers when direction matters.

## Related AP Physics C: Mechanics Guides

- [6.4 Conservation of Angular Momentum](04-conservation-of-angular-momentum.md)
- [6.6 Motion of Orbiting Satellites](06-motion-of-orbiting-satellites.md)
- [6.1 Rotational Kinetic Energy](01-rotational-kinetic-energy.md)
- [6.2 Torque and Work](02-torque-and-work.md)
- [6.5 Kinetic Energy of a System with Translational and Rotational Motion](05-kinetic-energy-of-a-system-with-translational-and-rotational-motion.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| angular acceleration | The rate of change of angular velocity with respect to time, represented by the symbol α. |
| angular impulse | The product of net torque and the time interval over which it acts, equal to the change in angular momentum of an object or system. |
| angular momentum | A measure of the rotational motion of an object or system, calculated as the product of moment of inertia and angular velocity, or as the cross product of position vector and linear momentum. |
| angular velocity | The rate of change of angular position with respect to time, represented by the symbol ω. |
| impulse-momentum theorem | The relationship stating that the impulse exerted on an object equals its change in momentum. |
| moment of inertia | A measure of a rigid body's resistance to rotational acceleration about a given axis, represented by the symbol I. |
| momentum | A vector quantity defined as the product of an object's mass and velocity (p=mv), used to describe the motion of objects and systems. |
| Newton's second law | The principle that the net force on an object equals the product of its mass and acceleration; in rotational form, net torque equals rotational inertia times angular acceleration. |
| radial distance | The perpendicular distance from a reference point or axis to an object's position. |
| rigid system | A collection of objects or particles that maintain fixed distances from each other and rotate as a single unit. |
| rotational inertia | A measure of an object's resistance to changes in its rotational motion about a given axis; depends on both the mass of the object and how that mass is distributed relative to the axis of rotation. |
| torque | A measure of the rotational effect of a force on a rigid body, calculated as the product of the force component perpendicular to the position vector and the distance from the axis of rotation. |

## Frequently Asked Questions

### What is angular momentum in AP Physics C: Mechanics?

Angular momentum describes rotational motion. For a rigid body rotating about a fixed axis, use L = I omega. For an object about a point, use the vector relationship L = r x p.

### What determines angular momentum for an object moving in a straight line?

Angular momentum about a point depends on the reference point, the object mass, its speed, the distance from the reference point, and the angle between position and velocity.

### What is angular impulse?

Angular impulse is the torque delivered over a time interval. For variable torque, it is the integral of torque with respect to time and equals the area under a torque-versus-time graph.

### How is angular impulse related to angular momentum?

The rotational impulse-momentum theorem says angular impulse equals the change in angular momentum: Delta L equals the integral of net torque over time.

### How do torque and angular momentum graphs connect?

On an angular momentum versus time graph, net torque is the slope. On a torque versus time graph, angular impulse is the area under the curve.

### What should I show on AP Physics C angular momentum FRQs?

State the system and axis or reference point, choose the correct angular momentum expression, track directions, and connect net torque or angular impulse to the change in angular momentum.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-6/3-angular-momentum-and-angular-impulse/study-guide/3jrKVVLAakxu58LX](https://fiveable.me/ap-physics-c-mechanics/unit-6/3-angular-momentum-and-angular-impulse/study-guide/3jrKVVLAakxu58LX)</sub>
