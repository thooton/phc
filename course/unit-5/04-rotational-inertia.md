# 5.4 Rotational Inertia

Rotational inertia (I) measures how hard it is to change a rigid system's rotation, and it depends on both total mass and how that mass is spread out from the axis. You find it with $`I = mr^2`$ for a point mass, by summing for several masses, or by integrating $`I = \int r^2\,dm`$ for a solid, and you can shift to a parallel axis using $`I' = I_{cm} + Md^2`$. In AP Physics C: Mechanics, this topic connects mass distribution, rotational dynamics, and calculus-based derivations.

## Why This Matters for the AP Physics C: Mechanics Exam

Rotational inertia is the rotational version of mass, and it shows up across rotation problems in both the multiple-choice and free-response sections. Once you can find I for a system, you can connect it to torque and angular acceleration through $`\tau_{net} = I\alpha`$, analyze rotational energy later in the course, and reason about how spreading mass out changes how a system spins.

This topic rewards two skills the exam tests often: deriving a symbolic expression by setting up and evaluating $`\int r^2\,dm`$, and predicting how I changes when you move mass or shift the axis. Comparing scenarios (like a hoop versus a disk of the same mass and radius) is exactly the kind of functional-reasoning move that appears in qualitative-quantitative translation work.

## Key Takeaways

- Rotational inertia depends on total mass and its distribution; mass farther from the axis counts much more because of the $`r^2`$ factor.
- Use $`I = mr^2`$ for a point mass, $`I_{tot} = \sum m_i r_i^2`$ for discrete masses, and $`I = \int r^2\,dm`$ for a continuous solid.
- The same object has different I values depending on the chosen axis.
- I is smallest when the axis passes through the center of mass.
- The parallel axis theorem, $`I' = I_{cm} + Md^2`$, shifts I from a center-of-mass axis to any parallel axis a distance d away.
- Calculus derivations on the exam stay within thin rods (uniform or nonuniform) about a perpendicular axis and shells, disks, or coaxial-ring solids about a central axis.

## Rotational Inertia of Rigid Systems

### Resistance to Rotational Changes

Rotational inertia tells you how hard it is to change an object's rotational motion, just like mass tells you how hard it is to change linear motion. It depends on both the total mass and where that mass sits relative to the axis.

- Objects with mass concentrated far from the rotation axis have greater rotational inertia.
- The same object can have different rotational inertia values depending on which axis it rotates around.
- This is why it is harder to start or stop a large spinning wheel than a compact mass of the same total weight.

### Rotational Inertia Equation

For a point mass rotating around an axis, rotational inertia is:

```math
I = mr^2
```

Where:

- $`I`$ is the rotational inertia (in kg·m²)
- $`m`$ is the mass of the object
- $`r`$ is the perpendicular distance from the mass to the rotation axis

Notice the relationship is quadratic in distance. If you double r, I increases by a factor of four, so the object becomes much more resistant to angular acceleration.

### Total Rotational Inertia

For a system of several discrete objects, add up the individual contributions:

```math
I_{tot} = \sum_{i} I_i = \sum_{i} m_i r_i^2
```

This applies to any collection of masses rotating around a common axis, such as:

- A dumbbell with two masses at different distances from the axis
- A set of objects mounted at various radii on a rotating frame
- A model of atoms positioned at various distances from a rotation axis

### Rotational Inertia of Solids

Real objects are continuous distributions of mass, not point masses. To handle them, add up the contributions from infinitesimal mass elements with calculus:

```math
I = \int r^2\,dm
```

This integration:

- Divides the object into infinitesimal mass elements $`dm`$
- Multiplies each by the square of its distance $`r`$ from the axis
- Adds these contributions over the entire object

For AP Physics C: Mechanics, use $`I = \int r^2\,dm`$ to apply or derive rotational inertia for thin rods (uniform or nonuniform density) about a perpendicular axis, and for thin cylindrical shells, disks, or objects modeled as coaxial rings or shells about a central axis. Focus on how mass distribution affects I rather than memorizing many shape formulas. A hoop has more rotational inertia than a solid disk of the same mass and radius because all the hoop's mass sits at the maximum distance from the axis, while the disk's mass is spread from the center outward.

## Rotational Inertia About Non-Center Axes

A rigid system can rotate about an axis that does not pass through its center of mass. In that case, the rotational inertia depends on how far the whole mass distribution is from the chosen axis. For axes in the same plane that are parallel to an axis through the center of mass, I is smallest for the center-of-mass axis and larger for any displaced parallel axis. The relationship is given by the parallel axis theorem, $`I' = I_{cm} + Md^2`$, where $`d`$ is the perpendicular distance between the center-of-mass axis and the new axis.

### Minimum Rotational Inertia

