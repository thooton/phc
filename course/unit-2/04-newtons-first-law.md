# 2.4 Newton's First Law

Newton's First Law says a system keeps a constant velocity (including staying at rest) whenever the net force on it is zero, a condition called translational equilibrium. To use it, add all forces as vectors, check that they cancel in each direction, and remember that forces can balance along one axis while staying unbalanced along another. In AP Physics C: Mechanics, this topic sets up equilibrium reasoning, free-body diagrams, and inertial reference frames.

## Why This Matters for the AP Physics C: Mechanics Exam

Newton's First Law is the starting point for almost every dynamics problem you will see in AP Physics C: Mechanics. Equilibrium reasoning, where you set the net force to zero, shows up in multiple-choice questions about hanging signs, sliding blocks, and objects at constant velocity, and in free-response problems where you build equations from a free-body diagram.

This topic also supports the kind of reasoning tested in the Qualitative/Quantitative Translation question, where you make a claim, back it with physics principles, and then connect it to equations you derive. Being able to explain why an object's velocity stays constant, without immediately plugging into numbers, is exactly the skill that question rewards. The same equilibrium setup carries into later topics like friction, springs, and circular motion, so getting comfortable here pays off across the whole course.

## Key Takeaways

- Net force is the vector sum of every force acting on the system, so direction matters as much as magnitude.
- Translational equilibrium means $`\sum \vec{F}_{i}=0`$, which gives constant velocity (zero or nonzero), not necessarily "at rest."
- Forces can be balanced along one axis and unbalanced along another; velocity only changes in the direction of the unbalanced force.
- Inertia is the resistance to changes in velocity, and more mass means more inertia.
- Newton's First Law only holds in an inertial reference frame; accelerating frames need fictitious forces to make the law appear to work.
- Resolving forces into x and y components and applying $`\sum F_x = 0`$ and $`\sum F_y = 0`$ separately is the standard method for equilibrium problems.

## Conditions for Constant Velocity

### Vector Sum of Forces

Forces are vector quantities, so the net force depends on both magnitude and direction. You find the net force by adding all individual forces vectorially.

Vector addition of forces follows specific rules:

- Forces in the same direction add together.
- Forces in opposite directions subtract.
- Forces at angles require component analysis using trigonometry.

For example, if a 5 N force pushes right and a 3 N force pushes left on an object, the net force is 2 N to the right. This vector approach is how you decide whether an object will keep a constant velocity.

### Translational Equilibrium

Translational equilibrium is the configuration of forces where the net force on a system is zero, so the system has no acceleration. The system either stays at rest or keeps moving with constant velocity.

```math
\sum \vec{F}_{i}=0
```

When the vector sum of all forces equals zero, the system holds its current velocity. This applies to stationary objects (velocity = 0) and to moving objects (constant nonzero velocity).

Consider a book on a table. It stays at rest because the upward normal force from the table exactly balances the downward gravitational force, giving zero net force.

### Newton's First Law

Newton's First Law states that if the net force on a system is zero, the velocity of that system remains constant. An object at rest stays at rest, and an object in motion keeps moving with constant velocity, unless an unbalanced force acts on it.

This connects to inertia, the property that makes an object resist changes in its velocity. Objects with greater mass have greater inertia, so they need larger forces to change their motion. That is why a bowling ball is harder to start moving, and harder to stop, than a ping pong ball.

### Balanced vs Unbalanced Forces

Telling balanced and unbalanced forces apart is the core skill for applying Newton's First Law.

Balanced forces cancel out, giving zero net force. When forces are balanced, velocity stays constant, either zero (stationary) or moving in a straight line at constant speed.

