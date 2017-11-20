# Designing the Mathtoys Proof Assistant for Wide Use

### Abstract

Wide use: 

- user interface
- problem domain
- underlying logic
- axiomatics
- problem-solving approach

## Role of the assistant

- User drives (selects strategy)
- Computer implements clerical steps

## User interface

- Web-based
- Highly interactive
- Hovers
- Selection
- Menu sensitive to selection
- Step suggestion for each menu item

## Logic

- Church's simple type theory
- Minimal, Peter Andrews version with only type schemas
- Otherwise no schemas, just variables
- Function and predicate variables
- Hilbert-style deduction
- Support definitions as abbreviations
- Also definitions justified by existence

## Challenge: presenting logic types to the user

- Make presence of logical types essentially invisible
- Naming conventions for variables, adjustable per proof

## Axiomatics

- Ordered field axioms
- Bottom element

## Presentation of logic to the user

- Rewriting, including "= T"
- Fine-grain management of assumptions
- Automatic simplification
- Automatic mgmt of math types (closure)


## System implementation

- Kernel
- Optimized for working with individuals, functions and predicates on individuals
- Client-side JavaScript

## Use of JavaScript

- Expression trees
- Hash maps with string keys


