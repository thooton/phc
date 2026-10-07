# 3.4 Conservation of Energy

## TLDR

Conservation of energy says energy can change form or move between objects, but the total never disappears. In AP Physics C: Mechanics, you use this to track kinetic and potential energy and solve for speeds, heights, or spring compressions without analyzing every force directly. The key skill is choosing your system wisely, because that choice decides whether mechanical energy stays constant or changes.

## Why This Matters for the AP Physics C: Mechanics Exam

This topic gives you a second toolbox alongside force analysis. When a problem gives you positions and speeds at two points but no clean way to track forces over time, energy methods usually get you to the answer faster.

The first free-response question, the Mathematical Routines question, rewards exactly this kind of thinking. You may need to derive a symbolic expression, build or use a representation like an energy bar chart, and then write a clear, organized explanation that cites physical principles. Energy conservation is a natural fit because it connects equations to a single bookkeeping idea. These methods also carry into later units, including momentum, rotation, gravitation, and oscillations, where you reuse the same conservation logic with new energy terms.

## Key Takeaways

- Mechanical energy is the sum of kinetic and potential energy: $`E = K + U`$.
- A single-object system can only have kinetic energy. Potential energy belongs to systems of interacting objects or to systems that change shape reversibly.
- Energy is conserved in every interaction. Any drop in one energy type shows up as a rise in another type or as a transfer across the system boundary.
- If the work done on your chosen system is zero and there are no nonconservative interactions inside it, total mechanical energy stays constant.
- If nonzero work is done on the system, the change in the system's energy equals the energy transferred in or out.
- Nonconservative forces like friction and air resistance dissipate mechanical energy as thermal energy or sound.

## System Energies

### Single Object Kinetic Energy

Kinetic energy is the energy an object has because it is moving. For a system that contains only one object, kinetic energy is the only mechanical energy it can have. Potential energy is not assigned to a lone object. It belongs to a system of interacting objects, such as an object and Earth or a block and a spring, or to a system that can change shape reversibly.

Kinetic energy depends on mass and speed, and speed has a stronger effect because it is squared:

```math
K = \frac{1}{2}mv^2
```

This is why doubling an object's speed multiplies its kinetic energy by four. A 2 kg ball moving at 3 m/s has 9 J of kinetic energy, but at 6 m/s it has 36 J.

### Kinetic and Potential Energies Together

Most systems involve interactions that let energy exist in more than one form at once. When objects interact through conservative forces, or when a system can change shape reversibly, energy converts back and forth between kinetic and potential forms.

- **Gravitational potential energy**: stored because of an object's position in a gravitational field.
- **Elastic potential energy**: stored in a stretched or compressed spring or elastic material.

A ball by itself has kinetic energy if it is moving. A ball-Earth system can have gravitational potential energy. A block-spring system can have elastic potential energy.

A pendulum shows this conversion clearly. At its highest point it stops for an instant, so kinetic energy is zero and gravitational potential energy is at its maximum. At its lowest point it moves fastest, so kinetic energy is at its maximum and potential energy is at its minimum.

## Conservation of Mechanical Energy

### Sum of Kinetic and Potential

Mechanical energy is the total of kinetic and potential energy in a system:

```math
E = K + U
```

For a ball thrown straight up, kinetic energy decreases and gravitational potential energy increases as it rises. At the peak, the energy is all potential. On the way down, potential energy turns back into kinetic energy. In an ideal system with no nonconservative forces, the total mechanical energy stays the same throughout.

### Energy Changes and Transfers

Energy changes follow strict accounting. Any decrease in one form of energy must be matched by an equal increase in another form or by a transfer to the surroundings.

When a skier goes down a slope, gravitational potential energy converts to kinetic energy. If friction acts, some energy becomes thermal energy, which lowers the mechanical energy of the skier-Earth system.

You can write the change in mechanical energy as:

```math
\Delta K + \Delta U = W_{nc}
```

where $`W_{nc}`$ is the work done by nonconservative forces.

### Constant Total Energy

By choosing your system boundaries carefully, you can often set up a situation where total energy stays constant. This lets you skip calculating external forces directly.

For a system with no external work and no dissipative forces:

- Total energy before equals total energy after.
- $`K_i + U_i = K_f + U_f`$

This applies to pendulums, roller coasters, orbiting planets, and many other systems where energy stays inside the defined boundaries.

### Energy Transfer Equivalence

When energy crosses a system boundary, the change in the system's total energy equals the amount transferred. That transfer can happen through work.

For a system experiencing external work:

