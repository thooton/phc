# 2.7 Kinetic and Static Friction

Friction opposes relative motion between surfaces. Kinetic friction acts when surfaces slide and has magnitude $`|\vec{F}_{f,k}| = \mu_k F_N`$, while static friction adjusts itself to prevent sliding up to a maximum of $`\mu_s F_N`$.

## Why This Matters for the AP Physics C: Mechanics Exam

Friction shows up constantly in force problems because it appears in free-body diagrams alongside gravity, normal force, tension, and applied forces. You will use it to decide whether an object stays still or accelerates, to set up Newton's second law on flat surfaces and inclines, and to interpret experimental data. Friction is also central to several later topics in this unit, including circular motion on banked curves and rolling. Being able to switch between a verbal description, a diagram, and the matching equations is exactly the kind of translation the free-response section rewards.

## Key Takeaways

- Kinetic friction acts opposite to the sliding direction and has a fixed magnitude: $`|\vec{F}_{f,k}| = \mu_k F_N`$.
- Static friction is a variable force that adjusts to prevent slipping, satisfying $`|\vec{F}_{f,s}| \le \mu_s F_N`$.
- The maximum static friction force is $`F_{f,s,max} = \mu_s F_N`$; objects start to slide once an applied force exceeds it.
- The coefficient of static friction is typically greater than the coefficient of kinetic friction for the same pair of surfaces.
- Friction does not depend on contact area; it depends on the normal force and the materials in contact.
- The normal force is not always equal to $`mg`$. On an incline of angle $`\theta`$, $`F_N = mg\cos\theta`$.

## Kinetic Friction Between Surfaces

### Relative Motion and Friction

Kinetic friction occurs when two surfaces in contact move relative to each other, like a sled sliding across snow or a book sliding across a table.

- It always acts opposite to the motion of each surface relative to the other.
- It points directly opposite the sliding direction.
- Its magnitude stays constant during sliding as long as the normal force and surfaces do not change.
- It does not depend on the contact area between the surfaces.

That last point is often surprising. A brick sliding on its narrow side experiences the same friction force as when it slides on its wide side, as long as the normal force is the same.

### Magnitude of Kinetic Friction Force

The kinetic friction force follows a direct relationship:

```math
|\vec{F}_{f,k}| = |\mu_k \vec{F}_N|
```

Where:

- $`|\vec{F}_{f,k}|`$ is the kinetic friction force (in newtons)
- $`\mu_k`$ is the coefficient of kinetic friction (dimensionless)
- $`\vec{F}_N`$ is the normal force the surface exerts on the object (in newtons)

The coefficient of kinetic friction $`\mu_k`$ depends on the material properties of the two surfaces in contact. Some approximate values:

- Rubber on concrete: $`\mu_k \approx 0.8`$ (high friction)
- Metal on metal: $`\mu_k \approx 0.2`$ (moderate friction)
- Ice on ice: $`\mu_k \approx 0.03`$ (very low friction)

The normal force is the perpendicular component of the force a surface exerts on an object in contact with it, directed away from the surface. On a horizontal surface with no vertical applied forces, it equals the object's weight ($`F_N = mg`$). On an incline of angle $`\theta`$, it becomes $`F_N = mg\cos\theta`$.

## Static Friction Between Surfaces

### Contacting Surfaces at Rest

Static friction may occur whenever two surfaces are in contact and are not moving relative to each other, even if the objects as a whole are moving together. For example, a box sitting in the bed of a truck that is accelerating forward stays in place because static friction between the box and the truck bed accelerates the box along with the truck.

Static friction is an adjustable force that matches the applied force up to its maximum value.

- Push lightly on a heavy box, and static friction pushes back with exactly the same force.
- That is why the box does not move until you push hard enough.

Unlike kinetic friction, which has a constant value during sliding, static friction changes in magnitude. It provides just enough opposition to prevent motion, adjusting to match any applied force up to its maximum.

### Prevention of Slipping or Sliding

Static friction works to keep surfaces from moving relative to each other. Slipping and sliding refer to situations in which two surfaces are moving relative to each other.

