---
layout: post
title: "Liskov's Principle Applied to Rectangle v. Square"
---

The following post explores all the possible reasons that Rectangles are not Squares in the OOP world. 

# Liskov's Principle
Liskov's principle applies that since a Square is a child of a Rectangle, it can be a variation of the Rectangle class.
However, it cannot modify the Rectangle class. When created, a square tends to change the instances of the Rectangle class
by not accepting both width and height at different values. This rejects the supposedly different values that the Rectangle class
has set for it's instances. Therefore it creates a logical misconception that a Square cannot be a child of a Rectangle and rather
should be treated as a sibling of Rectangle by being inherited by the parent class Quadrilateral because both of them are
clearly Quadrilaterals and do not have to modify their elements to fit the definition of a quadrilateral.
