---
layout: post
title: Functional Interfaces for Lambdas
---

# Functional Interfaces for Lambdas

### What is a lambda?
A lambda is an expression used in Java to support functional programming. The exact definition of a lambda would be an anonymous function / expression
that is not bound by any identifier.

### What is a functional interface?
A functional interface is one that is created for only one, singular, sole purpose.

### How do they connect?
A lambda is a way to create an instance of a functional interface. It can only take in reference variables of the functional interface that it is created for. When using lambdas, single abstract method (SAM) interfaces tend to start acting like classes. You are allowed to make instances and objects out of them.
