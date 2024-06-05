# Java
  Java is a popular programming language, created in 1995.
  Java, meticulously designed by James Gosling et al. at Sun Microsystems. 
  It stands as a cornerstone of modern programming languages.
  Its hallmark feature is platform independence, achieved through a revolutionary concept called bytecode. 
    -Java code is first compiled into bytecode, a machine-independent intermediate representation. 
    -This bytecode can then be executed on any platform that has a Java Virtual Machine (JVM).
       -This feature of engineering unlocked a new era of software development. 
         -Developers could now write code once and deploy it across various platforms, drastically improving portability and reducing maintenance overhead. 
         
    -It is used for:
        *Mobile applications (specially Android apps)
        *Desktop applications
        *Web applications
        *Web servers and application servers
        *Games
        *Database connection
    -Why Use Java
      -Java works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc.)
      -It is easy to learn and simple to use
      -It is secure, fast and powerful
      -Java is an object oriented language which gives a clear structure to programs and allows code to be reused, lowering development costs

      -Java Syntax
        -The main Method
          The main() method is required and you will see it in every Java program:
            -public static void main(String[] args)

              -Any code inside the main() method will be executed.
                  -System.out.println()
                    -Inside the main() method, we can use the println() method to print a line of text to the screen:

                    Print Numbers
                      -You can also use the println() method to print numbers.
                          -However, unlike text, we don't put numbers inside double quotes:
                              -System.out.println(50000);


          -Java Variables
              -Variables are containers for storing data values.
              
              -In Java, there are different types of variables, for example:
             
              -String - "Hello".
              -int - stores integers (whole numbers)
              -float -  19.99 or -19.99
              -char - stores single characters, such as 'a' or 'B'. Char values are surrounded by single quotes
              -boolean - stores values with two states: true or false

              -To create a variable, you must specify the type and assign it a value:
                  -String name = "John";

          -Final Variables
            If you don't want others (or yourself) to overwrite existing values, use the final keyword (this will declare the variable as "final" or "constant", which means unchangeable and read-only):
            -example: Final int myNum = 15;

      -Non-Primitive Data Types
              -Non-primitive data types are called reference types because they refer to objects.
              
              -The main difference between primitive and non-primitive data types are:
              
              -Primitive types are predefined (already defined) in Java. Non-primitive types are created by the programmer and is not defined by Java (except for String).
              -Non-primitive types can be used to call methods to perform certain operations, while primitive types cannot.
              -A primitive type has always a value, while non-primitive types can be null.
              -A primitive type starts with a lowercase letter, while non-primitive types starts with an uppercase letter.
              -Examples of non-primitive types are Strings, Arrays, Classes, Interface, etc. You will learn more about these in a later chapter.


      - Java Type Casting
                -Type casting is when you assign a value of one primitive data type to another type.
                
                    -In Java, there are two types of casting:
                            Widening Casting (automatically) - converting a smaller type to a larger type size
                            byte -> short -> char -> int -> long -> float -> double
                            
                            Narrowing Casting (manually) - converting a larger type to a smaller size type
                            double -> float -> long -> int -> char -> short -> byte
                            Widening Casting
                            Widening casting is done automatically when passing a smaller size type to a larger size type:
                            
                            ExampleGet your own Java Server
                            public class Main {
                              public static void main(String[] args) {
                                int myInt = 9;
                                double myDouble = myInt; // Automatic casting: int to double
                            
                                System.out.println(myInt);      // Outputs 9
                                System.out.println(myDouble);   // Outputs 9.0
                              }
                            }
                            
          - Java Strings
              - String Length
                  -the length of a string can be found with the length() method:
                    -tring txt = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
                      System.out.println("The length of the txt string is: " + txt.length());

                      -There are many string methods available, for example toUpperCase() and toLowerCase():

                          -Example
                           -String txt = "Hello World";
                           -System.out.println(txt.toUpperCase());   // Outputs "HELLO WORLD"
                           -System.out.println(txt.toLowerCase());   // Outputs "hello world"


           -Decision Structures in Java
               -Data Structures in Java
                    -Data structures are fundamental building blocks that define how data is organized, stored, and accessed.
                    
                    -Here's a scholarly overview of data structures in Java:

                            
                            Arrays:
                            
                            Fundamental fixed-size collections of elements of the same data type.
                            Efficient for random access 
                            Linked Lists:
                           
                            -LIFO
                            (Last-In-First-Out) data structure, similar to a stack of plates.
                              -Operations: push (add an element to the top), pop (remove the top element), peek (retrieve the top element without removal).
                              Efficient for implementing undo/redo functionality, function call stacks, etc.
                              
                            Queues:
                            
                            FIFO (First-In-First-Out) data structure, similar to a waiting line.
                            Operations: enqueue (add an element to the back), dequeue (remove the front element), peek (retrieve the front element without removal).
                            Useful for processing tasks in a specific order, managing network requests, etc.
                           
                            Trees:

                              Hierarchical data structures with a root node, child nodes, and potentially subtrees.
                              Operations: insertion, deletion, searching, traversal (in-order, pre-order, post-order).
                              Different types of trees exist: including binary search trees (BSTs), balanced trees , and heaps (priority queues).
                              Used for efficient searching, sorting, and representing hierarchical relationships.
                              Hash Tables:
                              
                              
                              If statements
                              
                              
                                  if Statements in Java
                                  Conditional Statements and Control Flow:
                                  
                                  if statements are fundamental control flow structures in Java that allow you to execute code conditionally based on whether a certain condition is true or false.
                                  They enable programs to make decisions and perform different actions depending on the state of the program or user input.
                                 
                                  Basic Syntax:
                              Java
                              int age = 25;
                              if (age >= 18) {
                                System.out.println("You are eligible to vote.");
}


                      -Repetition structures (loops) 
                          -are used similarly to other programming languages. 
                      Java  has three primary types of loops:
                                                            -for
                                                            -while, 
                                                            -do-while loops. 
                                                            
                            -1. For Loop
                            The for loop is used when you know in advance how many times you want to execute a statement or a block of statements.
                            
                                    -Syntax:
                                    
                                            public class Main {
                                              public static void main(String[] args) {
                                                  for (int i = 0; i < 10; i++) {
                                                      System.out.println(i);
                                                  }                                                                 ........
                                              }
                                          }
                            
                            2. While Loop
                            The while loop is used to repeat a block of code as long as a condition is true. If the condition is false initially, the loop may not                               execute at all.
                            
                            Syntax:

                              public class Main {
                                  public static void main(String[] args) {
                                      int i = 0;
                                      while (i < 10) { ..........
                                          System.out.println(i);
                                          i++;
                                      }
                                  }
                              }
                            3. Do-While Loop
                            The do-while loop is similar to the while loop, but it guarantees that the block of code will execute at least once.
                            
                            public class Main {
                                public static void main(String[] args) {
                                    int i = 0;
                                    do {
                                        System.out.println(i);
                                        i++;
                                    } while (i < 10);
                                }
                            }
                            4. Enhanced For Loop (For-Each Loop)
                            The enhanced for loop, also known as the for-each loop, is used to iterate over arrays or collections. It simplifies the syntax and                                  eliminates the need for an index variable.
                            
                           
                                  public class Main {
                                      public static void main(String[] args) {
                                          int[] numbers = {1, 2, 3, 4, 5};
                                          for (int number : numbers) {
                                              System.out.println(number);
                                          }
                                      }
                                  }