Unbalanced forces produce a nonzero net force, which causes acceleration in the direction of that net force (this is Newton's Second Law, covered in the next topic).

A system can have different force balances in different directions:

- Forces can be balanced in one direction and unbalanced in another. For example, if a puck slides to the right on frictionless ice while a net force acts upward, the horizontal net force is zero and the puck keeps a constant horizontal velocity, while the upward net force changes the vertical component of velocity.
- In general, velocity changes only in the direction of the unbalanced force. In directions where the net force is zero, that component of velocity stays constant.
- A projectile in flight (neglecting air resistance) has no horizontal net force, so its horizontal velocity stays constant, while gravity provides an unbalanced downward force, so the vertical velocity changes.

### Inertial Reference Frame

An inertial reference frame is one from which an observer would verify Newton's First Law. In such a frame, objects with no net force on them move with constant velocity.

Non-inertial reference frames, such as accelerating or rotating frames, appear to break Newton's First Law. In these frames, objects seem to accelerate without any real force acting on them. To account for this, you can introduce fictitious forces, like the apparent backward push in an accelerating car, which represent the acceleration of the frame itself rather than a real interaction.

For most everyday situations, Earth is a good approximation of an inertial reference frame. For very precise measurements, Earth's rotation and orbital motion make it slightly non-inertial.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

For equilibrium problems, start with a free-body diagram, then choose axes that line up with the motion or the surface. Split each force into components and apply $`\sum F_x = 0`$ and $`\sum F_y = 0`$ separately. Solving these two equations usually gives you the unknown force or angle.

### Free Response

When a question asks you to explain why velocity stays constant, name the principle (net force is zero) before you reach for numbers. Justify your claim with the free-body diagram and the equilibrium condition, then connect that reasoning to the equations you write. This claim-then-equation flow is exactly what the Qualitative/Quantitative Translation question rewards.

### Common Trap

Constant velocity does not mean zero velocity. An object cruising at a steady speed in a straight line is in equilibrium just as much as an object sitting still. Both have $`\sum \vec{F} = 0`$.

## Practice Problem 1: Translational Equilibrium

A 50 kg crate rests on a horizontal floor. A person pushes horizontally on the crate with a force of 150 N, but the crate doesn't move. What is the magnitude of the static friction force acting on the crate, and what can you conclude about the state of the crate based on Newton's first law?

**Solution**

Since the crate remains at rest, it must be in translational equilibrium, so the net force is zero.

Looking at the horizontal forces:

- Applied force to the right: 150 N
- Static friction force to the left: ? N

For horizontal equilibrium: $`\sum F_x = 0`$ 150 N - Static friction = 0

Static friction = 150 N

Looking at vertical forces:

- Weight downward: $`mg = (50 \text{ kg})(9.8 \text{ m/s}^2) = 490 \text{ N}`$
- Normal force upward: 490 N

For vertical equilibrium: $`\sum F_y = 0`$ Normal force - Weight = 0

490 N - 490 N = 0

Conclusion: The static friction force exactly matches the applied force at 150 N, creating translational equilibrium. The crate stays at rest because the net force is zero. This shows how static friction adjusts to match the applied force up to its maximum value.

## Practice Problem 2: Inertial Reference Frames

A passenger is standing in a bus that is initially at rest. When the bus suddenly accelerates forward at 2 m/s², the passenger feels like they're being pushed backward. Explain this sensation using the concepts of inertial reference frames and Newton's first law.

**Solution**

This problem shows the difference between inertial and non-inertial reference frames.

From an inertial reference frame (someone standing on the sidewalk):

1. The bus accelerates forward at 2 m/s².
2. The passenger initially has zero velocity.
3. By Newton's first law, the passenger keeps zero velocity unless a force acts on them.
4. Friction between the passenger's feet and the bus floor accelerates the passenger forward along with the bus.
5. If that friction were absent, the passenger would appear to move backward relative to the bus, actually staying in place while the bus moves forward.

From the non-inertial reference frame (inside the accelerating bus):

1. The bus appears stationary to the passenger.
2. The passenger feels a "force" pushing them backward.
3. This apparent force is not a real interaction but a fictitious force that shows up in non-inertial reference frames.
4. Its magnitude equals the mass times the acceleration of the frame: $`F = ma = m(2 \text{ m/s}^2)`$

The backward sensation tells you the accelerating bus is a non-inertial frame. In such frames, Newton's first law appears to fail unless you introduce fictitious forces, which is why the passenger has to lean forward or hold on to stay in place.

## Common Misconceptions

- **Misconception:** Equilibrium means the object is not moving.  
  **Actually:** Equilibrium means zero net force and constant velocity. An object moving at a steady speed in a straight line is in equilibrium too.
- **Misconception:** If something is moving, there must be a net force in that direction.  
  **Actually:** Constant-velocity motion needs zero net force. A force is only required to change velocity, not to keep it.
- **Misconception:** Heavier objects fall or stop differently because gravity prefers them.  
  **Actually:** The reason heavy objects resist changes in motion is inertia, which scales with mass, not a special pull.
- **Misconception:** Fictitious forces are real pushes.  
  **Actually:** In a non-inertial frame, fictitious forces are bookkeeping terms that account for the frame's acceleration, not interactions between objects.
- **Misconception:** Balanced forces in one direction mean the object cannot accelerate at all.  
  **Actually:** Forces can cancel along one axis while staying unbalanced along another, so velocity can change in just that one direction.

## Related AP Physics C: Mechanics Guides

- [2.1 Properties and Interactions of a System](01-properties-and-interactions-of-a-system.md)
- [2.2 Forces and Free-Body Diagrams](02-forces-and-free-body-diagrams.md)
- [2.3 Newton's Third Law](03-newtons-third-law.md)
- [2.6 Gravitational Force](06-gravitational-force.md)
- [2.7 Kinetic and Static Friction](07-kinetic-and-static-friction.md)
- [2.9 Resistive Forces](09-resistive-forces.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| balanced forces | Forces acting on a system such that their vector sum equals zero in a particular dimension. |
| inertial reference frame | A reference frame in which Newton's laws of motion are valid; a frame that is either at rest or moving at constant velocity. |
| net force | The vector sum of all forces acting on an object or system. |
| translational equilibrium | The configuration of forces such that the net force exerted on a system is zero, resulting in constant velocity. |
| unbalanced forces | Forces acting on a system such that their vector sum is not zero, resulting in acceleration in that direction. |
| vector sum | The result of adding two or more vectors by combining their components. |
| velocity | A vector quantity that describes the rate of change of an object's position with respect to time. |

## Frequently Asked Questions

### What is an inertial reference frame in AP Physics C: Mechanics?

An inertial reference frame is a viewpoint where Newton's First Law works normally: if the net force on a system is zero, its velocity stays constant. In AP Physics C, that means you can use equilibrium equations like the sum of forces equals zero without adding fictitious forces.

### What is the difference between inertial and non-inertial frames?

An inertial frame is not accelerating, so objects with zero net force keep constant velocity. A non-inertial frame is accelerating or rotating, so objects may appear to accelerate even when no real interaction force causes that motion. In non-inertial frames, fictitious forces are added as a bookkeeping tool.

### What is a fictitious force or pseudo force?

A fictitious force, also called a pseudo force, is an apparent force used in an accelerating reference frame. For example, a passenger in an accelerating bus may feel pushed backward, but that backward push is not a real interaction force. It appears because the passenger is observing from a non-inertial frame.

### Does Newton's First Law mean an object has to be at rest?

No. Newton's First Law says velocity stays constant when net force is zero. That constant velocity can be zero, meaning the object is at rest, or nonzero, meaning the object moves in a straight line at constant speed.

### How do I know if forces are balanced on the AP Physics C exam?

Draw a free-body diagram, split forces into components, and check whether the force components cancel in each direction. If the net force is zero in a direction, velocity does not change in that direction. If the net force is nonzero, the object accelerates in that direction.

### What is inertia?

Inertia is an object's resistance to changes in velocity. In AP Physics C, mass is the measure of inertia: a more massive object requires a larger net force to produce the same acceleration as a less massive object.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-2/4-newtons-first-law/study-guide/t0eQsK3dx7BBjFSK](https://fiveable.me/ap-physics-c-mechanics/unit-2/4-newtons-first-law/study-guide/t0eQsK3dx7BBjFSK)</sub>