- It can change both its magnitude and direction as needed.
- It always acts parallel to the surfaces in contact.
- It can only oppose motion up to a certain maximum value.
- Once that maximum is exceeded, the surfaces begin to slip.

When you walk, static friction between your shoes and the ground keeps your feet from slipping backward. When you push a heavy bookshelf, static friction between it and the floor keeps it in place until you push hard enough.

### Static vs Kinetic Friction Coefficients

The relationship between static and kinetic friction explains why it is harder to start moving an object than to keep it moving.

- The coefficient of static friction $`\mu_s`$ is typically greater than the coefficient of kinetic friction $`\mu_k`$ for a given pair of surfaces.
- Static friction satisfies the inequality $`|\vec{F}_{f,s}| \le |\mu_s \vec{F}_N|`$.
- The maximum static friction force is $`F_{f,s,max} = \mu_s F_N`$.
- Static friction takes any value from zero up to this maximum, in whatever direction is needed to prevent slipping.
- Once motion begins, friction drops to the kinetic value.

This explains the common experience of objects breaking free and then accelerating suddenly once you push hard enough to overcome static friction.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

1. Draw a free-body diagram and find the normal force first. Remember $`F_N`$ is not always $`mg`$, especially on inclines or when a force has a vertical component.
2. Decide whether the object is sliding or not. If it slides, use $`|\vec{F}_{f,k}| = \mu_k F_N`$. If it might stay still, compare the applied force to $`F_{f,s,max} = \mu_s F_N`$.
3. If the applied force is less than $`F_{f,s,max}`$, the object stays put and static friction equals whatever is needed to keep net force zero in that direction.
4. Set up Newton's second law along axes aligned with the surface so friction stays on one axis.

### Free Response

For a qualitative-then-quantitative question, you may need to explain in words why an object stays still or starts to slide before writing any equations. Connect the idea that static friction adjusts up to a maximum to the math: the object remains at rest as long as the required friction is at or below $`\mu_s F_N`$. Then derive the symbolic expression and tie your final equation back to that verbal claim.

### Common Trap

When a friction problem involves an incline or an applied force at an angle, recompute the normal force instead of assuming $`F_N = mg`$. A wrong normal force makes every friction value wrong.

## Practice Problem 1: Kinetic Friction on a Horizontal Surface

A 5.0 kg box is sliding across a horizontal floor with a coefficient of kinetic friction $`\mu_k = 0.3`$. What is the kinetic friction force acting on the box?

**Solution**

Use $`|\vec{F}_{f,k}| = \mu_k F_N`$.

First, find the normal force. The box is on a horizontal surface, so: $`F_N = mg = 5.0 \text{ kg} \times 9.8 \text{ m/s}^2 = 49 \text{ N}`$

Now calculate the kinetic friction force: $`|\vec{F}_{f,k}| = \mu_k F_N = 0.3 \times 49 \text{ N} = 14.7 \text{ N}`$

The kinetic friction force is 14.7 N, directed opposite the box's motion.

## Practice Problem 2: Static Friction and Motion

A 10.0 kg crate rests on a horizontal floor. The coefficient of static friction between the crate and floor is $`\mu_s = 0.4`$. If you apply a horizontal force of 35 N to the crate, will it move? If not, what is the static friction force?

**Solution**

Compare the applied force with the maximum static friction force.

First, find the normal force: $`F_N = mg = 10.0 \text{ kg} \times 9.8 \text{ m/s}^2 = 98 \text{ N}`$

The maximum static friction force is: $`F_{f,s,max} = \mu_s F_N = 0.4 \times 98 \text{ N} = 39.2 \text{ N}`$

Since the applied force (35 N) is less than the maximum static friction force (39.2 N), the crate does not move.

Because the crate stays at rest, static friction exactly balances the applied force: $`F_{f,s} = 35 \text{ N}`$

This shows how static friction adjusts to match the applied force when that force is below the maximum static friction threshold.

## Common Misconceptions

