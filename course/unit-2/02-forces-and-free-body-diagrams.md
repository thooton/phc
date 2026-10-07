# 2.2 Forces and Free-Body Diagrams

A force is a push or pull interaction between two objects, and it always has both size and direction. A free-body diagram shows every force acting on a single object as straight arrows starting from a dot at the center of mass, which makes it easier to translate a physical situation into equations.

## Why This Matters for the AP Physics C: Mechanics Exam

Free-body diagrams are the starting point for almost every force problem you will see. Once you can list every force acting on an object and draw it correctly, you can apply Newton's laws, set up net force equations, and solve for acceleration, tension, friction, and more.

This skill connects directly to the translation work the exam rewards. You will be asked to move between a written scenario, a diagram, and algebra, and a clean free-body diagram is how those representations stay consistent. Drawing forces correctly also protects easy points, since the exam expects each force as a single straight arrow from the dot, never as separate components.

## Key Takeaways

- A force is always an interaction between two objects, and no object can exert a net force on itself.
- Forces are vectors, so magnitude and direction both matter, measured in newtons (N).
- A free-body diagram shows only the external forces acting on one chosen object, drawn from a dot at the center of mass.
- Each force is a single straight arrow pointing in the force's direction; same-direction forces go side by side without overlapping.
- Choose a coordinate axis parallel to the acceleration (along the incline for ramp problems) to simplify the algebra.
- Do not draw force components as separate arrows on the diagram; resolve into components only when you write equations.

## Force as an Interaction

### Forces Are Vectors

A force describes the push or pull between two objects or systems. Every force comes from an interaction, so a force exerted on an object is always due to another object or system. An object cannot exert a net force on itself.

- Forces have both magnitude and direction, so treat them as vectors.
- The SI unit of force is the newton (N).

A 10 N force pushing north is not the same as a 10 N force pushing east, even though the numbers match. Direction changes everything when you add forces together.

### Contact Forces

Contact forces happen when two objects physically touch. At the atomic level, these are macroscopic effects of interatomic electric forces, but you treat them as ordinary pushes and pulls in problems.

- Normal force ($`F_n`$) acts perpendicular to the contact surface and points away from it.
- Friction acts parallel to the contact surface.
- Tension acts along a rope, string, or cable.
- Spring forces depend on how far the spring is stretched or compressed.

The normal force is what a surface exerts to keep an object from passing through it. When you stand on the floor, the floor pushes up on you so you do not sink in.

Gravity is a noncontact force, since it acts without the objects touching. You still include it on a free-body diagram because it is a force the environment exerts on the object.

## Free-Body Diagrams

### What a Free-Body Diagram Shows

A free-body diagram is a simplified picture of every force acting on one object or system. It is the bridge between the physical setup and the equations you will write.

- Represent the object as a dot, treated as if all its mass sits at the center of mass.
- Draw each force as a vector arrow starting from that dot.
- Point each arrow in the direction the force acts.
- Make arrow lengths roughly proportional to the force sizes so the picture matches the physics.

A clear, labeled free-body diagram is usually the first and most important step in a force problem. It keeps you from forgetting a force.

### Include Only Forces from the Environment

A complete free-body diagram shows every external force the environment exerts on your chosen object. Common ones include:

- Gravitational force ($`F_g = mg`$), directed toward Earth's center.
- Normal forces from surfaces.
- Friction forces that oppose motion or impending motion.
- Tension in ropes or cables.
- Applied pushes or pulls.
- Resistive forces like air drag.

Include only forces acting on your object, not forces your object exerts on something else. Mixing those up is one of the fastest ways to set up the wrong equation.

### Drawing Rules That Earn Points

On the AP exam, individual forces must be drawn as single straight arrows that start on the dot and point in the force's direction. If two forces point the same way, draw them side by side, not on top of each other.

You are expected to depict the forces themselves, not their components. Resolve a force into components only when you move to the algebra step, never as separate arrows on the diagram.

### Choosing a Coordinate System

A smart coordinate choice cuts down on messy algebra. Line up one axis with the direction of the acceleration.

- For an object on an inclined plane, set one axis parallel to the incline surface.
- For projectile-style problems, use horizontal and vertical axes.
- For circular motion, radial and tangential axes often help.

When you align an axis with the acceleration, the acceleration lives entirely on one axis and the equations get simpler. For a block sliding down a ramp, putting the x-axis along the incline means the acceleration is purely in the x-direction.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

1. Pick your object or system, then ignore everything else.
2. List every force the environment exerts on it.
3. Draw each force as a straight arrow from a single dot.
4. Choose axes, ideally with one axis along the acceleration.
5. Only now resolve forces into components and write net force equations.

### Free Response

When a question asks for a free-body diagram, draw clean separate arrows from the dot and label each one. Do not break a force into components on the picture. If a written scenario asks you to justify a claim about motion, point back to which forces are balanced or unbalanced and in what direction.

### Common Trap

Choosing axes is for writing equations, not for the drawing. Keep weight as one full arrow straight down on the diagram, then split it into $`mg\sin\theta`$ and $`mg\cos\theta`$ only in your equations.

## Practice Problem 1: Free-Body Diagram Analysis

A 5.0 kg box sits on a horizontal surface with a coefficient of static friction μs = 0.4. A horizontal force of 15 N is applied to the box. Draw the free-body diagram for this situation and determine if the box will move.

**Solution**

First, identify all forces acting on the box:

1. Weight ($`F_g = mg`$) pointing downward
2. Normal force ($`F_n`$) pointing upward
3. Applied force ($`F_{app}`$) pointing horizontally
4. Static friction force ($`F_s`$) pointing horizontally opposite to the applied force

