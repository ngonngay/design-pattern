# Design Patterns to Learn for Expertise

## 1. **Creational Patterns**
Creational patterns deal with object creation mechanisms, trying to create objects in a manner suitable to the situation.

- **Singleton**: Ensures a class has only one instance and provides a global point of access to it.
- **Factory Method**: Defines an interface for creating an object but lets subclasses alter the type of objects that will be created.
- **Abstract Factory**: Provides an interface for creating families of related or dependent objects without specifying their concrete classes.
- **Builder**: Separates the construction of a complex object from its representation, allowing the same construction process to create different representations.
- **Prototype**: Creates new objects by copying an existing object, known as the prototype.

## 2. **Structural Patterns**
Structural patterns deal with object composition, helping to ensure that objects and classes are combined in a way that benefits the system.

- **Adapter**: Allows incompatible interfaces to work together by wrapping an existing class with a new interface.
- **Bridge**: Decouples an abstraction from its implementation so that the two can vary independently.
- **Composite**: Composes objects into tree structures to represent part-whole hierarchies.
- **Decorator**: Adds new functionality to an object dynamically without altering its structure.
- **Facade**: Provides a simplified interface to a complex subsystem, hiding the system's complexity from the user.
- **Flyweight**: Reduces the cost of creating and managing a large number of objects by sharing common data.
- **Proxy**: Provides a surrogate or placeholder for another object to control access to it.

## 3. **Behavioral Patterns**
Behavioral patterns are concerned with communication between objects and responsibility assignments.

- **Chain of Responsibility**: Allows multiple objects to handle a request, passing the request along a chain until an object handles it.
- **Command**: Encapsulates a request as an object, allowing parameterization of clients with queues, requests, and operations.
- **Interpreter**: Defines a grammatical representation for a language and provides an interpreter to interpret sentences in the language.
- **Iterator**: Provides a way to access elements of a collection sequentially without exposing its underlying representation.
- **Mediator**: Defines an object that encapsulates how a set of objects interact, promoting loose coupling by keeping objects from referring to each other explicitly.
- **Memento**: Captures and externalizes an object's internal state, allowing it to be restored later without violating encapsulation.
- **Observer**: Allows a subject to notify its observers about changes without knowing who or what those observers are.
- **State**: Allows an object to alter its behavior when its internal state changes.
- **Strategy**: Defines a family of algorithms, encapsulates each one, and makes them interchangeable.
- **Template Method**: Defines the skeleton of an algorithm in the superclass but lets subclasses override specific steps of the algorithm.
- **Visitor**: Allows you to define new operations on elements of an object structure without changing the classes of the elements.

## 4. **Concurrency Patterns**
Concurrency patterns deal with multi-threading and concurrent execution.

- **Thread Pool**: Manages a pool of worker threads for executing tasks concurrently.
- **Read-Write Lock**: Allows multiple readers or one writer to access a resource, improving concurrency.
- **Producer-Consumer**: Deals with the coordination between two or more threads, with one producing data and the other consuming it.
- **Future**: Allows a result of an operation to be obtained asynchronously, typically through a proxy object.

## 5. **Architectural Patterns**
Architectural patterns deal with the overall structure and design of large systems.

- **Model-View-Controller (MVC)**: Separates the concerns of input (view), business logic (model), and user interface (controller).
- **Layered Architecture**: Divides an application into layers where each layer is responsible for a specific aspect of the application’s functionality.
- **Microservices**: Breaks down a monolithic application into small, independent services that communicate over a network.
- **Event-Driven Architecture (EDA)**: Focuses on the production, detection, consumption, and reaction to events.
