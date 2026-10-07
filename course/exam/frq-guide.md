# Free Response Questions

## Overview

The AP Physics C: Mechanics free-response section has 4 questions in 95 minutes and counts for 50% of your total exam score. The questions use Physics-style representations and reasoning, but with calculus integrated throughout.

The four FRQs appear in this order:

1. **Mathematical Routines (MR)** - Derivation and calculation with calculus
2. **Translation Between Representations (TBR)** - Graphs, equations, and physical analysis
3. **Experimental Design and Analysis (EDA)** - Lab-based scenarios with data
4. **Qualitative/Quantitative Translation (QQT)** - Explaining physics with and without math

Each Physics C: Mechanics exam includes all 4 FRQ types. This guide covers strategies for each type.

## Strategy Focus

Physics C free response demands smooth integration of calculus with physics reasoning. Understanding how each question type incorporates calculus helps you choose the right strategy.

**Calculus as a Physics Tool**

In Physics C, calculus isn't an add-on - it's fundamental to expressing physics relationships. When you see changing quantities, think derivatives. When you see accumulation, think integrals. This mindset shift matters.

Problems involving variable forces, non-constant acceleration, or continuous mass distributions require calculus. For instance:

- Finding velocity from a position-dependent force involves the work-energy theorem with integration
- Calculating moment of inertia for continuous objects requires integration over mass elements
- Analyzing motion with velocity-dependent drag forces leads to differential equations

Common calculus applications in Mechanics:

- Work from variable force: W = ∫F̅ • dr̅
- Impulse from time-varying force: J = ∫F(t) dt
- Center of mass for continuous distributions: x\_cm = (1/M)∫x dm
- Rotational inertia: I = ∫r^2 dm

**The Three-Pass Strategy**

Given four questions in 95 minutes, time management is critical. Use this approach:

*First Pass (4 minutes)*: Read all four questions completely. Identify which type seems most approachable. Starting with your strongest question builds confidence and banks time.

*Main Pass (18-23 minutes per question)*: Work systematically through each question, adjusting for the suggested time of each FRQ type. Show all steps, especially calculus operations. Even if you can do integration in your head, write it out - partial credit depends on visible work.

*Review Pass (4-6 minutes)*: Check for missing units, undefined variables, or unanswered parts. Add brief explanations where you provided only mathematics.

**Partial Credit Maximization**

Physics C FRQs award partial credit generously. Key strategies:

- State fundamental principles before applying them
- Define all variables you introduce
- Show calculus steps explicitly
- Include units throughout, not just in final answers
- If stuck, write what you would do conceptually

## Question Type 1: Mathematical Routines (MR)

Mathematical Routines in Physics C heavily emphasize calculus-based derivations and multi-step problem solving.

**Recognizing MR Questions**

These questions typically present a physical scenario and guide you through mathematical analysis using calculus. Look for phrases like "derive an expression," "integrate to find," or "use calculus to show."

**MR Structure and Approach**

Part (a) usually involves setup - drawing diagrams, identifying forces/fields, or stating relevant principles. Be thorough here as later parts build on this foundation.

Part (b) typically requires derivation using calculus. Common patterns in Mechanics:

- Deriving velocity from force using Newton's second law: F = ma = m(dv/dt)
- Finding work from variable force: W = ∫F̅ • dr̅
- Analyzing rotational motion with torque: τ = Iα = I(dω/dt)
- Solving for motion with drag: m(dv/dt) = mg - bv

Example MR progressions:

- Given force as function of position, find:
  
  - Work done over a distance
  - Speed at a specific point using work-energy theorem
  - Time to reach that point (requires solving differential equation)
- Given torque as function of angle, derive:
  
  - Angular acceleration function
  - Angular velocity after rotation through given angle
  - Time required for rotation

Part (c) often asks for evaluation at specific conditions or comparison between scenarios. This tests whether you understand the physics meaning of your mathematical results.

**Scoring Insights for MR**

Points typically distribute as:

- 2-3 points for correct setup/diagram
- 4-5 points for derivation with proper calculus
- 2-3 points for evaluation/interpretation
- 1-2 points for units and mathematical consistency

Common point losses: forgetting constants of integration, incorrect limits on definite integrals, or missing negative signs from derivatives.

## Question Type 2: Translation Between Representations (TBR)

TBR questions in Physics C test your ability to move fluently between graphs, equations, and physical descriptions while incorporating calculus relationships.

