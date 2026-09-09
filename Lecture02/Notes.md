# Abstraction in OOP

## Definition

**Abstraction** in Object-Oriented Programming (OOP) is the process of **hiding implementation details and showing only the essential features** of an object.

Abstraction allows users to interact with an object without knowing how it works internally.

---

## Real-Life Example

When you drive a car:

- You use the steering wheel, accelerator, and brakes.
- You don't need to know how the engine or transmission works internally.

This is **abstraction**—only the necessary functionality is exposed.

---

## How Abstraction is Achieved

### 1. Abstract Classes

- Can have abstract and concrete methods.
- Created using the `abstract` keyword.

### 2. Interfaces

- Define a contract that classes must implement.
- Support complete abstraction (traditionally).

---

## Benefits of Abstraction

- Hides complex implementation details.
- Improves security by exposing only required data.
- Reduces code complexity.
- Makes code easier to maintain and modify.

---

## Conclusion

**Abstraction** means **showing only essential information and hiding unnecessary implementation details**.



# Encapsulation

**Encapsulation** means hiding an object's data and controlling access to it through methods.

---

# 7.1. Two Facets of Encapsulation

## 1. Logical Grouping

* Data (fields) and behaviors (methods) that belong together live in the same **"capsule" (class)**.
* Example: A `Car` class encapsulates `engineOn`, `currentSpeed`, `shiftGear()`, `accelerate()`, etc., in one place.

## 2. Data Security

* Restrict direct external access to sensitive fields to prevent invalid or unsafe operations.
* Example: You can read the car’s odometer but cannot directly set it back to zero.

---

# 7.2. Real-World Analogies

## Medicine Capsule

* The capsule holds both the medicine (data) and its protective shell (access control).
* You swallow the capsule without exposing its contents directly.

## Car Odometer

* You can view the mileage but cannot tamper with it via the dashboard interface.

> **Note:** See the Code section for a full code example.

---

# 7.3. Access Modifiers in C++

## `public`

Members are accessible everywhere.

## `private`

Members are accessible only within the class itself.

## `protected`

Members are accessible in the class and its subclasses (for inheritance scenarios).

---

# 7.4. Getters & Setters with Validation

### Purpose

Allow controlled mutation with checks, rather than exposing fields blindly.

---

# 7.5. Encapsulation Benefits

## 1. Robustness

Prevents accidental or malicious misuse of internal state.

## 2. Maintainability

Internal changes (e.g., adding new constraints) do not ripple into client code.

## 3. Clear Contracts

Clients interact only via well-defined methods (the public API).

## 4. Modularity

Code is organized into self-contained units, easing testing and reuse.

---

# Conclusion

Encapsulation combines **data** and **behavior** into a single unit while protecting the internal state of an object through controlled access mechanisms such as access modifiers, getters, and setters.
