# High-Level and Low-Level Programming Languages

## High-Level Programming Language

### Q. What is a high-level programming language?

**A:** A high-level programming language is a programming language that is close to human language and abstracts most hardware details, making programs easier to write, read, understand, and maintain.

---

### Q. Why are high-level languages easier to use than low-level languages?

**A:** Because they hide hardware complexity, provide readable syntax, and simplify tasks such as memory management and control flow.

---

### Q. What does hardware abstraction mean in high-level languages?

**A:** Hardware abstraction means hiding hardware-specific details so the programmer does not need to interact directly with the CPU, memory, or registers.

---

### Q. Are high-level programming languages portable?

**A:** Yes, high-level languages are generally portable and can run on different platforms with little or no modification.

---

### Q. Why do high-level languages require a compiler or an interpreter?

**A:** Because computers can only execute machine code, high-level programs must be translated into machine instructions.

---

### Q. Give examples of high-level programming languages.

**A:** Python, Java, C++, JavaScript.

---

## Low-Level Programming Language

### Q. What is a low-level programming language?

**A:** A low-level programming language is a language that is close to machine code and provides minimal abstraction from computer hardware.

---

### Q. What are the main types of low-level programming languages?

**A:** Machine language and assembly language.

---

### Q. What is machine language?

**A:** Machine language is a set of binary instructions that are directly executed by the CPU.

---

### Q. What is assembly language?

**A:** Assembly language is a low-level language that uses mnemonic instructions instead of binary and must be translated into machine code by an assembler.

---

### Q. Why are low-level languages harder to write and debug?

**A:** Because they require detailed knowledge of computer architecture and involve complex, hardware-dependent instructions.

---

### Q. What is the main advantage of low-level programming languages?

**A:** They provide fine control over hardware resources and offer high performance and efficiency.

---

### Q. In which domains are low-level languages commonly used?

**A:** System programming, operating systems, device drivers, embedded systems, and performance-critical applications.

---

## Comparison

### Q. How do high-level and low-level languages differ in terms of portability?

**A:** High-level languages are portable across platforms, whereas low-level languages are hardware-dependent.

---

### Q. What is the main difference between high-level and low-level programming languages?

**A:** High-level languages emphasize readability and productivity, while low-level languages emphasize performance and hardware control.

---

# Compilation, Interpretation, and Programming Paradigms

## MTI – Méthodes et Technologies d’Implémentation

## Compilation and Interpretation

### Q. What is compilation?

**A:** Compilation is the process of translating the entire source code of a program into machine code before program execution.

---

### Q. What are the main characteristics of compilation?

**A:**

- Faster execution since the code is fully translated in advance
- Errors are detected before execution

---

### Q. Give examples of compiled languages.

**A:** C, C++, and Java (compiled into bytecode for the Java Virtual Machine).

---

### Q. What is interpretation?

**A:** Interpretation is the process of translating and executing a program line by line during runtime.

---

### Q. What are the main characteristics of interpretation?

**A:**

- Slower execution due to on-the-fly translation
- Easier testing and debugging

---

### Q. Give examples of interpreted languages.

**A:** Python, JavaScript, Ruby.

---

### Q. What is the main difference between compilation and interpretation?

**A:** Compilation translates the entire program before execution, while interpretation translates and executes the program line by line.

---

## Programming Paradigm

### Q. What does the term “paradigm” mean?

**A:** A paradigm is a pattern, model, or blueprint that defines a way of thinking or working.

---

### Q. What is a programming paradigm?

**A:** A programming paradigm is a style or approach that defines how programs are structured and organized.

---

### Q. Why do we use different programming paradigms?

**A:** Because different paradigms are better suited to different types of problems and applications.

---

### Q. Can a programming language support more than one paradigm?

**A:** Yes, many programming languages support multiple paradigms.

---

### Q. What are the two main categories of programming paradigms?

