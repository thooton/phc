# 1.4 Reference Frames and Relative Motion

A reference frame is the viewpoint you measure motion from, and the same object can have different positions and velocities depending on who is watching. To switch between frames, you add or subtract velocity vectors, but acceleration stays the same in every inertial frame. In AP Physics C: Mechanics, this topic connects relative velocity, vector addition, inertial frames, and frame-dependent measurements.

## Why This Matters for the AP Physics C: Mechanics Exam

Relative motion shows up whenever a problem has two things moving at once: a boat in a current, a plane in wind, or a person walking on a moving train. The exam expects you to combine velocities using vector addition and to track which frame each measurement comes from. This thinking supports the multiple-choice section, where you analyze and compare representations, and the free-response section, where you may need to translate a scenario into diagrams and equations. Getting comfortable with frames now also sets up later work in dynamics, since acceleration being frame-independent is why Newton's laws hold in any inertial frame.

## Key Takeaways

- A reference frame is defined by what the observer is at rest with respect to, plus the chosen axes and positive directions.
- Position, displacement, and velocity all depend on the frame you measure from, so always state the frame.
- To convert a velocity between frames, add the object's velocity in one frame to that frame's velocity relative to the other frame.
- Use $`\vec{v}_{P/G} = \vec{v}_{P/M} + \vec{v}_{M/G}`$ for velocity and $`\vec{r}_{P/G} = \vec{r}_{P/M} + \vec{r}_{M/G}`$ for position.
- Acceleration is the same in all inertial reference frames, which is why Newton's laws work in any inertial frame.
- Unless a problem says otherwise, assume the frame is inertial.

## Reference Frame Fundamentals

A reference frame is a coordinate system you use to observe and measure motion. It gives you the viewpoint needed to describe position, velocity, and acceleration. Without specifying a frame, a statement about motion has no clear meaning.

### Describing an Observer's Reference Frame

To describe the reference frame of a given observer, identify three things:

1. **What the observer is at rest with respect to.** This defines the frame.
2. **The coordinate axes and positive directions** (sign conventions) used by that observer.
3. **How positions and velocities are measured** relative to that observer.

Consider a passenger sitting on a train. In the **passenger's reference frame**, the passenger is at rest, the inside of the train can be treated as fixed, and objects outside like trees or buildings appear to move backward. In the **ground (Earth) frame**, the ground is at rest, the train moves, and the passenger moves along with the train. Both frames are valid. The description of motion just depends on which one you choose.

### Direction and Magnitude in Reference Frames

The choice of reference frame determines both the direction and the magnitude of the quantities an observer measures.

- An object's velocity can look completely different from different frames.
- Position, displacement, and velocity are all frame-dependent quantities.
- The same physical situation can give different measurements depending on your viewpoint.

For example, if a train moves at 20 m/s east relative to the ground and a passenger walks at 2 m/s east relative to the train, then the passenger's speed is 2 m/s in the train frame but 22 m/s in the ground frame. Both the direction and the magnitude of a measured velocity depend on the observer's frame.

As another example, a car moving at 60 mph east appears stationary to a passenger inside the car, but to an observer standing on the side of the road, the car's velocity is 60 mph east. Neither perspective is wrong. They are different frames measuring the same physical reality.

## Motion in Inertial Reference Frames

Inertial reference frames are frames that are either stationary or moving with constant velocity (not accelerating). Newton's laws of motion work correctly in inertial frames.

### Conversion Between Reference Frames

When you analyze motion from different perspectives, you convert measurements between frames. For an object P, the position measured in the ground frame G and in a moving frame M are related by:

- For position: $`\vec{r}_{P/G} = \vec{r}_{P/M} + \vec{r}_{M/G}`$
  
  - Here $`\vec{r}_{P/G}`$ is the position of object P in the ground frame, $`\vec{r}_{P/M}`$ is the position of object P in the moving frame, and $`\vec{r}_{M/G}`$ is the position of the moving frame relative to the ground frame.
