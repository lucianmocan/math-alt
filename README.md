# Math-Alt Library

A simple mathematics library for the Alt programming language, providing basic algebraic and trigonometric functions.

## Features

### Algebra Module
- **Basic Operations**: Addition, subtraction, multiplication, division
- **Power Operations**: Exponentiation, square, square root
- **Equation Solving**: Linear and quadratic equations

### Trigonometry Module
- **Angle Conversion**: Degrees to radians and vice versa
- **Trigonometric Functions**: Sine, cosine, tangent (with degree and radian versions)
- **Inverse Functions**: Arcsine, arccosine, arctangent
- **Geometric Calculations**: Pythagorean theorem, distance, triangle area

## Usage

```alt
import Math from "math.alt";

// Basic algebra
result = Math.add(5, 3);  // 8
solution = Math.solve_linear(2, 4);  // x = -2 for 2x + 4 = 0

// Trigonometry
sin_value = Math.sin_deg(30);  // 0.5
distance = Math.distance(0, 0, 3, 4);  // 5
```

## File Structure

```
math-alt/
├── alt.toml              # Project configuration
├── math.alt              # Main library file
├── examples.alt          # Usage examples
├── algebra/
│   └── basic.alt         # Algebraic functions
└── trigonometry/
    └── basic.alt         # Trigonometric functions
```

## Educational Purpose

This library is designed for learning. Each function includes:
- Mathematical explanations
- Domain and range information
- Common use cases
- Error handling for edge cases

## Examples

See `examples.alt` for comprehensive usage examples of all functions.
