# 5.3 Torque

## What is torque in AP Physics C: Mechanics?

Torque is the turning effect of a force, found from the part of the force that acts perpendicular to the line from the pivot to where the force is applied. You calculate it with the cross product tau = r x F, which gives both how strong the torque is (rF sin theta) and which way it points (right-hand rule). The farther the force is applied from the axis and the more perpendicular it is, the more torque you get.

## Why This Matters for the AP Physics C: Mechanics Exam

Torque is the rotational version of force, and it sets up everything later in rotational dynamics. Once you can find torque, you can analyze rotational equilibrium, apply Newton's second law in rotational form, and connect rotation to energy and momentum.

Unit 5 carries 10 to 15 percent of the exam. This topic rewards two skills the exam tests often: drawing clear force diagrams and predicting how a quantity changes when variables change. For example, you might be asked how the torque changes if the force doubles or if it is applied at half the distance. That functional-dependence reasoning shows up in both multiple-choice questions and the free-response section, including the qualitative/quantitative translation question.

## Key Takeaways

- Only the force component perpendicular to the position vector produces torque; a force aimed straight at or away from the axis gives zero torque.
- The lever arm is the perpendicular distance from the axis to the line of action of the force. A longer lever arm means more torque for the same force.
- Magnitude: tau = rF sin theta, which is the same as F times the lever arm (F times d\_perp). Units are newton-meters (N·m).
- Direction comes from the right-hand rule applied to tau = r x F. In flat 2-D problems, label torque as counterclockwise (positive) or clockwise (negative).
- Force diagrams for torque show where each force acts relative to the axis, not just its size and direction.
- Where you place the pivot is your choice, but a force acting through the pivot has zero lever arm and zero torque about that point.

## Torques on Rigid Systems

### Perpendicular Force Component

Torque comes only from the part of a force that acts perpendicular to the position vector from the axis of rotation to the point where the force is applied. This is why direction matters so much.

- The perpendicular component creates the turning effect around the axis.
- A force pointing straight along the position vector (toward or away from the axis) produces no torque.
- How well a force turns something depends on both its size and its orientation relative to the position vector.

### Lever Arm

The lever arm is the perpendicular distance from the axis of rotation to the line of action of the force. This distance largely controls how effective a force is at causing rotation.

- A longer lever arm produces more torque for the same force magnitude.
  
  - A small force at a large distance can match a large force at a small distance.
- The lever arm equals $`r \sin\theta`$, where $`r`$ is the distance from the axis to the point where the force acts and $`\theta`$ is the angle between the force and position vectors.
- Tools like long wrenches and pry bars work because a longer handle increases the lever arm.

## Describing Torques

### Force Diagrams

Force diagrams for rigid systems look a lot like free-body diagrams, but they are built to analyze torques about a chosen axis or pivot. Like free-body diagrams, they show the relative sizes and directions of the forces. The key difference is that a torque force diagram must also show where each force acts relative to the axis, because the location changes the torque a force produces.

Include these elements:

- The chosen axis of rotation or pivot point
- Each force vector with the correct direction and relative size
- The point on the system where each force is applied
- The position vector from the axis to the application point, or the lever arm for that force
- Any angles you need to find the perpendicular component of the force

A force that acts through the axis of rotation has zero lever arm, so it exerts zero torque about that axis.

### Cross-Product for Torque

The full mathematical description of torque uses the vector cross product, which gives both magnitude and direction.

The torque $`\vec{\tau}`$ on a rigid system about a chosen pivot from a force $`\vec{F}`$ is:

```math
\vec{\tau}=\vec{r} \times \vec{F}
```

Where:

- $`\vec{r}`$ is the position vector from the pivot to where the force is applied
- $`\vec{F}`$ is the applied force vector
- The magnitude is $`|\vec{\tau}| = rF\sin\theta`$, where $`\theta`$ is the angle between $`\vec{r}`$ and $`\vec{F}`$

The direction follows from cross-product rules:

- The torque vector is perpendicular to both $`\vec{r}`$ and $`\vec{F}`$, so it is normal to the plane they define.
- Use the right-hand rule: point your fingers along $`\vec{r}`$, curl them toward $`\vec{F}`$, and your thumb points along $`\vec{\tau}`$.
- In 2-D problems, torque is usually labeled clockwise (negative) or counterclockwise (positive).

Remember that the cross product is not commutative: $`\vec{r} \times \vec{F}`$ and $`\vec{F} \times \vec{r}`$ point in opposite directions, so order matters.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

- Pick your axis first. The pivot is your choice, and a smart choice can make a force vanish from the torque equation because it acts through the pivot.
- Decide whether to break the force into a perpendicular component or to use the lever arm. Both give the same answer; use whichever matches the given numbers.
- Track signs. Assign counterclockwise as positive (or the reverse) and stay consistent across every torque in the problem.
- Keep units in newton-meters and confirm angles are measured between $`\vec{r}`$ and $`\vec{F}`$.

### Free Response

- Draw a force diagram that clearly marks each force's location relative to the axis. Graders look for the application points, not just arrows.
- When asked how torque changes, use functional dependence. If $`\tau = rF\sin\theta`$ and the force doubles, the torque doubles; if the distance is halved, the torque is halved.
- Justify direction with the right-hand rule or with a clockwise/counterclockwise statement tied to your diagram.

### Common Trap

- Plugging in the full force when only the perpendicular component matters. Always check the angle between $`\vec{r}`$ and $`\vec{F}`$.

## Practice Problem 1: Calculating Torque

