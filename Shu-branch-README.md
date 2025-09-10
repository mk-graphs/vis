# Interactive 2D Visualizations with JSXGraph

This project contains 31 interactive 2D visualizations created using JSXGraph technology. Each visualization demonstrates mathematical and scientific concepts through dynamic, interactive graphics that help users understand complex topics through hands-on exploration.

## Project Overview

The visualizations are organized into 7 categories, covering topics from basic mathematics to advanced physics and applied sciences. Each interactive demonstration includes:
- Real-time parameter adjustment through sliders
- Dynamic visual feedback
- Educational explanations and formulas
- Interactive quizzes and practice questions
- Mathematical notation rendered with MathJax

## Categories and Visualizations

### 1. Basic Mathematics & Functions (01-05, 30)

#### 01. Dynamic Function Graphs
This interactive visualization lets you explore the behavior of different types of mathematical functions: linear, quadratic, and sine. It goes beyond a static graph by including dynamic elements that help you visualize how a function's output (y) changes as its input (x) varies.

**Key Features:**
- **Function Selection**: Use the dropdown menu to switch between three function types:
  - Linear: y = ax + b
  - Quadratic: y = ax² + b
  - Sine: y = A·sin(Bx)
- **Interactive Sliders**: The sliders allow you to instantly change the values of the coefficients (a, A, b, and B) and see how the changes affect the shape, slope, amplitude, or frequency of the graph in real-time.
- **Moving Points**: A set of small, moving points travel along the function's curve. This visual cue helps to demonstrate the continuous nature of the function and how the y-value is always directly linked to the x-value.
- **Mouse Tracking**: When you hover your mouse over the graph, a red point follows the curve, displaying the exact coordinates (x,y) at that position. This provides a precise way to inspect specific points on the function.
- **Interactive Quiz**: A short quiz at the bottom of the page challenges you to apply your understanding of the sine function's properties (amplitude and period) by finding the correct slider values.

#### 02. Interactive Parabola
This visualization explores the quadratic function y = ax² + bx + c, allowing you to understand how each parameter affects the parabola's shape and position.

**Key Features:**
- **Three-Parameter Control**: Adjust parameters a, b, and c independently to see their effects
- **Real-time Equation Display**: The current equation is shown and updates as you move the sliders
- **Vertex Tracking**: The vertex of the parabola is highlighted and labeled with its coordinates
- **Axis of Symmetry**: A dashed line shows the parabola's axis of symmetry
- **Educational Questions**: Multiple-choice questions test understanding of parameter effects
- **Detailed Explanations**: Step-by-step solutions explain the mathematical reasoning

#### 03. Tangent Line to a Circle
This geometric visualization demonstrates the fundamental relationship between a circle's radius and its tangent line.

**Key Features:**
- **Draggable Point**: Move a point around the circle to see how the tangent changes
- **Perpendicular Relationship**: Visual demonstration that the tangent is always perpendicular to the radius
- **Dynamic Angle Display**: Shows the 90° angle between radius and tangent
- **Interactive Learning**: Drag the point to explore different positions and observe the geometric relationships

#### 04. Pendulum Motion and Cosine Function
This dual-panel visualization connects the mathematical cosine function with the physical motion of a pendulum.

**Key Features:**
- **Side-by-Side Comparison**: Function graph on the left, animated pendulum on the right
- **Parameter Control**: Adjust amplitude (A) and frequency (B) to see effects on both the function and pendulum motion
- **Real-time Animation**: Watch the pendulum swing while observing the corresponding cosine curve
- **Mathematical Connection**: Demonstrates how d(t) = A·cos(Bt) describes pendulum motion
- **Educational Problem**: Practice question about calculating the period of pendulum motion

#### 05. Intersection of Function Graphs
This visualization explores the intersection points between a quadratic function (f(x) = x²) and a linear function (g(x) = mx + c).

**Key Features:**
- **Dynamic Linear Function**: Adjust slope (m) and intercept (c) of the linear function
- **Real-time Intersection Detection**: Automatically finds and highlights intersection points
- **Numerical Methods**: Uses bisection method to accurately locate intersection points
- **Visual Feedback**: Green points mark the exact intersection locations
- **Mathematical Understanding**: Helps visualize solutions to x² = mx + c

#### 30. Fractal Tree Recursion Visualization
This animated visualization demonstrates recursion concepts through the growth of a fractal tree.

**Key Features:**
- **Recursion Concept**: Visualizes how parent branches generate child branches recursively
- **Interactive Parameters**: Adjust branch angle, length scale, and recursion depth
- **Animated Growth**: Watch the tree grow branch by branch with smooth animation
- **Mathematical Formula**: Shows the formula for calculating total branches in recursive structures
- **Educational Quiz**: Practice calculating branch counts using recursive formulas

