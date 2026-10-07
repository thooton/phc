# FRQ 1 – Mathematical Routines

Practice with 46 Mathematical Routines FRQs

Read the full question, write your response, and see your score on every part.

[start practicing](https://fiveable.me/ap-physics-c-mechanics/frqs/mathematical-routines)

## Overview

AP Physics C: Mechanics FRQ 1 is the mathematical routines question, worth 10 points and recommended for about 20-25 minutes. It asks you to use calculus, diagrams, derivations, calculations, and mechanics reasoning to analyze a scenario.

The Mathematical Routines question in Physics C: Mechanics demands calculus-based analysis of mechanical systems. You'll derive relationships using differential and integral calculus, create force/torque diagrams, and demonstrate how mathematical formalism reveals physical behavior. This question type showcases the power of calculus as the natural language of mechanics.

## Strategy Focus

Mathematical Routines questions in Physics C follow a sophisticated progression from physical setup to mathematical analysis. Success requires seamlessly blending physics intuition with calculus techniques.

**The Calculus-First Mindset**

Unlike Physics 1, where calculus is forbidden, Physics C expects calculus as your primary analytical tool. When you see "derive an expression," the graders expect to see differential equations, integrals, or both. Key paradigm shifts:

- Variable forces demand integration: W = ∫F·dx, not just Fd
- Non-constant acceleration requires v = ∫a dt, not just v₀ + at
- Continuous mass distributions need dm integration for center of mass or moment of inertia
- Power analysis often involves P = dW/dt relationships

Start every derivation by identifying whether you're dealing with rates of change (derivatives) or accumulation (integrals). This decision shapes your entire approach.

**Advanced Free-Body Diagrams**

Physics C free-body diagrams go beyond simple force arrows. Consider:

- For rolling objects, show forces at their actual points of application (friction at contact point, not center)
- For extended objects, indicate where forces act to determine torque arms
- For systems with constraints, show constraint forces (like tension) that enforce the constraint
- For varying forces, indicate the coordinate system that makes integration simplest

Example: For a ball rolling down a ramp, draw gravity at center, normal and friction at contact point. This setup naturally leads to analyzing torque about the contact point, eliminating the unknown friction from the torque equation.

**Systematic Derivation Structure**

Physics C derivations demand rigorous presentation:

1. **State the principle**: "By Newton's second law for rotation, Στ = Iα"
2. **Apply to your system**: "About the contact point: MgR sin θ = (I + MR²)α"
3. **Use constraints**: "For rolling without slipping: a = αR"
4. **Solve systematically**: Show algebraic steps leading to your final expression
5. **Check dimensions**: Confirm your answer has correct units

The graders want to see physics reasoning at each step, not just mathematical manipulation.

**Integration Techniques Specific to Mechanics**

Common integration scenarios in Mathematical Routines:

- **Variable Force Work**: W = ∫F(x)dx where limits match the motion
- **Impulse from Time-Varying Force**: J = ∫F(t)dt
- **Center of Mass**: x\_cm = (1/M)∫x dm with appropriate dm expression
- **Moment of Inertia**: I = ∫r² dm about specified axis

Always define your integration variable clearly and express dm or other differentials in terms of that variable before integrating.

## Common Problem Types

Certain scenarios dominate Mathematical Routines questions, each with specific calculus applications.

**Rolling Motion with Energy Methods**

Classic setup: Object rolling down a curved path. The calculus comes from:

- Finding velocity at any point using energy: ½Mv² + ½Iω² = Mgh
- Differentiating to find acceleration: v(dv/dx) = g(dh/dx)
- Relating linear and angular quantities: v = ωR throughout

Key insight: For arbitrary curved paths, the component of g along the path varies with position, requiring calculus to find motion parameters.

**Variable Force Problems**

Springs with non-linear behavior (F ≠ -kx) or position-dependent forces require integration:

- Work done: W = ∫F(x)dx with careful attention to sign
- Potential energy: U(x) = -∫F(x)dx + C where C is determined by reference point
- Finding speed using work-energy theorem after calculating work

Remember: Variable forces often lead to differential equations. If F = F(x) and you need x(t), you'll likely use energy methods to avoid solving the differential equation directly.

**Continuous Mass Distributions**

Problems involving rods, disks, or spheres with non-uniform density:

- Express dm in terms of position: dm = λ(x)dx for linear density
- Set up integral for desired quantity (center of mass, moment of inertia)
- Choose integration limits matching the object's extent
- Evaluate, often using substitution or recognizing standard forms

**Systems with Constraints**

Atwood machines, connected pendulums, or pulley systems where calculus enters through:

- Constraint relationships: If string length is constant, d/dt(x₁ + x₂) = 0
- Energy methods for systems: d/dt(KE + PE) = P\_external
- Lagrangian approach (though rarely required): d/dt(∂L/∂q̇) - ∂L/∂q = 0

## Detailed Rubric Breakdown

Understanding scoring helps you maximize partial credit even when stuck.

**Part (a): Setup and Representation (2-3 points)**

**Force/Torque Identification (1-2 points)**:

- Draw all forces at correct locations
- Choose rotation axis strategically (often where unknown force acts)
- Set up coordinate system favorable for later calculus

**Initial Equations (1 point)**:

- Write fundamental principles that will guide derivation
- Define all variables you'll use
- State any constraints (like rolling without slipping)

Common deductions: Missing forces, poor choice of coordinates making integration harder, undefined variables.

**Part (b): Calculus-Based Derivation (4-5 points)**

**Correct Calculus Setup (2 points)**:

- Identify what needs differentiation or integration
- Write differential equation or integral with correct limits
- Show relationship between variables clearly

**Mathematical Execution (2 points)**:

- Perform integration/differentiation correctly
- Handle constants of integration appropriately
- Substitute limits correctly for definite integrals

**Physics Consistency (1 point)**:

- Check signs throughout (does friction oppose motion?)
- Verify dimensions at each major step
- Ensure result makes physical sense

Common deductions: Dropped negative signs, incorrect integral limits, forgetting to square terms in energy expressions.

**Part (c): Application and Analysis (3-4 points)**

**Numerical Evaluation (1-2 points)**:

- Substitute given values correctly
- Calculate with proper significant figures
- Include units in final answer

**Comparison/Prediction (2 points)**:

- Use derived expression to compare scenarios
- Explain physical significance of mathematical result
- Connect to limiting cases (what if friction → 0?)

Common deductions: Calculator errors, missing units, not explaining the physics meaning of mathematical results.

## Time Management

With ~22 minutes for Mathematical Routines:

- **Minutes 1-3**: Read carefully, identify all parts, sketch the scenario
- **Minutes 4-6**: Complete part (a) - diagram and setup
- **Minutes 7-15**: Work through part (b) - the major derivation
- **Minutes 16-20**: Complete part (c) - application and analysis
- **Minutes 21-22**: Review for completeness, check units

If running behind, prioritize showing physics understanding over completing calculations. Write "would integrate ∫F(x)dx from x₁ to x₂" rather than leaving blank.

## Calculator Strategies

Your calculator is useful for Mathematical Routines:

- Use it to check dimensional analysis quickly
- Evaluate definite integrals numerically if analytical solution is complex
- Graph functions to verify your derived expressions make sense
- Store intermediate results to avoid transcription errors

But remember: Show all analytical work first. The calculator confirms and evaluates; it doesn't replace showing your physics understanding.

## Final Tips

Mathematical Routines questions reward systematic thinking and clear presentation. The calculus should feel natural, not forced - it's simply the tool that makes analyzing realistic physics possible. When you see varying quantities, think calculus. When setting up problems, choose coordinates and reference frames that simplify the mathematics.

Most importantly, remember that every mathematical step should have physical meaning. You're not just doing math; you're using mathematics to reveal how nature behaves. Let physics guide your mathematics, and let mathematics make your physics precise.

## Frequently Asked Questions

### How many points is the Mathematical Routines FRQ worth on AP Physics C Mechanics?

FRQ 1, Mathematical Routines, is worth 10 of the 40 free-response points, with a suggested time of 20-25 minutes. It's the first of 4 FRQs in Section II, which lasts 95 minutes and counts for 50% of your exam score.

### How long is the FRQ section on the AP Physics C Mechanics exam?

Starting with the May 2027 exam, Section II gives you 95 minutes for 4 free-response questions and counts for 50% of your score. The suggested splits are 20-25 minutes for Q1 (Mathematical Routines), 25-30 for Q2 and Q3, and 15-20 for Q4.

### Do I have to start FRQ derivations with a fundamental physics principle?

Yes. Mathematical Routines prompts explicitly say to begin your derivation by writing a fundamental physics principle or an equation from the reference material. Starting mid-derivation with a rearranged formula can cost you the setup points even if your final expression is correct.

### Do you need calculus on the AP Physics C Mechanics FRQs?

Yes. The Mathematical Routines question expects calculus as a primary tool: integrating variable forces for work or impulse, differentiating potential energy to get force, and setting up dm integrals for rotational inertia or center of mass. If a quantity varies, the constant-value formulas from Physics 1 won't earn full credit.

### Can you use a calculator on the AP Physics C Mechanics exam?

Yes, a four-function, scientific, or graphing calculator is allowed on both the multiple-choice and free-response sections. On FRQ 1, use it to check numerical answers and verify graph shapes, but show all analytical work on paper since the points come from your written derivations.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/ap-physics-c-mechanics-exam/ap-physics-c-mechanics-ap-phys-mech-frq-mathematical-routines/study-guide/ap-physics-c-mechanics-ap-phys-mech-frq-mathematical-routines](https://fiveable.me/ap-physics-c-mechanics/ap-physics-c-mechanics-exam/ap-physics-c-mechanics-ap-phys-mech-frq-mathematical-routines/study-guide/ap-physics-c-mechanics-ap-phys-mech-frq-mathematical-routines)</sub>
