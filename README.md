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




        