The free-body diagram shows these four forces as separate arrows from a central dot.

To determine if the box will move, check whether the applied force exceeds the maximum static friction:

Maximum static friction: $`F_{s,max} = μ_s \times F_n`$

Since the box is on a horizontal surface, use the AP Physics C convention $`g \approx 10 \text{ m/s}^2`$, so $`F_n = mg = 5.0 \text{ kg} \times 10 \text{ m/s}^2 = 50 \text{ N}`$.

Therefore: $`F_{s,max} = 0.4 \times 50 \text{ N} = 20 \text{ N}`$

Since the applied force (15 N) is less than the maximum static friction (20 N), the box will not move. The actual static friction force equals 15 N, exactly opposing the applied force.

## Practice Problem 2: Inclined Plane Forces

A 2.0 kg block rests on a frictionless inclined plane that makes an angle of 30° with the horizontal. Draw the free-body diagram and calculate the acceleration of the block down the plane.

**Solution**

Identify the forces acting on the block:

1. Weight ($`F_g = mg`$) pointing straight downward
2. Normal force ($`F_n`$) perpendicular to the inclined surface

The free-body diagram shows only these two forces: the weight $`F_g = mg`$ straight down and the normal force $`F_n`$ perpendicular to the surface. After drawing it, choose axes parallel and perpendicular to the incline to write the equations. In those equations, the component of weight parallel to the incline is $`mg\sin 30°`$ and the component perpendicular to the incline is $`mg\cos 30°`$.

The normal force equals the perpendicular component of weight: $`F_n = mg\cos(30°) = 2.0 \text{ kg} \times 10 \text{ m/s}^2 \times 0.866 = 17.3 \text{ N}`$

The force causing acceleration down the plane is: $`F_x = mg\sin(30°) = 2.0 \text{ kg} \times 10 \text{ m/s}^2 \times 0.5 = 10 \text{ N}`$

Using Newton's Second Law: $`a = \frac{F_x}{m} = \frac{10 \text{ N}}{2.0 \text{ kg}} = 5.0 \text{ m/s}^2`$

The block accelerates down the incline at 5.0 m/s².

## Common Misconceptions

- **Misconception:** An object can push itself forward.  
  **Actually:** No object can exert a net force on itself. Every force on your object comes from something else in the environment.
- **Misconception:** Force components belong on the free-body diagram.  
  **Actually:** On the AP exam, draw each force as one full arrow. Break it into components only when you write equations.
- **Misconception:** The normal force always equals mg.  
  **Actually:** Normal force equals the perpendicular push from a surface, which is only mg on a flat horizontal surface with no other vertical forces. On an incline it is $`mg\cos\theta`$.
- **Misconception:** Forces in the same direction can overlap on the diagram.  
  **Actually:** They must be drawn side by side as separate arrows, not stacked on top of each other.
- **Misconception:** Free-body diagrams include forces the object exerts on other things.  
  **Actually:** A free-body diagram shows only the forces the environment exerts on the one object you chose.
- **Misconception:** Static friction is always μs times the normal force.  
  **Actually:** That product is the maximum static friction. The actual static friction is only as large as needed to prevent sliding, up to that maximum.

## Related AP Physics C: Mechanics Guides

- [2.1 Properties and Interactions of a System](01-properties-and-interactions-of-a-system.md)
- [2.3 Newton's Third Law](03-newtons-third-law.md)
- [2.4 Newton's First Law](04-newtons-first-law.md)
- [2.6 Gravitational Force](06-gravitational-force.md)
- [2.7 Kinetic and Static Friction](07-kinetic-and-static-friction.md)
- [2.9 Resistive Forces](09-resistive-forces.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| center of mass | The point in a system where the entire mass can be considered to be concentrated for the purposes of analyzing motion and forces. |
| contact forces | Forces that result from two objects or systems physically touching each other, arising from interatomic electric forces. |
| coordinate system | A reference frame with axes used to describe the position and direction of forces, often aligned with the direction of acceleration to simplify analysis. |
| force | A vector quantity that describes the interaction between two objects or systems. |
| free-body diagram | A visual representation showing all forces exerted on an object or system, with each force drawn as a vector originating from the center of mass. |
| interaction | The mutual influence or action between two objects or systems that results in forces. |
| net force | The vector sum of all forces acting on an object or system. |
| vector | A quantity that has both magnitude and direction, used to represent forces on a free-body diagram. |

## Frequently Asked Questions

### What is a force in AP Physics C Mechanics?

A force is a vector interaction between two objects or systems. A force acting on an object must come from something else in the environment; an object cannot exert a net force on itself.

### What should a free-body diagram include?

A free-body diagram should include every external force acting on the chosen object or system. Draw the object as a dot and draw each force as a labeled straight arrow starting from that dot.

### Should force components be drawn on a free-body diagram?

No. On AP Physics exams, draw the full forces only. Resolve forces into components later when you write equations, not as separate arrows on the free-body diagram.

### How should same-direction forces be drawn?

If two forces point in the same direction, draw them side by side as separate arrows. Do not overlap them, because each force must be visible as its own interaction.

### How do you choose coordinate axes for a force problem?

Choose one axis parallel to the object’s acceleration when possible. For an incline, that usually means one axis parallel to the surface and one axis perpendicular to it.

### What is the most common free-body diagram mistake?

A common mistake is drawing forces the object exerts on other things instead of forces exerted on the object. The free-body diagram should show only the forces acting on the chosen object.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-2/2-forces-and-free-body-diagrams/study-guide/2LH73zRqxtRXtAKH](https://fiveable.me/ap-physics-c-mechanics/unit-2/2-forces-and-free-body-diagrams/study-guide/2LH73zRqxtRXtAKH)</sub>
