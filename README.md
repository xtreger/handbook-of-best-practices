## Coding Standards

In the Software Development Industry, standardization has a positive impact in every business therefore certain coding
standards are essential for successful software development. They are an array of actions that can be defined for a
particular programming language specifying a programming style, the methods and different procedures that need to be
followed.

A coding standard makes sure that all developers working on a project follow certain guidelines. It is very important
for the programmers to maintain the coding standard, so it can be easily understood and maintained with proper
consistency.

&nbsp;

#### Purpose of Having Coding Standards:

* A coding standard gives a uniform appearance to the code written by various developers.
* It increases the efficiency of developers and promotes robust programming.
* It improves reliability, helps maintain the code and reduce its complexity.
* It reduces code duplication and helps code reuse making it easier to detect errors.

&nbsp;

##### Some of the coding standards are given below:

### 1. Indentation

---
Proper and consistent indentation should be followed throughout the code to increase the readability of the code. For
this, developers should make proper use of whitespaces:

* Between two function arguments there must be a space after a comma.
* Appropriate indentation should be there at the start and the end of each block in the program.
* Nested blocks of code should be properly spaced and indented.
* All braces should start from a new line, and the code that follows the braces should also start on a new line.

```html

<div style=”background-color: blue”> <! –div start–>

    <h2> A heading</h2>

    <p> A paragraph.</p>

</div> <! — div end –>

```

&nbsp;

### 2. Principle of DRY

---

When coding, developers should remember the principle of DRY, which means
**"Don't Repeat Yourself"**. It is a good practice to avoid duplication of code as it can eventually lead to
unmaintainable and buggy systems. Therefore, the code in the application should be such that the same code is not
repeated over and over.

```python
def my_function():
    print("I will not repeat my code!")
    print("I will not repeat my code!")
    print("I will not repeat my code!")
    print("I will not repeat my code!")
    print("I will not repeat my code!")
```

&nbsp;

### 3. Writing Test Cases

---

By writing test cases you will know what your methods do, what they take and what they return. This way you know when
your function should work or when it should fail. Functions should always be based on test cases, not the other way
around.

&nbsp;

### 4. Avoid Commenting on Obvious Things

---

While following the standards, make sure that you do not comment unnecessarily. Too much explanation will make your code
look clumsy. For example:

```java
for(int i=0;i<10;i++) //for loop starts here
        { //starting brace

        // logic starts here

        } //ending brace
```

&nbsp;

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

|References |
|---|
|[Coding Standards and Guidelines](https://www.geeksforgeeks.org/coding-standards-and-guidelines/)|
[Importance of Code Quality and Coding Standard](https://www.multidots.com/importance-of-code-quality-and-coding-standard-in-software-development/)|
|[Coding Standards and Best Practices](https://www.aversan.com/coding-standards-and-best-practices-2/)|
|[Write Better Code with Coding Standards](https://levelup.gitconnected.com/write-better-code-with-coding-standards-546faf3fd4d1)|
