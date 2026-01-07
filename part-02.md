## General Concepts

### Q. What is Object-Oriented Programming (OOP)?

**A:** Object-Oriented Programming is a programming paradigm that structures software around objects, which represent real-world entities combining state (data) and behavior (methods).

---

### Q. Why is OOP widely used in software engineering?

**A:** Because it improves modularity, reusability, maintainability, scalability, and models real-world systems naturally.

---

### Q. Why are design patterns based on OOP?

**A:** Design patterns rely on OOP principles to provide reusable, flexible solutions to common design problems.

---

### Q. What are the core principles of OOP?

**A:**

- Abstraction
- Encapsulation
- Inheritance
- Polymorphism

---

## Abstraction

### Q. What is abstraction in OOP?

**A:** Abstraction is the process of modeling complex systems by focusing on essential characteristics while hiding implementation details.

---

### Q. What problem does abstraction solve?

**A:** It reduces complexity and separates what an object does from how it does it.

---

### Q. How is abstraction implemented in programming?

**A:** Through abstract classes, interfaces, and base classes.

---

### Q. What is an abstract class?

**A:** A class that cannot be instantiated and may contain abstract (unimplemented) methods.

---

### Q. What is an interface?

**A:** A contract that defines method signatures without implementation, ensuring consistency across different classes.

---

### Q. Give a real-world example of abstraction.

**A:** A `Vehicle` abstraction defines common operations like `move()` without specifying whether the vehicle is a car or a bike.

---

## Encapsulation

### Q. What is encapsulation in OOP?

**A:** Encapsulation is the bundling of data and methods into a single unit (class) while restricting direct access to internal data.

---

### Q. Why is encapsulation important?

**A:** It protects data integrity, enhances security, and reduces system complexity.

---

### Q. What is information hiding?

**A:** Restricting access to internal object details and exposing only necessary interfaces.

---

### Q. What are access modifiers?

**A:** Keywords that control visibility of class members.

---

### Q. What are the common access modifiers?

**A:**

- **Public:** accessible everywhere
- **Protected:** accessible within class and subclasses
- **Private:** accessible only within the class

---

### Q. What is the role of getters and setters?

**A:** To provide controlled access to private attributes.

---

## Inheritance

### Q. What is inheritance?

**A:** Inheritance allows a subclass to reuse and extend the properties and behaviors of a superclass.

---

### Q. What relationship does inheritance represent?

**A:** An **“is-a”** relationship.

---

### Q. What are the advantages of inheritance?

**A:**

- Code reuse
- Reduced duplication
- Logical class hierarchy

---

### Q. What are the risks of excessive inheritance?

**A:** Tight coupling and reduced flexibility.

---

### Q. When should inheritance be avoided?

**A:** When the relationship is not a true "is-a" relationship.

---

## Inheritance vs Composition

### Q. What is composition?

**A:** Composition is a design principle where objects are built using other objects, representing a **“has-a”** relationship.

---

### Q. How does composition differ from inheritance?

**A:**

- Inheritance: is-a relationship
- Composition: has-a relationship

---

### Q. Why is composition often preferred over inheritance?

**A:** Because it provides greater flexibility and lower coupling.

---

## Polymorphism

### Q. What is polymorphism?

**A:** Polymorphism allows objects of different types to be treated uniformly through a common interface.

---

### Q. What are the main types of polymorphism?

**A:**

- Compile-time (method overloading)
- Run-time (method overriding)

---

### Q. What is method overloading?

**A:** Defining multiple methods with the same name but different parameters.

---

### Q. What is method overriding?

**A:** Redefining a superclass method in a subclass.

---

### Q. What is dynamic binding (late binding)?

**A:** The method implementation is selected at runtime based on the object's actual type.

---

### Q. Why is polymorphism important?

**A:** It improves flexibility, extensibility, and reduces code dependencies.

---

## Constructors

### Q. What is a constructor?

**A:** A special method used to initialize objects when they are created.

---

### Q. What is the role of constructors in OOP?

**A:** To ensure objects start in a valid state.

---

### Q. Can constructors be overloaded?

**A:** Yes, many languages support constructor overloading.

---

## OOP Summary

### Q. Summarize the four OOP principles.

**A:**

- **Abstraction:** hides complexity
- **Encapsulation:** protects data
- **Inheritance:** reuses code
- **Polymorphism:** enables flexibility

---

## OOP Glossary

### Q. What is a class?

**A:** A blueprint defining object structure and behavior.

---

### Q. What is an object?

**A:** An instance of a class.

---

### Q. What is an attribute?

**A:** A variable representing object state.

---

### Q. What is a method?

**A:** A function defining object behavior.

---

### Q. What is an instance?

**A:** A concrete object created from a class.

---

### Q. What is behavior?

**A:** The set of actions an object can perform.

---
