# C++ expression parsing.<br>
Expression parsing in C++ with Dijkstra's

## Features.
 + Unary operators. +, -
 + Binary operators. +, -, /, +, <<, >>
 + Map of variable names.

## Adding a binary operator.
To add a binary operator,

 1. Update the operator precedence map in `calculator::calculate`.
 2. Add the computation to `calculator::consume`.
