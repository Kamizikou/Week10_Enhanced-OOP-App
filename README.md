# PC16 – Week 10: Object-Oriented Programming in Dart

- **Student Name:** Caday, Ismael Haven R,
- **Year & Section:** 3.3 - BSIT
- **Course:** NTC_PC16 – Mobile Development w/ Lab

---

## Description
This Dart application models a vehicle hierarchy and diagnostic system built using advanced Object-Oriented Programming (OOP) concepts[cite: 1]. It builds upon core OOP foundations by implementing class inheritance, method overriding (polymorphism), abstract class contracts, and mixin compositions outside the main inheritance chain[cite: 1].

---

## Features & Rubric Alignment

- **Base Class (`Vehicle`):** Encapsulates core properties (`_brand`, `_speed`) using private fields, getters, setters, and base behaviors[cite: 1].
- **Inheritance & Derived Classes (`ElectricCar`, `Motorcycle`):** Extends the `Vehicle` base class using `extends` to share common logic across specialized types[cite: 1, 2].
- **Polymorphism:** Overrides base methods (`start()`, `displayInfo()`) using `@override` in derived classes to exhibit type-specific behavior[cite: 1, 2].
- **Abstract Class / Interface (`Startable`):** Defines a strict operational contract containing abstract `start()` and `stop()` signatures implemented by `Vehicle`[cite: 1, 2].
- **Mixin (`DiagnosticLogger`):** Applies shared logging capabilities using `with` to a standalone `ServiceInspector` class outside the main `Vehicle` inheritance chain[cite: 1, 2].

---

## 🚀 How to Run

### Steps:
- Open dartpad.dev
- Copy & Paste the code from Week10_Enchanced_OOP_App_Code
- run