A wrench with a handle 30 cm long is used to loosen a bolt. If a force of 40 N is applied perpendicular to the handle, what is the magnitude of the torque about the bolt?

Solution: When the force is perpendicular to the position vector (the wrench handle here), the calculation is direct.

Given:

- Lever arm (r) = 30 cm = 0.3 m
- Force (F) = 40 N
- Angle between force and position vector (θ) = 90° (perpendicular)

Using the torque formula: $`\tau = r \times F \times \sin\theta`$ $`\tau = 0.3 \text{ m} \times 40 \text{ N} \times \sin(90°)`$ $`\tau = 0.3 \text{ m} \times 40 \text{ N} \times 1`$ $`\tau = 12 \text{ N·m}`$

Therefore, the torque applied to the bolt is 12 N·m.

## Practice Problem 2: Torque Direction and Magnitude

A 5 N force is applied at the end of a 0.5 m rod that extends horizontally to the right from a pivot at its left end. The force makes a 30° angle above the rod. Determine the magnitude and direction of the resulting torque about the pivot.

Solution:

Given:

- Position vector length (r) = 0.5 m
- Force (F) = 5 N
- Angle between the rod (the position vector) and the force is θ = 30°

The magnitude of the torque is: $`\tau = rF\sin\theta`$ $`\tau = (0.5\,\text{m})(5\,\text{N})\sin 30°`$ $`\tau = (0.5)(5)(0.5) = 1.25\,\text{N·m}`$

For the direction, point your right-hand fingers along the rod from the pivot to where the force is applied, then curl toward the force. Your thumb points out of the page, so the torque is in the +z direction. In a 2-D diagram, this is a counterclockwise (positive) torque.

## Common Misconceptions

- **Misconception:** All of a force counts toward torque.  
  **Actually:** Only the perpendicular component does. A force aimed straight at or away from the axis produces zero torque.
- **Misconception:** The lever arm is the distance to the force.  
  **Actually:** The lever arm is the perpendicular distance to the line of action, which equals $`r\sin\theta`$, not just $`r`$.
- **Misconception:** Torque has a fixed value regardless of pivot.  
  **Actually:** Torque always depends on the chosen axis, so the same force gives different torques about different points.
- **Misconception:** Torque is a scalar with no direction.  
  **Actually:** Torque is a vector; in 2-D you still need to label it clockwise or counterclockwise.
- **Misconception:** Order does not matter in the cross product.  
  **Actually:** $`\vec{r} \times \vec{F}`$ is not the same as $`\vec{F} \times \vec{r}`$; they point in opposite directions.
- **Misconception:** A bigger force always means a bigger torque.  
  **Actually:** A larger force applied closer to the axis or at a poor angle can produce less torque than a smaller, well-placed force.

## Related AP Physics C: Mechanics Guides

- [5.1 Rotation](01-rotation.md)
- [5.4 Rotational Inertia](04-rotational-inertia.md)
- [5.5 Rotational Equilibrium and Newton's First Law in Rotational Form](05-rotational-equilibrium-and-newtons-first-law-in-rotational-form.md)
- [5.6 Newton's Second Law in Rotational Form](06-newtons-second-law-in-rotational-form.md)
- [5.2 Connecting Linear and Rotational Motion](02-connecting-linear-and-rotational-motion.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| axis of rotation | The fixed line about which a rigid body or system rotates. |
| cross product | A vector operation between two vectors that produces a third vector perpendicular to both, with magnitude AB sin θ. |
| force component perpendicular | The component of a force that is perpendicular to the position vector, which is the only component that contributes to torque. |
| force diagram | A diagram that represents the forces exerted on an object or system. |
| free-body diagram | A visual representation showing all forces exerted on an object or system, with each force drawn as a vector originating from the center of mass. |
| lever arm | The perpendicular distance from the axis of rotation to the line of action of an applied force. |
| pivot point | The chosen point about which torque on a rigid system is calculated. |
| position vector | A vector denoted by r⃗ that specifies the location of a point relative to the origin. |
| right-hand rule | A method for determining the direction of a vector resulting from a cross product by orienting the fingers of the right hand in the direction of the first vector and curling them toward the second vector. |
| rigid system | A collection of objects or particles that maintain fixed distances from each other and rotate as a single unit. |
| torque | A measure of the rotational effect of a force on a rigid body, calculated as the product of the force component perpendicular to the position vector and the distance from the axis of rotation. |

## Frequently Asked Questions

### What is torque in AP Physics C: Mechanics?

Torque is the rotational effect of a force about a chosen axis. It depends on the force magnitude, where the force is applied, and the angle between the position vector and the force.

### What is the torque formula?

The vector formula for torque is tau = r x F. Its magnitude is rF sin theta, where theta is the angle between the position vector and the force.

### What is the lever arm?

The lever arm is the perpendicular distance from the axis of rotation to the line of action of the force. A larger lever arm creates more torque for the same force.

### Which part of a force produces torque?

Only the force component perpendicular to the position vector produces torque. A force directed toward or away from the axis has zero torque about that axis.

### How do you find torque direction?

Use the right-hand rule for r x F. In two-dimensional problems, you can usually state the direction as clockwise or counterclockwise after choosing a sign convention.

### How is torque tested on AP Physics C: Mechanics?

AP Physics C questions can ask you to draw force diagrams, identify torques on a rigid system, calculate tau = rF sin theta, use lever arms, determine direction, or explain how torque changes when r, F, or theta changes.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-5/3-torque/study-guide/kQhoEJrKtYjpul5K](https://fiveable.me/ap-physics-c-mechanics/unit-5/3-torque/study-guide/kQhoEJrKtYjpul5K)</sub>