- **Misconception:** Friction depends on contact area.  
  **Actually:** It does not. Friction depends on the normal force and the material properties of the surfaces, not on how much surface is touching.
- **Misconception:** The normal force always equals $`mg`$.  
  **Actually:** Only on a horizontal surface with no vertical applied forces. On an incline, $`F_N = mg\cos\theta`$, and a vertical push or pull changes it too.
- **Misconception:** Static friction always equals $`\mu_s F_N`$.  
  **Actually:** That product is only the maximum. Static friction takes whatever value is needed to prevent sliding, from zero up to that maximum.
- **Misconception:** Kinetic friction depends on speed.  
  **Actually:** In this model, kinetic friction stays the same magnitude regardless of how fast the object slides, as long as the normal force does not change.
- **Misconception:** Static and kinetic coefficients are interchangeable.  
  **Actually:** They are different values, and $`\mu_s`$ is usually larger, which is why objects resist starting to move more than they resist continued sliding.
- **Misconception:** A heavier coefficient means more force in every case.  
  **Actually:** The friction force depends on both the coefficient and the normal force, so you always need both to find the actual force.

## Related AP Physics C: Mechanics Guides

- [2.1 Properties and Interactions of a System](01-properties-and-interactions-of-a-system.md)
- [2.2 Forces and Free-Body Diagrams](02-forces-and-free-body-diagrams.md)
- [2.3 Newton's Third Law](03-newtons-third-law.md)
- [2.4 Newton's First Law](04-newtons-first-law.md)
- [2.6 Gravitational Force](06-gravitational-force.md)
- [2.9 Resistive Forces](09-resistive-forces.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| coefficient of kinetic friction | A dimensionless constant (μₖ) that represents the ratio of kinetic friction force to the normal force between two surfaces that are sliding relative to each other. |
| coefficient of static friction | A dimensionless constant (μₛ) that represents the ratio of the maximum static friction force to the normal force between two surfaces. |
| friction | A nonconservative force that opposes motion and dissipates mechanical energy. |
| kinetic friction | The friction force exerted on a system moving relative to a surface, which acts at the point of contact and dissipates energy. |
| material properties | The characteristics of materials that affect how they interact, such as surface texture and composition, which determine the coefficient of kinetic friction. |
| normal force | The contact force exerted by a surface on an object perpendicular to that surface. |
| relative motion | The motion of one surface with respect to another surface in contact with it. |
| slipping | A situation in which two surfaces in contact are moving relative to each other. |
| static friction | A friction force that acts between two surfaces in contact that are not moving relative to each other, preventing an object from slipping or sliding. |

## Frequently Asked Questions

### What is the difference between static and kinetic friction?

Static friction acts when surfaces are not sliding relative to each other and adjusts up to a maximum value. Kinetic friction acts when surfaces slide and has magnitude mu\_k times the normal force.

### What is the kinetic friction formula?

The kinetic friction force has magnitude F\_f,k = mu\_k F\_N. It points opposite the relative sliding motion between the surfaces.

### What is the maximum static friction formula?

Maximum static friction is F\_f,s,max = mu\_s F\_N. Static friction can be smaller than that value because it adjusts to whatever force is needed to prevent slipping, up to the maximum.

### Why is static friction usually greater than kinetic friction?

For a given pair of surfaces, the coefficient of static friction is typically greater than the coefficient of kinetic friction. That is why it usually takes more force to start sliding than to keep sliding.

### Does friction depend on contact area?

In the AP Physics C model, friction does not depend on the size of the contact area. It depends on the normal force and the material properties summarized by the coefficient of friction.

### How do you solve AP Physics C friction problems?

Draw a free-body diagram first, resolve forces along useful axes, calculate the normal force, then decide whether static or kinetic friction applies before writing Newton’s second law.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-2/7-kinetic-and-static-friction/study-guide/D7dia71mCcEsurUu](https://fiveable.me/ap-physics-c-mechanics/unit-2/7-kinetic-and-static-friction/study-guide/D7dia71mCcEsurUu)</sub>