- For velocity: $`\vec{v}_{P/G} = \vec{v}_{P/M} + \vec{v}_{M/G}`$
  
  - In words: the object's velocity relative to the ground equals the object's velocity relative to the moving frame plus the moving frame's velocity relative to the ground.

These transformations are useful when a situation involves multiple moving objects or observers, such as boats crossing rivers, airplanes in wind, or objects moving on moving platforms.

### Observed Velocity vs Object Velocity

The velocity you observe for an object depends on both the object's actual velocity and the velocity of your reference frame.

An object's observed velocity is the vector sum of:

1. The object's velocity relative to its own reference frame.
2. The velocity of that reference frame relative to the observer's frame.

For example:

- If you walk forward at 3 mph on a train moving 60 mph east, an observer on the ground sees you moving at 63 mph east.
- If you walk backward at 3 mph on that same train, the ground observer sees you moving at 57 mph east.

While position and velocity change between inertial frames, acceleration stays the same.

- An object accelerating at $`10 \text{ m/s}^2`$ downward shows that same acceleration in all inertial frames.
- This consistency of acceleration across inertial frames is why Newton's laws work in any inertial frame.
- The invariance of acceleration is a core principle in classical mechanics.

**Boundary Statement**

Unless a problem specifies otherwise, assume the frame of reference is inertial.

## Practice Problem 1: Relative Velocity

