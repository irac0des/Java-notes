Object-Oriented Programming (OOP) and Procedural Programming (PP) are two distinct paradigms, each with its own principles and methodologies. Here are the main differences:

| Aspect                         | Object-Oriented Programming (OOP)                            | Procedural Programming (PP)                           |
|--------------------------------|------------------------------------------------------------|-----------------------------------------------------|
| **Focus**                      | Focuses on objects that combine data and behavior.         | Focuses on procedures or routines that operate on data. |
| **Data Handling**             | Data is encapsulated within objects; access is through methods. | Data is typically global or passed around as parameters. |
| **Structure**                  | Programs are structured around objects and classes.        | Programs are structured as a sequence of procedures.  |
| **Reusability**                | Promotes reuse through inheritance and polymorphism.       | Reusability is achieved through functions but is limited. |
| **Complexity Management**      | Easier to manage complexity through encapsulation and abstraction. | Complexity is managed through modular procedures, but can become difficult in larger systems. |
| **Example Languages**          | Java, C++, Python, Ruby                                     | C, Pascal, FORTRAN                                   |

### Detailed Explanation of Differences

1. **Focus**:
   - **OOP**: Emphasizes the concept of "objects," which are instances of classes containing both data and methods that manipulate that data. For example, in a class representing a car, attributes like `color` and methods like `drive()` would be included within the same entity.
   - **PP**: Centers around the idea of procedures or routines. The focus is on writing sequences of instructions that manipulate data. For instance, a program might define a series of functions like `initialize()`, `compute()`, and `display()`.

2. **Data Handling**:
   - **OOP**: Data is protected and accessed through specific methods, promoting data hiding. This encapsulation prevents direct access to an object’s data, which can lead to more secure and error-free code.
   - **PP**: Data is often manipulated directly, which can lead to issues such as unintentional modifications and difficulties in maintaining the codebase.

3. **Structure**:
   - **OOP**: Organizes programs into classes and objects, allowing for a more natural way to model real-world entities. Each class can represent a different object type, and objects can interact through method calls.
   - **PP**: Organizes code into procedures that are executed sequentially. Each procedure can take inputs and produce outputs, but the relationship between data and procedures is less structured.

4. **Reusability**:
   - **OOP**: Encourages reusability through inheritance, allowing new classes to derive from existing ones, inheriting their properties and methods. This promotes a hierarchical structure where subclasses can be extended and reused.
   - **PP**: Reusability is achieved through function calls, but it often requires manual duplication of code for similar operations, which can lead to redundancy.

5. **Complexity Management**:
   - **OOP**: Handles complexity more effectively through abstraction. Developers can create high-level interfaces that simplify interactions with complex systems, making it easier to reason about code.
   - **PP**: While procedural programming can manage complexity with modularity, it can become challenging as the size of the program grows, leading to "spaghetti code."

### Examples in Modern Programming Languages

- **OOP Example (Java)**:
  ```java
  public class Car {
      private String color;

      public Car(String color) {
          this.color = color;
      }

      public void drive() {
          System.out.println("The " + color + " car is driving.");
      }
  }

  Car myCar = new Car("red");
  myCar.drive();  // Output: The red car is driving.
  ```

- **PP Example (C)**:
  ```c
  void initialize() {
      // Initialization code
  }

  void compute() {
      // Computation code
  }

  void display() {
      // Display code
  }

  int main() {
      initialize();
      compute();
      display();
      return 0;
  }
  ```

In summary, OOP provides a framework that promotes more organized, maintainable, and scalable code, particularly for large applications, whereas procedural programming can be simpler and more straightforward for smaller, less complex tasks.

[[Inheritance in OOP]]