---
layout: post
title:  "SOLID Design Principles"
date:   2020-06-12 11:57:00 +0100
categories: design
excerpt: A quick reminder of the SOLID design principles
---

# What is SOLID?

SOLID design principles provide some guidelines for designing robust and maintainable software systems.

The subject is discussed in detail here: [SOLID Design Principles](https://stackify.com/solid-design-principles/). But here's a quick summary..

## What does the SOLID acronym stand for?

- **S**ingle Responsibility Principle
- **O**pen/Closed Principle
- **L**iskov Subsitution
- **I**nterface Segregation
- **D**ependency Inversion

## Single Responsibility Principle (sometimes known as SRP)

This specifies that a code object (class, method etc.) should have only one purpose and therefore should have only one reason to change.

## Open/Closed Principle

Objects should closed for modification but open for extension.

## Liskov Substitution

You should be able to replace objects of a superclass with objects of a subclass and your application should still function correctly.

## Interface Segration

Classes should not be compelled to implement functionality they don't need.

This can happen when interfaces are modified over time and functions are added that only some of the implementing classes require. This results in classes being forced to provide implementations for methods that are not appropriate to them.

## Dependency Inversion

Otherwise known as Inversion of Control and often implemented using Dependency Injection, this principle specifies that methods are given what they need (their dependencies) rather than having to reach out to get them.










