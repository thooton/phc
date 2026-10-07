# Multiple-Choice Questions (MCQ)

## Overview

The AP Physics C: Mechanics multiple-choice section has 42 questions in 85 minutes and counts for 50% of your total exam score. Calculators are allowed, but the section still rewards careful setup, calculus fluency, and physics reasoning.

Topic distribution emphasizes:

- **Kinematics** (10-15%): Position, velocity, and acceleration relationships using calculus
- **Force and Translational Dynamics** (20-25%): Forces, free-body diagrams, and dynamics
- **Work, Energy, and Power** (15-25%): Conservative forces, potential energy, and energy conservation
- **Linear Momentum** (10-20%): Collisions, center of mass, impulse, and momentum conservation
- **Torque and Rotational Dynamics** (10-15%): Torque, angular momentum, and rotational dynamics
- **Energy and Momentum of Rotating Systems** (10-15%): Rotational kinetic energy, angular impulse, and orbital motion
- **Oscillations** (10-15%): Springs, pendulums, and oscillatory motion

Expect heavy emphasis on combining concepts - rarely will a question test just one topic in isolation. A typical problem might involve a rolling object (combining rotation and translation) or a collision that requires both momentum and energy analysis.

The main challenge: Physics C tests your ability to apply calculus-based physics reasoning quickly. Unlike Physics 1 & 2, you'll see derivatives and integrals throughout. Questions often combine multiple topics - a rotation problem might involve energy conservation, or a projectile problem might require integration of variable forces. The pace is significantly faster than other AP Physics exams.

Critical distinction: A calculator is allowed, but Physics C multiple-choice still rewards strong symbolic reasoning. You should be comfortable with calculus operations, trigonometric identities, and algebraic manipulation so you can choose efficient solution paths quickly.

## Strategy Focus

Physics C multiple-choice questions test calculus-based physics thinking at a rapid pace, so your strategy needs to fit the format.

**Calculus Integration in Problem-Solving**

Physics C multiple-choice blends conceptual understanding with calculus fluency. When you see a varying force, immediately think integration. When you see a rate of change, think derivative. The math is part of the physics, not just a formality.

For example, when given a position-dependent force like F(x) = kx^2, you should instantly recognize that work requires integration: W = ∫F dx = ∫kx^2 dx = kx^3/3. Questions often provide:

- Force functions that vary with position: F(x) = F₀(1 - x/L)
- Velocity functions that change with time: v(t) = v₀e^(-bt)
- Acceleration that depends on velocity: a(v) = -bv^2

Common calculus applications in Mechanics:

- Finding velocity from varying acceleration: v = ∫a(t) dt
- Calculating work from variable force: W = ∫F̅ • dr̅
- Determining impulse from time-varying force: J = ∫F(t) dt

The test often uses questions where calculus provides efficient solution paths. A problem that seems complex algebraically often simplifies with the right derivative or integral. This rewards understanding over memorization.

**Rapid Symbolic Manipulation**

Even with calculator access, you must manipulate expressions efficiently. Key techniques that appear repeatedly:

*Dimensional analysis* becomes your quick-check tool. If asked for acceleration and your answer has dimensions of velocity, you know something's wrong immediately. This catches errors faster than re-solving.

*Limiting case analysis* helps eliminate options quickly. What happens as mass approaches infinity? As radius approaches zero? Often 2-3 answer choices fail simple limiting case tests.

*Symmetry arguments* save tremendous time. In rotational problems, recognize when objects with different mass distributions must have different behaviors. For collisions, use symmetry to simplify center of mass calculations.

**Multiple Concept Integration**

A typical complex question might involve a disk rolling down an incline (rotation + translation), connected by a string to a hanging mass (forces + constraints), with the system starting from rest (energy methods applicable). You must recognize which principles to apply and in what order.

Example integration patterns:

- Rolling motion: Combines v\_cm = ωR, rotational kinetic energy (1/2)Iω^2, and translational kinetic energy (1/2)Mv^2
- Pendulum with large amplitude: Integrates energy conservation, variable restoring force, and elliptic integrals
- Variable mass systems: Requires F = dp/dt = m(dv/dt) + v(dm/dt)

**Strategic Equation Selection**

Physics C rewards choosing the most efficient approach. Given the time constraints, selecting between energy methods, force methods, or momentum methods can save precious minutes.

For collision problems, momentum conservation often yields answers faster than analyzing forces:

- Elastic collisions: Use m₁v₁ᵢ + m₂v₂ᵢ = m₁v₁₆ + m₂v₂₆ and (1/2)m₁v₁ᵢ^2 + (1/2)m₂v₂ᵢ^2 = (1/2)m₁v₁₆^2 + (1/2)m₂v₂₆^2
- Inelastic collisions: Momentum alone often suffices

For objects moving through varying forces, energy methods typically outperform kinematics:

- Work-energy theorem: W\_net = ΔK
- Conservation of mechanical energy when only conservative forces act
- Power considerations: P = F̅ • v̅ or P = τω

## Common Question Patterns

