# 5.6 Newton's Second Law in Rotational Form

## Newton's Second Law in Rotational Form

Newton's second law in rotational form is $`\sum \tau = I\alpha`$. Net torque changes angular velocity the same way net force changes linear velocity: if the net torque on a rigid system is not zero, the system has angular acceleration.

Use this relationship when a problem asks how torque, rotational inertia, and angular acceleration connect. For rolling or translating systems, you may also need a separate linear equation, $`\sum F = Ma_{\text{cm}}`$, plus a rolling condition such as $`a_{\text{cm}} = \alpha R`$.

## Torque and Angular Acceleration

### Net Torque and Rotational Inertia

Newton's Second Law for rotational motion establishes a fundamental relationship between torque, rotational inertia, and angular acceleration, similar to how force relates to mass and linear acceleration in linear motion.

```math
\sum \tau = I \alpha
```

An object or system's angular velocity changes only when the net torque is not zero. If $`\tau_{\text{net}}=0`$, then $`\alpha=0`$, so the angular velocity remains constant (which may be zero or nonzero).

This equation states that the net torque (Στ) acting on an object equals the product of its rotational inertia (I) and angular acceleration (α). The rate at which the angular velocity of a rigid system changes is directly proportional to the net torque and is in the same direction. The angular acceleration is inversely proportional to the rotational inertia of the system:

```math
\alpha_{\text{sys}} = \frac{\Sigma \tau}{I_{\text{sys}}} = \frac{\tau_{\text{net}}}{I_{\text{sys}}}
```

This relationship allows us to predict how objects will rotate when subjected to various torques.

- Rotational inertia (I) quantifies an object's resistance to changes in rotational motion, analogous to how mass resists changes in linear motion
- Unlike mass, rotational inertia depends not only on the amount of mass but also on how that mass is distributed relative to the axis of rotation
- Torque (τ) is the rotational equivalent of force, causing angular acceleration just as force causes linear acceleration

### Direction of Angular Acceleration

The relationship between torque and angular acceleration includes directional components that follow the right-hand rule for rotational quantities.

- Net torque and angular acceleration vectors always point in the same direction
- Counterclockwise torques (positive by convention in 2D problems) produce counterclockwise angular accelerations
- Clockwise torques (negative by convention in 2D problems) result in clockwise angular accelerations
- For complex situations with multiple torques, determine the net torque by vector addition before calculating angular acceleration

### Linear and Rotational Analyses Together

To fully describe a rotating rigid system, you may need both a linear analysis of the center of mass and a rotational analysis about the center of mass or another axis. These are related but separate ideas: $`\sum F = Ma_{\text{cm}}`$ describes translational motion, and $`\sum \tau = I\alpha`$ describes rotational motion. In rolling problems, both equations are often needed, along with the no-slip condition $`a_{\text{cm}} = \alpha R`$.

### Mass Distribution Effects

The distribution of mass in an object significantly impacts its rotational inertia and consequently its rotational dynamics.

Rotational inertia depends on the distance of mass elements from the axis of rotation, with the mathematical relationship:

- For discrete masses: $`I = \sum m_i r_i^2`$
- For continuous mass distributions: $`I = \int r^2 dm`$

This distance dependence creates several important effects:

- Objects with mass concentrated farther from the axis have greater rotational inertia
- A hollow cylinder resists angular acceleration more than a solid cylinder of equal mass because its mass is distributed farther from the center
- Figure skaters exploit this principle by pulling their arms close to their body to reduce rotational inertia and spin faster
- The same torque applied to objects with different mass distributions will produce different angular accelerations

**Boundary Statement**

The AP Physics C: Mechanics exam does not require analyzing rotation in multiple planes simultaneously.

## Practice Problem 1: Torque and Angular Acceleration

A uniform solid disk with mass 2.0 kg and radius 0.15 m is free to rotate about its center. A constant force of 3.0 N is applied tangentially at the rim of the disk. Calculate the angular acceleration of the disk.

**Solution**

To solve this problem, we need to find the torque applied to the disk and its rotational inertia, then apply Newton's Second Law in rotational form.

Step 1: Calculate the torque applied to the disk. The torque is the product of the force and the perpendicular distance from the axis of rotation: $`\tau = F \times r = 3.0 \text{ N} \times 0.15 \text{ m} = 0.45 \text{ N·m}`$

Step 2: Calculate the rotational inertia of the solid disk. For a uniform solid disk rotating about its center, the rotational inertia is: $`I = \frac{1}{2}MR^2 = \frac{1}{2} \times 2.0 \text{ kg} \times (0.15 \text{ m})^2 = 0.0225 \text{ kg·m}^2`$

