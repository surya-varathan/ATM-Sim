# ATM-Sim

### Problem Statement

  A simple banking system built using Java programming language for a customer (which can either be a company or an individual) can open an account with type as
premium or non-premium, deposit money and withdraw it later. The system can also generate customer reports.

### Design Pattern

The initial code had no prevalent design pattern. As a part of the refactoring process, design principles were applied. For the customer creation, where a customer can either be an individual person or a company, Factory Pattern has been applied. Factory Method is a creational design pattern that provides an interface for creating objects in a superclass, but allows subclasses to alter the type of objects that will be created.

### Quality Metrics

SonarCloud was chosen to perform quality metrics analysis. For the initial code, 9 code smells were identified by tool (some smells included were mere renaming and moving packages) and the code duplication was around 1.1%. The metrics from the SonarCloud dashboard are shown in the below screenshot.

### Code Smells and Appropriate Refactoring

1. Duplicated Code - Extract method
2. Long Method - Extract method
3. Switch Statements - Replace conditional with polymorphism
4. Feature Envy and Inappropriate Intimacy - Move methods
5. Primitive Obsession and Data Clumps - Extract class, Introduce Parameter object
6. Lazy Class - Inline class
7. Divergent Change - Extract class

### Interpretation

A new design principle has been incorporated and code smells have been significantly reduced to zero for better maintainability. Code duplications have also been cut to zero percent.





### Contributors

[Sanjay Kumar S](https://github.com/ssk-14)

[Surya Varathan M](https://github.com/surya-varathan)