Physics C multiple-choice exhibits consistent patterns that reward recognition. Understanding these patterns accelerates your problem-solving.

**Derivative/Integral Relationships**

Questions frequently test whether you understand the calculus relationships between physics quantities. Given position as a function of time, can you find velocity (derivative) and acceleration (second derivative)? Given acceleration as a function of position, can you find velocity (requires careful integration)?

Classic patterns in Mechanics:

- "A particle's position is given by x(t) = At^3 - Bt. At what time is the acceleration zero?" This tests whether you can take derivatives correctly: v = dx/dt = 3At^2 - B, then a = dv/dt = 6At, so a = 0 when t = 0.
- "Force on a particle varies as F = -kx^3. Find the potential energy function." This requires integration: U = -∫F dx = ∫kx^3 dx = kx^4/4 + C.
- "Angular acceleration varies as α = -bω. Find ω(t)." This leads to the differential equation dω/dt = -bω, giving ω = ω₀e^(-bt).

**Proportionality Reasoning**

Many questions test how quantities scale with each other. If you double the radius, how does the moment of inertia change? If you triple the angular velocity, how does the rotational kinetic energy change? These questions reward understanding fundamental relationships.

The key insight: write the relevant equation and identify which variables are changing. For I = (2/5)MR^2 (solid sphere), doubling R quadruples I. For K\_rot = (1/2)Iω^2, tripling ω increases K by a factor of 9. Answer choices often include various powers representing common mistakes.

Common proportionality relationships:

- Period of pendulum: T ∝ √L (small angles)
- Centripetal acceleration: a\_c ∝ v^2/r
- Angular momentum: L ∝ Iω

**Vector Calculus Applications**

Cross products appear frequently in rotation problems. Given τ̅ = r̅ × F̅, you must quickly evaluate magnitude and direction. Questions test whether you understand right-hand rules and vector components.

Key vector relationships in Mechanics:

- Torque: |τ̅| = rFsinθ with direction from right-hand rule
- Angular momentum: L̅ = r̅ × p̅ or L̅ = Iω̅
- Velocity in rotating frame: v̅ = ω̅ × r̅

**Differential Equation Recognition**

Physics C often presents situations leading to differential equations. You won't solve them completely, but must recognize their form and resulting behavior.

Simple harmonic motion yields d^2x/dt^2 = -ω^2x, with solutions x = Acos(ωt + φ). Questions test whether you recognize this form and understand:

- Period: T = 2π/ω
- Maximum velocity: v\_max = Aω
- Maximum acceleration: a\_max = Aω^2

Damped oscillation adds a velocity-dependent term: d^2x/dt^2 + 2γ(dx/dt) + ω₀^2x = 0. Recognize three cases:

- Underdamped: γ \< ω₀ (oscillates with decreasing amplitude)
- Critically damped: γ = ω₀ (fastest return without oscillation)
- Overdamped: γ \> ω₀ (slow exponential decay)

## Time Management Reality

The 85-minute section for 42 questions demands steady pacing. Physics C allows roughly 2 minutes per question, but multi-concept items can still take longer if you do not choose an efficient setup.

**Pacing Strategy**

Start strong with the first 10-12 questions. These typically test fundamental concepts with less complexity. Bank time here by moving efficiently through problems you recognize immediately. Aim to complete these in 10-12 minutes.

Questions 13-25 represent the meat of the exam. Expect multi-concept problems requiring 2-3 steps. These legitimately require 90-120 seconds each. If you banked time early, you can afford this pace.

Questions 26-40 often include the most challenging problems. Having a clear pacing plan for these final questions lets you tackle them properly rather than rushing.

**Skip Strategy**

Unlike some AP exams, Physics C multiple-choice includes genuinely difficult questions meant to challenge even top students. Recognize when a question would take 3+ minutes and skip it initially. Circle it clearly and return if time permits.

Types worth skipping initially:

- Complex differential equation setups
- Multi-step derivations with messy algebra
- Unusual scenarios you haven't practiced

**Mental Stamina**

The pace is mentally demanding. Around question 25, mental fatigue can peak. Take a 5-second pause, breathe deeply, and refocus. This brief reset is worth the time investment.

Key idea: Physics C rewards depth over breadth. It is better to answer carefully than rush through all 42 questions with errors. Focus on accuracy, efficient setup, and disciplined pacing.

## Specific Topic Strategies

**Rotational Motion Strategy**

Rotation problems integrate multiple concepts. Key strategies:

- Always identify whether objects roll with or without slipping
- For rolling: v\_cm = ωR and total kinetic energy K = (1/2)Mv\_cm^2 + (1/2)Iω^2
- Parallel axis theorem: I = I\_cm + Md^2 when rotation axis differs from center of mass
- Conservation of angular momentum when net external torque is zero: L\_i = L\_f

Common moments of inertia to memorize:

- Solid sphere: I = (2/5)MR^2
- Solid disk/cylinder: I = (1/2)MR^2
- Thin hoop/ring: I = MR^2
- Rod about center: I = (1/12)ML^2
- Rod about end: I = (1/3)ML^2