### 2. Calculus & Advanced Mathematics (06-10)

#### 06. Antiderivative Visualization
This visualization demonstrates the relationship between a function and its antiderivative, showing how the constant of integration affects the family of antiderivatives.

**Key Features:**
- **Function Pair Display**: Shows both the original function f(x) = 2x + 1 and its antiderivative F(x) = x² + x + C
- **Constant Slider**: Adjust the constant C to see how it shifts the antiderivative vertically
- **Mathematical Explanation**: Detailed explanation of antiderivative concepts and formulas
- **Interactive Quiz**: Practice calculating antiderivative values with feedback

#### 07. Riemann Sums Visualization
This visualization demonstrates the concept of Riemann sums for approximating definite integrals, with both mathematical and real-world examples.

**Key Features:**
- **Two Examples**: Mathematical (f(x) = x²) and real-world (car velocity function)
- **Adjustable Parameters**: Change interval bounds (a, b) and number of rectangles (n)
- **Real-time Approximation**: Shows the sum of rectangle areas as an approximation of the integral
- **Visual Rectangles**: Colored rectangles show the approximation method
- **Educational Quiz**: Question about interpreting area under velocity-time graphs

#### 08. Logarithm Graph
This visualization explores the relationship between exponential and logarithmic functions, demonstrating their inverse nature.

**Key Features:**
- **Inverse Function Display**: Shows both exponential (y = b^x) and logarithmic (y = log_b(x)) functions
- **Base Control**: Adjust the base b to see how it affects both functions
- **Symmetry Demonstration**: Visual proof that the functions are symmetric about y = x
- **Compression Effect**: Demonstrates how logarithms compress large ranges of values
- **Educational Content**: Detailed explanation of inverse function properties

#### 09. Application of Logarithmic Functions in Investment Returns
This practical application shows how logarithms simplify complex compound growth calculations in finance.

**Key Features:**
- **Two Calculation Methods**: Compare exact exponential method with logarithmic approximation
- **Interactive Parameters**: Adjust principal, final amount, and time period
- **Real-time Comparison**: See both exact and approximate rates of return
- **Growth Curves**: Visual representation of investment growth over time
- **Practice Problems**: Financial calculation problems with detailed solutions

#### 10. Binary Visualizer
This interactive tool helps understand the relationship between binary and decimal number systems.

**Key Features:**
- **8-Bit Visualization**: Interactive buttons representing 8 binary digits
- **Dual Input Methods**: Click buttons or enter decimal numbers
- **Place Value Display**: Shows the power of 2 for each bit position
- **Real-time Conversion**: Instant conversion between binary and decimal
- **Educational Quiz**: Practice converting binary numbers to decimal

### 3. Statistics & Probability (11-13)

#### 11. Binomial Distribution
This visualization demonstrates the binomial probability distribution, showing how parameters n and p affect the shape of the distribution.

**Key Features:**
- **Parameter Control**: Adjust number of trials (n) and success probability (p)
- **Bar Chart Display**: Visual representation of probability mass function
- **Real-time Updates**: Distribution changes immediately as parameters are adjusted
- **Mathematical Formula**: Shows the binomial probability formula
- **Practice Problems**: Applied problems with detailed solutions

#### 12. Forgetting Curve in Language Learning
This visualization demonstrates the Ebbinghaus forgetting curve and how review strategies affect memory retention.

**Key Features:**
- **Three Learning Scenarios**: No review, weekly review, and daily review
- **Parameter Control**: Adjust forgetting rate and review effectiveness
- **Multiple Curves**: Compare different review strategies visually
- **Memory Retention Display**: Shows percentage retention over time
- **Educational Insights**: Demonstrates the power of spaced repetition

#### 13. Forgetting Curve Real Example
This practical application simulates learning 10 Finnish words over 30 days with interactive review scheduling.

**Key Features:**
- **Interactive Review Grid**: Click days to schedule reviews
- **Real-time Memory Curve**: Shows how memory retention changes with reviews
- **Mathematical Formula**: Explains the exponential decay formula R(t) = e^(-λt)
- **Strategy Testing**: Compare different review strategies
- **Educational Question**: Determine the best review strategy for maximum retention

### 4. Physics & Motion (14-18, 28, 31)

#### 14. Basketball Shot Parabola Simulation
This simulation demonstrates projectile motion using a basketball shot scenario.