For a rigid system in a given plane, rotational inertia is smallest when the axis passes through the center of mass. If the object rotates about any parallel axis displaced by a perpendicular distance $`d`$, then I increases according to $`I' = I_{cm} + Md^2`$. Because $`Md^2`$ is always positive for $`d > 0`$, any parallel axis not through the center of mass gives a larger rotational inertia than the center-of-mass axis.

- This minimum value marks the axis where the system is easiest to spin.
- This idea is why a spinning skater who pulls limbs in toward the center spins faster: pulling mass inward lowers rotational inertia.

### Parallel Axis Theorem

The parallel axis theorem lets you find rotational inertia about any axis parallel to one through the center of mass:

```math
I' = I_{cm} + Md^2
```

Where:

- $`I'`$ is the rotational inertia about the new axis
- $`I_{cm}`$ is the rotational inertia about the center of mass
- $`M`$ is the total mass of the object
- $`d`$ is the perpendicular distance between the two axes

This theorem is useful because:

- It removes the need to redo a full integration for each new axis.
- It shows that I grows quadratically with distance from the center of mass.
- It lets you set up rotational dynamics problems quickly in many situations.

🚫 **Scope Reminder**

On the exam, you should be able to use calculus to derive rotational inertia formulas for:

- Thin rods (uniform or nonuniform density) rotated about a perpendicular axis

- Thin cylindrical shells, disks, or objects made of coaxial rings/shells rotated about their central axis

You should also understand qualitatively how mass distribution affects rotational inertia, like why a hoop has more than a solid disk of equal mass and radius.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

- Identify the axis first. The same object has different I values for different axes, so pin down the axis before calculating.
- For discrete masses, list each mass and its perpendicular distance, then sum $`m_i r_i^2`$. Masses sitting on the axis contribute zero.
- For solids in the allowed shapes, set up $`\int r^2\,dm`$ by writing $`dm`$ in terms of a density (linear, area, or volume) and the geometry, then integrate over the correct limits.
- When an axis is off-center but parallel to a center-of-mass axis, reach for $`I' = I_{cm} + Md^2`$ instead of starting a new integral.

### Free Response

- Show your symbolic setup. When deriving I with an integral, define $`dm`$ clearly (for example $`dm = \lambda\,dx`$ for a thin rod) before you evaluate.
- Carry units through to kg·m² so your final answer is dimensionally correct.
- When asked how I changes, reason with functional dependence. Doubling a distance multiplies that contribution by four; shifting the axis adds the $`Md^2`$ term.

### Common Trap

- Do not forget that I depends on the axis, not just the object. A "disk" does not have one single rotational inertia.
- Do not apply the parallel axis theorem from an arbitrary axis. It only relates a center-of-mass axis to a parallel axis a distance d away.

## Practice Problem 1: Rotational Inertia of a Dumbbell

A dumbbell consists of two small spheres, each with mass 2.0 kg, connected by a light rod (negligible mass) of length 1.0 m. Calculate the rotational inertia of this dumbbell about an axis perpendicular to the rod and passing through (a) the center of the rod, and (b) one of the spheres.

**Solution**

For part (a), find the rotational inertia about an axis through the center:

1. Each sphere is 0.5 m from the axis of rotation.
2. Using $`I = mr^2`$ for each sphere:
   
   - $`I_1 = 2.0 \text{ kg} \times (0.5 \text{ m})^2 = 0.5 \text{ kg·m}^2`$
   - $`I_2 = 2.0 \text{ kg} \times (0.5 \text{ m})^2 = 0.5 \text{ kg·m}^2`$
3. Total: $`I_{tot} = I_1 + I_2 = 1.0 \text{ kg·m}^2`$

For part (b), find the rotational inertia about an axis through one sphere:

1. One sphere is on the axis, so its contribution is zero: $`I_1 = 2.0 \text{ kg} \times (0 \text{ m})^2 = 0`$
2. The other sphere is 1.0 m from the axis: $`I_2 = 2.0 \text{ kg} \times (1.0 \text{ m})^2 = 2.0 \text{ kg·m}^2`$
3. Total: $`I_{tot} = I_1 + I_2 = 2.0 \text{ kg·m}^2`$

## Practice Problem 2: Parallel Axis Theorem Application

A uniform solid disk has mass $`M = 5.0`$ kg and radius $`R = 0.20`$ m. This is a standard case for AP Physics C, since disks about their central axis fall within the expected scope. Find its rotational inertia about an axis that is (a) perpendicular to the disk through its center, and (b) perpendicular to the disk and tangent to its edge.

**Solution**

For part (a), find the rotational inertia about the center axis:

