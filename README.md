# The Ultimate JAVA CORE Cheatsheet 💻🚀

# Introduction

Welcome to the ultimate Java core cheat sheet! This quick reference guide is designed for both beginners and experienced developers to quickly review essential Java concepts, syntax, and best practices.

### Who is this Cheat Sheet For?

- **Beginners:** New to Java programming? Quickly grasp fundamental concepts and syntax.
  
- **Experienced Developers:** Use it as a handy reference for specific topics or to refresh your memory.


---

**What's Included?**

- **Variables and Data Types:** 
  - **Variables:** **[`Declaration`](#variable-declaration)__,__[`Initialization`](#variable-initialization)__,__[`Naming Conventions`](#naming-conventions)__
  - **Data Types:** **[`Primitive Types`](#primitive-types)__,__[`Reference Types`](#reference-types)**
  
- **Operators:** 
  - **Arithmetic Operators:** **[`+`](#addition)__,__[`-`](#subtraction)__,__[`*`](#multiplication)__,__[`/`](#division)__,__[`%`](#modulus)**
  - **Relational Operators:** **[`==`](#equality)__,__[`!=`](#inequality)__,__[`<`](#less-than)__,__[`>`](#greater-than)__,__[`<=`](#less-than-or-equal-to)__,__[`>=`](#greater-than-or-equal-to)**
  - **Logical Operators:** **[`&&`](#logical-and)__,__[`||`](#logical-or)__,__[`!`](#logical-not)**
  - **Assignment Operators:** **[`=`](#assignment)__,__[`+=`](#addition-assignment)__,__[`-=`](#subtraction-assignment)__,__[`*=`](#multiplication-assignment)__,__[`/=`](#division-assignment)__,__[`%=`](#modulus-assignment)**

- **Control Statements:** 
  - **If-Else Statement:** **[`if`](#if-statement)__,__[`else`](#else-statement)__,__[`else-if`](#else-if-statement)__
  - **Switch Statement:** **[`switch`](#switch-statement)__,__[`case`](#case-statement)__,__[`default`](#default-statement)__
  - **Loops:** **[`for`](#for-loop)__,__[`while`](#while-loop)__,__[`do-while`](#do-while-loop)**

- **Arrays:** 
  - **Declaration:** **[`Array Declaration`](#array-declaration)__
  - **Initialization:** **[`Array Initialization`](#array-initialization)__
  - **Accessing Elements:** **[`Accessing Array Elements`](#accessing-array-elements)__
  - **Multidimensional Arrays:** **[`Multidimensional Arrays`](#multidimensional-arrays)**

- **Methods:** 
  - **Declaration:** **[`Method Declaration`](#method-declaration)__
  - **Arguments:** **[`Method Arguments`](#method-arguments)__
  - **Return Values:** **[`Return Values`](#return-values)__
  - **Overloading:** **[`Method Overloading`](#method-overloading)**

- **Classes and Objects:** 
  - **Class Declaration:** **[`Class Declaration`](#class-declaration)__
  - **Object Instantiation:** **[`Object Instantiation`](#object-instantiation)__
  - **Constructors:** **[`Constructors`](#constructors)__
  - **Instance Variables:** **[`Instance Variables`](#instance-variables)**

- **Inheritance:** 
  - **Extending Classes:** **[`Inheritance`](#inheritance)__
  - **Super Keyword:** **[`Super Keyword`](#super-keyword)__
  - **Method Overriding:** **[`Method Overriding`](#method-overriding)**

- **Polymorphism:** 
  - **Static Polymorphism:** **[`Static Polymorphism`](#static-polymorphism)__
  - **Dynamic Polymorphism:** **[`Dynamic Polymorphism`](#dynamic-polymorphism)**

- **Exception Handling:** 
  - **Try-Catch Block:** **[`Try-Catch Block`](#try-catch-block)__
  - **Throw Statement:** **[`Throw Statement`](#throw-statement)__
  - **Finally Block:** **[`Finally Block`](#finally-block)**

- **Input/Output:** 
  - **Standard Input/Output:** **[`Standard Input/Output`](#standard-input/output)__
  - **File Input/Output:** **[`File Input/Output`](#file-input/output)__
  - **Buffered Input/Output:** **[`Buffered Input/Output`](#buffered-input/output)**

- **Collections Framework:** 
  - **Lists:** **[`Lists`](#lists)__
  - **Sets:** **[`Sets`](#sets)__
  - **Maps:** **[`Maps`](#maps)__
  - **Iterators:** **[`Iterators`](#iterators)**

- **Generics:** 
  - **Generic Classes:** **[`Generic Classes`](#generic-classes)__
  - **Generic Methods:** **[`Generic Methods`](#generic-methods)__
  - **Type Erasure:** **[`Type Erasure`](#type-erasure)**

- **Concurrency:** 
  - **Threads:** **[`Threads`](#threads)__
  - **Synchronization:** **[`Synchronization`](#synchronization)__
  - **Thread Safety:** **[`Thread Safety`](#thread-safety)**

---

---
## What is JAVA?
**Java** serves both as a programming language and a platform, renowned for its high-level, robust, object-oriented, and secure nature.

Initially crafted by Sun Microsystems (now a subsidiary of Oracle) in 1995, Java bears the imprint of James Gosling, hailed as its founding figure. Originally named Oak, the moniker underwent a transformation to Java when it was discovered that Oak was already a registered entity.

---
## Features of JAVA

1. Simplicity
2. Object-Orientation
3. Portability
4. Platform Independence
5. Security
6. Robustness
7. Architecture Neutrality
8. Interpretation Capabilities
9. High Performance
10. Multithreading Support
11. Distributed Computing Capabilities
12. Dynamic

---

## JDK, JRE, and JVM
**JVM(Java Virtual Machine**
- Loads code
- Verifies code
- Executes code
- Provides runtime environment

**JRE(Java Runtime Environment)**
- A set of software tools which are used for developing Java applications.
- It physically exists. 
- It contains a set of libraries + other files that JVM

**JDK(Java Developers Kit)** 
- 


**Variables and Data Types:**
- **Variables:** Containers for storing data values.
  ```java
  int age = 25;
  double salary = 50000.50;
  boolean isStudent = true;
  char grade = 'A';
  String name = "John Doe";
  ```
- **Data Types:** Types of data that can be stored in variables.
  ```java
  int // Integer
  double // Floating-point number
  boolean // Boolean (true/false)
  char // Character
  String // Text/String
  ```
---

**Operators:**
- **Arithmetic Operators:** Perform arithmetic operations.
  ```java
  int sum = 5 + 3;
  double result = 10.5 - 4.2;
  ```
- **Relational Operators:** Compare two values and return a boolean result.
  ```java
  boolean isEqual = (5 == 5);
  boolean isGreater = (10 > 5);
  ```
- **Logical Operators:** Perform logical operations.
  ```java
  boolean result = (true && false);
  boolean result2 = (true || false);
  ```
- **Assignment Operators:** Assign a value to a variable.
  ```java
  int x = 5;
  x += 3; // Equivalent to x = x + 3;
  ```
---

**Control Statements:**
- **If-Else Statement:** Execute code based on a condition.
  ```java
  int age = 18;
  if (age >= 18) {
      System.out.println("You are an adult.");
  } else {
      System.out.println("You are a minor.");
  }
  ```
- **Switch Statement:** Execute one of many blocks of code.
  ```java
  int day = 2;
  switch (day) {
      case 1:
          System.out.println("Sunday");
          break;
      case 2:
          System.out.println("Monday");
          break;
      default:
          System.out.println("Invalid day");
  }
  ```
- **Loops:** Repeatedly execute a block of code.
  They are of 3 types-
  1. for loop
  2. while loop
  3. do-while loop

---
1. **for loop:** 
    - Repeatedly execute a block of code.
    - Used when the number of iteration is **fixed**.
  ```java
  for (int i = 0; i < 5; i++) {
      System.out.println("Hello");
  }
  ```

2. **while loop:**
    - 

---
**Arrays:**
- **Declaration:** Create an array.
  ```java
  int[] numbers = new int[5];
  ```
- **Initialization:** Initialize an array with values.
  ```java
  int[] numbers = {1, 2, 3, 4, 5};
  ```
- **Accessing Elements:** Access elements of an array.
  ```java
  int value = numbers[0];
  ```
- **Multidimensional Arrays:** Arrays of arrays.
  ```java
  int[][] matrix = {{1, 2}, {3, 4}};
  ```

Certainly, let's continue:

---

**Methods:**
- **Declaration:** Define a method.
  ```java
  void greet() {
      System.out.println("Hello, world!");
  }
  ```
- **Arguments:** Pass data to a method.
  ```java
  void greet(String name) {
      System.out.println("Hello, " + name + "!");
  }
  ```
- **Return Values:** Return a value from a method.
  ```java
  int add(int a, int b) {
      return a + b;
  }
  ```
- **Overloading:** Define multiple methods with the same name but different parameters.
  ```java
  int add(int a, int b) {
      return a + b;
  }
  
  double add(double a, double b) {
      return a + b;
  }
  ```
---

**Classes and Objects:**
- **Class Declaration:** Blueprint for objects.
  ```java
  public class Car {
      String color;
      int speed;
      void drive() {
          System.out.println("Driving...");
      }
  }
  ```
- **Object Instantiation:** Create an instance of a class.
  ```java
  Car myCar = new Car();
  ```
- **Constructors:** Initialize object state.
  ```java
  public class Car {
      String color;
      int speed;
      public Car(String color, int speed) {
          this.color = color;
          this.speed = speed;
      }
  }
  ```
- **Instance Variables:** Object-specific variables.
  ```java
  myCar.color = "Red";
  myCar.speed = 60;
  ```
---

**Inheritance:**
- Acquires properties of parent class into child class
- IS-A relationship
- *extends* keyword is used for inheritance

*Types of Inheritance:*
1. single
2. multilevel
3. Hierarchical

- **Extending Classes:** Create a subclass.
  ```java
  public class ElectricCar extends Car {
      int batteryCapacity;
  }
  ```
- **Super Keyword:** Call superclass methods and constructors.
  ```java
  public ElectricCar(String color, int speed, int batteryCapacity) {
      super(color, speed);
      this.batteryCapacity = batteryCapacity;
  }
  ```
- **Method Overriding:** Redefine methods in subclasses.
  ```java
  @Override
  void drive() {
      System.out.println("Driving an electric car...");
  }
  ```


---

**Polymorphism:**
- **Static Polymorphism:** Compile-time polymorphism achieved through method overloading.
  ```java
  int add(int a, int b) {
      return a + b;
  }
  
  double add(double a, double b) {
      return a + b;
  }
  ```
- **Dynamic Polymorphism:** Runtime polymorphism achieved through method overriding.
  ```java
  class Animal {
      void makeSound() {
          System.out.println("Animal makes a sound");
      }
  }
  
  class Dog extends Animal {
      @Override
      void makeSound() {
          System.out.println("Dog barks");
      }
  }
  ```
---

**Exception Handling:**
- **Try-Catch Block:** Handle exceptions gracefully.
  ```java
  try {
      // Code that may throw an exception
  } catch (Exception e) {
      // Handle the exception
  }
  ```
- **Throw Statement:** Throw a custom exception.
  ```java
  if (x < 0) {
      throw new IllegalArgumentException("Value must be positive");
  }
  ```
- **Finally Block:** Execute code regardless of whether an exception occurred.
  ```java
  try {
      // Code that may throw an exception
  } catch (Exception e) {
      // Handle the exception
  } finally {
      // Code that always executes
  }
  ```
---

**Input/Output:**
- **Standard Input/Output:** Read input from the console and write output to the console.
  ```java
  Scanner scanner = new Scanner(System.in);
  int number = scanner.nextInt();
  System.out.println("You entered: " + number);
  ```
- **File Input/Output:** Read from and write to files.
  ```java
  File file = new File("example.txt");
  Scanner scanner = new Scanner(file);
  while (scanner.hasNextLine()) {
      String line = scanner.nextLine();
      System.out.println(line);
  }
  ```
- **Buffered Input/Output:** Improve performance when reading from and writing to files.
  ```java
  BufferedReader reader = new BufferedReader(new FileReader("example.txt"));
  BufferedWriter writer = new BufferedWriter(new FileWriter("output.txt"));
  ```

---

**Collections Framework:**
- **Lists:** Ordered collection of elements.
  ```java
  List<String> names = new ArrayList<>();
  names.add("Alice");
  names.add("Bob");
  ```
- **Sets:** Collection of unique elements.
  ```java
  Set<Integer> numbers = new HashSet<>();
  numbers.add(1);
  numbers.add(2);
  ```
- **Maps:** Key-value pairs.
  ```java
  Map<String, Integer> ages = new HashMap<>();
  ages.put("Alice", 25);
  ages.put("Bob", 30);
  ```
- **Iterators:** Traverse collections.
  ```java
  Iterator<String> iterator = names.iterator();
  while (iterator.hasNext()) {
      String name = iterator.next();
      System.out.println(name);
  }
  ```
  ---

**Generics:**
- **Generic Classes:** Classes that can work with any data type.
  ```java
  public class Box<T> {
      private T value;
      public void setValue(T value) {
          this.value = value;
      }
  }
  ```
- **Generic Methods:** Methods that can work with any data type.
  ```java
  public <T> T getValue(T[] array, int index) {
      return array[index];
  }
  ```
- **Type Erasure:** Compiler removes generic type information during compilation.
  ```java
  public class Box<T> {
      private T value;
  }
  ```
---

**Concurrency:**
- **Threads:** Independent paths of execution.
  ```java
  Thread thread = new Thread(() -> {
      // Code to be executed in a separate thread
  });
  thread.start();
  ```
- **Synchronization:** Control access to shared resources.
  ```java
  synchronized void increment() {
      // Synchronized block
  }
  ```
- **Thread Safety:** Ensuring data consistency in multithreaded environments.
  ```java
  AtomicInteger count = new AtomicInteger(0);
  count.incrementAndGet();
  ```

---