**Recognizing TBR Questions**

Look for problems providing information in one form (like a graph) and asking for analysis in another form (like equations or verbal descriptions). Calculus connects these representations.

**TBR Unique Challenges in Mechanics**

Common scenarios:

- Given a force vs. position graph, find work (area under curve), then use work-energy theorem to find velocity
- Given acceleration vs. time graph, integrate to find velocity, integrate again for position
- Given potential energy function, find force (negative derivative), then analyze motion
- Given angular velocity vs. time, find angular displacement (integral) and angular acceleration (derivative)

**Graph Analysis with Calculus**

Key relationships to remember:

- Slope represents derivative (velocity from position, acceleration from velocity)
- Area represents integral (impulse from force, work from force vs. position)
- Concavity indicates second derivative sign

When sketching derived or integrated quantities:

- Zeros of original become extrema of integral
- Extrema of original become zeros of derivative
- Sign of original determines increasing/decreasing integral

Example: Given velocity vs. time graph showing linear decrease from v₀ to zero:

- Acceleration is constant negative slope
- Position is parabolic (integral of linear function)
- Maximum displacement when velocity crosses zero

**Scoring Insights for TBR**

Points typically award for:

- Correct identification of calculus relationships (2-3 points)
- Accurate graph sketching or equation development (3-4 points)
- Physical interpretation of mathematical results (2-3 points)
- Consistency between representations (2-3 points)

Common mistakes: forgetting that integration introduces arbitrary constants, misidentifying whether to differentiate or integrate, or losing track of signs.

## Question Type 3: Experimental Design and Analysis (EDA)

EDA questions in Physics C incorporate calculus into experimental analysis, particularly in linearization and uncertainty propagation.

**Recognizing EDA Questions**

These problems present experimental scenarios with data tables, measurement uncertainties, or procedural descriptions. Calculus appears in data analysis and theoretical predictions.

**Linearization Techniques in Mechanics**

Examples:

- Measuring oscillation period vs. amplitude for large-angle pendulum: The relationship is non-linear, but theoretical analysis with elliptic integrals suggests specific linearization
- Analyzing damped oscillations: Plotting ln(amplitude) vs. time linearizes exponential decay to find damping coefficient
- Projectile with air resistance: Velocity decay follows differential equation; linearization helps extract drag coefficient

**Uncertainty Analysis with Calculus**

Physics C may ask for uncertainty propagation using derivatives: δf = √\[∑ᵢ (∂f/∂xᵢ · δxᵢ)^2\]

This appears when combining measurements to calculate derived quantities like:

- Moment of inertia from period measurements
- Energy from velocity and position data
- Angular momentum from rotation measurements

**Experimental Design Considerations**

When asked to design experiments:

- Identify what varies continuously (requiring calculus analysis)
- Consider whether numerical integration/differentiation of data is needed
- Think about linearization to extract parameters

Example experimental scenarios:

- Measuring g using pendulum: How does uncertainty in period affect g calculation?
- Finding spring constant from oscillation: How to account for mass of spring?
- Determining coefficient of restitution: How to handle multiple bounces?

**Scoring Insights for EDA**

Points distribute across:

- Experimental procedure clarity (2-3 points)
- Appropriate graph construction (2-3 points)
- Correct use of calculus in analysis (3-4 points)
- Uncertainty consideration (1-2 points)
- Comparison with theoretical predictions (2-3 points)

Common issues: attempting to linearize incorrectly, forgetting to propagate uncertainties, or not connecting experimental results to theoretical predictions.

## Question Type 4: Qualitative/Quantitative Translation (QQT)

QQT questions in Physics C test whether you can explain physics phenomena both with and without mathematical formalism.

**Recognizing QQT Questions**

These problems often have parts asking for explanation "without calculation" followed by mathematical verification, or vice versa. They test conceptual understanding alongside mathematical facility.

**Conceptual Explanation Strategies in Mechanics**

Examples of conceptual explanations before calculation:

- Why a sphere rolls down an incline faster than a hoop: Discuss energy distribution between rotational and translational motion, how moment of inertia affects angular acceleration
- Why a physical pendulum has different period than simple pendulum: Explain role of mass distribution, rotational inertia about pivot
- How damping affects oscillation: Describe energy dissipation, phase relationships, approach to equilibrium

**Mathematical Verification**