Step 3: Apply Newton's Second Law in rotational form to find the angular acceleration. $`\alpha = \frac{\tau}{I} = \frac{0.45 \text{ N·m}}{0.0225 \text{ kg·m}^2} = 20 \text{ rad/s}^2`$

Therefore, the disk experiences an angular acceleration of 20 rad/s².

## Practice Problem 2: Mass Distribution Effects

A solid cylinder and a hollow cylinder (thin-walled hoop) have the same mass M and radius R. Both are released from rest at the top of an inclined plane and roll without slipping. Which one reaches the bottom first, and why?

**Solution**

To determine which cylinder reaches the bottom first, we need to compare their accelerations, which depend on their rotational inertias. Since these objects both translate and rotate, we need to use both linear and rotational analyses.

Step 1: Identify the rotational inertias of both objects.

- Solid cylinder: $`I_{\text{solid}} = \frac{1}{2}MR^2`$
- Hollow cylinder (hoop): $`I_{\text{hollow}} = MR^2`$

Step 2: For an object rolling down an incline without slipping, it is usually easiest to find the linear acceleration first: $`a = \frac{mg\sin\theta}{M + I/R^2}`$ Then use the rolling condition $`a = \alpha R`$ to get angular acceleration.

Step 3: Substitute the rotational inertias and simplify.

- For the solid cylinder:

$`a_{\text{solid}} = \frac{mg\sin\theta}{M + (\frac{1}{2}MR^2)/R^2} = \frac{mg\sin\theta}{M + \frac{1}{2}M} = \frac{2}{3}g\sin\theta`$ so $`\alpha_{\text{solid}} = \frac{a_{\text{solid}}}{R} = \frac{2g\sin\theta}{3R}`$

- For the hollow cylinder (hoop):

$`a_{\text{hollow}} = \frac{mg\sin\theta}{M + MR^2/R^2} = \frac{mg\sin\theta}{2M} = \frac{1}{2}g\sin\theta`$ so $`\alpha_{\text{hollow}} = \frac{a_{\text{hollow}}}{R} = \frac{g\sin\theta}{2R}`$

Since $`\frac{2}{3}g\sin\theta > \frac{1}{2}g\sin\theta`$, the solid cylinder has the greater linear acceleration and reaches the bottom first. It also has the greater angular acceleration because $`\alpha = a/R`$. This demonstrates how mass distribution affects rotational dynamics - the solid cylinder has more mass concentrated closer to the axis of rotation, giving it a smaller rotational inertia relative to its mass, allowing it to accelerate more quickly.

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| angular acceleration | The rate of change of angular velocity with respect to time, represented by the symbol α. |
| angular velocity | The rate of change of angular position with respect to time, represented by the symbol ω. |
| net torque | The vector sum of all torques acting on an object or system, which causes changes in angular motion. |
| rigid system | A collection of objects or particles that maintain fixed distances from each other and rotate as a single unit. |
| rotational inertia | A measure of an object's resistance to changes in its rotational motion about a given axis; depends on both the mass of the object and how that mass is distributed relative to the axis of rotation. |

## Frequently Asked Questions

### What is Newton's second law in rotational form?

Newton's second law in rotational form is sum tau = I alpha. Net torque equals rotational inertia times angular acceleration.

### What is the rotational analogue of F = ma?

The rotational analogue of F = ma is tau\_net = I alpha, where torque plays the role of force, rotational inertia plays the role of mass, and angular acceleration plays the role of linear acceleration.

### When does angular velocity change?

A system's angular velocity changes when the net torque on the system is not zero. If net torque is zero, angular acceleration is zero.

### What is moment of inertia?

Moment of inertia, or rotational inertia, measures how strongly an object resists changes in rotational motion. It depends on both mass and how far that mass is from the axis.

### How do you calculate net torque?

Net torque is the sum of all torques about the chosen axis. For a force applied perpendicular to a lever arm, torque magnitude is tau = rF.

### Why do rolling problems need both linear and rotational analysis?

A rolling object both translates and rotates, so you often need sum F = Ma\_cm, sum tau = I alpha, and the no-slip relationship a\_cm = alpha R.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-5/6-newtons-second-law-in-rotational-form/study-guide/VuXCF8dn0RYwBEaK](https://fiveable.me/ap-physics-c-mechanics/unit-5/6-newtons-second-law-in-rotational-form/study-guide/VuXCF8dn0RYwBEaK)</sub>
