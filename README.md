### 5. Limited use of globals

---

Code is generally clearer and easier to maintain when it does not use globals. Global variables can be read or modified by any part of the program, making it difficult to identify the reason for every time it is used. Because global variables can be get or set by any part of the program, any rules regarding its use can be easily broken. Also, because globals are available everywhere, you might unknowingly end up using it when you think you are using a local variable (or vice versa).

&nbsp;

### 6. Code Comments and Proper Documentation

---

It is good to comment while writing code as it helps other developers to understand your code. It is good practice to start every method or function with a comment specifying what the method or function does, about its parameters and return values. Also the role of each class and file, their contents and any steps of complex code should be commented. For example, 

```java
/* this function will used to divide two variables */

int Divide()
{

//logic of the function

}
```

&nbsp;

### 7. Proper and Consistent Scheme for Naming

---

The main naming conventions are:

* camelCase: This is where the first letter of each word is capatalised, except for the first word.

* under_score: This is naming by using an underscore between the words.

It is the choice of the developer as to which naming scheme is used in the program, but is very important to maintain the consistency of the naming scheme throughout the code. Conventionally camelCase is used in Java while under_score is used in PHP.

&nbsp;

### 8. Refactoring of code

---

Refactoring means to restructure your existing code to improve its internal structure while maintaining its external behavior. This is done to modernise software, increasing a system's maintainability, enhancing performance and security as well as improving the readability of the code. It is extremely important when performing this procedure to avoid modifying the basic functionality of the code.

&nbsp;

### 9. Write test cases

---

Test cases can be vital to verify the functionality of your code, what it takes in and what it should return. By creating test case you will get an understanding for when a piece of your code should work and when it should fail. A test case includes specific variables or conditions to compare the expected and the actual results of your code. You should implement test cases to cover different levels of complexity for your code, and no two test cases should test the same concept.

&nbsp;

### 10. Length of functions should not be very large

---

Functions should be small enough as to carry out a small amount of work and lengthy functions should be broken down in small ones which complete small tasks. Lengthy functions can be very hard to read and understand. You can measure your functions by counting the number of things it achieves and to keep your functions as small as possible the function should do only one thing. This is important to help keep your functions from becoming overly complex as well as improving the readability of your code. Keep your functions focused on doing one thing and doing it well.

&nbsp;