**Key Features:**
- **Parameter Control**: Adjust initial velocity and shot angle
- **Real-time Animation**: Watch the basketball follow its parabolic trajectory
- **Hit Detection**: Determines if the shot hits the hoop
- **Trajectory Display**: Shows the complete parabolic path
- **Educational Problems**: Mathematical analysis of projectile motion

#### 15. Stone Hit Moving Drone Simulation
This advanced projectile motion simulation involves hitting a moving target.

**Key Features:**
- **Moving Target**: Drone moves horizontally at constant speed
- **Collision Detection**: Determines if the stone hits the drone
- **Parameter Control**: Adjust initial velocity and launch angle
- **Real-time Animation**: Watch both stone and drone movement
- **Mathematical Analysis**: Calculate maximum height and collision conditions

#### 16. Tangent and Inertia
This visualization demonstrates the relationship between circular motion, tangent lines, and inertia.

**Key Features:**
- **Animated Car**: Car moves in uniform circular motion
- **Dynamic Tangent Line**: Shows the car's instantaneous velocity direction
- **Perpendicular Relationship**: Demonstrates radius perpendicular to tangent
- **Inertia Concept**: Visual representation of how objects want to move in straight lines
- **Educational Content**: Explains the physics of circular motion

#### 17. Time Dilation Special Relativity
This simulation demonstrates gravitational time dilation using the Interstellar movie scenario.

**Key Features:**
- **Two Clock Display**: Shows time passing differently for different observers
- **Distance Control**: Move Miller's Planet closer to or farther from the black hole
- **Real-time Animation**: Watch clocks tick at different rates
- **Mathematical Formula**: Shows the time dilation formula
- **Educational Content**: Explains the physics of general relativity

#### 18. Black Hole Gravitational Lensing
This visualization demonstrates how black holes bend light through gravitational lensing.

**Key Features:**
- **Multiple Light Rays**: Shows several light rays bending around the black hole
- **Mass Control**: Adjust the black hole's mass to see its effect on light bending
- **Starfield Background**: Creates an immersive space environment
- **Mathematical Formula**: Shows the bending angle formula
- **Practice Problems**: Calculate mass and impact parameters

#### 28. Realistic Rain Simulation
This physics simulation demonstrates free fall motion and uniform distribution through animated raindrops.

**Key Features:**
- **Physics Concepts**: Demonstrates gravitational acceleration and free fall motion
- **Mathematical Distribution**: Shows uniform distribution for raindrop positioning
- **Interactive Controls**: Start, pause, and reset the rain simulation
- **Real-time Animation**: Watch raindrops fall with increasing velocity due to gravity
- **Educational Quiz**: Test understanding of physics and mathematical concepts

#### 31. Temperature Heat Visualization
This physics visualization demonstrates temperature changes and heat transfer during rainfall events.

**Key Features:**
- **Physics Concepts**: Shows specific heat capacity of water and heat transfer
- **Real-time Simulation**: Displays temperature changes over time during rainfall
- **Interactive Controls**: Adjust temperature drop and control simulation timing
- **Mathematical Formulas**: Demonstrates Q = c·m·ΔT heat transfer equation
- **Educational Quiz**: Test understanding of specific heat capacity concepts

### 5. Music & Sound (19-21)

#### 19. Guitar Strings Harmonic Visualization
This visualization demonstrates the physics of guitar string harmonics and how they create timbre.

**Key Features:**
- **Harmonic Display**: Shows fundamental frequency and harmonics
- **Frequency Control**: Adjust the fundamental frequency
- **Audio Playback**: Hear individual harmonics and combined sound
- **Wave Visualization**: Shows individual and combined wave shapes
- **Educational Quiz**: Test understanding of timbre and harmonics

#### 20. Piano Key Frequencies Visualization
This visualization shows the relationship between piano key numbers and their frequencies.

**Key Features:**
- **88 Keys Display**: Shows all piano keys with their frequencies
- **Interactive Selection**: Click or use slider to select specific keys
- **Audio Playback**: Hear the selected note
- **Mathematical Formula**: Shows the equal temperament formula
- **Educational Content**: Explains the 12-tone equal temperament system

#### 21. Kaleidoscope Symmetry Visualization
This artistic visualization demonstrates geometric symmetry and transformations.

**Key Features:**
- **Interactive Pattern**: Move mouse to create aurora-like patterns
- **Symmetry Control**: Adjust the number of mirror lines (symmetry order)
- **Mathematical Transformations**: Demonstrates reflection and rotation
- **Educational Content**: Explains symmetry and geometric transformations
- **Practice Problems**: Calculate rotation angles and coordinates

### 6. Economics & Social Sciences (22-25, 27)

