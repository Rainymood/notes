.. |checkbox| raw:: html

    <input type="checkbox">


Code review checklist
=====================

Purpose

  The primary purpose of code review is to make sure **that the overall code health
  of the code base is improving over time.** All of the tools and processes of
  code review are designed to this end. In order to accomplish this, a series of
  trade-offs have to be balanced.

Joy

* |checkbox| Does the code spark joy?

Requirements

* |checkbox| Does the code satisfy the requirements?

Design

* |checkbox| Does the code follow the Single Responsibility Principle (SRP)?
* |checkbox| Is data (input/output) pushed to the boundaries
* |checkbox| Is dependency injection (DI) followed? 

Maintainability

* |checkbox| Is the code easy to read & follow?
* |checkbox| Are the variable/class names clear and don't lie?
* |checkbox| Is there code duplication? 

Testing

* |checkbox| Is there an integration test for a new use case? 
* |checkbox| Is all new logic unit tested?
* |checkbox| Are all edge cases tested?

Documentation

* |checkbox| Is the `README` updated?

Code smells (optional)

* |checkbox| No `thing.save()`. Prefer using a `Saver`. Apply DIP.
* |checkbox| No paths being passed in. Prefer IO on the boundary. Apply DIP. 