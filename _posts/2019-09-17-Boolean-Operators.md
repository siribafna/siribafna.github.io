---
layout: post
title: Boolean Operators
---

The following are 16 boolean operators commonly used in the logic of programming.

 # Contradiction

 a | b | a ⊥ b
--- | --- | ---
*True* | True | False
*False* | True | False
True | False | False
False | False  | False

 # Logical NOR

 a | b | a ↓ b
--- | --- | ---
*True* | True | False
*False* | True | False
True | False | False
False | False  | True

# Converse Nonimplication

 a | b | a ↚ b
--- | --- | ---
*True*  |  True  |  False
*False*  |  True  |  False
True  |  False  |  True
False  |  False   |  False

# Negation

 a | b | ¬a
--- | --- | ---
*True* | True | False
*False* | True | False
True | False | True
False | False  | True

# Material Nonimplication

 a | b | a ↛ b
--- | --- | ---
*True* | True | False
*False* | True | True
True | False | False
False | False  | False

# Negation flipped

 a | b | ¬b
--- | --- | ---
*True* | True | False
*False* | True | True
True | False | False
False | False  | True

# Exclusive Disjunction

 a | b | a ⊕ b
--- | --- | ---
*True* | True | False
*False* | True | True
True | False | True
False | False  | False

# Logical NAND

 a | b | a ↑ b
--- | --- | ---
*True* | True | False
*False* | True | True
True | False | True
False | False  | True

# Logical Conjunction

 a | b | 	a ∧ b
--- | --- | ---
*True* | True | True
*False* | True | False
True | False | False
False | False  | False

# Logical Biconditional (p if and only q)

 a | b | XNOR
--- | --- | ---
*True* | True | True
*False* | True | False
True | False | False
False | False  | True

# Projection Function (p, l pq)

 a | b | b
--- | --- | ---
*True* | True | True
*False* | True | False
True | False | True
False | False  | False

# Material Implication (if p then q)

 a | b | a → b
--- | --- | ---
*True* | True | True
*False* | True | False
True | False | True
False | False  | True

# Projection Function (2)

 a | b | a
--- | --- | ---
*True* | True | True
*False* | True | True
True | False | False
False | False  | False

# Conversion Implication (p if q)

 a | b | a ← b
--- | --- | ---
*True* | True | True
*False* | True | True
True | False | False
False | False  | True

# Logical Disjunction (p v q)

 a | b | a || b
--- | --- | ---
*True* | True | True
*False* | True | True
True | False | True
False | False  | False

# Tautology  (V pq)

 a | b | Vab
--- | --- | ---
*True* | True | True
*False* | True | True
True | False | True
False | False  | True
