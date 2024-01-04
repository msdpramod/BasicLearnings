
EXCEPTION HANDLING

- An Exception in programming is an event, which occurs during the execution of a program, that disrupts the normal flow of the program's instructions. This can occur for various reasons, such as invalid user input, failure of a physical device, failed network connections, etc.
    In Java, Exceptions are objects that are thrown when an error occurs during the execution of the program. These exceptions can be caught and handled using the try, catch, and finally keywords. If not handled, they can cause the program to terminate unexpectedly.
    
- There are two types of exceptions in Java:
    Checked exceptions: These are exceptional conditions that a well-written application should anticipate and recover from. For example, FileNotFoundException.
    Unchecked exceptions: These are exceptional conditions that are external to the application, and that the application usually cannot anticipate or recover from. For example, NullPointerException.
    Here is a very simple example of how exceptions are used in Java:
   
     ~~~~**
      try {
        // code that may throw an exception
     }
     catch (ExceptionType name) {
        // code to handle the Exception
     }
     finally {
        // code to be executed regardless of whether an exception appears or not
     }

- In the above code, if an exception of ExceptionType occurs in the try block, the catch block will be executed. The finally block is optional and contains all the crucial statements that must be executed whether an exception occurs or not.
Java provides a hierarchy of exception classes, all inheriting from java.lang.Throwable, which allows the programmer to differentiate various types of exceptions.

Here are a few characteristics of unchecked exceptions (like Runtime Exceptions) in Java:
      ` All subclasses of RuntimeException and Error classes are considered as unchecked exceptions. For example, NullPointerException, ArrayIndexOutOfBoundsException, ClassCastException, NumberFormatException, ArithmeticException, etc.
       Unchecked exceptions are not required to be declared in the method signature's throws clause.
       Unchecked exceptions represent problems that result from faults in the code often due to logic errors. For example, if you try to access an element out of an array's bounds, you would get an ArrayIndexOutOfBoundsException.
       Often it makes sense to not catch these exceptions, and let the program fail so the error can be fixed. But if anticipated, they can be caught and handled.
`
    
     Here is an example of a runtime exception:
     public class Main {
         public static void main(String[] args) {
            String text = null;
            System.out.println(text.length()); // This will throw a NullPointerException
         }
    }

Exception Hierarchy

- Uncheck / Runtime Exception
    Unchecked exceptions, also known as Runtime Exceptions, in Java are a type of exception that is not checked at compile-time, but at runtime.
    These exceptions are called "Runtime Exceptions" because they occur during the execution of the program, and not during the compile-time. They are also known as "unchecked exceptions" because the compiler does not check whether these exceptions are being handled or declared in a method.

- Checked / CompileTime Exception
- How to handle the Exception properly (try, catch, finally, throw, throws)
- Creating User-Defined Exception class
- Advantages of Exception Handling
- Disadvantage of Exception Handling