Key Points:
For Loop: Best when the number of iterations is known in advance.
While Loop: Useful when the number of iterations is not known and depends on a condition.
Do-While Loop: Ensures the code block runs at least once before checking the condition.
Enhanced For Loop (For-Each): Ideal for iterating over arrays and collections without needing an index.
By using these loops effectively, you can perform repetitive tasks efficiently and keep your code clean and manageable.


        -Methods in Java: Building Blocks of Functionality
          -Methods, also known as functions, are essential elements in Java programming.
              -They encapsulate a set of instructions that perform a specific task, promoting code reusability, modularity, and organization. 
          
          
          Components of a Method:
          Return type: 
            -This specifies the data type of the value the method might return after its execution.
             Common types include void (doesn't return anything), int, double, String, etc.
             
              Method name: A unique identifier that reflects the method's purpose (e.g., calculateArea, displayMessage).
          Parameters (optional)
          Syntax:
                return_type method_name(parameter_list) {
                  // method body (code to be executed)
                }
               
                Java
                public int calculateArea(int length, int width) {
                  int area = length * width;
                  return area; // returning the calculated area
                }
                
                
      -Java Classes and Objects
          -Create an Object
                An object is created from a class. 
                To create an object of Main, specify the class name, followed by the object name, and use the keyword new:
                
            
                Create an object called "myObj" and print the value of x:
                public class Main {
                  int x = 5;
                
                  public static void main(String[] args) {
                    Main myObj = new Main();
                    System.out.println(myObj.x);
                  }
                }
              -Calling a Method:

                  -Once defined, a method can be called from another part of the code using its name followed by parentheses:
                  
                  int myArea = calculateArea(5, 10); // Calling the method, passing arguments
                  System.out.println("Area: " + myArea);


                -Types of Methods:
                        
                        Void methods: 
                          -Don't have a return type and are used to perform actions without returning a value (e.g., displayMessage).
                        Value-returning methods: 
                          -Return a value after execution (e.g., calculateArea).
                        
                        Benefits of Using Methods:
                        Code reusability: Write code once and call it from multiple places in your program.
                        Modularity: Break down complex programs into smaller, manageable units.
                        Improved readability: Self-contained methods enhance code clarity.
                        Maintainability: Easier to modify or debug specific portions of the code.
                        
                        Additional Concepts:
                        Method overloading:
                          -Defining multiple methods with the same name but different parameter lists for handling various input scenarios.
                        Method overriding:
                          -In inheritance, redefining a method in a subclass to provide specialized behavior.
                        Static methods:
                          -Methods associated with the class itself, not requiring a specific object instance to be called.





        
