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


              




        
