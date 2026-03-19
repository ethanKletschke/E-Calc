# E-Calc

An ISO Extended Backus-Naur Form (EBNF) specification for calculations and
assignment expressions.

- Author: Ethan Kletschke
- Version: `0.0.5`
- Developed on: Ubuntu (WSL2)
- License: MIT

## Current Definitions

E-Calc currently defines:

- The alphabet from A-Z (uppercase and lowercase)
- The digits 0-9
- Signs (`+` and `-`)
- Integers with optional signs
- Simple assignment of values to variables (RHS assigned to LHS, or `lhs = rhs`)
- Arithmetic operators

## Limitations

- E-Calc only supports single binary operations (for now)
- E-Calc has no parentheses or BODMAS precedence (yet)
