# Designing the Mathtoys Proof Assistant for Wide Use

### Abstract

Wide use: 

- user interface
- problem domain
- underlying logic
- axiomatics
- problem-solving approach

## User interface

- Web-based
- Highly interactive
- Selection

## User interaction style

- User drives (selects strategy)
- Computer implements clerical steps

## Logic

- Church's simple type theory
- Minimal, Peter Andrews version with only type schemas
- Hilbert-style deduction
- Support definitions as abbreviations
- Also definitions justified by existence

## Challenge: presenting logic types to the user

- Make presence of logical types essentially invisible
- Naming conventions for variables, adjustable per proof

## Axiomatics

- Hilbert-style system
- Actual variables, not schemas


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


