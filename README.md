# Inheritance


##  Aim

To implement and understand different types of inheritance in C++.

---

##  Objectives

* To study the concept of inheritance in Object-Oriented Programming (OOP).
* To demonstrate **single, multilevel, hierarchical, and multiple inheritance** through real-life inspired programs.
* To understand how inheritance models "is-a" relationships between entities.

---

##  Theory

###  What is Inheritance?

Inheritance is an OOP feature that allows a **derived (child) class** to acquire the **properties and behaviors** of a **base (parent) class**. It promotes **code reusability**, reduces redundancy, and provides a way to create a natural hierarchy of classes.

###  Key Concepts

* **Base Class (Parent Class):** Provides common attributes and methods.
* **Derived Class (Child Class):** Inherits from the base class and can add its own attributes/methods.
* **Access Specifiers:**

  * `public`: Members accessible outside the class.
  * `protected`: Members accessible only in base and derived classes.
  * `private`: Members not accessible by derived classes directly.

###  Types of Inheritance in C++

1. **Single Inheritance**

   * One base → One derived class.
   * Example: `College → Branch`

2. **Multilevel Inheritance**

   * A chain of inheritance.
   * Example: `Mobile → Origin → Brand`

3. **Hierarchical Inheritance**

   * One base → Multiple derived classes.
   * Example: `Clothes → Jeans, Tops, Sweater`

4. **Multiple Inheritance**

   * One derived class inherits from multiple base classes.
   * Example: `Automobile + Features → Car`

5. **Hybrid Inheritance**

   * Combination of two or more types.
   * May lead to the **Diamond Problem** (resolved using virtual inheritance).

---

##  Advantages of Inheritance

* Encourages **code reuse** and reduces redundancy.
* Makes programs **modular and organized**.
* Allows extension and specialization of base classes.
* Supports **polymorphism and dynamic binding**.
* Models real-world relationships naturally.

##  Limitations

* Increases coupling between base and derived classes.
* **Multiple inheritance** can cause ambiguity.
* **Multilevel inheritance** may become overly complex.
* Misuse of inheritance can make code harder to maintain.

---

##  Comparison of Inheritance Types

| Inheritance Type | Structure                | Example                        | Advantages                         | Limitations                  |
| ---------------- | ------------------------ | ------------------------------ | ---------------------------------- | ---------------------------- |
| **Single**       | One Base → One Derived   | College → Branch               | Simple, reusable                   | Limited reuse                |
| **Multilevel**   | Base → Derived → Derived | Mobile → Origin → Brand        | Stepwise refinement                | Debugging harder             |
| **Hierarchical** | One Base → Many Derived  | Clothes → Jeans, Tops, Sweater | Reuse across many classes          | Risk of duplication          |
| **Multiple**     | Many Base → One Derived  | Automobile + Features → Car    | Combines multiple features         | Ambiguity (Diamond Problem)  |
| **Hybrid**       | Mix of types             | Vehicle + Engine → Car         | Flexible, models complex relations | Complex, debugging difficult |

---

## Program Descriptions

### 1️⃣ Single Inheritance

* **Base class:** `College`
* **Derived class:** `Branch`
* Demonstrates how a child class can extend the functionality of a parent class.

### 2️⃣ Multilevel Inheritance

* **Classes:** `Mobile → Origin → Brand`
* Shows step-by-step refinement of information through multiple levels.

### 3️⃣ Hierarchical Inheritance

* **Base class:** `Clothes`
* **Derived classes:** `Jeans`, `Tops`, `Sweater`
* Demonstrates multiple derived classes sharing a single base.

### 4️⃣ Multiple Inheritance

* **Base classes:** `Automobile`, `Features`
* **Derived class:** `Car`
* Demonstrates combining properties of multiple parent classes.

---

##  Concepts Used

* Classes and Objects (OOP basics)
* Inheritance (`single`, `multilevel`, `hierarchical`, `multiple`)
* Access Specifiers (`public`)
* Function and Data Member usage
* Code Reusability and Extensibility

---

##  Conclusion

* Inheritance promotes **reusability, modularity, and extensibility**.
* **Single inheritance** is simple, while **multilevel** allows gradual refinement.
* **Hierarchical inheritance** demonstrates reuse across multiple classes.
* **Multiple inheritance** allows combining functionalities but can cause ambiguity.
* Careful use of inheritance ensures **clean, reusable, and maintainable code**.