**A:** Imperative programming and declarative programming.

---

## Imperative Programming

### Q. What is imperative programming?

**A:** Imperative programming describes how a program executes by specifying a sequence of commands step by step.

---

### Q. What is the main focus of imperative programming?

**A:** Explicitly defining instructions that modify the program state.

---

### Q. How is imperative programming related to Von Neumann architecture?

**A:** It follows the Von Neumann model, where instructions operate on memory sequentially.

---

## Procedural Programming

### Q. What is procedural programming?

**A:** Procedural programming is an imperative paradigm where programs are organized as sequences of procedures or functions.

---

### Q. How is data represented in procedural programming?

**A:** Data is represented as a collection of state variables.

---

### Q. How is computation defined in procedural programming?

**A:** As a transformation of program state from input to output.

---

### Q. What features extend basic imperative programming in procedural programming?

**A:** Functions, procedures, and subroutines.

---

### Q. Give examples of procedural programming languages.

**A:** BASIC, Fortran, COBOL, C, C++, Pascal, Python.

---

## Object-Oriented Programming (OOP)

### Q. What inspired Object-Oriented Programming?

**A:** The theory of concepts and models of real-world phenomena.

---

### Q. What are the main characteristics of objects in OOP?

**A:** Objects have state (data) and behavior (methods).

---

### Q. What is a class in OOP?

**A:** A class is a blueprint that defines the structure and behavior of objects.

---

### Q. How are data and behavior handled in OOP?

**A:** They are encapsulated within objects.

---

### Q. How do objects interact in OOP?

**A:** Through message passing (method calls).

---

### Q. How is computation defined in OOP?

**A:** As the evolution of objects through interactions and method calls.

---

### Q. Give examples of object-oriented programming languages.

**A:** Java, C++, Python, C#, JavaScript, PHP, Ruby, Smalltalk.

---

## Declarative Programming

### Q. What is declarative programming?

**A:** Declarative programming focuses on describing what the program should achieve rather than how it should execute.

---

### Q. What does declarative programming avoid specifying?

**A:** Control flow and step-by-step execution details.

---

## Functional Programming

### Q. What is functional programming?

**A:** Functional programming is a declarative paradigm inspired by mathematics, where computation is expressed as the evaluation of functions.

---

### Q. How is data treated in functional programming?

**A:** Data is immutable and represented as values.

---

### Q. How is computation defined in functional programming?

**A:** As a function mapping input values to output values.

---

### Q. What is recursion in functional programming?

**A:** A technique where a function calls itself, such as factorial:  
fac(0) = 1, fac(n) = n × fac(n−1).

---

### Q. Give examples of functional programming languages.

**A:** Haskell, Lisp, Common Lisp, OCaml, F#, Matlab, Python, C++.

---

## Logic Programming

### Q. What is logic programming?

**A:** Logic programming expresses computation using facts, relations, and inference rules based on mathematical logic.

---

### Q. How is computation performed in logic programming?

**A:** Through logical inference and systematic search over facts and rules.

---

### Q. How are data represented in logic programming?

**A:** As values and relations.

---

### Q. In which domains is logic programming commonly used?

**A:** Artificial Intelligence, Machine Learning, Natural Language Processing, NoSQL databases, and predictive analysis.

---

### Q. Give examples of logic programming languages.

**A:** Prolog, Datalog, Absys, Cycl, Alice, ALF.

---

## Descriptive (Data-Driven) Programming

### Q. What is descriptive programming?

**A:** A declarative paradigm where program behavior is defined by data rather than explicit procedural steps.

---

### Q. How is descriptive programming used in databases?

**A:** Through DBMS systems that manipulate data using queries instead of procedural code.

---

### Q. What language is most commonly associated with descriptive programming?

**A:** SQL (Structured Query Language).

---

### Q. What operations are typically performed using SQL?

**A:** Creating, reading, updating, and deleting records (CRUD operations).
