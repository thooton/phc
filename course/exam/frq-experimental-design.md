# FRQ 3 – Experimental Design

Practice with 37 Experimental Design FRQs

Read the full question, write your response, and see your score on every part.

[start practicing](https://fiveable.me/ap-physics-c-mechanics/frqs/experimental-design)

## Overview

AP Physics C: Mechanics FRQ 3 is the experimental design question, worth 10 points and recommended for about 25-30 minutes. It asks you to design an investigation, analyze data with calculus-based methods, and connect results to mechanics models.

The Experimental Design and Analysis question assesses your ability to create sophisticated experimental procedures and analyze data using calculus-based techniques. You'll design experiments that could realistically determine unknown quantities, often involving continuous measurements or rates of change. The data analysis portion frequently requires linearization techniques, uncertainty propagation, or calculus-based fitting. This question bridges theoretical physics with experimental practice.

## Strategy Focus

Success on Experimental Design questions requires thinking like an experimental physicist who uses calculus as a natural tool for analysis.

**Designing Experiments with Continuous Variables**

Physics C experiments often involve quantities that vary continuously, requiring calculus thinking from the start:

- Instead of measuring position at discrete times, you might track position continuously and differentiate to find velocity
- Rather than measuring force at specific angles, you might measure torque as a function of angle and integrate to find work
- Instead of timing single oscillations, you might record position vs. time and fit to sinusoidal functions

When designing procedures, consider: "What quantity can I measure continuously that relates to what I want to find through calculus?"

**Linearization Strategies for Physics C**

While Physics 1 uses basic linearization, Physics C employs sophisticated techniques:

*Example 1 - Exponential Decay*:

For capacitor discharge V(t) = V₀e^(-t/RC), plotting ln(V) vs. t gives a line with slope -1/RC. This turns exponential behavior into linear behavior.

*Example 2 - Power Laws*:

For relationships like F = Ax^n, plotting ln(F) vs. ln(x) gives slope n and intercept ln(A). This determines both the power and the coefficient.

*Example 3 - Sinusoidal Motion*:

For damped oscillations x(t) = A₀e^(-γt)cos(ωt), the envelope of peaks follows exponential decay, allowing separate determination of damping and frequency.

**Uncertainty Analysis Using Calculus**

Physics C may require propagating uncertainties using partial derivatives:

For a calculated quantity f(x,y), the uncertainty is: δf = √\[(∂f/∂x)²(δx)² + (∂f/∂y)²(δy)²\]

Example: If measuring period T to find g from T = 2π√(L/g):

- Solve for g: g = 4π²L/T²
- Find uncertainties: δg/g = √\[(δL/L)² + (2δT/T)²\]
- Note how timing uncertainty is doubled in the final result

**Data Analysis Beyond Simple Averaging**

Physics C data analysis often involves:

- Fitting functions beyond straight lines (polynomials, exponentials, sinusoids)
- Weighted averaging when uncertainties vary
- Numerical differentiation or integration of data
- Residual analysis to validate model selection

## Common Experimental Scenarios

Certain experimental setups appear frequently, each with specific design considerations.

**Measuring Moment of Inertia**

Classic approaches with calculus connections:

*Method 1 - Oscillation*: Measure period of torsional oscillation

- T = 2π√(I/κ) where κ is torsion constant
- Plot T² vs. added mass to find I of system
- Calculus enters through analyzing angular SHM

*Method 2 - Rolling Down Incline*: Time descent down ramp

- a = g sin θ/(1 + I/MR²) for rolling without slipping
- Measure acceleration vs. angle
- Extract I from slope of linearized plot

*Method 3 - Torque and Angular Acceleration*: Apply known torque

- τ = Iα requires measuring α = dω/dt
- Could measure ω(t) and differentiate
- Or integrate α(t) and check against final ω

**Determining Spring "Constants" for Non-Linear Springs**

When F ≠ -kx, experiments must determine force laws:

*Design Elements*:

- Measure force vs. displacement continuously
- Plot F vs. x to identify functional form
- If F = -kx - βx³, need multiple measurements to separate terms
- Use potential energy U = ∫F dx to verify force law

*Analysis Approach*:

- Fit F(x) data to polynomial
- Differentiate U(x) if measured via energy methods
- Compare oscillation periods at different amplitudes
- For large oscillations, T depends on amplitude (non-isochronous)

**Projectile Motion with Air Resistance**

Advanced projectile experiments considering drag:

*Experimental Design*:

- Launch at various angles and speeds
- Record full trajectory (not just range)
- Measure terminal velocity separately

*Calculus Analysis*:

- Drag force F\_d = -bv or -cv² requires differential equation
- Numerical integration to predict trajectory
- Compare to measured path
- Extract drag coefficient from trajectory shape

## Detailed Rubric Breakdown

Understanding scoring helps you craft complete responses efficiently.

**Part (a): Experimental Design (3-4 points)**

**Procedure Clarity (2 points)**:

- Step-by-step instructions someone could follow
- Specifies all measurements needed
- Indicates equipment required (realistic for high school lab)
- Addresses multiple trials or continuous measurement

**Physics Soundness (1-2 points)**:

- Controls relevant variables
- Measures quantities that determine desired unknown
- Accounts for systematic errors
- Incorporates calculus relationships naturally

Common losses: Vague procedures ("measure the force"), unrealistic equipment ("perfect vacuum chamber"), missing repeated trials.

**Part (b): Analysis Method (2-3 points)**

**Mathematical Framework (1-2 points)**:

- Clear statement of how to process raw data
- Correct calculus relationships identified
- Linearization or fitting procedure explained
- Uncertainty propagation method if relevant

**Graphical Planning (1 point)**:

- Specifies what to plot vs. what
- Explains expected graph shape
- Indicates how to extract desired quantity from graph

Common losses: Saying "plot the data" without specifying axes, missing linearization steps, forgetting uncertainty analysis.

**Part (c): Data Analysis Implementation (4-5 points)**

**Graph Construction (2 points)**:

- Correct quantities on axes with units
- Appropriate scale using most of grid
- All data points plotted accurately
- Error bars if uncertainty given

**Calculation/Extraction (2-3 points)**:

- Best-fit line drawn appropriately
- Slope/intercept calculated correctly
- Conversion from graph parameter to physical quantity shown
- Final answer with correct units and reasonable significant figures

Common losses: Poor scale choice, missing units on axes, calculation errors, unreasonable significant figures.

## Advanced Experimental Techniques

These sophisticated approaches showcase deep understanding.

**Phase Space Analysis**

For oscillator experiments, plotting v vs. x creates phase space trajectories:

- SHM creates ellipses
- Damped motion spirals inward
- Driven systems show limit cycles
- Area of trajectory relates to energy

This representation reveals dynamics not obvious from x(t) or v(t) alone.

**Fourier Analysis Applications**

When measuring complex oscillations:

- Decompose into frequency components
- Identify fundamental and harmonics
- Measure Q-factor from resonance width
- Detect nonlinear behavior from harmonic generation

Calculator capability for FFT can be mentioned even if not executed.

**Feedback Control Systems**

Advanced experiments might involve:

- Maintaining constant temperature while measuring other quantities
- Servo systems to hold position while applying force
- Lock-in detection for weak signals
- PID control for stability

Mentioning these shows experimental sophistication.

## Time Management Strategy

With ~27 minutes total:

- **Minutes 1-3**: Read entire problem, identify experimental goal
- **Minutes 4-8**: Design experiment, write clear procedure
- **Minutes 9-12**: Explain analysis method with mathematical detail
- **Minutes 13-14**: Process given data (calculate needed quantities)
- **Minutes 15-21**: Create graph with care and precision
- **Minutes 22-25**: Extract result from graph, calculate final answer
- **Minutes 26-27**: Check reasonableness, verify units

If running behind, prioritize the graph - it's often worth the most points and shows understanding even if calculations are incomplete.

## Common Pitfalls and Solutions

**Over-Complicating Procedures** Keep experiments realistic. A simple, well-executed measurement beats an elaborate setup you can't fully describe. Focus on what a motivated high school lab could actually do.

**Forgetting Calculus Connections** In Physics C, experiments often measure rates or accumulated quantities. Always consider whether derivatives or integrals connect what you measure to what you want to find.

**Poor Graph Construction** Invest time in quality graphs:

- Use ruler/straight edge
- Make data points visible
- Choose scales showing all data clearly
- Label everything completely

A excellent graph can earn full credit even with minor calculation errors.

**Ignoring Uncertainty** Physics C expects error analysis. If uncertainties are given, propagate them. If not given, discuss major sources of error and how they'd affect results.

## Laboratory Intuition

Successful experimental design requires practical intuition:

- **Measurement Precision**: Position to ±1 mm is reasonable, ±0.01 mm is not
- **Time Scales**: Hand timing limits you to ±0.2 s, photogate can do ±0.001 s
- **Force Sensors**: Typically ±0.01 N resolution in school labs
- **Sampling Rates**: Video at 30-240 fps, sensors at 1-1000 Hz typically

Reference realistic capabilities to show experimental maturity.

## Final Thoughts

Experimental Design questions test whether you can bridge theoretical physics and practical measurement. The calculus in Physics C isn't just for solving textbook problems - it's the natural language for analyzing real experimental data.

Approach these problems like a physicist: What can I measure? How does it relate to what I want to know? What mathematical tools extract the information I need? Your experimental design should feel like a natural application of physics principles, with calculus as the tool that makes precise analysis possible.

Remember that good experiments are simple in concept but sophisticated in analysis. Let the physics guide your design, and let calculus extract maximum information from your measurements.

## Frequently Asked Questions

### How long is the experimental design FRQ on AP Physics C Mechanics?

FRQ 3 (Experimental Design and Analysis) is worth 10 points with a suggested time of 25-30 minutes. It's one of 4 free-response questions in the 100-minute Section II, which makes up 50% of your AP Physics C: Mechanics exam score.

### How is the AP Physics C Mechanics experimental design question scored?

It's worth 10 of the 40 FRQ points. Roughly 3 points come from a replicable procedure that varies one parameter and includes uncertainty-reduction steps, about 2 from describing the data analysis, about 3 from choosing linearizing quantities and graphing the given data with a best-fit line, and about 2 from calculating the physical quantity from the line's slope or intercept.

### What makes a good procedure on the AP Physics C lab FRQ?

A scoring procedure names realistic high school equipment (motion sensors, photogates, balances), states exactly what is measured and when, varies a single parameter while holding everything else constant, and explicitly includes uncertainty-reduction steps like multiple trials with averaging. Vague steps like 'measure the speed' lose points because the experiment can't be replicated.

### What is linearization on the AP Physics C Mechanics exam?

Linearization means rearranging a physics equation so that plotting two chosen quantities produces a straight line, with the unknown sitting in the slope or intercept. For example, if theory predicts h = J²/(2g) · (1/M²), plotting h versus 1/M² gives a line whose slope equals J²/(2g). You can practice this skill with [FRQ practice and instant scoring](https://fiveable.me/ap-physics-c-mechanics/frq-practice).

### How many FRQs are on the AP Physics C Mechanics exam?

There are 4 FRQs in 95 minutes, worth 50% of the score: Mathematical Routines (10 points), Translation Between Representations (12 points), Experimental Design and Analysis (10 points), and Qualitative/Quantitative Translation (8 points). They always appear in that order, so the lab question is always Question 3.

---

<sub>Source: [https://fiveable.me/ap-physics-c-mechanics/ap-physics-c-mechanics-exam/ap-physics-c-mechanics-frq-experimental-design/study-guide/ap-physics-c-mechanics-frq-experimental-design](https://fiveable.me/ap-physics-c-mechanics/ap-physics-c-mechanics-exam/ap-physics-c-mechanics-frq-experimental-design/study-guide/ap-physics-c-mechanics-frq-experimental-design)</sub>
