#OOP 
# 213 Final Notes
## Stuff to study:
- Abstract classes
- Interfaces
-Polymorphism
-Inheritance
-Exception Handling, try-catch and finally blocks
- Generic class, Generic object creation
- JFrame
- JavaFX and its methods
- Layout manager
- Coloring Frame, components, and containers
- Menus
- windowListner
- Threads and runnable interface and synchronization
- Inner classes
- Privacy Leak
- Varargs  (variable argument )

### Lesson 6:

An *array* is a data structure used to process a collection of data that is all of the **same type**. It behaves like a numbered list of variables with a uniform naming system. It has a part that  **does not change**: the name, and a part that **does change**: an integer in square bracket.

**Arrays** possess two features: all of its **elements are of the same type** and its elements are **adjacent** in the memory

An array that behaves like a collection of variables can be made using the following (double used here):
```java
double[] score = new double[5];
```

or using two statements:
```java
double[] score;
score = new double[5];
```

Every array has three components:
	- The access modifier
	- The array type
	- The array name 

If an access modifier is not provided, the variable takes the default access modifier. Brackets showing that it is an array can be put before or after the name.
```java
float anArrayOfFloats[]; 

or 

float [] anArrayOfFloats;
```

The second option is preferable as it looks more natural

The **New** operator is used to make new arrays that dont already exist