```math
\Delta E_{system} = W_{external}
```

This lets you find energy changes by calculating the work done on the system, which is often easier than tracking every internal energy change.

## System Selection and Energy

### Conservation in Interactions

Energy conservation applies to all interactions. Energy may change form or move between objects, but the total amount stays the same. This holds across every scale of physics, which is part of why it is such a reliable tool.

### Zero Work and Constant Energy

When no external work acts on a system and no nonconservative forces act inside it, the system's mechanical energy stays constant.

Take planetary motion as an example, ignoring tidal effects and radiation. The total mechanical energy of the planet-sun system stays constant because:

- No external forces do work on the system.
- The gravitational force is conservative.
- No energy is dissipated.

### Nonzero Work and Energy Transfer

External work changes a system's total energy. Positive work, where the force points along the displacement, increases energy. Negative work decreases it.

When you push a box up a frictionless ramp, you do positive work, and the box-Earth system's potential energy rises. The energy gained equals the work you do.

🚫 **Boundary Statement**

For this course, know that nonconservative forces like friction and air resistance can dissipate mechanical energy as thermal energy or sound.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

Use this checklist on energy problems:

1. Define your system before anything else. The system choice decides whether mechanical energy is constant or changes.
2. Pick a zero level for potential energy. This is your choice, so pick the one that makes the numbers simplest.
3. Write the conservation statement. If no nonconservative forces act inside and no external work crosses the boundary, use $`K_i + U_i = K_f + U_f`$.
4. If friction or air resistance acts, account for the dissipated energy with $`\Delta K + \Delta U = W_{nc}`$.
5. Solve symbolically first, then plug in numbers and check units.

### Free Response

The Mathematical Routines question may ask you to derive an expression, build or use a representation, and explain your reasoning. For energy problems, an energy bar chart or a clear before-and-after energy statement makes your logic easy to follow. When you justify a claim, name the principle (conservation of mechanical energy) and tie it to the specific energies in your chosen system.

### Common Trap

Watch for problems where the system you pick changes whether energy is conserved. If you draw the system boundary around the block only, friction does negative work on it and its energy drops. If you draw the boundary around the block and surface together, that same friction is internal and shows up as thermal energy. Same physics, different bookkeeping.

## Common Misconceptions

- **Misconception:** A single object has potential energy.  
  **Actually:** Potential energy belongs to a system of interacting objects or a reversibly deforming system, not to one isolated object. Always name the system, like object-Earth or block-spring.
- **Misconception:** Energy disappears when friction acts.  
  **Actually:** It does not. Mechanical energy is dissipated into thermal energy and sound. The total energy is still conserved; it just left the mechanical category.
- **Misconception:** Conservation of mechanical energy always applies.  
  **Actually:** It only applies when no external work crosses the boundary and no nonconservative forces act inside the system. Check those conditions before using $`K_i + U_i = K_f + U_f`$.
- **Misconception:** The zero of potential energy is fixed by the problem.  
  **Actually:** You choose where $`U = 0`$. Different choices change the numbers for $`U`$ but not the physical answer for speeds or heights.
- **Misconception:** Perpendicular forces change kinetic energy.  
  **Actually:** A force perpendicular to the displacement, like the normal force on a flat surface or the tension in circular motion, does no work and does not change kinetic energy. It can still change direction.

## Practice Problem 1: Roller Coaster Energy Conservation

A 1000 kg roller coaster car starts from rest at a height of 40 meters. Assuming no friction or air resistance, determine the speed of the car when it reaches a height of 15 meters.

**Solution**

Apply conservation of mechanical energy since friction and air resistance are ignored:

Initial mechanical energy = Final mechanical energy $`K_i + U_i = K_f + U_f`$

Initial conditions:

- Initial height $`h_i = 40`$ m
- Initial velocity $`v_i = 0`$ m/s (starts from rest)
- Initial kinetic energy $`K_i = \frac{1}{2}mv_i^2 = 0`$ J
- Initial potential energy $`U_i = mgh_i = 1000 \times 9.8 \times 40 = 392{,}000`$ J

Final conditions:

- Final height $`h_f = 15`$ m
- Final potential energy $`U_f = mgh_f = 1000 \times 9.8 \times 15 = 147{,}000`$ J
- Final kinetic energy $`K_f = ?`$

From conservation of energy: $`0 + 392{,}000 = K_f + 147{,}000`$ $`K_f = 392{,}000 - 147{,}000 = 245{,}000`$ J

