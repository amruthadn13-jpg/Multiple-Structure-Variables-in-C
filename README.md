# Multiple Structure Variables in C

## Overview

This project demonstrates how to create and use **multiple structure variables** in C. Structures help organize related data into a single unit, making programs more readable and maintainable.

The program creates two structure variables, assigns different values to each, and displays their contents.

---

## Concepts Covered

* Structures (`struct`)
* Structure variables
* Multiple instances of a structure
* Member access using the dot (`.`) operator
* Integer and character data types
* Formatted output with `printf()`

---

## Project Description

The program defines a structure named `myStructure` containing:

* An integer member (`myNum`)
* A character member (`myLetter`)

Two structure variables are created:

```text
s1
s2
```

Each variable stores different values, demonstrating how multiple objects can be created from the same structure definition.

---

## Structure Definition

```text
struct myStructure {
    int myNum;
    char myLetter;
};
```

This structure acts as a template for creating multiple structure variables.

---

## Data Stored

### Structure Variable: s1

```text
Number : 13
Letter : B
```

### Structure Variable: s2

```text
Number : 20
Letter : C
```

---

## Sample Output

```text
s1 number: 13
s1 letter: B

s2 number: 20
s2 letter: C
```

---

## Learning Outcomes

* Understanding how structures work in C
* Creating multiple variables from a single structure
* Storing related information efficiently
* Accessing and displaying structure members

---

## Real-World Applications

Structures are widely used in:

* Student Information Systems
* Employee Management Applications
* Banking Systems
* Inventory Management
* Embedded Systems
* Database Record Storage

Multiple structure variables allow programs to manage many records using the same data format.

---

## Time Complexity

```text
O(1)
```

Accessing and displaying structure members takes constant time.

---

## Space Complexity

```text
O(1)
```

A fixed amount of memory is allocated for the structure variables.

---

## Key Takeaway

A structure acts as a blueprint, while structure variables such as `s1` and `s2` are individual instances that can store different data using the same format.

---

## Author

Amrutha D N