#### 22. Compound Effect of Habits
This visualization demonstrates how small daily changes compound over time.

**Key Features:**
- **Dual Curves**: Shows both improvement and decline scenarios
- **Parameter Control**: Adjust daily improvement and decline rates
- **One-Year Timeline**: Shows effects over 365 days
- **Mathematical Formula**: Demonstrates compound growth
- **Educational Insights**: Shows the power of small consistent actions

#### 23. Diminishing Marginal Utility
This economic visualization demonstrates the concept of diminishing marginal utility using a hamburger consumption example.

**Key Features:**
- **Utility Function**: Shows total utility as a function of consumption
- **Parameter Control**: Adjust maximum satisfaction and growth rate
- **Mathematical Formula**: Shows the exponential utility function
- **Educational Content**: Explains the law of diminishing marginal utility
- **Practice Questions**: Test understanding of economic concepts

#### 24. Weibull Survival Function
This statistical visualization demonstrates survival analysis using the Weibull distribution.

**Key Features:**
- **Parameter Control**: Adjust shape (β) and scale (λ) parameters
- **Survival Curve**: Shows probability of survival over time
- **Median Survival**: Highlights the 50% survival point
- **Age Slider**: See survival probability at different ages
- **Educational Content**: Explains survival analysis concepts

#### 25. Muscle Gain Beats Dieting for Metabolism
This health science visualization demonstrates how muscle mass affects basal metabolic rate.

**Key Features:**
- **Personalized Input**: Enter age, gender, weight, height, and activity level
- **BMR Calculation**: Shows basal metabolic rate using Mifflin-St Jeor equation
- **Muscle Impact**: Drag point to see how muscle changes affect metabolism
- **Real-time Updates**: Calculations update as parameters change
- **Educational Content**: Explains the relationship between muscle and metabolism

#### 27. Coffee Intake Comparison
This visualization compares annual coffee consumption between personal intake, Finland average, and world average using animated falling blocks.

**Key Features:**
- **Personal Input**: Enter your daily coffee consumption in cups
- **Animated Comparison**: Watch blocks fall to represent annual coffee bean consumption
- **Three Categories**: Compare your consumption with Finland (8.5 cups/day) and world average (5.5 cups/day)
- **Mathematical Calculations**: Converts cups to kilograms using 8g beans per cup
- **Educational Quiz**: Practice problems about coffee consumption calculations

### 7. Communication & Learning (26, 29)

#### 26. Morse Code Game
This interactive game teaches Morse code through visual and audio feedback.

**Key Features:**
- **Interactive Learning**: Click letters to hear and see their Morse code
- **Quiz Mode**: Guess the word from Morse code signals
- **Speed Control**: Adjust playback speed for practice
- **Audio Feedback**: Hear the beep sounds for dots and dashes
- **Educational Content**: Learn Morse code through interactive practice

#### 29. Reading Speed Simulator
This simulation compares reading speeds between different types of readers, visualizing eye movement patterns.

**Key Features:**
- **Personal Input**: Enter your reading speed in words per minute
- **Comparative Analysis**: Compare with native speaker (250 wpm) and non-native speaker (150 wpm) speeds
- **Eye Movement Visualization**: Watch animated points move across lines representing reading progress
- **Research-Based Data**: Uses 2019 meta-analysis data for average reading speeds
- **Educational Quiz**: Calculate reading times for classic literature

## Technical Details

### Technology Stack
- **JSXGraph**: Primary visualization library for 2D mathematical graphics
- **MathJax**: Mathematical notation rendering
- **Tone.js**: Audio synthesis for music and sound visualizations
- **HTML5/CSS3/JavaScript**: Frontend implementation

### Features
- **Responsive Design**: Works on desktop and tablet devices
- **Interactive Controls**: Sliders, buttons, and mouse interactions
- **Real-time Updates**: Immediate visual feedback for parameter changes
- **Educational Content**: Explanations, formulas, and practice problems
- **Cross-browser Compatibility**: Works in modern web browsers

## Usage

1. Open any HTML file in a modern web browser
2. Use the interactive controls (sliders, buttons, mouse) to explore the visualization
3. Read the educational content and explanations
4. Try the practice problems and quizzes
5. Experiment with different parameters to deepen understanding

## Educational Value

These visualizations are designed for:
- **Students**: Learning mathematical and scientific concepts.
- **Teachers**: Demonstrating abstract concepts in the classroom.
- **Self-learners**: Exploring topics independently.
- **Researchers**: Visualizing mathematical relationships.

Each visualization combines theoretical understanding with practical application, making complex concepts accessible through interactive exploration.