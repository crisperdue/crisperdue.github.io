# The Design of the Mathtoys Proof Assistant

### Abstract

Mathtoys is a web application designed and built to serve mathematics education.
It is implemented in JavaScript to run in Web browsers, with a modern, highly interactive
graphical Web user interface.

Its logic is a form of Church's type theory, with type variables being part of the metatheory.
In place of supporting definition of new types, Mathtoys provides for similarly defining new
sorts of individuals, which are not necessarily disjoint from other sorts.

Interactivity and web worker processes.

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
- User-selectable "algebra mode"
- Feedback to the user
  - Hover highlighting
  - Solution status

## Logic

- Church's simple type theory
- Minimal, Peter Andrews version with only type schemas
- Otherwise no schemas, just variables
- Function and predicate variables
- Hilbert-style deduction
- Support definitions as abbreviations
- Also definitions justified by existence

## Challenge: presenting the logic to the user

- Make presence of logical types essentially invisible
- Naming conventions for variables, adjustable per proof
- Implicit equivalences
- Ellipsis in step displays

## Axiomatics

- Ordered field axioms
- Bottom element

## Presentation of logic to the user

- Rewriting, including "= T"
- Fine-grain management of assumptions
- Automatic simplification
- Automatic mgmt of math types (closure of operations)
- Enough higher-order matching to support e.g. forall {x. p} vs. forall {x. p x}

## System implementation

- Kernel
- Optimized for working with individuals, functions and predicates on individuals
- Client-side JavaScript

## Use of JavaScript

- Expression trees
- Hash maps with string keys

## 