Common trap: forgetting that different shapes have different moments of inertia. A sphere, disk, and hoop rolling down the same incline arrive at different times. The object with smaller I/MR² accelerates faster.

**Oscillation Analysis**

SHM appears frequently, often combined with other topics:

- Recognize when restoring force is proportional to displacement: F = -kx
- For spring-mass systems: ω = √(k/m), so T = 2π√(m/k)
- For physical pendulums: T = 2π√(I/(mgd)) where d is distance from pivot to center of mass
- Energy in SHM oscillates between kinetic and potential: E = (1/2)kA^2 = (1/2)mv\_max^2
- Small angle approximation: sinθ ≈ θ for θ \<\< 1 radian

Calculus connections:

- Position: x = Acos(ωt + φ)
- Velocity: v = -Aωsin(ωt + φ)
- Acceleration: a = -Aω^2cos(ωt + φ) = -ω^2x

**Advanced Kinematics with Calculus**

When acceleration isn't constant, calculus becomes necessary:

- Velocity-dependent drag: F = -bv leads to v = v₀e^(-bt/m)
- Position-dependent force: Requires energy methods or solving m(dv/dt) = F(x)
- Time-varying acceleration: Direct integration v = v₀ + ∫a(t) dt

**Collision and Momentum Strategies**

For collision problems:

- Always conserve momentum: p̅\_initial = p̅\_final
- For elastic collisions, also conserve kinetic energy
- For explosions, momentum conservation often suffices
- Center of mass velocity remains constant if no external forces: v̅\_cm = (∑mᵢv̅ᵢ)/(∑mᵢ)

Variable mass problems require the full form: F\_ext = dp/dt = m(dv/dt) + v(dm/dt)

## Final Thoughts

AP Physics C: Mechanics multiple-choice rewards deep understanding of calculus-based physics applied rapidly. Success comes from recognizing patterns, choosing efficient solution methods, and maintaining accuracy without calculator support.

The mathematical sophistication required is significant, but problems are designed to test physics insight, not computational endurance. Elegant solutions exist for most problems - finding them quickly is the challenge.

Use your calculator strategically, but do not rely on it for every step. Build intuition for which calculus tools apply to which physical scenarios. Develop symbolic manipulation and limiting case analysis. Most importantly, understand that this section tests whether you think like a physicist who uses calculus as a natural language for describing change and accumulation.

The 50% weight of this section matters, but the generous curve means perfection isn't necessary. Focus on accuracy over completion. A student who works carefully and keeps a steady pace typically outscores one who rushes through all 42. Trust your preparation, maintain your pace, and let your understanding of calculus-based physics guide you through.

## Frequently Asked Questions

### How many multiple-choice questions are on the AP Physics C Mechanics exam?

Starting with the May 2027 exam, the MCQ section has 42 single-select questions with four answer choices each, and you get 85 minutes. It counts for 50% of your exam score.

### Can you use a calculator on the AP Physics C Mechanics multiple choice?

Yes. A four-function, scientific, or graphing calculator is allowed on both the multiple-choice and free-response sections. That said, most MCQs are built so symbolic reasoning, proportionality, and limiting cases get you to the answer faster than computation.

### How much is the MCQ section worth on AP Physics C Mechanics?

The multiple-choice section is worth 50% of your total exam score, equal to the four free-response questions in Section II. There is no guessing penalty, so you should answer all 42 questions. Check how MCQ and FRQ performance combine with the [AP score calculator](https://fiveable.me/ap-physics-c-mechanics/ap-score-calculator).

### Which units appear most on the AP Physics C Mechanics MCQ section?

Force and Translational Dynamics is the heaviest at 20-25%, followed by Work, Energy, and Power at 15-25% and Linear Momentum at 10-20%. Kinematics, Torque and Rotational Dynamics, Energy and Momentum of Rotating Systems, and Oscillations each run 10-15%. Prioritizing forces and energy gives you the most points per hour of review.

### Do you need calculus for the AP Physics C Mechanics multiple choice?

Yes, calculus shows up throughout the MCQ section. Expect to integrate time-varying forces for impulse, integrate position-dependent forces for work, take derivatives of position functions, and recognize differential equation forms like simple harmonic motion. You won't fully solve hard differential equations, but you must recognize what their solutions look like.

### Do you need to answer all 42 questions to get a 5 on AP Physics C Mechanics?

No, you don't need a perfect raw score for a 5. The smarter play is to answer everything (there's no guessing penalty) while spending your time on questions you can solve accurately and marking 3-minute problems to revisit. Build pacing with a [full-length practice exam](https://fiveable.me/ap-physics-c-mechanics/practice-exam) before test day.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/ap-physics-c-mechanics-exam/ap-physics-c-mechanics-ap-phys-mech-mcq/study-guide/ap-physics-c-mechanics-ap-phys-mech-mcq](https://fiveable.me/ap-physics-c-mechanics/ap-physics-c-mechanics-exam/ap-physics-c-mechanics-ap-phys-mech-mcq/study-guide/ap-physics-c-mechanics-ap-phys-mech-mcq)</sub>