Now find the final speed: $`K_f = \frac{1}{2}mv_f^2`$ $`245{,}000 = \frac{1}{2} \times 1000 \times v_f^2`$ $`v_f^2 = \frac{2 \times 245{,}000}{1000} = 490`$ $`v_f = \sqrt{490} \approx 22.1`$ m/s

## Practice Problem 2: Spring-Mass System

A 2 kg block is pressed against a spring with spring constant 500 N/m, compressing it by 0.3 meters. If the block is released from rest on a frictionless horizontal surface, what will be its speed after it loses contact with the spring?

**Solution**

This problem converts elastic potential energy into kinetic energy.

Initial conditions:

- The spring is compressed by $`x = 0.3`$ m
- Initial velocity $`v_i = 0`$ m/s
- Initial elastic potential energy $`U_i = \frac{1}{2}kx^2 = \frac{1}{2} \times 500 \times (0.3)^2 = 22.5`$ J
- Initial kinetic energy $`K_i = 0`$ J

Final conditions (after block leaves spring):

- Spring is at natural length, so $`U_f = 0`$ J
- Final kinetic energy $`K_f = ?`$

Applying conservation of energy: $`U_i + K_i = U_f + K_f`$ $`22.5 + 0 = 0 + K_f`$ $`K_f = 22.5`$ J

Now find the final speed: $`K_f = \frac{1}{2}mv_f^2`$ $`22.5 = \frac{1}{2} \times 2 \times v_f^2`$ $`v_f^2 = \frac{22.5}{\frac{1}{2} \times 2} = \frac{22.5}{1} = 22.5`$ $`v_f = \sqrt{22.5} \approx 4.74`$ m/s

## Related AP Physics C: Mechanics Guides

- [3.2 Work](02-work.md)
- [3.3 Potential Energy](03-potential-energy.md)
- [3.1 Translational Kinetic Energy](01-translational-kinetic-energy.md)
- [3.5 Power](05-power.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| conservation of mechanical energy | The principle that the total mechanical energy of a system remains constant when only conservative forces act on it. |
| conservative force | A force for which the work done is path-independent and depends only on the initial and final configurations of the system. |
| energy | The capacity to do work or cause change; a conserved quantity that can be transferred between a system and its environment. |
| energy transfer | The process by which energy moves into or out of a system through the action of forces or torques. |
| kinetic energy | The energy possessed by an object due to its motion, equal to one-half the product of its mass and the square of its velocity. |
| mechanical energy | The total energy of a system due to its motion and position, equal to the sum of kinetic and potential energies. |
| nonconservative interactions | Interactions within a system, such as friction or air resistance, that dissipate mechanical energy as heat or other forms of energy. |
| potential energy | The energy stored in a system due to the relative positions or configurations of objects that interact via conservative forces. |
| system | A defined collection of objects whose energy and interactions are being analyzed. |
| work | Energy transferred to or from a system by forces or torques acting on it. |

## Frequently Asked Questions

### What is conservation of energy in AP Physics C: Mechanics?

Conservation of energy means energy can change form or move across a system boundary, but the total energy is accounted for. In mechanics problems, you often track mechanical energy with kinetic energy plus potential energy.

### What is mechanical energy?

Mechanical energy is the sum of a system's kinetic and potential energies. Kinetic energy depends on motion, while potential energy belongs to systems with conservative interactions or reversible shape changes, such as an object-Earth system or block-spring system.

### When is mechanical energy conserved?

Mechanical energy is constant when no external work is done on the chosen system and no nonconservative interactions act inside the system. If friction or air resistance matters, mechanical energy can be dissipated as thermal energy or sound.

### Why does system choice matter in energy problems?

System choice determines whether energy is stored inside the system or transferred across its boundary. The same physical situation can use different energy equations depending on whether you include Earth, a spring, a surface, or another interacting object in the system.

### How do you handle friction in conservation of energy problems?

If friction is a nonconservative interaction in your selected system, include the change in mechanical energy with delta K plus delta U equals W\_nc. Friction usually reduces mechanical energy by transferring it into thermal energy.

### How is conservation of energy used on AP Physics C FRQs?

Use a clear before-and-after energy statement, define the system, and solve symbolically when possible. On FRQs, naming the principle and explaining why mechanical energy is or is not conserved often matters as much as the final equation.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-3/4-conservation-of-energy/study-guide/wQp39tHxbOSvmKDT](https://fiveable.me/ap-physics-c-mechanics/unit-3/4-conservation-of-energy/study-guide/wQp39tHxbOSvmKDT)</sub>
