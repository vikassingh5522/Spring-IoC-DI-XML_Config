Inversion of Control (IoC): The framework manages the creation and lifecycle of objects (beans). Developers define how objects are wired together, and the Spring IoC container handles instantiation and dependency injection.
2.
Dependency Injection (DI): Dependencies are injected into objects externally (via constructors, setters, or fields) rather than objects creating their own dependencies, promoting loose coupling.
3.
Aspect-Oriented Programming (AOP): Separates cross-cutting concerns (e.g., logging, security) from business logic by applying them modularly.
4.
Modularity: Spring is divided into modules, allowing developers to use only the components they need.

=====================================
Inversion of Control (IoC) and Dependency Injection (DI):
Inversion of Control (IoC) and Dependency Injection (DI) are core principles of the Spring Framework that promote loose coupling, modularity, and easier testing in applications.
what is loose and tight coupling?
Loose coupling and tight coupling are concepts in software engineering that describe the degree of dependency between components, classes, or modules in a system. These terms are particularly relevant in the context of object-oriented programming, design patterns, and frameworks like Spring, where principles like Inversion of Control (IoC) and Dependency Injection (DI) aim to achieve loose coupling.
Tight Coupling
Definition: Tight coupling occurs when two or more components (e.g., classes, modules) are highly dependent on each other, such that a change in one component directly affects the other. In tightly coupled systems, components often have direct knowledge of each other’s implementation details.
Characteristics:
•
Components directly create or instantiate their dependencies.
•
Classes reference concrete implementations rather than abstractions (e.g., interfaces or abstract classes).
•
Changes to one component (e.g., renaming a method, changing a class’s structure) often require changes in dependent components.
•
Difficult to test because dependencies are hardcoded, making it hard to mock or replace them.
Drawbacks:
•
Reduced flexibility: Hard to swap or modify components without affecting others.
•
Poor maintainability: Changes ripple through the system, increasing maintenance effort.
•
Difficult testing: Unit tests require the real dependency, which may involve complex setup or external resources.
•
Code is less reusable because components are tied to specific implementations