1. For a solid disk about its center: $`I_{cm} = \frac{1}{2}MR^2`$
2. Substituting the values: $`I_{cm} = \frac{1}{2}(5.0 \text{ kg})(0.20 \text{ m})^2 = \frac{1}{2}(5.0)(0.040) = 0.10 \text{ kg·m}^2`$

For part (b), use the parallel axis theorem:

1. The distance from the center axis to the tangent axis is $`d = R = 0.20`$ m.
2. Using $`I' = I_{cm} + Md^2`$: $`I' = 0.10 \text{ kg·m}^2 + (5.0 \text{ kg})(0.20 \text{ m})^2 = 0.10 \text{ kg·m}^2 + 0.20 \text{ kg·m}^2 = 0.30 \text{ kg·m}^2`$

## Common Misconceptions

- **Misconception:** Rotational inertia is just mass.  
  **Actually:** Rotational inertia is not just mass. Two objects with the same mass can have very different I values if the mass is spread out differently.
- **Misconception:** I is a fixed property of an object.  
  **Actually:** I is not a fixed property of an object. It changes with the chosen axis, so always state the axis.
- **Misconception:** The $`r`$ in $`I = mr^2`$ is the distance along the object or the position vector from any random point.  
  **Actually:** The $`r`$ in $`I = mr^2`$ is the perpendicular distance to the axis, not the distance along the object or the position vector from any random point.
- **Misconception:** The parallel axis theorem can be used to jump between two arbitrary axes that both miss the center of mass.  
  **Actually:** The parallel axis theorem starts from the center-of-mass axis. You cannot use it to jump between two arbitrary axes that both miss the center of mass.
- **Misconception:** A larger I means an object cannot rotate.  
  **Actually:** A larger I does not mean an object cannot rotate; it means a given torque produces a smaller angular acceleration, since $`\alpha = \tau_{net}/I`$.
- **Misconception:** Adding mass close to the axis changes I just as much as adding the same mass far out.  
  **Actually:** Adding mass close to the axis barely changes I, while the same mass far out changes it a lot, because of the $`r^2`$ weighting.

## Related AP Physics C: Mechanics Guides

- [5.1 Rotation](01-rotation.md)
- [5.3 Torque](03-torque.md)
- [5.5 Rotational Equilibrium and Newton's First Law in Rotational Form](05-rotational-equilibrium-and-newtons-first-law-in-rotational-form.md)
- [5.6 Newton's Second Law in Rotational Form](06-newtons-second-law-in-rotational-form.md)
- [5.2 Connecting Linear and Rotational Motion](02-connecting-linear-and-rotational-motion.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| axis of rotation | The fixed line about which a rigid body or system rotates. |
| center of mass | The point in a system where the entire mass can be considered to be concentrated for the purposes of analyzing motion and forces. |
| mass distribution | The spatial arrangement of mass within a system relative to a reference point or axis. |
| parallel axis theorem | A theorem that relates the rotational inertia of a rigid system about any axis to its rotational inertia about a parallel axis through its center of mass, expressed as I' = I\_cm + Md². |
| perpendicular distance | The shortest distance from a point or mass element to the axis of rotation, measured at a right angle to the axis. |
| rigid system | A collection of objects or particles that maintain fixed distances from each other and rotate as a single unit. |
| rotational inertia | A measure of an object's resistance to changes in its rotational motion about a given axis; depends on both the mass of the object and how that mass is distributed relative to the axis of rotation. |

## Frequently Asked Questions

### What is rotational inertia in AP Physics C: Mechanics?

Rotational inertia, usually written as I, measures how hard it is to change an object's rotational motion. It depends on both total mass and how far that mass is from the rotation axis.

### What is the moment of inertia formula for a point mass?

For a point mass, the rotational inertia is I = mr^2, where m is the mass and r is the perpendicular distance from the mass to the rotation axis.

### How do you calculate total rotational inertia for several masses?

For several point masses, add each contribution: I\_total = sum m\_i r\_i^2. Masses farther from the axis contribute much more because the distance is squared.

### How do you calculate rotational inertia for a continuous object?

For a continuous object, use I = integral r^2 dm. On AP Physics C: Mechanics, that means setting up dm from the object's density and geometry, then integrating over the allowed shape.

### What is the parallel axis theorem?

The parallel axis theorem is I' = I\_cm + Md^2. It shifts rotational inertia from a center-of-mass axis to a parallel axis a perpendicular distance d away.

### How is rotational inertia tested on the AP Physics C: Mechanics exam?

Expect questions that ask you to derive I with calculus, compare mass distributions, choose the correct axis, or apply the parallel axis theorem in rotational dynamics and energy problems.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-5/4-rotational-inertia/study-guide/lSrDkHqB6EviD5CA](https://fiveable.me/ap-physics-c-mechanics/unit-5/4-rotational-inertia/study-guide/lSrDkHqB6EviD5CA)</sub>