After conceptual explanation, mathematical parts often ask you to "verify your reasoning" or "calculate to confirm." This requires:

- Setting up relevant equations
- Using calculus where quantities vary
- Showing numerical or symbolic results support your conceptual argument

Example progression:

1. Explain conceptually why rolling objects of different shapes reach bottom at different times
2. Derive acceleration for rolling object: a = gsinθ/\[1 + I/(MR^2)\]
3. Calculate specific values for sphere, disk, and hoop
4. Show results confirm conceptual ranking

**Balancing Qualitative and Quantitative**

The key challenge: ensuring consistency between explanations and calculations. Your conceptual reasoning should predict what your math will show, and your math should illuminate why your conceptual reasoning works.

**Scoring Insights for QQT**

Points typically award for:

- Clear conceptual explanation (3-4 points)
- Correct mathematical setup (2-3 points)
- Proper calculus application (2-3 points)
- Consistency between approaches (2-3 points)
- Final synthesis/conclusion (1-2 points)

Common pitfalls: explanations that contradict calculations, overly vague conceptual arguments, or mathematics that doesn't actually address the question asked.

## Time Management Reality

With 95 minutes for 4 questions totaling 40 points, pacing matters. Here's a realistic timeline:

**Minutes 0-4: Survey and Select** Read all four questions completely. Identify types and difficulty. Choose your starting order - typically easiest first to build confidence and bank time. Mark parts that look time-consuming.

**Minutes 4-27: First Question** Allocate time by FRQ type, adjusting based on difficulty. For your first question:

- Setup and part (a): 3-4 minutes
- Main derivation/analysis: 10-14 minutes
- Final parts and checking: 3-4 minutes

**Minutes 27-52: Second Question** Maintain similar pacing. If running behind, identify which parts are worth most points, usually derivations, graphing, or data-analysis steps, and prioritize those.

**Minutes 52-88: Remaining Questions** Work through the remaining two questions with the official suggested times in mind: 20-25 minutes for MR, 25-30 minutes for TBR, 25-30 minutes for EDA, and 15-20 minutes for QQT. If one question feels rushed, you can still earn substantial partial credit. Focus on:

- Setting up the problem correctly
- Writing down relevant equations
- Showing calculus steps even if you can't complete them
- Adding units and brief explanations

**Minutes 88-95: Final Review** Quick scan for:

- Unanswered parts (even writing relevant equations earns points)
- Missing units
- Undefined variables
- Basic arithmetic errors in calculations

Time-saving tip: If a calculation yields a messy expression, leave it unsimplified and move on. Graders care more about correct setup and process than arithmetic simplification.

## Calculus-Specific Strategies

**Integration Techniques in Mechanics**

Common integrals you should recognize instantly:

- ∫F dx for work with variable force
- ∫r^2 dm for moment of inertia
- ∫dx/√\[2g(h-x)\] type for time calculations in free fall
- ∫v dt for displacement
- ∫ω dt for angular displacement

Specific techniques:

- For circular/spherical mass distributions: Convert dm to density times volume element
- For work integrals: Parametrize path if needed
- For time integrals: Often requires separation of variables

**Differential Equations in Mechanics**

Physics C FRQs sometimes lead to differential equations. You're not expected to solve complex ones, but should recognize standard forms:

Simple harmonic motion: d^2x/dt^2 = -ω^2x

- General solution: x = Acos(ωt + φ)
- Initial conditions determine A and φ

Damped oscillation: d^2x/dt^2 + 2γ(dx/dt) + ω₀^2x = 0