A boat can travel at 5 m/s in still water. The boat needs to cross a 100 m wide river that flows at 3 m/s eastward. If the boat points directly north (perpendicular to the river's flow), determine: (a) the boat's velocity relative to the shore, and (b) how far downstream the boat will land.

**Solution**

Apply vector addition of velocities from different reference frames.

(a) The boat's velocity relative to the shore:

- Boat's velocity relative to water: 5 m/s north
- River's velocity relative to shore: 3 m/s east
- Using the Pythagorean theorem to find the resultant velocity:

```math
v_{resultant} = \sqrt{5^2 + 3^2} = \sqrt{25 + 9} = \sqrt{34} = 5.83 \text{ m/s}
```

The direction comes from trigonometry:

```math
\theta = \tan^{-1}(3/5) = 31.0° \text{ east of north}
```

So the boat's velocity relative to the shore is 5.83 m/s, 31.0° east of north.

(b) To find how far downstream the boat lands:

- Time to cross the river: $`t = \frac{width}{northward\,speed} = \frac{100\,m}{5\,m/s} = 20\,s`$
- Distance drifted downstream: $`d = v_{east} \times t = 3\,m/s \times 20\,s = 60\,m`$

The boat lands 60 meters downstream from the point directly across from its starting position.

Notice that the eastward current does not change how long the crossing takes, because motion in one dimension can change without affecting a perpendicular dimension.

## Practice Problem 2: Reference Frame Conversion

A train moves east at 30 m/s. A passenger walks toward the back of the train at 2 m/s relative to the train. What is the passenger's velocity as observed by someone standing on the ground?

**Solution**

Convert from the train's reference frame to the ground reference frame.

Choose east as positive. Then the train's velocity relative to the ground is +30 m/s, and the passenger's velocity relative to the train is -2 m/s because the passenger walks toward the back (west).

Using the velocity transformation equation:

```math
\vec{v}_{passenger/ground} = \vec{v}_{passenger/train} + \vec{v}_{train/ground}
```

```math
v_{passenger/ground} = (-2) + 30 = +28\,\text{m/s}
```

So the passenger's velocity as observed from the ground is 28 m/s east.

## How to Use This on the AP Physics C: Mechanics Exam

### Problem Solving

- Label every velocity with two subscripts, like $`\vec{v}_{P/G}`$, so you always know the object and the frame.
- Set up the chain so the inner subscripts match: $`\vec{v}_{P/G} = \vec{v}_{P/M} + \vec{v}_{M/G}`$. If the subscripts line up, your equation is set up correctly.
- For 2D problems like boats and planes, split each velocity into components and add them component by component. Use the Pythagorean theorem and an inverse tangent only at the end.
- Pick a positive direction first and keep it consistent. A velocity pointing the other way gets a negative sign.

### MCQ

- Watch for questions that ask which quantity is the same in two inertial frames. Acceleration is invariant; position and velocity are not.
- If two objects move toward or away from each other, the relative speed can be larger than either individual speed.

### Common Trap

- Do not just add or subtract magnitudes when velocities point in different directions. Two dimensions require vector components, not a single arithmetic step.

## Common Misconceptions

- **Misconception:** There is one correct velocity for an object.  
  **Actually:** Velocity depends on the frame. The passenger and the ground observer both report correct, just different, values.
- **Misconception:** Slowing down always means negative acceleration.  
  **Actually:** The sign of acceleration depends on your chosen positive direction, not on whether the object speeds up or slows down.
- **Misconception:** A current makes the river crossing take longer.  
  **Actually:** A perpendicular current changes where you land, not how long the crossing takes, because perpendicular components are independent.
- **Misconception:** Acceleration changes between frames the way velocity does.  
  **Actually:** Acceleration is the same in all inertial frames, which is exactly why Newton's laws work the same in each.
- **Misconception:** You can add velocity magnitudes directly.  
  **Actually:** That only works along a single line. For different directions, add vectors using components.

## Related AP Physics C: Mechanics Guides

- [1.1 Scalars and Vectors](01-scalars-and-vectors.md)
- [1.3 Representing Motion](03-representing-motion.md)
- [1.5 Motion in Two or Three Dimensions](05-motion-in-two-or-three-dimensions.md)
- [1.2 Displacement, Velocity, and Acceleration](02-displacement-velocity-and-acceleration.md)

## Vocabulary

The following words are mentioned explicitly in the AP® course framework for this topic.

| Term | Definition |
|---|---|
| acceleration | A vector quantity that describes the rate of change of an object's velocity with respect to time. |
| inertial reference frame | A reference frame in which Newton's laws of motion are valid; a frame that is either at rest or moving at constant velocity. |
| observer | A person or point of measurement from which physical quantities are measured and described in a particular reference frame. |
| reference frame | A coordinate system or perspective from which an observer measures the position, velocity, and other physical quantities of objects. |
| vector addition | The mathematical process of combining two or more vectors to find a resultant vector. |
| velocity | A vector quantity that describes the rate of change of an object's position with respect to time. |

## Frequently Asked Questions

### What is a reference frame in AP Physics C?

A reference frame is the viewpoint or coordinate system from which an observer measures motion. In AP Physics C: Mechanics, the direction and magnitude of position, displacement, and velocity depend on the reference frame you choose.

### What does relative motion mean in physics?

Relative motion means describing how an object moves as measured from a particular observer or frame. The same object can have different velocities in different frames, such as a person walking on a moving train versus the same person observed from the ground.

### What is the relative velocity formula?

A common vector form is $`\vec{v}_{P/G} = \vec{v}_{P/M} + \vec{v}_{M/G}`$, where the velocity of P relative to G equals the velocity of P relative to M plus the velocity of M relative to G. The labels matter because each velocity is measured in a specific frame.

### Are accelerations the same in different reference frames?

Acceleration is the same in all inertial reference frames. That is why Newton's laws work in any inertial frame, and AP Physics C problems usually let you assume a frame is inertial unless the problem states otherwise.

### How do I solve a train or boat relative-motion problem?

Choose a clear ground frame, label the moving frame, define positive directions, and write each velocity with two-frame labels. Then add or subtract vectors component by component, keeping units and directions consistent.

### How does relative motion show up on the AP Physics C exam?

Relative motion can appear in multiple-choice or free-response problems with moving observers, vehicles, currents, wind, or changing frames. The exam usually rewards clear diagrams, labeled velocity vectors, and correct conversion between reference frames.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/unit-1/4-reference-frames-and-relative-motion/study-guide/MhWvdpnoJuVbZ0WW](https://fiveable.me/ap-physics-c-mechanics/unit-1/4-reference-frames-and-relative-motion/study-guide/MhWvdpnoJuVbZ0WW)</sub>
