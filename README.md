Aim : To write a program that demonstrates how various exceptions are caught with catch.

Algorithm:
Step 1: Class Design
 Define a class named ExceptionA which inherits from the built-in class Exception.
 Define ExceptionA class with appropriate onstructors and methods if needed.
 Define a class named ExceptionB which inherits from ExceptionA.
 Define ExceptionB class with appropriate constructors and methods if needed.
Step 2: Creating main()
 Declare variables and objects as needed.
 Use try blocks to encapsulate code sections where exceptions may occur.
Step 3: Within each try block:
 Throw exceptions of types ExceptionA, ExceptionB and IOException.
 For NullPointerException, initialize a null string and calculate the length of the string.
[Trying to access the length method on null string results in an Exception]
Step 4: Use catch blocks to catch exceptions of type Exception.
 Handle each caught exception appropriately within the catch blocks.