- Underdamped: x = Ae^(-γt)cos(ω't + φ) where ω' = √(ω₀^2 - γ^2)
- Know how to identify damping regime from coefficients

Variable mass (rocket equation): F\_ext = m(dv/dt) + v(dm/dt)

- Separation of variables often required
- Watch signs carefully (dm/dt typically negative)

**Approximation Methods**

When exact integration is difficult, Physics C accepts approximation methods:

- Small angle approximations: sinθ ≈ θ, cosθ ≈ 1 - θ^2/2
- Binomial approximation: (1+x)^n ≈ 1 + nx for |x| \<\< 1
- Series expansions for first-order effects

Example use: For large-amplitude pendulum, period involves elliptic integral. First-order correction: T ≈ T₀(1 + θ\_max^2/16)

## Common Pitfalls and Solutions

**Calculus Errors**

Most common mistakes:

- Forgetting constants of integration (especially in indefinite integrals)
- Wrong limits on definite integrals
- Sign errors in derivatives (especially with negative exponents)
- Confusing partial and total derivatives

Solution: Write every step. Show limits clearly. Check dimensions.

**Physics-Math Disconnect**

Sometimes correct math leads to physics nonsense (negative mass, imaginary time). When this happens:

- Check your setup - did you define coordinates consistently?
- Verify sign conventions throughout
- Consider whether approximations are valid

**Over-Complication**

Physics C problems have elegant solutions. If your approach yields pages of algebra:

- Step back and look for symmetry
- Consider alternative methods (energy vs. forces)
- Check if you're asked for a specific case rather than general solution

Example: Finding time for object to slide down curve. Force approach leads to messy differential equation. Energy approach with v = √(2gh) often simpler.

## Final Thoughts

Success on Physics C: Mechanics free response comes from seamlessly blending physics intuition with calculus tools. These aren't separate skills - they're complementary aspects of understanding how physical quantities change and accumulate.

Practice translating physical scenarios into mathematical language and vice versa. When you see a derivative, think rate of change. When you see an integral, think accumulation. This bidirectional fluency is what distinguishes strong Physics C performance.

Remember that partial credit rewards physics thinking even when mathematical execution falters. Show your reasoning, set up problems correctly, and show that you understand which calculus tools apply to which physical situations. The graders want to see physicist thinking, not just mathematical manipulation.

The 50% weight of this section matters, but the scoring is fair. A student who shows clear physics reasoning and attempts appropriate calculus typically scores well, even with computational errors. Trust your preparation, manage time wisely, and let your understanding of calculus-based physics guide your solutions.

## Frequently Asked Questions

### How many FRQs are on the AP Physics C Mechanics exam?

There are 4 free-response questions in 95 minutes, worth 50% of your exam score. They always appear in the same order: Mathematical Routines (10 points), Translation Between Representations (12 points), Experimental Design and Analysis (10 points), and Qualitative/Quantitative Translation (8 points), for 40 points total.

### How are AP Physics C Mechanics FRQs scored?

The four FRQs total 40 points and count for half your exam score: 10 points for Mathematical Routines, 12 for Translation Between Representations, 10 for Experimental Design and Analysis, and 8 for Qualitative/Quantitative Translation. Partial credit is generous, so stated principles, visible calculus steps, and correct setups earn points even when the final answer is wrong. You can check rubric-level feedback with [FRQ practice and instant scoring](https://fiveable.me/ap-physics-c-mechanics/frq-practice).

### Can you use a calculator on the AP Physics C Mechanics FRQ section?

Yes. A four-function, scientific, or graphing calculator is allowed on both the multiple-choice and free-response sections of the AP Physics C: Mechanics exam. Most FRQ work is symbolic derivation, though, so the calculator matters most for numerical parts and the data analysis in Question 3.

### Do AP Physics C Mechanics FRQs require calculus?

Yes, calculus is built into the FRQs. Expect to integrate variable forces for work or impulse, derive potential energy from force functions (with constants of integration), set up rotational inertia integrals, and recognize differential equations like drag and simple harmonic motion. Derivations must also start from a fundamental physics principle, not a memorized end formula.

### Do I have to answer the AP Physics C Mechanics FRQs in order?

No. You get all four questions at once for the 100-minute section, so you can work in any order. A common strategy is to spend the first 5 minutes reading all four, then start with your strongest question type to bank time and confidence. Just budget by point value: the 12-point Translation Between Representations question deserves more time than the 8-point QQT.

### What is the Experimental Design FRQ in AP Physics C Mechanics?

Question 3 (10 points, suggested 25-30 minutes) has two halves: design a replicable experiment that varies one parameter and measures one outcome, then linearize and graph provided data to extract a physical quantity from the slope or intercept. The [FRQ 3 Experimental Design guide](frq-experimental-design.md) walks through procedure-writing and linearization step by step.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/ap-physics-c-mechanics-exam/ap-physics-c-mechanics-frq-guide/study-guide/ap-physics-c-mechanics-frq-guide](https://fiveable.me/ap-physics-c-mechanics/ap-physics-c-mechanics-exam/ap-physics-c-mechanics-frq-guide/study-guide/ap-physics-c-mechanics-frq-guide)</sub>
